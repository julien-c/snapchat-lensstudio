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
  - Paper Head

# Paper Head

The Paper Head Template lets you create a customizable head that reacts
to facial movement. The template tracks the user’s eyes, mouth and the
direction the head is facing to drive 2D textures and 2D animations.  

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/paper_head_template_example.gif)

## Tutorial

## Guide

### Select Paper Head Controller

To edit the Paper Head template, first select the `Paper Head Controller
[Edit Me]` object in the `Objects` panel on the left side of Lens
Studio. With the object selected, we can configure its settings in the
`Inspector` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/paper_head_select_object.gif)

### Add Resources

For the Paper Head template, we should first import your 2D textures or
animations into the `Resources` panel that you want to apply to the
face. To do this, drag and drop a `PNG`, `JPG` or `GIF` into
the `Resources` panel from your computer. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/paper_head_template_add_resource.gif)

### Configure Mouth

The Mouth Face element has three different types of Mouths selectable
via the Mouth Type drop down.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/paper_head_template_mouth_type.gif)

The sections below walk through each Mouth Type. 

**Mouth Type, Texture Sequence**

In this Mouth Type, the `Mouth Textures` array is filled with various
textures that represent a mouth starting as closed and ending as opened.
As the user opens their mouth, the Texture Sequence will select an image
for the mouth based on how wide the mouth is opened. Fill the `Mouth
Textures` fields to your own custom textures. Press the `Trash` icon to
remove frames and the `Add Value` button to add frames. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/paper_head_template_texture_seq.gif)

**Mouth Type, Animated Texture**  

In this Mouth Type, an animated texture of a mouth is played back based
on how open the user’s mouth is. Set the `Animated Texture` field to
your own custom animated texture. For more information on importing a 2D
Animation, follow the [2D Animation](/guides/2d/2d-animation) guide. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/paper_head_template_animated_texture.gif)

**Mouth Type, Sliding Mouth**

The last Mouth Type is unique to Mouth. It requires two textures. One
texture of the entire head and another texture of the lower jaw. In
creating these textures, think of a ventriloquist’s puppet. In the
`Inspector` panel, set the `Head Texture` field to your custom head
texture and the `Mouth Texture` field to your custom mouth texture. The
Mouth Texture will slide based on the user’s mouth movement. The `Mouth
Offset` and `Slide Amount` can be configured in the `Inspector` panel
via the corresponding sliders. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/paper_head_template_sliding_mouth.gif)

Below is an example of a Head Texture (without mouth) and the Mouth
Texture (without head). 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cat_texture_head.png) ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/cat_texture_mouth.png)

**Tuning the Mouth**

Each mouth type has sliders to tune the mouth.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/paper_head_mouth_type_inspector.png)

  - **Size - **How big the mouth is
  - **Offset X - **The offset of the mouth horizontally
  - **Offset Y - **The offset of the mouth vertically
  - **Rotate - **Apply a rotation to the mouth if needed
  - **Alpha - **How transparent the mouth is
  - **Flip Image - **Will mirror the texture horizontally
  - **Flip With Head - **Based on the direction the head is facing, the
    texture will flip to face that direction. This gives the 2D texture
    a quasi 3D effect

### Configure Nose

Enable the `Nose` by checking the Nose checkbox. Unlike the mouth, it
does not have different Types. That said, if you do want an animated
nose, the `Nose Texture` field does support an animated texture. The
tuning settings as described in the Mouth section above (Size, Offset,
Rotation, Alpha, Flip Image and Flip With Head) are also available for
Nose. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/paper_head_template_nose.gif)

**Tip   
**We recommend using the `Flip with Head` option on the Nose to give it
an effect that responds to facial movement  

### Configure Eyes

Enable the `Left Eye` or `Right Eye` by checking the `Left Eye` or
`Right Eye` checkbox. The Eyes both support the `Texture Sequence` and
`Animated Texture` types which are selected from the `Eye Type` drop
down. The tuning settings as described in the Mouth section above (Size,
Offset, Rotation, Alpha, Flip Image and Flip With Head) are also
available for Left and Right Eyes. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/paper_head_template_eye.gif)

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
