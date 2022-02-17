#    RackCraft
#    This file contains a list of all available settings and their default value for multicraft.conf

#    By default, all the settings are commented and not functional.
#    Uncomment settings by removing the preceding #.

#    multicraft.conf is read by default from:
#    ../multicraft.conf
#    ../../multicraft.conf
#    Any other path can be chosen by passing the path as a parameter
#    to the program, eg. "minetest.exe --config ../multicraft.conf.example".

#    Further documentation:
#    http://wiki.minetest.net/

#
# Controls
#

#    If enabled, you can place blocks at the position (feet + eye level) where you stand.
#    This is helpful when working with nodeboxes in small areas.
#    type: bool
# enable_build_where_you_stand = false

#    Player is able to fly without being affected by gravity.
#    This requires the "fly" privilege on the server.
#    type: bool
# free_move = false

#    If enabled, makes move directions relative to the player's pitch when flying or swimming.
#    type: bool
# pitch_move = false

#    Fast movement (via the "special" key).
#    This requires the "fast" privilege on the server.
#    type: bool
# fast_move = false

#    If enabled together with fly mode, player is able to fly through solid nodes.
#    This requires the "noclip" privilege on the server.
#    type: bool
# noclip = false

#    Smooths camera when looking around. Also called look or mouse smoothing.
#    Useful for recording videos.
#    type: bool
# cinematic = false

#    Smooths rotation of camera. 0 to disable.
#    type: float min: 0 max: 0.99
# camera_smoothing = 0.0

#    Smooths rotation of camera in cinematic mode. 0 to disable.
#    type: float min: 0 max: 0.99
# cinematic_camera_smoothing = 0.7

#    Invert vertical mouse movement.
#    type: bool
# invert_mouse = false

#    Mouse sensitivity multiplier.
#    type: float
# mouse_sensitivity = 0.2

#    If enabled, "special" key instead of "sneak" key is used for climbing down and
#    descending.
#    type: bool
# aux1_descends = false

#    Double-tapping the jump key toggles fly mode.
#    type: bool
# doubletap_jump = false

#    If disabled, "special" key is used to fly fast if both fly and fast mode are
#    enabled.
#    type: bool
# always_fly_fast = true

#    The time in seconds it takes between repeated node placements when holding
#    the place button.
#    type: float min: 0.001
# repeat_place_time = 0.25

#    Automatically jump up single-node obstacles.
#    type: bool
# autojump = false

#    Prevent digging and placing from repeating when holding the mouse buttons.
#    Enable this when you dig or place too often by accident.
#    type: bool
# safe_dig_and_place = false

#    Enable random user input (only used for testing).
#    type: bool
# random_input = false

#    Continuous forward movement, toggled by autoforward key.
#    Press the autoforward key again or the backwards movement to disable.
#    type: bool
# continuous_forward = false

#    The length in pixels it takes for touch screen interaction to start.
#    type: int min: 0 max: 100
# touchscreen_threshold = 20

#    (Android) Fixes the position of virtual joystick.
#    If disabled, virtual joystick will center to first-touch's position.
#    type: bool
# fixed_virtual_joystick = false

#    (Android) Use virtual joystick to trigger "aux" button.
#    If enabled, virtual joystick will also tap "aux" button when out of main circle.
#    type: bool
# virtual_joystick_triggers_aux = false

#    Enable joysticks
#    type: bool
# enable_joysticks = false

#    The identifier of the joystick to use
#    type: int
# joystick_id = 0

#    The type of joystick
#    type: enum values: auto, generic, xbox
# joystick_type = auto

#    The time in seconds it takes between repeated events
#    when holding down a joystick button combination.
#    type: float min: 0.001
# repeat_joystick_button_time = 0.17

#    The deadzone of the joystick
#    type: int
# joystick_deadzone = 2048

#    The sensitivity of the joystick axes for moving the
#    ingame view frustum around.
#    type: float
# joystick_frustum_sensitivity = 170

#    Key for moving the player forward.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_forward = KEY_KEY_W

#    Key for moving the player backward.
#    Will also disable autoforward, when active.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_backward = KEY_KEY_S

#    Key for moving the player left.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_left = KEY_KEY_A

#    Key for moving the player right.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_right = KEY_KEY_D

#    Key for jumping.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_jump = KEY_SPACE

#    Key for sneaking.
#    Also used for climbing down and descending in water if aux1_descends is disabled.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_sneak = KEY_LSHIFT

#    Key for digging.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_dig = KEY_LBUTTON

#    Key for placing.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_place = KEY_RBUTTON

#    Key for opening the inventory.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_inventory = KEY_KEY_I

#    Key for moving fast in fast mode.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_special1 = KEY_KEY_E

#    Key for opening the chat window.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_chat = KEY_KEY_T

#    Key for opening the chat window to type commands.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_cmd = /

#    Key for opening the chat window to type local commands.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_cmd_local = .

#    Key for toggling unlimited view range.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_rangeselect = KEY_KEY_R

#    Key for toggling flying.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_freemove = KEY_KEY_K

#    Key for toggling pitch move mode.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_pitchmove = KEY_KEY_P

#    Key for toggling fast mode.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_fastmove = KEY_KEY_J

#    Key for toggling noclip mode.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_noclip = KEY_KEY_H

#    Key for selecting the next item in the hotbar.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_hotbar_next = KEY_KEY_N

#    Key for selecting the previous item in the hotbar.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_hotbar_previous = KEY_KEY_B

#    Key for muting the game.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_mute = KEY_KEY_M

#    Key for increasing the volume.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_increase_volume =

#    Key for decreasing the volume.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_decrease_volume =

#    Key for toggling autoforward.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_autoforward =

#    Key for toggling cinematic mode.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_cinematic =

#    Key for toggling display of minimap.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_minimap = KEY_KEY_V

#    Key for taking screenshots.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_screenshot = KEY_F12

#    Key for dropping the currently selected item.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_drop = KEY_KEY_Q

#    Key to use view zoom when possible.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_zoom = KEY_KEY_Z

#    Key for selecting the first hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot1 = KEY_KEY_1

#    Key for selecting the second hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot2 = KEY_KEY_2

#    Key for selecting the third hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot3 = KEY_KEY_3

#    Key for selecting the fourth hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot4 = KEY_KEY_4

#    Key for selecting the fifth hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot5 = KEY_KEY_5

#    Key for selecting the sixth hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot6 = KEY_KEY_6

#    Key for selecting the seventh hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot7 = KEY_KEY_7

#    Key for selecting the eighth hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot8 = KEY_KEY_8

#    Key for selecting the ninth hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot9 = KEY_KEY_9

#    Key for selecting the tenth hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot10 = KEY_KEY_0

#    Key for selecting the 11th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot11 =

#    Key for selecting the 12th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot12 =

#    Key for selecting the 13th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot13 =

#    Key for selecting the 14th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot14 =

#    Key for selecting the 15th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot15 =

#    Key for selecting the 16th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot16 =

#    Key for selecting the 17th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot17 =

#    Key for selecting the 18th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot18 =

#    Key for selecting the 19th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot19 =

#    Key for selecting the 20th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot20 =

#    Key for selecting the 21st hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot21 =

#    Key for selecting the 22nd hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot22 =

#    Key for selecting the 23rd hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot23 =

#    Key for selecting the 24th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot24 =

#    Key for selecting the 25th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot25 =

#    Key for selecting the 26th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot26 =

#    Key for selecting the 27th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot27 =

#    Key for selecting the 28th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot28 =

#    Key for selecting the 29th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot29 =

#    Key for selecting the 30th hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot30 =

#    Key for selecting the 31st hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot31 =

#    Key for selecting the 32nd hotbar slot.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_slot32 =

#    Key for toggling the display of the HUD.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_toggle_hud = KEY_F1

#    Key for toggling the display of chat.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_toggle_chat = KEY_F2

#    Key for toggling the display of the large chat console.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_console = KEY_F10

#    Key for toggling the display of fog.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_toggle_force_fog_off = KEY_F3

#    Key for toggling the camera update. Only used for development
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_toggle_update_camera =

#    Key for toggling the display of debug info.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_toggle_debug = KEY_F5

#    Key for toggling the display of the profiler. Used for development.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_toggle_profiler = KEY_F6

#    Key for switching between first- and third-person camera.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_camera_mode = KEY_KEY_C

#    Key for increasing the viewing range.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_increase_viewing_range_min = +

#    Key for decreasing the viewing range.
#    See http://irrlicht.sourceforge.net/docu/namespaceirr.html#a54da2a0e231901735e3da1b0edf72eb3
#    type: key
# keymap_decrease_viewing_range_min = -

#
# Graphics
#

## In-Game

### Basic

#    Whether nametag backgrounds should be shown by default.
#    Mods may still set a background.
#    type: bool
# show_nametag_backgrounds = true

#    Enable vertex buffer objects.
#    This should greatly improve graphics performance.
#    type: bool
# enable_vbo = true

#    Whether to fog out the end of the visible area.
#    type: bool
# enable_fog = true

#    Leaves style:
#    -   Fancy:  all faces visible
#    -   Simple: only outer faces, if defined special_tiles are used
#    -   Opaque: disable transparency
#    type: enum values: fancy, simple, opaque
# leaves_style = fancy

#    Connects glass if supported by node.
#    type: bool
# connected_glass = false

#    Enable smooth lighting with simple ambient occlusion.
#    Disable for speed or for different looks.
#    type: bool
# smooth_lighting = true

#    Clouds are a client side effect.
#    type: bool
# enable_clouds = true

#    Use 3D cloud look instead of flat.
#    type: bool
# enable_3d_clouds = true

#    Method used to highlight selected object.
#    type: enum values: box, halo, none
# node_highlighting = box

#    Adds particles when digging a node.
#    type: bool
# enable_particles = true

### Filtering

#    Use mip mapping to scale textures. May slightly increase performance,
#    especially when using a high resolution texture pack.
#    Gamma correct downscaling is not supported.
#    type: bool
# mip_map = false

#    Use anisotropic filtering when viewing at textures from an angle.
#    type: bool
# anisotropic_filter = false

#    Use bilinear filtering when scaling textures.
#    type: bool
# bilinear_filter = false

#    Use trilinear filtering when scaling textures.
#    type: bool
# trilinear_filter = false

#    Filtered textures can blend RGB values with fully-transparent neighbors,
#    which PNG optimizers usually discard, sometimes resulting in a dark or
#    light edge to transparent textures. Apply this filter to clean that up
#    at texture load time.
#    type: bool
# texture_clean_transparent = false

#    When using bilinear/trilinear/anisotropic filters, low-resolution textures
#    can be blurred, so automatically upscale them with nearest-neighbor
#    interpolation to preserve crisp pixels. This sets the minimum texture size
#    for the upscaled textures; higher values look sharper, but require more
#    memory.  Powers of 2 are recommended. Setting this higher than 1 may not
#    have a visible effect unless bilinear/trilinear/anisotropic filtering is
#    enabled.
#    This is also used as the base node texture size for world-aligned
#    texture autoscaling.
#    type: int
# texture_min_size = 64

#    Use multi-sample antialiasing (MSAA) to smooth out block edges.
#    This algorithm smooths out the 3D viewport while keeping the image sharp,
#    but it doesn't affect the insides of textures
#    (which is especially noticeable with transparent textures).
#    Visible spaces appear between nodes when shaders are disabled.
#    If set to 0, MSAA is disabled.
#    A restart is required after changing this option.
#    type: enum values: 0, 1, 2, 4, 8, 16
# fsaa = 0

#    Undersampling is similar to using a lower screen resolution, but it applies
#    to the game world only, keeping the GUI intact.
#    It should give a significant performance boost at the cost of less detailed image.
#    Higher values result in a less detailed image.
#    type: int min: 1 max: 8
# undersampling = 1

### Shaders

#    Shaders allow advanced visual effects and may increase performance on some video
#    cards.
#    This only works with the OpenGL video backend.
#    type: bool
# enable_shaders = true

#    Path to shader directory. If no path is defined, default location will be used.
#    type: path
# shader_path =

#### Tone Mapping

#    Enables Hable's 'Uncharted 2' filmic tone mapping.
#    Simulates the tone curve of photographic film and how this approximates the
#    appearance of high dynamic range images. Mid-range contrast is slightly
#    enhanced, highlights and shadows are gradually compressed.
#    type: bool
# tone_mapping = false

#### Waving Nodes

#    Set to true to enable waving liquids (like water).
#    Requires shaders to be enabled.
#    type: bool
# enable_waving_water = false

#    The maximum height of the surface of waving liquids.
#    4.0 = Wave height is two nodes.
#    0.0 = Wave doesn't move at all.
#    Default is 1.0 (1/2 node).
#    Requires waving liquids to be enabled.
#    type: float min: 0 max: 4
# water_wave_height = 1.0

#    Length of liquid waves.
#    Requires waving liquids to be enabled.
#    type: float min: 0.1
# water_wave_length = 20.0

#    How fast liquid waves will move. Higher = faster.
#    If negative, liquid waves will move backwards.
#    Requires waving liquids to be enabled.
#    type: float
# water_wave_speed = 5.0

#    Set to true to enable waving leaves.
#    Requires shaders to be enabled.
#    type: bool
# enable_waving_leaves = false

#    Set to true to enable waving plants.
#    Requires shaders to be enabled.
#    type: bool
# enable_waving_plants = false

### Advanced

#    Arm inertia, gives a more realistic movement of
#    the arm when the camera moves.
#    type: bool
# arm_inertia = true

#    If FPS would go higher than this, limit it by sleeping
#    to not waste CPU power for no benefit.
#    type: int min: 1
# fps_max = 60

#    Maximum FPS when the window is not focused, or when the game is paused.
#    type: int min: 1
# fps_max_unfocused = 20

#    Open the pause menu when the window's focus is lost. Does not pause if a formspec is
#    open.
#    type: bool
# pause_on_lost_focus = false

#    View distance in nodes.
#    type: int min: 20 max: 4000
# viewing_range = 190

#    Camera 'near clipping plane' distance in nodes, between 0 and 0.25
#    Only works on GLES platforms. Most users will not need to change this.
#    Increasing can reduce artifacting on weaker GPUs.
#    0.1 = Default, 0.25 = Good value for weaker tablets.
#    type: float min: 0 max: 0.25
# near_plane = 0.1

#    Width component of the initial window size.
#    type: int min: 1
# screen_w = 1024

#    Height component of the initial window size.
#    type: int min: 1
# screen_h = 600

#    Save window size automatically when modified.
#    type: bool
# autosave_screensize = true

#    Fullscreen mode.
#    type: bool
# fullscreen = false

#    Bits per pixel (aka color depth) in fullscreen mode.
#    type: int
# fullscreen_bpp = 24

#    Vertical screen synchronization.
#    type: bool
# vsync = false

#    Field of view in degrees.
#    type: int min: 45 max: 160
# fov = 72

#    Alters the light curve by applying 'gamma correction' to it.
#    Higher values make middle and lower light levels brighter.
#    Value '1.0' leaves the light curve unaltered.
#    This only has significant effect on daylight and artificial
#    light, it has very little effect on natural night light.
#    type: float min: 0.33 max: 3
# display_gamma = 1.0

#    Gradient of light curve at minimum light level.
#    Controls the contrast of the lowest light levels.
#    type: float min: 0 max: 3
# lighting_alpha = 0.0

#    Gradient of light curve at maximum light level.
#    Controls the contrast of the highest light levels.
#    type: float min: 0 max: 3
# lighting_beta = 1.5

#    Strength of light curve boost.
#    The 3 'boost' parameters define a range of the light
#    curve that is boosted in brightness.
#    type: float min: 0 max: 0.4
# lighting_boost = 0.2

#    Center of light curve boost range.
#    Where 0.0 is minimum light level, 1.0 is maximum light level.
#    type: float min: 0 max: 1
# lighting_boost_center = 0.5

#    Spread of light curve boost range.
#    Controls the width of the range to be boosted.
#    Standard deviation of the light curve boost Gaussian.
#    type: float min: 0 max: 0.4
# lighting_boost_spread = 0.2

#    Path to texture directory. All textures are first searched from here.
#    type: path
# texture_path =

#    The rendering back-end for Irrlicht.
#    A restart is required after changing this.
#    Note: On Android, stick with OGLES1 if unsure! App may fail to start otherwise.
#    On other platforms, OpenGL is recommended.
#    Shaders are supported by OpenGL (desktop only) and OGLES2 (experimental)
#    type: enum values: null, software, burningsvideo, direct3d8, direct3d9, opengl, ogles1, ogles2
# video_driver = opengl

#    Radius of cloud area stated in number of 64 node cloud squares.
#    Values larger than 26 will start to produce sharp cutoffs at cloud area corners.
#    type: int
# cloud_radius = 12

#    Enable view bobbing and amount of view bobbing.
#    For example: 0 for no view bobbing; 1.0 for normal; 2.0 for double.
#    type: float
# view_bobbing_amount = 1.0

#    Multiplier for fall bobbing.
#    For example: 0 for no view bobbing; 1.0 for normal; 2.0 for double.
#    type: float
# fall_bobbing_amount = 0.03

#    3D support.
#    Currently supported:
#    -    none: no 3d output.
#    -    anaglyph: cyan/magenta color 3d.
#    -    interlaced: odd/even line based polarisation screen support.
#    -    topbottom: split screen top/bottom.
#    -    sidebyside: split screen side by side.
#    -    crossview: Cross-eyed 3d
#    -    pageflip: quadbuffer based 3d.
#    Note that the interlaced mode requires shaders to be enabled.
#    type: enum values: none, anaglyph, interlaced, topbottom, sidebyside, crossview, pageflip
# 3d_mode = none

#    Strength of 3D mode parallax.
#    type: float
# 3d_paralax_strength = 0.025

#    In-game chat console height, between 0.1 (10%) and 1.0 (100%).
#    type: float min: 0.1 max: 1
# console_height = 0.6

#    In-game chat console background color (R,G,B).
#    type: string
# console_color = (0,0,0)

#    In-game chat console background alpha (opaqueness, between 0 and 255).
#    type: int min: 0 max: 255
# console_alpha = 200

#    Formspec full-screen background opacity (between 0 and 255).
#    type: int min: 0 max: 255
# formspec_fullscreen_bg_opacity = 140

#    Formspec full-screen background color (R,G,B).
#    type: string
# formspec_fullscreen_bg_color = (0,0,0)

#    Formspec default background opacity (between 0 and 255).
#    type: int min: 0 max: 255
# formspec_default_bg_opacity = 140

#    Formspec default background color (R,G,B).
#    type: string
# formspec_default_bg_color = (0,0,0)

#    Selection box border color (R,G,B).
#    type: string
# selectionbox_color = (0,0,0)

#    Width of the selection box lines around nodes.
#    type: int min: 1 max: 5
# selectionbox_width = 2

#    Crosshair color (R,G,B).
#    Also controls the object crosshair color
#    type: string
# crosshair_color = (255,255,255)

#    Crosshair alpha (opaqueness, between 0 and 255).
#    Also controls the object crosshair color
#    type: int min: 0 max: 255
# crosshair_alpha = 255

#    Maximum number of recent chat messages to show
#    type: int min: 2 max: 20
# recent_chat_messages = 6

#    Whether node texture animations should be desynchronized per mapblock.
#    type: bool
# desynchronize_mapblock_texture_animation = true

#    Maximum proportion of current window to be used for hotbar.
#    Useful if there's something to be displayed right or left of hotbar.
#    type: float
# hud_hotbar_max_width = 1.0

#    Modifies the size of the hudbar elements.
#    type: float
# hud_scaling = 1.0

#    Enables caching of facedir rotated meshes.
#    type: bool
# enable_mesh_cache = false

#    Delay between mesh updates on the client in ms. Increasing this will slow
#    down the rate of mesh updates, thus reducing jitter on slower clients.
#    type: int min: 0 max: 50
# mesh_generation_interval = 0

#    Size of the MapBlock cache of the mesh generator. Increasing this will
#    increase the cache hit %, reducing the data being copied from the main
#    thread, thus reducing jitter.
#    type: int min: 0 max: 1000
# meshgen_block_cache_size = 20

#    Enables minimap.
#    type: bool
# enable_minimap = true

#    Shape of the minimap. Enabled = round, disabled = square.
#    type: bool
# minimap_shape_round = true

#    True = 256
#    False = 128
#    Usable to make minimap smoother on slower machines.
#    type: bool
# minimap_double_scan_height = true

#    Make fog and sky colors depend on daytime (dawn/sunset) and view direction.
#    type: bool
# directional_colored_fog = true

#    The strength (darkness) of node ambient-occlusion shading.
#    Lower is darker, Higher is lighter. The valid range of values for this
#    setting is 0.25 to 4.0 inclusive. If the value is out of range it will be
#    set to the nearest valid value.
#    type: float min: 0.25 max: 4
# ambient_occlusion_gamma = 2.2

#    Enables animation of inventory items.
#    type: bool
# inventory_items_animations = false

#    Fraction of the visible distance at which fog starts to be rendered
#    type: float min: 0 max: 0.99
# fog_start = 0.4

#    Makes all liquids opaque
#    type: bool
# opaque_water = false

#    Textures on a node may be aligned either to the node or to the world.
#    The former mode suits better things like machines, furniture, etc., while
#    the latter makes stairs and microblocks fit surroundings better.
#    However, as this possibility is new, thus may not be used by older servers,
#    this option allows enforcing it for certain node types. Note though that
#    that is considered EXPERIMENTAL and may not work properly.
#    type: enum values: disable, enable, force_solid, force_nodebox
# world_aligned_mode = enable

#    World-aligned textures may be scaled to span several nodes. However,
#    the server may not send the scale you want, especially if you use
#    a specially-designed texture pack; with this option, the client tries
#    to determine the scale automatically basing on the texture size.
#    See also texture_min_size.
#    Warning: This option is EXPERIMENTAL!
#    type: enum values: disable, enable, force
# autoscale_mode = disable

#    Show entity selection boxes
#    A restart is required after changing this.
#    type: bool
# show_entity_selectionbox = false

## Menus

#    Use a cloud animation for the main menu background.
#    type: bool
# menu_clouds = true

#    Scale GUI by a user specified value.
#    Use a nearest-neighbor-anti-alias filter to scale the GUI.
#    This will smooth over some of the rough edges, and blend
#    pixels when scaling down, at the cost of blurring some
#    edge pixels when images are scaled by non-integer sizes.
#    type: float min: 0.001
# gui_scaling = 1.0

#    When gui_scaling_filter is true, all GUI images need to be
#    filtered in software, but some images are generated directly
#    to hardware (e.g. render-to-texture for nodes in inventory).
#    type: bool
# gui_scaling_filter = false

#    When gui_scaling_filter_txr2img is true, copy those images
#    from hardware to software for scaling.  When false, fall back
#    to the old scaling method, for video drivers that don't
#    properly support downloading textures back from hardware.
#    type: bool
# gui_scaling_filter_txr2img = true

#    Delay showing tooltips, stated in milliseconds.
#    type: int
# tooltip_show_delay = 400

#    Append item name to tooltip.
#    type: bool
# tooltip_append_itemname = false

#    Whether FreeType fonts are used, requires FreeType support to be compiled in.
#    If disabled, bitmap and XML vectors fonts are used instead.
#    type: bool
# freetype = true

#    type: bool
# font_bold = false

#    type: bool
# font_italic = false

#    Shadow offset (in pixels) of the default font. If 0, then shadow will not be drawn.
#    type: int
# font_shadow = 1

#    Opaqueness (alpha) of the shadow behind the default font, between 0 and 255.
#    type: int min: 0 max: 255
# font_shadow_alpha = 127

#    Font size of the default font in point (pt).
#    type: int min: 1
# font_size = 16

#    Path to the default font.
#    If “freetype” setting is enabled: Must be a TrueType font.
#    If “freetype” setting is disabled: Must be a bitmap or XML vectors font.
#    The fallback font will be used if the font cannot be loaded.
#    type: filepath
# font_path = fonts/Arimo-Regular.ttf

#    type: filepath
# font_path_bold = fonts/Arimo-Bold.ttf

#    type: filepath
# font_path_italic = fonts/Arimo-Italic.ttf

#    type: filepath
# font_path_bolditalic = fonts/Arimo-BoldItalic.ttf

#    Font size of the monospace font in point (pt).
#    type: int min: 1
# mono_font_size = 15

#    Path to the monospace font.
#    If “freetype” setting is enabled: Must be a TrueType font.
#    If “freetype” setting is disabled: Must be a bitmap or XML vectors font.
#    This font is used for e.g. the console and profiler screen.
#    type: filepath
# mono_font_path = fonts/Cousine-Regular.ttf

#    type: filepath
# mono_font_path_bold = fonts/Cousine-Bold.ttf

#    type: filepath
# mono_font_path_italic = fonts/Cousine-Italic.ttf

#    type: filepath
# mono_font_path_bolditalic = fonts/Cousine-BoldItalic.ttf

#    Font size of the fallback font in point (pt).
#    type: int min: 1
# fallback_font_size = 15

#    Shadow offset (in pixels) of the fallback font. If 0, then shadow will not be drawn.
#    type: int
# fallback_font_shadow = 1

#    Opaqueness (alpha) of the shadow behind the fallback font, between 0 and 255.
#    type: int min: 0 max: 255
# fallback_font_shadow_alpha = 128

#    Path of the fallback font.
#    If “freetype” setting is enabled: Must be a TrueType font.
#    If “freetype” setting is disabled: Must be a bitmap or XML vectors font.
#    This font will be used for certain languages or if the default font is unavailable.
#    type: filepath
# fallback_font_path = fonts/DroidSansFallbackFull.ttf

#    Font size of the recent chat text and chat prompt in point (pt).
#    Value 0 will use the default font size.
#    type: int
# chat_font_size = 0

#    Path to save screenshots at. Can be an absolute or relative path.
#    The folder will be created if it doesn't already exist.
#    type: path
# screenshot_path = screenshots

#    Format of screenshots.
#    type: enum values: png, jpg, bmp, pcx, ppm, tga
# screenshot_format = png

#    Screenshot quality. Only used for JPEG format.
#    1 means worst quality; 100 means best quality.
#    Use 0 for default quality.
#    type: int min: 0 max: 100
# screenshot_quality = 0

## Advanced

#    Adjust dpi configuration to your screen (non X11/Android only) e.g. for 4k screens.
#    type: int min: 1
# screen_dpi = 72

#    Windows systems only: Start Minetest with the command line window in the background.
#    Contains the same information as the file debug.txt (default name).
#    type: bool
# enable_console = false

#
# Sound
#

#    Enables the sound system.
#    If disabled, this completely disables all sounds everywhere and the in-game
#    sound controls will be non-functional.
#    Changing this setting requires a restart.
#    type: bool
# enable_sound = true

#    Volume of all sounds.
#    Requires the sound system to be enabled.
#    type: float min: 0 max: 1
# sound_volume = 0.7

#    Whether to mute sounds. You can unmute sounds at any time, unless the
#    sound system is disabled (enable_sound=false).
#    In-game, you can toggle the mute state with the mute key or by using the
#    pause menu.
#    type: bool
# mute_sound = false

#
# Client
#

## Network

#    Address to connect to.
#    Leave this blank to start a local server.
#    Note that the address field in the main menu overrides this setting.
#    type: string
# address =

#    Port to connect to (UDP).
#    Note that the port field in the main menu overrides this setting.
#    type: int min: 1 max: 65535
# remote_port = 30000

#    Prometheus listener address.
#    If minetest is compiled with ENABLE_PROMETHEUS option enabled,
#    enable metrics listener for Prometheus on that address.
#    Metrics can be fetch on http://127.0.0.1:30000/metrics
#    type: string
# prometheus_listener_address = 127.0.0.1:30000

#    Save the map received by the client on disk.
#    type: bool
# enable_local_map_saving = false

#    Enable usage of remote media server (if provided by server).
#    Remote servers offer a significantly faster way to download media (e.g. textures)
#    when connecting to the server.
#    type: bool
# enable_remote_media_server = true

#    Enable Lua modding support on client.
#    This support is experimental and API can change.
#    type: bool
# enable_client_modding = true

#    URL to the server list displayed in the Multiplayer Tab.
#    type: string
# serverlist_url = servers.minetest.net

#    File in client/serverlist/ that contains your favorite servers displayed in the
#    Multiplayer Tab.
#    type: string
# serverlist_file = favoriteservers.json

#    Maximum size of the out chat queue.
#    0 to disable queueing and -1 to make the queue size unlimited.
#    type: int
# max_out_chat_queue_size = 20

#    Enable register confirmation when connecting to server.
#    If disabled, new account will be registered automatically.
#    type: bool
# enable_register_confirmation = true

## Advanced

#    Timeout for client to remove unused map data from memory.
#    type: int
# client_unload_unused_data_timeout = 600

#    Maximum number of mapblocks for client to be kept in memory.
#    Set to -1 for unlimited amount.
#    type: int
# client_mapblock_limit = 7500

#    Whether to show the client debug info (has the same effect as hitting F5).
#    type: bool
# show_debug = false

#
# Server / Singleplayer
#

#    Name of the server, to be displayed when players join and in the serverlist.
#    type: string
# server_name = Minetest server

#    Description of server, to be displayed when players join and in the serverlist.
#    type: string
# server_description = mine here

#    Domain name of server, to be displayed in the serverlist.
#    type: string
# server_address = game.minetest.net

#    Homepage of server, to be displayed in the serverlist.
#    type: string
# server_url = https://minetest.net

#    Automatically report to the serverlist.
#    type: bool
# server_announce = false

#    Announce to this serverlist.
#    type: string
# serverlist_url = servers.minetest.net

#    Remove color codes from incoming chat messages
#    Use this to stop players from being able to use color in their messages
#    type: bool
# strip_color_codes = false

## Network

#    Network port to listen (UDP).
#    This value will be overridden when starting from the main menu.
#    type: int
# port = 30000

#    The network interface that the server listens on.
#    type: string
# bind_address =

#    Enable to disallow old clients from connecting.
#    Older clients are compatible in the sense that they will not crash when connecting
#    to new servers, but they may not support all new features that you are expecting.
#    type: bool
# strict_protocol_version_checking = false

#    Specifies URL from which client fetches media instead of using UDP.
#    $filename should be accessible from $remote_media$filename via cURL
#    (obviously, remote_media should end with a slash).
#    Files that are not present will be fetched the usual way.
#    type: string
# remote_media =

#    Enable/disable running an IPv6 server.
#    Ignored if bind_address is set.
#    Needs enable_ipv6 to be enabled.
#    type: bool
# ipv6_server = false

### Advanced

#    Maximum number of blocks that are simultaneously sent per client.
#    The maximum total count is calculated dynamically:
#    max_total = ceil((#clients + max_users) * per_client / 4)
#    type: int
# max_simultaneous_block_sends_per_client = 40

#    To reduce lag, block transfers are slowed down when a player is building something.
#    This determines how long they are slowed down after placing or removing a node.
#    type: float
# full_block_send_enable_min_time_from_building = 2.0

#    Maximum number of packets sent per send step, if you have a slow connection
#    try reducing it, but don't reduce it to a number below double of targeted
#    client number.
#    type: int
# max_packets_per_iteration = 1024

#    ZLib compression level to use when sending mapblocks to the client.
#    -1 - Zlib's default compression level
#    0 - no compresson, fastest
#    9 - best compression, slowest
#    (levels 1-3 use Zlib's "fast" method, 4-9 use the normal method)
#    type: int min: -1 max: 9
# map_compression_level_net = -1

## Game

#    Default game when creating a new world.
#    This will be overridden when creating a world from the main menu.
#    type: string
# default_game = minetest

#    Message of the day displayed to players connecting.
#    type: string
# motd =

#    Maximum number of players that can be connected simultaneously.
#    type: int
# max_users = 15

#    World directory (everything in the world is stored here).
#    Not needed if starting from the main menu.
#    type: path
# map-dir =

#    Time in seconds for item entity (dropped items) to live.
#    Setting it to -1 disables the feature.
#    type: int
# item_entity_ttl = 900

#    Specifies the default stack size of nodes, items and tools.
#    Note that mods or games may explicitly set a stack for certain (or all) items.
#    type: int
# default_stack_max = 99

#    Enable players getting damage and dying.
#    type: bool
# enable_damage = false

#    Enable creative mode for all players
#    type: bool
# creative_mode = false

#    A chosen map seed for a new map, leave empty for random.
#    Will be overridden when creating a new world in the main menu.
#    type: string
# fixed_map_seed =

#    New users need to input this password.
#    type: string
# default_password =

#    The privileges that new users automatically get.
#    See /privs in game for a full list on your server and mod configuration.
#    type: string
# default_privs = interact, shout

#    Privileges that players with basic_privs can grant
#    type: string
# basic_privs = interact, shout

#    Whether players are shown to clients without any range limit.
#    Deprecated, use the setting player_transfer_distance instead.
#    type: bool
# unlimited_player_transfer_distance = true

#    Defines the maximal player transfer distance in blocks (0 = unlimited).
#    type: int
# player_transfer_distance = 0

#    Whether to allow players to damage and kill each other.
#    type: bool
# enable_pvp = true

#    Enable mod channels support.
#    type: bool
# enable_mod_channels = true

#    If this is set, players will always (re)spawn at the given position.
#    type: string
# static_spawnpoint =

#    If enabled, new players cannot join with an empty password.
#    type: bool
# disallow_empty_password = false

#    If enabled, disable cheat prevention in multiplayer.
#    type: bool
# disable_anticheat = false

#    If enabled, actions are recorded for rollback.
#    This option is only read when server starts.
#    type: bool
# enable_rollback_recording = false

#    Format of player chat messages. The following strings are valid placeholders:
#    @name, @message, @timestamp (optional)
#    type: string
# chat_message_format = <@name> @message

#    A message to be displayed to all clients when the server shuts down.
#    type: string
# kick_msg_shutdown = Server shutting down.

#    A message to be displayed to all clients when the server crashes.
#    type: string
# kick_msg_crash = This server has experienced an internal error. You will now be disconnected.

#    Whether to ask clients to reconnect after a (Lua) crash.
#    Set this to true if your server is set up to restart automatically.
#    type: bool
# ask_reconnect_on_crash = false

#    From how far clients know about objects, stated in mapblocks (16 nodes).
#
#    Setting this larger than active_block_range will also cause the server
#    to maintain active objects up to this distance in the direction the
#    player is looking. (This can avoid mobs suddenly disappearing from view)
#    type: int
# active_object_send_range_blocks = 8

#    The radius of the volume of blocks around every player that is subject to the
#    active block stuff, stated in mapblocks (16 nodes).
#    In active blocks objects are loaded and ABMs run.
#    This is also the minimum range in which active objects (mobs) are maintained.
#    This should be configured together with active_object_send_range_blocks.
#    type: int
# active_block_range = 4

#    From how far blocks are sent to clients, stated in mapblocks (16 nodes).
#    type: int
# max_block_send_distance = 12

#    Maximum number of forceloaded mapblocks.
#    type: int
# max_forceloaded_blocks = 16

#    Interval of sending time of day to clients.
#    type: int
# time_send_interval = 5

#    Controls length of day/night cycle.
#    Examples:
#    72 = 20min, 360 = 4min, 1 = 24hour, 0 = day/night/whatever stays unchanged.
#    type: int
# time_speed = 72

#    Time of day when a new world is started, in millihours (0-23999).
#    type: int min: 0 max: 23999
# world_start_time = 6125

#    Interval of saving important changes in the world, stated in seconds.
#    type: float
# server_map_save_interval = 5.3

#    Set the maximum character length of a chat message sent by clients.
#    type: int
# chat_message_max_size = 500

#    Amount of messages a player may send per 10 seconds.
#    type: float
# chat_message_limit_per_10sec = 10.0

#    Kick players who sent more than X messages per 10 seconds.
#    type: int
# chat_message_limit_trigger_kick = 50

### Physics

#    Horizontal and vertical acceleration on ground or when climbing,
#    in nodes per second per second.
#    type: float
# movement_acceleration_default = 3

#    Horizontal acceleration in air when jumping or falling,
#    in nodes per second per second.
#    type: float
# movement_acceleration_air = 2

#    Horizontal and vertical acceleration in fast mode,
#    in nodes per second per second.
#    type: float
# movement_acceleration_fast = 10

#    Walking and flying speed, in nodes per second.
#    type: float
# movement_speed_walk = 4

#    Sneaking speed, in nodes per second.
#    type: float
# movement_speed_crouch = 1.35

#    Walking, flying and climbing speed in fast mode, in nodes per second.
#    type: float
# movement_speed_fast = 20

#    Vertical climbing speed, in nodes per second.
#    type: float
# movement_speed_climb = 3

#    Initial vertical speed when jumping, in nodes per second.
#    type: float
# movement_speed_jump = 6.5

#    Decrease this to increase liquid resistance to movement.
#    type: float
# movement_liquid_fluidity = 1

#    Maximum liquid resistance. Controls deceleration when entering liquid at
#    high speed.
#    type: float
# movement_liquid_fluidity_smooth = 0.5

#    Controls sinking speed in liquid.
#    type: float
# movement_liquid_sink = 10

#    Acceleration of gravity, in nodes per second per second.
#    type: float
# movement_gravity = 9.81

### Advanced

#    Handling for deprecated Lua API calls:
#    -    none: Do not log deprecated calls
#    -    log: mimic and log backtrace of deprecated call (default).
#    -    error: abort on usage of deprecated call (suggested for mod developers).
#    type: enum values: none, log, error
# deprecated_lua_api_handling = log

#    Number of extra blocks that can be loaded by /clearobjects at once.
#    This is a trade-off between sqlite transaction overhead and
#    memory consumption (4096=100MB, as a rule of thumb).
#    type: int
# max_clearobjects_extra_loaded_blocks = 4096

#    How much the server will wait before unloading unused mapblocks.
#    Higher value is smoother, but will use more RAM.
#    type: int
# server_unload_unused_data_timeout = 29

#    Maximum number of statically stored objects in a block.
#    type: int
# max_objects_per_block = 64

#    See https://www.sqlite.org/pragma.html#pragma_synchronous
#    type: enum values: 0, 1, 2
# sqlite_synchronous = 2

#    ZLib compression level to use when saving mapblocks to disk.
#    -1 - Zlib's default compression level
#    0 - no compresson, fastest
#    9 - best compression, slowest
#    (levels 1-3 use Zlib's "fast" method, 4-9 use the normal method)
#    type: int min: -1 max: 9
# map_compression_level_disk = 3

#    Length of a server tick and the interval at which objects are generally updated over
#    network.
#    type: float
# dedicated_server_step = 0.09

#    Length of time between active block management cycles
#    type: float
# active_block_mgmt_interval = 2.0

#    Length of time between Active Block Modifier (ABM) execution cycles
#    type: float
# abm_interval = 1.0

#    The time budget allowed for ABMs to execute on each step
#    (as a fraction of the ABM Interval)
#    type: float min: 0.1 max: 0.9
# abm_time_budget = 0.2

#    Length of time between NodeTimer execution cycles
#    type: float
# nodetimer_interval = 0.2

#    If enabled, invalid world data won't cause the server to shut down.
#    Only enable this if you know what you are doing.
#    type: bool
# ignore_world_load_errors = false

#    Max liquids processed per step.
#    type: int
# liquid_loop_max = 100000

#    The time (in seconds) that the liquids queue may grow beyond processing
#    capacity until an attempt is made to decrease its size by dumping old queue
#    items.  A value of 0 disables the functionality.
#    type: int
# liquid_queue_purge_time = 0

#    Liquid update interval in seconds.
#    type: float
# liquid_update = 1.0

#    At this distance the server will aggressively optimize which blocks are sent to
#    clients.
#    Small values potentially improve performance a lot, at the expense of visible
#    rendering glitches (some blocks will not be rendered under water and in caves,
#    as well as sometimes on land).
#    Setting this to a value greater than max_block_send_distance disables this
#    optimization.
#    Stated in mapblocks (16 nodes).
#    type: int min: 2
# block_send_optimize_distance = 4

#    If enabled the server will perform map block occlusion culling based on
#    on the eye position of the player. This can reduce the number of blocks
#    sent to the client 50-80%. The client will not longer receive most invisible
#    so that the utility of noclip mode is reduced.
#    type: bool
# server_side_occlusion_culling = true

#    Restricts the access of certain client-side functions on servers.
#    Combine the byteflags below to restrict client-side features, or set to 0
#    for no restrictions:
#    LOAD_CLIENT_MODS: 1 (disable loading client-provided mods)
#    CHAT_MESSAGES: 2 (disable send_chat_message call client-side)
#    READ_ITEMDEFS: 4 (disable get_item_def call client-side)
#    READ_NODEDEFS: 8 (disable get_node_def call client-side)
#    LOOKUP_NODES_LIMIT: 16 (limits get_node call client-side to
#    csm_restriction_noderange)
#    READ_PLAYERINFO: 32 (disable get_player_names call client-side)
#    type: int
# csm_restriction_flags = 60

#    If the CSM restriction for node range is enabled, get_node calls are limited
#    to this distance from the player to the node.
#    type: int
# csm_restriction_noderange = 0

## Security

#    Prevent mods from doing insecure things like running shell commands.
#    type: bool
# secure.enable_security = true

#    Comma-separated list of trusted mods that are allowed to access insecure
#    functions even when mod security is on (via request_insecure_environment()).
#    type: string
# secure.trusted_mods =

#    Comma-separated list of mods that are allowed to access HTTP APIs, which
#    allow them to upload and download data to/from the internet.
#    type: string
# secure.http_mods =

## Advanced

### Profiling

#    Load the game profiler to collect game profiling data.
#    Provides a /profiler command to access the compiled profile.
#    Useful for mod developers and server operators.
#    type: bool
# profiler.load = false

#    The default format in which profiles are being saved,
#    when calling `/profiler save [format]` without format.
#    type: enum values: txt, csv, lua, json, json_pretty
# profiler.default_report_format = txt

#    The file path relative to your worldpath in which profiles will be saved to.
#    type: string
# profiler.report_path = ""

#### Instrumentation

#    Instrument the methods of entities on registration.
#    type: bool
# instrument.entity = true

#    Instrument the action function of Active Block Modifiers on registration.
#    type: bool
# instrument.abm = true

#    Instrument the action function of Loading Block Modifiers on registration.
#    type: bool
# instrument.lbm = true

#    Instrument chatcommands on registration.
#    type: bool
# instrument.chatcommand = true

#    Instrument global callback functions on registration.
#    (anything you pass to a minetest.register_*() function)
#    type: bool
# instrument.global_callback = true

##### Advanced

#    Instrument builtin.
#    This is usually only needed by core/builtin contributors
#    type: bool
# instrument.builtin = false

#    Have the profiler instrument itself:
#    * Instrument an empty function.
#    This estimates the overhead, that instrumentation is adding (+1 function call).
#    * Instrument the sampler being used to update the statistics.
#    type: bool
# instrument.profiler = false

#
# Client and Server
#

#    Name of the player.
#    When running a server, clients connecting with this name are admins.
#    When starting from the main menu, this is overridden.
#    type: string
# name =

#    Set the language. Leave empty to use the system language.
#    A restart is required after changing this.
#    type: enum values: , ar, ca, cs, da, de, dv, el, en, eo, es, et, eu, fil, fr, hu, id, it, ja, ja_KS, jbo, kk, kn, lo, lt, ms, my, nb, nl, nn, pl, pt, pt_BR, ro, ru, sl, sr_Cyrl, sv, sw, th, tr, uk, vi
# language =

#    Level of logging to be written to debug.txt:
#    -    <nothing> (no logging)
#    -    none (messages with no level)
#    -    error
#    -    warning
#    -    action
#    -    info
#    -    verbose
#    type: enum values: , none, error, warning, action, info, verbose
# debug_log_level = action

#    If the file size of debug.txt exceeds the number of megabytes specified in
#    this setting when it is opened, the file is moved to debug.txt.1,
#    deleting an older debug.txt.1 if it exists.
#    debug.txt is only moved if this setting is positive.
#    type: int
# debug_log_size_max = 50

#    Minimal level of logging to be written to chat.
#    type: enum values: , none, error, warning, action, info, verbose
# chat_log_level = error

#    Enable IPv6 support (for both client and server).
#    Required for IPv6 connections to work at all.
#    type: bool
# enable_ipv6 = true

## Advanced

#    Default timeout for cURL, stated in milliseconds.
#    Only has an effect if compiled with cURL.
#    type: int
# curl_timeout = 5000

#    Limits number of parallel HTTP requests. Affects:
#    -    Media fetch if server uses remote_media setting.
#    -    Serverlist download and server announcement.
#    -    Downloads performed by main menu (e.g. mod manager).
#    Only has an effect if compiled with cURL.
#    type: int
# curl_parallel_limit = 8

#    Maximum time in ms a file download (e.g. a mod download) may take.
#    type: int
# curl_file_download_timeout = 300000

#    Makes DirectX work with LuaJIT. Disable if it causes troubles.
#    type: bool
# high_precision_fpu = true

#    Replaces the default main menu with a custom one.
#    type: string
# main_menu_script =

#    Print the engine's profiling data in regular intervals (in seconds).
#    0 = disable. Useful for developers.
#    type: int
# profiler_print_interval = 0

#
# Mapgen
#

#    Name of map generator to be used when creating a new world.
#    Creating a world in the main menu will override this.
#    Current mapgens in a highly unstable state:
#    -    The optional floatlands of v7 (disabled by default).
#    type: enum values: v7, valleys, carpathian, v5, flat, fractal, singlenode, v6
# mg_name = v7

#    Water surface level of the world.
#    type: int
# water_level = 1

#    From how far blocks are generated for clients, stated in mapblocks (16 nodes).
#    type: int
# max_block_generate_distance = 10

#    Limit of map generation, in nodes, in all 6 directions from (0, 0, 0).
#    Only mapchunks completely within the mapgen limit are generated.
#    Value is stored per-world.
#    type: int min: 0 max: 31000
# mapgen_limit = 31000

#    Global map generation attributes.
#    In Mapgen v6 the 'decorations' flag controls all decorations except trees
#    and junglegrass, in all other mapgens this flag controls all decorations.
#    type: flags possible values: caves, dungeons, light, decorations, biomes, ores, nocaves, nodungeons, nolight, nodecorations, nobiomes, noores
# mg_flags = caves,dungeons,light,decorations,biomes,ores

## Biome API temperature and humidity noise parameters

#    Temperature variation for biomes.
#    type: noise_params_2d
# mg_biome_np_heat = {
#    offset      = 50,
#    scale       = 50,
#    spread      = (1000, 1000, 1000),
#    seed        = 5349,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Small-scale temperature variation for blending biomes on borders.
#    type: noise_params_2d
# mg_biome_np_heat_blend = {
#    offset      = 0,
#    scale       = 1.5,
#    spread      = (8, 8, 8),
#    seed        = 13,
#    octaves     = 2,
#    persistence = 1.0,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Humidity variation for biomes.
#    type: noise_params_2d
# mg_biome_np_humidity = {
#    offset      = 50,
#    scale       = 50,
#    spread      = (1000, 1000, 1000),
#    seed        = 842,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Small-scale humidity variation for blending biomes on borders.
#    type: noise_params_2d
# mg_biome_np_humidity_blend = {
#    offset      = 0,
#    scale       = 1.5,
#    spread      = (8, 8, 8),
#    seed        = 90003,
#    octaves     = 2,
#    persistence = 1.0,
#    lacunarity  = 2.0,
#    flags       = eased
# }

## Mapgen V5

#    Map generation attributes specific to Mapgen v5.
#    type: flags possible values: caverns, nocaverns
# mgv5_spflags = caverns

#    Controls width of tunnels, a smaller value creates wider tunnels.
#    Value >= 10.0 completely disables generation of tunnels and avoids the
#    intensive noise calculations.
#    type: float
# mgv5_cave_width = 0.09

#    Y of upper limit of large caves.
#    type: int
# mgv5_large_cave_depth = -256

#    Minimum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgv5_small_cave_num_min = 0

#    Maximum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgv5_small_cave_num_max = 0

#    Minimum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgv5_large_cave_num_min = 0

#    Maximum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgv5_large_cave_num_max = 2

#    Proportion of large caves that contain liquid.
#    type: float min: 0 max: 1
# mgv5_large_cave_flooded = 0.5

#    Y-level of cavern upper limit.
#    type: int
# mgv5_cavern_limit = -256

#    Y-distance over which caverns expand to full size.
#    type: int
# mgv5_cavern_taper = 256

#    Defines full size of caverns, smaller values create larger caverns.
#    type: float
# mgv5_cavern_threshold = 0.7

#    Lower Y limit of dungeons.
#    type: int
# mgv5_dungeon_ymin = -31000

#    Upper Y limit of dungeons.
#    type: int
# mgv5_dungeon_ymax = 31000

### Noises

#    Variation of biome filler depth.
#    type: noise_params_2d
# mgv5_np_filler_depth = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (150, 150, 150),
#    seed        = 261,
#    octaves     = 4,
#    persistence = 0.7,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Variation of terrain vertical scale.
#    When noise is < -0.55 terrain is near-flat.
#    type: noise_params_2d
# mgv5_np_factor = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (250, 250, 250),
#    seed        = 920381,
#    octaves     = 3,
#    persistence = 0.45,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Y-level of average terrain surface.
#    type: noise_params_2d
# mgv5_np_height = {
#    offset      = 0,
#    scale       = 10,
#    spread      = (250, 250, 250),
#    seed        = 84174,
#    octaves     = 4,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    First of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgv5_np_cave1 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (61, 61, 61),
#    seed        = 52534,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    Second of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgv5_np_cave2 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (67, 67, 67),
#    seed        = 10325,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    3D noise defining giant caverns.
#    type: noise_params_3d
# mgv5_np_cavern = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (384, 128, 384),
#    seed        = 723,
#    octaves     = 5,
#    persistence = 0.63,
#    lacunarity  = 2.0,
#    flags       =
# }

#    3D noise defining terrain.
#    type: noise_params_3d
# mgv5_np_ground = {
#    offset      = 0,
#    scale       = 40,
#    spread      = (80, 80, 80),
#    seed        = 983240,
#    octaves     = 4,
#    persistence = 0.55,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    3D noise that determines number of dungeons per mapchunk.
#    type: noise_params_3d
# mgv5_np_dungeons = {
#    offset      = 0.9,
#    scale       = 0.5,
#    spread      = (500, 500, 500),
#    seed        = 0,
#    octaves     = 2,
#    persistence = 0.8,
#    lacunarity  = 2.0,
#    flags       =
# }

## Mapgen V6

#    Map generation attributes specific to Mapgen v6.
#    The 'snowbiomes' flag enables the new 5 biome system.
#    When the 'snowbiomes' flag is enabled jungles are automatically enabled and
#    the 'jungles' flag is ignored.
#    type: flags possible values: jungles, biomeblend, mudflow, snowbiomes, flat, trees, nojungles, nobiomeblend, nomudflow, nosnowbiomes, noflat, notrees
# mgv6_spflags = jungles,biomeblend,mudflow,snowbiomes,noflat,trees

#    Deserts occur when np_biome exceeds this value.
#    When the 'snowbiomes' flag is enabled, this is ignored.
#    type: float
# mgv6_freq_desert = 0.45

#    Sandy beaches occur when np_beach exceeds this value.
#    type: float
# mgv6_freq_beach = 0.15

#    Lower Y limit of dungeons.
#    type: int
# mgv6_dungeon_ymin = -31000

#    Upper Y limit of dungeons.
#    type: int
# mgv6_dungeon_ymax = 31000

### Noises

#    Y-level of lower terrain and seabed.
#    type: noise_params_2d
# mgv6_np_terrain_base = {
#    offset      = -4,
#    scale       = 20,
#    spread      = (250, 250, 250),
#    seed        = 82341,
#    octaves     = 5,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Y-level of higher terrain that creates cliffs.
#    type: noise_params_2d
# mgv6_np_terrain_higher = {
#    offset      = 20,
#    scale       = 16,
#    spread      = (500, 500, 500),
#    seed        = 85039,
#    octaves     = 5,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Varies steepness of cliffs.
#    type: noise_params_2d
# mgv6_np_steepness = {
#    offset      = 0.85,
#    scale       = 0.5,
#    spread      = (125, 125, 125),
#    seed        = -932,
#    octaves     = 5,
#    persistence = 0.7,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Defines distribution of higher terrain.
#    type: noise_params_2d
# mgv6_np_height_select = {
#    offset      = 0.5,
#    scale       = 1,
#    spread      = (250, 250, 250),
#    seed        = 4213,
#    octaves     = 5,
#    persistence = 0.69,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Varies depth of biome surface nodes.
#    type: noise_params_2d
# mgv6_np_mud = {
#    offset      = 4,
#    scale       = 2,
#    spread      = (200, 200, 200),
#    seed        = 91013,
#    octaves     = 3,
#    persistence = 0.55,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Defines areas with sandy beaches.
#    type: noise_params_2d
# mgv6_np_beach = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (250, 250, 250),
#    seed        = 59420,
#    octaves     = 3,
#    persistence = 0.50,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Temperature variation for biomes.
#    type: noise_params_2d
# mgv6_np_biome = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (500, 500, 500),
#    seed        = 9130,
#    octaves     = 3,
#    persistence = 0.50,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Variation of number of caves.
#    type: noise_params_2d
# mgv6_np_cave = {
#    offset      = 6,
#    scale       = 6,
#    spread      = (250, 250, 250),
#    seed        = 34329,
#    octaves     = 3,
#    persistence = 0.50,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Humidity variation for biomes.
#    type: noise_params_2d
# mgv6_np_humidity = {
#    offset      = 0.5,
#    scale       = 0.5,
#    spread      = (500, 500, 500),
#    seed        = 72384,
#    octaves     = 3,
#    persistence = 0.50,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Defines tree areas and tree density.
#    type: noise_params_2d
# mgv6_np_trees = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (125, 125, 125),
#    seed        = 2,
#    octaves     = 4,
#    persistence = 0.66,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Defines areas where trees have apples.
#    type: noise_params_2d
# mgv6_np_apple_trees = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (100, 100, 100),
#    seed        = 342902,
#    octaves     = 3,
#    persistence = 0.45,
#    lacunarity  = 2.0,
#    flags       = eased
# }

## Mapgen V7

#    Map generation attributes specific to Mapgen v7.
#    'ridges': Rivers.
#    'floatlands': Floating land masses in the atmosphere.
#    'caverns': Giant caves deep underground.
#    type: flags possible values: mountains, ridges, floatlands, caverns, nomountains, noridges, nofloatlands, nocaverns
# mgv7_spflags = mountains,ridges,nofloatlands,caverns

#    Y of mountain density gradient zero level. Used to shift mountains vertically.
#    type: int
# mgv7_mount_zero_level = 0

#    Lower Y limit of floatlands.
#    type: int
# mgv7_floatland_ymin = 1024

#    Upper Y limit of floatlands.
#    type: int
# mgv7_floatland_ymax = 4096

#    Y-distance over which floatlands taper from full density to nothing.
#    Tapering starts at this distance from the Y limit.
#    For a solid floatland layer, this controls the height of hills/mountains.
#    Must be less than or equal to half the distance between the Y limits.
#    type: int
# mgv7_floatland_taper = 256

#    Exponent of the floatland tapering. Alters the tapering behaviour.
#    Value = 1.0 creates a uniform, linear tapering.
#    Values > 1.0 create a smooth tapering suitable for the default separated
#    floatlands.
#    Values < 1.0 (for example 0.25) create a more defined surface level with
#    flatter lowlands, suitable for a solid floatland layer.
#    type: float
# mgv7_float_taper_exp = 2.0

#    Adjusts the density of the floatland layer.
#    Increase value to increase density. Can be positive or negative.
#    Value = 0.0: 50% of volume is floatland.
#    Value = 2.0 (can be higher depending on 'mgv7_np_floatland', always test
#    to be sure) creates a solid floatland layer.
#    type: float
# mgv7_floatland_density = -0.6

#    Surface level of optional water placed on a solid floatland layer.
#    Water is disabled by default and will only be placed if this value is set
#    to above 'mgv7_floatland_ymax' - 'mgv7_floatland_taper' (the start of the
#    upper tapering).
#    ***WARNING, POTENTIAL DANGER TO WORLDS AND SERVER PERFORMANCE***:
#    When enabling water placement the floatlands must be configured and tested
#    to be a solid layer by setting 'mgv7_floatland_density' to 2.0 (or other
#    required value depending on 'mgv7_np_floatland'), to avoid
#    server-intensive extreme water flow and to avoid vast flooding of the
#    world surface below.
#    type: int
# mgv7_floatland_ywater = -31000

#    Controls width of tunnels, a smaller value creates wider tunnels.
#    Value >= 10.0 completely disables generation of tunnels and avoids the
#    intensive noise calculations.
#    type: float
# mgv7_cave_width = 0.09

#    Y of upper limit of large caves.
#    type: int
# mgv7_large_cave_depth = -33

#    Minimum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgv7_small_cave_num_min = 0

#    Maximum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgv7_small_cave_num_max = 0

#    Minimum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgv7_large_cave_num_min = 0

#    Maximum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgv7_large_cave_num_max = 2

#    Proportion of large caves that contain liquid.
#    type: float min: 0 max: 1
# mgv7_large_cave_flooded = 0.5

#    Y-level of cavern upper limit.
#    type: int
# mgv7_cavern_limit = -256

#    Y-distance over which caverns expand to full size.
#    type: int
# mgv7_cavern_taper = 256

#    Defines full size of caverns, smaller values create larger caverns.
#    type: float
# mgv7_cavern_threshold = 0.7

#    Lower Y limit of dungeons.
#    type: int
# mgv7_dungeon_ymin = -31000

#    Upper Y limit of dungeons.
#    type: int
# mgv7_dungeon_ymax = 31000

### Noises

#    Y-level of higher terrain that creates cliffs.
#    type: noise_params_2d
# mgv7_np_terrain_base = {
#    offset      = 4,
#    scale       = 70,
#    spread      = (600, 600, 600),
#    seed        = 82341,
#    octaves     = 5,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Y-level of lower terrain and seabed.
#    type: noise_params_2d
# mgv7_np_terrain_alt = {
#    offset      = 4,
#    scale       = 25,
#    spread      = (600, 600, 600),
#    seed        = 5934,
#    octaves     = 5,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Varies roughness of terrain.
#    Defines the 'persistence' value for terrain_base and terrain_alt noises.
#    type: noise_params_2d
# mgv7_np_terrain_persist = {
#    offset      = 0.6,
#    scale       = 0.1,
#    spread      = (2000, 2000, 2000),
#    seed        = 539,
#    octaves     = 3,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Defines distribution of higher terrain and steepness of cliffs.
#    type: noise_params_2d
# mgv7_np_height_select = {
#    offset      = -8,
#    scale       = 16,
#    spread      = (500, 500, 500),
#    seed        = 4213,
#    octaves     = 6,
#    persistence = 0.7,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Variation of biome filler depth.
#    type: noise_params_2d
# mgv7_np_filler_depth = {
#    offset      = 0,
#    scale       = 1.2,
#    spread      = (150, 150, 150),
#    seed        = 261,
#    octaves     = 3,
#    persistence = 0.7,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Variation of maximum mountain height (in nodes).
#    type: noise_params_2d
# mgv7_np_mount_height = {
#    offset      = 256,
#    scale       = 112,
#    spread      = (1000, 1000, 1000),
#    seed        = 72449,
#    octaves     = 3,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Defines large-scale river channel structure.
#    type: noise_params_2d
# mgv7_np_ridge_uwater = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (1000, 1000, 1000),
#    seed        = 85039,
#    octaves     = 5,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    3D noise defining mountain structure and height.
#    Also defines structure of floatland mountain terrain.
#    type: noise_params_3d
# mgv7_np_mountain = {
#    offset      = -0.6,
#    scale       = 1,
#    spread      = (250, 350, 250),
#    seed        = 5333,
#    octaves     = 5,
#    persistence = 0.63,
#    lacunarity  = 2.0,
#    flags       =
# }

#    3D noise defining structure of river canyon walls.
#    type: noise_params_3d
# mgv7_np_ridge = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (100, 100, 100),
#    seed        = 6467,
#    octaves     = 4,
#    persistence = 0.75,
#    lacunarity  = 2.0,
#    flags       =
# }

#    3D noise defining structure of floatlands.
#    If altered from the default, the noise 'scale' (0.7 by default) may need
#    to be adjusted, as floatland tapering functions best when this noise has
#    a value range of approximately -2.0 to 2.0.
#    type: noise_params_3d
# mgv7_np_floatland = {
#    offset      = 0,
#    scale       = 0.7,
#    spread      = (384, 96, 384),
#    seed        = 1009,
#    octaves     = 4,
#    persistence = 0.75,
#    lacunarity  = 1.618,
#    flags       =
# }

#    3D noise defining giant caverns.
#    type: noise_params_3d
# mgv7_np_cavern = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (384, 128, 384),
#    seed        = 723,
#    octaves     = 5,
#    persistence = 0.63,
#    lacunarity  = 2.0,
#    flags       =
# }

#    First of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgv7_np_cave1 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (61, 61, 61),
#    seed        = 52534,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    Second of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgv7_np_cave2 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (67, 67, 67),
#    seed        = 10325,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    3D noise that determines number of dungeons per mapchunk.
#    type: noise_params_3d
# mgv7_np_dungeons = {
#    offset      = 0.9,
#    scale       = 0.5,
#    spread      = (500, 500, 500),
#    seed        = 0,
#    octaves     = 2,
#    persistence = 0.8,
#    lacunarity  = 2.0,
#    flags       =
# }

## Mapgen Carpathian

#    Map generation attributes specific to Mapgen Carpathian.
#    type: flags possible values: caverns, rivers, nocaverns, norivers
# mgcarpathian_spflags = caverns,norivers

#    Defines the base ground level.
#    type: float
# mgcarpathian_base_level = 12.0

#    Defines the width of the river channel.
#    type: float
# mgcarpathian_river_width = 0.05

#    Defines the depth of the river channel.
#    type: float
# mgcarpathian_river_depth = 24.0

#    Defines the width of the river valley.
#    type: float
# mgcarpathian_valley_width = 0.25

#    Controls width of tunnels, a smaller value creates wider tunnels.
#    Value >= 10.0 completely disables generation of tunnels and avoids the
#    intensive noise calculations.
#    type: float
# mgcarpathian_cave_width = 0.09

#    Y of upper limit of large caves.
#    type: int
# mgcarpathian_large_cave_depth = -33

#    Minimum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgcarpathian_small_cave_num_min = 0

#    Maximum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgcarpathian_small_cave_num_max = 0

#    Minimum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgcarpathian_large_cave_num_min = 0

#    Maximum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgcarpathian_large_cave_num_max = 2

#    Proportion of large caves that contain liquid.
#    type: float min: 0 max: 1
# mgcarpathian_large_cave_flooded = 0.5

#    Y-level of cavern upper limit.
#    type: int
# mgcarpathian_cavern_limit = -256

#    Y-distance over which caverns expand to full size.
#    type: int
# mgcarpathian_cavern_taper = 256

#    Defines full size of caverns, smaller values create larger caverns.
#    type: float
# mgcarpathian_cavern_threshold = 0.7

#    Lower Y limit of dungeons.
#    type: int
# mgcarpathian_dungeon_ymin = -31000

#    Upper Y limit of dungeons.
#    type: int
# mgcarpathian_dungeon_ymax = 31000

### Noises

#    Variation of biome filler depth.
#    type: noise_params_2d
# mgcarpathian_np_filler_depth = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (128, 128, 128),
#    seed        = 261,
#    octaves     = 3,
#    persistence = 0.7,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    First of 4 2D noises that together define hill/mountain range height.
#    type: noise_params_2d
# mgcarpathian_np_height1 = {
#    offset      = 0,
#    scale       = 5,
#    spread      = (251, 251, 251),
#    seed        = 9613,
#    octaves     = 5,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Second of 4 2D noises that together define hill/mountain range height.
#    type: noise_params_2d
# mgcarpathian_np_height2 = {
#    offset      = 0,
#    scale       = 5,
#    spread      = (383, 383, 383),
#    seed        = 1949,
#    octaves     = 5,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Third of 4 2D noises that together define hill/mountain range height.
#    type: noise_params_2d
# mgcarpathian_np_height3 = {
#    offset      = 0,
#    scale       = 5,
#    spread      = (509, 509, 509),
#    seed        = 3211,
#    octaves     = 5,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Fourth of 4 2D noises that together define hill/mountain range height.
#    type: noise_params_2d
# mgcarpathian_np_height4 = {
#    offset      = 0,
#    scale       = 5,
#    spread      = (631, 631, 631),
#    seed        = 1583,
#    octaves     = 5,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    2D noise that controls the size/occurrence of rolling hills.
#    type: noise_params_2d
# mgcarpathian_np_hills_terrain = {
#    offset      = 1,
#    scale       = 1,
#    spread      = (1301, 1301, 1301),
#    seed        = 1692,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    2D noise that controls the size/occurrence of ridged mountain ranges.
#    type: noise_params_2d
# mgcarpathian_np_ridge_terrain = {
#    offset      = 1,
#    scale       = 1,
#    spread      = (1889, 1889, 1889),
#    seed        = 3568,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    2D noise that controls the size/occurrence of step mountain ranges.
#    type: noise_params_2d
# mgcarpathian_np_step_terrain = {
#    offset      = 1,
#    scale       = 1,
#    spread      = (1889, 1889, 1889),
#    seed        = 4157,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    2D noise that controls the shape/size of rolling hills.
#    type: noise_params_2d
# mgcarpathian_np_hills = {
#    offset      = 0,
#    scale       = 3,
#    spread      = (257, 257, 257),
#    seed        = 6604,
#    octaves     = 6,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    2D noise that controls the shape/size of ridged mountains.
#    type: noise_params_2d
# mgcarpathian_np_ridge_mnt = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (743, 743, 743),
#    seed        = 5520,
#    octaves     = 6,
#    persistence = 0.7,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    2D noise that controls the shape/size of step mountains.
#    type: noise_params_2d
# mgcarpathian_np_step_mnt = {
#    offset      = 0,
#    scale       = 8,
#    spread      = (509, 509, 509),
#    seed        = 2590,
#    octaves     = 6,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    2D noise that locates the river valleys and channels.
#    type: noise_params_2d
# mgcarpathian_np_rivers = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (1000, 1000, 1000),
#    seed        = 85039,
#    octaves     = 5,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    3D noise for mountain overhangs, cliffs, etc. Usually small variations.
#    type: noise_params_3d
# mgcarpathian_np_mnt_var = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (499, 499, 499),
#    seed        = 2490,
#    octaves     = 5,
#    persistence = 0.55,
#    lacunarity  = 2.0,
#    flags       =
# }

#    First of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgcarpathian_np_cave1 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (61, 61, 61),
#    seed        = 52534,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    Second of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgcarpathian_np_cave2 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (67, 67, 67),
#    seed        = 10325,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    3D noise defining giant caverns.
#    type: noise_params_3d
# mgcarpathian_np_cavern = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (384, 128, 384),
#    seed        = 723,
#    octaves     = 5,
#    persistence = 0.63,
#    lacunarity  = 2.0,
#    flags       =
# }

#    3D noise that determines number of dungeons per mapchunk.
#    type: noise_params_3d
# mgcarpathian_np_dungeons = {
#    offset      = 0.9,
#    scale       = 0.5,
#    spread      = (500, 500, 500),
#    seed        = 0,
#    octaves     = 2,
#    persistence = 0.8,
#    lacunarity  = 2.0,
#    flags       =
# }

## Mapgen Flat

#    Map generation attributes specific to Mapgen Flat.
#    Occasional lakes and hills can be added to the flat world.
#    type: flags possible values: lakes, hills, caverns, nolakes, nohills, nocaverns
# mgflat_spflags = nolakes,nohills,nocaverns

#    Y of flat ground.
#    type: int
# mgflat_ground_level = 8

#    Y of upper limit of large caves.
#    type: int
# mgflat_large_cave_depth = -33

#    Minimum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgflat_small_cave_num_min = 0

#    Maximum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgflat_small_cave_num_max = 0

#    Minimum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgflat_large_cave_num_min = 0

#    Maximum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgflat_large_cave_num_max = 2

#    Proportion of large caves that contain liquid.
#    type: float min: 0 max: 1
# mgflat_large_cave_flooded = 0.5

#    Controls width of tunnels, a smaller value creates wider tunnels.
#    Value >= 10.0 completely disables generation of tunnels and avoids the
#    intensive noise calculations.
#    type: float
# mgflat_cave_width = 0.09

#    Terrain noise threshold for lakes.
#    Controls proportion of world area covered by lakes.
#    Adjust towards 0.0 for a larger proportion.
#    type: float
# mgflat_lake_threshold = -0.45

#    Controls steepness/depth of lake depressions.
#    type: float
# mgflat_lake_steepness = 48.0

#    Terrain noise threshold for hills.
#    Controls proportion of world area covered by hills.
#    Adjust towards 0.0 for a larger proportion.
#    type: float
# mgflat_hill_threshold = 0.45

#    Controls steepness/height of hills.
#    type: float
# mgflat_hill_steepness = 64.0

#    Y-level of cavern upper limit.
#    type: int
# mgflat_cavern_limit = -256

#    Y-distance over which caverns expand to full size.
#    type: int
# mgflat_cavern_taper = 256

#    Defines full size of caverns, smaller values create larger caverns.
#    type: float
# mgflat_cavern_threshold = 0.7

#    Lower Y limit of dungeons.
#    type: int
# mgflat_dungeon_ymin = -31000

#    Upper Y limit of dungeons.
#    type: int
# mgflat_dungeon_ymax = 31000

### Noises

#    Defines location and terrain of optional hills and lakes.
#    type: noise_params_2d
# mgflat_np_terrain = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (600, 600, 600),
#    seed        = 7244,
#    octaves     = 5,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Variation of biome filler depth.
#    type: noise_params_2d
# mgflat_np_filler_depth = {
#    offset      = 0,
#    scale       = 1.2,
#    spread      = (150, 150, 150),
#    seed        = 261,
#    octaves     = 3,
#    persistence = 0.7,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    First of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgflat_np_cave1 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (61, 61, 61),
#    seed        = 52534,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    Second of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgflat_np_cave2 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (67, 67, 67),
#    seed        = 10325,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    3D noise defining giant caverns.
#    type: noise_params_3d
# mgflat_np_cavern = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (384, 128, 384),
#    seed        = 723,
#    octaves     = 5,
#    persistence = 0.63,
#    lacunarity  = 2.0,
#    flags       =
# }

#    3D noise that determines number of dungeons per mapchunk.
#    type: noise_params_3d
# mgflat_np_dungeons = {
#    offset      = 0.9,
#    scale       = 0.5,
#    spread      = (500, 500, 500),
#    seed        = 0,
#    octaves     = 2,
#    persistence = 0.8,
#    lacunarity  = 2.0,
#    flags       =
# }

## Mapgen Fractal

#    Map generation attributes specific to Mapgen Fractal.
#    'terrain' enables the generation of non-fractal terrain:
#    ocean, islands and underground.
#    type: flags possible values: terrain, noterrain
# mgfractal_spflags = terrain

#    Controls width of tunnels, a smaller value creates wider tunnels.
#    Value >= 10.0 completely disables generation of tunnels and avoids the
#    intensive noise calculations.
#    type: float
# mgfractal_cave_width = 0.09

#    Y of upper limit of large caves.
#    type: int
# mgfractal_large_cave_depth = -33

#    Minimum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgfractal_small_cave_num_min = 0

#    Maximum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgfractal_small_cave_num_max = 0

#    Minimum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgfractal_large_cave_num_min = 0

#    Maximum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgfractal_large_cave_num_max = 2

#    Proportion of large caves that contain liquid.
#    type: float min: 0 max: 1
# mgfractal_large_cave_flooded = 0.5

#    Lower Y limit of dungeons.
#    type: int
# mgfractal_dungeon_ymin = -31000

#    Upper Y limit of dungeons.
#    type: int
# mgfractal_dungeon_ymax = 31000

#    Selects one of 18 fractal types.
#    1 = 4D "Roundy" Mandelbrot set.
#    2 = 4D "Roundy" Julia set.
#    3 = 4D "Squarry" Mandelbrot set.
#    4 = 4D "Squarry" Julia set.
#    5 = 4D "Mandy Cousin" Mandelbrot set.
#    6 = 4D "Mandy Cousin" Julia set.
#    7 = 4D "Variation" Mandelbrot set.
#    8 = 4D "Variation" Julia set.
#    9 = 3D "Mandelbrot/Mandelbar" Mandelbrot set.
#    10 = 3D "Mandelbrot/Mandelbar" Julia set.
#    11 = 3D "Christmas Tree" Mandelbrot set.
#    12 = 3D "Christmas Tree" Julia set.
#    13 = 3D "Mandelbulb" Mandelbrot set.
#    14 = 3D "Mandelbulb" Julia set.
#    15 = 3D "Cosine Mandelbulb" Mandelbrot set.
#    16 = 3D "Cosine Mandelbulb" Julia set.
#    17 = 4D "Mandelbulb" Mandelbrot set.
#    18 = 4D "Mandelbulb" Julia set.
#    type: int min: 1 max: 18
# mgfractal_fractal = 1

#    Iterations of the recursive function.
#    Increasing this increases the amount of fine detail, but also
#    increases processing load.
#    At iterations = 20 this mapgen has a similar load to mapgen V7.
#    type: int
# mgfractal_iterations = 11

#    (X,Y,Z) scale of fractal in nodes.
#    Actual fractal size will be 2 to 3 times larger.
#    These numbers can be made very large, the fractal does
#    not have to fit inside the world.
#    Increase these to 'zoom' into the detail of the fractal.
#    Default is for a vertically-squashed shape suitable for
#    an island, set all 3 numbers equal for the raw shape.
#    type: v3f
# mgfractal_scale = (4096.0, 1024.0, 4096.0)

#    (X,Y,Z) offset of fractal from world center in units of 'scale'.
#    Can be used to move a desired point to (0, 0) to create a
#    suitable spawn point, or to allow 'zooming in' on a desired
#    point by increasing 'scale'.
#    The default is tuned for a suitable spawn point for Mandelbrot
#    sets with default parameters, it may need altering in other
#    situations.
#    Range roughly -2 to 2. Multiply by 'scale' for offset in nodes.
#    type: v3f
# mgfractal_offset = (1.79, 0.0, 0.0)

#    W coordinate of the generated 3D slice of a 4D fractal.
#    Determines which 3D slice of the 4D shape is generated.
#    Alters the shape of the fractal.
#    Has no effect on 3D fractals.
#    Range roughly -2 to 2.
#    type: float
# mgfractal_slice_w = 0.0

#    Julia set only.
#    X component of hypercomplex constant.
#    Alters the shape of the fractal.
#    Range roughly -2 to 2.
#    type: float
# mgfractal_julia_x = 0.33

#    Julia set only.
#    Y component of hypercomplex constant.
#    Alters the shape of the fractal.
#    Range roughly -2 to 2.
#    type: float
# mgfractal_julia_y = 0.33

#    Julia set only.
#    Z component of hypercomplex constant.
#    Alters the shape of the fractal.
#    Range roughly -2 to 2.
#    type: float
# mgfractal_julia_z = 0.33

#    Julia set only.
#    W component of hypercomplex constant.
#    Alters the shape of the fractal.
#    Has no effect on 3D fractals.
#    Range roughly -2 to 2.
#    type: float
# mgfractal_julia_w = 0.33

### Noises

#    Y-level of seabed.
#    type: noise_params_2d
# mgfractal_np_seabed = {
#    offset      = -14,
#    scale       = 9,
#    spread      = (600, 600, 600),
#    seed        = 41900,
#    octaves     = 5,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Variation of biome filler depth.
#    type: noise_params_2d
# mgfractal_np_filler_depth = {
#    offset      = 0,
#    scale       = 1.2,
#    spread      = (150, 150, 150),
#    seed        = 261,
#    octaves     = 3,
#    persistence = 0.7,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    First of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgfractal_np_cave1 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (61, 61, 61),
#    seed        = 52534,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    Second of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgfractal_np_cave2 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (67, 67, 67),
#    seed        = 10325,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    3D noise that determines number of dungeons per mapchunk.
#    type: noise_params_3d
# mgfractal_np_dungeons = {
#    offset      = 0.9,
#    scale       = 0.5,
#    spread      = (500, 500, 500),
#    seed        = 0,
#    octaves     = 2,
#    persistence = 0.8,
#    lacunarity  = 2.0,
#    flags       =
# }

## Mapgen Valleys

#    Map generation attributes specific to Mapgen Valleys.
#    'altitude_chill': Reduces heat with altitude.
#    'humid_rivers': Increases humidity around rivers.
#    'vary_river_depth': If enabled, low humidity and high heat causes rivers
#    to become shallower and occasionally dry.
#    'altitude_dry': Reduces humidity with altitude.
#    type: flags possible values: altitude_chill, humid_rivers, vary_river_depth, altitude_dry, noaltitude_chill, nohumid_rivers, novary_river_depth, noaltitude_dry
# mgvalleys_spflags = altitude_chill,humid_rivers,vary_river_depth,altitude_dry

#    The vertical distance over which heat drops by 20 if 'altitude_chill' is
#    enabled. Also the vertical distance over which humidity drops by 10 if
#    'altitude_dry' is enabled.
#    type: int
# mgvalleys_altitude_chill = 90

#    Depth below which you'll find large caves.
#    type: int
# mgvalleys_large_cave_depth = -33

#    Minimum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgvalleys_small_cave_num_min = 0

#    Maximum limit of random number of small caves per mapchunk.
#    type: int min: 0 max: 256
# mgvalleys_small_cave_num_max = 0

#    Minimum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgvalleys_large_cave_num_min = 0

#    Maximum limit of random number of large caves per mapchunk.
#    type: int min: 0 max: 64
# mgvalleys_large_cave_num_max = 2

#    Proportion of large caves that contain liquid.
#    type: float min: 0 max: 1
# mgvalleys_large_cave_flooded = 0.5

#    Depth below which you'll find giant caverns.
#    type: int
# mgvalleys_cavern_limit = -256

#    Y-distance over which caverns expand to full size.
#    type: int
# mgvalleys_cavern_taper = 192

#    Defines full size of caverns, smaller values create larger caverns.
#    type: float
# mgvalleys_cavern_threshold = 0.6

#    How deep to make rivers.
#    type: int
# mgvalleys_river_depth = 4

#    How wide to make rivers.
#    type: int
# mgvalleys_river_size = 5

#    Controls width of tunnels, a smaller value creates wider tunnels.
#    Value >= 10.0 completely disables generation of tunnels and avoids the
#    intensive noise calculations.
#    type: float
# mgvalleys_cave_width = 0.09

#    Lower Y limit of dungeons.
#    type: int
# mgvalleys_dungeon_ymin = -31000

#    Upper Y limit of dungeons.
#    type: int
# mgvalleys_dungeon_ymax = 63

### Noises

#    First of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgvalleys_np_cave1 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (61, 61, 61),
#    seed        = 52534,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    Second of two 3D noises that together define tunnels.
#    type: noise_params_3d
# mgvalleys_np_cave2 = {
#    offset      = 0,
#    scale       = 12,
#    spread      = (67, 67, 67),
#    seed        = 10325,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       =
# }

#    The depth of dirt or other biome filler node.
#    type: noise_params_2d
# mgvalleys_np_filler_depth = {
#    offset      = 0,
#    scale       = 1.2,
#    spread      = (256, 256, 256),
#    seed        = 1605,
#    octaves     = 3,
#    persistence = 0.5,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    3D noise defining giant caverns.
#    type: noise_params_3d
# mgvalleys_np_cavern = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (768, 256, 768),
#    seed        = 59033,
#    octaves     = 6,
#    persistence = 0.63,
#    lacunarity  = 2.0,
#    flags       =
# }

#    Defines large-scale river channel structure.
#    type: noise_params_2d
# mgvalleys_np_rivers = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (256, 256, 256),
#    seed        = -6050,
#    octaves     = 5,
#    persistence = 0.6,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Base terrain height.
#    type: noise_params_2d
# mgvalleys_np_terrain_height = {
#    offset      = -10,
#    scale       = 50,
#    spread      = (1024, 1024, 1024),
#    seed        = 5202,
#    octaves     = 6,
#    persistence = 0.4,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Raises terrain to make valleys around the rivers.
#    type: noise_params_2d
# mgvalleys_np_valley_depth = {
#    offset      = 5,
#    scale       = 4,
#    spread      = (512, 512, 512),
#    seed        = -1914,
#    octaves     = 1,
#    persistence = 1.0,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Slope and fill work together to modify the heights.
#    type: noise_params_3d
# mgvalleys_np_inter_valley_fill = {
#    offset      = 0,
#    scale       = 1,
#    spread      = (256, 512, 256),
#    seed        = 1993,
#    octaves     = 6,
#    persistence = 0.8,
#    lacunarity  = 2.0,
#    flags       =
# }

#    Amplifies the valleys.
#    type: noise_params_2d
# mgvalleys_np_valley_profile = {
#    offset      = 0.6,
#    scale       = 0.5,
#    spread      = (512, 512, 512),
#    seed        = 777,
#    octaves     = 1,
#    persistence = 1.0,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    Slope and fill work together to modify the heights.
#    type: noise_params_2d
# mgvalleys_np_inter_valley_slope = {
#    offset      = 0.5,
#    scale       = 0.5,
#    spread      = (128, 128, 128),
#    seed        = 746,
#    octaves     = 1,
#    persistence = 1.0,
#    lacunarity  = 2.0,
#    flags       = eased
# }

#    3D noise that determines number of dungeons per mapchunk.
#    type: noise_params_3d
# mgvalleys_np_dungeons = {
#    offset      = 0.9,
#    scale       = 0.5,
#    spread      = (500, 500, 500),
#    seed        = 0,
#    octaves     = 2,
#    persistence = 0.8,
#    lacunarity  = 2.0,
#    flags       =
# }

## Advanced

#    Size of mapchunks generated by mapgen, stated in mapblocks (16 nodes).
#    WARNING!: There is no benefit, and there are several dangers, in
#    increasing this value above 5.
#    Reducing this value increases cave and dungeon density.
#    Altering this value is for special usage, leaving it unchanged is
#    recommended.
#    type: int
# chunksize = 5

#    Dump the mapgen debug information.
#    type: bool
# enable_mapgen_debug_info = false

#    Maximum number of blocks that can be queued for loading.
#    type: int
# emergequeue_limit_total = 1024

#    Maximum number of blocks to be queued that are to be loaded from file.
#    This limit is enforced per player.
#    type: int
# emergequeue_limit_diskonly = 128

#    Maximum number of blocks to be queued that are to be generated.
#    This limit is enforced per player.
#    type: int
# emergequeue_limit_generate = 128

#    Number of emerge threads to use.
#    Value 0:
#    -    Automatic selection. The number of emerge threads will be
#    -    'number of processors - 2', with a lower limit of 1.
#    Any other value:
#    -    Specifies the number of emerge threads, with a lower limit of 1.
#    WARNING: Increasing the number of emerge threads increases engine mapgen
#    speed, but this may harm game performance by interfering with other
#    processes, especially in singleplayer and/or when running Lua code in
#    'on_generated'. For many users the optimum setting may be '1'.
#    type: int
# num_emerge_threads = 1

#
# Online Content Repository
#

#    The URL for the content repository
#    type: string
# contentdb_url = https://content.minetest.net

#    Comma-separated list of flags to hide in the content repository.
#    "nonfree" can be used to hide packages which do not qualify as 'free software',
#    as defined by the Free Software Foundation.
#    You can also specify content ratings.
#    These flags are independent from Minetest versions,
#    so see a full list at https://content.minetest.net/help/content_flags/
#    type: string
# contentdb_flag_blacklist = nonfree, desktop_default

#    Maximum number of concurrent downloads. Downloads exceeding this limit will be queued.
#    This should be lower than curl_parallel_limit.
#    type: int
# contentdb_max_concurrent_downloads = 3
