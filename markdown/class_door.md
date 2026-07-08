<!-- source: http://scpcbmr.42web.io/class_door.html -->
# SCP: Containment Breach 2 Scripting: Door Class Reference

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

[Public Member Functions](class_door.md) |
[List of all members](class_door-members.md)

Door Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| void | [Use](class_door.md) () |
|  | |
| void | [SetOpen](class_door.md) (bool) |
|  | |
| bool | [IsOpened](class_door.md) () |
|  | |
| bool | [IsBreak](class_door.md) () |
|  | |
| void | [SetLockState](class_door.md) (int) |
|  | |
| int | [GetLockState](class_door.md) () |
|  | |
| float | [GetOpenState](class_door.md) () |
|  | |
| bool | [BreakDoor](class_door.md) (float x, float y, float z) |
|  | |
| void | [Decompose](class_door.md) () |
|  | |
| int | [GetDoorAccess](class_door.md) () |
|  | |
| int | [GetDoorType](class_door.md) () |
|  | |
| void | [SetKeycard](class_door.md) (int) |
|  | |
| int | [GetKeycard](class_door.md) () |
|  | |
| [Entity](class_entity.md) | [GetEntity](class_door.md) () |
|  | |
| [Entity](class_entity.md) | [GetButton](class_door.md) (int index) |
|  | |
| int | [GetIndex](class_door.md) () |
|  | |

## Member Function Documentation

## [◆](class_door.md)Use()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Door::Use | ( |  | ) |  |

Use door with sound

## [◆](class_door.md)SetOpen()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Door::SetOpen | ( | bool |  | ) |  |

Set open state

## [◆](class_door.md)IsOpened()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Door::IsOpened | ( |  | ) |  |

Is opened

## [◆](class_door.md)IsBreak()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Door::IsBreak | ( |  | ) |  |

Is break

## [◆](class_door.md)SetLockState()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Door::SetLockState | ( | int |  | ) |  |

Set door lock state. 2 - for wooden, office, fence doors

## [◆](class_door.md)GetLockState()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Door::GetLockState | ( |  | ) |  |

Get door lock state.

## [◆](class_door.md)GetOpenState()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Door::GetOpenState | ( |  | ) |  |

Get open state

## [◆](class_door.md)BreakDoor()

|  |  |  |  |
| --- | --- | --- | --- |
| bool Door::BreakDoor | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Break door like SCP-096. The position will calculate the direction of the door's fall.

## [◆](class_door.md)Decompose()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Door::Decompose | ( |  | ) |  |

Decompose door like from SCP-106

## [◆](class_door.md)GetDoorAccess()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Door::GetDoorAccess | ( |  | ) |  |

Get door access type

## [◆](class_door.md)GetDoorType()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Door::GetDoorType | ( |  | ) |  |

Get door type

## [◆](class_door.md)SetKeycard()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Door::SetKeycard | ( | int |  | ) |  |

Set keycard type

## [◆](class_door.md)GetKeycard()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Door::GetKeycard | ( |  | ) |  |

Get keycard type

## [◆](class_door.md)GetEntity()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Door::GetEntity | ( |  | ) |  |

Get door frame entity

## [◆](class_door.md)GetButton()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Door::GetButton | ( | int | *index* | ) |  |

Get door button entity. Can be NULL (0-1)

## [◆](class_door.md)GetIndex()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Door::GetIndex | ( |  | ) |  |

Get door index

- [Door](class_door.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
