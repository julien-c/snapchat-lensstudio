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
  - [Object](/templates/object)
  - Body

# Body

The Body template lets you create a Lens that adds images to an upper
body found in the camera. The detection for body works at far distances.
Great for experiences that interact with people in the rear camera. That
said, body tracking also works on an upper body close to the camera like
in a front camera selfie experience. Body tracking allows you to attach
content to the center of the body and the left and right shoulders.  

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/body_template_example_small.gif)

## Tutorial

## Guide

### Switch Preview Video

When working with the Body Template, you'll want to switch the preview
video to one with a Body. In the `Preview` panel, press the `Image /
Video Mode` button. Then, in the drop down at the top of the `Preview`
panel, select the `Body` preview video. You should now see the template
working with content applied to the upper body and shoulders. You can
also switch to Webcam in the `Preview` panel and see the content
attached to your own upper body.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/body_template_preview_video_small.gif)

### Add Resource

For the Body template, we should first import a 2D texture or animation
into the `Resources` panel. To do this, drag and drop a `PNG`, `JPG` or
`GIF` into the `Resources` panel from your computer. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/body_template_add_resource_small.gif)

### Configure Body Tracking Controller

With the `BodyTrackingControler [EDIT_ME]` object selected in the
`Objects` panel, we'll configure its settings in the `Inspector`
panel. The Body template allows you to configure the image attached to
the Right Shoulder, Left Shoulder and Center of the upper body. All are
tuned in the same way. When tuning Left Shoulder for example, I can
enable or disable the feature with the `Left Shoulder` checkbox. When
enabled, I can assign my custom texture that I imported into my
`Resources` panel to the `Left Shoulder` texture field. Finally, I can
adjust the `Size`, `Offset`, `Rotation` and `Alpha` of the feature with
the corresponding sliders.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/body_template_configure.gif)

### <span class="underline"></span>Adding Body Tracking Outside of Template

While the Body template gives you a simple way to add 2D images and
animation to the tracked points, you can also always add Body tracking
outside of the template. To do this, select `Add New -> Object Tracking
-> Body``Tracking` from the `Objects` panel. You can then edit the
position, scale and rotation of the added element in the 2D scene. 

### Object Tracking and 3D Objects

It is possible to attach 3D Objects to Object Tracking by adding a
helper script. Please refer to the [Object Tracking & 3D
Objects](/guides/general/tracking/object-tracking#3d-object-tracking) section
of the [Object Tracking](/guides/general/tracking/object-tracking) guide
for more information. 

## Submitting Your Lens

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

Hi\! We use cookies on this website to help operate our site and for
analytics and advertising purposes. For more on how we use cookies and
your cookie choices, go [here](https://www.snap.com/cookie-policy/)\! By
continuing to use our services, you are giving us your consent to use
cookies.
