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
  - [3D Object Formats](/guides/3d/3d-object-formats)
  - OBJ, 3D Object Import

# OBJ, 3D Object Import

Lens Studio supports importing the OBJ file format for 3D models. The
OBJ file format supports 3D geometry and texture but does not support
animation. Generally speaking, if you're exporting your own models, it's
recommended to use the FBX format by following our [3D Object
Export](/guides/3d/3d-object-export) guides. 

For models that are downloaded from other
sources, like [Sketchfab](https://sketchfab.com/) and
Google's [Poly](https://poly.google.com/), it's recommended to use the
OBJ format for the highest compatibility. 

Please refer to the [Performance and
Optimization](/guides/submission/performance-and-optimization) guide for
3D model performance requirements. 

## Import OBJ into Lens Studio

To import an OBJ, select `File -> Import...` from the menu bar.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_object_import_file_menu.png)

Select the OBJ you wish to import. You can also drag and drop your OBJ
into the `Resources` panel.

Once the OBJ is imported into Lens Studio, you should see it listed in
your `Objects` panel as a new object added to the scene. It will also
appear in your `Scene` panel, where it can be manipulated. Finally, your
model resource will now be available in the `Resources` panel as well.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/3d_object_import_new_object.png)

**Warning  
**If your OBJ fails to import, check the `Logger` panel for an import
error message.

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