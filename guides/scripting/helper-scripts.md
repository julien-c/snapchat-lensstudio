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

  - [Getting Started](/guides/getting-started)
  - General
      - [Panels](/guides/general/panels)
      - [Toolbar and Shortcuts](/guides/general/toolbar-and-shortcuts)
      - [Previewing Your Lens](/guides/general/previewing-your-lens)
      - [Pairing to Snapchat](/guides/general/pairing-to-snapchat)
      - [Importing and Updating
        Resources](/guides/general/importing-and-updating-resources)
      - Tracking
          - [Tracking Modes](/guides/general/tracking/tracking-modes)
          - [Marker Tracking](/guides/general/tracking/marker-tracking)
          - [Object Tracking](/guides/general/tracking/object-tracking)
      - [Camera and Layers](/guides/general/camera)
      - [Particles](/guides/general/particles)
      - [Segmentation](/guides/general/segmentation)
      - [Prefabs](/guides/general/prefabs)
  - Face
      - [Face Effects Overview](/guides/face/face-effects-overview)
      - Face Effects
          - [Face Mask](/guides/face/face-effects/face-mask)
          - [Face Image](/guides/face/face-effects/face-image)
          - [Head Attached 3D
            Objects](/guides/face/face-effects/head-attached-3d-objects)
          - [Face Retouch](/guides/face/face-effects/face-retouch)
          - [Face Stretch](/guides/face/face-effects/face-stretch)
          - [Eye Color](/guides/face/face-effects/eye-color)
          - [Face Liquify](/guides/face/face-effects/face-liquify)
          - [Face Inset](/guides/face/face-effects/face-inset)
          - [Face Texture](/guides/face/face-effects/face-texture)
          - [Face Image Picker
            Texture](/guides/face/face-effects/face-image-picker-texture)
      - [Working with Multiple
        Faces](/guides/face/working-with-multiple-faces)
      - [Combining World and
        Face](/guides/face/combining-face-templates-with-world-templates)
  - 2D
      - [Image](/guides/2d/image)
      - [Text](/guides/2d/text)
      - [Screen Transform](/guides/2d/screen-transform)
      - [2D Animation](/guides/2d/2d-animation)
      - [Post Effect](/guides/2d/post-effect)
      - [Video](/guides/2d/video)
      - [2D Optimization](/guides/2d/2d-optimization)
      - [Image Picker Texture](/guides/2d/image-picker-texture)
      - [GIPHY Import](/guides/2d/giphy-import)
  - 3D
      - [3D Object Export](/guides/3d/3d-object-export)
      - 3D Software
          - [Maya, 3D Object
            Export](/guides/3d/3d-software/maya-3d-object-export)
          - [Blender, 3D Object
            Export](/guides/3d/3d-software/blender-3d-object-export)
          - [Cinema 4D, 3D Object
            Export](/guides/3d/3d-software/cinema-4d-3d-object-export)
          - [3ds Max, 3D Object
            Export](/guides/3d/3d-software/3ds-max-3d-object-export)
      - [3D Object Import](/guides/3d/3d-object-import)
      - 3D Object Formats
          - [FBX, 3D Object
            Import](/guides/3d/3d-object-formats/fbx-3d-object-import)
          - [OBJ, 3D Object
            Import](/guides/3d/3d-object-formats/obj-3d-object-import)
          - [glTF, 3D Object
            Import](/guides/3d/3d-object-formats/gltf-import)
      - [3D Animation](/guides/3d/3d-animation)
      - [Vertex Animation](/guides/3d/vertex-animation)
      - Texturing
          - [Substance
            Texturing](/guides/3d/texturing/substance-texturing)
          - [Photoshop
            Texturing](/guides/3d/texturing/photoshop-texturing)
      - [Materials](/guides/3d/materials)
      - [Light and Shadow](/guides/3d/light-and-shadow)
      - [Occluders](/guides/3d/occluders)
      - [Pin To Mesh](/guides/3d/pin-to-mesh)
  - [Audio](/guides/audio)
  - [Audio Effect](/guides/audio-effect)
  - Scripting
      - [Scripting Overview](/guides/scripting/scripting-overview)
      - [Scripting Example](/guides/scripting/scripting-example)
      - [Script Events](/guides/scripting/script-events)
      - Helper Scripts
          - [Behavior](/guides/scripting/helper-scripts/behavior)
          - [Tween
            Manager](/guides/scripting/helper-scripts/tween-manager)
      - [Playing 3D Animation](/guides/scripting/playing-3d-animation)
      - [Manipulation](/guides/scripting/manipulation)
      - [Touch Input](/guides/scripting/touch-input)
      - [Persistent Storage](/guides/scripting/persistent-storage)
      - [Custom Script UI](/guides/scripting/custom-script-ui)
      - [Debugging](/guides/scripting/debugging)
      - [Scripting Hints](/guides/scripting/scripting-hints)
  - Submitting
      - [Submission
        Guidelines](/guides/submission/submission-guidelines)
      - [Performance and
        Optimization](/guides/submission/performance-and-optimization)
      - [Creating an Icon](/guides/submission/creating-an-icon)
      - [Configuring Project
        Info](/guides/submission/configuring-project-info)
      - [Lens Hints](/guides/submission/lens-hints)
      - [Preview Videos](/guides/submission/creating-a-preview-video)
      - [Community Lenses](/guides/submission/submitting-your-lens)
      - [Sponsored Lenses](/guides/submission/sponsored-lenses)
  - Sharing
      - [Sharing Your Lens](/guides/sharing/sharing-your-lens)
      - [Snapcodes](/guides/sharing/snapcodes)
      - [Unlocking Lenses](/guides/sharing/unlocking-lenses)
      - [Lens Visibility
        Settings](/guides/sharing/lens-visibility-settings)
  - [Snap Camera](/guides/snap-camera)

<!-- end list -->

  - [Guides](/guides)
  - [Scripting](/guides/scripting)
  - [Helper Scripts](/guides/scripting/helper-scripts)
  - Behavior

# Behavior

The Behavior helper script allows you to create simple interactions
without writing any custom script. With Behavior, interactions are
completely configured in the `Inspector` panel. It allows you to
configure the trigger type which defines when something should happen.
Next, it allows you to configure what should happen as a response to a
trigger. The selectable responses include a number of commonly used
interactions like playing an animation, playing a sound, enabling an
object and more. 

## Overview

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_graphic.png)

The Behavior helper script's interface is broken out into two sections:

  - **Trigger**: Defines when something should happen
  - **Response**: Defines what should happen as a response to the
    trigger

In the below example, I've configured the `Trigger` to Mouth Opened.
Next, I've configured the `Response` to `Play Sound`. The resulting
interaction is - when the user opens their mouth -\> play a sound. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_script_example.png)

## Adding Behavior

### Add Object

To add the Behavior helper script, in the `Objects` panel select `Add
New -> Helper Scripts -> Behavior`. This will create a new object with
the Behavior helper script added to it. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/behavior_add_new.gif)

**Note**  
If you're looking for the Legacy Behavior helper script, you
can [download it
here](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/files/BehaviorScript.js.zip).
Keep in mind that this version of the Lens Studio Behavior helper script
is no longer officially supported. It's highly recommended that you
follow the instructions above to add the Behavior helper script to your
project.

### Configure Behavior

Once the Behavior helper script is added, it can be configured in the
`Inspector` panel. To do this, first select the object in the `Objects`
panel. Then, in the `Inspector` panel you'll see a number of options. To
configure the Behavior helper script, first select the `Trigger` which
defines when something should happen. Then, select the `Response Type`,
which defines what should happen on trigger. Finally, configure
additional settings based on the selected Trigger and Response Type.
These additional settings are detailed below in the [Trigger
Types](#trigger-types) and [Response Types](#response-types) sections. 

In the example below, we first set the `Trigger` to the `Face Event`
type: `Brows Raised`. Then, we set the `Response Type` to `Play Sound`.
Finally, we configure the sound we want to play in the response type's
settings. The resulting interaction is - when the user's eyebrows are
raised -\> play a sound. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_script_configure.gif)

## Trigger Types

The Behavior helper script offers a number of Trigger Types via the
`Trigger` dropdown. When the Trigger happens, the Behavior helper script
will fire the Response. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_event_select.png)

The sections below detail the available Trigger Types. 

### Touch Event

The `Touch Event` trigger responds to the user touching the screen or a
portion of the screen.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_trigger_touch.png)

  - **Event Type** - The type of touch event to trigger on. Includes
    `Tap`, `Touch Start`, `Touch Move` and `Touch End` 
  - **Touch Target** - When `Touch Target` is left empty, the trigger
    will happen when the user touches the entire screen. If you set
    `Touch Target` to a MeshVisual, Scree Image or Image, the touch will
    happen only when you touch that specific object

### Face Event

The `Face Event` trigger responds to the user moving their face in some
way. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_trigger_face.png)

  - **Event Type **- The type of face event to trigger on. Includes
    `Mouth Opened`, `Brows Raised`, `Face Found`, `Kiss Started`, `Smile
    Started` and more
  - **Face Index** - The face to look for the trigger on. When two faces
    are in the scene, the first face found is `Face Index` 0 and the
    second face found is `Face Index` 1 

### Lens Turned On

The `Lens Turned On` trigger happens as soon as the Lens starts. 

### Update

The `Update` trigger happens every single frame. 

**Tip  
**You can utilize the `Update` trigger and configure the `Trigger
Options` to `After Interval`. This will create a trigger that happens
every X number of seconds.   

### Late Update

The `Late Update` trigger happens every single frame. The Late Update
however always happens immediately after the Update trigger.

### Front Camera

The `Front Camera` trigger happens every time the user switches to the
Front camera either through the swap camera button or by double tapping
the screen. 

### Back Camera

The `Back Camera` trigger happens every time the user switches to the
Back camera either through the swap camera button or by double tapping
the screen. 

### Animation End

The `Animation End` trigger happens when a specified animation finishes.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_trigger_animation_end.png)

  - **Anim Type **- The type of the animation that you want to respond
    to when the animation finishes. This can be an animated texture, an
    animated image or an animated 3D mesh
  - **Target **- Depending on the `Anim Type` that is selected, here
    you'll configure the animation resource or object you want to
    respond to when the animation finishes

### Tween End

The `Tween End` trigger happens when a Tween finishes utilizing the
[Tween System](/guides/scripting/helper-scripts/tween-manager). 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_trigger_tween_end.png)

  - **Target Object **- The object the Tween is on
  - **Tween Name **- The name of the Tween that is being played

### Looking At

The `Looking At` trigger happens when one object is looking at another
object.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_trigger_looking_at.png)

  - **Looking Object **- The object that's doing the looking. A common
    use case here is to make the ` Looking Object  ` your primary camera
  - **Look Target **- The object that when looked at triggers the
    response
  - **Flip Forward Vec **- Flips the z direction where the angle is
    compared. This should be enabled when your `Looking Object` is a
    camera
  - **Compare Type **- How you'll compare the angle between the two
    objects. Options are `Less Than`, `Equal To` and `Greater Than`
  - **Angle **- The tunable angle used to trigger the response
  - **Allow Repeat **- When enabled, the response will call every frame
    when the angle check succeeds`  `

### Distance Check

The `Distance Check` trigger happens when one object is within a
configurable distance of another object. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_trigger_distance_check.png)

  - **Object A **- The first object to distance check against
  - **Object B **- The second object to distance check against
  - **Compare Type **- How you'll compare the distance between the two
    objects. Options are `Less Than`, `Equal To` and `Greater Than`
  - **Distance **- The tunable distance used to trigger the response
  - **Allow Repeat **- When enabled, the response will call every frame
    when the distance check succeeds

### On Custom Trigger

The `On Custom Trigger` happens when a custom trigger is fired via
another Behavior helper script. See the [Send Custom
Trigger](#send-custom-trigger) response type below. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_trigger_on_custom_trigger.png)

  - **Trigger Name **- The name of the custom trigger to respond to

### None Trigger

The `None` trigger is when you don't want the behavior to be run. You
might use this when keeping old behaviors in your project as reference
but don't want them to ever run. 

## Trigger Options

A number of additional options are available when configuring your
Trigger that apply to all Trigger Types. 

### Always

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_script_trigger_option_always.png)

When `Always` is selected, the Trigger will always happen over multiple
same triggers. Additionally, you're able to configure a `Delay
Time` which delays the Response a configurable number of seconds after
the trigger happens. 

### Once

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_script_trigger_option_once.png)

When `Once` is selected, the Trigger will only happen once during the
lifetime of the Lens. Same triggers after the first will be
ignored. Additionally, you're able to configure a `Delay Time` which
delays the Response a configurable number of seconds after the trigger
happens. 

### After Interval

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_script_trigger_option_after_interval.png)

When `After Interval` is selected, the Trigger will wait the `Interval
Time` before allowing the trigger to happen again. Within the `Interval
Time` window, same triggers will be ignored. When the `Interval Time`
window is complete, the Trigger can happen again. Additionally, you're
able to configure a `Delay Time` which delays the Response a
configurable number of seconds after the trigger happens. 

## Response Types

The Behavior helper script offers a number of Response Types via
the `Response Type` dropdown. When the Trigger happens, the Behavior
helper script will fire the Response. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/behavior_response_types.png)

The sections below detail the available Response Types.   

### Animate Image

The `Animate Image` response type plays a 2D animation. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/behavior_response_animate_image.png)

  - **Animated Texture **- The animated texture you'd like to play
  - **Visual Object **- Alternatively, you can select a visual object to
    play the 2D animation on. This can be a Mesh Visual, Screen Image or
    Image. If both an `Animated Texture` and `Visual Object` are set,
    the `Animated Texture` will be applied to the Visual Object and
    played
  - **Action **- The action to take on the animation. Available options
    are: `Play`, `Play or Resume`, `Pause` and `Stop`
  - **Loop **- When playing an animation, should the playback
    continuously loop

### Animate Mesh

The `Animate Mesh` response type plays a mesh animation.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_animate_mesh.png)

  - **Animation Mixer **- The animation mixer to play the animation on
  - **Layer Name **- The layer name of the animation to play
  - **Action **- The action to take on the animation. Available options
    are: `Play`, `Play or Resume`, `Pause` and `Stop`
  - **Loop **- When playing an animation, should the playback
    continuously loop

### Play Sound

The `Play Sound` response type plays a sound. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_play_sound.png)

  - **Audio Track **- The audio resource (e.g. mp3) that you want to
    play. Note, the response automatically creates an Audio Component
    for you if one isn't specified
  - **Audio Component **- Alternatively, you can select an `Audio
    Component` to play the audio on. If both `Audio Track` and `Audio
    Component` are set, the `Audio Track` will be applied to the `Audio
    Component` and played
  - **Loop **- When playing a sound, should the playback continuously
    loop
  - **Volume **- The volume at which the sound is played

### Set Enabled

The `Set Enabled` response type enables or disables a Scene Object.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_set_enabled.png)

  - **Target **- The target Scene Object to enable or disable
  - **Action** - Defines if the object should be enabled, disabled or
    toggled (If disabled, enable. If enabled, disable)

### Set Color

The `Set Color` response type sets the color of an object or material.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_set_color.png)

  - **Visual **- A mesh visual or image object to set the color on
  - **Material **- A material to change the base color on. This is only
    used if `Mesh Visual` is not set
  - **Color **- The color that will be set

### Set Texture

The `Set Texture` response type sets the texture of an object.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_set_texture.png)

  - **Target **- A mesh visual or image object to set the texture of
  - **New Texture **- The texture to set on the target object

### Set Text

The `Set Text` response type sets the text of a Text or Screen Text
object.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/behavior_response_set_text.png)

  - **Text Component - **The Text Component to apply the text to
  - **Text - **The string you'd like to set the Text Component's text
    to 

### Run Tween

The `Run Tween` response type runs a Tween utilizing the [Tween
System](/guides/scripting/helper-scripts/tween-manager). 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_run_tween.png)

  - **Target Object **- The scene object the Tween is on
  - **Tween Name** -** **The name of the Tween to be played
  - **Action **- The action to take on the Tween. Available options are:
    `Start`, `Stop`, `Pause` and `Resume`

### Set Position

The `Set Position` response type sets the position of an object's
Transform. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_set_position.png)

  - **Object to Move** - The object to set the position of
  - **Position** - The vec3 position to set
  - **Local Space** - When enabled, local space will be used. When
    disabled, world space will be used

### Set Rotation

The `Set Rotation` response type sets the rotation of an object's
Transform. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_set_rotation.png)

  - **Object to Rotate **- The object to set the rotation of
  - **Euler Rotation **- The vec3 euler rotation to set
  - **Local Space **- When enabled, local space will be used. When
    disabled, world space will be used

### Set Scale

The `Set Scale` response type sets the scale of an object's Transform. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_set_scale.png)

  - **Object to Scale **- The object to set the scale of
  - **Scale **- The vec3 scale to set
  - **Local Space **- When enabled, local space will be used. When
    disabled, world space will be used

### Set Screen Position

The `Set Screen Position` response type sets the position of an object
with a Screen Transform. For example, a Screen Image or Screen Text
object. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/behavior_response_set_screen_position.png)

  - **Screen Transform - **The Screen Transform you'd like to apply the
    position to
  - **Position Type **- The type of position you'd like to set.
    Available options are Basic Position, Anchors Rect and Offset Rect
  - **Basic Position **- A basic local position. For most simple
    positioning, you should use basic position
  - **Anchors Rect - **The relative position within the parent on a -1
    to 1 scale
  - **Offset Rect - **Fixed world unit offsets to each edge position

### Set Screen Rotation

The `Set Screen Rotation` response type sets the rotation of an object
with a Screen Transform. For example, a Screen Image or Screen Text
object. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/behavior_response_set_screen_rotation.png)

  - **Screen Transform - **The Screen Transform you'd like to apply the
    rotation to
  - **Angle **- The angle rotation to set from 0.0 to 360.0

### Set Screen Size

The `Set Screen Size` response type sets the size of an object with a
Screen Transform. For example, a Screen Image or Screen Text object. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/behavior_response_set_screen_size.png)

  - **Screen Transform - **The Screen Transform you'd like to apply the
    size to
  - **Size Type -**  The type of size you'd like to set. Available
    options are Basic Scale, Anchors Rect and Offset Rect
  - **Basic Scale **- A basic local scale. For most simple scaling, you
    should use basic scale
  - **Anchors Rect - **The relative size within the parent on a -1 to 1
    scale
  - **Offset Rect - **Fixed world unit offsets to each edge position

### Print Message

The `Print Message` response type prints a debug message to the `Logger`
panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_print_message.png)

  - **Message** - The message to print to the `Logger` panel

### Send Custom Trigger

The `Send Custom Trigger` response type sends a custom trigger message
as a trigger to other Behavior helper scripts. The [On Custom
Trigger](#on-custom-trigger) type can trigger based on the `Send Custom
Trigger` response type. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_response_send_custom_trigger.png)

  - **Trigger Name **- The name of the custom trigger to send

## Script Interface

In addition to configuring BehaviorScripts through the
`Inspector` panel, it's also possible to interact with them through
script. This means you can use your scripts to trigger BehaviorScript
responses, or react to BehaviorScript triggers with your scripts.

### Local API

These functions are accessible on the `api` object of any
`ScriptComponent` holding a BehaviorScript. They only affect the
specific BehaviorScript being accessed.

  - `api.trigger()` -  Manually triggers the BehaviorScript's response
  - `api.addTriggerResponse(callback)` - Adds a callback function to
    call when this BehaviorScript is triggered
  - ` api.removeTriggerResponse(callback)  `- Removes the callback
    function from this BehaviorScript's response

<!-- end list -->

    //@input Component.ScriptComponent behaviorScript
    function onTrigger(){
        print("behavior script triggered");
        // Remove our onTrigger() function from the BehaviorScript responses
        script.behaviorScript.api.removeTriggerResponse(onTrigger);
    };
    // Add our onTrigger() function as a response to the BehaviorScript being triggered
    script.behaviorScript.api.addTriggerResponse(onTrigger);

### Global API

These functions are accessible on the `global.scBehaviorSystem` object
from anywhere in script. They provide a way to globally send Custom
Triggers or react to global Custom Triggers through script.

  - ` global.scBehaviorSystem.sendCustomTrigger(triggerName)  `- Sends
    out a global Custom Trigger that BehaviorScripts can react to
  - `global.scBehaviorSystem.addCustomTriggerResponse(triggerName,
    callback)` - Adds a callback function to call when the Custom
    Trigger is sent
  - `global.scBehaviorSystem.removeCustomTriggerResponse(triggerName,
    callback)` - Removes the callback function from the Custom Trigger's
    responses

**Example 1**  

In this example, executing the line of code will trigger the `Print
Message` response on the BehaviorScript.

    // Send a global Custom Trigger that any BehaviorScript can react to
    global.scBehaviorSystem.sendCustomTrigger("test_trigger");

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_api_send_trigger.png)

**Example 2**  

In this example, touching the screen will cause the BehaviorScript to
send a Custom Trigger which is reacted to by a function in script.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/behavior_api_add_custom_trigger_response.png)

    function onTrigger() {
        print("on trigger");
        // Remove our onTrigger() function from the custom trigger's responses
        global.scBehaviorSystem.removeCustomTriggerResponse("my_trigger", onTrigger);
    }
    // Add our onTrigger() function as a response to the custom trigger "my_trigger"
    global.scBehaviorSystem.addCustomTriggerResponse("my_trigger", onTrigger);

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
