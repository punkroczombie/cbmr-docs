<!-- source: http://scpcbmr.42web.io/json_interfaces.html -->
# SCP: Containment Breach 2 Scripting: Addons configurations

|  |  |  |
| --- | --- | --- |
| Logo | SCP: Containment Breach 2 Scripting |  |

![](sync_on.png "click to disable panel synchronization")

- [▼](javascript:void(0))[SCP: Containment Breach 2 Scripting](index.md)

  - [▼](javascript:void(0))[AngelScript](index.md)

    - [Writing your first script](scripting_guide.md)
    - [How to add plugins](plugins.md)
    - [How to add addons](addons.md)
    - [Addons configurations](json_interfaces.md)
    - [Text Formatting Guide](text_formatting.md)
  - [►](javascript:void(0))[Topics](topics.md)
  - [►](javascript:void(0))[Classes](annotated.md)

[•All](javascript:void(0))[Classes](javascript:void(0))[Functions](javascript:void(0))[Variables](javascript:void(0))[Modules](javascript:void(0))[Pages](javascript:void(0))

Loading...

Searching...

No Matches

Addons configurations

### Table of Contents

- - [Description](json_interfaces.md)
  - [JSON Array: <tt>playermodels</tt>](json_interfaces.md)
    - [Sub-Array: <tt>idlesounds</tt>](json_interfaces.md)
    - [Sub-Array: <tt>animations</tt>](json_interfaces.md)
    - [Sub-Array: <tt>deadanimations</tt>](json_interfaces.md)
  - [Description](json_interfaces.md)
  - [JSON Array: <tt>playertextures</tt>](json_interfaces.md)
  - [Description](json_interfaces.md)
  - [JSON Array: <tt>playerweapontextures</tt>](json_interfaces.md)
  - [Description](json_interfaces.md)
  - [JSON Array: <tt>attaches</tt>](json_interfaces.md)
    - [Sub-Array: <tt>presets</tt>](json_interfaces.md)
    - [Sub-Array: <tt>sounds</tt>](json_interfaces.md)
  - [Description](json_interfaces.md)
  - [JSON Array: <tt>weapons</tt>](json_interfaces.md)
  - [Description](json_interfaces.md)
  - [JSON Array: <tt>items</tt>](json_interfaces.md)
  - [Description](json_interfaces.md)
  - [JSON Array: <tt>objects</tt>](json_interfaces.md)
  - [Description](json_interfaces.md)
  - [JSON Array: <tt>textures</tt>](json_interfaces.md)
  - [Description](json_interfaces.md)
  - [JSON Array: <tt>fonts</tt>](json_interfaces.md)
  - [JSON Array: <tt>spritefonts</tt>](json_interfaces.md)
  - [Description](json_interfaces.md)
  - [JSON Array: <tt>lights</tt>](json_interfaces.md)
  - [Description](json_interfaces.md)
  - [JSON Array: <tt>emitters</tt>](json_interfaces.md)

# Overview

This page documents the JSON structure used to define custom content (player models, weapons, items, etc.) for the server. The configuration is loaded from the main `addons.jsonc` file, specifically from sections defined within it. Each section corresponds to a specific type of game asset.

Warning
:   All IDs must be in the specified ranges. Empty filenames or IDs outside the valid range will cause errors and the entry will be skipped.

Note
:   If you use an already created object, it will replace the values. If no value is specified, the value of the already created object will be saved.

## Global Settings

- **serverfolder**: The internal name of the addon folder.
- **files**: An array of objects containing `url`, `export` (local filename), and `hash` for integrity checks.
- **roomtemplates**: Path to the `.ini` file defining new room layouts. (like a rooms.ini in Data folder)
- **materials**: Path to the `.ini` file defining new materials. (like a materials.ini in Data folder)

# [Player](class_player.md) Models

## Description

Defines custom player character models, their skeletal properties, animations, and gameplay attributes.

## JSON Array: `playermodels`

An array of objects, each defining one player model preset.

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Unique model ID. **Range:** `1` to `MAX_PLAYER_MODELS-1`. |
| `filename` | String | **Required** | Path to the model file (e.g., `.b3d`). Cannot be empty. |
| `offsety` | Float | 0.0 | Vertical offset applied to the entire model. |
| `offsetyaw` | Float | 0.0 | Yaw rotation offset applied to the entire model. |
| `headbone` | String | "" | Name of the bone used for the character's head. |
| `spinebone` | String | "" | Name of the main spine bone. |
| `handbone` | String | "" | Name of the primary hand bone (e.g., for holding items). |
| `forearmbone` | String | "" | Name of the forearm bone. |
| `maximumspinepitch` | Float | 0.0 | How many degrees the spine can pitch relative to the head. |
| `maximumspinepitchdist` | Float | 0.0 | Distance factor for spine pitch limitation. |
| `maximumheadpitch` | Float | 0.0 | Maximum pitch angle for the head bone. |
| `fixedspinerotation` | Float | 0.0 | Limit for spine yaw rotation. |
| `usedefaultrolls` | Boolean | false | If `true`, the first rotations of bones are cached and used as a baseline offset. |
| `collisionradius` | Float | **Required** | Radius of the player's collision |
| `scale` | Float | **Required** | Global scale for the model. |
| `stepsound` | String | "" | [Sound](class_sound.md) file path played for footsteps. Leave empty for none. |
| `stamina` | Float | 0.0 | Stamina consumption multiplier (`1.0 or 0.0` is default). Lower values reduce stamina drain. |
| `speed` | Float | 0.0 | Movement speed multiplier (`0.0` means no change from base speed). |
| `viewoffsety` | Float | 0.0 | Vertical offset for the player's camera (Y-axis). |
| `holdingitemoffsetx` | Float | 0.0 | X-offset for held items from the `handbone`. |
| `holdingitemoffsety` | Float | 0.0 | Y-offset for held items from the `handbone`. |
| `holdingitemoffsetz` | Float | 0.0 | Z-offset for held items from the `handbone`. |
| `holdingitemoffsetpitch` | Float | 0.0 | Pitch rotation offset for held items. |
| `holdingitemoffsetyaw` | Float | 0.0 | Yaw rotation offset for held items. |
| `holdingitemoffsetroll` | Float | 0.0 | Roll rotation offset for held items. |
| `forearmholdingpitch` | Float | 0.0 | Pitch rotation offset for the forearm when holding an item. |
| `forearmholdingyaw` | Float | 0.0 | Yaw rotation offset for the forearm when holding an item. |
| `forearmholdingroll` | Float | 0.0 | Roll rotation offset for the forearm when holding an item. |
| `hitboxwidth` | Float | **Required** | Width of the player's hitbox (relative to model's local transform). |
| `hitboxheight` | Float | **Required** | Height of the player's hitbox (relative to model's local transform). |
| `hitboxdepth` | Float | **Required** | Depth of the player's hitbox (relative to model's local transform). |
| `movesound` | String | "" | [Sound](class_sound.md) file played during continuous movement (e.g., for SCP-173). |
| `disableroll` | Boolean | false | If `true`, disables head bobbing (camera roll). |
| `disablebloodloss` | Boolean | false | If `true`, the player does not lose blood from injuries. |
| `disableinjuries` | Boolean | false | If `true`, the player cannot be injured. |
| `flippitch` | Boolean | false | **Temporary workaround.** Inverts pitch calculations for certain models. |
| `disableinteractitems` | Boolean | false | If `true`, the player cannot pick up or interact with items. |
| `rotationmode` | Integer | 0 | **Temporary workaround.** Changes the rotation order Euler calculation. `0`-`2` are valid. |
| `comparedspinerotation` | Boolean | false | **Temporary workaround.** Alters how spine rotation is compared to the body. |
| `disablejump` | Boolean | false | If `true`, the player cannot jump. |
| `material` | Integer | 0 | Surface material type. `0`: Flesh, `1`: Concrete (e.g., SCP-173). |
| `collisiontype` | Integer | 0 | Physics collision type. `6` is used for SCP-106. |
| `emitterbones` | String | "" | Names of bones used for particle emitters. (e.g. SCP-457) |
| `boneemitter` | Integer | 0 | Index for bone-based particle emitter. (e.g. SCP-457) |
| `copyattaches` | Integer | 0 | Copies every attachment from the specified model ID. |
| `constantinvisibility` | Boolean | false | If `true`, the player model is permanently invisible. |
| `lightradius` | Float | 0.0 | Radius of the dynamic light source attached to the player. |
| `lightshadows` | Boolean | false | If `true`, the player-attached light source will cast shadows. |
| `lightr` | Float | 0.0 | Red color component value for the attached light source. |
| `lightg` | Float | 0.0 | Green color component value for the attached light source. |
| `lightb` | Float | 0.0 | Blue color component value for the attached light source. |
| `lightscattering` | Float | 0.0 | Volumetric scattering force for the player's light source. |

### Sub-Array: `idlesounds`

An array of objects defining ambient/idle sounds played by the model.

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | [Sound](class_sound.md) slot ID. **Range:** `0` to `MAX_PLAYER_MODEL_SOUNDS-1`. |
| `filename` | String | **Required** | Path to the sound file (e.g., `.ogg`). |
| `selfplay` | Boolean | false | If `true`, the sound will be heard by everyone, including the one who triggered it. |

### Sub-Array: `animations`

An array of objects defining the model's standard animations (idle, walk, etc.).

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Animation ID. **Range:** `1` to `MAX_PLAYER_MODEL_ANIMATIONS-1`.   `1`: Idle, `2`: Walk, `3`: Run, `4`: Sitting-Idle, `5`: Sitting-Walk, `6`: Falling, `7`: Fell, `8`: Walk... |
| `start` | Integer | **Required** | Starting frame of the animation. |
| `end` | Integer | **Required** | Ending frame of the animation. |
| `speed` | Float | **Required** | Playback speed. |
| `stepaccum` | Float | **Required** | Accumulator for footsteps. Determines interval between step sounds (1 second = 70.0). |
| `bones` | String | "" | Specific bones for this animation. Enable blending. |
| `disablespine` | Boolean | false | If `true`, disables default spine bone procedural rotation during this animation. |

### Sub-Array: `deadanimations`

An array of objects defining animations played upon death. One is selected randomly.

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Dead animation ID. **Range:** `0` to `MAX_PLAYER_MODEL_DEAD_ANIMATIONS-1`. |
| `start` | Integer | **Required** | Starting frame. |
| `end` | Integer | **Required** | Ending frame. |
| `speed` | Float | **Required** | Playback speed. |

# [Player](class_player.md) Textures

## Description

Defines texture files that can be applied to player models.

## JSON Array: `playertextures`

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Unique texture ID. **Range:** `1` to `MAX_PLAYER_MODEL_TEXTURES-1`. |
| `filename` | String | **Required** | Path to the primary texture file (e.g., `.png`). Cannot be empty. |
| `terminatefilename` | String | "" | Path to an alternate texture used for terminated/dead state. (e.g. hazmat suit player model) |

# Weapon Textures

## Description

Defines the texture of the hands for the player's model.

## JSON Array: `playerweapontextures`

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Unique texture ID. **Range:** `1` to `MAX_PLAYER_MODEL_TEXTURES-1`. |
| `filename` | String | **Required** | Path to the texture file. Cannot be empty. |

# Attach Models

## Description

Defines models that can be attached to player models (e.g., hats, gear, weapon viewmodels).

## JSON Array: `attaches`

Base object for preloading an attachable model.

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Unique attach model ID. **Range:** `1` to `MAX_ATTACH_MODELS-1`. |
| `filename` | String | "" | Path to the attach model file. Can be empty if only defining presets. |
| `texture` | String | "" | Path to a default texture for this attach model. |
| `rigged` | Boolean | false | If `true`, the model is rigged/animated. |
| `playeranimation` | Int | false | If `true`, the model is rigged/animated. Sets the 'loop' animation of the player registered in playermodels. |
| `variety` | Integer | 0 | Number of visual variations for this attach model. If >0, requires corresponding `filename`/`texture` for the variety. |

### Sub-Array: `presets`

An array of objects defining how this attach model is positioned on specific player models.

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | The player model ID this preset applies to. **Range:** `1` to `MAX_PLAYER_MODELS-1`. |
| `bone` | String | (Not specified) | Name of the bone on the player model to attach to. |
| `offsetx` | Float | (Not specified) | X position offset from the bone. |
| `offsety` | Float | (Not specified) | Y position offset from the bone. |
| `offsetz` | Float | (Not specified) | Z position offset from the bone. |
| `offsetpitch` | Float | (Not specified) | Pitch rotation offset. |
| `offsetyaw` | Float | (Not specified) | Yaw rotation offset. |
| `offsetroll` | Float | (Not specified) | Roll rotation offset. |
| `scale` | Float | (Not specified) | Scale for the attach model on this player. |
| `variety` | Integer | (Not specified) | Which visual variation to use for this player model. |

### Sub-Array: `sounds`

An array of sound definitions for the attach model.

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | [Sound](class_sound.md) slot ID. **Range:** `0` to `MAX_ATTACH_MODEL_SOUNDS-1`. |
| `filename` | String | **Required** | Path to the sound file. |

# Weapons

## Description

Creates new weapons, defines their stats, shell ejection behavior, animations, and links them to in-game items.

## JSON Array: `weapons`

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Unique weapon ID. **Range:** `1` to `MAX_WEAPONS-1`. |
| `filename` | String | **Required** | Path to the weapon model file. Cannot be empty. |
| `weapontype` | Integer | 0 | Hold type. Defines player animation set. |
| `attachid` | Integer | **Required** | ID from the `attaches` array to use as the world/3rd person model. |
| `offsetx` | Float | (Not specified) | X offset of the viewmodel from the camera. |
| `offsety` | Float | (Not specified) | Y offset of the viewmodel from the camera. |
| `offsetz` | Float | (Not specified) | Z offset of the viewmodel from the camera. |
| `offsetpitch` | Float | (Not specified) | Pitch rotation offset of the viewmodel. |
| `offsetyaw` | Float | (Not specified) | Yaw rotation offset of the viewmodel. |
| `offsetroll` | Float | (Not specified) | Roll rotation offset of the viewmodel. |
| `scale` | Float | (Not specified) | Scale multiplier for the viewmodel. |
| `muzzleflashscale` | Float | (Not specified) | Scale of the muzzle flash effect on the viewmodel. |
| `muzzleflashyaw` | Float | (Not specified) | Yaw offset for the muzzle flash. |
| `worldmuzzleflashscale` | Float | (Not specified) | Scale of the muzzle flash effect on the world (3rd person) model. |
| `recoil` | Float | (Not specified) | Intensity of screen recoil (kick). |
| `spread` | Float | (Not specified) | Base bullet spread angle in degrees. |
| `shootrate` | Float | (Not specified) | Delay between shots in seconds. |
| `recoilseed` | Integer | (Not specified) | Seed for procedural recoil pattern. |
| `damage` | Float | (Not specified) | Base damage per hit. |
| `maxammo` | Integer | (Not specified) | Maximum total ammunition reserve when acquired. Values above 255 display as 255. |
| `maxclipammo` | Integer | (Not specified) | Ammunition capacity per magazine. Values above 65535 display as 65535. |
| `reloadtime` | Float | (Not specified) | Time in seconds for the reload animation to complete. |
| `shootscount` | Integer | 0 | Multiplier or tracker for total shot counts/burst bursts properties. |
| `shootrange` | Float | 0.0 | Effective range limit for the weapon's projectiles or raycasts. |
| `shootsound` | String | (Not specified) | Path to the sound file played on firing. |
| `reloadsound` | String | (Not specified) | Path to the sound file played during reload. |
| `deploysound` | String | (Not specified) | Path to the sound file played when equipping the weapon. |
| `shootstartsound` | String | (Not specified) | [Sound](class_sound.md) file played once when firing begins (regardless of ammo capacity). |
| `misssound` | String | "" | [Sound](class_sound.md) file path played when a shot misses targets. |
| `hitsounds` | Array of Strings | `[]` | A JSON array containing hit sounds for specified material. MATERIAL\_BODY = 0, MATERIAL\_CONCRETE = 1, MATERIAL\_METAL = 2, MATERIAL\_GLASS = 3. Array value must contain 'id' and 'hitsound' values. |
| `sightoffsetx` | Float | (Not specified) | X offset for the camera when aiming down sights (ADS). |
| `sightoffsety` | Float | (Not specified) | Y offset for the camera when aiming down sights (ADS). |
| `sightmultiplier` | Float | 1.0 | Zoom / FOV multiplier applied when aiming down sights. |
| `isviewmodel` | Boolean | false | If `true`, the weapon is treated as a non-functional viewmodel (e.g., for certain SCPS). |
| `applyitemtexture` | Boolean | false | If `true`, allows the weapon model to inherit skin textures directly from the linked item data. |
| `isselectable` | Boolean | true | If `false`, the weapon cannot be manually selected via slots. |
| `notexture` | Boolean | false | If `true`, the model will bypass updating or replacing the default hand textures. |
| `realtimetexture` | Boolean | false | Enables real-time rendering/updating of specialized procedural textures on the weapon. |
| `handsurface` | Integer | (Not specified) | Index for the hand texture surface assignments. |
| `pump` | Boolean | false | Enables shotgun pump-action logic delays and animations after firing. |
| `pellets` | Integer | (Not specified) | Number of projectiles fired simultaneously per single shot (for shotguns). |
| `combat` | Boolean | false | Tags weapon as a combat-active entity, altering AI behavior or stance checks. |
| `shootafteranim` | Boolean | false | If `true`, forces weapon firing logic to wait completely until the animation sequence finishes. |
| `playeranimation` | Integer | 0 | Custom animation index override assigned to the player model when using this weapon. |
| `shellbone` | String | (Not specified) | Name of the sub-mesh bone designated to disappear/hide upon firing a shell. |
| `shellmodel` | String | (Not specified) | 3D model file path utilized for ejected weapon shells. |
| `shellactionsound` | String | (Not specified) | [Sound](class_sound.md) path triggered upon shell event action or explosion. |
| `shellcollisionsound` | String | (Not specified) | [Sound](class_sound.md) path triggered when the ejected shell hits standard collision geometry. |
| `shellsound` | String | (Not specified) | Continuous ambient/loop sound file associated with the shell (e.g., RPG projectile noise). |
| `shellexplosion` | String | "" | Asset path or configuration pointer for shell-induced explosion effects. |
| `shelltimeout` | Integer | (Not specified) | Expiration lifetime of the spawned shell entity in seconds. |
| `shellspeed` | Float | (Not specified) | Initial ejection velocity/speed multiplier applied to the shell. |
| `shellradius` | Float | (Not specified) | Physics collision radius size for the shell model. |
| `shellscale` | Float | 1.0 | Visual scale factor applied to the shell model. |
| `shellimpacttime` | Float | (Not specified) | Time delay in seconds from initial impact before the shell triggers an explosive action. |
| `shellgravity` | Float | (Not specified) | Custom gravity acceleration factor applied to the shell physics entity. |
| `shellrestitution` | Float | (Not specified) | Bounciness/elasticity coefficient assigned to shell surface collisions. |
| `shellemitter` | Integer | -1 | Particle emitter index reference used during shell ejection events. |
| `shellactionemitter` | String | "" | Named tracking index or path for particle emitters bound to shell physics actions. |
| `shellforce` | Float | 0.0 | Positional impulse force applied to the shell upon ejection. |
| `shellphysical` | Boolean | false | Enables active rigid-body physics collisions for the shell entity. |
| `shellsticky` | Boolean | false | If `true`, the shell sticks onto environments/players upon making contact. |
| `itemid` | Integer | 0 | If >0, generates a corresponding standard in-game item using this ID. |
| `itemname` | String | "" | Name assigned to the item structure. Required if `itemid` > 0. |
| `itemworldmodel` | String | "" | Model path for the item dropped in the world. Path relative to server root. |
| `itemicon` | String | "" | 2D UI Inventory slot icon path. Path relative to client root. |
| `itemscale` | Float | 0.1 | Global scale factor for the world item model mesh. |
| `itempicksound` | Integer | 1 | [Sound](class_sound.md) profile index triggered on item collection. **Range:** `0` to `4`. |

### Sub-Array: `animations`

Defines the weapon's viewmodel animations.

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Animation ID. **Range:** `1` to `MAX_WEAPON_MODEL_ANIMATIONS-1`.   `1`: Idle, `2`: Draw/Take, `3`: Shoot, `4`: Collide, `5`: Reload, `6`: Sprint, `7`: Unequip, `8`: Walk |
| `start` | Integer | **Required** | Starting frame. |
| `end` | Integer | **Required** | Ending frame. |
| `speed` | Float | **Required** | Playback speed. Negative values play in reverse. |

# [Items](class_items.md)

## Description

Defines generic in-game items (keycards, medical items, etc.) that are not weapons.

## JSON Array: `items`

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Unique item ID. Must be >= 1. |
| `name` | String | **Required** | Display name of the item. |
| `worldmodel` | String | **Required** | Path to the 3D model shown in the world. Relative to server root. |
| `icon` | String | **Required** | Path to the 2D inventory icon. Relative to client root. |
| `scale` | Float | 0.1 | Scale of the world model. |
| `picksound` | Integer | 1 | [Sound](class_sound.md) index for picking up the item. **Range:** `0` to `4`. |
| `weapon` | Integer | 0 | If >0, links this item to a weapon ID (makes it a weapon item). |
| `color` | String | "255 255 255" | RGB color applied to the world model. Format: `"R G B"`. |

# Objects

## Description

Predefines 3D object models for map/level design use.

## JSON Array: `objects`

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Unique object ID. **Range:** `1` to `MAX_WORLD_OBJECTS-1`. |
| `filename` | String | **Required** | Path to the object model file. Cannot be empty. |

# Textures

## Description

Predefines texture files for use with objects

## JSON Array: `textures`

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Unique texture ID. **Range:** `1` to `MAX_WORLD_TEXTURES-1`. |
| `filename` | String | **Required** | Path to the texture file (e.g., `.png`, `.jpg`). Cannot be empty. |

# Fonts

## Description

Load fonts or sprite fonts

## JSON Array: `fonts`

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Unique texture ID. **Range:** `16` to `24-1`. |
| `filename` | String | **Required** | Path to the font file (e.g., `.ttf`, `.otf`). Cannot be empty. |
| `size` | Float | **Required** | Size. Cannot be 0. Max is 128 |

## JSON Array: `spritefonts`

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `name` | String | **Required** | Name to use with [Player](class_player.md) Tag functions |
| `filename` | String | **Required** | Path to the font file (e.g., `.ttf`, `.otf`). Cannot be empty. |

# Lighting

## Description

## JSON Array: `lights`

Create lights in rooms

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `roomname` | String | **Required** | [Room](class_room.md) template name (from Data\rooms.ini) |
| `x` | Float | **Required** | [Light](class_light.md) X local position from room. |
| `y` | Float | **Required** | [Light](class_light.md) Y local position from room. |
| `z` | Float | **Required** | [Light](class_light.md) Z local position from room. |
| `type` | Integer | **Required** | [Light](class_light.md) type. 1 - Directional, 2 - Point, 3 - Spot |
| `range` | Float | **Required** | [Light](class_light.md) range. |
| `scattering` | Float | 0.0 | [Light](class_light.md) scattering force (volumetric lighting). |
| `r` | Integer | 255 | Red light color intensity. |
| `g` | Integer | 255 | Green light color intensity. |
| `b` | Integer | 255 | Blue light color intensity. |
| `castshadows` | false | **Required** | Cast shadows? |
| `pitch` | Float | 0.0 | [Light](class_light.md) pitch. For dir and spot lights. |
| `yaw` | Float | 0.0 | [Light](class_light.md) yaw. For dir and spot lights. |
| `coneangle` | Float | 90.0 | Spotlight cone angle |

# Emitters & Particles

## Description

The emitter system handles particle templates used for environmental effects, weapons, and special game conditions. Templates can be dynamically overloaded or created via the addon configuration files.

## JSON Array: `emitters`

Defines or overrides particle effect templates.

| Field | Type | Default | Description |
| --- | --- | --- | --- |
| `id` | Integer | **Required** | Unique effect slot ID (from 0 to `254`). |
| `blend` | Integer | 3 | Blitz3D entity blend mode (1: Alpha, 2: Multiply, 3: Additive). |
| `fx` | Integer | 34 | Blitz3D entity FX flags (e.g., 2 + 32 = 34 for fullbright/disable fog handling). |
| `interval` | Integer | 1 | Ticks (frames) to wait between particle generation intervals. |
| `particlesperinterval` | Integer | 1 | Number of particles spawned per interval. Clamped between 1 and 100. |
| `maxparticles` | Integer | 500 | Safe limit of maximum active particles for this emitter. Clamped up to 2000. |
| `emitterlifetime` | Integer | 300 | Total life duration of the emitter in ticks. Hard-clamped between 1 and 36000. **Cannot be infinite (<= 0 is forced to 300)**. |
| `mintime` | Integer | 0 | Minimum lifetime for an individual particle in ticks. |
| `maxtime` | Integer | 300 | Maximum lifetime for an individual particle in ticks. Hard limit: 1200. |
| `texture` | String | "" | Relative path to the particle texture file. |
| `animtex` | Boolean | false | Enables frame-based texture animation for particles. |
| `maxframes` | Integer | 1 | Maximum frames in the animated texture sequence. |
| `texspeed` | Float | 1.0 | Playback speed of the texture animation. |
| `minox` / `maxox` | Float | 0.0 | Random spawn position offset range on the X-axis. |
| `minoy` / `maxoy` | Float | 0.0 | Random spawn position offset range on the Y-axis. |
| `minoz` / `maxoz` | Float | 0.0 | Random spawn position offset range on the Z-axis. |
| `minxv` / `maxxv` | Float | 0.0 | Initial particle velocity range on the X-axis. |
| `minyv` / `maxyv` | Float | 0.0 | Initial particle velocity range on the Y-axis. |
| `minzv` / `maxzv` | Float | 0.0 | Initial particle velocity range on the Z-axis. |
| `rotvel1` / `rotvel2` | Float | 0.0 | Minimum and maximum random particle sprite rotation velocity. |
| `aligntofall` | Boolean | false | Rotates the particle sprite to align with its current velocity trajectory. |
| `aligntofalloffset` | Integer | 0 | Extra angle rotation offset when `aligntofall` is active. |
| `gravity` | Float | 0.0 | Gravity force applied to the velocity on the Y-axis every frame. |
| `floory` | Float | -1000000.0 | Fixed Y coordinate plane acting as a physical floor. |
| `floorbounce` | Float | 0.5 | Velocity retention multiplier after bouncing off the floor plane. |
| `floorup` | Integer | -1 | Floor orientation type (-1: Disabled, 0: Bounce if below FloorY, 1: Bounce if above FloorY). |
| `alpha` | Float | 1.0 | Base alpha transparency of the particle sprite (0.0 to 1.0). |
| `alphavel` | Boolean | false | If true, smoothly fades particle transparency out to 0 based on its age. |
| `sx` / `sy` | Float | 1.0 | Base sprite size on X (width) and Y (height) axes. |
| `sizemultiplicator1` | Float | 1.0 | Minimum random size multiplier scaling factor at spawn. |
| `sizemultiplicator2` | Float | 1.0 | Maximum random size multiplier scaling factor at spawn. |
| `sizeadd` | Float | 0.0 | Value added to particle scale dimensions every frame. |
| `sizemult` | Float | 1.0 | Scaling multiplier applied to particle size every frame. |
| `brightness` | Integer | 1 | Overlap rendering factor (draws extra geometry layers for extra brightness intensity). |
| `color1` | Integer | 16777215 | Starting particle RGB color packed as an integer (`$FFFFFF`). |
| `color2` | Integer | 16777215 | Target particle RGB color at the end of its life cycle (`$FFFFFF`). |
| `pitchfix` | Integer | -1 | Forces a locked pitch billboard angle for the sprites. Set to -1 to disable. |
| `yawfix` | Integer | -1 | Forces a locked yaw billboard angle for the sprites. Set to -1 to disable. |

- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
