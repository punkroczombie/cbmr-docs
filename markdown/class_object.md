<!-- source: http://scpcbmr.42web.io/class_object.html -->
# SCP: Containment Breach 2 Scripting: Object Class Reference

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

[Public Member Functions](class_object.md) |
[List of all members](class_object-members.md)

Object Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| void | [SetAttach](class_object.md) ([Player](class_player.md) player) |
|  | |
| [Player](class_player.md) | [GetAttach](class_object.md) () |
|  | |
| void | [SetRoom](class_object.md) ([Room](class_room.md)) |
|  | |
| [Room](class_room.md) | [GetRoom](class_object.md) () |
|  | |
| int | [GetIndex](class_object.md) () |
|  | |
| [Entity](class_entity.md) | [GetEntity](class_object.md) () |
|  | |
| [Entity](class_entity.md) | [GetModel](class_object.md) () |
|  | |
| void | [SetMovement](class_object.md) (float speed, float maxdistance) |
|  | |
| void | [SetTexture](class_object.md) (int textureid) |
|  | |
| void | [SetTouchable](class_object.md) (bool val) |
|  | |
| void | [SetClickCallback](class_object.md) (OBJECTCALLBACK@ callback) |
|  | |
| void | [Remove](class_object.md) () |
|  | |

## Member Function Documentation

## [◆](class_object.md)SetAttach()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Object::SetAttach | ( | [Player](class_player.md) | *player* | ) |  |

Set object attach to player. The [GetEntity()](class_object.md) position must be local from [Player::GetEntity](class_player.md)

## [◆](class_object.md)GetAttach()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Player](class_player.md) Object::GetAttach | ( |  | ) |  |

Get attached to player

## [◆](class_object.md)SetRoom()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Object::SetRoom | ( | [Room](class_room.md) |  | ) |  |

Set object room

## [◆](class_object.md)GetRoom()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Room](class_room.md) Object::GetRoom | ( |  | ) |  |

Get object room

## [◆](class_object.md)GetIndex()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Object::GetIndex | ( |  | ) |  |

Get object index.

## [◆](class_object.md)GetEntity()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Object::GetEntity | ( |  | ) |  |

Get object controller entity. Use pick mode 2 on this entity to enable bullets collision.

## [◆](class_object.md)GetModel()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Object::GetModel | ( |  | ) |  |

Get object model. Touching this not recommended

## [◆](class_object.md)SetMovement()

|  |  |  |  |
| --- | --- | --- | --- |
| void Object::SetMovement | ( | float | *speed*, |
|  |  | float | *maxdistance* ) |

Set object movement settings. Speed is for moving to controller position, maxdistance is distance for teleport if distance is too far away

## [◆](class_object.md)SetTexture()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Object::SetTexture | ( | int | *textureid* | ) |  |

Set object texture from preloaded textures

## [◆](class_object.md)SetTouchable()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Object::SetTouchable | ( | bool | *val* | ) |  |

Set touchable to activate PlayerClickObject

## [◆](class_object.md)SetClickCallback()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Object::SetClickCallback | ( | OBJECTCALLBACK@ | *callback* | ) |  |

Set object click callback

## [◆](class_object.md)Remove()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Object::Remove | ( |  | ) |  |

Remove object

- [Object](class_object.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
