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
  - Photo

# Photo

With Lens Studio you can easily create Face Lenses by importing an image
of a face. This technique is perfect for creators who specialize in
makeup, face painting, and other non-digital media. The Photo Template
shows you how to import an image, align it to the face and make specific
areas visible like just the lips. 

## Tutorial

## Guide

This tutorial assumes you have an image that contains a face. We will
use the image below in this guide.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-sub-mask-1.jpg)

### Importing your Texture

Once you have your image, you can import it into Lens Studio as a
texture by dragging it into the `Resources` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-sub-mask-6.gif)

### Applying your Texture

Next, click `Face Mask [EDIT_ME]` in the `Objects` panel to select your
face mask. Drag your texture into the `Texture` field in your
`Inspector` panel.

You can also press the field next to `Texture` to open up the resource
selector and select your texture.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-sub-mask-10.gif)

You can see your Lens in action by checking the `Preview` panel. If you
don't see a face press the camera switch button to flip to the front
camera.

 ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-sub-mask-1.png)

You can additionally use your webcam to preview your Lens on yourself by
pressing the web camera button. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-sub-mask-2.png)

### Aligning your Texture

To align your texture to the face, first select the `Face Mask
[EDIT_ME]` object in the `Objects` panel. Then, in the `Scene` panel,
press the `Detect Face` button. Lens Studio will then try to match the
anchor points to your image. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-sub-mask-9.gif)

### Aligning Details of your texture

If you need to, you can touch up the anchor points to fit more closely
to your texture. Select any anchor point and you will be able to move it
around. You can also select multiple anchor points, and move / resize
multiple anchors simultaneously.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-sub-mask-2.gif)

### Applying an Opacity Texture

By default, Lens Studio will apply your texture to the whole face. You
can choose to show only some parts of the face instead by pressing the
field next to `Opacity Texture` and selecting a texture under the
`Opacity Textures` folder. Opacity Textures show everything in the white
regions of the texture and hide everything in the black regions of the
texture. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-sub-mask-7.gif)

### Changing Blend Mode

You can change the blend mode of your texture to have it blend more with
the face by clicking the `Blend Mode` drop down in the `Face Mask`
component in the `Inspector` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-sub-mask-5.gif)

### Changing Opacity

You can also modify an image’s opacity by moving the `Alpha` slider in
the `Face Mask` component in the `Inspector` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/face-sub-mask-4.gif)

### Previewing Your Lens

You're now ready to preview your Face Lens experience. To preview your
Lens in Snapchat, follow the [Pairing to
Snapchat](https://lensstudio.snapchat.com/guides/general/pairing-to-snapchat)
guide.

## Related Guides

Please refer to the guides below for additional information:

  - [Face Mask](/guides/face/face-effects/face-mask)

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
