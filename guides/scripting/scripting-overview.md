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
  - Scripting Overview

# Scripting Overview

`  `![Scripting
Overview](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_overview.gif)

## Introduction

Lens Studio provides a scripting library for creating rich interactive
experiences. With scripts, your Lenses can respond to touch input, play
animation and audio, modify Scene Objects, and more. This guide provides
a broad overview of Lens Studio scripting.

### Scripting Example

For a step-by-step guide to creating and running your first script,
please refer to the [](/guides)[Scripting
Example](/guides/scripting/scripting-example).

### API Reference

For a detailed technical reference of all classes and methods available
in Lens Studio, please refer to the [Scripting API](/api) in the
navigation menu.

-----

## Script Components

In Lens Studio, scripts are added to the scene as  `Script` components,
which are attached to Scene Objects.

![Script
Component](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/script_component.png)

*A Script Component*

The Script Component integrates [Script Resources](#script-resources)
into a scene by:

  - Running custom code when Lens **events** are triggered
  - Exposing custom script **properties** for tweaking script behavior
    from the Lens Studio `Inspector` panel

### Events

A [Lens Event](/guides/scripting/script-events) is a trigger that is
activated while using a Lens. There are events for user activity (e.g.
Tapped, Touch Started, etc.), as well as inherent Lens events (Frame
Updated, Lens Turned On, etc.). The Script Component binds Lens Events
to custom script code.

For example, in the image below, we bind a script called *AddTintColor*
to the event *Touch Started*.

![Script Component
Event](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/script_component_event.png)

*A custom script bound to a Lens Event*

In this example, when the user touches the screen, the script
*AddTintColor* will run.

### Properties

Script Properties are variables you can define to customize your
script's behavior. Properties defined in a script can be modified in the
`Inspector` panel, making them useful for tweaks and adjustments in Lens
Studio. Properties are also useful for referencing Scene Objects,
Components, and Assets from your script.

![Script Component
Property](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/script_component_property.png)

*Custom script properties*

In the image above, the Script Component exposes the following
properties:

  - A Material named *Object Material*
  - A vec4 (color) named *Tint Color*
  - A float number named *Change Speed*

These properties can be edited live in the  `Inspector` panel without
the need for modifying code.

**Custom Property Widgets  
**Widgets like sliders, color pickers, and more are available using a
special definition syntax in your script. To learn more about how to
include widgets in your script properties, visit the [Custom Script UI
guide.](/guides/scripting/custom-script-ui)

## Script Resources

Script Resources (referred to as *Scripts*) are text files that contain
the code you write for your Lens. Scripts are written in Lens Studio's
own implementation of Javascript. Here's an example of a very basic
script:

    // My first Lens Studio script!
    print("Hello, World!");

*A basic script. When triggered, this script will print "Hello, World\!"
to the [Logger](/guides/scripting/debugging).*

**Javascript**  
While Lens Studio scripts are written in Javascript, there are some
practices specific to the Lens Studio environment with which you should
become familiar. To learn more, please refer to the section on [Writing
Scripts](#writing-scripts).

### Adding Script Resources

There are two ways to add Scripts to your Lens Studio project. You can:

  - **Create** an empty script file
  - **Import** an existing script file

#### Creating an Empty Script

You can add an empty script in the `Resources` panel by selecting

`Add New -> Script`

![Create Empty
Script](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/resources_new_script_empty.gif)

#### Importing an Existing Script

You can import an existing script in the  `Resources` panel by clicking

`Add New -> Import Files...`

![Create Empty
Script](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/resources_new_script_from_file.gif)

-----

## Writing Scripts in Lens Studio

Lens Studio scripts are written in an implementation of standard
Javascript, but there are a few practices specific to the Lens Studio
environment that you'll need to be aware of as you write scripts for
your Lenses.

#### Declaring Properties

To declare a property in your script, you'll need to use the `@input`
keyword. The format of a property definition looks like this:

    //@input float intensity = 1.0
    //@input string objectName
    //@input Component.AudioComponent music
    //@input float[] delayTimes

In this example, we declared four properties:

  - A `float` named `intensity` with a default value of 1.0
  - A `string` named `objectName`
  - A reference to an [Audio Component](/api/classes/AudioComponent)
    named `music`
  - A `list` of `floats` named `delayTimes`

Properties defined in script are editable in the object's
 `Script` component[](#script-components) via the  `Inspector` panel.

**Type Reference**  
You can learn more about available property types in the [Scripting
Input Type Reference](/api/InputTypes).

**Custom UI**  
You can learn more about customizing your script's UI in the [Custom UI
Guide](/guides/scripting/custom-script-ui).

#### Accessing a Property

Defined properties become members of the pre-defined object `script`.
You can access a property defined in your script using the keyword
`script`.

For example:

    //@input string hello = "Hello, World!"
    print( script.hello );

You can learn more about the `script` object in the [Scope](#scope)
section below.

### Scope

Variables and functions you declare in script are accessible in three
layers of scope.

#### Local Scope

All functions and variables you declare with `var` in a script are
locally scoped by default. In other words, they can be accessed only
from the script in which they're defined.

#### The `script` Scope

You can use the `script` object to access and modify properties defined
in a Script. The same `script` object is shared between all Scripts on a
Script Component.

#### The `global` Scope

You can create global properties and functions available to all scripts
by using the pre-defined `global` object.

For example,

    global.myMessage = "Hello, World!";
    global.sayHello = function(message)
    {
        global.myMessage = message;
        print(global.myMessage);
    }

In this example, `global.myMessage` and `global.sayHello` can now be
accessed from any other Script in the project.

**Global Properties  
**Please note that in order to properly access `global` properties and
methods assigned in another script, the properties need to be declared
in a script that's already been triggered. To learn more about script
triggering and event ordering, please refer to the [Event
Guide](/guides/scripting/script-events).

## Script Referencing

There may be times when you want a Script to access properties and
functions defined in other Scripts. In these instances, you can make use
of the `api` property.

### The `api` Property

The `api` property is a member property of the Script Component where
you can store references to properties and functions that you'd like to
make available to other Script Components.

In the following Script, `MyMessage.js`, we define a property,
`message`, that we want to make available to other Scripts in the
project.

    // MyMessage.js
    // (Bound to "Initialized" Event)
    //@input string message = "Hello, World!"
    script.api.message = script.message;

![Script
API](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/script_overview_api_my_message.png)

In the following Script, `MyPrinter.js`, we access the property
`message` defined above in `MyMessage.js`.

    // MyPrinter.js
    // (Bound to "Lens Turned On" Event)
    //@input Component.ScriptComponent myMessage
    if(script.myMessage && script.myMessage.api.message)
    {
         print(script.myMessage.api.message);
    }

![Script
API](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/script_overview_api_my_printer.png)

Note that in this example `MyMessage.js` should be bound to the
"Initialized" Lens Event. This is to ensure that the shared property
`message` is defined before `MyPrinter.js` (bound to "Lens Turned On")
is executed.

**Event Order**  
To learn more about the execution order of Lens Events, visit the
[Script Events guide](/guides/scripting/script-events).

### Calling Functions In Other Scripts

You can use the `api` property to access functions defined in other
scripts. 

In the following script, `MyFunction.js`, we define a function
`printHello` that can be accessed from other Script Components.

    // MyFunction.js
    script.api.printHello = function()
    {
        print("Hello!");
    }

In the following script, `MyPrinter.js,` we access the function
`printHello` defined in `MyFunction.js` from a Script Component input
property.

    // MyPrinter.js
    //@input Component.ScriptComponent myFunctionScript
    script.myFunctionScript.api.printHello();

With the scripts ready, we simply need to connect the Script Component
to MyPrinter's Scene Object in the `Inspector` panel, as shown below.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/script_api_inspector.png)

## Scripting Tools

Lens Studio has built-in tools for writing and debugging Scripts. You
can also use an external text editor to write Scripts.

### Logging

See the [Debugging Guide](/guides/scripting/debugging) for information
on logging in Lens Studio or on device.

### Script Editor

Scripts can be edited directly in Lens Studio's  `Inspector` panel.

![Script
Editor](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/script_editor.png)

To edit a script, select a Script from the  `Resources` panel. Once
selected, a preview of the script will populate the `Inspector` panel.
You can modify the text in this preview. Click the `Apply Changes`
button when finished editing to make sure any changes are applied.

### External Editors

Scripts can also be edited using any text editor of your choice.

To open any script in your system's default text editor, double click on
the script in the `Resources` panel. You can also select a script from
the  `Resources` panel, then click `Open External Editor` in the
`Inspector` panel.

![Edit
Script](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/scripting_edit_script.png)

You can also right click on any Script in the  `Resources` panel, and
select `Open`.

-----

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
