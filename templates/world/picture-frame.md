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
  - Picture Frame

# Picture Frame

The Picture Frame Template gives you the power to build a Lens with a
single 2D image. Import your own custom 2D image and link it to the
picture frame. The template then automatically builds a 3D picture frame
around your content.

## Tutorial

## Guide

### Adding the 2D Image

The Cutout Template assumes that you have a 2D image which you'll be
importing into Lens Studio. It's important to use optimized images for
Lens size and performance reasons. Follow below to create optimized
texture resources:

  - Images should never be greater than 2048 x 2048 pixels
  - Non-transparent images should be saved using JPEG. Transparent
    images should be saved using PNG
  - If the image allows, try compressing to reduce the Lens size

Drag and drop your 2D image into the `Resources` panel. Then click on
`PictureFrameController` in the `Objects` panel. In the `Inspector`
panel, click on the `Picture` setting and select your imported image.
Now, go to the `Preview` panel to see your auto generated 3D picture
frame.

![Picture Frame
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/picture_frame_template_add_image.gif)

### Customize

The `PictureFrameController` allows you to customize both the picture
and frame itself. To customize, select the `PictureFrameController` in
the `Objects` panel. Then in the `Inspector` panel under the `Script`
component you will see the list of customization options.

#### Customize the Picture

The following customization options allow you to configure the picture
itself, its size, positioning and shadow.

  - `Picture` - This should be replaced by your imported texture
  - `Picture Scale` - The scale of the picture and picture frame
  - `Picture Ground Offset` - How far off the picture frame is from the
    ground
  - `Shadow Density` - The intensity of the shadow from 0.0 to 1.0

![Picture Frame
Template](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/picture_frame_template_picture_customize.gif)

#### Customize the Frame

The following customization options allow you to configure the frame's
style, color and size.

  - `Frame Color` - The color of the frame
  - `Frame Style` - The style of the frame (3 Styles to choose from)
  - `Material` - The material of the frame (Glossy or Matte)
  - `Frame Scale` - The thickness of the frame

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img/picture_frame_template_frame_customize.gif)

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

### PictureFrameController.js

  - `Picture (Asset.Texture)` - The texture that the frame will
    automatically be built around. This should be replaced by your
    imported texture
  - `Picture Scale (float)` - The scale of the picture and picture
    frame. The larger the scale, the bigger the picture in the scene
  - `Picture Ground Offset (float)` - How far off the picture frame is
    from the ground
  - `Frame Color (vec4)` - The color of the frame selected via a color
    picker
  - `Frame Style (Dropdown)` - The style of the frame selected via a
    dropdown
  - `Material (Dropdown)` - The material of the frame selected via a
    dropdown. This allows you to select between a Glossy and Matte
    material
  - `Frame Scale (float)` - The scale of the frame itself. This allows
    you to create a thin or thick surrounding frame
  - `Shadow Density (float)` - The intensity of the shadow from 0.0 to
    1.0. The closer to 1.0, the darker the shadow

## Related Guides

Please refer to the guides below for additional information:

  - [Getting Started](/guides/getting-started)
  - [Image](/guides/2d/image)
  - [2D Animation](/guides/2d/2d-animation)
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

Hi\! We use cookies, including third-party cookies, on this website to
help operate our site and for analytics and advertising purposes. For
more on how we use cookies and your cookie choices, go
[here](https://snap.com/cookie-policy/) for our cookie policy\! By
clicking below, you are giving us consent to use cookies. You can change
your cookie settings by clicking on "More information" below.

I Accept

[More Information](https://www.snapchat.com/cookie-settings)
