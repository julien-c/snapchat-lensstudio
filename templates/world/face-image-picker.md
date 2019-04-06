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

  - Face
      - [Paper Head](/templates/face/paper-head)
      - [Sunglasses](/templates/face/sunglasses)
      - [Segmentation](/templates/face/segmentation)
      - [Team Celebrate](/templates/face/team-celebrate)
      - [Face in Picture](/templates/face/face-in-picture)
      - [2D Objects](/templates/face/2d-objects)
      - [Distort](/templates/face/distort)
      - [Face Paint](/templates/face/face-paint)
      - [Photo](/templates/face/photo)
      - [Baseball Cap](/templates/face/baseball-cap)
      - [3D Objects](/templates/face/3d-objects)
      - [Trigger](/templates/face/trigger)
      - [Cricket Helmet](/templates/face/cricket-helmet)
  - World
      - [Cutout](/templates/world/cutout)
      - [Face Image Picker](/templates/world/face-image-picker)
      - [Static Object](/templates/world/static-object)
      - [Animated Object](/templates/world/animated-object)
      - [Particles](/templates/world/particles)
      - [Portal](/templates/world/portal)
      - [Picture Frame](/templates/world/picture-frame)
      - [Look Around](/templates/world/look-around)
      - [Window](/templates/world/window)
  - Interactive
      - [Simple High Score](/templates/interactive/simple-high-score)
      - [High Score](/templates/interactive/high-score)
      - [Soundboard](/templates/interactive/soundboard)
      - [Fullscreen](/templates/interactive/fullscreen)
      - [Interactive Tap](/templates/interactive/interactive-tap)
      - [Interactive Path](/templates/interactive/interactive-path)
      - [Interactive
        Approach](/templates/interactive/interactive-approach)
      - [Interactive Look
        At](/templates/interactive/interactive-look-at)
  - Marker
      - [Marker](/templates/marker/marker)
      - [Marker with Snapcode](/templates/marker/marker-with-snapcode)
  - Object
      - [Pet](/templates/object/pet)
      - [Hand](/templates/object/hand)
      - [Body](/templates/object/body)
  - [Landmarker (Beta)](/templates/landmarker)
  - [Beginner Templates](/templates/beginner-templates)

<!-- end list -->

  - [Templates](/templates)
  - [World](/templates/world)
  - Face Image Picker

# Face Image Picker

The Face Image Picker Template allows you to put faces from your phone’s
camera roll on any object as a texture. The Face Image Picker
automatically detects any faces in the phone’s camera roll, crops them
and then applies the selected face to an object. The template includes a
3D face model that can be easily attached to and positioned on a
character.

## Tutorial

## Guide

### Add Your Custom Object

To import your custom 3D object select the `Add New -> Import Files`
from the `Resources` panel. If you're new to Lens Studio check out the
[Static Object](/templates/world/static-object) or [Animated
Object](/templates/world/animated-object) templates for adding 3D
content to Lens Studio. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/face_image_picker_import.gif)

After importing your content, it will appear in the `Objects` panel.
Drag and drop your content so that it is a child of
the `FaceImagePickerController [EDIT_ME]` object. Once your custom
content is added, you can delete the template’s placeholder content
labeled with `[REPLACE_ME]`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/face_image_picker_parent.gif)

### Included Face Mesh

This template comes with a ready to use face mesh with the Face Image
Picker functionality. Face mesh is included in the project as a prefab
which can be found under the`FaceMeshPrefab` folder in the `Resources`
panel. The prefab is named `FaceMesh [POSITION_ME]`.  

**Note**  
A prefab is a copy of a scene object (and its children) as a Resource.
For more information about Prefabs, reference the
[Prefabs](/guides/general/prefabs) guide.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/face_image_picker_prefab.png)

To use the Face Mesh prefab in Lens Studio, drag the prefab from the
`FaceMeshPrefab` folder in the `Resources` panel to be a child of the
`FaceImagePickerController [EDIT_ME]` object in the `Objects` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/face_image_picker_prefab_drag.gif)

### Align the Included Face Mesh

You can now position, scale and rotate the `Face Mesh [POSITION_ME]`
object to be aligned with where the face should go in your custom
content. If your custom content is animated, simply drag the included
face mesh to be a child of one of the animation’s bones. The custom mesh
will then animate with the parent bone. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/face_image_picker_move.gif)

### Custom Face Mesh

You can use the provided Face Mesh in Lens Studio which is already UV
mapped to the Face Image Picker texture. Alternatively, you can also
create your own custom 3D face and UV map it to the Face Image Picker
texture. If you are creating your own custom mesh, reference the below
images for creating your UV map. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/face_image_picker_uv_1.png)

### Linking the Custom Face Mesh

When using a custom mesh with the Face Image Picker, you need to assign
the `face_image_picker` material to the mesh. Select your custom 3D mesh
in the `Objects` panel. Select `Choose Material` in the `Inspector`
panel. In the material selection window, find the `face_image_picker`
material in the `Material` folder. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/VKgkU8_1_7_0/img/face_image_picker_choose_material.gif)

### Previewing Your Lens

You’re now ready to preview your Lens experience. To preview your Lens
in Snapchat, follow the [Pairing to
Snapchat](/guides/general/pairing-to-snapchat) guide.

## Related Guides

Please refer to the guides below for additional information:

  - [Face Image Picker
    Texture](/guides/face/face-effects/face-image-picker-texture)
  - [Image Picker Texture](/guides/2d/image-picker-texture)
  - [Creating an Icon](/guides/submission/creating-an-icon)
  - [Configuring Project
    Info](/guides/submission/configuring-project-info)
  - [Submitting Your Lens](/guides/submission/submitting-your-lens)
  - [Sharing Your Lens](/guides/sharing/sharing-your-lens)

  

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
