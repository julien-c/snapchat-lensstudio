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
  - Interactive Path

# Interactive Path

The Interactive Path template is an evolution of the [Interactive Tap
Template](/templates/interactive/interactive-tap)[](/templates/interactive/interactive-tap)
with additional functionality that allows a character to move on the
surface plane. The user is able to draw a path with their finger along
the surface and when complete, the character will move along that drawn
path.

## Tutorial

## Guide

### Exporting 3D Content

The Interactive Path Template assumes that you have a 3D animated object
which you'll be importing into Lens Studio. First you must export your
object to be Lens Studio ready. To do this, follow the [3D Object
Export](/guides/3d/3d-object-export) guide.

The Interactive Path Template optionally needs four layers of animation
in the exported FBX. To learn more about how to prepare multiple
animation layers, follow the [Maya
Export](/guides/3d/3d-software/maya-3d-object-export) guide. If your 3D
tool does not support animation layers, you can create Animation Clips
inside Lens Studio. Follow the Playing 3D Animation guide's [Animation
Clip](/guides/scripting/playing-3d-animation#animation-clips) section
for information on how to create Animation Clips.  

### Importing 3D Content

Once you have your 3D object exported, follow the [3D Object
Import](/guides/3d/3d-object-import) guide to import your 3D object into
Lens Studio.

### Linking the World Object

After importing, the 3D object will be automatically included in
the `Objects` panel and should also be visible in the `Scene` panel.
Next, you'll want to drag your newly imported object to be a child of
the `WorldObjectController` object. You can now delete the template's
placeholder object labeled with `[REPLACE_ME]`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/path_template_parent.gif)

### Linking the Animation

Next, we need to link the imported object's `AnimationMixer` component
to the `IdleAnim` script. Select the `WorldObjectController` object and
open the `Inspector` panel. Find the `IdleAnim` script and link
the `Animation Mixer` field to your model's animation mixer.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/path_anim_mixer.gif)

### Setting the Animation Names

When using multiple animations in a single FBX, they will be imported
into Lens Studio as `Animation Layers`. If all of the animations are on
one single timeline you can cut them into clips using the Animation
Mixer's Clips tool. These clips will be treated as Layers. You can find
more information regarding animation clips in our [Playing 3D
animation](/guides/scripting/playing-3d-animation) guide.  

These layers can be used to define the additional animations that will
play on interaction. For the Interactive Path Template we can use up to
four animations to expand on the behavior of found in the Interactive
Tap Template. First, set the `Idle Anim Layer` field to the layer name
of your looping idle animation. Then, set the `Tap Anim Layer` field to
the layer name of your tap animation which will play when the object is
tapped. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/path_template_anims_1.gif)

Next locate the `Follow Path Anim` script object and set the `Path Anim
Layer` field to the layer name of the animation you'd like to use while
the character moves along the path. This should be a looping
animation. Do the same for the `Arrive Anim Layer` field by entering
the name of the animation you'd like to use when the character reaches
the end of the path.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/path_template_anims_2.gif)

### The Layout

The object layout for the Interactive Path Template has a similar layout
to the [Interactive Tap
Template](/templates/interactive/interactive-tap)[](/templates/interactive/interactive-tap)
with a few additional objects. The Idle animation and the Tap animation
are still controlled as you would expect from the Tap Template which can
be found on the **WorldObjectController**.

**Note**  
Please make sure you're familiar with the Interactive Tap Template if
you have trouble understanding the Tap and Idle functionality of this
template

  - **Drawing Object** - This object is used to draw the path for the
    character to follow. This object should not be edited
  - **Finger Tracker** - This is an invisible object for tracking the
    users finger as they draw the path and helps to determine the
    direction of the drawn path. This object should not be edited
  - **FollowPathAnim** - This object contains the script for all of the
    path following logic

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/layout.png)

### Follow Path Anim Script

The FollowPathAnim.js script handles the movement of the character along
the path. It also draws a visual representation of the path.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/script.png)

**Path Animation Settings**

  - `Idle Anim Script (ScriptComponent)` - This value is a reference to
    the WorldObjectController SceneObject that contains an instance of
    IdleAnim.js and is recommended not to be adjusted unless necessary 
  - `Path Anim Layer (string)` - The name of the animation clip or layer
    that the object will play when moving along the path
  - `Arrival Anim Layer (string)` - The name of the animation clip or
    layer that the object will play when moving along the path

**Path Move Settings**

  - `Drawing Object (MeshVisual)` - A reference to the mesh that will be
    used to draw the path the object will move along
  - `Drawing Curve Mat (Material)` - This is the material that will be
    applied to the Drawing Object while a user is actively drawing the
    path
  - `Final Curve Mat (Material)` - This is the material that will be
    applied to the Drawing Object when the path is complete and the
    object is moving along that path
  - ` Follow Object (SceneObject)  `- This is the object that will move
    along the path and should be the WorldObjectController SceneObject
  - `Tracker Object (SceneObject)` - This is an invisible object that is
    tracked to the users finger and helps derive position and
    orientation of stroke along path
  - `Move Speed (float)` - This is how fast the object will move along
    the path
  - `Follow Audio (AudioTrackAsset)` **- ** A reference to an Audio
    Track Asset in resources. This is a looping sound that plays while
    the character or object is moving along the path
  - `Arrive Audio (AudioTrackAsset)` **- **A reference to an Audio Track
    Asset in resources. This is a non-looping sound that plays when the
    character or object reaches the end of the path
  - `Path Draw Audio (AudioTrackAsset)` **- **A reference to an Audio
    Track Asset in resources. This is a non-looping sound that plays
    each time a drawing arrow is placed on the surface by the users
    finger

### Materials

The materials for this template come with a few notes regarding how you
should interact with them

  - ` Arrow Material (Material)  `- This material should only have it's
    texture references edited and an attempt to adjust other parameters
    may present an undesired look
  - `Arrow Draw Material (Material)` - This material is applied to the
    final look of the path once it's complete and should only have its
    texture references updated as well

If you want to change the look of the `arrow_draw` material then you
will only update the Opacity Texture witch acts as a mask of what you
would like the outline of your texture to look like. You can also update
the base color.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/path_template_arrow.png)

For the `arrow_draw` material the Base Texture will scroll along the
"up" direction of the the material. The Opacity Texture will mask out
the color of the material.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/path_template_arrow_draw_texture.png)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/arrow_mat.gif)

Audio

You can add audio to your animation by importing an audio file into the
`Resources` panel and referencing it in the IdleAnim.js, TapAnim.js and
FollowPathAnim.js scripts (found on the WorldObjectController object and
the FollowPathAnim object). We recommend using a mono channel mp3 to
keep the lens size low. For more information on Audio, see the [Audio
guide](/guides/audio).

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/path_audio_1.png)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/path_audio_3.png)

## Related Guides

Please refer to the guides below for additional information:

  - [Getting Started](/guides/getting-started)
  - [3D Object Export](/guides/3d/3d-object-export)
  - [3D Object Import](/guides/3d/3d-object-import)
  - [Playing 3D Animation](/guides/general/pairing-to-snapchat)
  - [Pairing to Snapchat](/guides/general/pairing-to-snapchat)
  - [Scripting Overview](/guides/scripting/scripting-overview)
  - [Interactive Tap Template](/templates/interactive/interactive-tap)

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

Hi\! We use cookies, including third-party cookies, on this website to
help operate our site and for analytics and advertising purposes. For
more on how we use cookies and your cookie choices, go
[here](https://snap.com/cookie-policy/) for our cookie policy\! By
clicking below, you are giving us consent to use cookies. You can change
your cookie settings by clicking on "More information" below.

I Accept

[More Information](https://www.snapchat.com/cookie-settings)
