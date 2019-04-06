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
  - Pet

# Pet

The Pet Template lets you create a Lens that adds content to Cat or Dog
faces. The template allows you to attach images or animations to a Pet’s
Left Eye, Right Eye, Nose and Center of the head.  

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/pet_template_cat_example.gif)

## Tutorial

## Guide

### Switch Preview Video

When working with the Pet Template, you'll want to switch the preview
video to one with a cat or dog. In the `Preview` panel, press the `Image
/ Video Mode` button. Then, in the drop down at the top of the `Preview`
panel, select the `Cat and Dog`, `Cat`, or `Dog` preview video. You
should now see the template working with content applied to the Cat or
Dog’s face.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/pet_template_preview_panel_switch.gif)

### Add Resource

For the Pet template, we should first import a 2D texture or animation
into the `Resources` panel. To do this, drag and drop a `PNG`, `JPG` or
`GIF` into the `Resources` panel from your computer. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/object_add_resource.gif)

### Configure Pet Tracking Controller

With the `PetTrackingController [EDIT_ME]` object selected in the
`Objects` panel, we'll configure its settings in the `Inspector` panel.
First, let's select the Tracking Type we'd like to use from the
`Tracking Type` drop down. The `Cat` tracking type will only apply to
cats. The `Dog` tracking type will only apply to dogs. The ` Cat or Dog
 `tracking type will apply to either a Cat or a Dog found in the
camera. 

**Tip  
**If you're not creating an experience that ONLY works on Cats or ONLY
works on Dogs, we recommend using the `Cat or Dog` tracking type

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/pet_tracking_type.gif)

The Pet template allows you to configure the image attached to the Right
Eye, Left Eye, Nose or Center of the head. All are tuned in the same
way. When tuning Right Eye for example, I can enable or disable the
feature with the `Right Eye Tracking` checkbox. When enabled, I can
assign my custom texture that I imported into my `Resources` panel to
the `Right Eye` field. Finally, I can adjust the `Size`, `Offset`,
`Rotation` and `Alpha` of the feature with the corresponding sliders.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/pet_configure_large.gif)

### Adding Pet Tracking Outside of Template

While the Pet template gives you a simple way to add 2D images and
animation to the tracked points, you can also always add Cat and Dog
tracking outside of the template. To do this, select ` Add New -> Object
Tracking -> Cats and  ``Dogs Tracking` from the `Objects` panel. You can
then edit the position, scale and rotation of the added element in the
2D scene. 

### Object Tracking and 3D Objects

It is possible to attach 3D Objects to Object Tracking by adding a
helper script. Please refer to the [Object Tracking & 3D
Objects](/guides/general/tracking/object-tracking#3d-object-tracking)
section of the [Object
Tracking](/guides/general/tracking/object-tracking) guide for more
information. 

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
