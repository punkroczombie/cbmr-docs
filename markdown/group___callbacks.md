<!-- source: http://scpcbmr.42web.io/group___callbacks.html -->
# SCP: Containment Breach 2 Scripting: Callbacks

|  |  |  |
| --- | --- | --- |
| Logo | SCP: Containment Breach 2 Scripting |  |

![](sync_on.png "click to disable panel synchronization")

- [▼](javascript:void(0))[SCP: Containment Breach 2 Scripting](index.md)

  - [►](javascript:void(0))[AngelScript](index.md)
  - [▼](javascript:void(0))[Topics](topics.md)

    - [►](javascript:void(0))[Callbacks](group___callbacks.md)
    - [►](javascript:void(0))[Globals](group___globals.md)
    - [Objects](group___objects.md)
  - [►](javascript:void(0))[Classes](annotated.md)

[•All](javascript:void(0))[Classes](javascript:void(0))[Functions](javascript:void(0))[Variables](javascript:void(0))[Modules](javascript:void(0))[Pages](javascript:void(0))

Loading...

Searching...

No Matches

[Functions](group___callbacks.md)

Callbacks

|  |  |
| --- | --- |
| Functions | |
| void | [OnInitialize](group___callbacks.md) () |
|  | |
| void | [OnTerminate](group___callbacks.md) () |
|  | |
| void | [ServerUpdate](group___callbacks.md) () |
|  | |
| bool | [ServerConsole](group___callbacks.md) (string command) |
|  | |
| void | [ServerRestart](group___callbacks.md) () |
|  | |
| void | [WorldLoaded](group___callbacks.md) () |
|  | |
| void | [WorldUpdate](group___callbacks.md) () |
|  | |
| void | [PlayerUpdate](group___callbacks.md) ([Player](class_player.md) player) |
|  | |
| void | [PlayerConnect](group___callbacks.md) ([Player](class_player.md) player) |
|  | |
| void | [PlayerDisconnect](group___callbacks.md) ([Player](class_player.md) player) |
|  | |
| bool | [PlayerChat](group___callbacks.md) ([Player](class_player.md) player, string text) |
|  | |
| void | [PlayerAttachesUpdate](group___callbacks.md) ([Player](class_player.md) player) |
|  | |
| bool | [PlayerTakeItem](group___callbacks.md) ([Player](class_player.md) player, [Items](class_items.md) item) |
|  | |
| bool | [PlayerDropItem](group___callbacks.md) ([Player](class_player.md) player, [Items](class_items.md) item) |
|  | |
| void | [PlayerDialogAction](group___callbacks.md) ([Player](class_player.md) player, int index, bool response, string input, int selecteditem) |
|  | |
| bool | [PlayerShootPlayer](group___callbacks.md) ([Player](class_player.md) shooter, [Player](class_player.md) dest, float x, float y, float z, float damage, bool headshot) |
|  | |
| bool | [PlayerShoot](group___callbacks.md) ([Player](class_player.md) player, [Items](class_items.md) item, int weaponattach) |
|  | |
| void | [PlayerPressPlayer](group___callbacks.md) ([Player](class_player.md) src, [Player](class_player.md) dest) |
|  | |
| bool | [PlayerConsole](group___callbacks.md) ([Player](class_player.md) player, string input) |
|  | |
| void | [PlayerDeath](group___callbacks.md) ([Player](class_player.md) player, [Corpse](class_corpse.md) corpse) |
|  | |
| void | [PlayerRespawn](group___callbacks.md) ([Player](class_player.md) player) |
|  | |
| void | [PlayerHitPlayer](group___callbacks.md) ([Player](class_player.md) src, [Player](class_player.md) dest, int mousedata, float distance) |
|  | |
| bool | [PlayerExploreCorpse](group___callbacks.md) ([Player](class_player.md) player, [Corpse](class_corpse.md) corpse) |
|  | |
| void | [PlayerClickObject](group___callbacks.md) ([Player](class_player.md) player, [Object](class_object.md) object) |
|  | |
| void | [PlayerShootObject](group___callbacks.md) ([Player](class_player.md) player, [Object](class_object.md) object) |
|  | |
| bool | [PlayerUseDoorButton](group___callbacks.md) ([Player](class_player.md) player, [Door](class_door.md) door, [Items](class_items.md) useditem) |
|  | |
| bool | [PlayerUseItem](group___callbacks.md) ([Player](class_player.md) player, [Items](class_items.md) item) |
|  | |
| bool | [PlayerSelectItem](group___callbacks.md) ([Player](class_player.md) player, [Items](class_items.md) item) |
|  | |
| void | [PlayerUse914](group___callbacks.md) ([Player](class_player.md) player, int fineid) |
|  | |
| void | [PlayerSelectGUI](group___callbacks.md) ([Player](class_player.md) player, [GUIElement](class_g_u_i_element.md) element) |
|  | |
| bool | [PlayerVoice](group___callbacks.md) ([Player](class_player.md) player, int bank, bool radio) |
|  | |
| void | [PlayerTeleportElevator](group___callbacks.md) ([Player](class_player.md) player, [Room](class_room.md) room, [Entity](class_entity.md) firstentity, [Entity](class_entity.md) secondentity, float offsetx, float offsety) |
|  | |
| void | [PlayerShootNPC](group___callbacks.md) ([Player](class_player.md) player, [NPC](class_n_p_c.md) npc) |
|  | |
| void | [PlayerKeyAction](group___callbacks.md) ([Player](class_player.md) player, int newmask, int prevmask) |
|  | |
| bool | [PlayerSpectateAction](group___callbacks.md) ([Player](class_player.md) player, [Player](class_player.md) target, int mode) |
|  | |
| void | [IncomingConnection](group___callbacks.md) ([Connection](class_connection.md) conn) |
|  | |
| bool | [ConnectionLoaded](group___callbacks.md) ([Connection](class_connection.md) conn) |
|  | |
| void | [ConnectionClosed](group___callbacks.md) ([Connection](class_connection.md) conn) |
|  | |
| bool | [ShellDamagePlayer](group___callbacks.md) ([Shell](class_shell.md) shell, [Player](class_player.md) player, float damage) |
|  | |
| bool | [ShellExplode](group___callbacks.md) ([Shell](class_shell.md) shell) |
|  | |
| void | [OnLog](group___callbacks.md) (string message) |
|  | |
| bool | [FineItem](group___callbacks.md) ([Items](class_items.md) item, int fineid) |
|  | |
| void | [OnCreateItem](group___callbacks.md) ([Items](class_items.md) item) |
|  | |
| void | [OnRemoveItem](group___callbacks.md) ([Items](class_items.md) item) |
|  | |
| void | [OnCreateNPC](group___callbacks.md) ([NPC](class_n_p_c.md) npc) |
|  | |
| void | [OnRemoveNPC](group___callbacks.md) ([NPC](class_n_p_c.md) npc) |
|  | |
| void | [OnCreateCorpse](group___callbacks.md) ([Corpse](class_corpse.md) corpse) |
|  | |
| void | [OnRemoveCorpse](group___callbacks.md) ([Corpse](class_corpse.md) corpse) |
|  | |
| void | [OnCreateObject](group___callbacks.md) ([Object](class_object.md) obj) |
|  | |
| void | [OnRemoveObject](group___callbacks.md) ([Object](class_object.md) obj) |
|  | |
| void | [OnCreateLight](group___callbacks.md) ([Light](class_light.md) light) |
|  | |
| void | [OnRemoveLight](group___callbacks.md) ([Light](class_light.md) light) |
|  | |
| void | [OnCreateGUIElement](group___callbacks.md) ([GUIElement](class_g_u_i_element.md) element) |
|  | |
| void | [OnRemoveGUIElement](group___callbacks.md) ([GUIElement](class_g_u_i_element.md) element) |
|  | |
| void | [OnCreateShell](group___callbacks.md) ([Shell](class_shell.md) shell) |
|  | |
| void | [OnRemoveShell](group___callbacks.md) ([Shell](class_shell.md) shell) |
|  | |

## Detailed Description

Callbacks that can be registered by RegisterCallback(). Remember that you can register your own function names. This is examples of all exist callbacks

## Function Documentation

## [◆](group___callbacks.md)OnInitialize()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void OnInitialize | ( |  | ) |  |

Calls when script loaded

## [◆](group___callbacks.md)OnTerminate()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void OnTerminate | ( |  | ) |  |

Calls when script remove. (exit, shutdown, etc...)

## [◆](group___callbacks.md)ServerUpdate()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void ServerUpdate | ( |  | ) |  |

Calls every UPS tick

## [◆](group___callbacks.md)ServerConsole()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool ServerConsole | ( | string | *command* | ) |  |

Calls when somebody write to server Windows console. If returns false, then default commands will be cancelled

## [◆](group___callbacks.md)ServerRestart()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void ServerRestart | ( |  | ) |  |

Calls when server restart

## [◆](group___callbacks.md)WorldLoaded()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void WorldLoaded | ( |  | ) |  |

When scene has loaded. You can use world functions after this callback

## [◆](group___callbacks.md)WorldUpdate()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void WorldUpdate | ( |  | ) |  |

When scene is update. Calls every 16 milliseconds (60 UPS)

## [◆](group___callbacks.md)PlayerUpdate()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void PlayerUpdate | ( | [Player](class_player.md) | *player* | ) |  |

When server received player data

## [◆](group___callbacks.md)PlayerConnect()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void PlayerConnect | ( | [Player](class_player.md) | *player* | ) |  |

When player connected to server.

## [◆](group___callbacks.md)PlayerDisconnect()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void PlayerDisconnect | ( | [Player](class_player.md) | *player* | ) |  |

When player disconnect or kicked in any way

## [◆](group___callbacks.md)PlayerChat()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerChat | ( | [Player](class_player.md) | *player*, |
|  |  | string | *text* ) |

When player send chat message. If return false, then message won't send

## [◆](group___callbacks.md)PlayerAttachesUpdate()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void PlayerAttachesUpdate | ( | [Player](class_player.md) | *player* | ) |  |

When attaches of player updates. You can make your own attaches update there

## [◆](group___callbacks.md)PlayerTakeItem()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerTakeItem | ( | [Player](class_player.md) | *player*, |
|  |  | [Items](class_items.md) | *item* ) |

When player takes item. If returns false, then action will cancel. While this, the item still not in player's inventory

## [◆](group___callbacks.md)PlayerDropItem()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerDropItem | ( | [Player](class_player.md) | *player*, |
|  |  | [Items](class_items.md) | *item* ) |

When player drops item. If returns false, then action will cancel

## [◆](group___callbacks.md)PlayerDialogAction()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerDialogAction | ( | [Player](class_player.md) | *player*, |
|  |  | int | *index*, |
|  |  | bool | *response*, |
|  |  | string | *input*, |
|  |  | int | *selecteditem* ) |

When player response in showed dialog. You can determine what dialog is responsed by index

## [◆](group___callbacks.md)PlayerShootPlayer()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerShootPlayer | ( | [Player](class_player.md) | *shooter*, |
|  |  | [Player](class_player.md) | *dest*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | float | *damage*, |
|  |  | bool | *headshot* ) |

When player shooted to player. If returns false, then dest won't be damaged and damage rotation won't be sended. Usually, player dies when [Player::GetInjuries()](class_player.md) >= 8.0 - damage

## [◆](group___callbacks.md)PlayerShoot()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerShoot | ( | [Player](class_player.md) | *player*, |
|  |  | [Items](class_items.md) | *item*, |
|  |  | int | *weaponattach* ) |

When player shoot by shoots count. If returns false, then real shoots count won't be add, and old shoots count will be set. You can restrict shooting by this

## [◆](group___callbacks.md)PlayerPressPlayer()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerPressPlayer | ( | [Player](class_player.md) | *src*, |
|  |  | [Player](class_player.md) | *dest* ) |

When player click on player in tab list (P)

## [◆](group___callbacks.md)PlayerConsole()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerConsole | ( | [Player](class_player.md) | *player*, |
|  |  | string | *input* ) |

When player write something to console. If returns false, then won't be executed

## [◆](group___callbacks.md)PlayerDeath()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerDeath | ( | [Player](class_player.md) | *player*, |
|  |  | [Corpse](class_corpse.md) | *corpse* ) |

When player death. [Corpse](class_corpse.md) can be NULL

## [◆](group___callbacks.md)PlayerRespawn()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void PlayerRespawn | ( | [Player](class_player.md) | *player* | ) |  |

When player respawn

## [◆](group___callbacks.md)PlayerHitPlayer()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerHitPlayer | ( | [Player](class_player.md) | *src*, |
|  |  | [Player](class_player.md) | *dest*, |
|  |  | int | *mousedata*, |
|  |  | float | *distance* ) |

When player click on player in game by LMB (&1) RMB (&2) MMB (&4). Maximum distance is 1.0, but can be more due to ping or player is cheater

## [◆](group___callbacks.md)PlayerExploreCorpse()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerExploreCorpse | ( | [Player](class_player.md) | *player*, |
|  |  | [Corpse](class_corpse.md) | *corpse* ) |

When player explore corpse. If returns false, then items won't be explored, but corpse will be mark as explored. You can set explored state to false

## [◆](group___callbacks.md)PlayerClickObject()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerClickObject | ( | [Player](class_player.md) | *player*, |
|  |  | [Object](class_object.md) | *object* ) |

When player click object if this object is touchable

## [◆](group___callbacks.md)PlayerShootObject()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerShootObject | ( | [Player](class_player.md) | *player*, |
|  |  | [Object](class_object.md) | *object* ) |

When player shoot object if object model pick mode is 2

## [◆](group___callbacks.md)PlayerUseDoorButton()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerUseDoorButton | ( | [Player](class_player.md) | *player*, |
|  |  | [Door](class_door.md) | *door*, |
|  |  | [Items](class_items.md) | *useditem* ) |

When player use door button with item. Item can be NULL. If returns false, then action will cancel

## [◆](group___callbacks.md)PlayerUseItem()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerUseItem | ( | [Player](class_player.md) | *player*, |
|  |  | [Items](class_items.md) | *item* ) |

When player use item. If you remove item or returns false, then action will cancel

## [◆](group___callbacks.md)PlayerSelectItem()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerSelectItem | ( | [Player](class_player.md) | *player*, |
|  |  | [Items](class_items.md) | *item* ) |

When player select item. If returns false, can cancel action for SCP-513

## [◆](group___callbacks.md)PlayerUse914()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerUse914 | ( | [Player](class_player.md) | *player*, |
|  |  | int | *fineid* ) |

When player fine inside SCP-914.

## [◆](group___callbacks.md)PlayerSelectGUI()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerSelectGUI | ( | [Player](class_player.md) | *player*, |
|  |  | [GUIElement](class_g_u_i_element.md) | *element* ) |

When player click on selectable GUI Element. Element is null when player press ESCAPE

## [◆](group___callbacks.md)PlayerVoice()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerVoice | ( | [Player](class_player.md) | *player*, |
|  |  | int | *bank*, |
|  |  | bool | *radio* ) |

When player communicate voice. If returns false, then action will cancel. Don't remove bank in any way.

## [◆](group___callbacks.md)PlayerTeleportElevator()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerTeleportElevator | ( | [Player](class_player.md) | *player*, |
|  |  | [Room](class_room.md) | *room*, |
|  |  | [Entity](class_entity.md) | *firstentity*, |
|  |  | [Entity](class_entity.md) | *secondentity*, |
|  |  | float | *offsetx*, |
|  |  | float | *offsety* ) |

When player teleport in elevator.

## [◆](group___callbacks.md)PlayerShootNPC()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerShootNPC | ( | [Player](class_player.md) | *player*, |
|  |  | [NPC](class_n_p_c.md) | *npc* ) |

When player shoot at [NPC](class_n_p_c.md).

## [◆](group___callbacks.md)PlayerKeyAction()

|  |  |  |  |
| --- | --- | --- | --- |
| void PlayerKeyAction | ( | [Player](class_player.md) | *player*, |
|  |  | int | *newmask*, |
|  |  | int | *prevmask* ) |

When key state changed. Use & to compare mask bits. How to check that button is pressed: 'if((newmask & KEY\_M) && !(prevmask & KEY\_M))' or see funcs and keytypes in uerm.as include

## [◆](group___callbacks.md)PlayerSpectateAction()

|  |  |  |  |
| --- | --- | --- | --- |
| bool PlayerSpectateAction | ( | [Player](class_player.md) | *player*, |
|  |  | [Player](class_player.md) | *target*, |
|  |  | int | *mode* ) |

When player wants to spectate player with specified mode. If returns false, then action will be canceled.

## [◆](group___callbacks.md)IncomingConnection()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void IncomingConnection | ( | [Connection](class_connection.md) | *conn* | ) |  |

When player connect to server. Can be closed at any time.

## [◆](group___callbacks.md)ConnectionLoaded()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool ConnectionLoaded | ( | [Connection](class_connection.md) | *conn* | ) |  |

When player loaded into game. You can disallow to connect to server and make queue by return false. It can executes when somebody disconnects from the server and a free slot is appeared.

## [◆](group___callbacks.md)ConnectionClosed()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void ConnectionClosed | ( | [Connection](class_connection.md) | *conn* | ) |  |

When incoming connection closed. Executes always.

## [◆](group___callbacks.md)ShellDamagePlayer()

|  |  |  |  |
| --- | --- | --- | --- |
| bool ShellDamagePlayer | ( | [Shell](class_shell.md) | *shell*, |
|  |  | [Player](class_player.md) | *player*, |
|  |  | float | *damage* ) |

When shell damaged a player. Returning false will skip damage

## [◆](group___callbacks.md)ShellExplode()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool ShellExplode | ( | [Shell](class_shell.md) | *shell* | ) |  |

When shell explode. Return false will cancel explosion.

## [◆](group___callbacks.md)OnLog()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnLog | ( | string | *message* | ) |  |

Capture every message in console

## [◆](group___callbacks.md)FineItem()

|  |  |  |  |
| --- | --- | --- | --- |
| bool FineItem | ( | [Items](class_items.md) | *item*, |
|  |  | int | *fineid* ) |

When item fine inside SCP-914. If returns false, then action will cancel

## [◆](group___callbacks.md)OnCreateItem()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnCreateItem | ( | [Items](class_items.md) | *item* | ) |  |

When created any item. Don't remove while executing this.

## [◆](group___callbacks.md)OnRemoveItem()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnRemoveItem | ( | [Items](class_items.md) | *item* | ) |  |

When removed any item. Don't remove while executing this.

## [◆](group___callbacks.md)OnCreateNPC()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnCreateNPC | ( | [NPC](class_n_p_c.md) | *npc* | ) |  |

When created any [NPC](class_n_p_c.md). Don't remove while executing this.

## [◆](group___callbacks.md)OnRemoveNPC()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnRemoveNPC | ( | [NPC](class_n_p_c.md) | *npc* | ) |  |

When removed any [NPC](class_n_p_c.md). Don't remove while executing this.

## [◆](group___callbacks.md)OnCreateCorpse()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnCreateCorpse | ( | [Corpse](class_corpse.md) | *corpse* | ) |  |

When created any corpse. Don't remove while executing this, use OnPlayerDeath with fully loaded corpse.

## [◆](group___callbacks.md)OnRemoveCorpse()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnRemoveCorpse | ( | [Corpse](class_corpse.md) | *corpse* | ) |  |

When removed any corpse. Don't remove while executing this.

## [◆](group___callbacks.md)OnCreateObject()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnCreateObject | ( | [Object](class_object.md) | *obj* | ) |  |

When created any object. Don't remove while executing this.

## [◆](group___callbacks.md)OnRemoveObject()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnRemoveObject | ( | [Object](class_object.md) | *obj* | ) |  |

When removed any object. Don't remove while executing this.

## [◆](group___callbacks.md)OnCreateLight()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnCreateLight | ( | [Light](class_light.md) | *light* | ) |  |

When created any light. Don't remove while executing this.

## [◆](group___callbacks.md)OnRemoveLight()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnRemoveLight | ( | [Light](class_light.md) | *light* | ) |  |

When removed any light. Don't remove while executing this.

## [◆](group___callbacks.md)OnCreateGUIElement()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnCreateGUIElement | ( | [GUIElement](class_g_u_i_element.md) | *element* | ) |  |

When created any [GUIElement](class_g_u_i_element.md). Don't remove while executing this.

## [◆](group___callbacks.md)OnRemoveGUIElement()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnRemoveGUIElement | ( | [GUIElement](class_g_u_i_element.md) | *element* | ) |  |

When removed any [GUIElement](class_g_u_i_element.md). Don't remove while executing this.

## [◆](group___callbacks.md)OnCreateShell()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnCreateShell | ( | [Shell](class_shell.md) | *shell* | ) |  |

When shell created. Can be removed, but you need to check always when use [World::CreateShell](class_world.md)

## [◆](group___callbacks.md)OnRemoveShell()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void OnRemoveShell | ( | [Shell](class_shell.md) | *shell* | ) |  |

When removed any [GUIElement](class_g_u_i_element.md). Don't remove while executing this.

- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
