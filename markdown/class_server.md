<!-- source: http://scpcbmr.42web.io/class_server.html -->
# SCP: Containment Breach 2 Scripting: Server Class Reference

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

[Public Member Functions](class_server.md) |
[Public Attributes](class_server.md) |
[List of all members](class_server-members.md)

Server Class Reference

`#include <all.h>`

|  |  |
| --- | --- |
| Public Member Functions | |
| void | [Restart](class_server.md) () |
|  | |
| void | [Console](class_server.md) (string &in) |
|  | |
| string & | [GetVersion](class_server.md) () |
|  | |
| void | [AddVersion](class_server.md) (string &in version) |
|  | |
| void | [RemoveVersion](class_server.md) (string &in version) |
|  | |
| int | [GetUPS](class_server.md) () |
|  | |
| [Config](class_config.md) | [ParseConfig](class_server.md) (string &in filename) |
|  | |

|  |  |
| --- | --- |
| Public Attributes | |
| string & | [hostname](class_server.md) |
|  | |
| int | [port](class_server.md) |
|  | |
| int | [corpsealivetime](class_server.md) |
|  | |
| int | [timeout](class_server.md) |
|  | |
| bool | [chat](class_server.md) |
|  | |
| bool | [console](class_server.md) |
|  | |
| int | [voicebitrate](class_server.md) |
|  | |
| int | [maxplayers](class_server.md) |
|  | |
| string & | [mapseed](class_server.md) |
|  | |
| string & | [adminpassword](class_server.md) |
|  | |
| int | [difficulty](class_server.md) |
|  | |
| string & | [gamemode](class_server.md) |
|  | |
| int | [emptybehaviour](class_server.md) |
|  | |
| bool | [scriptsautoload](class_server.md) |
|  | |
| bool | [disablenpcs](class_server.md) |
|  | |
| float | [proximityplayers](class_server.md) |
|  | |
| float | [mapbounds](class_server.md) |
|  | |
| int | [respawntime](class_server.md) |
|  | |
| string & | [contenturl](class_server.md) |
|  | |
| string & | [password](class_server.md) |
|  | |
| bool | [improvedgates](class_server.md) |
|  | |
| int | [mapsize](class_server.md) |
|  | |
| bool | [allowjump](class_server.md) |
|  | |
| string & | [description](class_server.md) |
|  | |
| bool | [fastslots](class_server.md) |
|  | |
| float | [gravity](class_server.md) |
|  | |
| int | [holiday](class_server.md) |
|  | |
| string & | [addonsfile](class_server.md) |
|  | |
| bool | [enablehud](class_server.md) |
|  | |
| int | [max\_items](class_server.md) |
|  | |
| int | [max\_objects](class_server.md) |
|  | |
| int | [max\_corpses](class_server.md) |
|  | |
| int | [max\_lights](class_server.md) |
|  | |
| bool | [player\_culling](class_server.md) |
|  | |
| bool | [steam\_auth](class_server.md) |
|  | |
| bool | [fall\_damage](class_server.md) |
|  | |

## Detailed Description

Global property is 'server'

## Member Function Documentation

## [◆](class_server.md)Restart()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Server::Restart | ( |  | ) |  |

Restart server

## [◆](class_server.md)Console()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Server::Console | ( | string & | *in* | ) |  |

Send console message to server world

## [◆](class_server.md)GetVersion()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Server::GetVersion | ( |  | ) |  |

Get server version

## [◆](class_server.md)AddVersion()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Server::AddVersion | ( | string &in | *version* | ) |  |

Allows the version. Since version 2.1, the network code will try to maintain compatibility.

## [◆](class_server.md)RemoveVersion()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Server::RemoveVersion | ( | string &in | *version* | ) |  |

Disallows the version. Empty string disallow all versions.

## [◆](class_server.md)GetUPS()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Server::GetUPS | ( |  | ) |  |

Get server updates count per second

## [◆](class_server.md)ParseConfig()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Config](class_config.md) Server::ParseConfig | ( | string &in | *filename* | ) |  |

Parse .cfg file

## Member Data Documentation

## [◆](class_server.md)hostname

|  |
| --- |
| string& Server::hostname |

Changes hostname

## [◆](class_server.md)port

|  |
| --- |
| int Server::port |

Not used. Using this variable may harm the server.

## [◆](class_server.md)corpsealivetime

|  |
| --- |
| int Server::corpsealivetime |

Dead bodies removal time in seconds (may cause perfomance issues if too high).

## [◆](class_server.md)timeout

|  |
| --- |
| int Server::timeout |

[Player](class_player.md) timeout connection loss kick in seconds. Will be applied while server starting/restarting

## [◆](class_server.md)chat

|  |
| --- |
| bool Server::chat |

Allow players to chat

## [◆](class_server.md)console

|  |
| --- |
| bool Server::console |

Allow console for everybody

## [◆](class_server.md)voicebitrate

|  |
| --- |
| int Server::voicebitrate |

KBit/s, lower value will reduce network eating but quality will be bad, 0 - auto, 255 - max. 60 is recommended

## [◆](class_server.md)maxplayers

|  |
| --- |
| int Server::maxplayers |

60 is VERY recommended due to MTU limit (some players may lose data if more than 60)

## [◆](class_server.md)mapseed

|  |
| --- |
| string& Server::mapseed |

Changes map seed. Will apply after restarting. Empty string - random seed.

## [◆](class_server.md)adminpassword

|  |
| --- |
| string& Server::adminpassword |

Password for console allow, empty - disabled. Use /logadmin [password]

## [◆](class_server.md)difficulty

|  |
| --- |
| int Server::difficulty |

0 - safe, 1 - euclid, 2 - keter, 3 - apollyon

## [◆](class_server.md)gamemode

|  |
| --- |
| string& Server::gamemode |

Gamemode

## [◆](class_server.md)emptybehaviour

|  |
| --- |
| int Server::emptybehaviour |

0 - restart server and waiting for players, 1 - pause and waiting for players, 2 - without pause and restart, 0 not recommended

## [◆](class_server.md)scriptsautoload

|  |
| --- |
| bool Server::scriptsautoload |

Not used

## [◆](class_server.md)disablenpcs

|  |
| --- |
| bool Server::disablenpcs |

Not used. Using this variable may harm the server.

## [◆](class_server.md)proximityplayers

|  |
| --- |
| float Server::proximityplayers |

Deprecated. Use 'player\_culling'

## [◆](class_server.md)mapbounds

|  |
| --- |
| float Server::mapbounds |

The bounds of map (player XYZ can't go through this value)

## [◆](class_server.md)respawntime

|  |
| --- |
| int Server::respawntime |

Respawn time in seconds. 0 - disable auto-respawn.

## [◆](class_server.md)contenturl

|  |
| --- |
| string& Server::contenturl |

Content URL for content downloading. Can be HTTP and HTTPs

## [◆](class_server.md)password

|  |
| --- |
| string& Server::password |

[Server](class_server.md) password

## [◆](class_server.md)improvedgates

|  |
| --- |
| bool Server::improvedgates |

Use it only in ServerRestart\_c callback.

## [◆](class_server.md)mapsize

|  |
| --- |
| int Server::mapsize |

6-28 is allowed. 21 is default.

## [◆](class_server.md)allowjump

|  |
| --- |
| bool Server::allowjump |

Allow jumps

## [◆](class_server.md)description

|  |
| --- |
| string& Server::description |

[Server](class_server.md) description

## [◆](class_server.md)fastslots

|  |
| --- |
| bool Server::fastslots |

Allow fast slots

## [◆](class_server.md)gravity

|  |
| --- |
| float Server::gravity |

Gravity multiplier

## [◆](class_server.md)holiday

|  |
| --- |
| int Server::holiday |

Spawns holiday props ( 0 - disable, 1 - New year).

## [◆](class_server.md)addonsfile

|  |
| --- |
| string& Server::addonsfile |

Addon file path. addons.jsonc by default

## [◆](class_server.md)enablehud

|  |
| --- |
| bool Server::enablehud |

Enables main game HUD

## [◆](class_server.md)max\_items

|  |
| --- |
| int Server::max\_items |

Max items limit.

## [◆](class_server.md)max\_objects

|  |
| --- |
| int Server::max\_objects |

Max objects limit.

## [◆](class_server.md)max\_corpses

|  |
| --- |
| int Server::max\_corpses |

Max corpses limit.

## [◆](class_server.md)max\_lights

|  |
| --- |
| int Server::max\_lights |

Max lights limit.

## [◆](class_server.md)player\_culling

|  |
| --- |
| bool Server::player\_culling |

Useful for anti-wallhack.

## [◆](class_server.md)steam\_auth

|  |
| --- |
| bool Server::steam\_auth |

Steam authentication.

## [◆](class_server.md)fall\_damage

|  |
| --- |
| bool Server::fall\_damage |

Fall damage.

- [Server](class_server.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
