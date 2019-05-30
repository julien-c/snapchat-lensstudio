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
  - 2D Animation

# 2D Animation

Lens Studio allows you to import a sequence of textures or animated GIFs
for 2D animations. The texture sequence is converted to an optimized
sprite sheet and can be used as a texture asset in your project.
Playback can be controlled by enabling `Always Play` or scripting when
and how often the animation plays.

## Importing 2D Animations

Lens Studio supports both image sequence and GIF importing for 2D
animations. 

### Importing GIFs

Simply drag and drop your GIF file into the `Resources` panel. Lens
Studio will automatically create a new animated texture resource from
the GIF in the `Resources` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/cMAtrJAagEmjazjB_Internal/img_new/2d_animation_gif_import.gif)

### Importing Image Sequences

Since your Lens will be used on a mobile device, it is important that
the content is optimized.

  - Images should be saved in JPEG format, unless they contain
    transparency, in which case you need to use PNG
  - Avoid duplicated frames
  - Try to keep the resolution of your frames as low as possible

Go to the `Resources` panel and select `Add New -> Texture -> 2D
Animation From Files` and select the image sequence you want to use for
your animation. An image sequence is a series of separate image files
that make up an animation. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/cMAtrJAagEmjazjB_Internal/img_new/2d_animation_add_new_animated_files.png)

### Configuring Animation Sprite Sheets

Once you select all your images in the image sequence, a new window will
pop up that allows you to configure the resulting sprite sheet(s) of
your animation. The window has a number of parameters described below.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/cMAtrJAagEmjazjB_Internal/img_new/2d_animation_image_sequence_import.png)

#### Files count

`Files count` configures the number of sprite sheets your animation
frames will be distributed across. If you have 100 frames and you use 2
as the `Files count`, each sprite sheet texture will have 50 frames.

**Note  
** A lower number will give better performance, but will display the
frames at a lower resolution because each sprite sheet texture is capped
at a maximum size.

#### Single texture maximum size

This configures the maximum resolution of each sprite sheet that will be
generated for the animation.

**Warning  
** A single texture size should never be greater than 2048 x 2048
pixels.

#### Animation density

Generally, this will be left at the default `Keep every 1 frame`, but it
can be used to uniformly decrease the number of frames used in the
animation.

For example, if `Keep` is selected and 5 is entered, every fifth frame
will be used in the animation. If instead `Remove` is selected and 4 is
entered, every fourth frame will be removed from the animation.

#### Crop

This specifies the region of each frame that will be used in the
animation. This is useful for cutting off empty space around the edges
of sprites. If `Autodetect` is enabled, Lens Studio will automatically
find an optimal region to use.

#### Format Settings

Sprite Sheets should be saved in JPEG format unless they contain
transparency, For optimization purposes, only export as PNG if your
images contain transparency.

The quality of the file (0 - 100) controls the strength of compression.
Lower quality means more compression and a smaller file size.

### OK

Clicking `OK` will automatically create a new `animation` resource
derived from the image sequence in the `Resources` panel.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/cMAtrJAagEmjazjB_Internal/img_new/2d_animation_animation_saved.png)

## Configuring the 2D Animation Resource

Select the newly imported animation resource. In the `Inspector` panel
you will see the animation settings for your animation resource. You can
preview the animation in the `Inspector` panel by clicking the `Play`
button.

#### Always Play

`Always Play` sets the animation to repeat indefinitely. For simple
animation playback, enable this.

**Note  
** If you want it to only play at certain times, you can write a
customized script. You can find more info below. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/cMAtrJAagEmjazjB_Internal/img_new/2d_animation_inspector_settings.gif)

#### Reverse

`Reverse` plays the animation backwards.

#### Ping Pong

`Ping pong` alternates between playing the animation forward and
backward.

**Tip  
**You can check multiple boxes. For example, `Always Play` and `Reverse`
will play your animation backwards indefinitely.

### Using 2D animation as Texture

Now your 2D animation can be used the same way as other 2D static images
in Lens Studio. 

One common use case will be using the animated texture on an `Image`
or `Screen Image` object. Adding a new `Screen Image` is detailed in
the [Image](/guides/2d/image) guide. This imported animation can now be
used in the `Texture` field of a newly created `Screen Image`.

### Scripting Animation Playback

For more complex animation control beyond `Always Play` you'll have to
write a script. 

An example script for animation playback is shown below. It should be
added to the Image or `Screen Image` object. Bind it to the event when
you want the animation to play. For more information about scripting,
refer to the [Scripting Overview
Guide](/guides/scripting/scripting-overview).   

    var myAnimation = script.getSceneObject().getFirstComponent("Component.SpriteVisual");
    var loops = 1;
    var offset = 0.0;
    myAnimation.getMaterial(0).getPass(0).baseTex.control.play(loops, offset);

Set loops to -1 to tell the animation to loop indefinitely. Any other
number represents the number of times the animation should loop. For
more information about scripting a 2D animation, see the
[AnimatedTextureFileProvider](/api/classes/AnimatedTextureFileProvider)
scripting API reference.

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
