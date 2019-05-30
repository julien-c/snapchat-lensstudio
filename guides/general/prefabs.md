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
  - Prefabs

# Prefabs

When creating Lenses, you may encounter situations that call for the
creation of multiple copies of the same Scene Object. While you could
duplicate the object manually, you might find it inconvenient to update
properties on the individual copies. Prefabs offer a convenient
alternative to this process, allowing you to create reusable Scene
Objects that share common properties.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/object_prefab_grid.png)

The advantage to using a Prefab (rather than duplicating a SceneObject)
is that you can modify the Prefab and immediately apply your changes to
all instances of that Prefab. If you were to simply duplicate the
object, you would have to manually apply any changes to all copies
yourself.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_intro_demo.gif)

Prefabs allow you to:  

  - Instantly propagate changes across several identical SceneObjects
  - Dynamically instantiate Scene Objects via scripting
  - Export and share a Scene Object across different Lens Studio
    projects

This guide will cover how to create, edit, and script with Prefabs, as
well as how to export Prefabs from a Lens Studio project.

## Creating a Prefab

You can create a Prefab from an existing Scene Object in your Lens
Studio scene. To create a Prefab:

1.  In the `Objects` panel, select the Scene Object you want to convert
    to a Prefab
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_create_select_object.gif)

2.  Drag the Scene Object to the `Resources` panel, and release it
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_create_drop_in_resources.gif)

3.  A Prefab Resource with the same name as the Scene Object will be
    created
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_create_resource.png)

**Note  
**You can also create a prefab by right clicking an object in the
`Objects` panel and selecting `Save as Prefab`

The Prefab you create will have the same Components, Transform
properties, and Scene Object hierarchy (children) as the Scene Object
you originally selected.

Note that the original Scene Object you selected has now been converted
to an Instance of the Prefab. This is denoted in the `Inspector` panel
by the addition of three new buttons, which you can see when the Scene
Object is selected:

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_buttons.png)

  - **Highlight**: Selects the Prefab Resource in the `Resources` panel
  - **Apply**: Apply any changes made to a Prefab Instance to the Prefab
    Resource
  - **Revert**: Undo any changes made to a Prefab Instance, reverting to
    the state represented by the Prefab Resource

When you create a Prefab, the following properties will be saved in the
Prefab Resource:

  - Transform properties of every Scene Object in the hierarchy
  - Components and Component properties of every Scene Object in the
    hierarchy

## Using a Prefab

To include a Prefab in your scene:

1.  In the `Resources` panel, select the Prefab Resource you want to add
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_using_select_resource.gif)

2.  Drag the Prefab Resource from the `Resources` panel to the
    `Objects` panel, and release it
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_using_drop_in_objects.gif)

3.  A Scene Object with the same name as your Prefab Resource will be
    added to the Scene, and to the `Objects` panel
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_using_object_created.png)

The Scene Object created will have the same Components, Transform
properties, and Scene Object hierarchy (children) as the Prefab you
selected from the `Resources` panel.

## Applying Changes to a Prefab

One of the key advantages to working with Prefabs is the ability to
apply changes to all instances of a Prefab while editing only one
instance of the prefab.

To apply changes to a Prefab:

1.  Select an instance of the Prefab in your Scene
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_apply_select.gif)

2.  Modify the selected Scene Object or its children
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_apply_modify.gif)

3.  In the `Inspector` panel, select `Apply`
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_apply_button_press.gif)

All instances of the Prefab in your scene will reflect the changes you
made, with the following exceptions:

  - Changes to position of the Prefab’s root Scene Object will only be
    applied to new instances. Existing instances will not change their
    position
  - Changes to rotation of the Prefab’s root Scene Object will only be
    applied to new instances. Existing instances will not change their
    rotation
  - Changes to scale of the Prefab’s root Scene Object will be applied
    to both new and existing instances
  - Changes to position, rotation, and scale of the Prefab’s child Scene
    Objects will be applied to both new and existing instances

## Reverting a Prefab

If you’ve made unwanted changes to an instance of a Prefab, you can undo
them to prevent them from being applied to the Prefab Resource and other
Prefab instances.

1.  Select the Prefab instance you want to revert in the `Objects` panel
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_revert_select.gif)

2.  In the `Inspector` panel, select `Revert` 
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_revert_button_press.gif)

Any changes you made to the Scene Object will be reverted. Its state
should reflect the state of its Prefab resource.

## Highlighting a Prefab

You can find a Prefab instance’s Prefab resource. To do so: 

1.  Select a Scene Object. If it's an instance of a Prefab, you should
    see the `Highlight` button in the `Inspector` panel
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_highlight_select.gif)

2.  Select the `Highlight` button. 
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_highlight_button_press.gif)

3.  The Prefab Resource used to create the Scene Object will be
    automatically highlighted in the `Resources` panel
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_highlight_resource.gif)

## Nesting Prefabs

You can nest object Prefabs to create complex Scene Objects composed of
other Prefabs. The power of nested Prefabs is the ability to compose
reusable Scene Objects that are themselves a collection of reusable
Scene Objects.

### Creating a Nested Prefab

1.  Select a Prefab instance in your Scene
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_nesting_select.gif)

2.  In the `Objects` panel, drag it so that it becomes the child of
    another Prefab instance
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_nesting_parent_child.gif)

3.  Select the parent Prefab instance, and select the `Apply` button in
    the `Inspector` panel
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_nesting_apply.gif)

Now, when you create a new instance of the parent Prefab, you'll see
that it includes an instance of the child Prefab.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_nesting_use.gif)

Any changes you apply to the child Prefab will be reflected in any
instance of the parent Prefab.  

**Tip**  
When applying changes to Nested Prefabs, you may need to press the `Lens
Reset` button in the `Preview` panel to see your changes reflected in
Preview

### Nested Prefab Example

In the example below, we have a Structure Prefab made of a Roof Prefab
and several Pillar Prefabs.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_nested_structure.png)

The Roof object and the Pillar objects are children of the Structure
object. They are *nested* *Prefabs*.  

By nesting the Pillar Prefab under the Structure Prefabs, we can ensure
that any changes we make to the Pillar Prefab will show up in any
instance of the Structure Prefab.  

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_nesting_pillar.gif)

The Pillar Prefab retains independence from its parent,
the Structure Prefab. This allows us to edit and expect to see our
changes in every instance of the Structure Prefab.  

## Scripting with Prefabs

You can instantiate Prefabs with script to create more complex
experiences.  

The following example creates an instance of a Prefab every time the
user touches the screen.

    //@input Component.Camera camera
    //@input Asset.ObjectPrefab myPrefab
    script.createEvent("TouchStartEvent").bind(onTouchStart);
    function onTouchStart(e){
        if(script.camera){
            var touchPosition = e.getTouchPosition();
            var worldPosition = script.camera.screenSpaceToWorldSpace(touchPosition, 200);
            var mySceneObject = createObjectFromPrefab();
            mySceneObject.getTransform().setWorldPosition(worldPosition);
        }
    }
    function createObjectFromPrefab(){
        if(script.myPrefab){
            var instanceObject = script.myPrefab.instantiate(script.getSceneObject());
            return instanceObject;
        }
        else{
            return undefined;
        }
    }

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_scripting_example.gif)

This script makes use of the ObjectPrefab API to instantiate a Prefab
defined by the user in the script's input properties. The key lines to
focus on in the above example is adding the Asset.ObjectPrefab to the
script inputs and then calling instantiate to create the new object. 

    //@input Asset.ObjectPrefab myPrefab
    var instanceObject = script.myPrefab.instantiate(script.getSceneObject());

**Warning**  
Prefabs can contain objects with scripts that will be run when the
object is instantiated. That said, when instantiating prefabs in script,
any script bound to the `Lens Turned On` event within the prefab will
not be run because at that point, the Lens has already been turned on.
If you want a script in a prefab to be run when you instantiate it, make
sure to bind your logic to the `Initialized` event. 

## Sharing Prefabs Across Projects

Prefab resources can be exported and shared across different Lens Studio
projects, like any other Resource.

**Note**  
Changes made to an imported Prefab will not affect the Prefab in the
project from which the Prefab was exported.

### Exporting a Prefab

To export a Prefab:

1.  In the `Resources` panel, select the Prefab you want to export
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_export_select.gif)

2.  Right-click on the Prefab and select `Export`
    
    ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/prefab_export_option.gif)

3.  Select a location to save the `.oprfb` file and select `Save`

### Importing a Prefab

To import a Prefab:

1.  In the `Resources` panel, select `Add New -> Import Files`
2.  Navigate to the location of the `.oprfb` file, select it, and select
    `Open`
3.  The Prefab resource should now be in your `Resources` panel. To add
    it to your scene, you can drag it from the `Resources` panel to the
    `Objects` panel

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
