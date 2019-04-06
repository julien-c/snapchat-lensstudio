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
  - Face in Picture

# Face in Picture

The Face In Picture template allows you to fill a hole of a 2D image
with the user’s face. Additionally, it shows you how to overlay facial
features like the user’s eyes and mouth over an imported 2D image.  

## Tutorial

## Guide

### Import your Custom Artwork

First, import your own custom 2D artwork into the template by clicking
`Add New` in the `Resources` panel followed by `Import Files`.
Alternatively you can drag and drop your 2D image into the `Resources`
panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/face_in_picture_add_new.png)

### Assign your Artwork

Next you will need to assign your artwork to the Screen Image object.
Locate the object named `Screen Image [EDIT_ME]` in the `Objects` panel
and assign your texture to the `Texture` field of the Image component.
It is recommended that you keep the Screen Image in Fill mode so that it
fills the entire screen.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/face_in_picture_billboard.png)

### Background Image

There is an optional background image called `Background [REMOVE_ME]`
you can replace or remove. Because it is behind everything, this object
will appear if a face is not found or when a face is lost. 

### Positioning

Adjust the position of the Face Inset object called `Face [EDIT_ME]`.
With the object selected, adjust the position by selecting the Move tool
in Len’s Studio’s toolbar or by pressing the W shortcut. Drag the
movement arrows in the `Scene` panel. Position the face so that it’s
behind the hole in your artwork.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/face_in_picture_move_scene.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/face_in_picture_move.gif)

**Note**  
You can reorder any of the objects by dragging them up or down in the
`Objects` panel. Their order will determine the order in which they are
rendered.

**Note**   
It is recommended that you tune your Face Inset positions using a 16:9
preview image. All preview images that come with Lens Studio are 16:9.
For some images that are very different resolutions, you might see
snapping in the `Preview` panel. Press the refresh button in the
`Preview` panel to see the true position of the Face Inset.

### Supporting Multiple Faces

The template includes a script called `FaceInsetController` which allows
you to easily manage multiple faces. The script takes in a list of Face
Inset objects. Then, a simple dropdown allows you to assign the inputted
objects to the first or second face. Additionally, this script
intelligently maintains the positions of the face insets in relation to
the Screen Image when the Lens is used on different device resolutions.

**Warning  
**If you delete the included Screen Image or want to use another one as
reference, make sure to set the Screen Image parameter in this script.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/face_in_picture_first_face.png)

When set to the second face, you have the option to enable `Fallback To
First`. This will fallback to the first face if it can’t find a second
face. If disabled, the face insets will only ever apply to the second
face.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/img_new/face_in_picture_second_face.png)

### Particle Flair

For the template example, we’ve added a simple snow blizzard particle
that we exported from the particle template. This helps the static 2D
image come to life. For more information on particles check out the
[Particles Template](/templates/world/particles). If you don’t need the
particle, simply remove the object called `Blizzard Particle
[REMOVE_ME]` in the `Objects` panel.

### Previewing Your Lens

You're now ready to preview your world Lens experience. To preview your
Lens in Snapchat, follow the [Pairing to
Snapchat](https://lensstudio.snapchat.com/guides/general/pairing-to-snapchat) guide.

## Related Guides

Please refer to the guides below for additional information:

  - [Face Inset](/guides/face/face-effects/face-inset)
  - [Screen Image](/guides/2d/image)

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
