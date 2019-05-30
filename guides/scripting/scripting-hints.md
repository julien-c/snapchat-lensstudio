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
  - [Scripting](/guides/scripting)
  - Scripting Hints

# Scripting Hints

Adding Hints is a great way to teach users how to interact with your
Lens. Common Hints include "Open Your Mouth", "Look Around", "Try Rear
Camera" and more. A single hint can be easily added to a Lens by setting
the `Main Hint` in the `Project Info` window. This is explained in the
[Lens Hints](/guides/submission/lens-hints) guide. This only works if
you want to show a single hint at the beginning of the Lens. For more
complex hint use (like multiple hints or showing a hint on trigger), you
need to script the hint. This guide first walks through an importable
helper script used for showing hints that's tuned in the `Inspector`
panel. It then walks through how you can script Hints on your own for
even more complex use cases. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Hints_ScreenRecording.gif)

## Adding the Hints Package

Add the Hints package to your project by following these steps. 

1.  Download the [Lens
    Hints](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/files/Lens-Hints.zip) package
2.  Unzip the downloaded package
3.  Open your project in Lens Studio
4.  Drag and drop the `Lens Hints [EDIT_ME].lso` ( just downloaded )
    into the `Objects` panel
5.  You should see the `Lens Hints [EDIT_ME]` object appear in
    your `Objects` panel

Now you can add Hints to your Lens\!   

## Adding Hints

The Lens Hints package you just downloaded has two Hints added. In
the `Inspector` panel, you will see two `Script` Components under the
`Lens Hints [EDIT_ME]` Object. The `ShowHints.js` is bound to a specific
`Event`. The Hint will be displayed when the event is called.

For example, in this case, "Open Your Mouth" will be displayed with user
switches to the front camera.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Hints_Inspector.png)

You can add more Hints by adding a Script Component and selecting
`ShowHints.js` in the Scripts folder in the Resources panel.
Alternatively, you can also drag and drop the `ShowHint.js` from the
Resources Panel to the Inspector Panel. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/cMAtrJAagEmjazjB_Internal/img_new/scripting_hints_add_hints.gif)

**Note**  
You will not see the actual Hint message in Lens Studio. The Hint will
only appear when you preview your Lens on your device. For debugging
hints in Lens Studio, a print statement like "Showing Hint:
lens\_hint\_open\_your\_mouth" will be displayed in the `Logger` panel. 

## Hint Settings 

The `ShowHints.js` script has a number of settings that can be
configured in the `Inspector` panel. 

  - **Hint Id - **The hint to show. A drop down of all available hints
  - **Show Time - **The number of seconds that the hint message will be
    displayed
  - **Delay Time - **The number of seconds to wait before showing the
    hint after the Event is triggered
  - **Show Once - **If enabled, the hint will only show once. If not,
    the hint will be displayed every time the Event gets triggered

**Note**  
Hints will continue to display when users are recording snaps. However,
in the resulting Snap, the hint message will not be visible

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Hints_GIF.gif)

## Script Your Own Hints 

You can also script your own `Hints` directly instead of using the above
package. For hints to work, you need to first create a `Hints` Component
in Script.

    var hintComponent = script.getSceneObject().createComponent( "Component.HintsComponent" );

You can control the Hints Component by using the
methods `showHint(hintID, showDuration)` and `hideHint(hintID)`. HintID
is an ID that references a specific Hint string. Here is a list of
supported HintIDs: 

    lens_hint_aim_camera_at_the_sky
    lens_hint_blow_a_kiss
    lens_hint_blow_a_kiss_voice_changer
    lens_hint_come_closer
    lens_hint_do_not_smile
    lens_hint_do_not_try_with_a_friend
    lens_hint_draw_with_your_finger
    lens_hint_find_face
    lens_hint_find_image
    lens_hint_find_marker
    lens_hint_find_snapcode
    lens_hint_kiss
    lens_hint_kiss_again
    lens_hint_look_around
    lens_hint_look_down
    lens_hint_look_left
    lens_hint_look_right
    lens_hint_look_up
    lens_hint_make_some_noise
    lens_hint_move_your_head
    lens_hint_nod_your_head
    lens_hint_now_kiss
    lens_hint_now_open_your_mouth
    lens_hint_now_raise_your_eyebrows
    lens_hint_now_smile
    lens_hint_open_your_mouth
    lens_hint_open_your_mouth_again
    lens_hint_open_your_mouth_voice_changer
    lens_hint_pick_a_face
    lens_hint_pick_a_photo
    lens_hint_pick_an_image
    lens_hint_raise_your_eyebrows
    lens_hint_raise_your_eyebrows_again
    lens_hint_raise_eyebrows_or_open_mouth
    lens_hint_raise_your_eyebrows_voice_changer
    lens_hint_rotate_your_phone
    lens_hint_say_something
    lens_hint_smile
    lens_hint_smile_again
    lens_hint_smile_voice_changer
    lens_hint_swap_camera
    lens_hint_tap_a_surface
    lens_hint_tap_ground_to_place
    lens_hint_tap_surface_to_place
    lens_hint_tap_ground
    lens_hint_tap
    lens_hint_tilt_your_head
    lens_hint_try_friend
    lens_hint_try_rear_camera
    lens_hint_turn_around
    lens_hint_voice_changer
    lens_hint_walk_through_the_door

Example of Scripting Hints: 

    hintComponent.showHint("lens_hint_tap", 3);
    hintComponent.hideHint("lens_hint_tap");

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
