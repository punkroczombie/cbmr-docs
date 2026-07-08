<!-- source: http://scpcbmr.42web.io/class_graphics.html -->
# SCP: Containment Breach 2 Scripting: Graphics Class Reference

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

[Public Member Functions](class_graphics.md) |
[List of all members](class_graphics-members.md)

Graphics Class Reference

`#include <all.h>`

|  |  |
| --- | --- |
| Public Member Functions | |
| [GUIElement](class_g_u_i_element.md) | [CreateOval](class_graphics.md) ([Player](class_player.md) player, float x, float y, float width, float height, bool align=false) |
|  | |
| [GUIElement](class_g_u_i_element.md) | [CreateRect](class_graphics.md) ([Player](class_player.md) player, float x, float y, float width, float height, bool align=false) |
|  | |
| [GUIElement](class_g_u_i_element.md) | [CreateProgressBar](class_graphics.md) ([Player](class_player.md) player, float time, float x, float y, float width, float height, bool align=false) |
|  | |
| [GUIElement](class_g_u_i_element.md) | [CreateProgressBar](class_graphics.md) ([Player](class_player.md) player, float time, float x, float y, float width, float height, bool align, string &in callback) |
|  | |
| [GUIElement](class_g_u_i_element.md) | [CreateProgressBar](class_graphics.md) ([Player](class_player.md) player, float time, float x, float y, float width, float height, bool align, ref &in callback) |
|  | |
| [GUIElement](class_g_u_i_element.md) | [CreateText](class_graphics.md) ([Player](class_player.md) player, int fontid, string &in text, float x, float y, bool align=false) |
|  | |
| [GUIElement](class_g_u_i_element.md) | [CreateImage](class_graphics.md) ([Player](class_player.md) player, string &in filename, float x, float y, float width, float height, bool align=false) |
|  | |
| [GUIElement](class_g_u_i_element.md) | [CreatePostEffect](class_graphics.md) ([Player](class_player.md) player, string &in filename, string &in defines="") |
|  | |

## Detailed Description

Global property is 'graphics'

## Member Function Documentation

## [◆](class_graphics.md)CreateOval()

|  |  |  |  |
| --- | --- | --- | --- |
| [GUIElement](class_g_u_i_element.md) Graphics::CreateOval | ( | [Player](class_player.md) | *player*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *width*, |
|  |  | float | *height*, |
|  |  | bool | *align* = false ) |

Creates a graphic element (Oval). If the player is NULL, the graphic element is created for all players. x, y, width, height are normalized to 1.0. You can use [Player::GetScreenSize](class_player.md) to display the element correctly.

## [◆](class_graphics.md)CreateRect()

|  |  |  |  |
| --- | --- | --- | --- |
| [GUIElement](class_g_u_i_element.md) Graphics::CreateRect | ( | [Player](class_player.md) | *player*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *width*, |
|  |  | float | *height*, |
|  |  | bool | *align* = false ) |

Creates a graphic element (Rect). If the player is NULL, the graphic element is created for all players. x, y, width, height are normalized to 1.0. You can use [Player::GetScreenSize](class_player.md) to display the element correctly.

## [◆](class_graphics.md)CreateProgressBar() [1/3]

|  |  |  |  |
| --- | --- | --- | --- |
| [GUIElement](class_g_u_i_element.md) Graphics::CreateProgressBar | ( | [Player](class_player.md) | *player*, |
|  |  | float | *time*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *width*, |
|  |  | float | *height*, |
|  |  | bool | *align* = false ) |

Creates a graphic element (Progress bar). If the player is NULL, the graphic element is created for all players. x, y, width, height are normalized to 1.0. You can use [Player::GetScreenSize](class_player.md) to display the element correctly.

## [◆](class_graphics.md)CreateProgressBar() [2/3]

|  |  |  |  |
| --- | --- | --- | --- |
| [GUIElement](class_g_u_i_element.md) Graphics::CreateProgressBar | ( | [Player](class_player.md) | *player*, |
|  |  | float | *time*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *width*, |
|  |  | float | *height*, |
|  |  | bool | *align*, |
|  |  | string &in | *callback* ) |

Creates a graphic element (Progress bar) with string callback function (time in seconds). The specified callback will be triggered when the progress bar reaches the end. If the player is NULL, the graphic element is created for all players. x, y, width, height are normalized to 1.0. You can use [Player::GetScreenSize](class_player.md) to display the element correctly.

## [◆](class_graphics.md)CreateProgressBar() [3/3]

|  |  |  |  |
| --- | --- | --- | --- |
| [GUIElement](class_g_u_i_element.md) Graphics::CreateProgressBar | ( | [Player](class_player.md) | *player*, |
|  |  | float | *time*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *width*, |
|  |  | float | *height*, |
|  |  | bool | *align*, |
|  |  | ref &in | *callback* ) |

Creates a graphic element (Progress bar) with callback function (time in seconds). The specified callback will be triggered when the progress bar reaches the end. If the player is NULL, the graphic element is created for all players. x, y, width, height are normalized to 1.0. You can use [Player::GetScreenSize](class_player.md) to display the element correctly.

## [◆](class_graphics.md)CreateText()

|  |  |  |  |
| --- | --- | --- | --- |
| [GUIElement](class_g_u_i_element.md) Graphics::CreateText | ( | [Player](class_player.md) | *player*, |
|  |  | int | *fontid*, |
|  |  | string &in | *text*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | bool | *align* = false ) |

Creates a graphic element (Text). If the player is NULL, the graphic element is created for all players. x, y are normalized to 1.0. You can use [Player::GetScreenSize](class_player.md) to display the element correctly.

## [◆](class_graphics.md)CreateImage()

|  |  |  |  |
| --- | --- | --- | --- |
| [GUIElement](class_g_u_i_element.md) Graphics::CreateImage | ( | [Player](class_player.md) | *player*, |
|  |  | string &in | *filename*, |
|  |  | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *width*, |
|  |  | float | *height*, |
|  |  | bool | *align* = false ) |

Creates a graphic element (Image). It is also possible to play videos, the webm format is supported. If the player is NULL, the graphic element is created for all players. x, y, width, height are normalized to 1.0. You can use [Player::GetScreenSize](class_player.md) to display the element correctly.

## [◆](class_graphics.md)CreatePostEffect()

|  |  |  |  |
| --- | --- | --- | --- |
| [GUIElement](class_g_u_i_element.md) Graphics::CreatePostEffect | ( | [Player](class_player.md) | *player*, |
|  |  | string &in | *filename*, |
|  |  | string &in | *defines* = "" ) |

Creates a post effect element. If the player is NULL, the graphic element is created for all players.

- [Graphics](class_graphics.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
