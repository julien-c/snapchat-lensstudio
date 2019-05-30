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
  - [Tracking](/guides/general/tracking)
  - Tracking Modes

# Tracking Modes

This guide walks through the various tracking modes Lens Studio offers
for world experiences.  

## Device Tracking

The `Device Tracking` component allows you to place objects in your Lens
Studio experience that will be locked to the world. When run in
Snapchat, the content will appear in front of you at the start of the
Lens. The `Device Tracking` component has three modes:

  - **Rotation**: Users can rotate their phone and have the objects stay
    locked relative to their orientation. Users will not be able to walk
    towards, away from or around the content
  - **Surface**: Users are able to walk towards, away from and around
    the content, in addition to being able to rotate their phones. When
    Surface is selected, you have the option to also enable `Use Native
    AR`. With `Use Native AR` enabled, the device's native AR tracking
    capabilities will be utilized to enhance tracking
  - **World: **Users are able to walk freely through the scene without
    focusing on a surface. This mode solely relies on the device's
    native AR tracking capabilities and falls back to a Rotation
    experience if native AR tracking is not available. For most use
    cases where you want to take advantage of native tracking, we
    recommend instead using `Surface` with `Use Native AR` enabled
    because it will fallback to Surface if native tracking is
    unavailable

**Note**  
`Surface` mode tracking works best when content is scaled roughly human
size or less. For anything bigger, consider enabling `Use Native AR` as
well which will utilize the device's native tracking capabilities if
available. When `Surface` mode is enabled, content in your scene is
attached to the ground. Surface mode does not understand or detect walls
or obstacles (like a couch or coffee table).

### Adding Device Tracking

To add `Device Tracking`, first select the `Camera` object in the
`Objects` panel. Then, in the `Inspector` panel click the `Add
Component` button and select `Device Tracking`.

![Tracking
Modes](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/tracking_modes_world_tracking_component.gif)

When `Device Tracking` is enabled, you'll see a green grid in your
`Scene` panel indicating that `Device Tracking` is turned on. Any object
in the scene will now be attached to the world.

### Choosing Device Tracking Mode

By default, `Surface` mode is used in the `Device Tracking` component.
To change this, in the `Inspector` component, press the `Tracking Mode`
drop down and select an option.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/tracking_modes_change_mode.gif)

### Using Surface Mode

Surface mode is useful for when you want to allow users to walk up to
your content, as well as walk around it. For experiences that encourage
the user to more freely walk around (like a portal) or for larger
content, consider enabling `Use Native AR` which will utilize the
device's native tracking capabilities if available. 

### Positioning Object in Surface Mode

When you use `Surface` tracking mode, `Manipulation` can be added to any
object allowing the user to move, rotate and scale objects. To add
`Manipulation` follow the [Manipulation](/guides/scripting/manipulation)
guide.

![Tracking
Modes](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/tracking_modes_world_tracking_grid.png)

For an example of the `Device Tracking` component in-use, please refer
to the [Static Object Template](/templates/world/static-object).

### Choosing Tracking Point in Surface Mode

As you move your object around on a surface, the further it gets from
the origin the less stable the tracking can become. Telling the Device
Tracking system what the tracking target should be can
significantly help this. Each time you start your lens you can reset
the device tracker's target with a very simple script. Create a new
script named SetSurfaceTrackingTarget.js and add below to the contents.

    // -----JS CODE-----
    // @input Component.DeviceTracking deviceTrackingComponent
    function onSurfaceReset(eventData)
    { 
        if(script.deviceTrackingComponent) 
        { 
            script.deviceTrackingComponent.surfaceTrackingTarget = script.getSceneObject(); 
        }
    }
    var worldTrackingResetEvent = script.createEvent("WorldTrackingResetEvent");
    worldTrackingResetEvent.bind(onSurfaceReset);

With the object you want to be the tracking target selected, add a new
`Script` Component and set it to the SetSurfaceTrackingTarget script.
Make sure the event dropdown is set to `Initialized`. This object will
now be the device tracker's target.  

### Using Rotation Mode

`Rotation` mode takes the device's gyroscope rotation and applies it to
whatever object it is added to. The primary use case for the `Device
Tracking` component with `Rotation` mode is to have the scene's camera
rotation be driven by the device's gyroscope. This will allow you to
place content all around the user in 3D space and give the user the
ability to freely look around the scene. It is useful for when you want
to surround the user with content, but not necessarily walk towards it. 

For an example of `Rotation` mode in-use, please refer to the [Look
Around Template](/templates/world/look-around).

## Marker Tracking

The `Marker Tracking` Component allows you to track content to images in
physical space. An ideal use case for [Marker
Tracking](/guides/general/tracking/marker-tracking) is a Lens that
overlays content on a real poster or mural.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/VKgkU8_1_7_0/img/marker_guide_intro.gif)

To learn how you can add Marker Tracking to a Lens, visit the
[Marker Tracking](/guides/general/tracking/marker-tracking) guide. You
can also try out the [Marker Template](/templates/marker/marker) and
[Marker with Snapcode Template](/templates/marker/marker-with-snapcode)
to get started with Marker Tracking right away.

## Object Tracking

Object Tracking allows you to attach images and animations to certain
objects found in the scene. Object Tracking currently supports the
detection and tracking of a Cat, Dog, Cat and Dog, Hand and Body. Each
Object Tracking type offers various Attachment Points to attach content
to. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/object_tracking_cat_example.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/object_tracking_hand_example.gif) ![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/object_tracking_body_example_sm.gif)

To learn how you can add Object Tracking to a Lens, visit the [Object
Tracking](/guides/general/tracking/object-tracking) guide. You can also
try out the [Pet Template](/templates/object/pet), [Hand
Template](/templates/object/hand) and [Body
Template](/templates/object/body) to get started with Object Tracking
right away.

## Camera Attached

You can attach an object to the camera. This is great for simulating a
first person object (For example: a magic wand pretending to be in the
user's hand). To do this, in the `Objects` panel, drag the object you
want to be attached to the camera to be a child of the `Camera` object.

![Tracking
Modes](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/tracking_modes_camera_attach.gif)

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
