<!-- source: http://scpcbmr.42web.io/class_player.html -->
# SCP: Containment Breach 2 Scripting: Player Class Reference

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

[Public Member Functions](class_player.md) |
[List of all members](class_player-members.md)

Player Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| [Entity](class_entity.md) | [GetHitbox](class_player.md) () |
|  | |
| [Entity](class_entity.md) | [GetHead](class_player.md) () |
|  | |
| [Entity](class_entity.md) | [GetEntity](class_player.md) () |
|  | |
| void | [GetScreenSize](class_player.md) (int &out width, int &out height) |
|  | |
| string & | [GetLanguage](class_player.md) () |
|  | |
| string & | [GetIP](class_player.md) () |
|  | |
| string & | [GetSteamID](class_player.md) () |
|  | |
| string & | [GetHWID](class_player.md) (int wmid=0) |
|  | |
| string & | [GetName](class_player.md) () |
|  | |
| void | [SetSteamID](class_player.md) (string &in steamid64) |
|  | |
| void | [SetName](class_player.md) (string &in name) |
|  | |
| int | [GetPing](class_player.md) () |
|  | |
| int | [GetTime](class_player.md) () |
|  | |
| int | [GetIndex](class_player.md) () |
|  | |
| string & | [GetVersion](class_player.md) () |
|  | |
| bool | [IsInvisible](class_player.md) () |
|  | |
| bool | [IsInvisibleForPlayer](class_player.md) ([Player](class_player.md) player) |
|  | |
| void | [SetInvisible](class_player.md) (bool inv) |
|  | |
| void | [SetLocalInvisible](class_player.md) ([Player](class_player.md) player, bool inv) |
|  | |
| void | [Kick](class_player.md) (int code=0, string &in custom="") |
|  | |
| void | [ShowDialog](class_player.md) (int type, int index, string &in header, string &in message, string &in leftbutton, string &in rightbutton="", bool align=true) |
|  | |
| void | [ShowDialog](class_player.md) (int type, DIALOGCALLBACK@ callback, string &in header, string &in message, string &in leftbutton, string &in rightbutton="", bool align=true) |
|  | |
| void | [SetDialogData](class_player.md) (string &in data) |
|  | |
| string & | [GetDialogData](class_player.md) () |
|  | |
| void | [HideDialog](class_player.md) () |
|  | |
| void | [SendMessage](class_player.md) (string &in message, float time=6.0, bool localized=false) |
|  | |
| void | [Desync](class_player.md) (bool value) |
|  | |
| bool | [IsDesync](class_player.md) () |
|  | |
| void | [SetSpectatePlayer](class_player.md) ([Player](class_player.md) target) |
|  | |
| void | [SetSpectateMode](class_player.md) (int mode) |
|  | |
| [Player](class_player.md) | [GetSpectatePlayer](class_player.md) () |
|  | |
| int | [GetSpectateMode](class_player.md) () |
|  | |
| bool | [Kill](class_player.md) (bool bloody=false, bool createcorpse=true) |
|  | |
| bool | [Respawn](class_player.md) () |
|  | |
| bool | [IsDead](class_player.md) () |
|  | |
| void | [SetInjuries](class_player.md) (float val) |
|  | |
| float | [GetInjuries](class_player.md) () |
|  | |
| void | [SetBloodloss](class_player.md) (float val) |
|  | |
| float | [GetBloodloss](class_player.md) () |
|  | |
| bool | [GetGodmode](class_player.md) () |
|  | |
| void | [SetGodmode](class_player.md) (bool val) |
|  | |
| void | [SetColor](class_player.md) (uint hx) |
|  | |
| uint | [GetColor](class_player.md) () |
|  | |
| void | [GetNetworkPosition](class_player.md) (float &out x, float &out y, float &out z) |
|  | |
| void | [GetNetworkRotation](class_player.md) (float &out pitch, float &out yaw) |
|  | |
| void | [SetNetworkPosition](class_player.md) (float x, float y, float z) |
|  | |
| void | [SetNetworkRotation](class_player.md) (float pitch, float yaw) |
|  | |
| void | [SetPosition](class_player.md) (float x, float y, float z, [Room](class_room.md) room=NULL, bool updatepivot=true) |
|  | |
| void | [SetRotation](class_player.md) (float pitch, float yaw) |
|  | |
| void | [Teleport](class_player.md) ([Room](class_room.md) room, float x, float y, float z, bool updatepivot=true) |
|  | |
| void | [SetRoom](class_player.md) ([Room](class_room.md) room) |
|  | |
| [Room](class_room.md) | [GetRoom](class_player.md) () |
|  | |
| void | [SetPositionBounds](class_player.md) ([Room](class_room.md) room, float x=0.0, float y=0.0, float z=0.0, float distance=0.0) |
|  | |
| void | [Explode](class_player.md) (bool thrust=false) |
|  | |
| void | [MovePlayer](class_player.md) (float speedmult, float angle) |
|  | |
| void | [IgnoreProximity](class_player.md) (bool value) |
|  | |
| void | [SendDamage](class_player.md) ([Player](class_player.md) player, float force, bool headshot, float offsetx, float offsety, float offsetz) |
|  | |
| void | [SetAdmin](class_player.md) (bool val) |
|  | |
| bool | [IsAdmin](class_player.md) () |
|  | |
| void | [SetGlobalTransmission](class_player.md) (bool val) |
|  | |
| bool | [IsGlobalTransmission](class_player.md) () |
|  | |
| bool | [SendVoice](class_player.md) (int bank, int radio=0, bool global=false, [Player](class_player.md) target=NULL) |
|  | |
| int | [GetItemsCount](class_player.md) () |
|  | |
| [Items](class_items.md) | [GetInventory](class_player.md) (int) |
|  | |
| [Items](class_items.md) | [GetSelectedItem](class_player.md) () |
|  | |
| float | [GetBlinkTimer](class_player.md) () |
|  | |
| void | [SetBlinkTimer](class_player.md) (float time) |
|  | |
| bool | [IsBlinking](class_player.md) () |
|  | |
| void | [SetBlinkEffect](class_player.md) (float effectvalue, float time) |
|  | |
| void | [GetBlinkEffect](class_player.md) (float &out effectvalue, float &out time) |
|  | |
| void | [EnableBlinking](class_player.md) (bool blink) |
|  | |
| bool | [IsBlinkingEnabled](class_player.md) () |
|  | |
| int | [GetRadio](class_player.md) () |
|  | |
| void | [PlayAnimation](class_player.md) (int animid) |
|  | |
| void | [SetNetworkAnimation](class_player.md) (int animid) |
|  | |
| void | [SetAnimation](class_player.md) (int animid) |
|  | |
| int | [GetAnimation](class_player.md) () |
|  | |
| void | [SetSpeedMultiplier](class_player.md) (float multiplier) |
|  | |
| void | [SetStaminaMultiplier](class_player.md) (float multiplier) |
|  | |
| float | [GetSpeedMultiplier](class_player.md) () |
|  | |
| float | [GetStaminaMultiplier](class_player.md) () |
|  | |
| void | [SetAttach](class_player.md) (int bodyindex, int attachmodelindex, [Items](class_items.md) item=NULL) |
|  | |
| int | [GetAttach](class_player.md) (int bodyindex) |
|  | |
| [Items](class_items.md) | [GetAttachItem](class_player.md) (int bodyindex) |
|  | |
| int | [GetModel](class_player.md) () |
|  | |
| void | [SetModel](class_player.md) (int modelid, int textureid=-1) |
|  | |
| void | [SetModelSize](class_player.md) (float) |
|  | |
| float | [GetModelSize](class_player.md) () |
|  | |
| void | [SetModelTexture](class_player.md) (int textureid) |
|  | |
| int | [GetModelTexture](class_player.md) () |
|  | |
| void | [SetCollisionRadius](class_player.md) (float) |
|  | |
| float | [GetCollisionRadius](class_player.md) () |
|  | |
| float | [GetVolume](class_player.md) () |
|  | |
| bool | [IsCrouch](class_player.md) () |
|  | |
| void | [SetGravity](class_player.md) (float multiplier) |
|  | |
| float | [GetGravity](class_player.md) () |
|  | |
| void | [SetTagText](class_player.md) (int index, string &in) |
|  | |
| void | [SetTagScales](class_player.md) (int index, float, float) |
|  | |
| void | [SetTagOffset](class_player.md) (int index, float) |
|  | |
| void | [SetTagColors](class_player.md) (int index, int, int) |
|  | |
| void | [SetTagFont](class_player.md) (int index, string &in) |
|  | |
| string & | [GetTagText](class_player.md) (int index) |
|  | |
| void | [GetTagScales](class_player.md) (int index, float &out scalex, float &out scaley) |
|  | |
| float | [GetTagOffset](class_player.md) (int index) |
|  | |
| void | [GetTagColors](class_player.md) (int index, uint &out start, uint &out end) |
|  | |
| string & | [GetTagFont](class_player.md) (int index) |
|  | |
| int | [GetShootsCount](class_player.md) () |
|  | |
| void | [SetShootsCount](class_player.md) (int count) |
|  | |
| void | [RedirectMove](class_player.md) (bool move) |
|  | |
| bool | [IsBot](class_player.md) () |
|  | |
| bool | [IsAiming](class_player.md) () |
|  | |
| void | [SetWearData](class_player.md) (int bodyindex, [Items](class_items.md) item) |
|  | |
| void | [Console](class_player.md) (string &in message) |
|  | |
| bool | [GetKeyState](class_player.md) (int keytype) |
|  | |
| void | **GetTeleportData** (float &out x, float &out y, float &out z, [Room](class_room.md) &out room, int &out tick) |
|  | |

## Member Function Documentation

## [◆](class_player.md)GetHitbox()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Player::GetHitbox | ( |  | ) |  |

Get hitbox entity

## [◆](class_player.md)GetHead()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Player::GetHead | ( |  | ) |  |

Get head entity

## [◆](class_player.md)GetEntity()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Player::GetEntity | ( |  | ) |  |

Get main entity

## [◆](class_player.md)GetScreenSize()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::GetScreenSize | ( | int &out | *width*, |
|  |  | int &out | *height* ) |

Get screen size

## [◆](class_player.md)GetLanguage()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Player::GetLanguage | ( |  | ) |  |

Get language. (ru-RU, en-EN)

## [◆](class_player.md)GetIP()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Player::GetIP | ( |  | ) |  |

Get IP

## [◆](class_player.md)GetSteamID()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Player::GetSteamID | ( |  | ) |  |

Get SteamID

## [◆](class_player.md)GetHWID()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| string & Player::GetHWID | ( | int | *wmid* = 0 | ) |  |

Get HWID. 0 - all. Look for another WMID in uerm.as

## [◆](class_player.md)GetName()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Player::GetName | ( |  | ) |  |

Get name

## [◆](class_player.md)SetSteamID()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetSteamID | ( | string &in | *steamid64* | ) |  |

Set SteamID

## [◆](class_player.md)SetName()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetName | ( | string &in | *name* | ) |  |

Set name

## [◆](class_player.md)GetPing()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Player::GetPing | ( |  | ) |  |

Get ping

## [◆](class_player.md)GetTime()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Player::GetTime | ( |  | ) |  |

Get player timeGetTime() value. Can be used for Cheat Engine detection

## [◆](class_player.md)GetIndex()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Player::GetIndex | ( |  | ) |  |

Get player index

## [◆](class_player.md)GetVersion()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Player::GetVersion | ( |  | ) |  |

Get version

## [◆](class_player.md)IsInvisible()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::IsInvisible | ( |  | ) |  |

Is invisible for everybody

## [◆](class_player.md)IsInvisibleForPlayer()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool Player::IsInvisibleForPlayer | ( | [Player](class_player.md) | *player* | ) |  |

Is invisible for one player

## [◆](class_player.md)SetInvisible()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetInvisible | ( | bool | *inv* | ) |  |

Set invisible for everybody

## [◆](class_player.md)SetLocalInvisible()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetLocalInvisible | ( | [Player](class_player.md) | *player*, |
|  |  | bool | *inv* ) |

Set invisible for one player

## [◆](class_player.md)Kick()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::Kick | ( | int | *code* = 0, |
|  |  | string &in | *custom* = "" ) |

Kick player with specified code. Custom text will work with CUSTOMERROR code

## [◆](class_player.md)ShowDialog() [1/2]

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::ShowDialog | ( | int | *type*, |
|  |  | int | *index*, |
|  |  | string &in | *header*, |
|  |  | string &in | *message*, |
|  |  | string &in | *leftbutton*, |
|  |  | string &in | *rightbutton* = "", |
|  |  | bool | *align* = true ) |

Shows multifunctional menu. Calls PlayerDialogAction on response.

## [◆](class_player.md)ShowDialog() [2/2]

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::ShowDialog | ( | int | *type*, |
|  |  | DIALOGCALLBACK@ | *callback*, |
|  |  | string &in | *header*, |
|  |  | string &in | *message*, |
|  |  | string &in | *leftbutton*, |
|  |  | string &in | *rightbutton* = "", |
|  |  | bool | *align* = true ) |

Shows multifunctional menu. Calls callback function on response.

## [◆](class_player.md)SetDialogData()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetDialogData | ( | string &in | *data* | ) |  |

Set dialog data for script messaging.

## [◆](class_player.md)GetDialogData()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Player::GetDialogData | ( |  | ) |  |

Get dialog data

## [◆](class_player.md)HideDialog()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Player::HideDialog | ( |  | ) |  |

Hide current dialog

## [◆](class_player.md)SendMessage()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SendMessage | ( | string &in | *message*, |
|  |  | float | *time* = 6.0, |
|  |  | bool | *localized* = false ) |

Send middle screen message.

## [◆](class_player.md)Desync()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::Desync | ( | bool | *value* | ) |  |

If enabled, PlayerUpdate will not be called and no new player data will be accepted. Useful for freezing a player's actions

## [◆](class_player.md)IsDesync()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::IsDesync | ( |  | ) |  |

Desynced?

## [◆](class_player.md)SetSpectatePlayer()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetSpectatePlayer | ( | [Player](class_player.md) | *target* | ) |  |

Get current spectate player. This function works even if the player is alive. If you set NULL, then player won't see any players.

## [◆](class_player.md)SetSpectateMode()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetSpectateMode | ( | int | *mode* | ) |  |

Get current spectate mode. This function works even if the player is alive. 0 - TPV, 1 - FPV, 2 - free. If you set wrong mode, then player will just freeze at spectation

## [◆](class_player.md)GetSpectatePlayer()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Player](class_player.md) Player::GetSpectatePlayer | ( |  | ) |  |

Get current spectate player. This function works even if the player is alive.

## [◆](class_player.md)GetSpectateMode()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Player::GetSpectateMode | ( |  | ) |  |

Get current spectate mode. This function works even if the player is alive. 0 - TPV, 1 - FPV, 2 - free

## [◆](class_player.md)Kill()

|  |  |  |  |
| --- | --- | --- | --- |
| bool Player::Kill | ( | bool | *bloody* = false, |
|  |  | bool | *createcorpse* = true ) |

Kill player. If successfully, returns true

## [◆](class_player.md)Respawn()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::Respawn | ( |  | ) |  |

Respawn player. If successfully, returns true. Calls PlayerRespawn\_c callback

## [◆](class_player.md)IsDead()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::IsDead | ( |  | ) |  |

Is dead

## [◆](class_player.md)SetInjuries()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetInjuries | ( | float | *val* | ) |  |

Set injuries

## [◆](class_player.md)GetInjuries()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Player::GetInjuries | ( |  | ) |  |

Get injuries

## [◆](class_player.md)SetBloodloss()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetBloodloss | ( | float | *val* | ) |  |

Set bloodloss

## [◆](class_player.md)GetBloodloss()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Player::GetBloodloss | ( |  | ) |  |

Get bloodloss

## [◆](class_player.md)GetGodmode()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::GetGodmode | ( |  | ) |  |

Get godmode

## [◆](class_player.md)SetGodmode()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetGodmode | ( | bool | *val* | ) |  |

Set godmode

## [◆](class_player.md)SetColor()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetColor | ( | uint | *hx* | ) |  |

Set color in players list in HEX Value (0xFFFFFFFF - full white). It's not recommend to use this function often

## [◆](class_player.md)GetColor()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| uint Player::GetColor | ( |  | ) |  |

Get color in players list

## [◆](class_player.md)GetNetworkPosition()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::GetNetworkPosition | ( | float &out | *x*, |
|  |  | float &out | *y*, |
|  |  | float &out | *z* ) |

Get network data after latest PlayerUpdate

## [◆](class_player.md)GetNetworkRotation()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::GetNetworkRotation | ( | float &out | *pitch*, |
|  |  | float &out | *yaw* ) |

Get network data after latest PlayerUpdate

## [◆](class_player.md)SetNetworkPosition()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetNetworkPosition | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Set network data after latest PlayerUpdate

## [◆](class_player.md)SetNetworkRotation()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetNetworkRotation | ( | float | *pitch*, |
|  |  | float | *yaw* ) |

Set network data after latest PlayerUpdate

## [◆](class_player.md)SetPosition()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetPosition | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | [Room](class_room.md) | *room* = NULL, |
|  |  | bool | *updatepivot* = true ) |

Set position and send sync back to player. Set player room.

## [◆](class_player.md)SetRotation()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetRotation | ( | float | *pitch*, |
|  |  | float | *yaw* ) |

Set rotation and send sync back to player

## [◆](class_player.md)Teleport()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::Teleport | ( | [Room](class_room.md) | *room*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | bool | *updatepivot* = true ) |

Helper of 'SetPosition' which teleports the player to the local coordinates of the room from the 'debughud' room position. If room = NULL, then teleport won't work.

## [◆](class_player.md)SetRoom()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetRoom | ( | [Room](class_room.md) | *room* | ) |  |

Set player room. Useful for bots.

## [◆](class_player.md)GetRoom()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Room](class_room.md) Player::GetRoom | ( |  | ) |  |

Get player room

## [◆](class_player.md)SetPositionBounds()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetPositionBounds | ( | [Room](class_room.md) | *room*, |
|  |  | float | *x* = 0.0, |
|  |  | float | *y* = 0.0, |
|  |  | float | *z* = 0.0, |
|  |  | float | *distance* = 0.0 ) |

Set player position limiter. The player will not be able to go beyond this limit in any way. If room is NULL then limiter is disabled

## [◆](class_player.md)Explode()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::Explode | ( | bool | *thrust* = false | ) |  |

Send explosion timer to player. If thrust is true then only camera shaking and sound will be sent.

## [◆](class_player.md)MovePlayer()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::MovePlayer | ( | float | *speedmult*, |
|  |  | float | *angle* ) |

Forcibly moves the player on his side. If the player does not respond, there will be no movement.

## [◆](class_player.md)IgnoreProximity()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::IgnoreProximity | ( | bool | *value* | ) |  |

If this is enabled, all players will be visible to the player from every room (player\_culling). This function was created specially for SCP-096

## [◆](class_player.md)SendDamage()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SendDamage | ( | [Player](class_player.md) | *player*, |
|  |  | float | *force*, |
|  |  | bool | *headshot*, |
|  |  | float | *offsetx*, |
|  |  | float | *offsety*, |
|  |  | float | *offsetz* ) |

Send damage to player. Offset is blood particle position offset

## [◆](class_player.md)SetAdmin()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetAdmin | ( | bool | *val* | ) |  |

Set admin access

## [◆](class_player.md)IsAdmin()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::IsAdmin | ( |  | ) |  |

Is admin?

## [◆](class_player.md)SetGlobalTransmission()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetGlobalTransmission | ( | bool | *val* | ) |  |

Set global transmission for voice. Use for example for intercom

## [◆](class_player.md)IsGlobalTransmission()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::IsGlobalTransmission | ( |  | ) |  |

Is global transmission enabled

## [◆](class_player.md)SendVoice()

|  |  |  |  |
| --- | --- | --- | --- |
| bool Player::SendVoice | ( | int | *bank*, |
|  |  | int | *radio* = 0, |
|  |  | bool | *global* = false, |
|  |  | [Player](class_player.md) | *target* = NULL ) |

Send voice data from player. Radio can be sent too. Global is local sound. If target != NULL then voice data will send only to target player

## [◆](class_player.md)GetItemsCount()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Player::GetItemsCount | ( |  | ) |  |

Get items count in inventory

## [◆](class_player.md)GetInventory()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Items](class_items.md) Player::GetInventory | ( | int |  | ) |  |

Get item from inventory slot

## [◆](class_player.md)GetSelectedItem()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Items](class_items.md) Player::GetSelectedItem | ( |  | ) |  |

Get current selected item

## [◆](class_player.md)GetBlinkTimer()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Player::GetBlinkTimer | ( |  | ) |  |

Get blink timer.

## [◆](class_player.md)SetBlinkTimer()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetBlinkTimer | ( | float | *time* | ) |  |

Set blink timer. Better to use SetBlinkEffect instead of this.

## [◆](class_player.md)IsBlinking()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::IsBlinking | ( |  | ) |  |

Is player blinking

## [◆](class_player.md)SetBlinkEffect()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetBlinkEffect | ( | float | *effectvalue*, |
|  |  | float | *time* ) |

Set blink effect.

## [◆](class_player.md)GetBlinkEffect()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::GetBlinkEffect | ( | float &out | *effectvalue*, |
|  |  | float &out | *time* ) |

Get blink effect

## [◆](class_player.md)EnableBlinking()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::EnableBlinking | ( | bool | *blink* | ) |  |

Enable blinking (noblink effect)

## [◆](class_player.md)IsBlinkingEnabled()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::IsBlinkingEnabled | ( |  | ) |  |

Is blinking enabled (noblink effect)

## [◆](class_player.md)GetRadio()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Player::GetRadio | ( |  | ) |  |

Get player current using radio.

## [◆](class_player.md)PlayAnimation()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::PlayAnimation | ( | int | *animid* | ) |  |

Play animation. If animation isn't blended, then animation won't play.

## [◆](class_player.md)SetNetworkAnimation()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetNetworkAnimation | ( | int | *animid* | ) |  |

Set network animation

## [◆](class_player.md)SetAnimation()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetAnimation | ( | int | *animid* | ) |  |

Set animation constantly after PlayerUpdate.

## [◆](class_player.md)GetAnimation()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Player::GetAnimation | ( |  | ) |  |

Get current animation

## [◆](class_player.md)SetSpeedMultiplier()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetSpeedMultiplier | ( | float | *multiplier* | ) |  |

Set speed multiplier. (limits is -3276.7 - 3276.7)

## [◆](class_player.md)SetStaminaMultiplier()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetStaminaMultiplier | ( | float | *multiplier* | ) |  |

Set stamina multiplier. The more the faster the stamina is spent. (limits is -3276.7 - 3276.7)

## [◆](class_player.md)GetSpeedMultiplier()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Player::GetSpeedMultiplier | ( |  | ) |  |

Get speed multiplier

## [◆](class_player.md)GetStaminaMultiplier()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Player::GetStaminaMultiplier | ( |  | ) |  |

Get stamina multiplier

## [◆](class_player.md)SetAttach()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetAttach | ( | int | *bodyindex*, |
|  |  | int | *attachmodelindex*, |
|  |  | [Items](class_items.md) | *item* = NULL ) |

Sets the exist attach

## [◆](class_player.md)GetAttach()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| int Player::GetAttach | ( | int | *bodyindex* | ) |  |

Get attach model from body index. Ranges from 0 to 9. Range from 0 to 5 reserved by server, but you still can use them in PlayerAttachesUpdate\_c

## [◆](class_player.md)GetAttachItem()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Items](class_items.md) Player::GetAttachItem | ( | int | *bodyindex* | ) |  |

Get attach item from body index. Ranges from 0 to 9. Range from 0 to 5 reserved by server, but you still can use them in PlayerAttachesUpdate\_c

## [◆](class_player.md)GetModel()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Player::GetModel | ( |  | ) |  |

Get model

## [◆](class_player.md)SetModel()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetModel | ( | int | *modelid*, |
|  |  | int | *textureid* = -1 ) |

Set model and texture id. It is not recommended to use this command too often.

## [◆](class_player.md)SetModelSize()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetModelSize | ( | float |  | ) |  |

Set model size. It is not recommended to use this command too often.

## [◆](class_player.md)GetModelSize()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Player::GetModelSize | ( |  | ) |  |

Get model size

## [◆](class_player.md)SetModelTexture()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetModelTexture | ( | int | *textureid* | ) |  |

Set model texture. It is not recommended to use this command too often.

## [◆](class_player.md)GetModelTexture()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Player::GetModelTexture | ( |  | ) |  |

Get model texture

## [◆](class_player.md)SetCollisionRadius()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetCollisionRadius | ( | float |  | ) |  |

Set player collision radius. If player model was changed, then collision radius will be reseted to model's radius. It is not recommended to use this command too often.

## [◆](class_player.md)GetCollisionRadius()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Player::GetCollisionRadius | ( |  | ) |  |

Get player collision radius.

## [◆](class_player.md)GetVolume()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Player::GetVolume | ( |  | ) |  |

Get current player volume (Voice, steps, shoots, etc...)

## [◆](class_player.md)IsCrouch()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::IsCrouch | ( |  | ) |  |

Is player crouch?

## [◆](class_player.md)SetGravity()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetGravity | ( | float | *multiplier* | ) |  |

Set gravity multiplier for player. Global gravity will be ignored. If multiplier = 0.0, then global gravity will be used

## [◆](class_player.md)GetGravity()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Player::GetGravity | ( |  | ) |  |

Get player gravity multiplier. If not set, return 0.0

## [◆](class_player.md)SetTagText()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetTagText | ( | int | *index*, |
|  |  | string & | *in* ) |

Set tag text. The index from 0 to 2 is reserved for nickname, voice, tag.

## [◆](class_player.md)SetTagScales()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetTagScales | ( | int | *index*, |
|  |  | float | , |
|  |  | float | ) |

Set tag scales

## [◆](class_player.md)SetTagOffset()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetTagOffset | ( | int | *index*, |
|  |  | float | ) |

Set tag offset

## [◆](class_player.md)SetTagColors()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetTagColors | ( | int | *index*, |
|  |  | int | , |
|  |  | int | ) |

Set tag colors

## [◆](class_player.md)SetTagFont()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetTagFont | ( | int | *index*, |
|  |  | string & | *in* ) |

Set tag font

## [◆](class_player.md)GetTagText()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| string & Player::GetTagText | ( | int | *index* | ) |  |

Get tag text. The index from 0 to 2 is reserved for nickname, voice, tag.

## [◆](class_player.md)GetTagScales()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::GetTagScales | ( | int | *index*, |
|  |  | float &out | *scalex*, |
|  |  | float &out | *scaley* ) |

Get tag scales

## [◆](class_player.md)GetTagOffset()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Player::GetTagOffset | ( | int | *index* | ) |  |

Get tag offset

## [◆](class_player.md)GetTagColors()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::GetTagColors | ( | int | *index*, |
|  |  | uint &out | *start*, |
|  |  | uint &out | *end* ) |

Get tag colors

## [◆](class_player.md)GetTagFont()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| string & Player::GetTagFont | ( | int | *index* | ) |  |

Get tag font

## [◆](class_player.md)GetShootsCount()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Player::GetShootsCount | ( |  | ) |  |

Get shoots count.

## [◆](class_player.md)SetShootsCount()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::SetShootsCount | ( | int | *count* | ) |  |

Set shoots count. The player will shoot until this value is reached.

## [◆](class_player.md)RedirectMove()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::RedirectMove | ( | bool | *move* | ) |  |

If enabled, the player is controlled by his entity, not network data. Useful for bots.

## [◆](class_player.md)IsBot()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::IsBot | ( |  | ) |  |

Bot?

## [◆](class_player.md)IsAiming()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Player::IsAiming | ( |  | ) |  |

Is aiming in weapon.

## [◆](class_player.md)SetWearData()

|  |  |  |  |
| --- | --- | --- | --- |
| void Player::SetWearData | ( | int | *bodyindex*, |
|  |  | [Items](class_items.md) | *item* ) |

Sets the item for attaches. This thing only useful for bots, as they cannot update data.

## [◆](class_player.md)Console()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Player::Console | ( | string &in | *message* | ) |  |

Sends console message to player

## [◆](class_player.md)GetKeyState()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool Player::GetKeyState | ( | int | *keytype* | ) |  |

Is key pressed

- [Player](class_player.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
