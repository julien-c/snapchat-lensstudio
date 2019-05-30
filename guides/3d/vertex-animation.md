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
  - [3D](/guides/3d)
  - Vertex Animation

# Vertex Animation

Vertex animation or PLA (Point Level Animation) allows you to animate
the individual vertices of an object. Vertex animation can be useful for
creating complex or simulated animations. For example, it can be used to
create a flag waving animation using cloth simulation. 

Some things to consider when using Vertex Animation:

  - Complex vertex animation can cause performance issues on lower end
    devices. Please pay close attention to your Lens frame rate
  - Because vertex animation is storing keyframes for each vertex,
    vertex animations have a heavy file size. Please pay close attention
    to your Lens size-on-disk
  - Please refer to the [Performance and
    Optimization](/guides/submission/performance-and-optimization) guide
    when working with vertex animation

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_main.gif)

The guides below have exports guides for the following 3D tools:

  - [Maya Export Guide](#maya-export)
  - [Cinema 4D Export Guide](#cinema-export)
  - [3ds Max Export Guide](#3ds-export)

And a guide for importing Vertex Animation into Lens Studio:

  - [Vertex Animation Import Guide](#vertex-import)

## Maya Export Guide

To export from Maya, first we need to define a set of objects that we
want to export as vertex animation. In order to create a set in Maya,
select the objects that have a geometry cache, then select `Create ->
Sets -> Quick Select Set…` from Maya’s menu bar.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_maya_create_set.png)

This will open the `Create Quick Select Set` window. In this window you
can set the name for your objects set. Then, click the `OK` button.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_maya_set.png)

  

Now we are ready to export the Vertex Animation. Select the object(s)
you wish to export in Maya’s `Outliner` window. Then, Select the `File
-> Export Selection...` from Maya’s menu bar.

This will open the `Export Selection` option window.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_maya_export.png)

In the `Export Selections` option window, expand `Animation` options.
Then check the `Animation` checkbox.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_maya_animation.png)

Then expand the `Geometry Cache File(s)` option and check the `Geometry
Cache File(s)` checkbox.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_maya_geometry.png)

Now we need to select the `Set` that we created before in the `Set` drop
down menu.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_maya_cache_select.gif)

You should now be ready to export. Give your file a name then select the
`Export Selection` button.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_maya_finder.png)

**Note**  
To learn more about Maya's export process, refer to the [Maya, 3D Object
Export](/guides/3d/3d-software/maya-3d-object-export) guide.

You now have an exported `FBX` file with a folder in the same path that
contains data for Vertex Animation.

## Cinema 4D Export Guide

To export your own 3D object `PLA` animation we need to make sure that
the animation is cached as keyframes and is not using Cinema
4D's `deformers` or `effects`. Next, select the `File -> Export… -> FBX
(*.fbx)` from Cinema 4D’s menu bar. Select where you want to save your
FBX and click `Save`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_c4d_export.png)

This will open the `FBX Export Settings` window. In the `FBX Export
Settings`, inside the `Animation` section, make sure `Tracks` and `PLA
to Vertex Cache` are checked.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_c4d_export_window.png)

**Note**  
To learn more about Cinema 4D’s export process, refer to the [Cinema 4D,
3D Object
Export](/guides/3d/3d-software/cinema-4d-3d-object-export) guide.

Finally, in the `FBX Export Settings` window, click the `OK` button.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_c4d_finder.png)

You now have an exported FBX file with a folder in the same path that
contains data for Vertex Animation.

## 3ds Max Export Guide

To export from 3ds Max, first we need to create a set of object(s) that
we want to export as vertex animation. To create a set in 3ds Max,
select the object(s), then click `Create Selection Set` from 3ds Max’s
menu bar and give the set a name.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_3ds_click_sets.png)

Now we have a set called `SphereSelectionSet`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_3ds_created_sets.png)

We are now ready to export the `Vertex Animation`. Click on the `3ds Max
icon` in the top left corner and then select `Export`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_3ds_export.png)

Select a path where you want to save your `FBX` file and then in the
`Save as type` drop down menu, select `Autodesk(*.FBX)`. Then, click the
`Save` button.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_3ds_path.png)

This will open the `FBX Export` window.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_3ds_exportwindow.png)

In the `FBX Export` window, click the small triangle to the left of
`Animation` to show the animation options and check the `Animation`
checkbox.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_3ds_created_animationcheck.png)

Then click on the small triangle to the left of `Point Cache File(s)` to
show the options and then, check the `Point Cache File(s)` checkbox.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_3ds_pointcache_checked.png)

Now we need to select the set that we created before in the `Set` drop
down menu.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_3ds_select_set.png)

You should now be ready to export. Click on `OK` button to export.

**Note**  
To learn more about 3ds Max’s export process, refer to the [3ds Max, 3D
Object Export](/guides/3d/3d-software/3ds-max-3d-object-export) guide. 

You now have an exported FBX file with a folder in the same path that
contains data for Vertex Animation.  

## Vertex Animation Import Guide

To import your Vertex Animation make sure you have both a `FBX` and also
a folder with the `XML` and `MC``  (MCX for Maya) ` inside. This folder
should be stored at the same level as your `FBX`. Then, drag and drop
your `FBX` file into the Lens Studio `Objects` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_ls_import.gif)

This will open the `FBX Import Options` window. Make sure `Import Vertex
Animation` is checked. Then, click the `Import` button.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_ls_fbx_import.png)

Once the `FBX` is imported into Lens Studio, you should see it listed in
your `Objects` panel as a new object added to the scene.

In order to check if your object(s) has a Vertex Animation, select the
object. Then, in the `Inspector` panel make sure there is a `Vertex
Animation` component.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation_ls_vertex.png)

To learn how to play the animation please visit the [Playing 3D
Animation](/guides/scripting/playing-3d-animation) guide.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/vertex_animation-main.gif)

## Related Guides

Please refer to the guides below for additional information:

  - [](/guides/3d/3d-object-import)[3D Object
    Import](/guides/3d/3d-object-import)
  - [](/guides/3d/materials)[Maya Export
    Guide](/guides/3d/3d-software/maya-3d-object-export)
  - [](/guides/3d/texturing/substance-texturing)[Cinema 4D Export
    Guide](/guides/3d/3d-software/cinema-4d-3d-object-export)
  - [3ds Max Export
    Guide](/guides/3d/3d-software/3ds-max-3d-object-export)
  - [](/guides/3d/light-and-shadow)[Playing 3D
    Animation](/guides/scripting/playing-3d-animation)
  - [Performance and
    Optimization](/guides/submission/performance-and-optimization)

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
