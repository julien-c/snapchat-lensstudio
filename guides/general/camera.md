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
  - [General](/guides/general)
  - Camera and Layers

# Camera and Layers

The `Camera` component is used to display the Scene in a Lens. Each Lens
requires at least one Camera to render the Scene. Cameras will render
everything on the selected `Layers` to the `Render Target`. This guide
will introduce how to add a Camera, the types of Cameras, the Camera
settings and how to work with multiple Cameras and Render Targets. 

## Add a Camera 

You can add a Camera by using `Add New -> Camera` in the `Objects`
panel. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Camera_add_camera.gif)

## Camera Types 

### Perspective Camera

The Perspective Camera simulates how perspective and depth-perception
work in the real world. Objects appear smaller when they are further
away. The Perspective Camera is useful for visualizing 3D models.   

### Orthographic Camera 

The Orthographic Camera does not include perspective distortion.
Parallel lines stay parallel no matter how far away they are. The
Orthographic Camera is commonly used for 2D effects like Screen Image
and Screen Text.  

## Camera Settings 

Select the Camera in the `Objects` panel, then in the `Inspector` panel
under the `Camera` Component, you will see the settings for your
Camera. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/camera_guide_inspector_setting_new.png)

  - **Layers** - The Camera renders all Objects that belong to the
    selected layers
  - **Render Target** - Sets the render output of this Camera to a
    Render Target. More information about Render Target can be found
    below
  - **Render Order **- Controls the render order within the Camera's
    Render Target. The lower the Render Order, the earlier that this
    camera's output texture will be added to the Render Target
  - **Mask Texture** - Sets the opacity mask to apply to the Camera's
    output
  - **Camera Type -** Choose between Perspective and Orthographic using
    the drop-down
  - **Depth Mode** - Choose Between the regular depth mode and
    logarithmic mode

**Note**  
`Regular depth mode` has high depth precision on near objects and low
depth precision on distant fragments. `Logarithmic mode` is the other
way around with higher precision on far objects. Logarithmic mode works
better when rendering scenes with far and big 3D objects

  - **Device Property - **Choose from None, Physical Aspect, Physical
    Fov and All Physical using the drop down. When set to All
    Physical, the Camera will adopt the settings of the mobile device
      - **Aspect Preset** - Controls the aspect ratio of the viewing
        frustum. Choose from the provided device aspects or set your own
        custom aspect 
      - **Field of View **- Perspective Camera Only. The viewing angle
        of the Camera
  - **Size** - Orthographic Camera Only. The height of the viewing box
    of the Orthographic Camera 
  - **Near **- The closest distance the Camera can render  
  - **Far** - The furthest distance the Camera can render 
  - **Clear Color** - If enabled, the Render Target of this Camera will
    be filled by Input Texture if exist or plain color otherwise. Alpha
    is always 1
  - **Clear Depth** - If enabled, depth buffer from previous Render
    Target will be cleared 

## Render Target

A Render Target is the output texture of a single camera or the combined
output of multiple cameras. Each Camera has a Render Target associated
with it and multiple cameras can share one Render Target. You can add a
new Render Target by `Add New -> Texture -> Render Target` from the
`Resources` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/camera_add_render_target_190322_231151.gif)

**Tip   
**For the common use case of having multiple cameras in a defined render
order, it's recommended to have them all output to the same Render
Target for performance reasons. Or put another way, less Render Targets
generally equals better performance

Select the Render Target in the `Resources` panel, then in
the `Inspector` panel, you will see the settings for this Render
Target. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/camera_guide_inspector_render_target_setting.png)

  - **Input** - The input texture of this render target. It can be the
    Device Camera Texture, an image or another Render Target
  - **Clear Color** - If enabled, the Render Target will be filled with
    input texture if exist or plain color otherwise. Alpha is always 1.
    When `Clear Color` is enabled in the Camera setting, it will
    override the Render Target setting
  - **Clear Depth** - If enabled, depth buffer from previous Render
    Target will be cleared. When `Clear Depth` is enabled in the Camera
    setting, it will override the Render Target setting
  - **Depth Buffer** - Choose from Auto, ForceOn and ForceOff. ForceOn
    will force depth buffer available for this Render Target while
    ForceOff turns it off
  - **MSAA** - Turns on multisample anti-aliasing if enabled
  - **Use Screen Resolution** - Sets to the device's screen resolution
    if enabled 

**Tip**  
For the Render Target to render on top of the mobile device's camera
feed, use the `Device Camera Texture` as the Input of the Render Target.

## Scene Config

The `Scene Config` panel allows you to set the Live Target, the Capture
Target and quickly rearrange the camera render order. If you are in the
default panel layout, the `Scene Config` panel is next to the
`Resources` panel. You can also add the `Scene Config` panel by
selecting ` Windows -> Panels -> Scene Config  `from the main menu bar. 

### Live Target and Capture Target

Live Target sets the output Render Target that users will see in the
live camera and during recording in Snapchat. Capture Target sets the
output Render Target of the actual recorded snap. This is handy when you
have UI elements or hints in the Lens that you want to hide in the final
recorded snap, but still be present during the recording. Check out the
[Soundboard Template](/templates/interactive/soundboard) for an example
of using the Capture Target and Live Target fields. 

You can set the `Live Target` and `Capture Target` in the `Scene Config`
panel. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/camera_guide_set_live_target.gif)

**Tip**  
In the `Preview` panel, you can toggle the `Capture Mode` option under
the `Show UI` options. Refer to the [Previewing Your
Lens](/guides/general/previewing-your-lens) guide for more information. 

**Note **  
Lenses that don't have different content in live camera vs. post
capture will have their `Capture Target` and `Live Target` fields set
to the same Render Target.  

In the `Scene Config` panel, you can drag the order of the camera's
within a Render Target. You can also drag a camera to a different Render
Target which will reassign the camera's `Render Target` field. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/camera_guide_scene_config.gif)

## Layers 

### Assigning Layers

Understanding how `Layers` work is important to working with Cameras.
For any object, you can choose the Layer which it will be rendered on by
defining its Layers in the `Inspector` panel. You can also add a new
Layer by clicking `Add New`. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/camera_and_layers_inspector_panel.gif)

**Note**  
Layer is only relevant to objects with visual Components such as
MeshVisual and Image.  

### Camera's Layers

In a Camera's settings, all Objects that belong to the selected Layers
will be rendered to the selected Render Target. For example, if Cube A
is on Layer 1 and Cube B is on Layer 2. And, Camera A's Layers is set to
solely Layer 1. Then, Cube B will not be rendered in Camera A's render
target texture. 

### Layer Mode

In the `Objects` panel, you can switch to `Layer Mode` to view scene
objects in your project in different layers. This is helpful if you are
working with multiple cameras and render layers and you want a clear
understanding of how each layer looks.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/camera_and_layers_layer_mode.gif)

You can also customize the color and name of each render layer. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/camera_and_layers_change_color_and_name.gif)

## Multiple Cameras 

You can have multiple Cameras in the Scene. A common use case would be a
Perspective Camera for 3D objects and an Orthographic Camera for Screen
Images. In this use case, the separate cameras should share the same
Render Target and the order should render the Perspective Camera before
the Orthographic Camera.

For more complex use cases, you can chain multiple Cameras together by
using the Render Target of one camera as the Input to another Camera's
Render Target. For example if you use Camera A's render target as Input
to Camera B's Render Target, Camera B will render its layers on top of
Camera A's output texture. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/camera_guide_chain_input.gif)

## Examples of Switching Cameras in Script

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/camera_toggle.gif)

We can also set and change Render Layers of Cameras in `Script`. Below
is an example of how to toggle between two Cameras in Script using
Render Layers.  

In your scene, create a second camera by selecting  ` Add New -> Camera
 ` in the `Objects` panel. Then, make sure the new Camera's Render
Target is set to the same as the original camera's Render Target. Both
cameras should now render to the Lens, one before the other. 

Next, this script below enables and disables the default render layer
based on the toggle checkbox in the Inspector. Bind this to
`Initialized` Event, link the two Cameras and each time you press the
toggle checkbox you should see it reflected in the preview window.   

    // -----JS CODE-----
    // @input Component.Camera cameraA
    // @input Component.Camera cameraB
    // @input bool toggle
    if( !script.toggle ) {
        removeAllRenderLayers( script.cameraA );
        removeAllRenderLayers( script.cameraB );
        script.cameraA.addRenderLayer( 0 );
    }
    else {
        removeAllRenderLayers( script.cameraA );
        removeAllRenderLayers( script.cameraB );
        script.cameraB.addRenderLayer( 0 );
    }
    function removeAllRenderLayers( camera )
    {
        var renderLayers = camera.getAllRenderLayers();
        for( var i = 0; i < renderLayers.length; i++ ){
            camera.removeRenderLayer( i );
        }
    }

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
