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
  - Touch Input

# Touch Input

## Introduction

You can add interactivity to the Lenses you create in Lens Studio by
handling user touch input events. Your Lens can play a sound, trigger a
character animation, and more by listening for events when the user
touches the screen of their device.

This guide provides an overview of the available touch events in Lens
Studio, as well as instruction in handling user touch events in a Lens.

**Scripting**  
This guide assumes you are familiar with the basics of scripting in Lens
Studio. To learn more about scripting, please visit the [Scripting
Overview](/guides/scripting/scripting-overview).  

-----

## Touch Events Overview

Lenses can handle and respond to a number of user touch events,
including when a touch starts or ends, when the user taps the screen,
and when the user moves a held touch across the screen.

### Touch Started

This event is triggered when the user starts a screen touch.

### Touch Moved

This event is triggered when the user moves their finger while holding a
screen touch (i.e. while dragging on the screen).

### Touch Ended

This event is triggered when the user ends a screen touch (i.e. when the
user lifts their finger off of the screen).

### Tapped

This event is triggered when the user taps the screen (i.e. when they
quickly start and stop a touch).

**Requires Touch Blocking  
**To handle the Tapped event, your Lens needs to [enable touch
blocking](#touch-blocking).

**Events**  
To learn more about events in Lens Studio, please visit the [Script
Events Guide](/guides/scripting/script-events).

-----

## Handling Touch Events

User touch input is handled by assigning scripts to the events described
above. In Lens Studio, touch input events can come from touching the
screen, or from touching a specific 3D object in the scene.

### Touching the Screen

Lenses can respond to touch events that trigger when the user touches
the screen. For example, your Lens can play a sound any time the user
touches the screen.

The following guide will walk you through setting up a screen-based
Touch Started event.

#### Set up the Script Component

Add a Script Component to a Scene Object.

On the new Script component, select `Add Script`.

![Touch Input
Guide](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/touch_guide_script_add_script.png)

In the Script selection popup dialog, select `Add New -> Create Empty`

Bind the Script to the "Touch Started" event by selecting it from the
Script Component's dropdown.

![Touch Input
Guide](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/touch_guide_script_select_touch_started.png)

Select the new Script from the Resources panel. In the Inspector, edit
the Script by adding the following code:

``` 
    // Set the object's scale to a random value.
    var min = 0.1;
    var max = 1.5;
    var newScale = Math.random()*(max - min) + min;
    script.getTransform().setWorldScale(new vec3(newScale, newScale, newScale));
```

Select `Apply Changes` in the Inspector.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/script_apply_changes.png)

#### Preview the Project

[Preview the Lens on your device](/guides/general/pairing-to-snapchat).
You should see a sphere rendered on the screen. When you touch anywhere
on the screen, the sphere will randomly change in scale.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/touch_input_2D.gif)

  

-----

### Touching a 3D Object

Lenses can respond to touch events that trigger when the user touches a
3D object. This is useful for cases when the user should interact with a
specific object in the scene. For example, when the user taps on a 3D
character in your Lens, that character plays an animation. This type of
interaction is implemented in the [Interactive Tap
Template](/templates/interactive/interactive-tap).

Touch events on 3D Objects are enabled by adding a Touch Component. The
Touch Component keeps references to Mesh Visual components in the scene.
When any of these Mesh Visuals are touched or tapped by the user, a
touch event will be triggered.

The following guide will walk you through setting up a Touch Started
event on a 3D object.

#### Set up the Touch Component

Add a  `Touch` Component to a Scene Object.

On the new  `Touch` Component, select `Choose Mesh Visual`.

![Touch Input
Guide](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/touch_guide_touch_choose_mesh_visual.png)

Select the Mesh Visual component from your Scene Object.

**Touch Component and Mesh Visuals**  
The Touch Component can only be used on Scene Objects that have a Mesh
Visual component. If you do not explicitly add a Mesh Visual reference
to the Touch Component, it will try to find one on the Scene Object.

Set the Camera property to the Camera component in your scene.

![Touch Input
Guide](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/touch_guide_touch_mesh_selected.png)

  

**Default Camera**  
If you don't set the Camera property on a Touch Component, it will use
the Scene's current main camera by default.

#### Set up the Script Component

Add a  `Script` Component to the Scene Object.

On the new  `Script` component, select `Add Script`.

![Touch Input
Guide](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/touch_guide_script_add_script.png)

In the Script selection popup window, select `Add New -> Create Empty`

Bind the Script to the "Touch Started" event by selecting it from the
Script Component's dropdown.

![Touch Input
Guide](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/touch_guide_script_select_touch_started.png)

Select the new Script from the Resources pane. In the Inspector's Script
Editor, paste the following script:

``` 
    // Set the object's scale to a random value.
    var min = 0.1;
    var max = 1.5;
    var newScale = Math.random()*(max - min) + min;
    script.getTransform().setWorldScale(new vec3(newScale, newScale, newScale));
```

Select `Apply Changes` in the Inspector.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/script_apply_changes.png)

-----

#### Preview the Project

[Preview the Lens on your device](/guides/general/pairing-to-snapchat).
You should see a sphere rendered on the screen. When you touch the
sphere, it will randomly change in scale.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/touch_input_3D.gif)

  

**Touch Bounds  
**The Touch Component uses the Mesh Visual's bounding box to determine
the touch target. Keep this in mind as you set up your touch
interactions.  

-----

## Touch Blocking

There may be times when you want your Lens to receive all touch events
to prevent the user from unintentionally triggering other Snapchat
actions while using your Lens. For example, if your Lens has a rapid
tapping interaction you may want to override Snapchat's default behavior
of switching cameras on double-tap.

In these instances, you can make use of Touch Blocking. With Touch
Blocking, you can override some or all of Snapchat's default touch
behaviors.

### Basic Use

To override the Snapchat app's default touch events, add the following
line to a script bound to the "Lens Turned On" event:

    global.touchSystem.touchBlocking = true;

With this line included, your Lens will override all of the app's
default screen touch events.

**Touch System**  
The global property `global.touchSystem` is a TouchDataProvider object
used to manage touch blocking exceptions.

### Touch Blocking Exceptions

You may not want to override all of the default Snapchat touch events.
For example, you may want to override the double-tap event, but still
allow the user to swipe to Stories or Chat. In this instance, you can
make use of Touch Blocking Exceptions.

#### Usage

To make an exception for a specific type of touch, add the following
code to a script bound to the "Lens Turned On" event:

    global.touchSystem.touchBlocking = true;
    global.touchSystem.enableTouchBlockingException("TouchTypeSwipe", true);

In the example above, the Lens overrides all of the default touch
events, but makes an exception for screen swipes. Enabling this
exception allows the user to still swipe into another view of Snapchat
(like Stories or Chat) while the Lens is active.

You can replace the string `TouchTypeSwipe` with any of the Touch Types
listed in the section below.

#### Exception Types

You can enable or disable the following Touch Type Exceptions:

**TouchTypeTap**: Enabling this exception allows Snapchat to continue
handling the tap gesture.

**TouchTypeDoubleTap**: Enabling this exception allows Snapchat to
continue handling the double-tap gesture.

**TouchTypeScale**: Enabling this exception allows Snapchat to continue
handling the two-finger pinch gesture.

**TouchTypePan**: Enabling this exception allows Snapchat to continue
handling the two-finger pan gesture.

**TouchTypeSwipe**: Enabling this exception allows Snapchat to continue
handling the swipe gesture.

## Related Documentation

Please refer to the guides below for additional information:

  - [Scripting Overview](/guides/scripting/scripting-overview)
  - [Scripting Events](/guides/scripting/script-events)

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
