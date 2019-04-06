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
  - Scripting Example

# Scripting Example

## Introduction

This guide will walk you through the process of creating a simple script
in Lens Studio. You'll learn how to create a Script resource, connect
your script to a Scene Object using the Script Component, and finally
trigger the script from a Lens Event.

The script you create in this guide will add an oscillating bounce
movement to a 3D object.

### Related Guides

This walk-through touches on concepts from the following guides:

  - [](/guides/scripting/scripting-overview)[Scripting
    Overview](/guides/scripting/scripting-overview)
  - [Script Events](/guides/scripting/script-events)
  - [Custom Script UI](/guides/scripting/custom-script-ui)

## Project Setup

To follow this guide, you'll need to set up a Lens Studio project that
has a Scene Object with a  `Mesh Visual` component. You can use any mesh
you like.

## Prepare the Script Resource

With our Scene Object ready, we can now prepare a Script Resource.

**Script Resources**  
To learn more about Script Resources, visit the [Scripting
Overview](/guides/scripting/scripting-overview).

### Create a Script Resource

In the `Resources` panel, select `Add New -> Script`.

![Create Empty
Script](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/resources_new_script_empty.gif)

Give the newly created script a name that describes what the script
does. Rename it to `Bounce`.

![Rename
Script](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_example_script_rename.gif)

### Open the Script

You can open the `Bounce` script in either Lens Studio's internal
editor, or the external text editor of your choice.

#### Internal Editor

To open your script in the built-in Lens Studio editor, select your
Script in the `Resources` panel.

You'll see the Script editor in the `Inspector` panel.

![Script
Editor](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_example_script_editor_internal.png)

#### External Editor

To open your script in an external editor, double click on your script
in the `Resources` panel.

Alternatively, you can also select your script resource in the
`Resources` panel, then select `Open External Editor` in the
 `Inspector` panel.

![Script
Editor](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_example_script_editor_external.png)

-----

## Connect the Script

Scripts in Lens Studio are triggered by assigning them to Events on a
Script Component.

### Add the Script Component

Select your Scene Object.

In the `Inspector` panel, select `Add Component -> Script`.

### Select the Script Resource

On the Script Component you just added, select `Add Script`.

![Script
Editor](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_example_component_add_script.gif)

In the selection dialog that pops up, select the `Bounce` script you
created earlier.

![Script
Editor](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_example_component_select_script.png)

Using the  `Script` component's event dropdown, Set the Bounce script's
event to `Frame Updated`.

## ![Script Editor](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_example_component_set_event.gif)

## Write the Script

We can now write the code for our project. This code will continuously
bounce a 3D object up and down.

This section breaks down each part of the script's code. The [completed
script](#completed-script-bouncejs) is provided at the end of this
guide.

### Define the Properties

Properties are variables used by a script that can be edited live in the
Lens Studio `Inspector` panel.

For this script, we will define two properties:

  - **`speed`**: (float) The speed at which the object will bounce
  - **`range`**: (float) The range of the object's bounce

Add the following line to your script:

    //@input float speed = 1.0
    //@input float range = 10.0

The Script Component you added to your Scene Object should now be
updated with these two properties. Note that the `Inspector` panel view
reflects the default values defined in the script.

![Script
Editor](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_example_component_properties.png)

  

**Properties**  
To learn more about properties, visit the [Scripting
Overview](/guides/scripting/scripting-overview)

### Create Property Widgets

It's possible to [create a custom Inspector
interface](/guides/scripting/custom-script-ui) for your Script Component
properties. This is especially useful when you have properties that need
tuning.

In the case of the Bounce script, it would be handy to adjust the
`speed` and `range` properties of the bouncing motion using sliders.

To create the custom UI, update the property definitions in your script
as follows:

    //@input float speed = 1.0 {"widget": "slider", "min": 0, "max": 10.0, "step": 0.01}
    //@input float range = 10.0 {"widget": "slider", "min": 0, "max": 30.0, "step": 0.01}

You should now see the `speed` and `range` properties represented as
sliders in the `Inspector` panel.

![Script
Editor](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_example_component_widgets.png)

**Custom Script UI**  
To learn more about the different UI elements you can add to Script
Components, visit the [Custom Script UI
guide](/guides/scripting/custom-script-ui).

### Complete the Script

Let's complete the script. Add the following code to your Bounce script,
below the property definitions:

    // Calculate the new height of the Scene Object and store it in newY.
    var newY = Math.sin(getTime() * script.speed) * script.range;
    // Set the new local position of the Scene Object to [0, newY, 0].
    script.getSceneObject().getTransform().setLocalPosition(new vec3(0, newY, 0));

Because we bound this script to the `Frame Updated` event in the
Inspector, this code will run every frame, adding an incremental change
in position to the Scene Object's transform.

## Preview the Lens

Press the Refresh button in the `Preview` panel to reload the scene. You
should now see the Scene Object bouncing up and down in the `Preview`
panel.

![Script
Editor](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_example_preview.gif)

-----

## Completed Script: Bounce.js

Here's the completed `Bounce.js` script.

    // Bounce.js
    // Event: Frame Updated
    // Properties:
    //@input float speed = 1.0 {"widget": "slider", "min": 0, "max": 10.0, "step": 0.01}
    //@input float range = 10.0 {"widget": "slider", "min": 0, "max": 30.0, "step": 0.01}
    var newY = Math.sin(getTime() * script.speed) * script.range;
    script.getSceneObject().getTransform().setLocalPosition(new vec3(0, newY, 0));

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
