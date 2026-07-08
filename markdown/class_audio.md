<!-- source: http://scpcbmr.42web.io/class_audio.html -->
# SCP: Containment Breach 2 Scripting: Audio Class Reference

|  |  |  |
| --- | --- | --- |
| Logo | SCP: Containment Breach 2 Scripting |  |

![](sync_on.png "click to disable panel synchronization")

- [▼](javascript:void(0))[SCP: Containment Breach 2 Scripting](index.md)

  - [►](javascript:void(0))[AngelScript](index.md)
  - [►](javascript:void(0))[Topics](topics.md)
  - [▼](javascript:void(0))[Classes](annotated.md)

    - [▼](javascript:void(0))[Class List](annotated.md)

      - [►](javascript:void(0))[Сhat](class_xD0_xA1hat.md)
      - [►](javascript:void(0))[Audio](class_audio.md)
      - [►](javascript:void(0))[Config](class_config.md)
      - [►](javascript:void(0))[Connection](class_connection.md)
      - [►](javascript:void(0))[Corpse](class_corpse.md)
      - [►](javascript:void(0))[Door](class_door.md)
      - [►](javascript:void(0))[Entity](class_entity.md)
      - [►](javascript:void(0))[Event](class_event.md)
      - [►](javascript:void(0))[Graphics](class_graphics.md)
      - [►](javascript:void(0))[GUIElement](class_g_u_i_element.md)
      - [►](javascript:void(0))[Items](class_items.md)
      - [►](javascript:void(0))[Light](class_light.md)
      - [ModelPreset](class_model_preset.md)
      - [►](javascript:void(0))[NPC](class_n_p_c.md)
      - [►](javascript:void(0))[Object](class_object.md)
      - [►](javascript:void(0))[Player](class_player.md)
      - [►](javascript:void(0))[Room](class_room.md)
      - [►](javascript:void(0))[Server](class_server.md)
      - [►](javascript:void(0))[Shell](class_shell.md)
      - [►](javascript:void(0))[Sound](class_sound.md)
      - [►](javascript:void(0))[World](class_world.md)
    - [Class Index](classes.md)
    - [►](javascript:void(0))[Class Members](functions.md)

[•All](javascript:void(0))[Classes](javascript:void(0))[Functions](javascript:void(0))[Variables](javascript:void(0))[Modules](javascript:void(0))[Pages](javascript:void(0))

Loading...

Searching...

No Matches

[Public Member Functions](class_audio.md) |
[List of all members](class_audio-members.md)

Audio Class Reference

`#include <all.h>`

|  |  |
| --- | --- |
| Public Member Functions | |
| [Sound](class_sound.md) | [Play3DSound](class_audio.md) (string &in filenameorurl, [Player](class_player.md) player, float range, float volume, bool norange=false) |
|  | |
| [Sound](class_sound.md) | [Play3DSound](class_audio.md) (string &in filenameorurl, [Entity](class_entity.md) entity, float range, float volume, bool norange=false) |
|  | |
| [Sound](class_sound.md) | [Play3DSound](class_audio.md) (string &in filenameorurl, float x, float y, float z, float range, float volume, bool norange=false) |
|  | |
| [Sound](class_sound.md) | [PlaySound](class_audio.md) (string &in filenameorurl) |
|  | |
| [Sound](class_sound.md) | [PlaySoundForPlayer](class_audio.md) ([Player](class_player.md) player, string &in filenameorurl) |
|  | |
| [Sound](class_sound.md) | [Play3DSoundForPlayer](class_audio.md) ([Player](class_player.md) player, string &in filenameorurl, [Entity](class_entity.md) entity, float range, float volume, bool norange=false) |
|  | |
| [Sound](class_sound.md) | [Play3DSoundForPlayer](class_audio.md) ([Player](class_player.md) player, string &in filenameorurl, float x, float y, float z, float range, float volume, bool norange=false) |
|  | |
| [Sound](class_sound.md) | [Play3DSoundForPlayer](class_audio.md) ([Player](class_player.md) player, string &in filenameorurl, [Player](class_player.md) player, float range, float volume, bool norange=false) |
|  | |

## Detailed Description

Global property is 'audio'

## Member Function Documentation

## [◆](class_audio.md)Play3DSound() [1/3]

|  |  |  |  |
| --- | --- | --- | --- |
| [Sound](class_sound.md) Audio::Play3DSound | ( | string &in | *filenameorurl*, |
|  |  | [Player](class_player.md) | *player*, |
|  |  | float | *range*, |
|  |  | float | *volume*, |
|  |  | bool | *norange* = false ) |

Emit and attach sound to player. If norange = true, then the sound is sent to all players regardless of the distance.

## [◆](class_audio.md)Play3DSound() [2/3]

|  |  |  |  |
| --- | --- | --- | --- |
| [Sound](class_sound.md) Audio::Play3DSound | ( | string &in | *filenameorurl*, |
|  |  | [Entity](class_entity.md) | *entity*, |
|  |  | float | *range*, |
|  |  | float | *volume*, |
|  |  | bool | *norange* = false ) |

Emit sound at entity, instead of position. If norange = true, then the sound is sent to all players regardless of the distance.

## [◆](class_audio.md)Play3DSound() [3/3]

|  |  |  |  |
| --- | --- | --- | --- |
| [Sound](class_sound.md) Audio::Play3DSound | ( | string &in | *filenameorurl*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | float | *range*, |
|  |  | float | *volume*, |
|  |  | bool | *norange* = false ) |

Emit sound at position. If norange = true, then the sound is sent to all players regardless of the distance.

## [◆](class_audio.md)PlaySound()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Sound](class_sound.md) Audio::PlaySound | ( | string &in | *filenameorurl* | ) |  |

Play global sound for all players

## [◆](class_audio.md)PlaySoundForPlayer()

|  |  |  |  |
| --- | --- | --- | --- |
| [Sound](class_sound.md) Audio::PlaySoundForPlayer | ( | [Player](class_player.md) | *player*, |
|  |  | string &in | *filenameorurl* ) |

Play global sound for one player

## [◆](class_audio.md)Play3DSoundForPlayer() [1/3]

|  |  |  |  |
| --- | --- | --- | --- |
| [Sound](class_sound.md) Audio::Play3DSoundForPlayer | ( | [Player](class_player.md) | *player*, |
|  |  | string &in | *filenameorurl*, |
|  |  | [Entity](class_entity.md) | *entity*, |
|  |  | float | *range*, |
|  |  | float | *volume*, |
|  |  | bool | *norange* = false ) |

Emit sound at entity for one player. If norange = true, then the sound is sent to player regardless of the distance.

## [◆](class_audio.md)Play3DSoundForPlayer() [2/3]

|  |  |  |  |
| --- | --- | --- | --- |
| [Sound](class_sound.md) Audio::Play3DSoundForPlayer | ( | [Player](class_player.md) | *player*, |
|  |  | string &in | *filenameorurl*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | float | *range*, |
|  |  | float | *volume*, |
|  |  | bool | *norange* = false ) |

Emit sound at position for one player. If norange = true, then the sound is sent to player regardless of the distance.

## [◆](class_audio.md)Play3DSoundForPlayer() [3/3]

|  |  |  |  |
| --- | --- | --- | --- |
| [Sound](class_sound.md) Audio::Play3DSoundForPlayer | ( | [Player](class_player.md) | *player*, |
|  |  | string &in | *filenameorurl*, |
|  |  | [Player](class_player.md) | *player*, |
|  |  | float | *range*, |
|  |  | float | *volume*, |
|  |  | bool | *norange* = false ) |

Emit and attach sound to player for one player. If norange = true, then the sound is sent to player regardless of the distance.

- [Audio](class_audio.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
