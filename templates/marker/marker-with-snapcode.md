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
  - [Marker](/templates/marker)
  - Marker with Snapcode

# Marker with Snapcode

The Marker with Snapcode template lets you unlock a Lens via Snapcode
and immediately track your content to it; then, switching to tracking
your image when it’s visible. This template is great for creating a Lens
that overlays content onto existing images such as a poster or mural.

**Tip**  
Since you won't get a Snapcode until you've submitted your Lens, you can
[download](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/lens-studio-snapcode.png)
this example Snapcode to use as a placeholder in your image.

**Warning**  
It is not recommended to utilize the Marker with Snapcode template for a
sponsored experience because it is not guaranteed that the user will
have the target marker readily available. For brands, the Marker with
Snapcode template is instead recommended for print campaigns with a Lens
that is unlockable via Snapcode. 

## Tutorial

## Guide

### Exporting 3D Content

The Animated Object Template assumes that you have a 3D animated object
which you'll be importing into Lens Studio. First you must export your
object to be Lens Studio ready. To do this, follow the [3D Object
Export](https://lensstudio-internal-dot-inedia-tigers.appspot.com/guides/3d/3d-object-export)
guide.

### Importing 3D Content

Once you have your 3D object exported, follow the [3D Object
Import](https://lensstudio-internal-dot-inedia-tigers.appspot.com/guides/3d/3d-object-import)
guide to import your 3D object into Lens Studio.

### Placing Your Content

Once your content is imported, in the `Objects` panel, drag your content
underneath the `MarkerWithSnapcodeController`. Then remove the object
`MyScene [REPLACE_ME]`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/marker-with-snapcode-1.gif)

### Importing your Image as a Visual Hint

Since we’re using marker tracking, your content will not show up when
your marker is not visible. To help your user find the right image, we
provide a simple UI to let the user know what they need to do.

To do this, import your image by dragging and dropping your image from
your computer to the `Resources` panel. Then, in the `Objects` panel,
select `Magnifying Hint [EDIT_ME]` and select the `Preview Texture`
field. In the popup window, select your newly imported image.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/marker-with-snapcode-2.gif)

### Importing your Image as a Marker

Now, we need to tell our Lens what image to look for. In your `Resources
panel`, click `Add New -> Image Marker`. Then in the file selection
window, choose your image.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/marker-with-snapcode-3.gif)

**Note**  
Your image should be high resolution, but below 2048 x 2048

### Tracking your Image Marker

To use the new marker you created, in the `Objects` panel, select `Image
Tracking`. Then, in the `Inspector` panel, select the `Marker` field,
and choose your new Image Marker in the popup.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/marker-with-snapcode-4.gif)

### Setting Up Your Markers

Since we are tracking two different markers, it is crucial that their
relationship in the real world is reflected in Lens Studio so that your
content will seamlessly track across the two markers. 

Select `Snapcode Marker [EDIT_ME]` in the `Resources` panel, and in the
`Inspector` panel, type in the height of your Snapcode in centimeters.

Similarly, select your marker in the `Resources` panel, and in the
`Inspector` panel, type in the height of your image in centimeters.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/marker-with-snapcode-5_181004_213908.gif)

Finally, in the `Objects` panel select `Snapcode Tracking`, and in the
`Scene` panel, use the move widget to position your Snapcode
relationally to your image.

### Setting Up Reference Points

Additionally, we will need to track our content to a common reference
point so the Lens knows how to position our content in relation to each
marker. 

To do this, we need three objects that all have the same world position.
Since, by default, the `Reference Point` under `Image Tracking` is in
the same position as `MarkerWithSnapcodeController` (world origin), all
we need to do is copy this position to `Snapcode Tracking`. To do
this: right-click the `Reference Point` under `Image Tracking` and
select `Duplicate`. Then, drag the duplicated object under `Snapcode
Tracking`. Finally, remove the original `Reference Point` under Snapcode
Tracking. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/marker-with-snapcode-7.gif)

### Setting Up Cross Hint

We provide a multi-colored cross animation that plays to help users
understand that a marker has been found. You can set this animation to
animate from a certain point. Usually this is where your Snapcode is.

In the `Objects` panel, select `CrossController [POSITION_ME]`, and in
the `Scene` panel, use the move widget to move this object in the x and
y coordinate to where your `Snapcode Tracking` object is.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/marker-with-snapcode-8.gif)

### Setting Up an Occluder

We provide a rectangle occluder to help you occlude anything outside
your image. In the `Objects` panel, select `Occluder`, and in the
`Inspector` panel, modify the x and y scale to the size of your image in
centimeters. You can fine tune the occluder using the scale widget in
the `Scene` panel. 

**Note**  
This occluder is a regular mesh with an occluder material which has a
rectangular hole cut out in the middle. If your image is not
rectangular, feel free to replace it with your own custom occluder
mesh. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/marker-with-snapcode-9.gif)

### Fading in Your Content

In most cases you will want to transition your content in so that it
feels like it’s coming from the marker rather than instantly popping
into place.

To do this, in the `Resources` panel, select the materials that your
content uses that you want to fade in. Then, in the
`Inspector` panel, tick the box labeled `Fizzle`. Finally, in your
`Objects` panel, select `MeshFadeController` and under `Fade Materials`,
press `Add Value` and add the materials which you want to fade in.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/marker-with-snapcode-10.gif)

**Tip**  
You can choose whether your object fades in or fades out in the `Fade
Type` drop down. 

### Previewing Your Lens

You're now ready to preview your Lens experience. To preview your Lens
in Snapchat, follow the [Pairing to
Snapchat](/guides/general/pairing-to-snapchat) guide.

### Submitting Your Lens

For information on submitting your Lens, follow the below guides:

  - [Creating an Icon](/guides/submission/creating-an-icon)
  - [Configuring Project
    Info](/guides/submission/configuring-project-info)
  - [Submitting Your Lens](/guides/submission/submitting-your-lens)
  - [Sharing Your Lens](/guides/sharing/sharing-your-lens)

## Script Interface

### MarkerWithSnapcodeController.js

In some cases you may want to specify how your content should play. To
do this, you can add a global function which the template will call
based on the status of the marker tracker. One way to do this is to
create a script on an object and set the script to run on
`Initialized`. This template includes an example script which is
attached to the `MyScene` object (found in the `Resources` panel
under `Mark in the City Example [REMOVE_ME] -> Scripts ->
MySceneController.js`). 

  - `global.onSceneEnabled` - This function, if it exists, will be
    called when a marker is found
  - `global.onSceneWillDisable` - This function, if it exists, will be
    called when a marker is lost
  - `global.onSceneDisabled` - This function, if it exists, will be
    called one frame after global.onSceneWillDisable is called

## Related Guides

Please refer to the guides below for additional information:

  - [Marker Tracking](/guides/general/tracking/marker-tracking)
  - [](/guides/face/face-stretch)[Marker
    Template](/templates/marker/marker)

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
