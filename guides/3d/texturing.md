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
  - [Texturing](/guides/3d/texturing)
  - Substance Texturing

# Substance Texturing

## Using Substance Painter

Lens Studio supports high quality physically based rendering (PBR).
[Allegorithmic's Substance
Painter](https://www.allegorithmic.com/products/substance-painter) is a
tool built for creating PBR textures. The below guide will walk through
how to configure Substance Painter for Lens Studio use. This allows you
to visualize your model in Substance Painter as it would appear in Lens
Studio and Snapchat. And then, how to export your PBR textures to be
easily loaded into Lens Studio.

### The Mesh

You should import the exact same mesh file into Substance Painter that
you will import into Studio. In order for normal maps to look as
intended, the tangent space on the mesh must match in both packages. 

Up until Lens Studio version 1.7.x, the only way to ensure that the
tangent space will match is to use the .obj file format in both
Substance and Lens Studio. This will force matching mikktspace tangents
to be generated in both packages. From version 2.0, .fbx meshes will
also work correctly.

### New Project, Lens Studio

When creating a new Substance project, use the Lens Studio template.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/substance-lens-studio-template.png)

  

If you are not starting a new project, but have an existing project:

  - Select `Edit -> Project Configuration...` and verify that the
    `Normal map format` drop down is set correctly to `OpenGL`.
    Additionally, make sure the `Compute tangent space per fragment`
    checkbox is checked. 

![Normal Map
Format](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/substance_texturing_edit_normal_map_format.png)

  - Switch the preview shader to the Lens Studio shader in `Window ->
    Views -> Shader Settings`. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/substance-lens-studio-shader.png)

**Warning  
**If you are importing a normal map texture into Substance, you need to
make sure your normal map's `Color space` setting is set to `OpenGL
normal` and not `auto`.  
  
![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/pbr_material_edit_normal_color_space.png)

### Export Textures

To export your textures, go to `File -> Export Textures...`. This will
open the `Export` window. Select `Lens Studio` in the `Config` drop
down. Finally, select your desired export directory and click the export
button.

![Export
Textures](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/substance_texturing_export.png)

This will export three textures that are ready to be added to Lens
Studio.

  - One of the textures is your `Base Texture`

  - Another is your `Normal Map`

  - Finally, the `Material Params Texture` is unique to our engine. It
    is a single texture that represents Metallic, Roughness and Ambient
    Occlusion in the red, green and blue color channels respectively.

## Lens Studio PBR Material

To use your PBR textures in Lens Studio, first import them to the
project by dragging them into your `Resources` panel. Next, create a new
PBR material by selecting `Add New -> Material -> PBR` in the
`Resources` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/LS-new-material.png)

With your new material selected, link all three textures to the
appropriate channels in the `Inspector` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/LS-material-inspector.png)

Now, assign your material to an imported mesh. For more information on
importing meshes, follow the [3D Object
Import](/guides/3d/3d-object-import) guide.

![Mesh](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/substance_texturing_mesh.png)

You now have a high quality PBR material with textures inside Lens
Studio\!

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/substance_texturing_final.png)

### Environment Maps

Environment maps enhance the effect of PBR lighting. If you use the same
environment map in Substance and in Lens Studio, your rendering should
look identical in both packages. Lens Studio uses a particular
environment map by default, but you may choose from several built-in
environment maps, or import your own. 

To import your own environment map, make sure it is an .hdr or .exr
image in latitude/longitude (latlong) format. Simply drag the file to
the resources tab in Lens Studio. Substance uses the same environment
map formats, so you can import the same environment into Substance, and
vice versa.

If you would like to use a built-in environment map, you may choose it
from`Resources -> Add New -> Texture -> Environment Map`

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/LS-marvista.png)

After import, two textures will be generated: a diffuse and a specular
environment map. Select the Envmap light source and replace the textures
with your newly generated diffuse and specular textures.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/LS-envmap-object.png)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/LS-envmap-inspector.png)

### 

### Debugging High Res to Low Res Normal Map Baking

It is notoriously difficult to bake high res to low res normal maps and
have the results match in different software packages. The vertex
normals and tangents must match exactly (see notes at the top of this
document), but sometimes various packages drop the tangents
and calculate their own tangents, or use mikktspace tangents, etc.
DirectX normal maps have the green channel inverted versus OpenGL normal
maps (Lens Studio expects OpenGL format). The normal map baker even
needs to take into account whether the target engine computes tangents
in the pixel shader or in the vertex shader (Lens Studio computes them
in the pixel shader). Having a mismatch anywhere along the line will
cause strange lighting, including seams. We find it useful to validate
the full pipeline with a simple test scene.

The simplest test case is to bake a high res cube with hard normals onto
a low res cube with soft normals. The low res cube with soft normals
lights like a sphere, but once the normal map is baked to it, it will
look like a cube again. It should look like a cube in Substance, and
once it's imported into Studio, it should still look like a cube with
flat sides. If your result looks like a cube in Lens Studio, you can be
confident that your workflow is correct. If the sides of the cube look
warped, revisit all of the points above to find the source of the
mismatch. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/LS-normalmaps.png)

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
