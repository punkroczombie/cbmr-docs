<!-- source: http://scpcbmr.42web.io/scripting_guide.html -->
# SCP: Containment Breach 2 Scripting: Writing your first script

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

Writing your first script

# Introduction to Scripting

[Server](class_server.md) gamemodes logic in **SCP: Containment Breach 2** is powered by **AngelScript**. Scripts allow you to manage player behavior, anticheat logic, and world events, etc...

Scripts are located in the `scripts/` folder and are usually included via the main entry point defined in your server configuration.

Note
:   The classic Breach mode is located in the Tools\Gamemodes folder, here you can see how the scripts work.

# Script Lifecycle

Understanding when your code runs is crucial for stability.

- **[OnInitialize()](group___callbacks.md)**: Runs once when the script is loaded.
- *Best for:* Registering callbacks, initializing variables, creating timers.
- Warning
  :   Do **not** use world-related functions (like spawning items) here as the world isn't ready yet.
- **OnWorldLoaded()**: Runs after the map and all objects are fully loaded.
- *Best for:* Spawning NPCs, setting up lobby logic, or modifying room properties.
- **OnWorldUpdate()**: Runs every frame.
- *Best for:* Global logic checks, but be careful with performance. Use **Timers** for non-critical tasks.
- **[OnTerminate()](group___callbacks.md)**: Runs once when the script is terminate.

---

# Basic Template

Here is a standard structure for a new game module:

#include "include/uerm.as" // Core engine constants and types

void [OnInitialize](group___callbacks.md)()

{

// 1. Register all standard callbacks

RegisterAllCallbacks();

// 2. Set server variables

server.gamemode = "My Custom Mode";

server.disablenpcs = false;

// 3. Setup recurring tasks (1000ms = 1 second)

[CreateTimer](group___globals.md)(MyGlobalUpdate, 1000, true);

[print](group___globals.md)("My Script Loaded!");

}

// This function is called every second by the timer

void MyGlobalUpdate()

{

// Broadcast a message to all players every second (example)

// chat.Send("Tick!");

}

[OnInitialize](group___callbacks.md)

void OnInitialize()

[print](group___globals.md)

void print(string &in message)

[CreateTimer](group___globals.md)

int CreateTimer(ref &in callback, int time, bool repeat, int timerdata=0)

---

# Callbacks Registration

Callbacks are the primary way to respond to game and server events (e.g., a player connecting, pressing a key, or a console command). You must register them inside `OnInitialize()` using `RegisterCallback()`.

### Some of Common Callback Types:

| Callback Constant | Function Signature | Description |
| --- | --- | --- |
| `PlayerConnect_c` | `void Func(Player p)` | Called when a player joins the server. |
| `PlayerKeyAction_c` | `void Func(Player p, int n, int o)` | Called when a player presses or releases a key. |
| `PlayerPressPlayer_c` | `void Func(Player src, Player dest)` | Called when one player "interacts" with another. |
| `ServerConsole_c` | `bool Func(string command)` | Called when a command is entered in the server console. |

### Example: Admin Panel Registration

namespace AdminPanel

{

void Register()

{

// Registering events for the admin system

RegisterCallback(PlayerKeyAction\_c, OnPlayerKeyAction);

RegisterCallback(PlayerConnect\_c, OnPlayerConnect);

RegisterCallback(PlayerPressPlayer\_c, OnPlayerPressPlayer);

RegisterCallback(ServerConsole\_c, OnConsole);

}

// Example handler for console commands

bool OnConsole(string command)

{

if(command == "reloadadmins") {

Load(); // Your custom function to reload data

[print](group___globals.md)("Admins reloaded!");

return false; // Return false to indicate the command was handled

}

return true;

}

}

---

# Working with Players

To handle player data safely, it is recommended to use a namespace and a data class.

namespace PlayerSystem

{

class SessionData {

int points;

bool isVerified;

SessionData() {

points = 0;

isVerified = false;

}

}

// Global array to store data for each player slot

SessionData@[] pData(MAX\_PLAYERS + 1);

void OnPlayerConnect([Player](class_player.md) p) {

@pData[p.[GetIndex](class_player.md)()] = SessionData();

[print](group___globals.md)("Data initialized for: " + p.[GetName](class_player.md)());

}

}

[Player](class_player.md)

**Definition** all.h:366

[Player::GetIndex](class_player.md)

int GetIndex()

[Player::GetName](class_player.md)

string & GetName()

Note
:   When writing scripts that affect movement or gameplay, always remember that you won't trust a client. Players can primarily spoof or manipulate only their own position (e.g., speedhack, teleport, noclip), however, even if other actions seem secure, you should always implement additional server-side checks for any sensitive logic (mostly player to player interaction (OnPlayerHitPlayer)) to ensure the integrity of the game state.

# Best Practices

Important
:   - **Performance:** Avoid heavy loops in `OnWorldUpdate`. It runs ~60-100 times per second.
    - **Null Checks:** Always check if a [Player](class_player.md) object is valid (`if(p != NULL)`) before accessing its methods.
    - **Memory:** If you create objects in a loop, ensure they are properly handled or scoped.

See also
:   [How to use DLLs in Plugins](plugins.md)
:   [How to configure items and models](json_interfaces.md)

- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
