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
  - Maya, 3D Object Export

# Maya, 3D Object Export

This guide will walk through how to export a 3D model to the FBX format,
so that it can be imported into Lens Studio. For the purposes of this
guide, we're using [Autodesk's
Maya 2016](https://www.autodesk.com/products/maya/overview). That said,
any 3D tool that can export to FBX should be able to export models that
can be imported into Lens Studio.

## Animation Settings

Before exporting to FBX we have to make sure that we are using the
correct project settings so we can successfully import the 3D model into
Lens Studio. To see the project settings, first select `Windows ->
Settings/Preferences -> Preferences` from Maya's menu bar.

![Export
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_object_export_pref.png)

This will open the `Preferences` window. In the left side categories,
select `Settings`.

Then, under `Working Units` select the `Time` drop down menu and select
`NTSC (30 fps)`. This will change the scene's frame rate to 30 FPS.

![Export
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_object_export_prefwindow.png)

Finally, press the `Save` button.

Now we're ready to export the 3D model.

## Export for Lens Studio

To export a FBX from Maya, first select the object(s) you wish to export
in Maya's `Outliner` window. Then, select the square to the right of
`File -> Export Selection...` from Maya's menu bar. This will open the
`Export Selections` options window.  

![Export
Selection](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_object_export_selection.png)

In the `Export Selections` options window, expand `General Options`.
Then, select `FBX` in the `File type` dropdown.

![FBX
Type](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_object_export_fbx_type.png)

Then, in the `Export Selections` options window, click the `Export
Selection` button.

![Export Selection
Button](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_object_export_selection_button.png)

When exporting a FBX, Maya will bring up the `FBX Exporter` options
window. Here, you're given a number of options for defining the type of
FBX export.

Expand `Embed Media` and verify that the `Embed Media` checkbox is
checked.

![Embed
Media](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_object_export_embed_media.png)

### Triangulate, Tangents and Binormals

3D models imported into Lens Studio must be triangulated. In Maya, you
can triangulate your mesh by checking `Triangulate` in the FBX Export
settings under `Geometry`. Also check `Tangents and Binormals`.

![Triangulate](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_object_export_triangulate_rev.png)

**Note   
**`Split per-vertex Normals` will be used to transfer hard edge
information to Lens Studio. If your 3D model has hard edges please make
sure to check the `Split per-vertex Normals` checkbox.

### Animation Settings

If you want to export animation with your model, make sure the
`Animation` checkbox is selected. In Maya 2016, the following settings
should be selected under the `Animation` section of the FBX export
settings before exporting:

  - `Animation` to unlock animation settings
  - `Deformed Models`, `Skins` and `Blend Shapes` under `Deformed
    Models`
  - `Constraints` and `Skeleton Definitions` under `Constraints`

![Animation
Settings](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_anim_settings.png)

**Warning**  
Below is a list of things to ensure when exporting your 3D assets to
work best in Lens Studio and ultimately Snapchat.  
• Your model has to be triangulated via the export dialog  
• Tangent and Binormals must be enabled in the export dialog  
• Your scene total of 3D assets should add up to less than `10,000
triangles (5,000 polys assuming your model is built with quads)`. This
will allow your model to display smoothly across the widest variety of
Android and iPhone devices  
• In general, stay under `100 joints` for your animation rig.
Additionally, while the engine does support Blend Shape animation, try
to avoid using it. If Blend Shapes are required, use sparingly and pay
close attention to your frame rate performance  
• Lens Studio supports up to a `4 bones per vertex` limit. If the
influence is greater than 4 then there will be problems in your rigged
model when imported into Lens Studio

You should now be ready to export. In the `FBX Exporter` options window
select the `Export` button.

![Export
Button](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_object_export_button.png)

You now have an exported FBX file that's ready to be imported into Lens
Studio. For information on importing 3D models into Lens Studio, review
the [3D Object Import](/guides/3d/3d-object-import) guide.

## Preparing Multiple Animation Layers

**Note   
**If your 3D model does not have multiple animations you can skip this
section.

Lens Studio supports 3D models with multiple animation. The [Interactive
Tap Template](/templates/interactive/interactive-tap), [Interactive
Approach Template](/templates/interactive/interactive-approach)
and [Interactive Look At
Template](/templates/interactive/interactive-look-at) all support
multiple animations for the interactions. These animations should be in
separate `Animation Layers` in Maya so that Lens Studio recognizes each
individual animation.

Animation layers hold keyframe data of the animation in your scene. For
example, the model we are exporting has an Idle animation and a Jump
animation. In Maya, these separate animations both exist in
the `BaseAnimation` layer by default. We need to assign each individual
animation to different animation layers. 

Before creating our animation layers, we have to make note of the frame
ranges that correspond to each animation.

For example:

  -  The Idle animation takes up frames 1 - 95
  -  The Jump animation takes up frames 95 - 200

Then, open the `Outliner` window by selecting `Windows -> Outliner` from
Maya’s menu bar.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_layer_Outliner.png)

Next, select all the joints and controllers that contains animations
(keyframes), in the `Outliner` window.

**Tip  
**You can collapse a hierarchy in Maya by holding `Shift` and clicking
the `+` button.

Next, we need to bake the animation. Baking the animation
will automatically create an animation layer for you.

Select the square to the right of `Edit -> Keys -> Bake Simulation` from
Maya’s menu bar. This will open the `Bake Simulation Options` window.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_layer_bake.png)

In the `Bake Simulation Options` window, set the `Time Range` to `Start
/ End` to unlock the time range settings. Now in the `Start Time` field
specify the time that your animation starts and in the `End Time` field
specify the time when your animation ends. 

For example if the Idle animation starts at frame 1 and ends at frame
95, we have to put 1 in the `Start Time` field and 95 in the `End
Time` field.

Next, make sure the `Bake To` is set to `New Layer` and that the `Baked
Layers` drop down menu is set to `Keep`.****

Now we are ready to bake the animation by clicking on the `Bake` button
in the `Bake Simulation Options` window.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_layer_bakewindow.png)

You should now have a newly baked animation in the `Anim` tab in Maya.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_layer_rename_171205_200555.gif)

After baking all of the animations and creating anim layers for them, we
need to make sure all of our animations start at frame 0 in the
timeline.  

**Note  
**When animation plays in the Lens Studio it will be playing the
animation from frame 0.

In order to move all the keyframes of animation layers to start at
frame 0, first select all the joints and controllers that contain
animations in the `Outliner` window.

Then we need to `Mute` all of the `Animation Layers` besides the
animation layer that we want to move to frame 0.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_layer_mutelayer_171205_200618.gif)

Next, we can select all of the keyframes that are showing in Maya’s
`Timeline` by holding the `Shift` key. Then, click and drag from the
start time of your animation to the end time of the animation in the
`Timeline` panel.   

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_animation_export_layer_timeline_171205_200634.gif)

Finally, move the keyframes to frame 0 by clicking and dragging the
selection to frame 0 in the `Timeline`.   

Repeat the same process above so that all anim layers start at frame 0.
For information on playing back your animations, please refer to the
[Playing 3D Animation](/guides/scripting/playing-3d-animation) guide. 

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
