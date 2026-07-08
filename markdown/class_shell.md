<!-- source: http://scpcbmr.42web.io/class_shell.html -->
# SCP: Containment Breach 2 Scripting: Shell Class Reference

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

[Public Member Functions](class_shell.md) |
[List of all members](class_shell-members.md)

Shell Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| [Entity](class_entity.md) | **GetEntity** () |
|  | |
| int | [GetIndex](class_shell.md) () |
|  | |
| void | [GetVelocity](class_shell.md) (float &out x, float &out y, float &out z) |
|  | |
| string & | [GetActionEmitter](class_shell.md) () |
|  | |
| int | [GetEmitter](class_shell.md) () |
|  | |
| string & | [GetActionSound](class_shell.md) () |
|  | |
| string & | [GetCollisionSound](class_shell.md) () |
|  | |
| string & | [GetSound](class_shell.md) () |
|  | |
| float | [GetSpeed](class_shell.md) () |
|  | |
| float | [GetForce](class_shell.md) () |
|  | |
| float | [GetRestitution](class_shell.md) () |
|  | |
| float | [GetGravity](class_shell.md) () |
|  | |
| float | [GetCollisionRadius](class_shell.md) () |
|  | |
| float | [GetDamage](class_shell.md) () |
|  | |
| float | [GetTimeout](class_shell.md) () |
|  | |
| float | [GetImpactTime](class_shell.md) () |
|  | |
| int | [GetAction](class_shell.md) () |
|  | |
| float | [GetActionRadius](class_shell.md) () |
|  | |
| bool | [IsSticky](class_shell.md) () |
|  | |
| uint | [GetStickFlags](class_shell.md) () |
|  | |
| int | [GetStickIndex](class_shell.md) () |
|  | |
| int | [GetWeapon](class_shell.md) () |
|  | |
| [Player](class_player.md) | [GetShooter](class_shell.md) () |
|  | |
| void | [Unstick](class_shell.md) () |
|  | |
| void | [SetSticky](class_shell.md) (bool sticky) |
|  | |
| void | [SetVelocity](class_shell.md) (float x, float y, float z) |
|  | |
| void | [SetActionEmitter](class_shell.md) (string &in emitters) |
|  | |
| void | [SetEmitter](class_shell.md) (int id) |
|  | |
| void | [SetActionSound](class_shell.md) (string &in sound) |
|  | |
| void | [SetCollisionSound](class_shell.md) (string &in sound) |
|  | |
| void | [SetSound](class_shell.md) (string &in sound) |
|  | |
| void | [SetSpeed](class_shell.md) (float speed) |
|  | |
| void | [SetForce](class_shell.md) (float force) |
|  | |
| void | [SetRestitution](class_shell.md) (float restitution) |
|  | |
| void | [SetGravity](class_shell.md) (float gravity) |
|  | |
| void | [SetCollisionRadius](class_shell.md) (float radius) |
|  | |
| void | [SetTimeout](class_shell.md) (float time) |
|  | |
| void | [SetImpactTime](class_shell.md) (float time) |
|  | |
| void | [SetDamage](class_shell.md) (float damage) |
|  | |
| void | [SetAction](class_shell.md) (int action) |
|  | |
| void | [SetActionRadius](class_shell.md) (float radius) |
|  | |
| void | [SetShooter](class_shell.md) ([Player](class_player.md) player) |
|  | |
| void | [Remove](class_shell.md) (bool action=false) |
|  | |

## Member Function Documentation

## [◆](class_shell.md)GetIndex()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Shell::GetIndex | ( |  | ) |  |

Get shell index

## [◆](class_shell.md)GetVelocity()

|  |  |  |  |
| --- | --- | --- | --- |
| void Shell::GetVelocity | ( | float &out | *x*, |
|  |  | float &out | *y*, |
|  |  | float &out | *z* ) |

Get shell velocity

## [◆](class_shell.md)GetActionEmitter()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Shell::GetActionEmitter | ( |  | ) |  |

Get shell action emitter strings ids between spaces

## [◆](class_shell.md)GetEmitter()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Shell::GetEmitter | ( |  | ) |  |

Get shell emitter id

## [◆](class_shell.md)GetActionSound()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Shell::GetActionSound | ( |  | ) |  |

Get shell action sound

## [◆](class_shell.md)GetCollisionSound()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Shell::GetCollisionSound | ( |  | ) |  |

Get shell collision sound

## [◆](class_shell.md)GetSound()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Shell::GetSound | ( |  | ) |  |

Get shell sound

## [◆](class_shell.md)GetSpeed()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Shell::GetSpeed | ( |  | ) |  |

Get shell speed

## [◆](class_shell.md)GetForce()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Shell::GetForce | ( |  | ) |  |

Get shell explosion force. 100.0 by default

## [◆](class_shell.md)GetRestitution()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Shell::GetRestitution | ( |  | ) |  |

Get shell restitution

## [◆](class_shell.md)GetGravity()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Shell::GetGravity | ( |  | ) |  |

Get shell gravity

## [◆](class_shell.md)GetCollisionRadius()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Shell::GetCollisionRadius | ( |  | ) |  |

Get shell collision radius

## [◆](class_shell.md)GetDamage()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Shell::GetDamage | ( |  | ) |  |

Get shell non-distance damage. The ShellDamagePlayer\_c callback has damage by distance

## [◆](class_shell.md)GetTimeout()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Shell::GetTimeout | ( |  | ) |  |

Get shell timeout. 10.0 seconds by default

## [◆](class_shell.md)GetImpactTime()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Shell::GetImpactTime | ( |  | ) |  |

Get shell impact (explosion action) time after collision.

## [◆](class_shell.md)GetAction()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Shell::GetAction | ( |  | ) |  |

Get shell action. 1 - emp action.

## [◆](class_shell.md)GetActionRadius()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Shell::GetActionRadius | ( |  | ) |  |

Get shell radius for the action shell.

## [◆](class_shell.md)IsSticky()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Shell::IsSticky | ( |  | ) |  |

Is shell has sticky physics

## [◆](class_shell.md)GetStickFlags()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| uint Shell::GetStickFlags | ( |  | ) |  |

Is shell sticked to any surface, returns bitwise: 1 - sticked to surface, 2 - sticked to player, 4 - sticked to [Object](class_object.md)

## [◆](class_shell.md)GetStickIndex()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Shell::GetStickIndex | ( |  | ) |  |

If shell sticked to any surface, returns the sticked surface index. If just sticked to surface (1), then it will return 0.

## [◆](class_shell.md)GetWeapon()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Shell::GetWeapon | ( |  | ) |  |

Get weapon id

## [◆](class_shell.md)GetShooter()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Player](class_player.md) Shell::GetShooter | ( |  | ) |  |

Get shell shooter. Can be NULL

## [◆](class_shell.md)Unstick()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Shell::Unstick | ( |  | ) |  |

Unstick shell from surface if sticked.

## [◆](class_shell.md)SetSticky()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetSticky | ( | bool | *sticky* | ) |  |

Set sticky.

## [◆](class_shell.md)SetVelocity()

|  |  |  |  |
| --- | --- | --- | --- |
| void Shell::SetVelocity | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Set shell velocity

## [◆](class_shell.md)SetActionEmitter()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetActionEmitter | ( | string &in | *emitters* | ) |  |

Set shell action emitters strings ids between spaces

## [◆](class_shell.md)SetEmitter()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetEmitter | ( | int | *id* | ) |  |

Set shell emitter id

## [◆](class_shell.md)SetActionSound()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetActionSound | ( | string &in | *sound* | ) |  |

Set shell action sound

## [◆](class_shell.md)SetCollisionSound()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetCollisionSound | ( | string &in | *sound* | ) |  |

Set shell collision sound

## [◆](class_shell.md)SetSound()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetSound | ( | string &in | *sound* | ) |  |

Set shell sound

## [◆](class_shell.md)SetSpeed()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetSpeed | ( | float | *speed* | ) |  |

Set shell speed

## [◆](class_shell.md)SetForce()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetForce | ( | float | *force* | ) |  |

Set shell explosion force. 100.0 by default.

## [◆](class_shell.md)SetRestitution()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetRestitution | ( | float | *restitution* | ) |  |

Set shell restitution

## [◆](class_shell.md)SetGravity()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetGravity | ( | float | *gravity* | ) |  |

Set shell gravity

## [◆](class_shell.md)SetCollisionRadius()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetCollisionRadius | ( | float | *radius* | ) |  |

Set shell collision radius

## [◆](class_shell.md)SetTimeout()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetTimeout | ( | float | *time* | ) |  |

Set shell timeout. 10.0 seconds by default

## [◆](class_shell.md)SetImpactTime()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetImpactTime | ( | float | *time* | ) |  |

Set shell impact (explosion action) time after collision.

## [◆](class_shell.md)SetDamage()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetDamage | ( | float | *damage* | ) |  |

Set shell non-distance damage. The ShellDamagePlayer\_c callback will get damage by distance

## [◆](class_shell.md)SetAction()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetAction | ( | int | *action* | ) |  |

Set shell action. 1 - emp action.

## [◆](class_shell.md)SetActionRadius()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetActionRadius | ( | float | *radius* | ) |  |

Set shell radius for the action shell.

## [◆](class_shell.md)SetShooter()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::SetShooter | ( | [Player](class_player.md) | *player* | ) |  |

Set shell shooter

## [◆](class_shell.md)Remove()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Shell::Remove | ( | bool | *action* = false | ) |  |

Removes the shell. Action if true

- [Shell](class_shell.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
