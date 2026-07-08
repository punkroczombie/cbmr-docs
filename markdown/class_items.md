<!-- source: http://scpcbmr.42web.io/class_items.html -->
# SCP: Containment Breach 2 Scripting: Items Class Reference

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

[Public Member Functions](class_items.md) |
[List of all members](class_items-members.md)

Items Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| bool | [IsPicked](class_items.md) () |
|  | |
| [Player](class_player.md) | [GetPicker](class_items.md) () |
|  | |
| bool | [SetPicker](class_items.md) ([Player](class_player.md) player, float throwforce=0.0) |
|  | |
| [Entity](class_entity.md) | [GetEntity](class_items.md) () |
|  | |
| int | [GetIndex](class_items.md) () |
|  | |
| string & | [GetName](class_items.md) () |
|  | |
| string & | [GetTemplateName](class_items.md) () |
|  | |
| int | [GetTemplateIndex](class_items.md) () |
|  | |
| bool | [IsWeapon](class_items.md) () |
|  | |
| void | [SetState](class_items.md) (float state) |
|  | |
| void | [SetState2](class_items.md) (float state) |
|  | |
| void | [SetState3](class_items.md) (float state) |
|  | |
| float | [GetState](class_items.md) () |
|  | |
| float | [GetState2](class_items.md) () |
|  | |
| float | [GetState3](class_items.md) () |
|  | |
| [Items](class_items.md) | [Fine](class_items.md) (int) |
|  | |
| int | [GetSlots](class_items.md) () |
|  | |
| [Items](class_items.md) | [GetParentItem](class_items.md) () |
|  | |
| [Items](class_items.md) | [GetSlotItem](class_items.md) (int) |
|  | |
| bool | [PushItem](class_items.md) ([Items](class_items.md)) |
|  | |
| bool | [RemoveSlotItem](class_items.md) (int) |
|  | |
| void | [Remove](class_items.md) () |
|  | |

## Member Function Documentation

## [◆](class_items.md)IsPicked()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Items::IsPicked | ( |  | ) |  |

Is picked

## [◆](class_items.md)GetPicker()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Player](class_player.md) Items::GetPicker | ( |  | ) |  |

Get item picker

## [◆](class_items.md)SetPicker()

|  |  |  |  |
| --- | --- | --- | --- |
| bool Items::SetPicker | ( | [Player](class_player.md) | *player*, |
|  |  | float | *throwforce* = 0.0 ) |

Set item picker. If player = NULL and item inside player's inventory, then throw force will be applied

## [◆](class_items.md)GetEntity()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Items::GetEntity | ( |  | ) |  |

Get item entity

## [◆](class_items.md)GetIndex()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Items::GetIndex | ( |  | ) |  |

Get item index

## [◆](class_items.md)GetName()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Items::GetName | ( |  | ) |  |

Get item name

## [◆](class_items.md)GetTemplateName()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Items::GetTemplateName | ( |  | ) |  |

Get item template name

## [◆](class_items.md)GetTemplateIndex()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Items::GetTemplateIndex | ( |  | ) |  |

Get item template index

## [◆](class_items.md)IsWeapon()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Items::IsWeapon | ( |  | ) |  |

Is item weapon

## [◆](class_items.md)SetState()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Items::SetState | ( | float | *state* | ) |  |

Set item state

## [◆](class_items.md)SetState2()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Items::SetState2 | ( | float | *state* | ) |  |

Set item state

## [◆](class_items.md)SetState3()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Items::SetState3 | ( | float | *state* | ) |  |

Set item state

## [◆](class_items.md)GetState()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Items::GetState | ( |  | ) |  |

Get item state

## [◆](class_items.md)GetState2()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Items::GetState2 | ( |  | ) |  |

Get item state

## [◆](class_items.md)GetState3()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Items::GetState3 | ( |  | ) |  |

Get item state

## [◆](class_items.md)Fine()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Items](class_items.md) Items::Fine | ( | int |  | ) |  |

Improves the item as if SCP-914 had been used. The item can be deleted or remain, and returns a new item, or returns NULL if the new item isn't created.

## [◆](class_items.md)GetSlots()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Items::GetSlots | ( |  | ) |  |

Get item slots if exist.

## [◆](class_items.md)GetParentItem()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Items](class_items.md) Items::GetParentItem | ( |  | ) |  |

Get parent item if item in any item slot.

## [◆](class_items.md)GetSlotItem()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Items](class_items.md) Items::GetSlotItem | ( | int |  | ) |  |

Get item from slot.

## [◆](class_items.md)PushItem()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool Items::PushItem | ( | [Items](class_items.md) |  | ) |  |

Push item to item slot. If can't, returns false

## [◆](class_items.md)RemoveSlotItem()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool Items::RemoveSlotItem | ( | int |  | ) |  |

Remove item from slot. Item drops. If can't, returns false

## [◆](class_items.md)Remove()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Items::Remove | ( |  | ) |  |

Remove item

- [Items](class_items.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
