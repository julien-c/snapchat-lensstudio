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

# Release History

## Release Notes

2.0.0

released 2019-04-04

New

  - [Pet Tracking Template](/templates/object/pet) - Track cat and/or
    dog faces to enable experiences made to order for our favorite
    canine and feline companions.
  - [Hand Tracking Template](/templates/object/hand) - Hand tracking
    opens up all new possibilities for interactive Lenses. Use as a
    basic trigger or anchor content to the *Screen Transform* provided.
  - [Body Tracking Template](/templates/object/body) - Body tracking
    provides a bounding-box, ideal for registering content to people
    detected in the camera.
  - [High Score Templates](/templates/interactive/simple-high-score) -
    The High Score templates demonstrate playable experiences built
    inside Lens Studio. They use new capabilities like User Context (for
    displaying the user’s name) and Persistent Storage (for saving a
    high score with the Lens).
  - [Paper Head Template](/templates/face/paper-head) - Attach 2D
    textures to the face that animate in response to facial movements.
  - [Cutout Template](/templates/world/cutout) - Add moveable 2D images
    to the world that cast a shadow.
  - [Landmarker Templates (Beta)](/templates/landmarker) - With new
    Landmarker AR technology, you are able to place 2D and 3D content
    onto a set of real-world landmarks. The templates show you how to
    place 2D planes on the buildings, position 3D objects relative to
    the buildings and even retexture their surfaces.
  - [UI 2.0 Text](/guides/2d/text) - Text component adds support to
    Labels for resizing, word wrap and even dynamic strings – like the
    Snapchat user’s display name – with no scripting required.
  - [UI 2.0 Image](/guides/2d/image) - Image component gives you the
    same familiar ease-of-use as Sprite and adds powerful support for
    pixel-perfect 2D layouts that look great on all devices.
  - [UI 2.0 Screen Regions](/guides/2d/screen-transform) - Screen
    regions are like 2D containers that help you lay out *Text* and
    *Images* exactly as you want them to appear. Helpful presets – Safe
    Render, Full Screen, Capture and Preview – give you easy access to
    perfect Lens UI, unobstructed by Snapchat’s native UI.
  - [UI 2.0 Screen Transform](/guides/2d/screen-transform) - The
    underlying building block for Screen Regions, Text and Images, power
    users and beginners alike can create, customize and even nest Screen
    Transforms to unlock simple-yet-powerful relationships between UI
    elements in the scene hierarchy. Screen Transforms give you total
    control over how your UI elements scale, move and adapt to changes
    in the parent.
  - [UI 2.0 Persistent Storage](/guides/scripting/persistent-storage) -
    Persistent Storage lets you save data related to your Lens
    experience on users’ devices so they can pick up right where they
    left off the next time they launch your Lens. Unlock content, let
    users customize their experience, keep track of high scores…
  - [Live & Capture Render Targets](/guides/general/camera) - Ever
    wanted to put overlays on screen that you don’t want recorded in
    Snaps? With separated Live and Capture render targets you can show
    one thing and record another. You now have the power to give users
    the context they need while still producing beautiful Snaps that
    they’ll want to share. Karaoke, anyone?
  - [Script Behavior System](/guides/scripting/helper-scripts/behavior)
    - If you’re not a pro coder, or just sick of writing boilerplate
    Javascript, the Script Behavior system is for you. It makes adding
    simple but powerful interactivity to your Lens easier than ever by
    providing an intuitive UI right in the inspector panel. No scripting
    or coding required\!
  - [Visual Effects Library](/guides/2d/post-effect) - Check out our
    awesome new materials, each with powerful custom controls, that let
    you create stunning visual effects without needing to worry about
    the details of a shader languages and hardware compatibility.
  - [User Context System](/guides/2d/text) - Request real-time info
    about the Lens user to customize on-screen text, including user
    name, city, altitude, time, weather, temperature, birthday and
    more\!
  - [Device Simulation](/guides/general/previewing-your-lens) - Pop-out
    the preview panel to reveal realistic renders and screen simulations
    from a diverse set of devices. For sponsored Lens creators, you can
    toggle placeholders for the sponsored slug and call-to-action
    attachment button so you can avoid overlapping UI.
  - [Lens Previews](/guides/submission/creating-a-preview-video) -
    Creating an interesting preview so users know what your Lens is all
    about is critical for engagement. Choose from a library of
    pre-recorded videos and images and Lens Preview does the rest,
    applying your Lens, recording a short sample and adding it to your
    project info. And when you want full creative control, you can still
    create your own previews from scratch.
  - [glTF](/guides/3d/3d-object-formats/gltf-import) - Adding to
    our range of supported file types, you can now import glTF files
    directly into Lens Studio.
  - [Optimization
    Tools](/guides/submission/performance-and-optimization) - New
    measurement tools and UI shows your Lens’s size right where you need
    it: on the toolbar. Color coding and tips provide context so you can
    understand the trade-off between adding adding that high-res texture
    and potential impact on user engagement.

Improvements

  - All changes in the public folder are synced with Resources panel
    on-the-fly
  - Improved resources’ undo/redo mechanism

Fixed

  - Various bug fixes and performance improvements

1.7.1

released 2018-12-12

New

  - [Sunglasses Template](/templates/face/sunglasses) - Create custom
    sunglasses\! Simply tune your frame, lenses and reflection
  - [Logo Controller](/guides/2d/logo-controller) - The Logo Controller
    is a new helper script used for placing a logo on the screen. It
    includes preset logo positions, enforces screen safe areas and adds
    padding for Snapchat UI elements

Improvements

  - Added symmetrical mode for Face Liquify

Fixed

  - AudioEffect - Exported objects with the AudioEffect component now
    import properly
  - Animated Textures - Fixed crashes related to importing textures
  - Animation Mixer - Fixed crash on Undo
  - Prefabs - You can now delete imported FBX/OBJ resources
  - Sprites - Fixed crash on sprite duplication
  - Fixed crash after applying prefab with Touch component
  - Fixed visual pivot editor in the inspector of Label component

1.7

released 2018-10-18

New

  - [Marker Template](/templates/marker/marker) - Adds content tightly
    tracked to an image marker. Includes pre-built marker animations
  - [Marker with Snapcode
    Template](/templates/marker/marker-with-snapcode) - Unlock a marker
    experience from a Snapcode. The Snapcode will be tracked until the
    marker is found
  - [Segmentation Template](/templates/face/segmentation) - Replace a
    segment of the camera with an image, tiled image or post effect
    coloring
  - [Face Image Picker Template](/templates/world/face-image-picker) -
    Select a face from your camera roll and add it to an animated world
    object
  - [Label](/guides/2d/text) - Lets you add dynamic text to your Lens
    experience
  - [Audio Effect](/guides/audio-effect) - Add audio effects to your
    Lens that are applied to the audio that the microphone recorded
  - [Segmentation](/guides/general/segmentation) - Segmentation textures
    can be applied to a camera's input to show or hide certain areas of
    the scene
  - [Marker Tracking](/guides/general/tracking/marker-tracking) - Adds
    the ability to track to a unique physical image
  - [Image Picker](/guides/2d/image-picker-texture) and [Face Image
    Picker](/guides/face/face-effects/face-image-picker-texture)
    textures - Allows you to get an image from your device's camera roll
    and use it as a texture
  - [Prefabs](/guides/general/prefabs) - Create reusable Scene Objects
    that share common properties
  - [Pin to Mesh](/guides/3d/pin-to-mesh) - Allows you to attach one
    object to another object's mesh surface
  - [Vertex Animation](/guides/3d/vertex-animation) - Animate the
    individual vertices of an object
  - [Tween System](/guides/scripting/helper-scripts/tween-manager) -
    Tween system integrated into Lens Studio with new features added

Improvements

  - Icon Cropper - You can now easily crop and set your icon background
    color inside Lens Studio
  - 2D Scene, Multiple Object - You can now see and select from multiple
    objects in the 2D scene
  - 2D Scene, Rotation - Simply mouse over a 2D elements corner to
    rotate the object
  - 2D Scene, Snapping - Snap points for 2D tools that can be enabled /
    disabled
  - Template Categories - On the start screen, templates are categorized
  - Unified Manipulator Tool - Translate, Rotate and Scale all at the
    same time
  - FBX Import Options - Options to configure the 3D model import
  - Render Layer Visualization - Small icon in objects panel that
    represents object's render layer
  - Object Panel Views - You can now configure your objects panel to
    sort by render order and by assigned render layers
  - Sprite and Label Pivot - New helper buttons for assigning commonly
    used pivot positions
  - Record Preview - Ability to record a video from the Preview panel
  - Preview Videos - New preview images and videos for testing Marker
    experiences
  - GIPHY Add as Resource - Added ability to add just the resource from
    GIPHY

Fixed

  - Various bug fixes and performance improvements

1.6.2

released 2018-06-19

New

  - [Team Celebrate Template](/templates/face/team-celebrate) - Create a
    Lens for your team\! Simply tune your team's colors and logo

Improvements

  - Default My Lenses window size increased

Fixed

  - Scripts with invalid inputs crashed Lens Studio after preview reset
  - Preview was not working for some projects
  - Video rendering inside Lens Studio for macOS 10.10 and 10.11

1.6.1

released 2018-06-01

Fixed

  - Fixed issue with running on unsupported Windows versions and GPUs
  - Fixed issue with adding video textures
  - Fixed issue with video texture autoplay setting when saving project
    file

1.6.0

released 2018-05-30

New

  - Native AR tracking support. With “Use Native AR” enabled in Surface
    tracking mode, tracking will be enhanced on compatible devices using
    the device’s native AR tracking capabilities, such as ARKit and
    ARCore. Tracking will fallback to Surface for all other devices
  - Camera gizmos in the Scene panel change depending on tracking mode
  - New World Template: Portal
  - New Face Template: Face in Picture
  - Automatic resize of Lens icon when it’s added in Project Info dialog
  - Validation of unsupported audio formats
  - Several new device aspect ratios for Webcam Preview
  - Validation of system requirements before Lens Studio starts. The app
    will show a warning if the system requirements aren’t met.

Improvements

  - More precise Lens size calculation

Fixed

  - Stability fixes for Undo
  - Lens is submitted as new after Save As
  - My Lenses window resizability fix
  - Various Windows stability fixes
  - Various bug fixes and performance improvements

1.5.1

released 2018-04-30

Improvements

  - Optimization of disk space usage

Fixed

  - Various stability improvements on Windows
  - Fixed crash in optimization dialog for disabled objects

1.5

released 2018-04-17

Introducing Face Lenses in Lens Studio\!

New

  - Face Lenses with a collection of Face Templates: Photo, Face Paint,
    Distort, 2D Objects, 3D Objects, Baseball Cap and Trigger
  - New Face effects: Face Mask, Face Stretch, Face Sprite, Face
    Liquify, Face Retouch, Face Binding, Heading Binding and Face
    Texture
  - New World Templates: Particles and Interactive Path
  - Smart Scene Toggle: Switches between 2D Scene and 3D Scene
    automatically based on object selected
  - Particles: A new object type that allows you to create and tune
    particles
  - Add From GIPHY: Add new Face Sprites, World Sprites and Billboards
    using animated resources from Giphy Stickers
  - GIF import: Drag and drop a GIF into the Resources panel to create
    an animated texture
  - Animation Mixer: You are now able to create animation clips and auto
    play the animation
  - Global Lighting: Environment map is stored globally on an Ambient
    Light object. Shadow density can be tuned globally as well on a
    Directional Light object
  - Post Effect Presets: Added a number of Post Effect textures in the
    Resources Panel for easy full screen coloring
  - Webcam Preview: Added the ability to preview your Lens using your
    computer's webcam
  - Preview: New preview images and videos for face
  - Tracking: Added scriptable support for setting a surface tracking
    target for better tracking performance
  - Copy / Paste Component: Components and their settings can now be
    copy and pasted
  - Find Usage: Right click the Resources panel to find the usage of a
    resource in the scene
  - Camera Select: Ability to select which camera the Lens will appear
    on in Project Info
  - Hints: New hints for face support and scriptable hints
  - Updates: Automatic Check for Updates
  - Resources: Added 'Show in Finder/Explorer...' right click option

Improvements

  - Layout: Improved default layout which includes a larger Inspector
    panel
  - Add Object / Component / Resource / Preview Selection UI: The new
    selection prompt is searchable and elements can easily be favorited
  - 2D Scene UI: Various helper buttons and tunable settings moved to
    the button of the 2D Scene panel
  - Template Selection: Categorized by Face and World. Added links to
    each template's tutorial video and documentation
  - 2D Animation: Improved default settings for 2D animation importing
    for better resource optimization

Fixed

  - Various FBX import issues
  - Frame tool selection issues
  - Reset tracking after changing preview video
  - Zoom for orthographic camera
  - Various bug fixes and performance improvements

1.0.1 (Win) & 1.0.2 (Mac)

released 2018-03-02

1.0.2 update fixes an issue with Mac OS X 10.10 Yosemite.

1.0.1 includes a Fullscreen Template that makes it even easier to create
2D experiences, as well as bug fixes for improved stability.

New

  - Check out the new [Fullscreen
    Template](/templates/interactive/fullscreen)\!

Improvements

  - FBX export from popular libraries including Mixamo
  - Added ability to multiselect the whole hierarchy in order to assign
    materials
  - Overall stability and performance

Fixed

  - Mac OS X 10.10 Yosemite issue
  - Non-Latin characters in username and folders no longer cause
    instability on Windows
  - Fixed issues relating to duplicating top-level and empty objects
  - Improved handling of loss of Internet connection
  - 2D screen mode Snapchat UI layout adjustments
  - Restore volume on unmute

1.0.1

released 2018-02-05

This update includes a Fullscreen Template that makes it even easier to
create 2D experiences, as well as bug fixes for improved stability.

New

  - Check out the new [Fullscreen
    Template](/templates/interactive/fullscreen)\!

Improvements

  - FBX export from popular libraries including Mixamo
  - Added ability to multiselect the whole hierarchy in order to assign
    materials
  - Overall stability and performance

Fixed

  - Non-Latin characters in username and folders no longer cause
    instability on Windows
  - Fixed issues relating to duplicating top-level and empty objects
  - Improved handling of loss of Internet connection
  - 2D screen mode Snapchat UI layout adjustments
  - Restore volume on unmute

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
