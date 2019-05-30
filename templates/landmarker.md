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
  - Landmarker (Beta)

# Landmarker (Beta)

The Landmarker Template allows you to create unique Lens experiences at
selected locations around the world. Similar to Marker Tracking,
Landmarker Tracking tracks the specified physical location's landmark.
The template shows you how to utilize Landmarker tracking to create a 3D
experience tightly tracked to the location's architecture. It also
includes debug features that allow you to test your Lens without
actually being at the location. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_example_snap.gif)

**Warning**  
It is not recommended to utilize the Landmarker Templates for
a sponsored experience because it requires users to use the Lens at the
Landmarker's physical location, thus limiting the number of people that
can experience the campaign.

## Locations 

Landmarker Tracking is currently available at five locations around the
world. 

  - Buckingham Palace in London, UK
  - Eiffel Tower in Paris, France 
  - Flatiron Building in NYC, US
  - TCL Chinese Theater in Los Angeles, California, US
  - US Capitol in Washington, D.C., US

Each location has a corresponding template. Select the Landmarker
template for the location where you want to base your Lens. In the
following guide, we'll use the Eiffel Tower Landmarker Template. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_template_homescreen.png)

## Preview Landmarker Lens 

In the Preview panel, select the Location Tracking preview video for
your chosen Landmarker. If you don't see the preview videos, flip the
camera to back camera. These preview selections provide the tracking
data needed to simulate the experience of being at the location.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_guide_preview_video.png)

The template also comes with debug features that allow you to preview
your Lens with more control, which will be explained in detail later in
this guide.   

## 3D Reference Model

Each Landmarker template comes with the 3D reference model of the
Landmarker's architecture. You can download a reference model (FBX) for
each Landmarker location below:

  - [](%7Basset:7071:url%7D)[Buckingham Palace in London,
    UK](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/files/Buckingham-Palace.fbx.zip)
  - [](%7Basset:7070:url%7D)[Eiffel Tower in Paris,
    France ](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/files/Eiffel-Tower.fbx.zip)
  - [](%7Basset:7073:url%7D)[Flatiron Building in NYC,
    US](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/files/Flatiron-Building.fbx.zip)
  - [](%7Basset:7072:url%7D)[TCL Chinese Theater in Hollywood,
    California](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/files/TCL-Chinese-Theater.fbx.zip)
  - [US Capitol in Washington, D.C.,
    US](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/files/US-Capitol.fbx.zip)

**Warning  
**The reference 3D model is built to align with the real Landmarker's
physical features. For correct alignment, make sure not to scale or
offset the mesh in your Scene  

## Adding Content

You can create your unique Landmarker Lens by adding your own 2D and 3D
content.

### 2D and 3D Content 

First, import your 2D or 3D assets into Lens Studio. Drag them under
the  `Eiffel Tower [PLACE_CONTENT_HERE]` and position it relative to
the Landmarker reference model. The template comes with a few example
assets to choose from. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_add_3d_asset.gif)

You can download the Landmarker reference model and import it to your
preferred 3D software for more precise content creation. 

### Graffiti/Custom Textures

By default, the reference model is used as an `Occluder` for your
content. You can also apply custom textures onto the building to create
a graffiti design, coloring effect, or entirely new look for the
Landmarker.

### Reference Textures

You can find the base textures of the reference models below.

  - [](%7Basset:6805:url%7D)[](%7Basset:6805:url%7D)[Buckingham Palace
    in London,
    UK](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/files/buckingham_palace_base_tex.jpg)
  - [](%7Basset:6804:url%7D)[Eiffel Tower in Paris,
    France ](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/files/eiffel_tower_base_tex.jpg)
  - [](%7Basset:6803:url%7D)[Flatiron Building in NYC,
    US](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/files/flatiron_building_base_tex.jpg)
  - [](%7Basset:6813:url%7D)[](%7Basset:7064:url%7D)[TCL Chinese Theater
    in Hollywood,
    California](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/files/tcl_chinese_theatre_base_tex.jpg)
  - [](%7Basset:6814:url%7D)[US Capitol in Washington, D.C.,
    US](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/files/us_capitol_base_tex.jpg)

You can also import the reference model to your preferred texturing
software to create custom textures.  

### Import Textures

Import your textures into Lens Studio. If you are only updating the base
texture, click on the `LandmarkerController` Scene Object. In the
Inspector panel, under Building Mode, select Custom Textures and add
your custom base textures.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_import_texture.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_change_texture.gif)

**Note**  
If you want to use a different material or have more control over the
material setting, you can modify or replace the material on the
reference model `MeshVisual` directly. Make sure you still select the
`Custom Textures` option for the Building Mode in the `Inspector` panel
to ensure `LandmarkerController` script is not overwritten that
setting. 

## LandmarkerController

`LandmarkerController` is the main script that controls the Landmarker
template. You can view its properties in the `Inspector Panel` by
selecting the `LandmarkerController[EDIT_ME]` SceneObject.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_landmarkerController_inspector.png)

### Building Mode

The Building Mode controls how the Landmarker model looks.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_building_semi_mode.gif)

  - **Occluder**: the reference model will not be visible and will
    occlude other visuals behind it
  - **Semi-transparent**: the reference model will be colored in
    semi-transparent red color 
  - **Custom Textures**: the reference model will keep its current
    material and use the custom texture as its base texture 
  - **None**: the reference model will be disabled 

## Debug Mode

Debug Mode can be used to preview the Landmarker Lens without having to
be at the physical location. You can unlock Debug Mode by scanning the
default Lens Studio Image Marker. In the Preview panel, select the Image
Marker Preview Video and you will enter Debug Mode automatically.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_switch_to_debug_mode.gif)

The `Building Mode` property found in the `LandmarkerController` Debug
Settings controls how the reference model looks in Debug Mode. It does
not change how it will look in the actual Lens experience. 

There are two types of Debug Mode: Full Size and Birds Eye. 

### Full Size Mode

Full Size mode teleports you into a first-person Debug Scene that
simulates physical distance and scale. You can use the navigation UI to
move around the Landmarker. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_full_size_mode_navigation.gif)

You can set the starting position of the camera by moving the ` Default
Debug Camera Position [Move Me]  `SceneObject. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_default_debug_cam_pos.png)

There are two types of Camera Mode in Full Size Debug Mode. `Gyro` is
useful when you want to test the Lens on your device. You can look
around the scene and check out different angles.    

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_gyro_recording.gif)

The ` Look At Distance Target  `Camera Mode is useful if you are testing
your Lens using the Preview panel. This will make the Camera always look
at the Distance Target. You can move the Distance Target in the 3D Scene
panel to set up the desired camera angle. For example, in the Eiffel
Tower template, it can be handy to move the Distance Target higher up to
check out the top of the tower. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_set_distance_target.gif)

### Birds Eye Mode

Birds Eye mode places the entire 3D scene on the Image Marker. This
creates the effect of having a miniature scene you can physical
manipulate. You can toggle between Full Size Mode and Birds Eye mode
using the toggle button. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_toggle_debug_mode.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_birds_eye_recording.gif)

## HintController

The `HintController` script controls all the different hints that guide
users when playing with a Landmarker Lens. You can view its properties
by selecting the `HintController` Scene Object in the `Inspector Panel`.

### Loading 

When the Lens starts, a loading hint is displayed. You can change the
Landmarker graphic to your own 2D image by first importing it to Lens
Studio and selecting it in the `Inspector Panel`. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_loading_hint.gif)

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_update_hint_texture.gif)

### Go To Hint

The `Go To Hint` is displayed if the user is too far away from the
Landmarker. You can change the hint texture as well as the text hint in
the `Inspector Panel`. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_go_to_hint.gif)

### Point At Hint

The `Point At Hint` is displayed when the user is close enough to see
the Landmarker, but is not looking at it. This hint texture and text can
also be edited in the `Inspector`. 

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Templates/T2kuv7A_2_0_0/img/landmarker_point_at_hint.gif)

## Selfie Mode 

The Landmarker Template provides a Selfie Mode that allows users to a
selfie with the Landmarker Lens on the front camera. The entire scene is
mirrored on the front camera to ensure the Lens content is correctly
aligned with the actual Landmarker architecture.  

The script `FrontCameraMirror` negates the X scale on front camera. A
consequence of negative scale is that geometry is turned inside out. A
single-sided material (default) will disappear when turned inside
out. To counter this, the script also swaps the Cull Mode (e.g. Front
to Back) of any Material in its hierarchy.

**Warning**  
Outside of this hierarchy, a flipped Cull Mode could cause a visual to
disappear. Since many mesh visuals can share the same material, take
care not to use materials both in this hierarchy, where Cull Mode can be
flipped. 

## Submitting Your Lens

You’re now ready to submit your Landmarker Lens\! Follow the below
guides:

  - [Pairing to Snapchat](/guides/general/pairing-to-snapchat)
  - [Creating an Icon](/guides/submission/creating-an-icon)
  - [Configuring Project
    Info](/guides/submission/configuring-project-info)
  - [Submitting Your Lens](/guides/submission/submitting-your-lens)
  - [Sharing Your Lens](/guides/sharing/sharing-your-lens)

## Related Guides

Please refer to the guides below for additional information:

  - [Marker Tracking](/guides/general/tracking/marker-tracking)
  - [Substance Texturing](/guides/3d/texturing/substance-texturing)
  - [3D Object Export  
    ](/guides/3d/3d-object-export)

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
