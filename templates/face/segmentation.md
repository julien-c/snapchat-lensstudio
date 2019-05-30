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
  - Segmentation

# Segmentation

The Segmentation Template lets you easily segment a portion of the
camera and replace it with an image, tiled image or post effect
coloring. Multiple segmentation types are supported including portrait
background, hair, sky and more. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_examples.png)

## Tutorial

## Guide

### Select Segmentation Controller Object

To tune the Segmentation Template, select the `SegmentationController
[EDIT_ME]` object in the `Objects` panel and then tune its settings in
the `Inspector` panel. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_select_object.png)

### Set Segmentation Texture

With the `Headband Controller [EDIT_ME]` object selected, select the
field next to `Segmentation Texture` in the `Inspector` Panel. Then,
select a segmentation texture from the included `Segmentation Textures`
folder. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_texture.png)

Available segmentation textures are:  

  - Portrait Background
  - Portrait Hair
  - Portrait Shoulder
  - Portrait Head
  - Portrait Head
  - Sky

**Note**  
All of the segmentation textures can be inverted by selecting the
segmentation texture in the `Resources` panel and checking the `Invert`
checkbox. 

### Background Color

To enable a solid background color, make sure the `Use Background Color`
checkbox is checked.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_coloring_enabled.png)

Once enabled, you’re able to tune the solid background color and alpha.
This background color will be masked by your selected Segmentation
Texture.   

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_background_color_tune.png)

### Image

To enable a segmentation masked image, make sure the `Use Image`
checkbox is checked. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_use_image.png)

**Set Texture**

After selecting you image type, you’ll want to assign the image texture.
To add a texture to Lens Studio, drag and drop a PNG or JPG to the
`Resources` panel. Alternatively, select `Add New -> Import Files` from
the `Resources` panel. Then, click the `Image Texture` field and assign
it to your newly imported texture. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_image_texture.png)

**Set Alpha**

You have control for how transparent your image will be via the `Image
Alpha` slider.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_image_alpha.png)

**Set Blend Mode**

You can set your image blend mode using the `Image Blend Mode` drop
down. Available blend modes are `Normal`, `Screen` & `Multiply`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_image_blend_mode.png)

**Tiled**

When the `Tiled` checkbox is selected, your image is tiled. This tiled
background will be masked by your selected segmentation texture. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_example_1.png)

The following options in the `Inspector` panel allow you to configure
the tiling.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_tiled_settings.png)

  - **Tile Density** - How dense the tiled pattern is. Smaller number =
    smaller tiles. Bigger number = bigger tiles
  - **Scrolling** - If enabled, the tile pattern will play a scrolling
    animation
  - **Scroll Speed X** - How fast the tile pattern scrolls in the
    horizontal direction
  - **Scroll Speed Y** - How fast the tile pattern scrolls in the
    vertical direction

**Non-Tiled**

When the `Tiled` checkbox is not checked, your image texture will be
used as a single background image. This image will be masked by your
selected segmentation texture.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_example_2.png)

When using a non-tiled image, you can configure how the image fills the
screen by selecting from the `Fill Mode` dropdown. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_full_fill_mode.png)

### Post Effect

To enable post effect, make sure the `Use Post Effect` checkbox is
checked.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_use_post_effect.png)

When enabled, a post effect will be applied to the camera feed, masked
by your selected segmentation texture. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_example_3.png)

You can change your post effect texture by selecting the field next to
`Post Effect Texture` in the `Inspector` panel. Then select a post
effect resource. To add a new Post Effect type, select `Add New -> Post
Effect Textures` in the `Resources` panel or create your own by
following the [Post Effect](/guides/2d/post-effect) guide.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/sementation_template_post_effect_texture.png)

You can also tune the transparency of the applied post effect. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/sementation_template_post_effect_alpha.png)

### Adding Additional Objects

**Not Segmented**

To add an additional object that lives on top of the segmentation mask
(not segmented). Simply use `Add New` from the `Objects` panel as you
normally would. As long as the objects are set to either the `Default`
or `Orthographic Camera` layers, the object will not be segmented by the
mask.

**Segmented**

To add an additional object that is segmented, you need to assign your
object to the appropriate camera render layer. For perspective camera
objects, set your object’s render layer to `Masked`. For orthographic
camera objects, set your object’s render layer to `Orthographic
Masked`. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/segmentation_template_render_layer.png)

### Previewing Your Lens

You’re now ready to preview your Lens experience. To preview your Lens
in Snapchat, follow the [Pairing to
Snapchat](/guides/general/pairing-to-snapchat) guide.

## Related Guides

Please refer to the guides below for additional information:

  - [Segmentation](/guides/general/segmentation)
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
