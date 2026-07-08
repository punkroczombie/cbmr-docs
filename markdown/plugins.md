<!-- source: http://scpcbmr.42web.io/plugins.html -->
# SCP: Containment Breach 2 Scripting: How to add plugins

|  |  |  |
| --- | --- | --- |
| Logo | SCP: Containment Breach 2 Scripting |  |

![](sync_on.png "click to disable panel synchronization")

- [▼](javascript:void(0))[SCP: Containment Breach 2 Scripting](index.md)

  - [▼](javascript:void(0))[AngelScript](index.md)

    - [Writing your first script](scripting_guide.md)
    - [How to add plugins](plugins.md)
    - [How to add addons](addons.md)
    - [Addons configurations](json_interfaces.md)
    - [Text Formatting Guide](text_formatting.md)
  - [►](javascript:void(0))[Topics](topics.md)
  - [►](javascript:void(0))[Classes](annotated.md)

[•All](javascript:void(0))[Classes](javascript:void(0))[Functions](javascript:void(0))[Variables](javascript:void(0))[Modules](javascript:void(0))[Pages](javascript:void(0))

Loading...

Searching...

No Matches

How to add plugins

Plugins are loaded via **AngelScript (.as)** files (plugin in server.cfg). These scripts allow you to extend the server functionality by loading external libraries (DLLs) and registering their functions.

Attention
:   - 'Register' functions **must not** be used in regular scripts. Plugins are initialized strictly **before** any standard scripts are loaded to ensure all registered functions are available globally.
    - DLL libraries must match the architecture of the application (32-bit).

Note
:   Using stdcall is not recommended. Although we use a custom AngelScript core to handle it, the system is still not perfect and is limited to internal server use only.

### Basic Script Structure

Every plugin script should define the necessary library handles and initialization logic.

enum ConvTypes

{

cdecl = 0,

stdcall = 1

}

int currentlib = 0;

int convtype = 0;

string libmethod = "";

void [OnInitialize](group___callbacks.md)()

{

// Initialize your plugin here

ExampleLoad();

}

[OnInitialize](group___callbacks.md)

void OnInitialize()

### Loading a Library Example

To register functions from a DLL, you need to load the library and set the calling convention.

void ExampleLoad()

{

// Load the external DLL

SetLibrary([LoadLibrary](group___globals.md)("uemph.dll"));

SetConvType(stdcall);

// Registering custom functions from the DLL

RegisterFunction("void CreateConsole()", "\_CreateConsole@0");

RegisterFunction("void ConsoleTitle(const char)", "\_ConsoleTitle@4");

// Memory management examples

RegisterFunction("int malloc(int)", "\_Memory\_Alloc@4");

RegisterFunction("void free(int)", "\_Memory\_Dealloc@4");

}

[LoadLibrary](group___globals.md)

int LoadLibrary(string &in)

### Loading a Library with cdecl

void ExampleLoad()

{

SetLibrary([LoadLibrary](group___globals.md)("custom\_lib.dll"));

// CDecl conv type

SetConvType(cdecl);

RegisterFunction("int calculate\_sum(int, int)", "calculate\_sum");

RegisterFunction("void log\_message(const char)", "log\_message");

}

### Method Registration Example

To register a class and its methods, use `RegisterClass` followed by `RegisterMethod`.

void RegisterConsole()

{

SetLibrary([LoadLibrary](group___globals.md)("custom\_console.dll"));

SetConvType(stdcall);

// Register the class 'Console' and a way to get it in scripts

RegisterClass("Console", "GetConsole()", "\_GetConsoleInstance@0");

// All subsequent RegisterMethod calls will belong to 'Console'

SetLibraryMethod("Console");

RegisterMethod("void Print(const char)", "\_Console\_Print@4");

RegisterMethod("void Clear()", "\_Console\_Clear@0");

}

### Helper Functions

The following helper functions are used to manage the registration process:

**SetLibrary(int lib)**: Sets the current active library handle.  
**SetConvType(int type)**: Sets the calling convention (`cdecl` or `stdcall`).  
**RegisterFunction(string declaration, string proc)**: Maps a script function name to a DLL procedure address.  
**RegisterClass(string decl, string get, string proc)**: Registers a complex object and its accessor.

Note
:   Ensure that the procedure names (e.g., `_CreateConsole@0`) match the exported symbols in your DLL exactly.

### Plugin loader script example

enum ConvTypes

{

cdecl = 0,

stdcall = 1

}

int currentlib = 0;

int convtype = 0;

string libmethod = "";

void [OnInitialize](group___callbacks.md)()

{

SetLibrary([LoadLibrary](group___globals.md)("uemph.dll"));

SetConvType(stdcall);

RegisterFunction("const char SplitString(const char, const char, int)", "\_SplitString@12");

RegisterFunction("void CreateConsole()", "\_CreateConsole@0");

RegisterFunction("void ConsoleTitle(const char)", "\_ConsoleTitle@4");

RegisterFunction("const char ConsoleInput(const char)", "\_ConsoleInput@4");

RegisterFunction("void ConsoleColor(int)", "\_ConsoleColor@4");

RegisterFunction("void ConsoleMessage(const char)", "\_ConsoleMessage@4");

RegisterFunction("int malloc(int)", "\_Memory\_Alloc@4");

RegisterFunction("void free(int)", "\_Memory\_Dealloc@4");

RegisterFunction("void mem\_pokebyte(int,int8)", "\_Memory\_PokeByte@8");

RegisterFunction("void mem\_pokeshort(int,int16)", "\_Memory\_PokeShort@8");

RegisterFunction("void mem\_pokeint(int,int)", "\_Memory\_PokeInt@8");

RegisterFunction("void mem\_pokefloat(int,float)", "\_Memory\_PokeFloat@8");

RegisterFunction("void mem\_pokeint64(int,int64)", "\_Memory\_PokeInt64@12");

RegisterFunction("int8 mem\_peekbyte(int)", "\_Memory\_PeekByte@4");

RegisterFunction("int16 mem\_peekshort(int)", "\_Memory\_PeekShort@4");

RegisterFunction("int mem\_peekint(int)", "\_Memory\_PeekInt@4");

RegisterFunction("float mem\_peekfloat(int)", "\_Memory\_PeekFloat@4");

RegisterFunction("int64 mem\_peekint64(int)", "\_Memory\_PeekInt64@4");

RegisterFunction("const char mem\_peekconstchar(int)", "\_Memory\_PeekConstChar@4");

}

void SetLibrary(int lib)

{

currentlib = lib;

}

void SetConvType(int type)

{

convtype = type;

}

void SetLibraryMethod(string method)

{

libmethod = method;

}

void RegisterMethod(string declaration, string proc)

{

[RegisterLibraryMethod](group___globals.md)(libmethod, declaration, [GetProcAddress](group___globals.md)(currentlib, proc), convtype);

}

void RegisterFunction(string declaration, string proc)

{

[RegisterLibraryFunction](group___globals.md)(declaration, [GetProcAddress](group___globals.md)(currentlib, proc),convtype);

}

void RegisterClass(string decl, string get, string proc)

{

[RegisterLibraryObject](group___globals.md)(decl);

RegisterFunction(decl + "& " + get, proc);

}

[RegisterLibraryFunction](group___globals.md)

void RegisterLibraryFunction(string &in decl, int procaddress, int convtype)

[RegisterLibraryMethod](group___globals.md)

void RegisterLibraryMethod(string &in classname, string &in decl, int procaddress, int convtype)

[GetProcAddress](group___globals.md)

int GetProcAddress(int, string &in)

[RegisterLibraryObject](group___globals.md)

void RegisterLibraryObject(string &in classname)

- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
