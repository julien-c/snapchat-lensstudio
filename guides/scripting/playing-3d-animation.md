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
  - Playing 3D Animation

# Playing 3D Animation

## Introduction

This guide will walk you through playing 3D animations imported into
your Lens Studio project. Lens Studio supports the following types of
animation:

  - Joint Animation
  - Transform Animation
  - Blendshape Animation

### Related Guides

This guide touches on concepts in the following guides:

  - [3D Object Export](/guides/3d/3d-object-export)
  - [3D Object Import](/guides/3d/3d-object-import)
  - [Scripting Overview](/guides/scripting/scripting-overview)
  - [Scripting Example](/guides/scripting/scripting-example)

## Project Setup

To follow this guide, you'll need to set up a Lens Studio project with
an imported 3D animated mesh. For more information on how to import a 3D
mesh, please refer to the [3D Object Import
guide](/guides/3d/3d-object-import).

## Autoplay Animation

For simple animation playback, the Animation Mixer component has
an `Autoplay` checkbox. When enabled, Autoplay will automatically play
a looping animation.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/animation_mixer_autoplay.png)

## Scripting Animation

Animation playback in Lens Studio can also be controlled by script. The
following script can be used in most cases when your scene has an
imported animated mesh.

### Create The Script Resource

Create an empty Script in the `Resources` panel.

![Create Empty
Script](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/resources_new_script_empty.gif)

Copy the `PlayAnimation.js` code below into the Script you just created:

### Script: PlayAnimation.js

    // PlayAnimation.js
    // Version: 0.0.3
    // Event: Lens Turned On
    // Description: Plays a single animation on an animated mesh. If an AnimationMixer is not set, the script will attempt to find one on the SceneObject.
    //@input Component.AnimationMixer animationMixer
    //@input string animationLayerName = "BaseLayer"
    //@input float animationWeight = 1.0 {"widget":"slider", "min": 0, "max": 1, "step": 0.01}
    //@input float animationStartOffset = 0.0
    //@input int numberOfLoops = -1
    if(!script.animationMixer)
    {
        script.animationMixer = script.getSceneObject().getFirstComponent("Component.AnimationMixer");
    }
    if(script.animationMixer)
    {
        script.animationMixer.setWeight(script.animationLayerName, script.animationWeight);
        script.animationMixer.start(script.animationLayerName, script.animationStartOffset, script.numberOfLoops);
    }

**Script Resources**  
For a detailed guide on creating a Script Resource, visit the [Scripting
Example](/guides/scripting/scripting-example).

## PlayAnimation.js Properties

`PlayAnimation.js` defines properties that can be customized for your
Lens.

#### Animation Mixer

This is a reference to the Animation Mixer Component controlling
playback of the mesh's animation. All animated meshes imported into Lens
Studio automatically have an Animation Mixer. If this property is left
undefined in the Inspector, the script will try to use the
AnimationMixer on the Scene Object (if one exists). Defaults to None.

#### Animation Layer Name

The name of the Animation Layer to be played on the Animation Mesh. To
learn more about setting up Animation Layers, please refer to the [3D
Object Export Guide](/guides/3d/3d-object-export). Defaults to
"BaseLayer".

#### Animation Weight

A float from 0 to 1 that indicates the blend weight of the current
Animation Layer. Defaults to 1. The default value should be used in the
majority of cases.

#### Animation Start Offset

The time offset in seconds at which the animation should start playing.
Defaults to 0.

#### Number Of Loops

An integer indicating the number of times the animation should loop. A
value of -1 will make the animation loop infinitely. Defaults to -1.

## Set up the Script Component

Add a Script Component to your imported Scene Object.

In the `Inspector` panel, select `Add Component -> Script`.

On the `Script` Component you just added, select `Add Script`.

In the selection dialog that pops up, select the `PlayAnimation` script
you created earlier.

Using the `Script` Component's event dropdown, set the script's event to
`Lens Turned On`.

In the `Inspector` panel you should see the Script Component updated
with the properties from the PlayAnimation script.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/playing_animation_inspector.png)

## Animation Clips

If you prefer to animate your objects on a single timeline, the
Animation Mixer component supports the ability to define clips directly
inside of Lens Studio. This allows you specify a start and stop time and
name for each clip. When you create an animation clip, it creates a new
layer called whatever you named the clip. You can then play the
animation layer just like you would an imported animation layer by
referencing the layer name in the above PlayAnimation script or in the
various Interactive templates. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/anim_clips_editor.png)

  - **Clip View** - This is where you can create, remove and edit clips
  - **From / To / Offset** - Here you can define the start and stop
    times for you clip as well as an offset if you'd like to shift the
    entire animation start and stop times
  - **Range Type** - This allows you to specify your animations time in
    frames or seconds
  - **Cycles** - How many times you'd like the animation to play
  - **Weight** - This value determines the amount of influence the
    animation will have on the objects joints where a value of 0.0 = 0%
    and a value of 1.0 = 100%
  - **Speed** - How fast will the animation playback where a value of
    0.0 = 0% and a value of 1.0 = 100%
  - **Blend Type** - When blending multiple animations you can specify
    how you would like this blend to be applied
      - **Override** - Completely overrides any influence on the joints
        this animation will be applied giving this animation priority
      - **Additive** - The weight of this animation will be added to any
        current animation influence already being applied to the joints
        this animation is being applied to
  - **Scale Accum** - This value determines how you want the animation
    values to be applied to the joints
      - **Multiply** - Multiples the values to each joint effectively
        scaling values currently applied
      - **Additive** - Adds the desired animation's values to the
        currently applied values on joints
  - **Post Infinity** - When an animation clip reaches it's last frame
    this value determines how the animation will continue
      - **Cycle** - The animation will start over at the first frame and
        continue on
      - **Oscillate** - The animation will play in reverse when it
        reaches it's final frame and vice versa effectively giving a
        "ping pong" effect

## Previewing the Animation

Press the `Reset Preview` button in the `Preview` panel to see your 3D
mesh play its animation.

![Animation](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/playing_animation_preview.gif)

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
