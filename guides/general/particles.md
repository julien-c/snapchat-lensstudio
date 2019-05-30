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
  - Particles

# Particles

You can emit particles in Lens Studio by using the Particles object. The
Particles object is a shader based system that has many options,
including, but not limited to: animated textures, velocity, gravity,
noise, and collision.  

The [Particles Template](/templates/world/particles) includes a number
of preset particle systems such as rain, snow, smoke, and more. 

## Create the Particles

To create particles, in the `Objects` panel, select `Add New ->
Particles`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/particles_template_add_new.gif)

## Configuring the Particles

To configure the particles, in your `Resources` panel, open the
Particles folder and select the `Particles Emitter Material`. Then, in
your `Inspector` panel, you can modify the properties of your particles.

For example, you can modify the texture of each particle by dragging and
dropping your new texture into the `Resources` panel, and assigning it
to the `Textures -> Base Texture -> Texture` field.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/particles_template_texture_replace.gif)

  

Refer to the [Particle Material
Options](#particle-material-options) section below for detailed
explanation of each setting.

## Starting Particles on Event

By default, the particles object emits on start. You can modify this
behavior by using the `External Time` option, and using a script to
start the particles.

### Enable External Time

To enable the `External Time` option, select the "Particles Emitter
Material" in the `Resources` panel and in the `Inspector` panel, tick
the box next to `External Time`.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/particles_template_external_time.png)

At this point you won’t see the particle emitting, this is normal.  

**Tip**  
The External Time option allows us to control at which point in time the
particle simulation is in.

###   
Script The Event

Next, add a script to pass in the time. In your `Resources` panel, press
`Add New -> Script`. Then select your particle object, and drag the new
script into the `Inspector` panel. We’ll run the script on
`Initialized` since we need to bind a couple events: one to start the
particles and one to update the particles over time.

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/particles_template_add_script.gif)

Then in the `Resources` panel, select your new script and copy and paste
the following in the `Inspector` panel:

    // What event to trigger particle on
    var triggerEventName = "MouthOpenedEvent";
    // Get the Particle's Mesh Visual
    var meshVis = script.getSceneObject().getFirstComponent("Component.MeshVisual");
    // Variable to store what time particle started
    var startTime;
    // Update the particle time every frame when needed
    function update()
    {
        if (startTime) 
        {
            // Calculate how many seconds have elapsed since we've triggered particles
            var particleTime = getTime() - startTime;
            // Pass it in to our Particle Material
            meshVis.mainPass.externalTimeInput = particleTime; 
        }
    }
    var updateEvent = script.createEvent("UpdateEvent");
    updateEvent.bind(update);
    // On an event, store the time when particle is triggered
    function startParticle()
    {
        startTime = getTime();
    }
    var particleTriggerEvent = script.createEvent(triggerEventName);
    particleTriggerEvent.bind(startParticle);

In this case the script triggers the particle when the user opens their
mouth. You can modify `eventTriggerName` to change this. For example:
replacing `MouthOpenedEvent` with `TouchStartEvent` will start the
particle when the user taps the screen instead. Take a look at the
[Script Event](/guides/scripting/script-events/) page to see different
types of events.

**Tip**  
If you are using `Instant Spawn`, you will need to utilize this script
or similar to start the particle.

## Stopping Particles on Event

In some cases you may want to stop the particles from emitting. You can
add an additional event to the script above to do this.

    // What event to stop particle on
    var stopEventName = "TouchStartEvent";
    // On an event, stop particle by setting particle time to 0
    function stopParticle()
    {
        startTime = 0;
        meshVis.mainPass.externalTimeInput = 0; 
    }
    var particleStopEvent = script.createEvent(stopEventName);
    particleStopEvent.bind(stopParticle);

## Particles Control Helper

Alternatively, you can import the `ParticlesControlHelper` script to
help you control particle start and stop time. ParticlesControlHelper is
a script that allows you to trigger an effect via the `Inspector` panel
by giving you a drop down with a list of possible events. Additionally,
there is an option to set an event to stop the particle.  

To use it, download
[ParticlesControlHelper](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/cMAtrJAagEmjazjB_Internal/ParticleControlHelper.js.zip),
unzip it, and drag the javascript file inside into your `Resources`
panel. Then in your `Objects` panel, select your Particles object, and
drag the script into the `Inspector` panel to add it. As above, make
sure `External Time` is ticked in the `Inspector` panel of `Particles
Emitter Material.`

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/particle-guide-add-particleControlHelper.gif)

## Particles Material Options

Here we'll cover the features and parameters of the material that
controls the particles. Each object that we treat as an emitter has a
material applied to it for emitting particles.

**Note**  
Changing a materials parameters will apply across all objects with that
material applied to it. If you want to create another emitter object
with the same material but slightly different settings then make sure
you duplicate the material first and then apply that to your new object.

**Tip  
**You can script any property material by hovering over the property
name to get its scriptable variable name. Then, you can modify the
material's [mainPass](/api/classes/Pass/) to change it\!  
  
![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/cMAtrJAagEmjazjB_Internal/img/material-property.png)

**Spawn / Time**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/particles_guide_properties_spawn.png)

Spawn / Time controls lifetime of particles and particle count. You can
customize these options to spawn particles over time of a burst of
particles all at once.

  - **World / Local Space **- Specifies the space in which rotation is
    applied
  - **Global Time Multiplier(float) **- A multiplier of time across the
    entire effect which can be used to make the effect move faster or
    slower
  - **External Time (bool)** - Enables the use of external time
    controlling the particle effect
  - **External Time Input (float)** - The external time input from an
    outside source such as script
  - **External Seed (float)** - Assigns a seed value to the effect which
    allows you to control the randomness of particles while still
    keeping them synced with other effects sharing the same seed value
  - **World Position Seed (bool)** - Takes into account the world
    positions when using the seed value
  - **Lifetime Random (bool)** - Enables random lifetime duration for
    each particle
  - **Lifetime Min/Max (float)** - The range, in seconds, of each
    particle's lifetime is randomly assigned
  - **Particle Count (bool)** - Enables definition of a maximum particle
    count for the emitter
  - **Amount (float) - **When "Particle Count" is enabled, defines the
    maximum particle count
  - **Instant Spawn (bool)** - When enabled will "burst" entire particle
    count on the first frame the particle system is emitted. You must
    also enable "External Time", and pass in the time through script.
    Refer to the [Starting Particles on Event](#starting-particles)
    section above for information on passing in time to particles. 

**Spawn Location/Shape**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/img/particles_guide_properties_spawn_location_shape.png)

Spawn location allows you to define the area in which particles will
spawn. You can control this by defining the dimensions of the volume in
which the particles will emit from.

  - **Initial Location / Spawn Location (bool / vec3)** - When enabled
    allows you to define the initial location where an effect will spawn
    offset from the origin of the object which the material as applied
    to
  - **Initial Box Spawn / Spawn Box **(bool / vec3)**** - When enabled
    will allow you to define the dimension of the box volume in which
    particles will spawn
  - **Initial Sphere Spawn / Spawn Sphere (bool / vec3)** - When enabled
    will allow you to define the dimension of the sphere volume in which
    particles will spawn

**Textures**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/particles_guide_properties_textures.png)

Textures allow you to define custom color and alpha textures you’ll
apply to each particle. You can define a flipbook texture to play
animated image sequences per particle. You can also define a ramp
texture to control fading particle or add a gradient of color to
particles over their lifetime. This is great for fiery smoke effects.  

  - **Base Texture / Texture (bool / texture)** - Allows you to specify
    a texture to apply to each particle
  - **Flipbook (bool)** - Enables use of a flipbook (sprite sheet)
    texture to animate on each particle over its lifespan
  - **Flipbook Numbers (vec2)** - Defines the width and height (in
    frames) of the flipbook
  - **Flipbook Speed (float)** - Controls the playback speed of the
    flipbook animation
  - **Flipbook Random (float)** - Controls a random value between 0 and
    the number you define to randomize the flipbook
  - **Frame Blend (bool)** - Will "fade" the images of the flipbook
    between each other to create a smooth transition
  - **Vector Blend (bool) **- Enables use of a vector field texture for
    frame blending
  - **Vector Texture (texture) **- If "Vector Blend" is enabled, the
    texture to use as the vector field source
  - **By Life (bool)** - When enabled will animate the flipbook sequence
    over the lifespan of the particle
  - **Color Ramp Texture (bool / texture)** - Unlocks a texture to
    multiply the color and alpha on top of your particles over their
    lifespan
  - **Color Ramp Mult (color)** - Color that is multiplied against the
    "Color Ramp Texture"

**Color / Alpha**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/particles_guide_properties_color_alpha.png)

These parameters control color being applied to your particles and the
alpha values. You can specify random color and alpha values for each
particle as it’s spawned.  

  - **Color Random (bool) - **Enables a random color applied to each
    particle
  - **Color Min Start (color) **- The start of the color range used to
    randomly assign each particle's color
  - **Color Max Start (color) **- The end of the color range used to
    randomly assign each particle's color
  - **Alpha Random (bool) **- Enables a random alpha applied to each
    particle
  - **Alpha Min Start (float) **- The minimum value of the range used to
    randomly assign each particle's alpha
  - **Alpha Max Start (float) **- The minimum value of the range used to
    randomly assign each particle's alpha
  - **Premultiplied Color (bool)** - Enabled will multiply the color
    values against the Base Texture if one is defined so that the
    particles will look correct in premultiplied alpha mode
  - **Black as Alpha (bool)** - Enabled will treat the black value of
    the Base Texture as the alpha value for each particle
  - **Alpha Dissolving (bool / float)** - Allows you to "erode" the
    alpha of particle over their lifespan
  - **Mono Color Random (bool)** - Keeps random color values within the
    expected spectrum based on the color picker otherwise the random
    values lean more towards random mathematical values

**Light and Shadow**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/particles_guide_properties_lighting.png)

Your particles can receive light from directional lights and here you
can control the amount of influence these particles will get from the
light source.  

  - **Camera Lighting (bool)** - Enables use of camera lighting
  - **Camera Color Texture (texture)** - 3x3 texture to use as the
    camera light buffer
  - **Camera Light Blend (float) **- Amount to blend the camera color
    texture
  - **Pixel Lighting (bool)** - Enables pixel lighting
  - **Lighting Texture (texture) **- Pre-calculated light direction
    texture
  - **Vertex Lighting (bool)** - Enables the influence of runtime lights
    interpolated between the vertices of the particles
  - **Particle Shade (float)** - Shadow amount blend
  - **Shadow Size (float)** - Controls the size of the shadow cast by
    particles

**Distortion / Screen**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/particle_template_distortion.png)

In some cases you may want to distort the background image for heat
distortion effects and water effects. Once you enable this feature
you’ll have access to a texture input to control how to distort pixels
and a value to control the intensity of the effect.

  - **Distortion (bool)** - Enables the distortion functionality
  - **Texture (texture)** - Texture used for distorting background
    pixels
  - **Distortion Strength (float)** - The intensity of the distortion
    effect

**Noise**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/particle_template_noise.png)

Noise allows you to control how much random movement you’d like to add
to your particles.

  - **Noise (bool)** - Enables the noise functionality
  - **Noise Scale (vec3)** - Defines the 3D intensity of the noise
    applied
  - **Noise Frequency (vec3)** - The 3D frequency of the noise 
  - **Simplex Noise (bool)** - Enables the simplex noise
    functionality which can be used as a cheaper alternative to
    standard noise and can also act as a second layer of noise for added
    detail
  - **Simplex Noise Scale (vec3)** - Defines the 3D intensity of the
    simplex noise applied
  - **Simplex Noise Frequency (vec3)** - The 3D frequency of the simplex
    noise 

**Collision**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/particles_guide_properties_collision.png)

Collision allows particles to collide with the ground to give the sense
of bouncing around and sliding.  

  - **Collision Bounce (bool)** - Enables the bounce of particles
  - **Collision Offset (float)** - Offset the point where collisions are
    detected per particle outward from the center of the particle
  - **Bounciness (float)** - The intensity of the bounce the particles
    will have
  - **Number of Bounces (float)** -The maximum number of bounces each
    particle will simulate
  - **Collision Slide (bool) **- Simulates collision and a sliding
    motion against an infintie plane
  - **Collision Height** **(float) **- If "Collision Slide" is enabled,
    defines the height of the infinite plane

**Velocity**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/particles_guide_properties_velocity.png)

Velocity controls the movement speed of your particles. You can specify
random 3 dimensional directions to apply to your particles.  

  - **Velocity Ramp Texture (bool/texture) **- Enables use of a texture
    to define the change in velocity
  - **Velocity Min (vec3) **- Defines the minimum of the range from
    which each particle's velocity is randomly assigned
  - **Velocity Max (vec3) **- Defines the maximum of the range from
    which each particle's velocity is randomly assigned
  - **Velocity Drag (vec3) **- Defines the amount of drag applied to
    each particle's velocity over time

**Rotation**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/particles_guide_properties_rotation.png)

Rotation will control the amount of random rotation applied to your
particles. Rotation is applied around the center of the particle. The
values you specify are random ranges to rotate around this center
point.  

  - **Rotation Rate (vec2)** - The min and max rotations in radians each
    particle will have rotate over their life
  - **Initial Rotation (vec2)** - The min and max rotations in radians
    each particle will have at birth
  - **Rotation Drag (float)** - The power applied to the rotation rate
    on each particle
  - **Align (bool)** - Each axis you'd like to force the particle to
    face where most particles usually face "Z"
  - **Align to Direction (bool)** - This aligns particle to their
    velocity direction

**Scale**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/particles_guide_properties_scale.png)

Scale controls the size applied to each particle between a random range
of values.  

  - **Size Start (vec2) **- The size of each particle at the start of
    its life
  - **Size End (vec2) **- The size of each particle at the end of its
    life
  - **Size Random (vec2)** - Enables definition of random size ranges
    for both the start and end of each particle's life
  - **Size Drag (float)** - The power of the Size applied to the
    particles which can be used to "ramp" up the scale of particles at
    birth
  - **Size Ramp Texture (texture)** - Enables use of a texture to
    describe change in size over time (not available on low-end devices)

**Force / Gravity**

![](https://storage.googleapis.com/snapchat-lens-assets/f1a09194-f02d-43ed-92b8-62e843179ff0/lensStudio/Guides/x7yZgWpMpDYXNbm_Face/img/particle_template_gravity.png)

Force / Gravity controls the amount of gravity applied to your
particles. A negative value sends particles toward the ground and
positive values send the particles into the air.

  - **Gravity (float)** - The force of gravity applied to particles
    which is usually represented as -9.8
  - **Local Force (bool)** - When enabled allows you to define a
    specific axis that gravity will respect else it assumes global Y-Up

## Related Guides

Please refer to the guides below for additional information:

  - [Particles Template](/templates/world/particles)
  - [Script Events](/guides/scripting/script-events)
  - [2D Animation](/guides/2d/2d-animation)

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
