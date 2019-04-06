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
  - Custom Script UI

# Custom Script UI

**Tip**  
This is an advanced scripting feature. If you aren't already familiar
with scripting properties, please first see the [Scripting
Overview](/guides/scripting/scripting-overview) guide.

Custom UI can be used to control how your script properties appear in
the `Inspector` panel. This is configured by adding a json string after
your normal `@input` property declaration. For example:

Normal input declaration:

    //@input vec3 myColor

Input with custom UI:

    //@input vec3 myColor {"widget":"color"}

## General UI Controls

![Label and
hints](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/custom_ui_global.png)

These are optional controls that work on `@input` properties and `@ui`
widgets.

  - **"label"** - Overrides the text label displayed
  - **"hint"** - Sets a hint message to appear on mouse hover
  - **"widget"** - Specifies the widget used for drawing (see below)

<!-- end list -->

    //@input string string1 = "hello" {"label":"String #1"}
    //@input int number1 {"label":"Number (1.0)", "hint":"This is a number variable"}

  - **"showIf"** - Sets a property name to control the element's
    visibility

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/custom_ui_showif.gif)

    //@input bool useColor
    //@input vec3 myColor {"widget":"color", "showIf":"useColor"}

  - **"showIfValue"** - Used with "showIf", sets a required value for
    the element to be visible (defaults to `true`)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/custom_ui_showifvalue2.gif)

    //@input string inputMode {"widget":"combobox", "values":[{"label":"float", "value":"float"}, {"label":"vec3", "value":"vec3"}, {"label":"color", "value":"color"}]}
    //@input float floatVal {"showIf":"inputMode", "showIfValue":"float"}
    //@input vec3 vec3Val {"showIf":"inputMode", "showIfValue":"vec3"}
    //@input vec4 colorVal {"widget":"color", "showIf":"inputMode", "showIfValue":"color"}

## Input Widgets

Widgets can make dramatic changes to how `@input` properties are drawn.
Each widget works with a certain set of property types, so make sure
your property type is supported by the widget.

### **Color**

![Color
pickers](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/custom_ui_color_picker.png)

A color picker for `vec3` and `vec4` properties.

    // RGB (red, green, blue)
    //@input vec3 myColor = {1,0,0} {"widget":"color"}
    // RGBA (red, green, blue, alpha)
    //@input vec4 colorWithAlpha = {1,1,1,.5} {"widget":"color"}

### **Spinbox**

![Spinbox](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/custom_ui_spinbox.gif)

The default widget for `int` and `float` properties.

  - **"min"** - Minimum allowed value
  - **"max"** - Maximum allowed value
  - **"step"** - Amount added when clicking the up and down buttons

<!-- end list -->

    //@input int myInt {"label":"My Int", "min":0, "max":25, "step":5}
    //@input float myFloat {"label":"My Float", "min":0.0, "max":1.0, "step":0.001}

### **Slider**

![Slider](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/custom_ui_slider.gif)

Draws a draggable slider that interpolates between two values. This
works with `int` and `float` properties.

  - **"min"** - Minimum allowed value
  - **"max"** - Maximum allowed value
  - **"step"** - Smallest increment allowed between min/max

<!-- end list -->

    //@input int intSlider {"widget":"slider", "min":0, "max":10, "step":1}
    //@input float floatSlider = 0.5 {"widget":"slider", "min":0.0, "max":1.0, "step":0.01}

### **Combo Box**

![Combo
Box](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/custom_ui_combobox.gif)

Shows a dropdown menu with a list of selectable options. This works with
`string`, `int`, and `float` properties.

  - **"values"** - List of options in the combo box. Each option is a
    json object formatted as follows:
      - **"label"** - How this option appears in the drop down menu
    <!-- end list -->
      - **"value"** - The value returned in script if this option is
        selected

<!-- end list -->

    //@input int radius {"widget":"combobox", "values":[{"label":"one", "value":1}, {"label":"two", "value":2}]}
    //@input string animalType {"widget":"combobox", "values":[{"label":"cat", "value":"cat"}, {"label":"dog", "value":"dog"}, {"label":"bird", "value":"bird"}]}

Here's a breakdown of the json strings being used in this example.
Remember that each UI element is defined in a single line, so this
expanded version is only for readability and won't work as is.

    {
        "widget": "combobox",
        "values":
        [
            {"label": "one", "value": 1},
            {"label": "two", "value": 2}
        ]
    }
    {
        "widget": "combobox",
        "values":
        [
            {"label": "cat", "value": "cat"},
            {"label": "dog", "value": "dog"},
            {"label": "bird", "value": "bird"}
        ]
    }

## UI Widgets

UI widgets are purely for visual organization and decoration, since
unlike `@input` properties they won't provide values to your script.
They are created by starting a line with `//@ui`. For example:

    //@ui {"widget":"label", "label":"Hello"}

### **Label**

![Label](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/custom_ui_label.png)

Draws a line of text. Useful for titles, warnings and descriptions.

    //@ui {"widget":"label", "label":"Color Controls"}
    // Empty label, adds empty space
    //@ui {"widget":"label"}

### **Separator**

![Separator](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/custom_ui_separator.png)

Draws a horizontal line for separating content.

    //@ui {"widget":"separator"}

### **Group**

![Group](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/custom_ui_group.gif)

Creates a collapsible group that hides or shows all content inside. Use
a `"group_start"` widget to begin the group, and a `"group_end"` widget
to end it. Any `@input` or `@ui` between the two will become part of the
group.

    //@ui {"widget":"group_start", "label":"My Group"}
    // inner content...
    //@ui {"widget":"group_end"}

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
