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
  - Fullscreen

# Fullscreen

The Fullscreen Template allows you to create a sequence of fullscreen
states triggered by tap or time. A state is defined in the template by
specifying which objects are shown and which animations and sounds are
played at a given time. The template includes helpers such as a freeze
frame effect (with different zoom levels), a tween system, and a way to
hide Mesh or Sprite Visuals while recording.

## Tutorial

## Setup Resources and Objects

### Importing 2D Content

Once you have your 2D content exported, we can add it as a texture to
Lens Studio by dragging and dropping the image(s) into your `Resources`
panel.  

You can import animated content by following
the [](https://lensstudio.snapchat.com/guides/2d/2d-animation)[2D
Animation](/guides/2d/2d-animation) guide on adding animated images.  

### Importing Sounds

Similarly, we can add your sounds (we recommend mono channel MP3) to
Lens Studio by dragging and dropping the sounds(s) into your `Resources`
panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_addFiles.gif)

### Creating a Billboard

You can create a new fullscreen image by pressing `Add New ->
Billboard`. Then, drag your imported texture from the `Resources` panel
to the `BaseTex` field in the Sprite Component of your new `Billboard`
object. You can learn more about billboards in our
[](https://lensstudio.snapchat.com/guides/2d/billboard/) [Billboard
guide](/guides/2d/image).

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_addBillboard.gif)

## Setup States

Once you have several Billboards, we can hook them up to different
states to create our Lens.

### Ordering States

In the `Objects` panel, the `FullscreenTemplateManager` object contains
children objects that represent each state of your Lens in the order
they will appear (1st child being the 1st state, 2nd child being the 2nd
state, and so on). When an end condition is met, the current state will
end and the next one will begin.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_stateOrder.png)

### Creating a State

A state is an empty child object of `FullscreenTemplateManager` with the
script `FullscreenTemplateState` set to `Initialized`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_state.png)

### Anatomy of a State

A state contains three section:

  - **On Start**: called when the state is entered
      - Here you can add objects you want to enable, add SpriteVisual
        components with animations you want to play, and audio files you
        want to play
  - **On End**: called when the state is leaving
      - Here you can add objects you want to disable, add SpriteVisual
        components with animations you want to stop, and audio files you
        want to stop
  - **End Condition**: triggers the `On End` event and leads to the next
    state being activated
      - Here you can choose what will cause the state to end and
        continue to the next state
      - If there is an `End Condition` on the last state, it will lead
        back to the first state

### Transitioning out of States

The `End Condition` section of a state allows you to specify when the
Lens should proceed to the next state in the list. A state can be
transitioned out by tapping, by time, or both:

  - **End On Tap**
      - `End on Tap` will be triggered when the user taps anywhere on
        the screen
      - Double-tap and swipes will be passed to the main Snapchat app
  - **End On Time**
      - Will proceed to the next state after `End Time Length` seconds
        has elapsed since the state was entered
      - If `End On Tap` is also enabled, the user can “skip” the `End
        Time Length`

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_endCondition.png)

You can learn more about each field in the [Script
Interface](#interface) section at the bottom of this guide.

## State Examples

### Showing an Object On Start

You can have objects show up when you enter a state by adding them to
the `Enable Objects` list in the `On Start` section of the state.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_enableObjects.gif)

### Playing an Animation On Start

You can play an animation when you enter a state by adding it to the
`Play Animation` list in the `On Start` section of the state. Don’t
forget to uncheck `Always Play` in the animation’s `Inspector` panel so
it doesn’t start in the middle of the animation when you enter the
state.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_playAnimation.gif)

### Disabling an Object On End

If you don’t want your `Billboard` to stay visible in the next state,
you can add it to the list of `Disabled Objects` in the `On End` section
of the state.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_disableObjects.gif)

## Additional State Tips

### Empty Start

You may want to start with a normal camera feed until the user taps. You
can simply create an empty state with the option `End On Tap` checked as
your first state.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_addTap.gif)

### Freeze frame

To freeze the camera feed when you enter a state: in the `On Start`
section,  add an object to the `Enable Objects` array. Choose:
`Orthographic Camera -> Effects -> Freeze Camera -> Freeze Camera`. You
can use 1x, 1.5x, 2x, 3x, depending on how zoomed in you want the frozen
frame to be.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_freeze.gif)

### Delaying a State

To create a delay before activating the next state, we can add a new
state in between the two states. In this between state, we can set its
`End Condition` to `End On Time` and set the `End Time Length` to the
delay length.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_waitSec.gif)

## Additional Helper Functionality

### Tweening System

You can add animations to your `Billboard` by using the included Tween
System. In your Billboard's `Inspector` panel select `Add Component ->
Script`. Then select `Helper -> TweenSystem -> TweenTypes ->
TweenBillboard`, and set the dropdown to `Initialized`. You can learn
more about the Tween System in the [Tweening
guide](/guides/scripting/helper-scripts/tween-manager).

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_addTween.gif)

In this template, the tween should only play when you enter a state. In
order to do so, uncheck `Play Automatically` to prevent it from playing
when the Lens opens, and name the tween so that we can reference it.

After adding all your tweens, we can add the `PlayTweensOnStart` script
to play our tweens in series when we enter a state. To do this, press
`Add Component -> Script`. Then choose `Helper -> PlayTweensOnStart` and
set it to `Initialized`. Then add the name(s) of your tween(s) to the
`Tween Names` field.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_playTween.gif)

### Hiding Hints

This template also includes a `HideWhenRecording` script. This is useful
for when you want to provide hints to the user that won’t appear while
the Lens is recording. To use it, select the object you want to hide,
and in its `Inspector` panel, add a `Script` component: `Add Component
-> Script`. Then select `Helpers -> HideWhenRecording` and set the
dropdown to `Frame Updated.`

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/fullscreenTemplate_addHint.gif)

## Previewing Your Lens

You're now ready to preview your world Lens experience. To preview your
Lens in Snapchat, follow the [Pairing to
Snapchat](https://lensstudio.snapchat.com/guides/general/pairing-to-snapchat)
guide.

## Script Interface

### FullscreenTemplateState.js

  - **On Start**
      - `Enable Objects (SceneObjects[])` When a state starts these
        objects will be enabled. When the Lens opens, these objects will
        be disabled automatically
      - Animation Control
          - `Play Animations (Component.SpriteVisual[])` The BaseTex
            attached to these SpriteVisuals will be played based on the
            options below
          - `Play Count (number)` How many times the sprites should be
            played when the state starts. -1 will loop the animation
            forever
          - `Play Offset (number)` The sprites play offset in seconds
      - Sound Control
          - `Play Sounds (Asset.AudioTrackAsset[])` The AudioTrackAsset
            attached from the Resource panel will automatically be given
            an AudioComponent accessible by any state and will be played
            when we enter the state
          - `Play Count (number)` How many times to play the sound when
            this state starts. -1 will loop the sound forever
  - **On End**
      - `Disable Objects (SceneObjects[])` When a state ends these
        objects will be disabled. When the Lens opens, these objects
        will be disabled automatically
      - Animation Control
          - `Stop Animations (Component.SpriteVisual[])` Stop the
            BaseTex attached to these SpriteVisuals when the state ends
      - Sound Control
          - `Stop Sounds (Asset.AudioTrackAsset[])` Stop the attached
            AudioTrackAssets when the state ends
  - **End Condition**
      - `End On Tap (bool)` Whether the state should end when the user
        taps anywhere in the screen
      - Time Control
          - `End On Time (bool)` Whether the state should end when “End
            TIme Length” has elapsed since the state started
          - `End Time Length (number)` Max number of seconds that the
            current state will be active for

### Custom Scripts in State

You can create your own custom logic attached to the state system by
using the following API in your scripts:

  - `script.api.onStart (function)` Called when a state starts
  - `script.api.onUpdate (function)` Called while a state is active
  - `script.api.onEnd (function)` Called when a state ends

FullscreenTemplateState.js will go through each object in its “Enable
Objects” list and call these API functions on any Script components it
finds. You can see an example of this in FreezeCameraOnStart.js or
PlayTweensOnStart.js.

### FreezeCameraOnStart.js

  - `Freeze Camera (Component.Camera)` The camera which should be
    disabled when the state starts, and enabled when the state ends.
    Disabling the camera will freeze the camera output texture to the
    last frame. This is used in conjunction with a billboard with the
    camera’s output as texture to freeze a frame

### PlayTweensOnStart.js

This script allows you to hook the TweenSystem to each state. You can
learn more about tweens in the [Tweening
guide](/guides/scripting/helper-scripts/tween-manager).

  - `Tween Names (String[])` The names of the tweens on the current or
    specified Scene Object to be played one after the other when the
    state starts
  - `Reset On End (Bool)` Whether or not the object attached to the
    tween should be reset back to its start position at the end of the
    state
  - `Scene Object (SceneObject) (optional)` The object that contains the
    tweens listed above. By default it is the current object

### HideWhenRecording.js

This script will disable or enable any MeshVisual and/orSpriteVisual on
the attached object  when the user is recording a lens. This is useful
for adding hints that you don’t want to appear while recording. It
should be bound to `Frame Updated`.

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
