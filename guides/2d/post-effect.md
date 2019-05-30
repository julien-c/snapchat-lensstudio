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
  - Post Effect

# Post Effect

Post effects are visual effects that you can apply to the whole screen.
Lens Studio has a number of such built in effects that you can easily
add and modify. Because Color Correction is by far the most commonly
used Post Effect, this guide is broken out into two sections: the [Color
Correction Post Effect](#color-correction) and all of the other [Post
Effects](#post-effect-types). 

## Color Correction Post Effect

The Color Correction Post Effect uses an input color lookup table image
to adjust the coloring of the Lens. Image adjustments (saturation,
exposure, color balance, etc.) are performed in an external editor like
Photoshop and applied to the lookup table. The lookup table is then
imported into Lens Studio and added to a Color Correction Post Effect
object. 

**Tip**  
Lens Studio includes a number of built-in Color Correction textures if
you are unable to create your own. They can be added to your project in
the `Objects` panel by selecting `Add New -> Color Correction`. 

### Download the Color Correction Lookup Table

To make your own custom Color Correction Post Effect, download the below
base lookup table. You'll be making your modifications to this image.

#### [Download the Base Lookup Table](http://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/base_post_effect_lookup_table.png)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/base_post_effect_lookup_table.png)

### Modify the Color Correction Lookup Table

Open the base lookup table image in Photoshop or a similar image editing
tool. You'll be making your adjustments to this lookup image. Add a
reference photo as a layer above the lookup layer. Then, add adjustment
layers above both the reference and the lookup. In the example below,
we've added simple `Hue/Saturation` and `Color Balance` adjustment
layers to give the Lens a pink tone.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/post_effect_adjust.png)

Use your reference layer and the added adjustment layers to tune your
effect.

![Post Effect Matrix
Ref](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/post_effect_ref.png)

Before export, hide the reference layer. Your adjustment layers will
apply to the still visible image lookup table.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/post_effect_hide.png)

Export the lookup image with your newly added adjustments as a PNG.

![Post Effect Matrix
Results](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/post_effect_results.png)

**Warning  
** The Color Correction Post Effect object only supports a
non-compressed PNG. Compressing the PNG or using a JPG will result in
noticeable artifacts.

### Using the Color Correction Lookup Table

To create a Color Correction Post Effect object, press the `Add New`
button in the `Objects` panel. Then, select `Post Effect -> Color
Correction`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_color_correction.png)

<span class="underline"></span>Add your adjusted lookup table texture to
your project by dragging it to the `Resources` panel. Then, in the
`Objects` panel, select your newly added `Post Effect` object and set
its `Main Texture` to the adjusted lookup table texture in the
`Inspector` panel. You should now see your image adjustments applied to
your Lens. You can also tune the intensity of the `Post Effect` with the
`Alpha` slider in the `Inspector` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_color_inspector.png)

**Tip**  
Make sure your Color Correction Post Effect object is listed below
everything you want to colorize in the `Objects` panel.

## Post Effects

### Adding Post Effects

To add a Post Effect select `Add New -> Post Effect` in the `Objects`
panel. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/add_post_effect.gif)

### Adjusting the Post Effect

Post Effects have various parameters that you can adjust in
the `Inspector` panel. First, find the corresponding material for the
added Post Effect in the `Resources` panel. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_object.jpg)

With the corresponding material selected in the `Resources` panel,
you're able to adjust its settings in the `Inspector` panel.   

### Post Effect Types

Below are the available Post Effect types outside of [Color
Correction](#color-correction) and their available tunable params. 

**Analog TV**

Creates a Analog TV effect with tunable noise, distortion and chromatic
aberration.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_analog_tv.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_analog_tv.png)

**Color Gradient**

Adjust the colors in the camera to a gradient defined by four colors.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_color_gradient.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_color_gradient.png)

**Color re-map**

Re-maps the colors in the camera with four separate color mixer colors. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_color_remap.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_color_remap.png)

**Distortion**

Distorts the camera with a tunable distortion texture. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_distortion.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_distortion.png)

**Dithering**

Dithers the screen, either in Color or Greyscale, with a tunable
dithering size. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_dithering.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_dithering.png)

**Edge detection**

Finds edges in the camera and colors them with a tunable outline color. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_edges.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_edge_detection.png)

**Halftone**

Creates a comic book like dot pattern with two tunable colors. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_halftone.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_halftone.png)

**Oil Paint**

Creates a painterly effect applied to the camera with a tunable
intensity. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_oil_paint.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_oil_paint.png)

**Pixelization**

Pixelates the screen and allows you to tune the effect's pixel size. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_pixelization.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_pixelization.png)

**Radial Blur**

Creates a blur centered on a point of the screen.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_radial_blur.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_radial_blur.png)

**Shake**

Shakes the screen with a tunable horizontal and vertical intensity.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_shake.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_shake.png)

**VHS**

Creates a VHS like effect with an animated band. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_preview_vhs.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/post_effect_inspector_vhs.png)

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
