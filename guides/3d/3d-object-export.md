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
  - 3D Object Export

# 3D Object Export

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/3d_object_export_softwares.png)

## Introduction

For 3D models, Lens Studio supports the FBX export format which can be
generated by many 3D tools.

When exporting the FBX format we have to make sure that we are using the
correct settings so we can successfully import the FBX into Lens Studio.
Below is the list of requirements to keep in mind when exporting models
for Lens Studio and Snapchat.

  - Meshes must be triangulated. Either manually triangulate the mesh or
    do it automatically through your 3D tool's export settings
  - Meshes need to have a UV map and texture for use in Lens Studio.
    Lens Studio currently does not support vertex coloring. In order to
    import vertex color to Lens Studio, you need to bake your vertex
    coloring as a texture
  - The models in your scene should optimally not exceed 10,000
    triangles (5,000 polys assuming your model is built with quads). If
    it does, you'll have to play close attention to your frame rate. For
    more information, see the [Performance and
    Optimization](/guides/submission/performance-and-optimization) guide
  - If you want to add additional detail to your model, it is
    recommended to use a normal map texture. Please refer to the
    [Materials](/guides/3d/materials) guide and the [Substance
    Texturing](/guides/3d/texturing/substance-texturing) guide to learn
    more about materials and textures for Lens Studio
  - For animation, configure your tool's time unit to be 30 FPS (frames
    per second)

If you make your 3D objects in Autodesk’s Maya, Maxon’s Cinema 4D,
Blender or 3ds Max, you can follow the in-depth guides listed below to
export your models for use in Lens Studio.

**Note   
**Lens Studio does support the OBJ file format; however, this format
lacks support for animation. We recommend, if you're creating your own
models, to use FBX which the below export guides focus on. The OBJ
format is great to use when downloading models from sources
like [Sketchfab](https://sketchfab.com/) and
Google's [Poly](https://poly.google.com/). Please refer to the [OBJ, 3D
Object Import](/guides/3d/3d-object-formats/obj-3d-object-import) guide
for more information.

## Software Export Guides

### [Maya Export Guide](/guides/3d/3d-software/maya-3d-object-export)

### [Blender Export Guide](/guides/3d/3d-software/blender-3d-object-export)

### [Cinema 4D Export Guide](/guides/3d/3d-software/cinema-4d-3d-object-export)

### [3DS Max Export Guide](/guides/3d/3d-software/3ds-max-3d-object-export)

## Related Guides

Please refer to the guides below for additional information:

  - [3D Object Import](/guides/3d/3d-object-import)
  - [Materials](/guides/3d/materials)
  - [Substance Texturing](/guides/3d/texturing/substance-texturing)
  - [Photoshop Texturing](/guides/3d/texturing/photoshop-texturing)
  - [Light and Shadow](/guides/3d/light-and-shadow)

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
