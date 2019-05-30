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
  - Cutout

# Cutout

The Cutout Template lets you create a World Lens by importing just a 2D
image or animation. A cutout includes movement, scale, rotation, shadow
and the ability to always look at the camera. Multiple Cutouts can be
added to the Lens allowing you to create a 3D scene with movable 2D
objects.   

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cutout_example.gif)

## Tutorial

## Guide

### Switch Preview Video

Switch the preview video to one of our World Lens preview videos. In the
preview panel, press the `Image / Video Mode` button. Then, in the drop
down at the top of the `Preview` panel, select any video under the
`World` category. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cutout_select_preview.gif)

**Tip   
**If you don’t see the World category, press the `Switch Camera` button
to switch your preview to the rear camera.

### Add Resource

First import a custom 2D texture by dragging and dropping it into the
`Resources` panel. This can be a `PNG`, `JPG` or `GIF` animation. For
more information on importing 2D Animation, refer to the [2D
Animation](/guides/2d/2d-animation) guide.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cutout_add_resource.gif)

### Select Cutout Controller

Next, in the `Objects` panel, select the `CutoutController [EDIT_ME]`
object.  

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cutout_select_object.gif)

### Configure Cutout

With the `CutoutController [EDIT_ME]` object selected, you can configure
its settings in the `Inspector` panel. First, click the `Texture` field
and set it to your newly imported Texture resource. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cutout_set_texture.gif)

You can then configure the following settings to tune your cutout. 

  - **Ground Offset - **How far above or below the cutout is from the
    ground
  - **Shadow -** When enabled, the cutout casts a real time shadow on
    the ground. It is derived from the silhouette of the 2D image
  - **Look At Camera - **When enabled, the cutout will always face the
    camera about the Y axis
  - **Flip - **The 2D image will be mirrored horizontally

### Scale Cutout

To resize the Cutout object, select the `CutoutController` object in
the `Objects` panel. Then, in the `Scene` panel, press the `R` keyboard
shortcut to enable the object's scale handles. Drag the `cyan` cube in
the center of the object to scale up or down the object uniformly. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cutout_scale.gif)

### Multiple Cutouts

The template supports multiple Cutout Controller objects. To create a
new one, right click on the `CutoutController` object and select
`Duplicate`. Alternatively, you can drag and drop the `CutoutController`
prefab in the `Resources` panel to the `Objects` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cutout_new_cutout.gif)

After you've added a new Cutout Controller object, you'll want to offset
its starting position so it's not overlapping your original cutout. To
do this, select the duplicated object in the `Objects` panel. Then, in
the `Scene` panel, press the `W` keyboard shortcut to enable the
object's movement handles. Drag the `red` and `blue` handles to offset
it along the x and y axis. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cutout_position_cutout.gif)

### Shadow Direction

The direction of the shadow can be adjusted by selecting the `Light`
object in the `Objects` panel. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cutout_select_light_sm.png)

Then, with the light selected, in the `Scene` panel rotate the light by
pressing `E` keyboard shortcut and dragging the axis rings. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cutout_light.gif)

### Submitting Your Lens

You’re now ready to submit your Lens\! Follow the guides below:

  - [Pairing to Snapchat](/guides/general/pairing-to-snapchat)
  - [Creating an Icon](/guides/submission/creating-an-icon)
  - [Configuring Project
    Info](/guides/submission/configuring-project-info)
  - [Submitting Your Lens](/guides/submission/submitting-your-lens)
  - [Sharing Your Lens](/guides/sharing/sharing-your-lens)

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
