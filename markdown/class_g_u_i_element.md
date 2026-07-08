<!-- source: http://scpcbmr.42web.io/class_g_u_i_element.html -->
# SCP: Containment Breach 2 Scripting: GUIElement Class Reference

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

[Public Member Functions](class_g_u_i_element.md) |
[List of all members](class_g_u_i_element-members.md)

GUIElement Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| void | [GetPosition](class_g_u_i_element.md) (float &out x, float &out y) |
|  | |
| void | [SetPosition](class_g_u_i_element.md) (float x, float y) |
|  | |
| void | [SetScale](class_g_u_i_element.md) (float width, float height) |
|  | |
| void | [GetScale](class_g_u_i_element.md) (float &out width, float &out height) |
|  | |
| void | [SetRotation](class_g_u_i_element.md) (int degrees) |
|  | |
| void | [GetRotation](class_g_u_i_element.md) (int &out degrees) |
|  | |
| void | [SetData](class_g_u_i_element.md) (string &in data) |
|  | |
| void | [SetText](class_g_u_i_element.md) (string &in text) |
|  | |
| void | [SetSelectable](class_g_u_i_element.md) (bool selectable) |
|  | |
| void | [SetShadow](class_g_u_i_element.md) (bool shadowed) |
|  | |
| void | [SetAspect](class_g_u_i_element.md) (bool keep) |
|  | |
| void | [SetOpacity](class_g_u_i_element.md) (float target, float lerp) |
|  | |
| void | [SetColor](class_g_u_i_element.md) (int r, int g, int b) |
|  | |
| void | [SetTechnique](class_g_u_i_element.md) (string &in technique) |
|  | |
| [Player](class_player.md) | [GetPlayer](class_g_u_i_element.md) () |
|  | |
| void | [SetAttach](class_g_u_i_element.md) ([Player](class_player.md) player) |
|  | |
| void | [SetAttach](class_g_u_i_element.md) (bool enable, float x=0.0, float y=0.0, float z=0.0) |
|  | |
| [Player](class_player.md) | [GetAttach](class_g_u_i_element.md) () |
|  | |
| bool | [GetAttach](class_g_u_i_element.md) (float &out x, float &out y, float &out z) |
|  | |
| string & | [GetText](class_g_u_i_element.md) () |
|  | |
| string & | [GetData](class_g_u_i_element.md) () |
|  | |
| bool | [IsSelectable](class_g_u_i_element.md) () |
|  | |
| bool | [IsHidden](class_g_u_i_element.md) () |
|  | |
| void | [SetCallback](class_g_u_i_element.md) (string &in funcname) |
|  | |
| void | [SetCallback](class_g_u_i_element.md) (GUICALLBACK @gc) |
|  | |
| void | [Hide](class_g_u_i_element.md) () |
|  | |
| void | [Show](class_g_u_i_element.md) () |
|  | |
| void | [Remove](class_g_u_i_element.md) () |
|  | |

## Member Function Documentation

## [◆](class_g_u_i_element.md)GetPosition()

|  |  |  |  |
| --- | --- | --- | --- |
| void GUIElement::GetPosition | ( | float &out | *x*, |
|  |  | float &out | *y* ) |

Get element position

## [◆](class_g_u_i_element.md)SetPosition()

|  |  |  |  |
| --- | --- | --- | --- |
| void GUIElement::SetPosition | ( | float | *x*, |
|  |  | float | *y* ) |

Set element position

## [◆](class_g_u_i_element.md)SetScale()

|  |  |  |  |
| --- | --- | --- | --- |
| void GUIElement::SetScale | ( | float | *width*, |
|  |  | float | *height* ) |

Set element scale

## [◆](class_g_u_i_element.md)GetScale()

|  |  |  |  |
| --- | --- | --- | --- |
| void GUIElement::GetScale | ( | float &out | *width*, |
|  |  | float &out | *height* ) |

Get element scale

## [◆](class_g_u_i_element.md)SetRotation()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::SetRotation | ( | int | *degrees* | ) |  |

Set element rotation (Only for static image)

## [◆](class_g_u_i_element.md)GetRotation()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::GetRotation | ( | int &out | *degrees* | ) |  |

Get element rotation

## [◆](class_g_u_i_element.md)SetData()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::SetData | ( | string &in | *data* | ) |  |

Set element data for scripting messaging

## [◆](class_g_u_i_element.md)SetText()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::SetText | ( | string &in | *text* | ) |  |

Set element text

## [◆](class_g_u_i_element.md)SetSelectable()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::SetSelectable | ( | bool | *selectable* | ) |  |

Set element selectability. If at least one element is visible and selectable, then the player get a mouse cursor.

## [◆](class_g_u_i_element.md)SetShadow()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::SetShadow | ( | bool | *shadowed* | ) |  |

Set element shadow. Only for Text

## [◆](class_g_u_i_element.md)SetAspect()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::SetAspect | ( | bool | *keep* | ) |  |

Keep aspect ratio. For example, the scales of 0.1 0.1 will be square instead of stretching across the screen width.

## [◆](class_g_u_i_element.md)SetOpacity()

|  |  |  |  |
| --- | --- | --- | --- |
| void GUIElement::SetOpacity | ( | float | *target*, |
|  |  | float | *lerp* ) |

Set element opacity

## [◆](class_g_u_i_element.md)SetColor()

|  |  |  |  |
| --- | --- | --- | --- |
| void GUIElement::SetColor | ( | int | *r*, |
|  |  | int | *g*, |
|  |  | int | *b* ) |

Set element color. If you want opacity, use SetOpacity

## [◆](class_g_u_i_element.md)SetTechnique()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::SetTechnique | ( | string &in | *technique* | ) |  |

Set element technique. Only for PostEffect

## [◆](class_g_u_i_element.md)GetPlayer()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Player](class_player.md) GUIElement::GetPlayer | ( |  | ) |  |

Get GUI owner

## [◆](class_g_u_i_element.md)SetAttach() [1/2]

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::SetAttach | ( | [Player](class_player.md) | *player* | ) |  |

Attach GUI to player.

## [◆](class_g_u_i_element.md)SetAttach() [2/2]

|  |  |  |  |
| --- | --- | --- | --- |
| void GUIElement::SetAttach | ( | bool | *enable*, |
|  |  | float | *x* = 0.0, |
|  |  | float | *y* = 0.0, |
|  |  | float | *z* = 0.0 ) |

Attach GUI to 'position'. Set to false if you wan't to null position attach. If you attach an attachment to both the position and the player, then the priority will be on the player.

## [◆](class_g_u_i_element.md)GetAttach() [1/2]

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Player](class_player.md) GUIElement::GetAttach | ( |  | ) |  |

Get attached player to GUI

## [◆](class_g_u_i_element.md)GetAttach() [2/2]

|  |  |  |  |
| --- | --- | --- | --- |
| bool GUIElement::GetAttach | ( | float &out | *x*, |
|  |  | float &out | *y*, |
|  |  | float &out | *z* ) |

Get attached position to GUI. If position wasn't attached (latest SetAttach with entity was NULL), then it's return false, otherwise return true

## [◆](class_g_u_i_element.md)GetText()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & GUIElement::GetText | ( |  | ) |  |

Get text

## [◆](class_g_u_i_element.md)GetData()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & GUIElement::GetData | ( |  | ) |  |

Get data

## [◆](class_g_u_i_element.md)IsSelectable()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool GUIElement::IsSelectable | ( |  | ) |  |

Is selectable

## [◆](class_g_u_i_element.md)IsHidden()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool GUIElement::IsHidden | ( |  | ) |  |

Is hidden

## [◆](class_g_u_i_element.md)SetCallback() [1/2]

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::SetCallback | ( | string &in | *funcname* | ) |  |

Set AS function callback for selectable elements. if not specified, PlayerClickGui\_c is call. Declaration must be: void MyCallback(Player p, GUIElement gui)

## [◆](class_g_u_i_element.md)SetCallback() [2/2]

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void GUIElement::SetCallback | ( | GUICALLBACK @ | *gc* | ) |  |

Set AS function callback for selectable elements. if not specified, PlayerClickGui\_c is call. Declaration must be: void MyCallback(Player p, GUIElement gui)

## [◆](class_g_u_i_element.md)Hide()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void GUIElement::Hide | ( |  | ) |  |

Hide GUI element

## [◆](class_g_u_i_element.md)Show()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void GUIElement::Show | ( |  | ) |  |

Show GUI element

## [◆](class_g_u_i_element.md)Remove()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void GUIElement::Remove | ( |  | ) |  |

Remove GUI element

- [GUIElement](class_g_u_i_element.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
