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
  - Script Events

# Script Events

## Introduction

This guide provides a breakdown of Lens Events available from
the  `Script` component's  `Inspector` panel. Events can be selected
from the event dropdown in the Script Component. Scripts are triggered
by assigning them to these events.

![Script Component
Event](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/script_component_event.png)

*The Script Component's Event selection field*

**Learn More**  
To learn more about how to create scripts and connect them to Lens
Events, please visit the [Scripting
Overview](/guides/scripting/scripting-overview) guide.

## Lens Events

Scripts added to a Script Component can be bound to a number of events
in Lens Studio's `Inspector` panel. We've broken down the events into
four categories: Scene, Camera, Touch and Other.

**Lens Events API**  
For a technical reference of all Lens Events, please visit the [Events
API Reference](/api/Events).

## Scene Events

These events are tied to the timing and execution of the Lens Scene.

-----

**Lens Turned On**

Scripts bound to this event will trigger once when the Lens starts.

*Scripting API*

[TurnOnEvent](/api/classes/TurnOnEvent)

-----

**Frame Updated**

Scripts bound to this event will trigger once on every frame update.
This is handy for running code that changes things over time.

*Scripting API*

[UpdateEvent](/api/classes/UpdateEvent)

-----

**Initialized**

Scripts bound to this event will trigger before any other event in the
Lens (including `Lens Turned On` and `Frame Updated`).

*Scripting API*

This event cannot be bound from script.

-----

## Face Events

These events are triggered based on user face actions (e.g. opening or
closing the mouth, raising eyebrows).

**Brows Frowned**

Scripts bound to this event will trigger when a face's eyebrows are
lowered.

*Scripting API*****

*[BrowsLoweredEvent](/api/classes/BrowsLoweredEvent)*

-----

**Brows Raised**

Scripts bound to this event will trigger when a face's eyebrows are
raised.

*Scripting API*****

*[BrowsRaisedEvent](/api/classes/BrowsRaisedEvent)*

-----

**Brows Returned To Normal**

Scripts bound to this event will trigger when a face's eyebrows are
returned to a neutral pose.

*Scripting API*****

*[BrowsReturnedToNormalEvent](/api/classes/BrowsReturnedToNormalEvent)*

-----

**Face Found**

Scripts bound to this event will trigger when a face enters the video
frame.

*Scripting API*****

*[FaceFoundevent](/api/classes/FaceFoundEvent)*

-----

**Face Lost**

Scripts bound to this event will trigger when a face leaves the video
frame.

*Scripting API*****

*[FaceLostEvent](/api/classes/FaceLostEvent)*

-----

**Mouth Closed**

Scripts bound to this event will trigger when a face's mouth closes.

*Scripting API*****

*[MouthClosedEvent](/api/classes/MouthClosedEvent)*

-----

**Mouth Opened**

Scripts bound to this event will trigger when a face's mouth opens.

*Scripting API*****

*[MouthOpenedEvent](/api/classes/MouthOpenedEvent)*

-----

-----

## Camera Events

These events are triggered when a change is made to the current device
camera.

**Switched To Front Camera**

Scripts bound to this event will trigger once when the camera is
switched to the front (selfie) camera.

*Scripting API*

[CameraFrontEvent](/api/classes/CameraFrontEvent)

-----

**Switched To Rear Camera**

Scripts bound to this event will trigger once when the camera is
switched to the rear (world) camera.

*Scripting API*

[CameraBackEvent](/api/classes/CameraBackEvent)

-----

## Touch Events

These events are triggered user touch gestures. To use these events,
you'll need a Scene Object with a  `Touch` Component. To learn more
about how to use the `Touch` Component, visit the [Touch Input
guide.](/guides/scripting/touch-input)

-----

**Touch Started**

Scripts bound to this event will trigger once when the user starts a
Touch gesture.

*Scripting API*

[TouchStartEvent](/api/classes/TouchStartEvent)

-----

**Touch Moved**

Scripts bound to this event will trigger once every frame while the user
is moving their finger during a Touch gesture (i.e. dragging their
finger).

*Scripting API*

[TouchMoveEvent](/api/classes/TouchMoveEvent)

-----

**Touch Ended**

Scripts bound to this event will trigger once when the user ends a Touch
gesture (i.e. lifts their finger).

*Scripting API*

[TouchEndEvent](/api/classes/TouchEndEvent)

-----

## Other Events

In addition to the selectable events described above, there are many
other events that can be bound in script. To learn more about binding
events in script, please visit the [section
below](#binding-events-in-script).

-----

**Lens Turned Off**

Scripts bound to this event will trigger once when the Lens is exited
(if the user switches to another Lens, or closes the Lens carousel).

*Scripting API*

[TurnOffEvent](/api/classes/TurnOffEvent)

-----

**Delayed Callback**

Scripts bound to this event will trigger after a specified amount of
time. This event can be used as a countdown timer.

*Scripting API*

[DelayedCallBackEvent](/api/classes/DelayedCallbackEvent)

-----

**Late Update**

Scripts bound to this event will trigger every frame after all other
frame update logic is complete.

*Scripting API*

[LateUpdateEvent](/api/classes/LateUpdateEvent)

-----

**Manipulate Start**

Scripts bound to this event will trigger when the user starts a
[Manipulate gesture](/guides/scripting/manipulation).

*Scripting API*

[ManipulateStartEvent](/api/classes/ManipulateStartEvent)

-----

**Manipulate End**

Scripts bound to this event will trigger when the user ends a
[Manipulate gesture](/guides/scripting/manipulation).

*Scripting API*

[ManipulateEndEvent](/api/classes/ManipulateEndEvent)

-----

**World Tracking Restart**

Scripts bound to this event will trigger when the user taps on the
ground to reinitialize [World
Tracking](/guides/general/tracking/tracking-modes).

*Scripting API*

[WorldTrackingResetEvent](/api/classes/WorldTrackingResetEvent)

-----

## Binding Events In Script

You have the option of binding script logic to Lens Events in code, as
opposed to the  `Inspector` panel. There are some Lens Events that are
unavailable in the  `Inspector` panel, making it necessary to bind in
this way.

You can bind a function to a Lens Event as follows:

    function printTime (eventData)
    {
        // Print the elapsed Lens time
        print(getTime().toString());
    }
    // Bind the function printTime to the event UpdateEvent
    var event = script.createEvent("UpdateEvent");
    event.bind( printTime );

In this example, the function `printTime` is bound to the
[UpdateEvent](/api/classes/UpdateEvent) using a
[SceneEvent](/api/classes/SceneEvent).

**Script Event Documentation**  
To learn more about what the Script Component can do with events, visit
the [Script Component API Documentation](/api/classes/ScriptComponent).

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
