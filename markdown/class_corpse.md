<!-- source: http://scpcbmr.42web.io/class_corpse.html -->
# SCP: Containment Breach 2 Scripting: Corpse Class Reference

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

[Public Member Functions](class_corpse.md) |
[List of all members](class_corpse-members.md)

Corpse Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| int | [GetIndex](class_corpse.md) () |
|  | |
| [Player](class_player.md) | [GetPlayer](class_corpse.md) () |
|  | |
| [Entity](class_entity.md) | [GetEntity](class_corpse.md) () |
|  | |
| float | [GetTimeout](class_corpse.md) () |
|  | |
| void | [SetTimeout](class_corpse.md) (float) |
|  | |
| bool | [PushItem](class_corpse.md) ([Items](class_items.md)) |
|  | |
| bool | [ExploreItem](class_corpse.md) (int slot) |
|  | |
| [Items](class_items.md) | [GetItem](class_corpse.md) (int slot) |
|  | |
| int | [GetModel](class_corpse.md) () |
|  | |
| int | [GetItemsCount](class_corpse.md) () |
|  | |
| bool | [IsExplored](class_corpse.md) () |
|  | |
| void | [SetExplore](class_corpse.md) (bool explore) |
|  | |
| bool | [Explore](class_corpse.md) () |
|  | |
| void | [SetData](class_corpse.md) (string &in data) |
|  | |
| string & | [GetData](class_corpse.md) () |
|  | |
| void | [Remove](class_corpse.md) () |
|  | |

## Member Function Documentation

## [◆](class_corpse.md)GetIndex()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Corpse::GetIndex | ( |  | ) |  |

Get corpse index

## [◆](class_corpse.md)GetPlayer()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Player](class_player.md) Corpse::GetPlayer | ( |  | ) |  |

Get player of corpse. Can be NULL

## [◆](class_corpse.md)GetEntity()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Corpse::GetEntity | ( |  | ) |  |

Get corpse entity

## [◆](class_corpse.md)GetTimeout()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Corpse::GetTimeout | ( |  | ) |  |

Get corpse timeout

## [◆](class_corpse.md)SetTimeout()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Corpse::SetTimeout | ( | float |  | ) |  |

Set corpse timeout

## [◆](class_corpse.md)PushItem()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool Corpse::PushItem | ( | [Items](class_items.md) |  | ) |  |

Push item to corpse.

## [◆](class_corpse.md)ExploreItem()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool Corpse::ExploreItem | ( | int | *slot* | ) |  |

Take item from corpse slot.

## [◆](class_corpse.md)GetItem()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Items](class_items.md) Corpse::GetItem | ( | int | *slot* | ) |  |

Get corpse item from slot index

## [◆](class_corpse.md)GetModel()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Corpse::GetModel | ( |  | ) |  |

Get corpse player model id

## [◆](class_corpse.md)GetItemsCount()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Corpse::GetItemsCount | ( |  | ) |  |

Get corpse items count

## [◆](class_corpse.md)IsExplored()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Corpse::IsExplored | ( |  | ) |  |

Is explored

## [◆](class_corpse.md)SetExplore()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Corpse::SetExplore | ( | bool | *explore* | ) |  |

Set explored state

## [◆](class_corpse.md)Explore()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Corpse::Explore | ( |  | ) |  |

Takes all items from corpse, like usual exploring.

## [◆](class_corpse.md)SetData()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Corpse::SetData | ( | string &in | *data* | ) |  |

Set data for scripting messaging

## [◆](class_corpse.md)GetData()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Corpse::GetData | ( |  | ) |  |

Get data

## [◆](class_corpse.md)Remove()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Corpse::Remove | ( |  | ) |  |

Remove corpse

- [Corpse](class_corpse.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
