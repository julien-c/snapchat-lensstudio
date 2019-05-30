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
  - [Interactive](/templates/interactive)
  - Soundboard

# Soundboard

The Soundboard Template allows you to create your very own soundboard
Lens\! This Lens template features a set of buttons that each trigger a
different sound and popup graphic. The buttons in the Soundboard
Template's Lens will show during recording allowing the user to press
them but won't be rendered in the final Snap. It does this by using a
unique Capture Target and Live Target. Refer to the [Camera and
Layers](/guides/general/camera) guide for more information on showing
things during recording but not having them be in the final Snap. 

## Guide

### Exploring The Template

Once you have the project open, you’ll see a set of buttons in the
`Preview` panel. Try clicking on these buttons in the `Preview` panel to
see what they do.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/soundboard_intro.gif)

You should see that each button triggers a different sound and kitty
visual.  

### The Soundboard Keys

The sounds and visuals triggered by the buttons are controlled by a
group of SceneObjects. You can see them in the `Objects` panel, named
with the prefix “SoundboardKey\_”.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/soundboard_template_soundboard_keys.png)

### The Trigger Visuals

The Kitty visuals you see popping in after each button press are also
SceneObjects, named with the prefix “TriggerVisual\_”.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/soundboard_template_visuals.png)

### Adding Custom Sounds

To edit the sound played by a button, start by selecting its
corresponding “SoundboardKey\_” object in the `Objects` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/select_soundboard_key.png)

The selected object has a SoundboardKey script. You can change the sound
it plays by editing the `Audio Track` property on that script
component.  

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/soundboard_replace_sound_new.gif)

To bring in your own audio track, in the `Resources` panel, select `Add
New -> Import Files`.  

### Adding Custom Visuals

To replace the image displayed on one of the popup visuals, start by
selecting its corresponding “TriggerVisual\_” object in the `Objects`
panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/soundboard_select_visual.png)

The selected object has a Sprite component. You can change its image by
editing the `BaseTex` property on the Sprite Component.  

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/soundboard_replace_visual.gif)

To bring in your own image, in the `Resources` panel, select `Add New ->
Import Files`.   

### Updating The Motion

Each of the TriggerVisual objects has its own predefined tweens for
entering and exiting the frame. You can adjust these settings by editing
the TweenBillboard script components attached to the “TriggerVisual\_”
objects.

To edit the visual’s start position, edit the `Start` property on the
Tween named “show”, and edit the `End` property on the Tween named
“hide.” Also, be sure to set the Sprite Aligner’s `Binding Position`
property to match this value.

To edit the visual’s end position, edit the `End` property on the Tween
named “show”, and edit the `Start` property on the Tween named “hide.”

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/soundboard_tween.png)

To learn more about how the Tween system works, visit our documentation
on **[Tweening](https://lensstudio.snapchat.com/guides/scripting/tweening/)**.  

### Editing The Buttons

You can change the appearance of the buttons by editing the button’s
Material, which you can find in the `Resources` panel under “Materials.”

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/soundboard_button_materials.png)

You’ll likely only want to adjust the `Base Color` and `Base Texture`
properties.   

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/soundboard_material_properties.png)

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

Hi\! We use cookies, including third-party cookies, on this website to
help operate our site and for analytics and advertising purposes. For
more on how we use cookies and your cookie choices, go
[here](https://snap.com/cookie-policy/) for our cookie policy\! By
clicking below, you are giving us consent to use cookies. You can change
your cookie settings by clicking on "More information" below.

I Accept

[More Information](https://www.snapchat.com/cookie-settings)
