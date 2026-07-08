<!-- source: http://scpcbmr.42web.io/group___globals.html -->
# SCP: Containment Breach 2 Scripting: Globals

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

[Functions](group___globals.md)

Globals

|  |  |
| --- | --- |
| Functions | |
| [Entity](class_entity.md) | [CreatePivot](group___globals.md) (int parent=0) |
|  | |
| [Entity](class_entity.md) | [LinePick](group___globals.md) (float x, float y, float z, float dx, float dy, float dz, float radius=0.0) |
|  | |
| [Player](class_player.md) | [GetPlayer](group___globals.md) (int index) |
|  | |
| float | [PeekFloat](group___globals.md) (int bank, int offset) |
|  | |
| float | [PickedNX](group___globals.md) () |
|  | |
| float | [PickedNY](group___globals.md) () |
|  | |
| float | [PickedNZ](group___globals.md) () |
|  | |
| float | [PickedX](group___globals.md) () |
|  | |
| float | [PickedY](group___globals.md) () |
|  | |
| float | [PickedZ](group___globals.md) () |
|  | |
| float | [TFormedX](group___globals.md) () |
|  | |
| float | [TFormedY](group___globals.md) () |
|  | |
| float | [TFormedZ](group___globals.md) () |
|  | |
| float | **clamp** (float val, float minimal, float maximum) |
|  | |
| float | [frand](group___globals.md) (float from, float to=0.0) |
|  | |
| float | **max** (float val, float val2) |
|  | |
| float | **min** (float val, float val2) |
|  | |
| int | [BankSize](group___globals.md) (int bank) |
|  | |
| int | [BankStringSize](group___globals.md) (string &in) |
|  | |
| int | [CreateBank](group___globals.md) (int size) |
|  | |
| int | [CreateTimer](group___globals.md) (ref &in callback, int time, bool repeat, int timerdata=0) |
|  | |
| int | [CreateTimer](group___globals.md) (string &in funcdecl, int time, bool repeat, int timerdata=0) |
|  | |
| int | [CreateTimerData](group___globals.md) () |
|  | |
| int | [CreateTimerEx](group___globals.md) (ref &in callback, int time, bool repeat, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null) |
|  | |
| int | [CreateTimerEx](group___globals.md) (string &in funcdecl, int time, bool repeat, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null) |
|  | |
| int | [GetActiveContext](group___globals.md) () |
|  | |
| int | [GetPlayersCount](group___globals.md) () |
|  | |
| int | [GetProcAddress](group___globals.md) (int, string &in) |
|  | |
| int | [LoadLibrary](group___globals.md) (string &in) |
|  | |
| int | [PeekInt](group___globals.md) (int bank, int offset) |
|  | |
| int | [rand](group___globals.md) (int from, int to=0) |
|  | |
| int | [rndseed](group___globals.md) () |
|  | |
| int | **round** (bool val) |
|  | |
| int | **round** (float val) |
|  | |
| int | [srand](group___globals.md) (int val) |
|  | |
| int16 | [PeekShort](group___globals.md) (int bank, int offset) |
|  | |
| int8 | [PeekByte](group___globals.md) (int bank, int offset) |
|  | |
| string & | [PeekString](group___globals.md) (int bank, int offset) |
|  | |
| string & | [StripFormatting](group___globals.md) (string &in txt) |
|  | |
| void | [Collisions](group___globals.md) (int src\_type, int dest\_type, int method, int response) |
|  | |
| void | [FreeBank](group___globals.md) (int bank) |
|  | |
| void | [PokeByte](group___globals.md) (int bank, int offset, int value) |
|  | |
| void | [PokeFloat](group___globals.md) (int bank, int offset, float value) |
|  | |
| void | [PokeInt](group___globals.md) (int bank, int offset, int value) |
|  | |
| void | [PokeShort](group___globals.md) (int bank, int offset, int value) |
|  | |
| void | [PokeString](group___globals.md) (int bank, int offset, string &in value) |
|  | |
| void | [RegisterFuncdef](group___globals.md) (string &in declaration) |
|  | |
| void | [RegisterLibraryFunction](group___globals.md) (string &in decl, int procaddress, int convtype) |
|  | |
| void | [RegisterLibraryMethod](group___globals.md) (string &in classname, string &in decl, int procaddress, int convtype) |
|  | |
| void | [RegisterLibraryObject](group___globals.md) (string &in classname) |
|  | |
| void | [RemoveTimer](group___globals.md) () |
|  | |
| void | [RemoveTimer](group___globals.md) (int timer) |
|  | |
| void | [RemoveTimer](group___globals.md) (ref &in callback) |
|  | |
| void | [SetTimerBool](group___globals.md) (int timerdata, bool val) |
|  | |
| void | [SetTimerFloat](group___globals.md) (int timerdata, float val) |
|  | |
| void | [SetTimerHandle](group___globals.md) (int timerdata, int handle) |
|  | |
| void | [SetTimerInt](group___globals.md) (int timerdata, int val) |
|  | |
| void | [SetTimerString](group___globals.md) (int timerdata, string &in val) |
|  | |
| void | [TFormNormal](group___globals.md) (float x, float y, float z, [Entity](class_entity.md) src, [Entity](class_entity.md) dest) |
|  | |
| void | [TFormPoint](group___globals.md) (float x, float y, float z, [Entity](class_entity.md) src, [Entity](class_entity.md) dest) |
|  | |
| void | [TFormVector](group___globals.md) (float x, float y, float z, [Entity](class_entity.md) src, [Entity](class_entity.md) dest) |
|  | |
| void | [print](group___globals.md) (string &in message) |
|  | |
| void | [sleep](group___globals.md) (int milliseconds) |
|  | |

## Detailed Description

Global functions

## Function Documentation

## [◆](group___globals.md)CreatePivot()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Entity](class_entity.md) CreatePivot | ( | int | *parent* = 0 | ) |  |

Create pivot. Can create sphere collision

## [◆](group___globals.md)LinePick()

|  |  |  |  |
| --- | --- | --- | --- |
| [Entity](class_entity.md) LinePick | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | float | *dx*, |
|  |  | float | *dy*, |
|  |  | float | *dz*, |
|  |  | float | *radius* = 0.0 ) |

Pick entity in specified coordinates

## [◆](group___globals.md)GetPlayer()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Player](class_player.md) GetPlayer | ( | int | *index* | ) |  |

Get player by his index

## [◆](group___globals.md)PeekFloat()

|  |  |  |  |
| --- | --- | --- | --- |
| float PeekFloat | ( | int | *bank*, |
|  |  | int | *offset* ) |

Take float from buffer

## [◆](group___globals.md)PickedNX()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float PickedNX | ( |  | ) |  |

Get picked Normal X after pick function

## [◆](group___globals.md)PickedNY()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float PickedNY | ( |  | ) |  |

Get picked Normal Y after pick function

## [◆](group___globals.md)PickedNZ()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float PickedNZ | ( |  | ) |  |

Get picked Normal Z after pick function

## [◆](group___globals.md)PickedX()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float PickedX | ( |  | ) |  |

Get picked X after pick function

## [◆](group___globals.md)PickedY()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float PickedY | ( |  | ) |  |

Get picked Y after pick function

## [◆](group___globals.md)PickedZ()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float PickedZ | ( |  | ) |  |

Get picked Z after pick function

## [◆](group___globals.md)TFormedX()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float TFormedX | ( |  | ) |  |

Get TFormX

## [◆](group___globals.md)TFormedY()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float TFormedY | ( |  | ) |  |

Get TFormY

## [◆](group___globals.md)TFormedZ()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float TFormedZ | ( |  | ) |  |

Get TFormZ

## [◆](group___globals.md)frand()

|  |  |  |  |
| --- | --- | --- | --- |
| float frand | ( | float | *from*, |
|  |  | float | *to* = 0.0 ) |

Float random

## [◆](group___globals.md)BankSize()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| int BankSize | ( | int | *bank* | ) |  |

Get memory buffer size

## [◆](group___globals.md)BankStringSize()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| int BankStringSize | ( | string & | *in* | ) |  |

Get string size required for memory buffer

## [◆](group___globals.md)CreateBank()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| int CreateBank | ( | int | *size* | ) |  |

Create memory buffer

## [◆](group___globals.md)CreateTimer() [1/2]

|  |  |  |  |
| --- | --- | --- | --- |
| int CreateTimer | ( | ref &in | *callback*, |
|  |  | int | *time*, |
|  |  | bool | *repeat*, |
|  |  | int | *timerdata* = 0 ) |

Create timer. DEPRECATED! Use CreateTimerEx instead

## [◆](group___globals.md)CreateTimer() [2/2]

|  |  |  |  |
| --- | --- | --- | --- |
| int CreateTimer | ( | string &in | *funcdecl*, |
|  |  | int | *time*, |
|  |  | bool | *repeat*, |
|  |  | int | *timerdata* = 0 ) |

Create timer. DEPRECATED! Use CreateTimerEx instead

## [◆](group___globals.md)CreateTimerData()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int CreateTimerData | ( |  | ) |  |

Create timer arguments buffer. Will be deleted in CreateTimer function. DEPRECATED! Use CreateTimerEx instead

## [◆](group___globals.md)CreateTimerEx() [1/2]

|  |  |  |  |
| --- | --- | --- | --- |
| int CreateTimerEx | ( | ref &in | *callback*, |
|  |  | int | *time*, |
|  |  | bool | *repeat*, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null ) |

Create timer with variadic arguments. Supports 8 arguments.

## [◆](group___globals.md)CreateTimerEx() [2/2]

|  |  |  |  |
| --- | --- | --- | --- |
| int CreateTimerEx | ( | string &in | *funcdecl*, |
|  |  | int | *time*, |
|  |  | bool | *repeat*, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null, |
|  |  | ?& | *in* = null ) |

Create timer with variadic arguments. Supports 8 arguments.

## [◆](group___globals.md)GetActiveContext()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int GetActiveContext | ( |  | ) |  |

Get pointer of active context of AngelScript. Need for plugins

## [◆](group___globals.md)GetPlayersCount()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int GetPlayersCount | ( |  | ) |  |

Get players count

## [◆](group___globals.md)GetProcAddress()

|  |  |  |  |
| --- | --- | --- | --- |
| int GetProcAddress | ( | int | , |
|  |  | string & | *in* ) |

Get proc address of function from DLL

## [◆](group___globals.md)LoadLibrary()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| int LoadLibrary | ( | string & | *in* | ) |  |

Load DLL

## [◆](group___globals.md)PeekInt()

|  |  |  |  |
| --- | --- | --- | --- |
| int PeekInt | ( | int | *bank*, |
|  |  | int | *offset* ) |

Take int from buffer

## [◆](group___globals.md)rand()

|  |  |  |  |
| --- | --- | --- | --- |
| int rand | ( | int | *from*, |
|  |  | int | *to* = 0 ) |

Random

## [◆](group___globals.md)rndseed()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int rndseed | ( |  | ) |  |

Get random seed

## [◆](group___globals.md)srand()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| int srand | ( | int | *val* | ) |  |

Seed random

## [◆](group___globals.md)PeekShort()

|  |  |  |  |
| --- | --- | --- | --- |
| int16 PeekShort | ( | int | *bank*, |
|  |  | int | *offset* ) |

Take short from buffer

## [◆](group___globals.md)PeekByte()

|  |  |  |  |
| --- | --- | --- | --- |
| int8 PeekByte | ( | int | *bank*, |
|  |  | int | *offset* ) |

Take byte from buffer

## [◆](group___globals.md)PeekString()

|  |  |  |  |
| --- | --- | --- | --- |
| string & PeekString | ( | int | *bank*, |
|  |  | int | *offset* ) |

Take string from buffer

## [◆](group___globals.md)StripFormatting()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| string & StripFormatting | ( | string &in | *txt* | ) |  |

Get plain text without formatting

## [◆](group___globals.md)Collisions()

|  |  |  |  |
| --- | --- | --- | --- |
| void Collisions | ( | int | *src\_type*, |
|  |  | int | *dest\_type*, |
|  |  | int | *method*, |
|  |  | int | *response* ) |

Set collision methods

## [◆](group___globals.md)FreeBank()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void FreeBank | ( | int | *bank* | ) |  |

Delete memory buffer

## [◆](group___globals.md)PokeByte()

|  |  |  |  |
| --- | --- | --- | --- |
| void PokeByte | ( | int | *bank*, |
|  |  | int | *offset*, |
|  |  | int | *value* ) |

Set byte in buffer

## [◆](group___globals.md)PokeFloat()

|  |  |  |  |
| --- | --- | --- | --- |
| void PokeFloat | ( | int | *bank*, |
|  |  | int | *offset*, |
|  |  | float | *value* ) |

Set float in buffer

## [◆](group___globals.md)PokeInt()

|  |  |  |  |
| --- | --- | --- | --- |
| void PokeInt | ( | int | *bank*, |
|  |  | int | *offset*, |
|  |  | int | *value* ) |

Set int in buffer

## [◆](group___globals.md)PokeShort()

|  |  |  |  |
| --- | --- | --- | --- |
| void PokeShort | ( | int | *bank*, |
|  |  | int | *offset*, |
|  |  | int | *value* ) |

Set short in buffer

## [◆](group___globals.md)PokeString()

|  |  |  |  |
| --- | --- | --- | --- |
| void PokeString | ( | int | *bank*, |
|  |  | int | *offset*, |
|  |  | string &in | *value* ) |

Set string in buffer

## [◆](group___globals.md)RegisterFuncdef()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void RegisterFuncdef | ( | string &in | *declaration* | ) |  |

Register new funcdef for callbacks. This function does not create new funcdefs during runtime. Required for plugins

## [◆](group___globals.md)RegisterLibraryFunction()

|  |  |  |  |
| --- | --- | --- | --- |
| void RegisterLibraryFunction | ( | string &in | *decl*, |
|  |  | int | *procaddress*, |
|  |  | int | *convtype* ) |

Register new function from DLL. This function does not create new functions during runtime. Required for plugins

## [◆](group___globals.md)RegisterLibraryMethod()

|  |  |  |  |
| --- | --- | --- | --- |
| void RegisterLibraryMethod | ( | string &in | *classname*, |
|  |  | string &in | *decl*, |
|  |  | int | *procaddress*, |
|  |  | int | *convtype* ) |

Register new class function from DLL. This function does not create new functions during runtime. Required for plugins

## [◆](group___globals.md)RegisterLibraryObject()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void RegisterLibraryObject | ( | string &in | *classname* | ) |  |

Register new class. Required for plugins. This function does not create new classes during runtime.

## [◆](group___globals.md)RemoveTimer() [1/3]

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void RemoveTimer | ( |  | ) |  |

Remove current executed timer

## [◆](group___globals.md)RemoveTimer() [2/3]

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void RemoveTimer | ( | int | *timer* | ) |  |

Remove timer by handle

## [◆](group___globals.md)RemoveTimer() [3/3]

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void RemoveTimer | ( | ref &in | *callback* | ) |  |

Remove all timers with this function

## [◆](group___globals.md)SetTimerBool()

|  |  |  |  |
| --- | --- | --- | --- |
| void SetTimerBool | ( | int | *timerdata*, |
|  |  | bool | *val* ) |

Add timer bool. DEPRECATED! Use CreateTimerEx instead

## [◆](group___globals.md)SetTimerFloat()

|  |  |  |  |
| --- | --- | --- | --- |
| void SetTimerFloat | ( | int | *timerdata*, |
|  |  | float | *val* ) |

Add timer float. DEPRECATED! Use CreateTimerEx instead

## [◆](group___globals.md)SetTimerHandle()

|  |  |  |  |
| --- | --- | --- | --- |
| void SetTimerHandle | ( | int | *timerdata*, |
|  |  | int | *handle* ) |

Add timer handle. DEPRECATED! Use CreateTimerEx instead

## [◆](group___globals.md)SetTimerInt()

|  |  |  |  |
| --- | --- | --- | --- |
| void SetTimerInt | ( | int | *timerdata*, |
|  |  | int | *val* ) |

Add timer int. DEPRECATED! Use CreateTimerEx instead

## [◆](group___globals.md)SetTimerString()

|  |  |  |  |
| --- | --- | --- | --- |
| void SetTimerString | ( | int | *timerdata*, |
|  |  | string &in | *val* ) |

Add timer string. DEPRECATED! Use CreateTimerEx instead

## [◆](group___globals.md)TFormNormal()

|  |  |  |  |
| --- | --- | --- | --- |
| void TFormNormal | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | [Entity](class_entity.md) | *src*, |
|  |  | [Entity](class_entity.md) | *dest* ) |

Transforms between coordinate systems.

## [◆](group___globals.md)TFormPoint()

|  |  |  |  |
| --- | --- | --- | --- |
| void TFormPoint | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | [Entity](class_entity.md) | *src*, |
|  |  | [Entity](class_entity.md) | *dest* ) |

Transforms between coordinate systems.

## [◆](group___globals.md)TFormVector()

|  |  |  |  |
| --- | --- | --- | --- |
| void TFormVector | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | [Entity](class_entity.md) | *src*, |
|  |  | [Entity](class_entity.md) | *dest* ) |

Transforms between coordinate systems.

## [◆](group___globals.md)print()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void print | ( | string &in | *message* | ) |  |

Print message to console and logger

## [◆](group___globals.md)sleep()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void sleep | ( | int | *milliseconds* | ) |  |

Sleep thread

- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
