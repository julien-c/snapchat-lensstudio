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
  - [Interactive](/templates/interactive)
  - Interactive Look At

# Interactive Look At

Building off of the [Animated Object
Template](/templates/world/animated-object), the Interactive Look At
Template allows you to add 3D animated content to the world. When the
user looks at the object, it plays an additional animation. The template
gives you access to manipulation control which allows the user to move,
scale and rotate the object.

## Tutorial

## Guide

### Exporting 3D Content

The Interactive Look At Template assumes that you have a 3D animated
object which you'll be importing into Lens Studio. First you must export
your object to be Lens Studio ready. To do this, follow the [3D Object
Export](/guides/3d/3d-object-export) guide.

**Warning**  
The Interactive Look At Template needs two layers of animation in the
exported FBX. To learn more about how to prepare multiple animation
layers, follow the [Maya
Export](/guides/3d/3d-software/maya-3d-object-export) guide. If your 3D
tool does not support animation layers, you can create Animation Clips
inside Lens Studio. Follow the Playing 3D Animation guide's [Animation
Clip](/guides/scripting/playing-3d-animation#animation-clips) section
for information on how to create Animation Clips. 

### Importing 3D Content

Once you have your 3D object exported, follow the [3D Object
Import](/guides/3d/3d-object-import) guide to import your 3D object into
Lens Studio.

### Linking the World Object

After importing, the 3D object will be automatically included in the
`Objects` panel and should also be visible in the `Scene` panel. Next,
you'll want to drag your newly imported object to be a child of the
`WorldObjectController` object. You can now delete the template's
placeholder object labeled with `[REPLACE_ME]`.

![Interactive Look At
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/interactive_look_at_template_object_setup.gif)

### Linking the Animation

Next, we need to link the imported object's `AnimationMixer` component
to the `IdleAnim` script. Select the `WorldObjectController` object and
open the `Inspector` panel. Find the `IdleAnim` script and link the
`Animation Mixer` field to your model's animation mixer.

![Interactive Look At
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/interactive_look_at_template_anim_mixer_set.gif)

### Setting the Animation Names

When using multiple animations in a single FBX, they will be imported
into Lens Studio as `Animation Layers`. These layers can be used to
define the additional animations that will play on interaction. For the
Interactive Look At Template, set the `Idle Anim Layer` field to the
layer name of your looping idle animation. Then, set the `Look At Anim
Layer` field to the layer name of your look at animation which will play
when the object is looked at.

![Interactive Look At
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/interactive_look_at_template_set_anim_names.gif)

### Tuning the Collision

The `TouchCollision` object represents the area the user must touch to
manipulate (scale, move and rotate) the object. In the `Objects` panel,
select the `TouchCollision` object and scale it to roughly match the
size of your 3D object.

![Interactive Look At
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/interactive_look_at_template_tune_collision.gif)

### Adding the Shadow

If you want to add a real-time shadow to your experience, first select
your 3D object in the `Objects` panel. Find the object(s) with the `Mesh
Visual` component. In the `Inspector` panel, set the `Shadow Mode` drop
down to `Caster`. Here, you're also able to tune the shadow's intensity
via the `Shadow Density` slider.

### Audio

You can add audio to your animation by importing an audio file into the
`Resources` panel and referencing it in the IdleAnim.js and
LookatAnim.js scripts (found on the WorldObjectController object). We
recommend using a mono channel mp3 to keep the lens size low. For more
information on Audio, see the [Audio guide](/guides/audio).

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/lookat_audio.png)

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

### LookAtAnim.js

  - `Look At Anim Layer (string)` - The name of the anim layer that
    should be played when a user looks at the object within a specified
    angle. The anim layer name is configured in your external 3D editor.
    The anim layer name is also listed in the object's Animation Mixer
    component

  - `Trigger Angle (float)` - This value defines the angle in which a
    user must look at the object to trigger the look at animation. The
    object will return the to idle animation when the user looks away

  - `Camera Object (SceneObject)` - This is a reference to the active
    camera in the scene. It's used to calculate the viewing angle from
    the user to the animated object

  - `Look At Target (SceneObject)` - This is an optional field. This
    represents center point of the object and is used to when
    calculating the look at angle. If not set, the WorldObjectController
    object's position is used

  - `Look At Anim Audio (Asset.AudioTrackAsset)` - A reference to an
    Audio Track Asset in your resources. If set, the inputted audio will
    play alongside your animation when the object is looked at

## Related Guides

Please refer to the guides below for additional information:

  - [Getting Started](/guides/getting-started)
  - [3D Object Export](/guides/3d/3d-object-export)
  - [3D Object Import](/guides/3d/3d-object-import)
  - [Pairing to Snapchat](/guides/general/pairing-to-snapchat)
  - [Scripting Overview](/guides/scripting/scripting-overview)

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
