<!-- source: http://scpcbmr.42web.io/class_light.html -->
# SCP: Containment Breach 2 Scripting: Light Class Reference

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

[Public Member Functions](class_light.md) |
[List of all members](class_light-members.md)

Light Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| int | [GetIndex](class_light.md) () |
|  | |
| void | [SetFOV](class_light.md) (float fov) |
|  | |
| void | [SetRange](class_light.md) (float range) |
|  | |
| void | [SetScattering](class_light.md) (float scattering) |
|  | |
| void | [SetColor](class_light.md) (int r, int g, int b) |
|  | |
| void | [SetCastShadows](class_light.md) (bool shadows) |
|  | |
| void | [SetIntensity](class_light.md) (float intensity) |
|  | |
| void | [SetLength](class_light.md) (float length) |
|  | |
| float | [GetFOV](class_light.md) () |
|  | |
| float | [GetRange](class_light.md) () |
|  | |
| float | [GetScattering](class_light.md) () |
|  | |
| void | [GetColor](class_light.md) (int &out r, int &out g, int &out b) |
|  | |
| bool | [GetCastShadows](class_light.md) () |
|  | |
| float | [GetIntensity](class_light.md) () |
|  | |
| float | [GetLength](class_light.md) () |
|  | |
| void | [SetAttach](class_light.md) ([Player](class_player.md) player) |
|  | |
| [Player](class_player.md) | [GetAttach](class_light.md) () |
|  | |
| void | [SetRoom](class_light.md) ([Room](class_room.md)) |
|  | |
| [Room](class_room.md) | [GetRoom](class_light.md) () |
|  | |
| [Entity](class_entity.md) | [GetEntity](class_light.md) () |
|  | |
| [Entity](class_entity.md) | [GetLight](class_light.md) () |
|  | |
| void | [SetMovement](class_light.md) (float speed, float maxdistance) |
|  | |
| void | [Remove](class_light.md) () |
|  | |

## Member Function Documentation

## [◆](class_light.md)GetIndex()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Light::GetIndex | ( |  | ) |  |

Get light index.

## [◆](class_light.md)SetFOV()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Light::SetFOV | ( | float | *fov* | ) |  |

Set light FOV. Only for spotlight. Range is 0.0 - 179.0

## [◆](class_light.md)SetRange()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Light::SetRange | ( | float | *range* | ) |  |

Set light range.

## [◆](class_light.md)SetScattering()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Light::SetScattering | ( | float | *scattering* | ) |  |

Set light scattering force.

## [◆](class_light.md)SetColor()

|  |  |  |  |
| --- | --- | --- | --- |
| void Light::SetColor | ( | int | *r*, |
|  |  | int | *g*, |
|  |  | int | *b* ) |

Set light color.

## [◆](class_light.md)SetCastShadows()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Light::SetCastShadows | ( | bool | *shadows* | ) |  |

Set light cast shadows.

## [◆](class_light.md)SetIntensity()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Light::SetIntensity | ( | float | *intensity* | ) |  |

Set light intensity. It affects on light's range.

## [◆](class_light.md)SetLength()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Light::SetLength | ( | float | *length* | ) |  |

Set light length. Area light.

## [◆](class_light.md)GetFOV()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Light::GetFOV | ( |  | ) |  |

Get light FOV. Only for spotlight. Range is 0.0 - 179.0

## [◆](class_light.md)GetRange()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Light::GetRange | ( |  | ) |  |

Get light range.

## [◆](class_light.md)GetScattering()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Light::GetScattering | ( |  | ) |  |

Get light scattering force.

## [◆](class_light.md)GetColor()

|  |  |  |  |
| --- | --- | --- | --- |
| void Light::GetColor | ( | int &out | *r*, |
|  |  | int &out | *g*, |
|  |  | int &out | *b* ) |

Get light color.

## [◆](class_light.md)GetCastShadows()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Light::GetCastShadows | ( |  | ) |  |

Get light cast shadows.

## [◆](class_light.md)GetIntensity()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Light::GetIntensity | ( |  | ) |  |

Get light intensity. It affects on light's range.

## [◆](class_light.md)GetLength()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Light::GetLength | ( |  | ) |  |

Get light length. Area light.

## [◆](class_light.md)SetAttach()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Light::SetAttach | ( | [Player](class_player.md) | *player* | ) |  |

Attach light to player. The [GetEntity()](class_light.md) position must be local from [Player::GetEntity](class_player.md)

## [◆](class_light.md)GetAttach()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Player](class_player.md) Light::GetAttach | ( |  | ) |  |

Get attach to player

## [◆](class_light.md)SetRoom()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Light::SetRoom | ( | [Room](class_room.md) |  | ) |  |

Set light room

## [◆](class_light.md)GetRoom()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Room](class_room.md) Light::GetRoom | ( |  | ) |  |

Get light room

## [◆](class_light.md)GetEntity()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Light::GetEntity | ( |  | ) |  |

Get light controller entity.

## [◆](class_light.md)GetLight()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Light::GetLight | ( |  | ) |  |

Get light entity. Touching this not recommended

## [◆](class_light.md)SetMovement()

|  |  |  |  |
| --- | --- | --- | --- |
| void Light::SetMovement | ( | float | *speed*, |
|  |  | float | *maxdistance* ) |

Set light movement settings. Speed is for moving to controller position, maxdistance is distance for teleport if distance is too far away

## [◆](class_light.md)Remove()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Light::Remove | ( |  | ) |  |

Remove light

- [Light](class_light.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
