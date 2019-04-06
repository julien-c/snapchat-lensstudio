# [Lens Studio](/)

  - [Lens Studio](/)
  - [Snap Camera](/snap-camera)
  - [Creators](/creators)
  - [Lenses](/lenses)
  - [News](/news)
  - [Reference](#)
      - [Templates](/templates)
      - [Guides](/guides)
      - [API](/api)
      - [FAQ](/support)
      - [Forum](https://support.lensstudio.com/hc/en-us/community/topics)

[Download](/download)

[](#) [](#)

This site requires JavaScript to be enabled for proper functionality.

  - Face
      - [Paper Head](/templates/face/paper-head)
      - [Sunglasses](/templates/face/sunglasses)
      - [Segmentation](/templates/face/segmentation)
      - [Team Celebrate](/templates/face/team-celebrate)
      - [Face in Picture](/templates/face/face-in-picture)
      - [2D Objects](/templates/face/2d-objects)
      - [Distort](/templates/face/distort)
      - [Face Paint](/templates/face/face-paint)
      - [Photo](/templates/face/photo)
      - [Baseball Cap](/templates/face/baseball-cap)
      - [3D Objects](/templates/face/3d-objects)
      - [Trigger](/templates/face/trigger)
      - [Cricket Helmet](/templates/face/cricket-helmet)
  - World
      - [Cutout](/templates/world/cutout)
      - [Face Image Picker](/templates/world/face-image-picker)
      - [Static Object](/templates/world/static-object)
      - [Animated Object](/templates/world/animated-object)
      - [Particles](/templates/world/particles)
      - [Portal](/templates/world/portal)
      - [Picture Frame](/templates/world/picture-frame)
      - [Look Around](/templates/world/look-around)
      - [Window](/templates/world/window)
  - Interactive
      - [Simple High Score](/templates/interactive/simple-high-score)
      - [High Score](/templates/interactive/high-score)
      - [Soundboard](/templates/interactive/soundboard)
      - [Fullscreen](/templates/interactive/fullscreen)
      - [Interactive Tap](/templates/interactive/interactive-tap)
      - [Interactive Path](/templates/interactive/interactive-path)
      - [Interactive
        Approach](/templates/interactive/interactive-approach)
      - [Interactive Look
        At](/templates/interactive/interactive-look-at)
  - Marker
      - [Marker](/templates/marker/marker)
      - [Marker with Snapcode](/templates/marker/marker-with-snapcode)
  - Object
      - [Pet](/templates/object/pet)
      - [Hand](/templates/object/hand)
      - [Body](/templates/object/body)
  - [Landmarker (Beta)](/templates/landmarker)
  - [Beginner Templates](/templates/beginner-templates)

<!-- end list -->

  - [Templates](/templates)
  - [World](/templates/world)
  - Look Around

# Look Around

The Look Around Template allows you to add 3D content all around the
user. It uses the gyroscope to lock objects in the scene, allowing the
user to look around and see different content.

## Tutorial

## Guide

### Exporting 3D Content

The Look Around Template assumes that you have a 3D object (optionally
animated) which you'll be importing into Lens Studio. First you must
export your object to be Lens Studio ready. To do this, follow the [3D
Object Export](/guides/3d/3d-object-export) guide.

### Importing 3D Content

Once you have your 3D object exported, follow the [3D Object
Import](/guides/3d/3d-object-import) guide to import your 3D object into
Lens Studio.

### Adding the World Object

After importing, the 3D object will be automatically included in the
`Objects` panel and should also be visible in the `Scene` panel. Next,
you'll want to drag your newly imported object to be a child of the
`WorldObjectParent` object. You can now delete the template's
placeholder objects labeled with `[REPLACE_ME]`.

![Look Around
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/look_around_template_add_asset.gif)

### Linking the Animation

If your object has an animation, we can play it by using the `IdleAnim`
script. To do this, select your imported object and open the `Inspector`
panel. Add a `Script` component and add the `IdleAnim` script bound to
the `Initialized` event.

Next, we need to link the imported object's `AnimationMixer` component
to the `IdleAnim` script. Find the `Animation Mixer` field and link it
to your model's animation mixer. Additionally, set the `Idle Anim Layer`
field to whatever you named your animation's anim layer.

![Look Around
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/look_around_template_add_script.gif)

### Tuning the Object's Transform

You can position, scale, rotate the world object relative to the
`Camera` object and it will be locked to that position relative to the
user.

![Look Around
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/look_around_template_tuning.gif)

### Making the Object Face the User

Sometimes you may want the world object to always face the user. To do
this, add a `Look At` component to your object in the `Inspector` panel.
Link your scene's `Camera` object to the `Target` field. Set the `Aim
Vector` to `Z aim, Y up`. Your object will now always face the camera
and the user.

![Look Around
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/look_around_template_look_at.gif)

### Adding More Objects

You can add more world objects by repeating the step above to surround
users with content.

**Tip**  
You can press `Command+D` or `Ctrl+D` to duplicate objects.

![Look Around
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/look_around_template_duplicate.gif)

### 

### Audio

You can add audio to your animation by importing an audio file into the
`Resources` panel and referencing it in the IdleAnim.js script (found on
the ChickFBX \[REPLACE\_ME\] objects). We recommend using a mono channel
mp3 to keep the lens size low. For more information on Audio, see
the [Audio guide](/guides/audio).

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/lookaround_audio.png)

### Previewing Your Lens

You're now ready to preview your world Lens experience. To preview your
Lens in Snapchat, follow the [Pairing to
Snapchat](/guides/general/pairing-to-snapchat) guide.

## Script Interface

### WorldObjectController.js

  - `Use Ground Grid (bool)` - When enabled, a circular grid will appear
    underneath the world object when the user touches the object. This
    grid helps visualize the surface the content is attached to. Setting
    to false will disable the ground grid visualization

  - `Touch Collision Material (Asset.Material)` - The material used by
    the touch collision mesh. In Lens Studio's scene panel, the mesh is
    visualized with a semi transparent material. When running in Lens,
    this material is made invisible

  - `Ground Grid (SceneObject)` - A reference to the ground grid object

### IdleAnim.js

  - `Animation Mixer (Component.AnimationMixer)` - A reference to the
    world object's Animation Mixer component

  - `Idle Anim Layer (string)` - The name of the anim layer that should
    be played for the idle animation. The anim layer name is configured
    in your external 3D editor. The anim layer name is also listed in
    the object's Animation Mixer component

  - `Anim Audio (Asset.AudioTrackAsset)` - A reference to an Audio Track
    Asset in your resources. If set, the inputted audio will play
    alongside your animation

## Related Guides

Please refer to the guides below for additional information:

  - [Getting Started](/guides/getting-started)
  - [3D Object Export](/guides/3d/3d-object-export)
  - [3D Object Import](/guides/3d/3d-object-import)
  - [Pairing to Snapchat](/guides/general/pairing-to-snapchat)
  - [Scripting Overview](/guides/scripting/scripting-overview)
  - [Tracking Modes](/guides/general/tracking/tracking-modes)
  - [Look At Component](/api/classes/LookAtComponent)

Still Looking for help?

[Visit Support](/support)

Company

[Snap Inc.](https://www.snap.com/) [Jobs](https://www.snap.com/jobs/)
[News](https://www.snap.com/news/)

Community

[Support](https://support.snapchat.com/) [Community
Guidelines](https://support.snapchat.com/a/guidelines) [Safety
Center](https://www.snapchat.com/safety)

Advertising

[Buy Ads](https://www.snapchat.com/ads) [Advertising
Policies](https://www.snap.com/ad-policies/) [Brand
Guidelines](https://www.snap.com/brand-guidelines/) [Promotions
Rules](https://support.snapchat.com/a/promotions-rules)

Legal

[Privacy Center](https://www.snap.com/privacy/privacy-center/) [Cookie
Policy](https://www.snap.com/cookie-policy/)
[Copyright](https://support.snapchat.com/co/report-copyright) [Custom
Creative Tool
Terms](https://www.snap.com/en-US/terms/custom-creative-tools/)
[Community Geofilter Terms](https://www.snapchat.com/create/terms.html)
[Lens Studio Terms](https://www.snap.com/terms/lens-studio-terms/)

[Privacy Policy](https://www.snap.com/privacy/privacy-policy/) [Terms of
Service](https://www.snap.com/terms/)

Hi\! We use cookies on this website to help operate our site and for
analytics and advertising purposes. For more on how we use cookies and
your cookie choices, go [here](https://www.snap.com/cookie-policy/)\! By
continuing to use our services, you are giving us your consent to use
cookies.
