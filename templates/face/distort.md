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
  - Distort

# Distort

The Distort Template provides a base for creating Face Lenses that
stretch, liquify, and duplicate your facial features. The Distort
Template allows you to create a compelling Face Lens without importing
any additional resources. The template contains a few preconfigured
effects which you can edit or delete.  This guide covers how to modify
the template’s effects, as well as how to add more.  

## Tutorial

## Guide

### Editing the Face Liquify Effect

The Face Liquify Effect can bulge and pucker any region of the face. The
Distort Template includes two Face Liquify Points, attached to the eyes.
You can find them in the `Objects` panel under the `Distortion Effects`
object.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/distort_object_show_face_liquify.png)

Select one of the `Liquify Points` to modify it. In the
`Scene` panel, you can change the position of the Face Liquify Effect
by dragging the blue circle.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/distort_position_liquify_points.gif)

You can adjust the radius and intensity of the Face Liquify effect
by setting the values under the 2D editor. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/distort_position_adjust_radius_intensity_liquify_points.gif)

### Adding a Face Liquify Effect

To add a new Face Liquify Effect, select `Add New -> Face Effects ->
Face Liquify` in the `Objects` Panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img_new/face_distort_liquify_add.gif)

### Editing The Face Stretch Effect

The Face Stretch Effect distorts the shape of the face by manipulating
points mapped to the face. The Face Distort Template includes a Face
Stretch Effect, used to shrink the head and round out the overall shape
of the face. You can find it in the `Objects` panel under the
` Distortion Effects  `object.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/distort_object_show_face_stretch.png)

Select the `Face Stretch` object to modify it. In the `Scene` panel, you
can drag the Face Stretch points to change the shape of the face.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/distort_position_face_stretch_adjust.gif)

You can change the strength of the Face Stretch Effect by adjusting the
Face Stretch Component’s `Feature` slider in the `Inspector` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/distort_position_face_stretch_intensity.gif)

### Adding a Face Stretch Effect

To add a new Face Stretch Effect, select `Add New -> Face Effects ->
Face Stretch` in the `Objects` panel.  

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img_new/face_distort_stretch_add.gif)

### Editing The Face Inset Effect

The Face Inset Effect creates an image with a cropped texture of a
facial feature. This effect is great for adding extra eyes, mouths, or
noses to a face. The Face Stretch Template includes a Face Inset Effect,
used to create a comically large mouth that tracks the user’s face. You
can find it in the `Objects` panel under the `Distortion Effects`
object.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/distort_object_show_face_inset.png)

Select the `Face Inset` object to modify it. In the `Scene` panel, you
can drag and resize the Mouth to any part of the face. Holding `Alt`
while dragging the Face Inset will rotate the Face Inset. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/distort_position_face_inset_modify.gif)

You can adjust the appearance (including feathering, blend mode,
mirroring, and more) of the Face Inset Effect by adjusting the
properties of the Face Inset Component in the `Inspector` panel. Here,
you can also change the part of the face used in the effect.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/distort_position_face_inset_inspector_setting.gif)

### Adding a Face Inset Effect

To add a new Face Inset Effect, select `Add New -> Face Effects -> Face
Inset` in the `Objects` Panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img_new/face_distort_inset_add.gif)

### Previewing Your Lens

You're now ready to preview your Face Lens. To preview your Lens in
Snapchat, follow the [Pairing to
Snapchat](https://lensstudio.snapchat.com/guides/general/pairing-to-snapchat)
guide.

## Related Guides

Please refer to the guides below for additional information:

  - [Face Stretch](/guides/face/face-effects/face-stretch)
  - [Face Liquify](/guides/face/face-effects/face-liquify)
  - [Face Inset](/guides/face/face-effects/face-inset)

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
