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
  - [Helper Scripts](/guides/scripting/helper-scripts)
  - Tween Manager

# Tween Manager

[Tween.js](https://github.com/tweenjs/tween.js/) is a great Javascript
tweening engine for creating simple programmatic animations. It’s an
open source Javascript library created
by [Sole](https://github.com/sole) and can be easily integrated into
your Lens Studio project. We've created a convenient importable object
that automatically includes Tween.js into your project. Additionally, in
includes a Lens Studio specific wrapper called `TweenManager` and a
number of Lens Studio specific `TweenType` scripts which can be tuned in
the `Inspector` panel. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/tween_example_small.gif)

## Adding the Tween Package

To add the Tween package to your project, select `Add New -> Helper
Scripts -> Tween Manager` in the `Objects` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/T2kuv7A_2_0_0/img/tween_add_object.gif)

You're now ready to tween\!  

**Note**  
The imported package includes some example objects using tweening. To
remove these objects, delete anything labeled `[REMOVE_ME]` in the
`Objects` panel and the `Resources` panel. 

**Note**  
If you're looking for the Legacy Tween package, you can [download it
here](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Tween.lso.zip).
Keep in mind that this version of the Lens Studio Tween package is no
longer officially supported. It's highly recommended that you follow the
instructions above to add the Tween package to your project.

## Adding Tweens

Tweens are added to Scene Objects as [Script
Components](/guides/scripting). These scripts, referred to
as `TweenTypes`, each tween a different set of properties. You can
learn more about the different TweenTypes in the next section.

To add a Tween Type to a Scene Object:

1.  Select an object in the `Objects` panel
2.  In the `Inspector` panel, click `Add Component` and select `Script`
3.  Click `Add Script` and select one of the `TweenType` scripts in the
    `Tween -> TweenTypes` folder
4.  The script should be bound to the `Lens Turned On` event

## Tween Types

Below is a description of each `TweenType` and the `Inspector` settings
used for tuning the tween.

### Tween Transform

The `TweenTransform` type modifies an object's Transform using either
Move, Scale or Rotate. The `TweenTransform` type has a number of
settings that can be configured in the `Inspector` panel. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/TweenTransform.png)

  - **Scene Object - **The object you want to apply the tween to. This
    field allows you to separate your tween tuning from the object
    itself. If this field is left empty, the tween is applied to the
    object that the script component has been added to
  - **Tween Name - **The name of the tween. This is used when scripting
    playback for a tween. Please see the section [Scripting
    Tweens](#scripting-tweens) below for more information
  - **Play Automatically - **When enabled, the tween will start
    automatically
  - **Loop Type - **The type of tween loop. **None** doesn't loop.
    **Loop** plays to the end and then resets to the beginning. **Ping
    Pong** plays to the end and then reverses back to the beginning.
    **Ping Pong Once** plays to the end and then reverses back to the
    beginning, but only once
  - **Type - **The type of transform tweening. Move tweens the
    transform's position, Scale tweens the transform's scale and Rotate
    tweens the transform's rotation
  - **Movement Type - **Indicates how the tween start and end values
    will be specified. From / To specifies both the start and end values
    of the tween. To takes the start value of the tween from the current
    state of the Scene Object, while the end value of the tween is
    specified. From takes the end value of the tween from the current
    state of the Scene Object, while the start value of the tween is
    specified. Offset takes the start value of the tween from the
    current state of the Scene Object and the end value of the tween
    from the start value transformed by the specified offset
  - **Start - **A vec3 that represents the starting values for the tween
  - **End - **A vec3 that represents the ending values for the tween
  - **Time -** The duration of the Tween (in seconds)
  - **Offset - **A vec3 that represents the offset from the tween's
    start value (only available if Offset is chosen as the Movement
    Type)
  - **Additive - **If true while Movement Type is set to Offset and Loop
    Type is set to Loop, the tween will continue to be offset at each
    loop iteration rather than reset to its original start value.
  - **Delay - **How long to wait before starting the tween
  - **Is Local - **If true, the transform is changed in local space. If
    false, the transform is changed in global space
  - **Easing Function - **The easing function for the tween. Available
    easing functions
    are: Linear, Quadratic, Cubic, Quartic, Quintic, Sinusoidal, Exponential, Circular, Elastic, Back
    and Bounce
  - **Easing Type - **The type of easing. Available easing types
    are: In, Out and In / Out

**Tip**                                                                 
                                                                 
The Rotation `TweenTransform` will always choose the shortest angle of
rotation to go from start to end. For instance, if you specify the end
rotation to be 359 degrees greater than the start rotation, then the
tween will appear as though it has rotated one degree. This means that
you cannot rotate more than 180 degrees in a single tween. A workaround
is to define a `TweenChain` to incrementally rotate an object less than
180 degrees at a time until the desired rotation is reached.

### Tween Screen Transform

The `TweenScreenTransform` type modifies an object's [Screen
Transform](/guides/2d/screen-transform). This is useful for tweening a
Screen Transform's position, scale, rotation, or
anchors. The `TweenScreenTransform` type has a number of settings that
can be configured in the `Inspector` panel. Below details the settings
that aren't shared with the [Tween
Transform](/admin/entries/lensStudioGuidesEntries/3963-tween-manager/drafts/84#tween-transform) type.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/TweenScreenTransform.png)

  - **Type - **The type of Screen Transform tweening to perform.  
    *Position - *Tweens the Screen Transform's `position` property  
    *Scale - *Tweens the Screen Transform's `scale` property  
    *Rotation *- Tweens the Screen Transform's `rotation` property (Z
    axis only)  
    *Anchors* - Tweens the Screen Transform's `anchors` property

### Tween Color

The `TweenColor` type modifies an object's color. The object can be
[Text](/guides/2d/text), a [2D Image](/guides/2d/image), or a [3D
Mesh](/guides/3d/3d-object-formats). The `TweenColor` type has a number
of settings that can be configured in the `Inspector` panel. Below
details the settings that aren't shared with the [Tween
Transform](#tween-transform) type.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/tween_color.png)

  - **Color Property** - Specifies the color property to tween.  
    *****Default -* Tweens the object's base color (or Text Fill, if the
    object is Text).  
    *Outline (Text Only)* - If the object is Text, tweens the text's
    Outline color  
    *Drop Shadow (Text Only)* - If the object is Text, tweens the text's
    Drop Shadow color
  - **Start - **A vec4 that represents the starting color for the tween
  - **End - **A vec4 that represents the ending color for the tween
  - **Offset - **A vec4 that represents the offset from the tween's
    start value (only available if Offset is chosen as the Movement
    Type)
  - **Recursive - **If enabled, the color is applied to all child
    objects
  - **Ignore Alpha - **If enabled, the alpha is ignored when the color
    is applied. This allows you to run both a `TweenColor` and a
    `TweenAlpha` together

### Tween Alpha

The `TweenAlpha` type modifies an object's transparency. The object can
be [Text](/guides/2d/text), a [2D Image](/guides/2d/image), or a [3D
Mesh](/guides/3d/3d-object-formats). The `TweenAlpha` type has a number
of settings that can be configured in the `Inspector` panel. Below
details the settings that aren't shared with the above [Tween
Transform](#tween-transform) type.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/TweenAlpha.png)

  - **Start - **A float that represents the starting transparency for
    the tween
  - **End - **A float that represents the ending transparency for the
    tween
  - **Offset - **A float that represents the offset from the tween's
    start value (only available if Offset is chosen as the Movement
    Type)
  - **Recursive - **If enabled, the transparency is applied to all child
    objects

### Tween Billboard (Legacy)

The `TweenBillboard` type allows you to Move, Scale and Rotate a
Billboard object. Billboard objects are unique in that movement and
scaling is controlled via the Billboard's `SpriteAligner` component. The
`TweenBillboard` type has a number of settings that can be configured in
the `Inspector` panel. Below details the settings that aren't shared
with the above [Tween Transform](#tween-transform) type.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/TweenBillboard.png)

  - **Type - **The type of Billboard tweening. Binding Point tweens the
    Billboard's position using the `SpriteAligner` binding point
    parameter, Size tweens the Billboard's scale using the
    `SpriteAligner` width and height parameter and Rotation tweens the
    transform's Z rotation
  - **Start -** A vec2 (or float if Type is set to Rotation) that
    represents the starting values for the tween
  - **End - **A vec2 (or float if Type is set to Rotation) that
    represents the ending values for the tween
  - **Offset - **A vec2 (or float if Type is set to Rotation) that
    represents the offset from the tween's start value (only available
    if Offset is chosen as the Movement Type)

### Tween Value

The `TweenValue` type modifies a generic data value (int, float, vec2,
vec3, or vec4). The value of a `TweenValue` at a certain point in time
can be obtained by calling the
`global.tweenManager.getGenericTweenValue` function (see [Get Generic
Tween Value](#get-generic-tween-value) below). Below details the
settings that aren't shared with the above [Tween
Transform](#tween-transform) type.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/TweenValue_180723_215013.png)

  - **Data Type -** The data type of the value to be tweened (i.e. int,
    float, vec2, vec3, vec4)
  - **Start -** A value (of the data type specified in the Inspector)
    that represents the starting values for the tween
  - **End -** A value (of the data type specified in the Inspector) that
    represents the ending values for the tween

### Tween Chain

The `TweenChain` type plays multiple tweens in sequence or
simultaneously. All tweens specified within a `TweenChain` must
be attached to a single Scene Object. Below details the settings that
aren't shared with the above [Tween Transform](#tween-transform) type.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Tween-Chain.png)

  - **Scene Object - **The object that contains all of the `TweenType`
    script components to be used in this `TweenChain`. This field allows
    you to separate your base tweens from the object itself. If this
    field is left empty, the `TweenChain` will use `TweenType` script
    components attached to the object that the script component has been
    added to
  - **All At Once** **-** If enabled, all specified `TweenType` scripts
    will play simultaneously. If disabled, the specified `TweenType`
    scripts will play in sequential order
  - **Recursive - **If enabled, this `TweenChain` will search the Scene
    Object, along with all of its children, for the tweens specified
    under `Tween Names`
  - **Tween Names** **- **The list of names of `TweenType` scripts,
    attached to Scene Object, to be chained together

**Note**  
When using TweenChain, all `TweenType` Script Components of the names
specified under Tween Names must have Play Automatically disabled.

**Note**  
When using TweenChain, all `TweenType` Script Components specified under
Tween Names must be initialized before this `TweenChain` can be
initialized. Script components with the same script event are
initialized in the order that they appear in the `Objects` panel
hierarchy. If they are on the same Scene Object, they are initialized
based on their order in the `Inspector` panel.

**Note**  
You are allowed to invoke another `TweenChain` within a `TweenChain`.
However, the `All At Once` setting on the first TweenChain will be
applied to any other `TweenChain` that it invokes.

**Tip**  
A `TweenChain` is useful if you would like to change the default
behavior of one of the other `TweenTypes`. For instance, you may want a
delay to only be applied to the start of a looping or ping pong tween
rather than at the start of every cycle. To do this, you may chain two
separate copies of a `TweenType` - the first copy is set to no loop type
with a delay, while the second copy is set to loop or ping pong with no
delay.

**Tip**  
You can use a `TweenValue` to specify a delay within your `TweenChain`
sequence. Simply add its name under `Tween Names` like normal, and the
`Time` that is set on it will be the amount of delay that will occur
inside the `TweenChain`.

## Scripting Tweens

The `TweenManager` includes a number of global helper functions that
allow you to easily control added tweens through script. Scripted tweens
are added in the same way as non-scripted tweens by adding a `TweenType`
as a component. When scripting a tween, make sure `Play Automatically`
is unchecked.

### Start Tween

    global.tweenManager.startTween(SceneObject sceneObject, string, tweenName [, function onComplete, function onStart, function onStop])

The `global.tweenManager.startTween` function takes in an object (that
contains a `TweenType` script), the name of the tween and three optional
callbacks that represent when the tween completes, starts and stops.
When called, it starts the tween. Below is an example of using
`global.tweenManager.startTween` with and without callbacks.

    // -----JS CODE-----
    // @input SceneObject objectWithTweens
    global.tweenManager.startTween( script.objectWithTweens, "box_move" );
    global.tweenManager.startTween( script.objectWithTweens, "box_move_with_callbacks", moveComplete, moveStart, moveStop );
    function moveComplete() 
    {
        // Callback example
    }

### Stop Tween

    global.tweenManager.stopTween(SceneObject sceneObject, string tweenName)

The `global.tweenManager.stopTween` function takes in an object (that
contains a `TweenType` script) and the name of the tween. When called,
it stops the tween. Below is an example of
using `global.tweenManager.stopTween`.

    // -----JS CODE-----
    // @input SceneObject objectWithTweens
    global.tweenManager.stopTween( script.objectWithTweens, "box_move" );

### Pause Tween 

    global.tweenManager.pauseTween(SceneObject sceneObject, string tweenName)

The `global.tweenManager.pauseTween` function takes in an object (that
contains a `TweenType` script) and the name of the tween. When called,
it pauses a tween that is currently playing. Note
that `global.tweenManager.pauseTween` allows a tween to later resume
from the state at which it was paused,
unlike `global.tweenManager.stopTween`. Below is an example of using
`global.tweenManager.pauseTween`.

    // -----JS CODE----- 
    // @input SceneObject objectWithTweens 
    global.tweenManager.pauseTween( script.objectWithTweens, “box_move” );

### Resume Tween 

    global.tweenManager.resumeTween(SceneObject sceneObject, string tweenName);

The `global.tweenManager.resumeTween` function takes in an object (that
contains a `TweenType` script) and the name of the tween. When called,
it resumes a tween that is currently paused. Below is an example of
using `global.tweenManager.resumeTween`.

    // -----JS CODE-----
    // @input SceneObject objectWithTweens
    global.tweenManager.resumeTween( script.objectWithTweens, “box_move” );

### Get Generic Tween Value

    global.tweenManager.getGenericTweenValue(SceneObject sceneObject, string tweenName)

The `global.tweenManager.getGenericTweenValue` function takes in an
object (that contains a `TweenValue` script) and the name of the tween.
Int and float values can be obtained directly from the returned value.
Vec2 values can be obtained with the `x` and `y` properties of the
returned value. Vec3 values can be obtained with the `x`, `y`, and `z`
properties of the returned value. Vec4 values can be obtained with the
`x`, `y`, `z` and `w` properties of the returned value. Below is an
example of using `global.tweenManager.getGenericTweenValue`.

    // -----JS CODE-----
    // @input SceneObject objectWithTweens
    var tweenValue = global.tweenManager.getGenericTweenValue( script.objectWithTweens, “generic_tween” );
    print( tweenValue.toString() );

### Set Start Value

    global.tweenManager.setStartValue(SceneObject sceneObject, string tweenName, newStartValue)

The `global.tweenManager.setStartValue` function takes in an object
(that contains a `TweenValue` script), the name of the tween, and the
start value to be passed in. When called, it manually sets the start
value of the tween. For tweening rotations, the passed-in start value
must be a `quat`. Otherwise, its type must match the type of the `Start`
value of the original `TweenType`. Below is an example of
using `global.tweenManager.setStartValue`.

    // -----JS CODE-----
    //@input SceneObject objectWithTweens
    var newStart = new vec3( 0.0, 0.0, 0.0 );
    global.tweenManager.setStartValue( script.objectWithTweens, "box_move", newStart);

### Set End Value

    global.tweenManager.setEndValue(SceneObject sceneObject, string tweenName, newEndValue)

The `global.tweenManager.setEndValue` function takes in an object (that
contains a `TweenValue` script), the name of the tween, and the end
value to be passed in. When called, it manually sets the end value of
the tween. For rotations, the passed-in end value must be a `quat`.
Otherwise, its type must match the type of the `End` value of the
original `TweenType`. Below is an example of
using `global.tweenManager.setEndValue`.

    // -----JS CODE-----
    //@input SceneObject objectWithTweens
    var newEnd = new vec3( 0.0, 0.0, 0.0 );
    global.tweenManager.setEndValue( script.objectWithTweens, "box_move", newEnd);

### Reset Object

    global.tweenManager.resetObject(SceneObject sceneObject, string tweenName)

The `global.tweenManager.resetObject` function takes in an object (that
contains a `TweenType` script) and the name of the tween. When called,
it resets the object to its start values. Below is an example of
using `global.tweenManager.resetObject`.

    // -----JS CODE-----
    // @input SceneObject objectWithTweens
    global.tweenManager.resetObject( script.objectWithTweens, "box_move" );

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
