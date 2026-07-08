<!-- source: http://scpcbmr.42web.io/class_connection.html -->
# SCP: Containment Breach 2 Scripting: Connection Class Reference

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

[Public Member Functions](class_connection.md) |
[List of all members](class_connection-members.md)

Connection Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| int | [GetPort](class_connection.md) () |
|  | |
| string & | [GetLanguage](class_connection.md) () |
|  | |
| string & | [GetHWID](class_connection.md) (int wmid=0) |
|  | |
| string & | [GetIP](class_connection.md) () |
|  | |
| string & | [GetSteamID](class_connection.md) () |
|  | |
| int | [GetQueue](class_connection.md) () |
|  | |
| bool | [Join](class_connection.md) () |
|  | |
| void | [Accept](class_connection.md) () |
|  | |
| void | [Cancel](class_connection.md) (int code) |
|  | |
| void | [Cancel](class_connection.md) (string &in custom="") |
|  | |
| void | [Remove](class_connection.md) () |
|  | |

## Member Function Documentation

## [◆](class_connection.md)GetPort()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Connection::GetPort | ( |  | ) |  |

Get port

## [◆](class_connection.md)GetLanguage()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Connection::GetLanguage | ( |  | ) |  |

Get language

## [◆](class_connection.md)GetHWID()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| string & Connection::GetHWID | ( | int | *wmid* = 0 | ) |  |

Get HWID. 0 - all. Look for another WMID in uerm.as

## [◆](class_connection.md)GetIP()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Connection::GetIP | ( |  | ) |  |

Get IP

## [◆](class_connection.md)GetSteamID()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Connection::GetSteamID | ( |  | ) |  |

Get SteamID

## [◆](class_connection.md)GetQueue()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Connection::GetQueue | ( |  | ) |  |

Get connection queue. If 0 then it's not loaded yet.

## [◆](class_connection.md)Join()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Connection::Join | ( |  | ) |  |

Join connection even if the number of max slots is exceeded or player still not loaded. Return true if successfully, also a connection is removed.

## [◆](class_connection.md)Accept()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Connection::Accept | ( |  | ) |  |

Accept connection anyway even with max players reached and player will wait joining in queue. Should work only in IncomingConnection\_c

## [◆](class_connection.md)Cancel() [1/2]

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Connection::Cancel | ( | int | *code* | ) |  |

Cancel connection with specified code. Should work only in IncomingConnection\_c and in ConnectionLoaded\_c

## [◆](class_connection.md)Cancel() [2/2]

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Connection::Cancel | ( | string &in | *custom* = "" | ) |  |

Cancel connection with custom error. Should work only in IncomingConnection\_c and in ConnectionLoaded\_c

## [◆](class_connection.md)Remove()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Connection::Remove | ( |  | ) |  |

Remove authentication at anytime silently. The object will not be deleted immediately, but after a couple of seconds. It is recommended to use the function outside of callbacks, because there's an immediate [Cancel()](class_connection.md)

- [Connection](class_connection.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
