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
  - [Face](/templates/face)
  - Trigger

# Trigger

The Trigger Template provides a base for creating Face Lenses that react
to user events, including Face Events like Mouth Open and Brows Raised,
as well as Touch Events. It provides helpers for using touch or face
triggers to activate 3D and 2D animation and sound. Additionally, it can
display different hints based on the opened camera.

## Tutorial

## Guide

### Exporting 3D Content

The Trigger Template assumes that you have a 3D object which you'll be
importing into Lens Studio. To make your 3D object ready for import into
Lens Studio, follow the [3D Object
Export](https://lensstudio.snapchat.com/guides/3d/3d-object-export)
guide.

### Importing 3D Content

Once your 3D object is exported, follow the [3D Object
Import](https://lensstudio.snapchat.com/guides/3d/3d-object-import)
guide to import your 3D object into Lens Studio.

### Importing 2D Content

Once you your 2D content is exported, you can add it as a texture to
Lens Studio by dragging and dropping the image(s) into your `Resources`
panel.

**Tip**  
You can import animated content by following the [2D
Animation](https://lensstudio.snapchat.com/guides/2d/2d-animation) guide
on adding animated images.  

### Importing Sounds

Similarly, you can add sounds (mono channel MP3 is recommended) to Lens
Studio by dragging and dropping the sounds(s) into your `Resources`
panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-trigger-template-8.gif)

### Attaching 3D Object to Face

Now that your content has been imported, you can start to put your lens
together. First, drag your 3D object under the Head object which will
attach your object to the user’s face. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-trigger-template-3.gif)

We can use the `Scene` panel to position your 3D object correctly on the
face. For more information on attaching a 3D object to your face, follow
the [Head Attached 3D
Objects](/guides/face/face-effects/head-attached-3d-objects) guide. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/trigger_attach_3d_object_to_face.gif)

### Adding Screen Image

We can additionally add 2D textures to the screen by using a Screen
Image to add more layers to your Lens. This is useful for adding things
like branding, and other effects (such as a vignette). In your `Objects`
panel: `Add New -> Screen Image`. You can use the `Scene` panel to move
your Screen Image to the correct location. You can learn more about the
Screen Image in the [Image](/guides/2d/image) guide. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/trigger_add_2d_billboard.gif)

### Triggering a 3D Animation

If you have an animation that you want to be played on some action, in
the `Inspector` panel of the `Head` object, drag
the `FaceTriggerAnim` Script from the `Resources` panel to the
`Inspector` panel. You can select which event will trigger your
animation. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/trigger_add_3d_animation_trigger.gif)

### Adding a Second Trigger

You can create multiple triggers in your lens by adding multiple
`FaceTriggerAnim` Script to the `Head` object as above. You can specify
actions other than playing 3D animation, such as playing 2D animation or
sound.

For example, if you have a 2D animated texture on a Screen Image, under
the ` 2D Anim Control  ` section, you can press `Add Value` and select
your Screen Image in the pop-up. Similarly, if you want to play music,
under `Sound Control`, you can press `Add Value` and select your
music from the pop-up. More information about each field can be found
at the bottom of this guide. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/trigger_add_2d_animation_trigger.gif)

### Adding a Second Face Effects

You can have your effects and trigger work with a second face as well.
To do this, start by duplicating the `Head [EDIT_ME]` object by `Right
Clicking -> Duplicate`. Then, in the duplicated Head object, in the
`Inspector` panel, under the `Head Binding` component, increment the
`Face Index` field by 1. This will bind your new glasses to the second
face (the first face is 0, and the second face is 1, and so forth). 

Then, in the same object, under your `FaceTriggerAnim` Script component,
set its `Face Index` field to 1 to match--this way a mouth opened event
on the second face, will trigger the animation on the second
face. Finally, like when setting up the first face effect, link up your
duplicated animated 3D/2D objects and sounds underneath. For example,
under `3D Anim Control`, for the `Animation Mixer` field, make sure to
select the Animation object (Sunglasses \[REPLACE\_ME\]) under the
**duplicated** head.  

You can learn more about creating effects for a second face in the
guide: [Working with Multiple
Faces](/guides/face/working-with-multiple-faces) 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/trigger-add-second.gif)

### Adding Hints

You can also have the Lens display different hints based on a trigger.
This is useful if you need different hints when the front camera is
opened vs the back camera. To do this, select the `Lens Hint` object in
the `Objects` panel and in it’s `Inspector` panel, drag the `ShowHint`
Script from the `Resources` panel to the `Inspector` Panel. Then in the
script event drop down choose the event which should trigger this hint.
Then, you can choose which hint you want to show in the `Hint Id` drop
down, as well as configure how your hint is shown. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/trigger_add_hints.gif)

**Note**  
Hints are only shown on device. To see your hint, preview your Lens in
Snapchat. 

## Previewing Your Lens

You're now ready to preview your Face Lens experience. To preview your
Lens in Snapchat, follow the [Pairing to
Snapchat](https://lensstudio.snapchat.com/guides/general/pairing-to-snapchat)
guide.

## Script Interface

### FaceTriggerAnim.js

  - `Animation Trigger (Event)` - An event type that will play 3D
    animation, 2D animation and sound
  - `Face Index (int)` - The face which this trigger will reference. The
    first face is 0, the second face is 1, and so forth
  - 3D Anim Control
      - `Animation Mixer (Component.AnimationMixer)` - The animation
        component which contains the animation you want to play
      - `Layer Name (string)` - The name of the animation layer you want
        to play when the animation trigger occurs
      - `Play Count (number)` - How many times the animation should be
        played. -1 will loop the animation forever

<!-- end list -->

  - 2D Anim Control
      - `Play Animations (Component.SpriteVisual[])` - The BaseTex
        attached to these SpriteVisuals will be played based on the
        options below
      - `Play Count (number)` - How many times the sprites should be
        played when the animation trigger occurs. -1 will loop the
        animation forever
      - `Play Offset (number)` - The sprites play offset in seconds

<!-- end list -->

  - Sound Control
      - `Play Sounds (Asset.AudioTrackAsset[])` - The AudioTrackAsset
        attached from the `Resource` panel will automatically be given
        an AudioComponent accessible by any state and will be played
        when we enter the state
      - `Play Count (number)` - How many times to play the sound when
        the animation trigger occurs. -1 will loop the sound forever
      - `Trigger Disable Time` - Time in seconds before this event can
        be triggered again

### ShowHint.js

  - `Hint Id` - The hint which will be shown before fading out
  - `Show Time (number)` - Number of seconds hint should be shown before
    fading out
  - ` Delay Time (number)  ` - Number of seconds to wait before hint is
    shown
  - `Show Once (bool)` - Whether this hint should be only be shown once
    or every time the script event is triggered

## Related Guides

Please refer to the guides below for additional information:

  - [3D Object
    Export](https://lensstudio.snapchat.com/guides/3d/3d-object-export)
  - [3D Object
    Import](https://lensstudio.snapchat.com/guides/3d/3d-object-import)
  - [Screen Image](/guides/2d/image)
  - [2D
    Animation](https://lensstudio.snapchat.com/guides/2d/2d-animation)
  - [Head Attached 3D
    Objects](/guides/face/face-effects/head-attached-3d-objects)
  - [Pairing to
    Snapchat](https://lensstudio.snapchat.com/guides/general/pairing-to-snapchat)
  - [Working with Multiple
    Faces](/guides/face/working-with-multiple-faces)

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
