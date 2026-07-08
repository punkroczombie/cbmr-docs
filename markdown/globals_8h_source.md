<!-- source: http://scpcbmr.42web.io/globals_8h_source.html -->
# SCP: Containment Breach 2 Scripting: globals.h Source File

|  |  |  |
| --- | --- | --- |
| Logo | SCP: Containment Breach 2 Scripting |  |

![](sync_on.png "click to disable panel synchronization")

- [►](javascript:void(0))[SCP: Containment Breach 2 Scripting](index.md)

[•All](javascript:void(0))[Classes](javascript:void(0))[Functions](javascript:void(0))[Variables](javascript:void(0))[Modules](javascript:void(0))[Pages](javascript:void(0))

Loading...

Searching...

No Matches

globals.h

1;

7

[8](group___globals.md)[Entity](class_entity.md) [CreatePivot](group___globals.md)(int parent = 0) ;

[9](group___globals.md)[Entity](class_entity.md) [LinePick](group___globals.md)(float x, float y, float z, float dx, float dy, float dz, float radius = 0.0) ;

[10](group___globals.md)[Player](class_player.md) [GetPlayer](group___globals.md)(int index) ;

[11](group___globals.md)float [PeekFloat](group___globals.md)(int bank, int offset) ;

[12](group___globals.md)float [PickedNX](group___globals.md)() ;

[13](group___globals.md)float [PickedNY](group___globals.md)() ;

[14](group___globals.md)float [PickedNZ](group___globals.md)() ;

[15](group___globals.md)float [PickedX](group___globals.md)() ;

[16](group___globals.md)float [PickedY](group___globals.md)() ;

[17](group___globals.md)float [PickedZ](group___globals.md)() ;

[18](group___globals.md)float [TFormedX](group___globals.md)() ;

[19](group___globals.md)float [TFormedY](group___globals.md)() ;

[20](group___globals.md)float [TFormedZ](group___globals.md)() ;

21float clamp(float val, float minimal, float maximum) ;

[22](group___globals.md)float [frand](group___globals.md)(float from, float to = 0.0) ;

23float max(float val, float val2) ;

24float min(float val, float val2) ;

[25](group___globals.md)int [BankSize](group___globals.md)(int bank) ;

[26](group___globals.md)int [BankStringSize](group___globals.md)(string& in) ;

[27](group___globals.md)int [CreateBank](group___globals.md)(int size) ;

[28](group___globals.md)int [CreateTimer](group___globals.md)(ref& in callback, int time, bool repeat, int timerdata = 0) ;

[29](group___globals.md)int [CreateTimer](group___globals.md)(string& in funcdecl, int time, bool repeat, int timerdata = 0) ;

[30](group___globals.md)int [CreateTimerData](group___globals.md)() ;

[31](group___globals.md)int [CreateTimerEx](group___globals.md)(ref& in callback, int time, bool repeat, ?&in = null, ?&in = null, ?&in = null, ?&in = null, ?&in = null, ?&in = null, ?&in = null, ?&in = null) ;

[32](group___globals.md)int [CreateTimerEx](group___globals.md)(string& in funcdecl, int time, bool repeat, ?&in = null, ?&in = null, ?&in = null, ?&in = null, ?&in = null, ?&in = null, ?&in = null, ?&in = null) ;

[33](group___globals.md)int [GetActiveContext](group___globals.md)() ;

[34](group___globals.md)int [GetPlayersCount](group___globals.md)() ;

[35](group___globals.md)int [GetProcAddress](group___globals.md)(int, string &in) ;

[36](group___globals.md)int [LoadLibrary](group___globals.md)(string &in) ;

[37](group___globals.md)int [PeekInt](group___globals.md)(int bank, int offset) ;

[38](group___globals.md)int [rand](group___globals.md)(int from, int to = 0) ;

[39](group___globals.md)int [rndseed](group___globals.md)() ;

40int round(bool val) ;

41int round(float val) ;

[42](group___globals.md)int [srand](group___globals.md)(int val) ;

[43](group___globals.md)int16 [PeekShort](group___globals.md)(int bank, int offset) ;

[44](group___globals.md)int8 [PeekByte](group___globals.md)(int bank, int offset) ;

[45](group___globals.md)string& [PeekString](group___globals.md)(int bank, int offset) ;

[46](group___globals.md)string& [StripFormatting](group___globals.md)(string& in txt) ;

[47](group___globals.md)void [Collisions](group___globals.md)(int src\_type, int dest\_type, int method, int response) ;

[48](group___globals.md)void [FreeBank](group___globals.md)(int bank) ;

[49](group___globals.md)void [PokeByte](group___globals.md)(int bank, int offset, int value) ;

[50](group___globals.md)void [PokeFloat](group___globals.md)(int bank, int offset, float value) ;

[51](group___globals.md)void [PokeInt](group___globals.md)(int bank, int offset, int value) ;

[52](group___globals.md)void [PokeShort](group___globals.md)(int bank, int offset, int value) ;

[53](group___globals.md)void [PokeString](group___globals.md)(int bank, int offset, string &in value) ;

[54](group___globals.md)void [RegisterFuncdef](group___globals.md)(string &in declaration) ;

[55](group___globals.md)void [RegisterLibraryFunction](group___globals.md)(string &in decl, int procaddress, int convtype) ;

[56](group___globals.md)void [RegisterLibraryMethod](group___globals.md)(string &in classname, string &in decl, int procaddress, int convtype) ;

[57](group___globals.md)void [RegisterLibraryObject](group___globals.md)(string &in classname) ;

[58](group___globals.md)void [RemoveTimer](group___globals.md)() ;

[59](group___globals.md)void [RemoveTimer](group___globals.md)(int timer) ;

[60](group___globals.md)void [RemoveTimer](group___globals.md)(ref& in callback) ;

[61](group___globals.md)void [SetTimerBool](group___globals.md)(int timerdata, bool val) ;

[62](group___globals.md)void [SetTimerFloat](group___globals.md)(int timerdata, float val) ;

[63](group___globals.md)void [SetTimerHandle](group___globals.md)(int timerdata, int handle) ;

[64](group___globals.md)void [SetTimerInt](group___globals.md)(int timerdata, int val) ;

[65](group___globals.md)void [SetTimerString](group___globals.md)(int timerdata, string &in val) ;

[66](group___globals.md)void [TFormNormal](group___globals.md)(float x, float y, float z, [Entity](class_entity.md) src, [Entity](class_entity.md) dest) ;

[67](group___globals.md)void [TFormPoint](group___globals.md)(float x, float y, float z, [Entity](class_entity.md) src, [Entity](class_entity.md) dest) ;

[68](group___globals.md)void [TFormVector](group___globals.md)(float x, float y, float z, [Entity](class_entity.md) src, [Entity](class_entity.md) dest) ;

[69](group___globals.md)void [print](group___globals.md)(string &in message) ;

[70](group___globals.md)void [sleep](group___globals.md)(int milliseconds) ;

[Entity](class_entity.md)

**Definition** all.h:82

[Player](class_player.md)

**Definition** all.h:366

[RegisterFuncdef](group___globals.md)

void RegisterFuncdef(string &in declaration)

[PokeFloat](group___globals.md)

void PokeFloat(int bank, int offset, float value)

[GetPlayersCount](group___globals.md)

int GetPlayersCount()

[frand](group___globals.md)

float frand(float from, float to=0.0)

[PickedNZ](group___globals.md)

float PickedNZ()

[TFormPoint](group___globals.md)

void TFormPoint(float x, float y, float z, Entity src, Entity dest)

[rand](group___globals.md)

int rand(int from, int to=0)

[PokeString](group___globals.md)

void PokeString(int bank, int offset, string &in value)

[PickedNX](group___globals.md)

float PickedNX()

[PokeShort](group___globals.md)

void PokeShort(int bank, int offset, int value)

[CreateTimerData](group___globals.md)

int CreateTimerData()

[RegisterLibraryFunction](group___globals.md)

void RegisterLibraryFunction(string &in decl, int procaddress, int convtype)

[print](group___globals.md)

void print(string &in message)

[TFormVector](group___globals.md)

void TFormVector(float x, float y, float z, Entity src, Entity dest)

[RegisterLibraryMethod](group___globals.md)

void RegisterLibraryMethod(string &in classname, string &in decl, int procaddress, int convtype)

[BankSize](group___globals.md)

int BankSize(int bank)

[GetActiveContext](group___globals.md)

int GetActiveContext()

[PickedY](group___globals.md)

float PickedY()

[PokeInt](group___globals.md)

void PokeInt(int bank, int offset, int value)

[SetTimerInt](group___globals.md)

void SetTimerInt(int timerdata, int val)

[PeekByte](group___globals.md)

int8 PeekByte(int bank, int offset)

[BankStringSize](group___globals.md)

int BankStringSize(string &in)

[GetProcAddress](group___globals.md)

int GetProcAddress(int, string &in)

[PeekShort](group___globals.md)

int16 PeekShort(int bank, int offset)

[sleep](group___globals.md)

void sleep(int milliseconds)

[CreateTimerEx](group___globals.md)

int CreateTimerEx(ref &in callback, int time, bool repeat, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null, ?&in=null)

[GetPlayer](group___globals.md)

Player GetPlayer(int index)

[TFormedZ](group___globals.md)

float TFormedZ()

[TFormedY](group___globals.md)

float TFormedY()

[CreatePivot](group___globals.md)

Entity CreatePivot(int parent=0)

[StripFormatting](group___globals.md)

string & StripFormatting(string &in txt)

[CreateTimer](group___globals.md)

int CreateTimer(ref &in callback, int time, bool repeat, int timerdata=0)

[PokeByte](group___globals.md)

void PokeByte(int bank, int offset, int value)

[LinePick](group___globals.md)

Entity LinePick(float x, float y, float z, float dx, float dy, float dz, float radius=0.0)

[PeekString](group___globals.md)

string & PeekString(int bank, int offset)

[SetTimerString](group___globals.md)

void SetTimerString(int timerdata, string &in val)

[PickedNY](group___globals.md)

float PickedNY()

[RemoveTimer](group___globals.md)

void RemoveTimer()

[FreeBank](group___globals.md)

void FreeBank(int bank)

[CreateBank](group___globals.md)

int CreateBank(int size)

[PickedZ](group___globals.md)

float PickedZ()

[SetTimerBool](group___globals.md)

void SetTimerBool(int timerdata, bool val)

[SetTimerHandle](group___globals.md)

void SetTimerHandle(int timerdata, int handle)

[rndseed](group___globals.md)

int rndseed()

[TFormedX](group___globals.md)

float TFormedX()

[TFormNormal](group___globals.md)

void TFormNormal(float x, float y, float z, Entity src, Entity dest)

[PickedX](group___globals.md)

float PickedX()

[PeekFloat](group___globals.md)

float PeekFloat(int bank, int offset)

[SetTimerFloat](group___globals.md)

void SetTimerFloat(int timerdata, float val)

[PeekInt](group___globals.md)

int PeekInt(int bank, int offset)

[srand](group___globals.md)

int srand(int val)

[Collisions](group___globals.md)

void Collisions(int src\_type, int dest\_type, int method, int response)

[LoadLibrary](group___globals.md)

int LoadLibrary(string &in)

[RegisterLibraryObject](group___globals.md)

void RegisterLibraryObject(string &in classname)

- **globals.h**
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
