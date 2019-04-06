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
  - [3D Software](/guides/3d/3d-software)
  - Cinema 4D, 3D Object Export

# Cinema 4D, 3D Object Export

This guide will walk through how to export a 3D model from Cinema4D to
the FBX format, so that it can be imported into Lens Studio. For the
purposes of this guide we're using [Maxon's Cinema 4D
R17](https://www.maxon.net/en/products/cinema-4d/overview/). That said,
any 3D tool that can export to FBX should be able to export models that
can be imported into Lens Studio.

## Animation Settings

To configure your animation settings in Cinema 4D, select `Edit ->
Project Settings...` from the menu bar.

![Animation
Settings](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_animation_projectsetting.png)

Now you can see your current project settings in the `Attributes`
window.

Leave the `Project Scale` set to `1 Centimeters`.

Change the `FPS` to `30`.

Set the `Minimum Time` to when your animation starts and the `Maximum
Time` to when your animation ends.

![Animation
Settings](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_animation_projectvalue.png)

## Export for Lens Studio

To export an FBX, first select the `File -> Export... -> FBX (*.fbx)`
from Cinema 4D's menu bar. Select where you want to save your FBX then
click `Save`.

![Export
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_exportmenu.png)

This will open the `FBX Export Settings` window. In the `FBX Export
Settings`, set the FBX version to `6.1 (2010)`.

Then, in the `General` section, un-check `Lights`, `Cameras` and
`Splines`.

If you want to export animation with your model, in the `Animation`
section, make sure `Tracks` is checked.

In the `Geometry` section, make sure `Normals` and `Triangulate
Geometry` are checked.

In the `Additional` section, make sure both `Textures and Materials` and
`Embed Textures` are checked.

![Export
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_exportsettings.png)

**Warning  
**Below is a list of things to ensure when exporting your 3D assets to
work best in Lens Studio and ultimately Snapchat.  
• Your model has to be triangulated via the export dialog  
• Your scene total of 3D assets should add up to less than `10,000
triangles (5,000 polys assuming your model is built with quads)`. This
will allow your model to display smoothly across the widest variety of
Android and iPhone devices  
• In general, stay under `100 joints` for your animation rig.
Additionally, while the engine does support Blend Shape animation, try
to avoid using it. If Blend Shapes are required, use sparingly and pay
close attention to your frame rate performance  
• Lens Studio supports up to a `4 bones per vertex` limit. If the
influence is greater than 4 then there will be problems in your rigged
model when imported into Lens Studio

Finally, in the `FBX Export Settings` window, click the `OK` button.

You now have an exported FBX file that's ready to be imported into Lens
Studio. For information on importing 3D models into Lens Studio, review
the [3D Object Import](/guides/3d/3d-object-import) guide.

## Baking Textures for Lens Studio

**Warning**  
Some of the Cinema 4D's shaders, like procedural shaders, are not
compatible with Lens Studio. In order to successfully export your 3D
model you need to bake the texture(s).

To bake textures in Cinema 4D, first select the object you wish to bake
in Cinema 4D's `Objects` window. Then, from the menu bar, select
`Objects -> Bake Texture...`

![Bake
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_objectmenu.png)

This will add the `Bake Texture Tag` to your selected 3D model.

![Bake
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_baketag.png)

Click on the `Bake Texture Tag`. Then in the `Attributes` window select
the `Tag` tab.

Now, you have to choose where you want to save the baked texture(s). To
the right of `Filename` click the `...` button to specify where you want
to save the baked texture file(s).

**Tip**  
We recommend creating a new folder to keep both the baked texture(s) and
FBX file in the same place.

Next, select `PNG` from the `Format` drop down menu.

Change the `Color Depth` to `8 bits per channel`.

Change the `Width` to `1024` and the `Height` to `1024`.

![Bake
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_baketagmenu.png)

Select the `Options` tab. In the `Options` settings, check the `Color`
checkbox then click the `Bake` button.

![Bake
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_bakeoptionsmenu.png)

Once it is finished, you have to apply the baked texture to the 3d
model. In Cinema 4D's menu bar, select `Window -> Material Manager`.

![Bake
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_materialmenu.png)

This will open the `Material Manager` window. Create a new material by
clicking the `Create` button and selecting `New Material`.

![Bake
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_materialwindow.png)

Double click the new material to open `Material Editor` window. To the
left, make sure the `Color` checkbox is checked. Then click `Color`.
With the `Color` settings open, click the `...` button. Select your
exported baked texture.

![Bake
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_materialeditor.png)

Cinema 4D will bring up a window asking you to copy the image to your
project. Click `Yes`.

![Bake
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_materialcopy.png)

Now we have a material with a baked texture. To apply the material to
the model, first select the 3D model. Then navigate to the `Material
Manager` window. Right click on the material with the baked texture and
select `Apply`.

![Bake
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_applymaterial.png)

In the `Objects` menu select the 3d model and delete `Bake Tag`,
`Polygon Selection Tag` and any `Materials` that are no longer used.

![Bake
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_tagsdelete.png)

You now have a 3D model with a baked texture applied to it.

## Baking Animation for Lens Studio

Baking animation is the process of taking complex animation and
simplifying it down to key frames that can be used in Lens Studio. If
your animation is using Mograph, Effectors or XPresso we need to bake
the animation. Otherwise, there is no need to bake the animation.

To bake the animation using XPresso, select your `Mograph Object` from
the `Objects` window. Then, create a copy of your `Mograph Object`.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_firststep.png)

Now you will have two Mograph objects in your scene. Select one of them
and rename it to `xxx_Bake` to make sure that you can easily find it in
the future.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_duplicate.png)

Next, we have to make the `xxx_bake` object editable.

**Warning  
**Before making the object editable, if you're using `Cloner` make sure
that object is not using `Render Instances`. Select the `Cloner`, then
in the `Attributes` window, select the `Object` tab. Make sure `Render
Instances` is NOT checked.

To make the object editable, select the `xxx_Bake` object. Right click
it and select `Make Editable`.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_editableobject.png)

Next, we have to add a `XPresso` tag to the `xxx_Bake` object.

`XPresso` is Cinema 4D's node based scripting editor where you can set
up complex, automated object interactions by drawing lines from one node
to another.

In order to add the `XPresso` tag, select the `xxx_Bake` object. Right
click it and select `CINEMA 4D Tags -> XPresso`.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_xpressotag.png)

This will open the `XPresso Editor` window.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_xpressowindow.png)

Now we need to create a system that will link all of the attributes of
`Mograph Object` to `xxx_Bake` every frame.

Select the `xxx_Bake` object from the `Objects` window and drag the
object into the `XPresso Editor`. Do the same for the `Mograph Object`.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_xpressonode.png)

Then, we need to add nodes to link the attributes of the `MoGraph
Object` to the `xxx_Bake` object.

The first node that we need to add is the `Data` node. The `Data` node
can link the data of one node to the other node. To add the `Data` node,
right click the grid and select `New Node -> Motion Graphics -> Data`.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_datanode.png)

Next, we need to add the `Object Index` node by right clicking the grid
and selecting `New Node -> XPresso -> General -> Object Index`.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_objectindexnode.png)

Next, we need to add the last node which is the `Hierarchy` node. In
order to add the node, right click on the grid and select the `New Node
-> XPresso -> Iterator -> Hierarchy`. The `Hierarchy` node allows us to
access the selected object's children.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_hierarchynode.png)

Each node has an input and an output. The blue square on the top left of
each node indicates the input. The red square on the top right indicates
the output. You can add input or output by clicking on these squares.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_inputoutpu.png)

We need to add an output to our `Mograph Object`. Select the `MoGraph
Object` in the `Xpresso Window`. Click the red square and select
`Object`.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_outputnode.png)

Now, let's add inputs to the `xxx_Bake` object. Select the `xxx_Bake`
object and click on the blue square. Select `Object`. Click the blue
square again and select `Local Matrix`.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_finalnodelook.png)

Next, we need to make connections between the nodes. To connect nodes
together, click an output circle and drag it to an input circle. This
will make a line connecting the two nodes together.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_nodeconnection.png)

Follow the below picture to connect your nodes.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_xpressoconnection.png)

Now both the `Mograph Object` and `xxx_Bake` are linked and ready to be
baked.

To bake the animation, make sure the `xxx_Bake` object is selected.
Then, in Cinema 4D's top menu, select `Character -> Manager ->
Cappucino`.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_cappucinomenu.png)

This will open the `Cappucino` window.

In this window make sure the `Range` is set to `Project` and both `Start
at Current Time` and `Rewind Time` are checked.

Then in the `What` section, check everything that needs to be baked. If
you have moving, scaling and rotating animation, make sure `Position`,
`Scale` and `Rotation` are all checked.

Check the `Hierarchy` checkbox.

**Tip**  
If the animation is not using scale or rotation, make sure to un-check
those. This will make the file size smaller.

**Warning  
**Lens Studio does not support `PLA` (Point Level Animation). Make sure
to un-check the `PLA` checkbox.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_cappucinosettings.png)

With your keyboard, press `Shift + F` to navigate the timeline to the
beginning of the animation.

Press the `Start Realtime` button and then click and hold on the
`Perspective` window.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_holdtobake.png)

You should see the animation playing. Keep holding the left click button
until the animation is done.

When the animation is done playing, delete the `Mograph Object` and any
other effectors that we used in our project. We can also delete the
`Xpresso` tag on the `xxx_Bake` object.

![XPresso
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_c4d_xpresso_deleteunused.png)

We now have a baked animation object ready to be exported as a FBX.

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
