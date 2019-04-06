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
  - [2D](/guides/2d)
  - Screen Transform

# Screen Transform

The Screen Transform is added to objects that exists in 2D space. These
include [Screen Image](/guides/2d/image) and [Screen
Text](/guides/2d/text) objects. Screen Transform replaces the normal
Transform for these 2D objects. It defines the position, size and
rotation of the 2D object. Beyond that, Screen Transform allows you to
pin 2D objects to edges of the screen and define if the 2D object is
fixed width or fixed height. This is important and useful for creating
UI for your Lenses that adapt to different device resolutions. 

## Device Simulation

Before working with Screen Transform, it's important to understand how
to test your Lens at different device resolutions. To test different
device resolutions, in the `Preview` panel, the dropdown on the bottom
of the panel allows you to simulate a different device's screen
resolutions. When working with Screen Transform, it's recommended to
always test your Lens UI against all of these different device
resolutions. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/st_preview_device.gif)

## <span class="underline"></span>Screen Transform, Basic

By default, Screen Transform opens to the `Basic` tab. The `Basic` tab
allows you to tune if the 2D object is pinned to an edge and if it's set
to fixed width or fixed height. These are relative to the parent's
Screen Transform. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/st_basic_inspect.png)

  - **Pin to Edge - **Anchor the edge of the rectangle to the edge of
    the parent, so that the rectangle’s position is controlled by a
    fixed size padding from that edge
  - **Fix Size - **Lock the size of the rectangle at a fixed world unit
    size. You can lock width and height independently
  - **Position - **When width or height of the rectangle is fixed but
    not pinned, this represents the shared values of Bounds. Controls
    the relative position of the Pivot within the parent rectangle on a
    -1 to 1 scale
  - **Size - **The fixed size of the rectangle, see: Fix Size
  - **Bounds** - The relative position within the parent on a -1 to 1
    scale where this edge should be positioned
  - **Padding** - The fixed distance from a parent edge the edge should
    be positioned when that edge is pinned. See: Pin To Edge
  - **Pivot Position - **The point around which the rectangle should be
    rotated. The (0, 0) point for any child objects

Below are a number of common use cases for different Basic Screen
Transform setups. 

### Example - Pin Corner

In this example, we are pinning a Screen Image to the top left corner of
the screen. This for example would be used for a brand's logo. When
pinned, notice that the offset from the top left corner will be
maintained as the screen resolution changes. Next, the image is set to
both Fix Width and Fix Height. Because of this, notice the pinned
image's width and height remains the same (doesn't shrink or grow) as
the screen resolution changes. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_pin_corner.png)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_pin_corner_example.gif)

### Example - Pin Banner to Top of Screen

In this example, we are pinning a Screen image to the top, left and
right edges of the screen. This for example would be used for a
stretching banner. Because Fix Width is disabled, notice that the left
and right edges of the Screen Image stretch to the changing screen
resolution. But because Fix Height is enabled, the height of the Screen
Image does not change. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_pin_top.png)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_pin_top_example.gif)

### Example - Fixed Width and Fixed Height

In this example, we are placing a Screen Image on the screen and not
pinning it. Because of this, it simply stays in the center of the screen
as you change the screen resolution (does not attach to an edge).
Because Fix Width and Fix Height is enabled, the Screen Image's size
does not change as the screen resolution changes. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_fixed.png)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_fixed_example.gif)

### Example - No Fixed Width or Fixed Height

In this example, we are placing a Screen Image on the screen and not
pinning it. Because of this, it simply stays in the center of the screen
as you change the screen resolution (does not attach to an edge).
Different from the above example, we are not enabling Fix Width or Fix
Size. Because of this, we are allowing the Screen Image to adapt its
heigh and width to the screen resolution. Notice how as you change the
screen resolution, the Screen Image mimics the aspect ratio. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_no_fixed.png)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_no_fixed_example.gif)

## Screen Transform, Advanced

For most Lens Creators, Basic mode will give you all the functionality
you need to create responsive UI. That said, we also offer an Advanced
mode that gives you full control of the Screen Transform's Pivot, Anchor
and Offset. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_advanced_inspector.png)

  - **Position Presets, Set Pivot Position - **When enabled, the Pivot
    Position will be automatically set to the interface's selected
    corner or edge
  - **Position Presets, Set Object Position - **When enabled, the Object
    Position will be automatically set to the interface's selected
    corner or edge
  - **Pivot Position - **The point around which the rectangle should be
    rotated. The (0, 0) point for any child objects
  - **Anchors - **The relative position within the parent on a -1 to 1
    scale where this edge should be positioned
  - **Offset - **After determining the edge positions based on
    Anchors/Bounds, apply these fixed world unit offsets to each edge
    position. Only differs from paddings in that: Paddings assume bounds
    position is -1 or 1, Offset is always positive right negative left,
    paddings are positive towards the center, negative towards the
    outside

### Example - Advanced Corner Pinning

In `Advanced` mode, you're able to lock a Screen Image to the center,
corner or edges of the screen. When `Set Pivot Position` and `Set Object
Position` is enabled, the Screen Image's position and pivot position are
automatically moved to the selected position. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_advanced_corner_pin.gif)

## Screen Transform Hierarchy

All Screen Transform objects need to be a child of either another Screen
Transform or an Orthographic Camera. As you tune a Screen Transform, it
is tuned relative to its parent. So if its parent is another Screen
Transform, it is tuned against the size of that parent Screen Transform.
Or, if its parent is a Orthographic Camera, its tuned relative to the
size of the camera. 

In the below example, we've created two Screen Transforms each pinned to
the top left. Notice that `Screen Image 0` is a child of the camera.
Because of this, it is pinned to the top left corner of the parent
camera's bounds. Now notice that `Screen Image 1` is a child of `Screen
Image 0`. Because of this, `Screen Image 1` is pinned to the top left
corner of `Screen Image 0`. Taking advantage of the Screen Transform
Hierarchy will allow you to create complex and responsive UI. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/st_parent_child_example_large.gif)

## Screen Region

The Screen Region component can be added to an object that's a child of
an Orthographic Camera. When added, it takes over the Screen Transform
and defines its bounds by tunable screen areas. These screen areas adapt
to different device types. By default, when adding a Screen Image or
Screen Text, it includes a Screen Region parent set to `Full Frame`.
With the Screen Region object selected in the `Objects` panel, you can
adjust the `Screen Region` type the `Inspector` panel. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_screen_region.png)

  - **Full Frame - **This region represents the entire area of the
    device
  - **Capture - **This region represents the area shown to the user when
    capturing (recording). On some devices, this region is a subset of
    full frame
  - **Preview - **This region represents the area shown to the user when
    previewing a Snap (post capture). On some devices, this region is a
    subset of the capture region
  - **Safe Render - **This region represents a safe render shown for
    showing UI elements that will always be visible on screen and not
    overlapped by Snapchat UI elements

In the below example, the green rectangle represents the Screen Region
and how it changes on an iPhone X device. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/image_st_safe_render.gif)

## Scripting Screen Transform

Below are some common scripting use cases for modifying Screen Transform
programatically. 

### Position

The script below will set the local position of the Screen Transform
relative to the parent's pivot. 

    // @input Component.ScreenTransform screenTransform
    // @input vec3 position 
    script.screenTransform.position = script.position;

### Scale

The script below will set the local scale of the Screen Transform.

    // @input Component.ScreenTransform screenTransform
    // @input vec3 scale
    script.screenTransform.scale = script.scale;

### Rotation

The script below will set the local rotation of the Screen Transform in
the Z axis. Often for Screen Transform rotation, the only axis that
makes sense to rotate is around the Z. 

    // @input Component.ScreenTransform screenTransform
    // @input float rotation
    var DEG_TO_RAD = 0.0174533;
    script.screenTransform.rotation = quat.fromEulerAngles( 0.0, 0.0, script.rotation * DEG_TO_RAD );

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
