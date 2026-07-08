<!-- source: http://scpcbmr.42web.io/class_world.html -->
# SCP: Containment Breach 2 Scripting: World Class Reference

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

[Public Member Functions](class_world.md) |
[List of all members](class_world-members.md)

World Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| void | [CreateDecal](class_world.md) (int decalid, float x, float y, float z, float pitch, float yaw, float roll, [Room](class_room.md) room=NULL, float lifetime=1.0f, float alpha=1.0f, float size=1.0f, float sizechange=0.0f, float maxsize=1.0f, float alphachange=0.0f, int r=0, int g=0, int b=0, float timer=0.0) |
|  | |
| void | [CreateEmitter](class_world.md) ([Player](class_player.md) target, int id, float x, float y, float z) |
|  | |
| void | [CreateEmitter](class_world.md) ([Player](class_player.md) target, int id, float x, float y, float z, [Player](class_player.md) attachPlayer) |
|  | |
| void | [CreateEmitter](class_world.md) ([Player](class_player.md) target, int id, float x, float y, float z, [Object](class_object.md) attachObject) |
|  | |
| int | [GetZone](class_world.md) (float x, float y, float z) |
|  | |
| [Player](class_player.md) | [CreateBot](class_world.md) (string &in) |
|  | |
| void | [RaycastItems](class_world.md) () |
|  | |
| [Items](class_items.md) | [GetItem](class_world.md) (int index) |
|  | |
| [Items](class_items.md) | [CreateItem](class_world.md) (string &in templatename, bool collision=true, float x=0, float y=0, float z=0, int r=0, int g=0, int b=0, float alpha=1.0, int invslots=0) |
|  | |
| [Items](class_items.md) | [CreateItem](class_world.md) (int templateindex, bool collision=true, float x=0, float y=0, float z=0, int r=0, int g=0, int b=0, float alpha=1.0, int invslots=0) |
|  | |
| [Room](class_room.md) | [GetRoomByName](class_world.md) (string &in) |
|  | |
| [Room](class_room.md) | [GetRoomByIndex](class_world.md) (int) |
|  | |
| [Room](class_room.md) | [GetRoomByIdentifier](class_world.md) (int) |
|  | |
| [Corpse](class_corpse.md) | [GetCorpse](class_world.md) (int index) |
|  | |
| [Door](class_door.md) | [GetDoor](class_world.md) (int) |
|  | |
| [Event](class_event.md) | [GetEvent](class_world.md) (int index) |
|  | |
| [Event](class_event.md) | [GetEventByIdentifier](class_world.md) (int index) |
|  | |
| [Object](class_object.md) | [CreateObject](class_world.md) (int objectid, [Room](class_room.md) room=NULL, bool animated=false) |
|  | |
| [Object](class_object.md) | [GetObject](class_world.md) (int index) |
|  | |
| [Light](class_light.md) | [CreateLight](class_world.md) (int type, float range=10.0, [Room](class_room.md) room=NULL) |
|  | |
| [NPC](class_n_p_c.md) | [CreateNPC](class_world.md) (int npctype, float x, float y, float z) |
|  | |
| [NPC](class_n_p_c.md) | [GetNPC](class_world.md) (int index) |
|  | |
| [ModelPreset](class_model_preset.md) | **GetModelPreset** (int modelid) |
|  | |
| [Shell](class_shell.md) | [CreateShell](class_world.md) (int weaponid, [Player](class_player.md) shooter=NULL) |
|  | |

## Member Function Documentation

## [◆](class_world.md)CreateDecal()

|  |  |  |  |
| --- | --- | --- | --- |
| void World::CreateDecal | ( | int | *decalid*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | float | *pitch*, |
|  |  | float | *yaw*, |
|  |  | float | *roll*, |
|  |  | [Room](class_room.md) | *room* = NULL, |
|  |  | float | *lifetime* = 1.0f, |
|  |  | float | *alpha* = 1.0f, |
|  |  | float | *size* = 1.0f, |
|  |  | float | *sizechange* = 0.0f, |
|  |  | float | *maxsize* = 1.0f, |
|  |  | float | *alphachange* = 0.0f, |
|  |  | int | *r* = 0, |
|  |  | int | *g* = 0, |
|  |  | int | *b* = 0, |
|  |  | float | *timer* = 0.0 ) |

Creates decal.

## [◆](class_world.md)CreateEmitter() [1/3]

|  |  |  |  |
| --- | --- | --- | --- |
| void World::CreateEmitter | ( | [Player](class_player.md) | *target*, |
|  |  | int | *id*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Create emitter on position. If target = NULL, then emitter will be created for every player.

## [◆](class_world.md)CreateEmitter() [2/3]

|  |  |  |  |
| --- | --- | --- | --- |
| void World::CreateEmitter | ( | [Player](class_player.md) | *target*, |
|  |  | int | *id*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | [Player](class_player.md) | *attachPlayer* ) |

Create emitter and attach to player. X Y Z is local offset position from player. If target = NULL, then emitter will be created for every player.

## [◆](class_world.md)CreateEmitter() [3/3]

|  |  |  |  |
| --- | --- | --- | --- |
| void World::CreateEmitter | ( | [Player](class_player.md) | *target*, |
|  |  | int | *id*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | [Object](class_object.md) | *attachObject* ) |

Create emitter and attach to object. X Y Z is local offset position from object. If target = NULL, then emitter will be created for every player.

## [◆](class_world.md)GetZone()

|  |  |  |  |
| --- | --- | --- | --- |
| int World::GetZone | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Get zone by X, Y, Z. 0 - LCZ, 1 - HCZ, 2 - EZ

## [◆](class_world.md)CreateBot()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Player](class_player.md) World::CreateBot | ( | string & | *in* | ) |  |

Creates bot with specified name. Calls PlayerConnect callback. Can return null

## [◆](class_world.md)RaycastItems()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void World::RaycastItems | ( |  | ) |  |

After creating a large number of items, it is recommended to use this function, as it is possible that the items will sink under the floor.

## [◆](class_world.md)GetItem()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Items](class_items.md) World::GetItem | ( | int | *index* | ) |  |

Get item by index. DEPRECATED! Don't use it! It will be deleted in the near future. Use instead: for(auto it = Items::Iterator(); it != NULL; it++){[Items](class_items.md) item = it.Get();} or custom array with OnCreateItem hook.

## [◆](class_world.md)CreateItem() [1/2]

|  |  |  |  |
| --- | --- | --- | --- |
| [Items](class_items.md) World::CreateItem | ( | string &in | *templatename*, |
|  |  | bool | *collision* = true, |
|  |  | float | *x* = 0, |
|  |  | float | *y* = 0, |
|  |  | float | *z* = 0, |
|  |  | int | *r* = 0, |
|  |  | int | *g* = 0, |
|  |  | int | *b* = 0, |
|  |  | float | *alpha* = 1.0, |
|  |  | int | *invslots* = 0 ) |

Creates an item by template name. There is a possibility of not creating due to reaching the limit.

## [◆](class_world.md)CreateItem() [2/2]

|  |  |  |  |
| --- | --- | --- | --- |
| [Items](class_items.md) World::CreateItem | ( | int | *templateindex*, |
|  |  | bool | *collision* = true, |
|  |  | float | *x* = 0, |
|  |  | float | *y* = 0, |
|  |  | float | *z* = 0, |
|  |  | int | *r* = 0, |
|  |  | int | *g* = 0, |
|  |  | int | *b* = 0, |
|  |  | float | *alpha* = 1.0, |
|  |  | int | *invslots* = 0 ) |

Creates an item by template index. There is a possibility of not creating due to reaching the limit.

## [◆](class_world.md)GetRoomByName()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Room](class_room.md) World::GetRoomByName | ( | string & | *in* | ) |  |

Get room by name

## [◆](class_world.md)GetRoomByIndex()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Room](class_room.md) World::GetRoomByIndex | ( | int |  | ) |  |

Get room by index (MAX\_ROOMS)

## [◆](class_world.md)GetRoomByIdentifier()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Room](class_room.md) World::GetRoomByIdentifier | ( | int |  | ) |  |

Get room by identifier

## [◆](class_world.md)GetCorpse()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Corpse](class_corpse.md) World::GetCorpse | ( | int | *index* | ) |  |

Get corpse by index. DEPRECATED! Don't use it! It will be deleted in the near future. Use instead: for(auto it = Corpse::Iterator(); it != NULL; it++){[Corpse](class_corpse.md) c = it.Get();} or custom array with OnCreateCorpse hook.

## [◆](class_world.md)GetDoor()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Door](class_door.md) World::GetDoor | ( | int |  | ) |  |

Get door by index. (MAX\_DOORS)

## [◆](class_world.md)GetEvent()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Event](class_event.md) World::GetEvent | ( | int | *index* | ) |  |

Get event by index (MAX\_EVENTS)

## [◆](class_world.md)GetEventByIdentifier()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Event](class_event.md) World::GetEventByIdentifier | ( | int | *index* | ) |  |

Get event by identifier.

## [◆](class_world.md)CreateObject()

|  |  |  |  |
| --- | --- | --- | --- |
| [Object](class_object.md) World::CreateObject | ( | int | *objectid*, |
|  |  | [Room](class_room.md) | *room* = NULL, |
|  |  | bool | *animated* = false ) |

Creates object. If no room is specified, the object will be synchronized by distance, not by room. Use animated if you want to use [Entity::SetAnimTime](class_entity.md)

## [◆](class_world.md)GetObject()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Object](class_object.md) World::GetObject | ( | int | *index* | ) |  |

Get object by index. DEPRECATED! Don't use it! Use instead: for(auto it = Object::Iterator(); it != NULL; it++){[Object](class_object.md) obj = it.Get();} or custom array with OnCreateObject hook.

## [◆](class_world.md)CreateLight()

|  |  |  |  |
| --- | --- | --- | --- |
| [Light](class_light.md) World::CreateLight | ( | int | *type*, |
|  |  | float | *range* = 10.0, |
|  |  | [Room](class_room.md) | *room* = NULL ) |

Creates light. If no room is specified, the light will be synchronized by distance, not by room. 1 - directional, 2 - point, 3 - spot

## [◆](class_world.md)CreateNPC()

|  |  |  |  |
| --- | --- | --- | --- |
| [NPC](class_n_p_c.md) World::CreateNPC | ( | int | *npctype*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Creates a [NPC](class_n_p_c.md). Doesn't work with 'disablenpcs' setting

## [◆](class_world.md)GetNPC()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [NPC](class_n_p_c.md) World::GetNPC | ( | int | *index* | ) |  |

Get [NPC](class_n_p_c.md) by index. (MAX\_NPCS)

## [◆](class_world.md)CreateShell()

|  |  |  |  |
| --- | --- | --- | --- |
| [Shell](class_shell.md) World::CreateShell | ( | int | *weaponid*, |
|  |  | [Player](class_player.md) | *shooter* = NULL ) |

Creates shell. If shooter isn't null, then shell will be created from player's head.

- [World](class_world.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
