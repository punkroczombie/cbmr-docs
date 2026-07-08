<!-- source: http://scpcbmr.42web.io/callbacks_8h_source.html -->
# SCP: Containment Breach 2 Scripting: callbacks.h Source File

|  |  |  |
| --- | --- | --- |
| Logo | SCP: Containment Breach 2 Scripting |  |

![](sync_on.png "click to disable panel synchronization")

- [►](javascript:void(0))[SCP: Containment Breach 2 Scripting](index.md)

[•All](javascript:void(0))[Classes](javascript:void(0))[Functions](javascript:void(0))[Variables](javascript:void(0))[Modules](javascript:void(0))[Pages](javascript:void(0))

Loading...

Searching...

No Matches

callbacks.h

1;

7

[8](group___callbacks.md)void [OnInitialize](group___callbacks.md)() ;

[9](group___callbacks.md)void [OnTerminate](group___callbacks.md)() ;

[10](group___callbacks.md)void [ServerUpdate](group___callbacks.md)() ;

[11](group___callbacks.md)bool [ServerConsole](group___callbacks.md)(string command) ;

[12](group___callbacks.md)void [ServerRestart](group___callbacks.md)() ;

[13](group___callbacks.md)void [WorldLoaded](group___callbacks.md)() ;

[14](group___callbacks.md)void [WorldUpdate](group___callbacks.md)() ;

[15](group___callbacks.md)void [PlayerUpdate](group___callbacks.md)([Player](class_player.md) player) ;

[16](group___callbacks.md)void [PlayerConnect](group___callbacks.md)([Player](class_player.md) player) ;

[17](group___callbacks.md)void [PlayerDisconnect](group___callbacks.md)([Player](class_player.md) player) ;

[18](group___callbacks.md)bool [PlayerChat](group___callbacks.md)([Player](class_player.md) player, string text) ;

[19](group___callbacks.md)void [PlayerAttachesUpdate](group___callbacks.md)([Player](class_player.md) player) ;

[20](group___callbacks.md)bool [PlayerTakeItem](group___callbacks.md)([Player](class_player.md) player, [Items](class_items.md) item) ;

[21](group___callbacks.md)bool [PlayerDropItem](group___callbacks.md)([Player](class_player.md) player, [Items](class_items.md) item) ;

[22](group___callbacks.md)void [PlayerDialogAction](group___callbacks.md)([Player](class_player.md) player, int index, bool response, string input, int selecteditem) ;

[23](group___callbacks.md)bool [PlayerShootPlayer](group___callbacks.md)([Player](class_player.md) shooter, [Player](class_player.md) dest, float x, float y, float z, float damage, bool headshot) ;

[24](group___callbacks.md)bool [PlayerShoot](group___callbacks.md)([Player](class_player.md) player, [Items](class_items.md) item, int weaponattach) ;

[25](group___callbacks.md)void [PlayerPressPlayer](group___callbacks.md)([Player](class_player.md) src, [Player](class_player.md) dest) ;

[26](group___callbacks.md)bool [PlayerConsole](group___callbacks.md)([Player](class_player.md) player, string input) ;

[27](group___callbacks.md)void [PlayerDeath](group___callbacks.md)([Player](class_player.md) player, [Corpse](class_corpse.md) corpse) ;

[28](group___callbacks.md)void [PlayerRespawn](group___callbacks.md)([Player](class_player.md) player) ;

[29](group___callbacks.md)void [PlayerHitPlayer](group___callbacks.md)([Player](class_player.md) src, [Player](class_player.md) dest, int mousedata, float distance) ;

[30](group___callbacks.md)bool [PlayerExploreCorpse](group___callbacks.md)([Player](class_player.md) player, [Corpse](class_corpse.md) corpse) ;

[31](group___callbacks.md)void [PlayerClickObject](group___callbacks.md)([Player](class_player.md) player, [Object](class_object.md) object) ;

[32](group___callbacks.md)void [PlayerShootObject](group___callbacks.md)([Player](class_player.md) player, [Object](class_object.md) object) ;

[33](group___callbacks.md)bool [PlayerUseDoorButton](group___callbacks.md)([Player](class_player.md) player, [Door](class_door.md) door, [Items](class_items.md) useditem) ;

[34](group___callbacks.md)bool [PlayerUseItem](group___callbacks.md)([Player](class_player.md) player, [Items](class_items.md) item) ;

[35](group___callbacks.md)bool [PlayerSelectItem](group___callbacks.md)([Player](class_player.md) player, [Items](class_items.md) item) ;

[36](group___callbacks.md)void [PlayerUse914](group___callbacks.md)([Player](class_player.md) player, int fineid) ;

[37](group___callbacks.md)void [PlayerSelectGUI](group___callbacks.md)([Player](class_player.md) player, [GUIElement](class_g_u_i_element.md) element) ;

[38](group___callbacks.md)bool [PlayerVoice](group___callbacks.md)([Player](class_player.md) player, int bank, bool radio) ;

[39](group___callbacks.md)void [PlayerTeleportElevator](group___callbacks.md)([Player](class_player.md) player, [Room](class_room.md) room, [Entity](class_entity.md) firstentity, [Entity](class_entity.md) secondentity, float offsetx, float offsety ) ;

[40](group___callbacks.md)void [PlayerShootNPC](group___callbacks.md)([Player](class_player.md) player, [NPC](class_n_p_c.md) npc) ;

[41](group___callbacks.md)void [PlayerKeyAction](group___callbacks.md)([Player](class_player.md) player, int newmask, int prevmask) ;

[42](group___callbacks.md)bool [PlayerSpectateAction](group___callbacks.md)([Player](class_player.md) player, [Player](class_player.md) target, int mode) ;

[43](group___callbacks.md)void [IncomingConnection](group___callbacks.md)([Connection](class_connection.md) conn) ;

[44](group___callbacks.md)bool [ConnectionLoaded](group___callbacks.md)([Connection](class_connection.md) conn) ;

[45](group___callbacks.md)void [ConnectionClosed](group___callbacks.md)([Connection](class_connection.md) conn) ;

[46](group___callbacks.md)bool [ShellDamagePlayer](group___callbacks.md)([Shell](class_shell.md) shell, [Player](class_player.md) player, float damage) ;

[47](group___callbacks.md)bool [ShellExplode](group___callbacks.md)([Shell](class_shell.md) shell) ;

48

[49](group___callbacks.md)void [OnLog](group___callbacks.md)(string message) ;

[50](group___callbacks.md)bool [FineItem](group___callbacks.md)([Items](class_items.md) item, int fineid) ;

51

[52](group___callbacks.md)void [OnCreateItem](group___callbacks.md)([Items](class_items.md) item) ;

[53](group___callbacks.md)void [OnRemoveItem](group___callbacks.md)([Items](class_items.md) item) ;

54

[55](group___callbacks.md)void [OnCreateNPC](group___callbacks.md)([NPC](class_n_p_c.md) npc) ;

[56](group___callbacks.md)void [OnRemoveNPC](group___callbacks.md)([NPC](class_n_p_c.md) npc) ;

57

[58](group___callbacks.md)void [OnCreateCorpse](group___callbacks.md)([Corpse](class_corpse.md) corpse) ;

[59](group___callbacks.md)void [OnRemoveCorpse](group___callbacks.md)([Corpse](class_corpse.md) corpse) ;

60

[61](group___callbacks.md)void [OnCreateObject](group___callbacks.md)([Object](class_object.md) obj) ;

[62](group___callbacks.md)void [OnRemoveObject](group___callbacks.md)([Object](class_object.md) obj) ;

63

[64](group___callbacks.md)void [OnCreateLight](group___callbacks.md)([Light](class_light.md) light) ;

[65](group___callbacks.md)void [OnRemoveLight](group___callbacks.md)([Light](class_light.md) light) ;

66

[67](group___callbacks.md)void [OnCreateGUIElement](group___callbacks.md)([GUIElement](class_g_u_i_element.md) element) ;

[68](group___callbacks.md)void [OnRemoveGUIElement](group___callbacks.md)([GUIElement](class_g_u_i_element.md) element) ;

69

[70](group___callbacks.md)void [OnCreateShell](group___callbacks.md)([Shell](class_shell.md) shell) ;

[71](group___callbacks.md)void [OnRemoveShell](group___callbacks.md)([Shell](class_shell.md) shell) ;

[Connection](class_connection.md)

**Definition** all.h:27

[Corpse](class_corpse.md)

**Definition** all.h:42

[Door](class_door.md)

**Definition** all.h:62

[Entity](class_entity.md)

**Definition** all.h:82

[GUIElement](class_g_u_i_element.md)

**Definition** all.h:181

[Items](class_items.md)

**Definition** all.h:225

[Light](class_light.md)

**Definition** all.h:251

[NPC](class_n_p_c.md)

**Definition** all.h:330

[Object](class_object.md)

**Definition** all.h:350

[Player](class_player.md)

**Definition** all.h:366

[Room](class_room.md)

**Definition** all.h:485

[Shell](class_shell.md)

**Definition** all.h:547

[OnRemoveNPC](group___callbacks.md)

void OnRemoveNPC(NPC npc)

[PlayerConsole](group___callbacks.md)

bool PlayerConsole(Player player, string input)

[PlayerRespawn](group___callbacks.md)

void PlayerRespawn(Player player)

[PlayerConnect](group___callbacks.md)

void PlayerConnect(Player player)

[PlayerShootPlayer](group___callbacks.md)

bool PlayerShootPlayer(Player shooter, Player dest, float x, float y, float z, float damage, bool headshot)

[PlayerDialogAction](group___callbacks.md)

void PlayerDialogAction(Player player, int index, bool response, string input, int selecteditem)

[OnCreateCorpse](group___callbacks.md)

void OnCreateCorpse(Corpse corpse)

[PlayerHitPlayer](group___callbacks.md)

void PlayerHitPlayer(Player src, Player dest, int mousedata, float distance)

[PlayerDisconnect](group___callbacks.md)

void PlayerDisconnect(Player player)

[OnCreateGUIElement](group___callbacks.md)

void OnCreateGUIElement(GUIElement element)

[OnTerminate](group___callbacks.md)

void OnTerminate()

[PlayerUpdate](group___callbacks.md)

void PlayerUpdate(Player player)

[ShellExplode](group___callbacks.md)

bool ShellExplode(Shell shell)

[PlayerVoice](group___callbacks.md)

bool PlayerVoice(Player player, int bank, bool radio)

[OnCreateNPC](group___callbacks.md)

void OnCreateNPC(NPC npc)

[PlayerUseItem](group___callbacks.md)

bool PlayerUseItem(Player player, Items item)

[ConnectionClosed](group___callbacks.md)

void ConnectionClosed(Connection conn)

[OnRemoveShell](group___callbacks.md)

void OnRemoveShell(Shell shell)

[OnCreateItem](group___callbacks.md)

void OnCreateItem(Items item)

[PlayerClickObject](group___callbacks.md)

void PlayerClickObject(Player player, Object object)

[PlayerShoot](group___callbacks.md)

bool PlayerShoot(Player player, Items item, int weaponattach)

[PlayerShootNPC](group___callbacks.md)

void PlayerShootNPC(Player player, NPC npc)

[PlayerUse914](group___callbacks.md)

void PlayerUse914(Player player, int fineid)

[WorldLoaded](group___callbacks.md)

void WorldLoaded()

[OnCreateObject](group___callbacks.md)

void OnCreateObject(Object obj)

[ServerUpdate](group___callbacks.md)

void ServerUpdate()

[OnRemoveObject](group___callbacks.md)

void OnRemoveObject(Object obj)

[OnRemoveItem](group___callbacks.md)

void OnRemoveItem(Items item)

[OnRemoveGUIElement](group___callbacks.md)

void OnRemoveGUIElement(GUIElement element)

[PlayerUseDoorButton](group___callbacks.md)

bool PlayerUseDoorButton(Player player, Door door, Items useditem)

[OnCreateLight](group___callbacks.md)

void OnCreateLight(Light light)

[OnRemoveLight](group___callbacks.md)

void OnRemoveLight(Light light)

[IncomingConnection](group___callbacks.md)

void IncomingConnection(Connection conn)

[PlayerSpectateAction](group___callbacks.md)

bool PlayerSpectateAction(Player player, Player target, int mode)

[PlayerExploreCorpse](group___callbacks.md)

bool PlayerExploreCorpse(Player player, Corpse corpse)

[ServerConsole](group___callbacks.md)

bool ServerConsole(string command)

[ShellDamagePlayer](group___callbacks.md)

bool ShellDamagePlayer(Shell shell, Player player, float damage)

[ServerRestart](group___callbacks.md)

void ServerRestart()

[OnCreateShell](group___callbacks.md)

void OnCreateShell(Shell shell)

[PlayerChat](group___callbacks.md)

bool PlayerChat(Player player, string text)

[PlayerTeleportElevator](group___callbacks.md)

void PlayerTeleportElevator(Player player, Room room, Entity firstentity, Entity secondentity, float offsetx, float offsety)

[OnLog](group___callbacks.md)

void OnLog(string message)

[PlayerSelectGUI](group___callbacks.md)

void PlayerSelectGUI(Player player, GUIElement element)

[PlayerShootObject](group___callbacks.md)

void PlayerShootObject(Player player, Object object)

[PlayerDeath](group___callbacks.md)

void PlayerDeath(Player player, Corpse corpse)

[OnInitialize](group___callbacks.md)

void OnInitialize()

[PlayerTakeItem](group___callbacks.md)

bool PlayerTakeItem(Player player, Items item)

[PlayerDropItem](group___callbacks.md)

bool PlayerDropItem(Player player, Items item)

[PlayerKeyAction](group___callbacks.md)

void PlayerKeyAction(Player player, int newmask, int prevmask)

[WorldUpdate](group___callbacks.md)

void WorldUpdate()

[PlayerPressPlayer](group___callbacks.md)

void PlayerPressPlayer(Player src, Player dest)

[PlayerSelectItem](group___callbacks.md)

bool PlayerSelectItem(Player player, Items item)

[OnRemoveCorpse](group___callbacks.md)

void OnRemoveCorpse(Corpse corpse)

[FineItem](group___callbacks.md)

bool FineItem(Items item, int fineid)

[PlayerAttachesUpdate](group___callbacks.md)

void PlayerAttachesUpdate(Player player)

[ConnectionLoaded](group___callbacks.md)

bool ConnectionLoaded(Connection conn)

- **callbacks.h**
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
