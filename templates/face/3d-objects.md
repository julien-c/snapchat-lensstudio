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
  - 3D Objects

# 3D Objects

The 3D Objects Template shows you how to attach 3D objects to a face or
multiple faces. For multiple faces, the 3D objects for each face can be
the same or different. This template also includes a helper script to
play looping animation on the 3D objects.

## Tutorial

## Guide

### Exporting 3D Content

The 3D Objects Template assumes that you have a 3D object which you'll
be importing into Lens Studio. To make your 3D object ready for import
into Lens Studio, follow the [3D Object
Export](https://lensstudio.snapchat.com/guides/3d/3d-object-export)
guide.

### Importing 3D Content

Once your 3D object is exported, follow the [3D Object
Import](https://lensstudio.snapchat.com/guides/3d/3d-object-import)
guide to import your 3D object into Lens Studio.

### Adding the Face Object

After importing, the 3D object will be automatically included in the
`Objects` panel and should also be visible in the `Scene` panel. Drag
your newly imported object to be a child of the `FaceObjectContainer
[EDIT_ME]` object found under `First Head`. This will attached the
object to the first head found in the camera. You can now delete the
template's placeholder content labeled with `[REPLACE_ME]`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/3d_objects_template_add_face_object.gif)

### Tuning the Object's Transform

In the `Scene` panel, you can position, scale, rotate the world object
relative to the head. In the Lens, the face object will automatically be
locked to the face as shown in the `Preview` Panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/3d_objects_template_tune_object_transform.gif)

### Playing an Object’s Animation

You can play animation on 3D objects by using the helper script
`IdleAnim`. To do this, in the `Inspector` panel select ` Add Component
-> Script  `followed by  `Add Script -> Scripts -> IdleAnim`. Set
the `Animation Mixer` property in the `Inspector` panel to your 3D
Object’s `AnimationMixer` component. Next, set the property `Idle Anim
Layer` to the name of your animated object's animation layer. 

Optionally, you can add music by dragging and dropping your mono channel
mp3 into the `Resources` panel and adding it to the `Idle Anim
Audio` field.<span class="underline"></span>

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/3d_objects_template_idle_animation.gif)

### Adding a Second Face Object

To add 3D objects to the second face, repeat the same process as above,
but place it under the `FaceObjectContainer` below the `Second Head`.
The Lens will automatically show and hide the object as needed depending
on the number of heads visible.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/3d_objects_template_second_head.gif)

### Previewing Your Lens

You're now ready to preview your Face Lens experience. To preview your
Lens in Snapchat, follow the [Pairing to
Snapchat](https://lensstudio.snapchat.com/guides/general/pairing-to-snapchat)
guide.

## Script Interface

### IdleAnim.js

  - `Animation Mixer (Component.AnimationMixer)` - A reference to the
    world object's Animation Mixer component
  - ` Idle Anim Layer (string)  ` - The name of the anim layer that
    should be played for the idle animation. The anim layer name is
    configured in your external 3D editor. The anim layer name is also
    listed in the object's Animation Mixer component
  - `Anim Audio (Asset.AudioTrackAsset)` - A reference to an mp3 file.
    If set, the inputted audio will play alongside your animation

## Related Guides

Please refer to the guides below for additional information:

  - [Getting
    Started](https://lensstudio.snapchat.com/guides/getting-started)
  - [3D Object
    Export](https://lensstudio.snapchat.com/guides/3d/3d-object-export)
  - [3D Object
    Import](https://lensstudio.snapchat.com/guides/3d/3d-object-import)
  - [Head Attached 3D
    Objects](/guides/face/face-effects/head-attached-3d-objects)
  - [Pairing to
    Snapchat](https://lensstudio.snapchat.com/guides/general/pairing-to-snapchat)

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
