<!-- source: http://scpcbmr.42web.io/class_n_p_c.html -->
# SCP: Containment Breach 2 Scripting: NPC Class Reference

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

[Public Member Functions](class_n_p_c.md) |
[List of all members](class_n_p_c-members.md)

NPC Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| [Entity](class_entity.md) | [GetEntity](class_n_p_c.md) () |
|  | |
| [Entity](class_entity.md) | [GetModel](class_n_p_c.md) () |
|  | |
| void | [SetPickable](class_n_p_c.md) (bool pickable) |
|  | |
| void | [SetDead](class_n_p_c.md) (bool state) |
|  | |
| bool | [IsDead](class_n_p_c.md) () |
|  | |
| void | [SetHealth](class_n_p_c.md) (int health) |
|  | |
| int | [GetHealth](class_n_p_c.md) () |
|  | |
| void | [SetIdle](class_n_p_c.md) (float state) |
|  | |
| void | [SetState1](class_n_p_c.md) (float state) |
|  | |
| void | [SetState2](class_n_p_c.md) (float state) |
|  | |
| void | [SetState3](class_n_p_c.md) (float state) |
|  | |
| float | [GetIdle](class_n_p_c.md) () |
|  | |
| float | [GetState1](class_n_p_c.md) () |
|  | |
| float | [GetState2](class_n_p_c.md) () |
|  | |
| float | [GetState3](class_n_p_c.md) () |
|  | |
| void | [Remove](class_n_p_c.md) () |
|  | |

## Member Function Documentation

## [◆](class_n_p_c.md)GetEntity()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) NPC::GetEntity | ( |  | ) |  |

Get entity

## [◆](class_n_p_c.md)GetModel()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) NPC::GetModel | ( |  | ) |  |

Get model

## [◆](class_n_p_c.md)SetPickable()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void NPC::SetPickable | ( | bool | *pickable* | ) |  |

Sets that the [NPC](class_n_p_c.md) can be shot at. Calls PlayerShootNPC\_c on shoot

## [◆](class_n_p_c.md)SetDead()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void NPC::SetDead | ( | bool | *state* | ) |  |

Set [NPC](class_n_p_c.md) dead state

## [◆](class_n_p_c.md)IsDead()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool NPC::IsDead | ( |  | ) |  |

Is [NPC](class_n_p_c.md) dead

## [◆](class_n_p_c.md)SetHealth()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void NPC::SetHealth | ( | int | *health* | ) |  |

Get [NPC](class_n_p_c.md) HP

## [◆](class_n_p_c.md)GetHealth()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int NPC::GetHealth | ( |  | ) |  |

Get [NPC](class_n_p_c.md) HP

## [◆](class_n_p_c.md)SetIdle()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void NPC::SetIdle | ( | float | *state* | ) |  |

Set idle state. Some values can disable NPCs.

## [◆](class_n_p_c.md)SetState1()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void NPC::SetState1 | ( | float | *state* | ) |  |

Set [NPC](class_n_p_c.md) state

## [◆](class_n_p_c.md)SetState2()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void NPC::SetState2 | ( | float | *state* | ) |  |

Set [NPC](class_n_p_c.md) state

## [◆](class_n_p_c.md)SetState3()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void NPC::SetState3 | ( | float | *state* | ) |  |

Set [NPC](class_n_p_c.md) state

## [◆](class_n_p_c.md)GetIdle()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float NPC::GetIdle | ( |  | ) |  |

Get idle state.

## [◆](class_n_p_c.md)GetState1()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float NPC::GetState1 | ( |  | ) |  |

Get [NPC](class_n_p_c.md) state

## [◆](class_n_p_c.md)GetState2()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float NPC::GetState2 | ( |  | ) |  |

Get [NPC](class_n_p_c.md) state

## [◆](class_n_p_c.md)GetState3()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float NPC::GetState3 | ( |  | ) |  |

Get [NPC](class_n_p_c.md) state

## [◆](class_n_p_c.md)Remove()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void NPC::Remove | ( |  | ) |  |

Remove

- [NPC](class_n_p_c.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
