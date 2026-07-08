<!-- source: http://scpcbmr.42web.io/all_8h_source.html -->
# SCP: Containment Breach 2 Scripting: all.h Source File

|  |  |  |
| --- | --- | --- |
| Logo | SCP: Containment Breach 2 Scripting |  |

![](sync_on.png "click to disable panel synchronization")

- [►](javascript:void(0))[SCP: Containment Breach 2 Scripting](index.md)

[•All](javascript:void(0))[Classes](javascript:void(0))[Functions](javascript:void(0))[Variables](javascript:void(0))[Modules](javascript:void(0))[Pages](javascript:void(0))

Loading...

Searching...

No Matches

all.h

[1](class_audio.md)class [Audio](class_audio.md)

2{

3public:

[4](class_audio.md) [Sound](class_sound.md) [Play3DSound](class_audio.md)(string& in filenameorurl, [Player](class_player.md) player, float range, float volume, bool norange = false) ;

[5](class_audio.md) [Sound](class_sound.md) [Play3DSound](class_audio.md)(string& in filenameorurl, [Entity](class_entity.md) entity, float range, float volume, bool norange = false) ;

[6](class_audio.md) [Sound](class_sound.md) [Play3DSound](class_audio.md)(string& in filenameorurl, float x, float y, float z, float range, float volume, bool norange = false) ;

[7](class_audio.md) [Sound](class_sound.md) [PlaySound](class_audio.md)(string& in filenameorurl) ;

[8](class_audio.md) [Sound](class_sound.md) [PlaySoundForPlayer](class_audio.md)([Player](class_player.md) player, string& in filenameorurl) ;

[9](class_audio.md) [Sound](class_sound.md) [Play3DSoundForPlayer](class_audio.md)([Player](class_player.md) player, string& in filenameorurl, [Entity](class_entity.md) entity, float range, float volume, bool norange = false) ;

[10](class_audio.md) [Sound](class_sound.md) [Play3DSoundForPlayer](class_audio.md)([Player](class_player.md) player, string& in filenameorurl, float x, float y, float z, float range, float volume, bool norange = false) ;

[11](class_audio.md) [Sound](class_sound.md) [Play3DSoundForPlayer](class_audio.md)([Player](class_player.md) player, string& in filenameorurl, [Player](class_player.md) player, float range, float volume, bool norange = false) ;

12};

[1](class_audio.md)class [Audio](class_audio.md) {[…](javascript:codefold.toggle('00001'))};

[13](class_xD0_xA1hat.md)class [Сhat](class_xD0_xA1hat.md)

14{

15public:

[16](class_xD0_xA1hat.md) void [Send](class_xD0_xA1hat.md)(string& in message) ;

[17](class_xD0_xA1hat.md) void [SendPlayer](class_xD0_xA1hat.md)([Player](class_player.md) player, string& in message) ;

18};

[13](class_xD0_xA1hat.md)class [Сhat](class_xD0_xA1hat.md) {[…](javascript:codefold.toggle('00013'))};

[19](class_config.md)class [Config](class_config.md)

20{

21public:

[22](class_config.md) bool [Exist](class_config.md)(string& in key, int index = 0) ;

[23](class_config.md) string& [Get](class_config.md)(string& in key, int index = 0) ;

[24](class_config.md) void [Remove](class_config.md)() ;

25};

[19](class_config.md)class [Config](class_config.md) {[…](javascript:codefold.toggle('00019'))};

[26](class_connection.md)class [Connection](class_connection.md)

27{

28public:

[29](class_connection.md) int [GetPort](class_connection.md)() ;

[30](class_connection.md) string& [GetLanguage](class_connection.md)() ;

[31](class_connection.md) string& [GetHWID](class_connection.md)(int wmid = 0) ;

[32](class_connection.md) string& [GetIP](class_connection.md)() ;

[33](class_connection.md) string& [GetSteamID](class_connection.md)() ;

[34](class_connection.md) int [GetQueue](class_connection.md)() ;

[35](class_connection.md) bool [Join](class_connection.md)() ;

[36](class_connection.md) void [Accept](class_connection.md)() ;

[37](class_connection.md) void [Cancel](class_connection.md)(int code) ;

[38](class_connection.md) void [Cancel](class_connection.md)(string& in custom = "") ;

[39](class_connection.md) void [Remove](class_connection.md)() ;

40};

[26](class_connection.md)class [Connection](class_connection.md) {[…](javascript:codefold.toggle('00026'))};

[41](class_corpse.md)class [Corpse](class_corpse.md)

42{

43public:

[44](class_corpse.md) int [GetIndex](class_corpse.md)() ;

[45](class_corpse.md) [Player](class_player.md) [GetPlayer](class_corpse.md)() ;

[46](class_corpse.md) [Entity](class_entity.md) [GetEntity](class_corpse.md)() ;

[47](class_corpse.md) float [GetTimeout](class_corpse.md)() ;

[48](class_corpse.md) void [SetTimeout](class_corpse.md)(float) ;

[49](class_corpse.md) bool [PushItem](class_corpse.md)([Items](class_items.md)) ;

[50](class_corpse.md) bool [ExploreItem](class_corpse.md)(int slot) ;

[51](class_corpse.md) [Items](class_items.md) [GetItem](class_corpse.md)(int slot) ;

[52](class_corpse.md) int [GetModel](class_corpse.md)() ;

[53](class_corpse.md) int [GetItemsCount](class_corpse.md)() ;

[54](class_corpse.md) bool [IsExplored](class_corpse.md)() ;

[55](class_corpse.md) void [SetExplore](class_corpse.md)(bool explore) ;

[56](class_corpse.md) bool [Explore](class_corpse.md)() ;

[57](class_corpse.md) void [SetData](class_corpse.md)(string& in data) ;

[58](class_corpse.md) string& [GetData](class_corpse.md)() ;

[59](class_corpse.md) void [Remove](class_corpse.md)() ;

60};

[41](class_corpse.md)class [Corpse](class_corpse.md) {[…](javascript:codefold.toggle('00041'))};

[61](class_door.md)class [Door](class_door.md)

62{

63public:

[64](class_door.md) void [Use](class_door.md)() ;

[65](class_door.md) void [SetOpen](class_door.md)(bool) ;

[66](class_door.md) bool [IsOpened](class_door.md)() ;

[67](class_door.md) bool [IsBreak](class_door.md)() ;

[68](class_door.md) void [SetLockState](class_door.md)(int) ;

[69](class_door.md) int [GetLockState](class_door.md)() ;

[70](class_door.md) float [GetOpenState](class_door.md)() ;

[71](class_door.md) bool [BreakDoor](class_door.md)(float x, float y, float z) ;

[72](class_door.md) void [Decompose](class_door.md)() ;

[73](class_door.md) int [GetDoorAccess](class_door.md)() ;

[74](class_door.md) int [GetDoorType](class_door.md)() ;

[75](class_door.md) void [SetKeycard](class_door.md)(int) ;

[76](class_door.md) int [GetKeycard](class_door.md)() ;

[77](class_door.md) [Entity](class_entity.md) [GetEntity](class_door.md)() ;

[78](class_door.md) [Entity](class_entity.md) [GetButton](class_door.md)(int index) ;

[79](class_door.md) int [GetIndex](class_door.md)() ;

80};

[61](class_door.md)class [Door](class_door.md) {[…](javascript:codefold.toggle('00061'))};

[81](class_entity.md)class [Entity](class_entity.md)

82{

83public:

[84](class_entity.md) void [SetPosition](class_entity.md)(float x, float y, float z, bool global = false) ;

[85](class_entity.md) void [SetRotation](class_entity.md)(float pitch, float yaw, float roll, bool global = false) ;

[86](class_entity.md) void [SetScale](class_entity.md)(float x, float y, float z, bool global = false) ;

[87](class_entity.md) float [PositionX](class_entity.md)(bool global = false, float tween = 1.0) ;

[88](class_entity.md) float [PositionY](class_entity.md)(bool global = false, float tween = 1.0) ;

[89](class_entity.md) float [PositionZ](class_entity.md)(bool global = false, float tween = 1.0) ;

[90](class_entity.md) void [Translate](class_entity.md)(float x, float y, float z, bool global = false) ;

[91](class_entity.md) void [Move](class_entity.md)(float x, float y, float z, bool global = false) ;

[92](class_entity.md) float [Pitch](class_entity.md)(bool global = false, float tween = 1.0) ;

[93](class_entity.md) float [Yaw](class_entity.md)(bool global = false, float tween = 1.0) ;

[94](class_entity.md) float [Roll](class_entity.md)(bool global = false, float tween = 1.0) ;

[95](class_entity.md) float [Turn](class_entity.md)(float pitch, float yaw, float roll, bool global = false) ;

[96](class_entity.md) float [ScaleX](class_entity.md)(bool global = false, float tween = 1.0) ;

[97](class_entity.md) float [ScaleY](class_entity.md)(bool global = false, float tween = 1.0) ;

[98](class_entity.md) float [ScaleZ](class_entity.md)(bool global = false, float tween = 1.0) ;

[99](class_entity.md) void [SetAnimTime](class_entity.md)(float time, int sequence = 0) ;

[100](class_entity.md) float [GetAnimTime](class_entity.md)() ;

[101](class_entity.md) float [Point](class_entity.md)([Entity](class_entity.md) target, float roll = 0.0) ;

[102](class_entity.md) [Entity](class_entity.md) [Pick](class_entity.md)(float distance) ;

[103](class_entity.md) void [SetPickMode](class_entity.md)(int pickmode, bool obscurer = false) ;

[104](class_entity.md) bool [Visible](class_entity.md)([Entity](class_entity.md) target, float radius = 0.0f) ;

[105](class_entity.md) float [Distance](class_entity.md)([Entity](class_entity.md) target) ;

[106](class_entity.md) float [DistanceSquared](class_entity.md)([Entity](class_entity.md) target) ;

[107](class_entity.md) void [SetParent](class_entity.md)([Entity](class_entity.md) target, bool retain = true) ;

[108](class_entity.md) [Entity](class_entity.md) [GetParent](class_entity.md)() ;

[109](class_entity.md) int [CountChildren](class_entity.md)() ;

[110](class_entity.md) [Entity](class_entity.md) [GetChild](class_entity.md)(int) ;

[111](class_entity.md) string& [GetName](class_entity.md)() ;

[112](class_entity.md) void [SetName](class_entity.md)(string& in name) ;

[113](class_entity.md) bool [Collided](class_entity.md)(int colltype) ;

[114](class_entity.md) int [CountCollisions](class_entity.md)() ;

[115](class_entity.md) float [CollisionX](class_entity.md)(int index) ;

[116](class_entity.md) float [CollisionY](class_entity.md)(int index) ;

[117](class_entity.md) float [CollisionZ](class_entity.md)(int index) ;

[118](class_entity.md) float [CollisionNX](class_entity.md)(int index) ;

[119](class_entity.md) float [CollisionNY](class_entity.md)(int index) ;

[120](class_entity.md) float [CollisionNZ](class_entity.md)(int index) ;

[121](class_entity.md) float [CollisionImpulse](class_entity.md)(int index) const ;

[122](class_entity.md) float [CollisionDistance](class_entity.md)(int index) const ;

[123](class_entity.md) float [CollisionTime](class_entity.md)(int index) const ;

[124](class_entity.md) [Entity](class_entity.md) [CollisionEntity](class_entity.md)(int index) const ;

[125](class_entity.md) int [CollisionTriangle](class_entity.md)(int index) const ;

[126](class_entity.md) void [SetType](class_entity.md)(int colltype, bool recursive = false) ;

[127](class_entity.md) void [SetRadius](class_entity.md)(float x, float y = 0.0) ;

[128](class_entity.md) void [SetCylinder](class_entity.md)(float x\_radius, float y\_radius = 0.0) ;

[129](class_entity.md) void [SetBox](class_entity.md)(float x, float y, float z, float w, float h, float d) ;

[130](class_entity.md) int [GetType](class_entity.md)() const ;

[131](class_entity.md) int [GetShape](class_entity.md)(float &out x, float &out y, float &out z, float &out width, float &out height, float &out depth) const ;

[132](class_entity.md) void [Reset](class_entity.md)() ;

[133](class_entity.md) bool [InView](class_entity.md)([Entity](class_entity.md) target) ;

[134](class_entity.md) void [Show](class_entity.md)() ;

[135](class_entity.md) void [Hide](class_entity.md)() ;

[136](class_entity.md) void [Remove](class_entity.md)() ;

[137](class_entity.md) void [SetMass](class_entity.md)(float mass) ;

[138](class_entity.md) void [SetPhysics](class_entity.md)(bool enable) ;

[139](class_entity.md) void [SetKinematic](class_entity.md)(bool enable) ;

[140](class_entity.md) void [SetCenter](class_entity.md)(float x, float y, float z) ;

[141](class_entity.md) void [SetLinearCast](class_entity.md)(bool enable) ;

[142](class_entity.md) void [SetFriction](class_entity.md)(float friction) ;

[143](class_entity.md) void [SetRollFriction](class_entity.md)(float friction) ;

[144](class_entity.md) void [SetRestitution](class_entity.md)(float res) ;

[145](class_entity.md) void [SetGravity](class_entity.md)(float factor) ;

[146](class_entity.md) void [SetLinearFactor](class_entity.md)(float x, float y, float z) ;

[147](class_entity.md) void [SetAngularFactor](class_entity.md)(float x, float y, float z) ;

[148](class_entity.md) void [SetLinearDamping](class_entity.md)(float damping) ;

[149](class_entity.md) void [SetAngularDamping](class_entity.md)(float damping) ;

[150](class_entity.md) void [SetConstraint](class_entity.md)(float normalAngle, float planeAngle, float twistMinAngle, float twistMaxAngle, float torqueFriction) ;

[151](class_entity.md) void [Activate](class_entity.md)(bool enable) ;

[152](class_entity.md) void [Sleep](class_entity.md)(bool enable) ;

[153](class_entity.md) void [Freeze](class_entity.md)(bool enable) ;

[154](class_entity.md) bool [IsFreezed](class_entity.md)() const ;

[155](class_entity.md) bool [IsActive](class_entity.md)() const ;

[156](class_entity.md) void [SetLinearVelocity](class_entity.md)(float x, float y, float z) ;

[157](class_entity.md) void [SetAngularVelocity](class_entity.md)(float x, float y, float z) ;

[158](class_entity.md) void [GetLinearVelocity](class_entity.md)(float &out x, float &out y, float &out z) const ;

[159](class_entity.md) void [GetAngularVelocity](class_entity.md)(float &out x, float &out y, float &out z) const ;

[160](class_entity.md) void [Impulse](class_entity.md)(float x, float y, float z) ;

[161](class_entity.md) void [Torque](class_entity.md)(float x, float y, float z) ;

[162](class_entity.md) void [ClearForces](class_entity.md)() ;

163};

[81](class_entity.md)class [Entity](class_entity.md) {[…](javascript:codefold.toggle('00081'))};

[164](class_event.md)class [Event](class_event.md)

165{

166public:

[167](class_event.md) [Room](class_room.md) [GetRoom](class_event.md)() ;

[168](class_event.md) int [GetIndex](class_event.md)() ;

[169](class_event.md) int [GetIdentifier](class_event.md)() ;

[170](class_event.md) float [GetState](class_event.md)() ;

[171](class_event.md) float [GetState2](class_event.md)() ;

[172](class_event.md) float [GetState3](class_event.md)() ;

[173](class_event.md) float [GetState4](class_event.md)() ;

[174](class_event.md) float [SetState](class_event.md)(float state) ;

[175](class_event.md) float [SetState2](class_event.md)(float state) ;

[176](class_event.md) float [SetState3](class_event.md)(float state) ;

[177](class_event.md) float [SetState4](class_event.md)(float state) ;

[178](class_event.md) void [Remove](class_event.md)() ;

179};

[164](class_event.md)class [Event](class_event.md) {[…](javascript:codefold.toggle('00164'))};

[180](class_g_u_i_element.md)class [GUIElement](class_g_u_i_element.md)

181{

182public:

[183](class_g_u_i_element.md) void [GetPosition](class_g_u_i_element.md)(float& out x, float& out y) ;

[184](class_g_u_i_element.md) void [SetPosition](class_g_u_i_element.md)(float x, float y) ;

[185](class_g_u_i_element.md) void [SetScale](class_g_u_i_element.md)(float width, float height) ;

[186](class_g_u_i_element.md) void [GetScale](class_g_u_i_element.md)(float& out width, float& out height) ;

[187](class_g_u_i_element.md) void [SetRotation](class_g_u_i_element.md)(int degrees) ;

[188](class_g_u_i_element.md) void [GetRotation](class_g_u_i_element.md)(int& out degrees) ;

[189](class_g_u_i_element.md) void [SetData](class_g_u_i_element.md)(string& in data) ;

[190](class_g_u_i_element.md) void [SetText](class_g_u_i_element.md)(string& in text) ;

[191](class_g_u_i_element.md) void [SetSelectable](class_g_u_i_element.md)(bool selectable) ;

[192](class_g_u_i_element.md) void [SetShadow](class_g_u_i_element.md)(bool shadowed) ;

[193](class_g_u_i_element.md) void [SetAspect](class_g_u_i_element.md)(bool keep) ;

[194](class_g_u_i_element.md) void [SetOpacity](class_g_u_i_element.md)(float target, float lerp) ;

[195](class_g_u_i_element.md) void [SetColor](class_g_u_i_element.md)(int r, int g, int b) ;

[196](class_g_u_i_element.md) void [SetTechnique](class_g_u_i_element.md)(string& in technique) ;

[197](class_g_u_i_element.md) [Player](class_player.md) [GetPlayer](class_g_u_i_element.md)() ;

[198](class_g_u_i_element.md) void [SetAttach](class_g_u_i_element.md)([Player](class_player.md) player) ;

[199](class_g_u_i_element.md) void [SetAttach](class_g_u_i_element.md)(bool enable, float x = 0.0, float y = 0.0, float z = 0.0) ;

[200](class_g_u_i_element.md) [Player](class_player.md) [GetAttach](class_g_u_i_element.md)() ;

[201](class_g_u_i_element.md) bool [GetAttach](class_g_u_i_element.md)(float& out x, float& out y, float& out z) ;

[202](class_g_u_i_element.md) string& [GetText](class_g_u_i_element.md)() ;

[203](class_g_u_i_element.md) string& [GetData](class_g_u_i_element.md)() ;

[204](class_g_u_i_element.md) bool [IsSelectable](class_g_u_i_element.md)() ;

[205](class_g_u_i_element.md) bool [IsHidden](class_g_u_i_element.md)() ;

[206](class_g_u_i_element.md) void [SetCallback](class_g_u_i_element.md)(string& in funcname) ;

[207](class_g_u_i_element.md) void [SetCallback](class_g_u_i_element.md)(GUICALLBACK @gc) ;

[208](class_g_u_i_element.md) void [Hide](class_g_u_i_element.md)() ;

[209](class_g_u_i_element.md) void [Show](class_g_u_i_element.md)() ;

[210](class_g_u_i_element.md) void [Remove](class_g_u_i_element.md)() ;

211};

[180](class_g_u_i_element.md)class [GUIElement](class_g_u_i_element.md) {[…](javascript:codefold.toggle('00180'))};

[212](class_graphics.md)class [Graphics](class_graphics.md)

213{

214public:

[215](class_graphics.md) [GUIElement](class_g_u_i_element.md) [CreateOval](class_graphics.md)([Player](class_player.md) player, float x, float y, float width, float height, bool align = false) ;

[216](class_graphics.md) [GUIElement](class_g_u_i_element.md) [CreateRect](class_graphics.md)([Player](class_player.md) player, float x, float y, float width, float height, bool align = false) ;

[217](class_graphics.md) [GUIElement](class_g_u_i_element.md) [CreateProgressBar](class_graphics.md)([Player](class_player.md) player, float time, float x, float y, float width, float height, bool align = false) ;

[218](class_graphics.md) [GUIElement](class_g_u_i_element.md) [CreateProgressBar](class_graphics.md)([Player](class_player.md) player, float time, float x, float y, float width, float height, bool align, string &in callback) ;

[219](class_graphics.md) [GUIElement](class_g_u_i_element.md) [CreateProgressBar](class_graphics.md)([Player](class_player.md) player, float time, float x, float y, float width, float height, bool align, ref &in callback) ;

[220](class_graphics.md) [GUIElement](class_g_u_i_element.md) [CreateText](class_graphics.md)([Player](class_player.md) player, int fontid, string& in text, float x, float y, bool align = false) ;

[221](class_graphics.md) [GUIElement](class_g_u_i_element.md) [CreateImage](class_graphics.md)([Player](class_player.md) player, string& in filename, float x, float y, float width, float height, bool align = false) ;

[222](class_graphics.md) [GUIElement](class_g_u_i_element.md) [CreatePostEffect](class_graphics.md)([Player](class_player.md) player, string& in filename, string& in defines = "") ;

223};

[212](class_graphics.md)class [Graphics](class_graphics.md) {[…](javascript:codefold.toggle('00212'))};

[224](class_items.md)class [Items](class_items.md)

225{

226public:

[227](class_items.md) bool [IsPicked](class_items.md)() ;

[228](class_items.md) [Player](class_player.md) [GetPicker](class_items.md)() ;

[229](class_items.md) bool [SetPicker](class_items.md)([Player](class_player.md) player, float throwforce = 0.0) ;

[230](class_items.md) [Entity](class_entity.md) [GetEntity](class_items.md)() ;

[231](class_items.md) int [GetIndex](class_items.md)() ;

[232](class_items.md) string& [GetName](class_items.md)() ;

[233](class_items.md) string& [GetTemplateName](class_items.md)() ;

[234](class_items.md) int [GetTemplateIndex](class_items.md)() ;

[235](class_items.md) bool [IsWeapon](class_items.md)() ;

[236](class_items.md) void [SetState](class_items.md)(float state) ;

[237](class_items.md) void [SetState2](class_items.md)(float state) ;

[238](class_items.md) void [SetState3](class_items.md)(float state) ;

[239](class_items.md) float [GetState](class_items.md)() ;

[240](class_items.md) float [GetState2](class_items.md)() ;

[241](class_items.md) float [GetState3](class_items.md)() ;

[242](class_items.md) [Items](class_items.md) [Fine](class_items.md)(int) ;

[243](class_items.md) int [GetSlots](class_items.md)() ;

[244](class_items.md) [Items](class_items.md) [GetParentItem](class_items.md)() ;

[245](class_items.md) [Items](class_items.md) [GetSlotItem](class_items.md)(int) ;

[246](class_items.md) bool [PushItem](class_items.md)([Items](class_items.md)) ;

[247](class_items.md) bool [RemoveSlotItem](class_items.md)(int) ;

[248](class_items.md) void [Remove](class_items.md)() ;

249};

[224](class_items.md)class [Items](class_items.md) {[…](javascript:codefold.toggle('00224'))};

[250](class_light.md)class [Light](class_light.md)

251{

252public:

[253](class_light.md) int [GetIndex](class_light.md)() ;

[254](class_light.md) void [SetFOV](class_light.md)(float fov) ;

[255](class_light.md) void [SetRange](class_light.md)(float range) ;

[256](class_light.md) void [SetScattering](class_light.md)(float scattering) ;

[257](class_light.md) void [SetColor](class_light.md)(int r, int g, int b) ;

[258](class_light.md) void [SetCastShadows](class_light.md)(bool shadows) ;

[259](class_light.md) void [SetIntensity](class_light.md)(float intensity) ;

[260](class_light.md) void [SetLength](class_light.md)(float length) ;

[261](class_light.md) float [GetFOV](class_light.md)() ;

[262](class_light.md) float [GetRange](class_light.md)() ;

[263](class_light.md) float [GetScattering](class_light.md)() ;

[264](class_light.md) void [GetColor](class_light.md)(int& out r, int& out g, int& out b) ;

[265](class_light.md) bool [GetCastShadows](class_light.md)() ;

[266](class_light.md) float [GetIntensity](class_light.md)() ;

[267](class_light.md) float [GetLength](class_light.md)() ;

[268](class_light.md) void [SetAttach](class_light.md)([Player](class_player.md) player) ;

[269](class_light.md) [Player](class_player.md) [GetAttach](class_light.md)() ;

[270](class_light.md) void [SetRoom](class_light.md)([Room](class_room.md)) ;

[271](class_light.md) [Room](class_room.md) [GetRoom](class_light.md)() ;

[272](class_light.md) [Entity](class_entity.md) [GetEntity](class_light.md)() ;

[273](class_light.md) [Entity](class_entity.md) [GetLight](class_light.md)() ;

[274](class_light.md) void [SetMovement](class_light.md)(float speed, float maxdistance) ;

[275](class_light.md) void [Remove](class_light.md)() ;

276};

[250](class_light.md)class [Light](class_light.md) {[…](javascript:codefold.toggle('00250'))};

[277](class_model_preset.md)class [ModelPreset](class_model_preset.md)

278{

279public:

280 const string& headbone;

281 const string& spinebone;

282 const string& handbone;

283 const string& forearmbone;

284 const int maximumspinepitch;

285 const int maximumspinepitchdist;

286 const int maximumheadpitch;

287 const int fixedspinerotation;

288 const bool usedefaultrolls;

289 const float offsetyaw;

290 const float offsety;

291 const float collisionradius;

292 const float scale;

293 const string& stepsound;

294 const float blobshadowsize;

295 const float forearmholdingpitch;

296 const float forearmholdingyaw;

297 const float forearmholdingroll;

298 const float holdingitemoffsetx;

299 const float holdingitemoffsety;

300 const float holdingitemoffsetz;

301 const float holdingitemoffsetpitch;

302 const float holdingitemoffsetyaw;

303 const float holdingitemoffsetroll;

304 const float hitboxwidth;

305 const float hitboxheight;

306 const float hitboxdepth;

307 const float speed;

308 const float stamina;

309 const string& movesound;

310 const bool disablejump;

311 const int collisiontype;

312 const float viewoffsety;

313 const bool disableroll;

314 const bool disablebloodloss;

315 const bool disableinjuries;

316 const bool flippitch;

317 const bool disableinteractitems;

318 const int rotationmode;

319 const int comparedspinerotation;

320 const int material;

321 const bool constantinvisibility;

322 const float lightradius;

323 const int lightshadows;

324 const int lightr;

325 const int lightg;

326 const int lightb;

327 const float lightscattering;

328};

[277](class_model_preset.md)class [ModelPreset](class_model_preset.md) {[…](javascript:codefold.toggle('00277'))};

[329](class_n_p_c.md)class [NPC](class_n_p_c.md)

330{

331public:

[332](class_n_p_c.md) [Entity](class_entity.md) [GetEntity](class_n_p_c.md)() ;

[333](class_n_p_c.md) [Entity](class_entity.md) [GetModel](class_n_p_c.md)() ;

[334](class_n_p_c.md) void [SetPickable](class_n_p_c.md)(bool pickable) ;

[335](class_n_p_c.md) void [SetDead](class_n_p_c.md)(bool state) ;

[336](class_n_p_c.md) bool [IsDead](class_n_p_c.md)() ;

[337](class_n_p_c.md) void [SetHealth](class_n_p_c.md)(int health) ;

[338](class_n_p_c.md) int [GetHealth](class_n_p_c.md)() ;

[339](class_n_p_c.md) void [SetIdle](class_n_p_c.md)(float state) ;

[340](class_n_p_c.md) void [SetState1](class_n_p_c.md)(float state) ;

[341](class_n_p_c.md) void [SetState2](class_n_p_c.md)(float state) ;

[342](class_n_p_c.md) void [SetState3](class_n_p_c.md)(float state) ;

[343](class_n_p_c.md) float [GetIdle](class_n_p_c.md)() ;

[344](class_n_p_c.md) float [GetState1](class_n_p_c.md)() ;

[345](class_n_p_c.md) float [GetState2](class_n_p_c.md)() ;

[346](class_n_p_c.md) float [GetState3](class_n_p_c.md)() ;

[347](class_n_p_c.md) void [Remove](class_n_p_c.md)() ;

348};

[329](class_n_p_c.md)class [NPC](class_n_p_c.md) {[…](javascript:codefold.toggle('00329'))};

[349](class_object.md)class [Object](class_object.md)

350{

351public:

[352](class_object.md) void [SetAttach](class_object.md)([Player](class_player.md) player) ;

[353](class_object.md) [Player](class_player.md) [GetAttach](class_object.md)() ;

[354](class_object.md) void [SetRoom](class_object.md)([Room](class_room.md)) ;

[355](class_object.md) [Room](class_room.md) [GetRoom](class_object.md)() ;

[356](class_object.md) int [GetIndex](class_object.md)() ;

[357](class_object.md) [Entity](class_entity.md) [GetEntity](class_object.md)() ;

[358](class_object.md) [Entity](class_entity.md) [GetModel](class_object.md)() ;

[359](class_object.md) void [SetMovement](class_object.md)(float speed, float maxdistance) ;

[360](class_object.md) void [SetTexture](class_object.md)(int textureid) ;

[361](class_object.md) void [SetTouchable](class_object.md)(bool val) ;

[362](class_object.md) void [SetClickCallback](class_object.md)(OBJECTCALLBACK@ callback) ;

[363](class_object.md) void [Remove](class_object.md)() ;

364};

[349](class_object.md)class [Object](class_object.md) {[…](javascript:codefold.toggle('00349'))};

[365](class_player.md)class [Player](class_player.md)

366{

367public:

[368](class_player.md) [Entity](class_entity.md) [GetHitbox](class_player.md)() ;

[369](class_player.md) [Entity](class_entity.md) [GetHead](class_player.md)() ;

[370](class_player.md) [Entity](class_entity.md) [GetEntity](class_player.md)() ;

[371](class_player.md) void [GetScreenSize](class_player.md)(int& out width, int& out height) ;

[372](class_player.md) string& [GetLanguage](class_player.md)() ;

[373](class_player.md) string& [GetIP](class_player.md)() ;

[374](class_player.md) string& [GetSteamID](class_player.md)() ;

[375](class_player.md) string& [GetHWID](class_player.md)(int wmid = 0) ;

[376](class_player.md) string& [GetName](class_player.md)() ;

[377](class_player.md) void [SetSteamID](class_player.md)(string &in steamid64) ;

[378](class_player.md) void [SetName](class_player.md)(string &in name) ;

[379](class_player.md) int [GetPing](class_player.md)() ;

[380](class_player.md) int [GetTime](class_player.md)() ;

[381](class_player.md) int [GetIndex](class_player.md)() ;

[382](class_player.md) string& [GetVersion](class_player.md)() ;

[383](class_player.md) bool [IsInvisible](class_player.md)() ;

[384](class_player.md) bool [IsInvisibleForPlayer](class_player.md)([Player](class_player.md) player) ;

[385](class_player.md) void [SetInvisible](class_player.md)(bool inv) ;

[386](class_player.md) void [SetLocalInvisible](class_player.md)([Player](class_player.md) player, bool inv) ;

[387](class_player.md) void [Kick](class_player.md)(int code = 0, string& in custom = "") ;

[388](class_player.md) void [ShowDialog](class_player.md)(int type, int index, string& in header, string& in message, string& in leftbutton, string& in rightbutton = "", bool align = true) ;

[389](class_player.md) void [ShowDialog](class_player.md)(int type, DIALOGCALLBACK@ callback, string& in header, string& in message, string& in leftbutton, string& in rightbutton = "", bool align = true) ;

[390](class_player.md) void [SetDialogData](class_player.md)(string& in data) ;

[391](class_player.md) string& [GetDialogData](class_player.md)() ;

[392](class_player.md) void [HideDialog](class_player.md)() ;

[393](class_player.md) void [SendMessage](class_player.md)(string& in message, float time = 6.0, bool localized = false) ;

[394](class_player.md) void [Desync](class_player.md)(bool value) ;

[395](class_player.md) bool [IsDesync](class_player.md)() ;

[396](class_player.md) void [SetSpectatePlayer](class_player.md)([Player](class_player.md) target) ;

[397](class_player.md) void [SetSpectateMode](class_player.md)(int mode) ;

[398](class_player.md) [Player](class_player.md) [GetSpectatePlayer](class_player.md)() ;

[399](class_player.md) int [GetSpectateMode](class_player.md)() ;

[400](class_player.md) bool [Kill](class_player.md)(bool bloody = false, bool createcorpse = true) ;

[401](class_player.md) bool [Respawn](class_player.md)() ;

[402](class_player.md) bool [IsDead](class_player.md)() ;

[403](class_player.md) void [SetInjuries](class_player.md)(float val) ;

[404](class_player.md) float [GetInjuries](class_player.md)() ;

[405](class_player.md) void [SetBloodloss](class_player.md)(float val) ;

[406](class_player.md) float [GetBloodloss](class_player.md)() ;

[407](class_player.md) bool [GetGodmode](class_player.md)() ;

[408](class_player.md) void [SetGodmode](class_player.md)(bool val) ;

[409](class_player.md) void [SetColor](class_player.md)(uint hx) ;

[410](class_player.md) uint [GetColor](class_player.md)() ;

[411](class_player.md) void [GetNetworkPosition](class_player.md)(float& out x, float& out y, float& out z) ;

[412](class_player.md) void [GetNetworkRotation](class_player.md)(float& out pitch, float& out yaw) ;

[413](class_player.md) void [SetNetworkPosition](class_player.md)(float x, float y, float z) ;

[414](class_player.md) void [SetNetworkRotation](class_player.md)(float pitch, float yaw) ;

[415](class_player.md) void [SetPosition](class_player.md)(float x, float y, float z, [Room](class_room.md) room = NULL, bool updatepivot = true) ;

[416](class_player.md) void [SetRotation](class_player.md)(float pitch, float yaw) ;

[417](class_player.md) void [Teleport](class_player.md)([Room](class_room.md) room, float x, float y, float z, bool updatepivot = true) ;

[418](class_player.md) void [SetRoom](class_player.md)([Room](class_room.md) room) ;

[419](class_player.md) [Room](class_room.md) [GetRoom](class_player.md)() ;

[420](class_player.md) void [SetPositionBounds](class_player.md)([Room](class_room.md) room, float x = 0.0, float y = 0.0, float z = 0.0, float distance = 0.0) ;

[421](class_player.md) void [Explode](class_player.md)(bool thrust = false) ;

[422](class_player.md) void [MovePlayer](class_player.md)(float speedmult, float angle) ;

[423](class_player.md) void [IgnoreProximity](class_player.md)(bool value) ;

[424](class_player.md) void [SendDamage](class_player.md)([Player](class_player.md) player, float force, bool headshot, float offsetx, float offsety, float offsetz) ;

[425](class_player.md) void [SetAdmin](class_player.md)(bool val) ;

[426](class_player.md) bool [IsAdmin](class_player.md)() ;

[427](class_player.md) void [SetGlobalTransmission](class_player.md)(bool val) ;

[428](class_player.md) bool [IsGlobalTransmission](class_player.md)() ;

[429](class_player.md) bool [SendVoice](class_player.md)(int bank, int radio = 0, bool global = false, [Player](class_player.md) target = NULL) ;

[430](class_player.md) int [GetItemsCount](class_player.md)() ;

[431](class_player.md) [Items](class_items.md) [GetInventory](class_player.md)(int) ;

[432](class_player.md) [Items](class_items.md) [GetSelectedItem](class_player.md)() ;

[433](class_player.md) float [GetBlinkTimer](class_player.md)() ;

[434](class_player.md) void [SetBlinkTimer](class_player.md)(float time) ;

[435](class_player.md) bool [IsBlinking](class_player.md)() ;

[436](class_player.md) void [SetBlinkEffect](class_player.md)(float effectvalue, float time) ;

[437](class_player.md) void [GetBlinkEffect](class_player.md)(float &out effectvalue, float &out time) ;

[438](class_player.md) void [EnableBlinking](class_player.md)(bool blink) ;

[439](class_player.md) bool [IsBlinkingEnabled](class_player.md)() ;

[440](class_player.md) int [GetRadio](class_player.md)() ;

[441](class_player.md) void [PlayAnimation](class_player.md)(int animid) ;

[442](class_player.md) void [SetNetworkAnimation](class_player.md)(int animid) ;

[443](class_player.md) void [SetAnimation](class_player.md)(int animid) ;

[444](class_player.md) int [GetAnimation](class_player.md)() ;

[445](class_player.md) void [SetSpeedMultiplier](class_player.md)(float multiplier) ;

[446](class_player.md) void [SetStaminaMultiplier](class_player.md)(float multiplier) ;

[447](class_player.md) float [GetSpeedMultiplier](class_player.md)() ;

[448](class_player.md) float [GetStaminaMultiplier](class_player.md)() ;

[449](class_player.md) void [SetAttach](class_player.md)(int bodyindex, int attachmodelindex, [Items](class_items.md) item = NULL) ;

[450](class_player.md) int [GetAttach](class_player.md)(int bodyindex) ;

[451](class_player.md) [Items](class_items.md) [GetAttachItem](class_player.md)(int bodyindex) ;

[452](class_player.md) int [GetModel](class_player.md)() ;

[453](class_player.md) void [SetModel](class_player.md)(int modelid, int textureid = -1) ;

[454](class_player.md) void [SetModelSize](class_player.md)(float) ;

[455](class_player.md) float [GetModelSize](class_player.md)() ;

[456](class_player.md) void [SetModelTexture](class_player.md)(int textureid) ;

[457](class_player.md) int [GetModelTexture](class_player.md)() ;

[458](class_player.md) void [SetCollisionRadius](class_player.md)(float) ;

[459](class_player.md) float [GetCollisionRadius](class_player.md)() ;

[460](class_player.md) float [GetVolume](class_player.md)() ;

[461](class_player.md) bool [IsCrouch](class_player.md)() ;

[462](class_player.md) void [SetGravity](class_player.md)(float multiplier) ;

[463](class_player.md) float [GetGravity](class_player.md)() ;

[464](class_player.md) void [SetTagText](class_player.md)(int index, string& in) ;

[465](class_player.md) void [SetTagScales](class_player.md)(int index, float, float) ;

[466](class_player.md) void [SetTagOffset](class_player.md)(int index, float) ;

[467](class_player.md) void [SetTagColors](class_player.md)(int index, int, int) ;

[468](class_player.md) void [SetTagFont](class_player.md)(int index, string& in) ;

[469](class_player.md) string& [GetTagText](class_player.md)(int index) ;

[470](class_player.md) void [GetTagScales](class_player.md)(int index, float&out scalex, float&out scaley) ;

[471](class_player.md) float [GetTagOffset](class_player.md)(int index) ;

[472](class_player.md) void [GetTagColors](class_player.md)(int index, uint&out start, uint&out end) ;

[473](class_player.md) string& [GetTagFont](class_player.md)(int index) ;

[474](class_player.md) int [GetShootsCount](class_player.md)() ;

[475](class_player.md) void [SetShootsCount](class_player.md)(int count) ;

[476](class_player.md) void [RedirectMove](class_player.md)(bool move) ;

[477](class_player.md) bool [IsBot](class_player.md)() ;

[478](class_player.md) bool [IsAiming](class_player.md)() ;

[479](class_player.md) void [SetWearData](class_player.md)(int bodyindex, [Items](class_items.md) item) ;

[480](class_player.md) void [Console](class_player.md)(string& in message) ;

[481](class_player.md) bool [GetKeyState](class_player.md)(int keytype) ;

482 void GetTeleportData(float&out x, float&out y, float&out z, [Room](class_room.md)&out room, int&out tick) /\* Get latest SetPosition data \*/;

483};

[365](class_player.md)class [Player](class_player.md) {[…](javascript:codefold.toggle('00365'))};

[484](class_room.md)class [Room](class_room.md)

485{

486public:

[487](class_room.md) string& [GetName](class_room.md)() ;

[488](class_room.md) int [GetIndex](class_room.md)() ;

[489](class_room.md) int [GetIdentifier](class_room.md)() ;

[490](class_room.md) [Entity](class_entity.md) [GetEntity](class_room.md)() ;

[491](class_room.md) [Entity](class_entity.md) [GetObject](class_room.md)(int index) ;

[492](class_room.md) [Entity](class_entity.md) [GetLever](class_room.md)(int index) ;

[493](class_room.md) bool [IsAdjacent](class_room.md)([Room](class_room.md)) ;

[494](class_room.md) [Room](class_room.md) [GetAdjacentRoom](class_room.md)(int index) ;

[495](class_room.md) [Door](class_door.md) [GetAdjacentDoor](class_room.md)(int index) ;

[496](class_room.md) [Door](class_door.md) [GetDoor](class_room.md)(int) ;

[497](class_room.md) bool [IsInside](class_room.md)([Entity](class_entity.md)) ;

498};

[484](class_room.md)class [Room](class_room.md) {[…](javascript:codefold.toggle('00484'))};

[499](class_server.md)class [Server](class_server.md)

500{

501public:

[502](class_server.md) void [Restart](class_server.md)() ;

[503](class_server.md) void [Console](class_server.md)(string& in) ;

[504](class_server.md) string& [GetVersion](class_server.md)() ;

[505](class_server.md) void [AddVersion](class_server.md)(string& in version) ;

[506](class_server.md) void [RemoveVersion](class_server.md)(string& in version) ;

[507](class_server.md) int [GetUPS](class_server.md)() ;

[508](class_server.md) [Config](class_config.md) [ParseConfig](class_server.md)(string& in filename) ;

[509](class_server.md) string& [hostname](class_server.md);

[510](class_server.md) int [port](class_server.md);

[511](class_server.md) int [corpsealivetime](class_server.md);

[512](class_server.md) int [timeout](class_server.md);

[513](class_server.md) bool [chat](class_server.md);

[514](class_server.md) bool [console](class_server.md);

[515](class_server.md) int [voicebitrate](class_server.md);

[516](class_server.md) int [maxplayers](class_server.md);

[517](class_server.md) string& [mapseed](class_server.md);

[518](class_server.md) string& [adminpassword](class_server.md);

[519](class_server.md) int [difficulty](class_server.md);

[520](class_server.md) string& [gamemode](class_server.md);

[521](class_server.md) int [emptybehaviour](class_server.md);

[522](class_server.md) bool [scriptsautoload](class_server.md);

[523](class_server.md) bool [disablenpcs](class_server.md);

[524](class_server.md) float [proximityplayers](class_server.md);

[525](class_server.md) float [mapbounds](class_server.md);

[526](class_server.md) int [respawntime](class_server.md);

[527](class_server.md) string& [contenturl](class_server.md);

[528](class_server.md) string& [password](class_server.md);

[529](class_server.md) bool [improvedgates](class_server.md);

[530](class_server.md) int [mapsize](class_server.md);

[531](class_server.md) bool [allowjump](class_server.md);

[532](class_server.md) string& [description](class_server.md);

[533](class_server.md) bool [fastslots](class_server.md);

[534](class_server.md) float [gravity](class_server.md);

[535](class_server.md) int [holiday](class_server.md);

[536](class_server.md) string& [addonsfile](class_server.md);

[537](class_server.md) bool [enablehud](class_server.md);

[538](class_server.md) int [max\_items](class_server.md);

[539](class_server.md) int [max\_objects](class_server.md);

[540](class_server.md) int [max\_corpses](class_server.md);

[541](class_server.md) int [max\_lights](class_server.md);

[542](class_server.md) bool [player\_culling](class_server.md);

[543](class_server.md) bool [steam\_auth](class_server.md);

[544](class_server.md) bool [fall\_damage](class_server.md);

545};

[499](class_server.md)class [Server](class_server.md) {[…](javascript:codefold.toggle('00499'))};

[546](class_shell.md)class [Shell](class_shell.md)

547{

548public:

549 [Entity](class_entity.md) GetEntity();

[550](class_shell.md) int [GetIndex](class_shell.md)() ;

[551](class_shell.md) void [GetVelocity](class_shell.md)(float& out x, float& out y, float& out z) ;

[552](class_shell.md) string& [GetActionEmitter](class_shell.md)() ;

[553](class_shell.md) int [GetEmitter](class_shell.md)() ;

[554](class_shell.md) string& [GetActionSound](class_shell.md)() ;

[555](class_shell.md) string& [GetCollisionSound](class_shell.md)() ;

[556](class_shell.md) string& [GetSound](class_shell.md)() ;

[557](class_shell.md) float [GetSpeed](class_shell.md)() ;

[558](class_shell.md) float [GetForce](class_shell.md)() ;

[559](class_shell.md) float [GetRestitution](class_shell.md)() ;

[560](class_shell.md) float [GetGravity](class_shell.md)() ;

[561](class_shell.md) float [GetCollisionRadius](class_shell.md)() ;

[562](class_shell.md) float [GetDamage](class_shell.md)() ;

[563](class_shell.md) float [GetTimeout](class_shell.md)() ;

[564](class_shell.md) float [GetImpactTime](class_shell.md)() ;

[565](class_shell.md) int [GetAction](class_shell.md)() ;

[566](class_shell.md) float [GetActionRadius](class_shell.md)() ;

[567](class_shell.md) bool [IsSticky](class_shell.md)() ;

[568](class_shell.md) uint [GetStickFlags](class_shell.md)() ;

[569](class_shell.md) int [GetStickIndex](class_shell.md)() ;

[570](class_shell.md) int [GetWeapon](class_shell.md)() ;

[571](class_shell.md) [Player](class_player.md) [GetShooter](class_shell.md)() ;

[572](class_shell.md) void [Unstick](class_shell.md)() ;

[573](class_shell.md) void [SetSticky](class_shell.md)(bool sticky) ;

[574](class_shell.md) void [SetVelocity](class_shell.md)(float x, float y, float z) ;

[575](class_shell.md) void [SetActionEmitter](class_shell.md)(string& in emitters) ;

[576](class_shell.md) void [SetEmitter](class_shell.md)(int id) ;

[577](class_shell.md) void [SetActionSound](class_shell.md)(string& in sound) ;

[578](class_shell.md) void [SetCollisionSound](class_shell.md)(string& in sound) ;

[579](class_shell.md) void [SetSound](class_shell.md)(string& in sound) ;

[580](class_shell.md) void [SetSpeed](class_shell.md)(float speed) ;

[581](class_shell.md) void [SetForce](class_shell.md)(float force) ;

[582](class_shell.md) void [SetRestitution](class_shell.md)(float restitution) ;

[583](class_shell.md) void [SetGravity](class_shell.md)(float gravity) ;

[584](class_shell.md) void [SetCollisionRadius](class_shell.md)(float radius) ;

[585](class_shell.md) void [SetTimeout](class_shell.md)(float time) ;

[586](class_shell.md) void [SetImpactTime](class_shell.md)(float time) ;

[587](class_shell.md) void [SetDamage](class_shell.md)(float damage) ;

[588](class_shell.md) void [SetAction](class_shell.md)(int action) ;

[589](class_shell.md) void [SetActionRadius](class_shell.md)(float radius) ;

[590](class_shell.md) void [SetShooter](class_shell.md)([Player](class_player.md) player) ;

[591](class_shell.md) void [Remove](class_shell.md)(bool action = false) ;

592};

[546](class_shell.md)class [Shell](class_shell.md) {[…](javascript:codefold.toggle('00546'))};

[593](class_sound.md)class [Sound](class_sound.md)

594{

595public:

[596](class_sound.md) void [SetVolume](class_sound.md)(float vol) ;

[597](class_sound.md) void [Seek](class_sound.md)(float time) ;

[598](class_sound.md) void [Stop](class_sound.md)() ;

599};

[593](class_sound.md)class [Sound](class_sound.md) {[…](javascript:codefold.toggle('00593'))};

[600](class_world.md)class [World](class_world.md)

601{

602public:

[603](class_world.md) void [CreateDecal](class_world.md)(int decalid, float x, float y, float z, float pitch, float yaw, float roll, [Room](class_room.md) room = NULL, float lifetime = 1.0f, float alpha = 1.0f, float size = 1.0f, float sizechange = 0.0f, float maxsize = 1.0f, float alphachange = 0.0f, int r = 0, int g = 0, int b = 0, float timer = 0.0) ;

[604](class_world.md) void [CreateEmitter](class_world.md)([Player](class_player.md) target, int id, float x, float y, float z) ;

[605](class_world.md) void [CreateEmitter](class_world.md)([Player](class_player.md) target, int id, float x, float y, float z, [Player](class_player.md) attachPlayer) ;

[606](class_world.md) void [CreateEmitter](class_world.md)([Player](class_player.md) target, int id, float x, float y, float z, [Object](class_object.md) attachObject) ;

[607](class_world.md) int [GetZone](class_world.md)(float x, float y, float z) ;

[608](class_world.md) [Player](class_player.md) [CreateBot](class_world.md)(string& in) ;

[609](class_world.md) void [RaycastItems](class_world.md)() ;

[610](class_world.md) [Items](class_items.md) [GetItem](class_world.md)(int index) ;

[611](class_world.md) [Items](class_items.md) [CreateItem](class_world.md)(string& in templatename, bool collision = true, float x = 0, float y = 0, float z = 0, int r = 0, int g = 0, int b = 0, float alpha = 1.0, int invslots = 0) ;

[612](class_world.md) [Items](class_items.md) [CreateItem](class_world.md)(int templateindex, bool collision = true, float x = 0, float y = 0, float z = 0, int r = 0, int g = 0, int b = 0, float alpha = 1.0, int invslots = 0) ;

[613](class_world.md) [Room](class_room.md) [GetRoomByName](class_world.md)(string& in) ;

[614](class_world.md) [Room](class_room.md) [GetRoomByIndex](class_world.md)(int) ;

[615](class_world.md) [Room](class_room.md) [GetRoomByIdentifier](class_world.md)(int) ;

[616](class_world.md) [Corpse](class_corpse.md) [GetCorpse](class_world.md)(int index) ;

[617](class_world.md) [Door](class_door.md) [GetDoor](class_world.md)(int) ;

[618](class_world.md) [Event](class_event.md) [GetEvent](class_world.md)(int index) ;

[619](class_world.md) [Event](class_event.md) [GetEventByIdentifier](class_world.md)(int index) ;

[620](class_world.md) [Object](class_object.md) [CreateObject](class_world.md)(int objectid, [Room](class_room.md) room = NULL, bool animated = false) ;

[621](class_world.md) [Object](class_object.md) [GetObject](class_world.md)(int index) ;

[622](class_world.md) [Light](class_light.md) [CreateLight](class_world.md)(int type, float range = 10.0, [Room](class_room.md) room = NULL) ;

[623](class_world.md) [NPC](class_n_p_c.md) [CreateNPC](class_world.md)(int npctype, float x, float y, float z) ;

[624](class_world.md) [NPC](class_n_p_c.md) [GetNPC](class_world.md)(int index) ;

625 [ModelPreset](class_model_preset.md) GetModelPreset(int modelid) /\* Get model data by modelid \*/;

[626](class_world.md) [Shell](class_shell.md) [CreateShell](class_world.md)(int weaponid, [Player](class_player.md) shooter = NULL) ;

627};

[600](class_world.md)class [World](class_world.md) {[…](javascript:codefold.toggle('00600'))};

[Audio](class_audio.md)

**Definition** all.h:2

[Audio::Play3DSound](class_audio.md)

Sound Play3DSound(string &in filenameorurl, Entity entity, float range, float volume, bool norange=false)

[Audio::Play3DSoundForPlayer](class_audio.md)

Sound Play3DSoundForPlayer(Player player, string &in filenameorurl, Entity entity, float range, float volume, bool norange=false)

[Audio::PlaySoundForPlayer](class_audio.md)

Sound PlaySoundForPlayer(Player player, string &in filenameorurl)

[Audio::PlaySound](class_audio.md)

Sound PlaySound(string &in filenameorurl)

[Audio::Play3DSound](class_audio.md)

Sound Play3DSound(string &in filenameorurl, Player player, float range, float volume, bool norange=false)

[Audio::Play3DSoundForPlayer](class_audio.md)

Sound Play3DSoundForPlayer(Player player, string &in filenameorurl, Player player, float range, float volume, bool norange=false)

[Audio::Play3DSound](class_audio.md)

Sound Play3DSound(string &in filenameorurl, float x, float y, float z, float range, float volume, bool norange=false)

[Audio::Play3DSoundForPlayer](class_audio.md)

Sound Play3DSoundForPlayer(Player player, string &in filenameorurl, float x, float y, float z, float range, float volume, bool norange=false)

[Config](class_config.md)

**Definition** all.h:20

[Config::Exist](class_config.md)

bool Exist(string &in key, int index=0)

[Config::Get](class_config.md)

string & Get(string &in key, int index=0)

[Config::Remove](class_config.md)

void Remove()

[Connection](class_connection.md)

**Definition** all.h:27

[Connection::Accept](class_connection.md)

void Accept()

[Connection::Join](class_connection.md)

bool Join()

[Connection::GetPort](class_connection.md)

int GetPort()

[Connection::GetHWID](class_connection.md)

string & GetHWID(int wmid=0)

[Connection::GetSteamID](class_connection.md)

string & GetSteamID()

[Connection::Cancel](class_connection.md)

void Cancel(int code)

[Connection::GetIP](class_connection.md)

string & GetIP()

[Connection::GetLanguage](class_connection.md)

string & GetLanguage()

[Connection::GetQueue](class_connection.md)

int GetQueue()

[Connection::Cancel](class_connection.md)

void Cancel(string &in custom="")

[Connection::Remove](class_connection.md)

void Remove()

[Corpse](class_corpse.md)

**Definition** all.h:42

[Corpse::IsExplored](class_corpse.md)

bool IsExplored()

[Corpse::SetData](class_corpse.md)

void SetData(string &in data)

[Corpse::SetTimeout](class_corpse.md)

void SetTimeout(float)

[Corpse::GetTimeout](class_corpse.md)

float GetTimeout()

[Corpse::GetData](class_corpse.md)

string & GetData()

[Corpse::GetEntity](class_corpse.md)

Entity GetEntity()

[Corpse::GetItemsCount](class_corpse.md)

int GetItemsCount()

[Corpse::Remove](class_corpse.md)

void Remove()

[Corpse::PushItem](class_corpse.md)

bool PushItem(Items)

[Corpse::Explore](class_corpse.md)

bool Explore()

[Corpse::GetItem](class_corpse.md)

Items GetItem(int slot)

[Corpse::SetExplore](class_corpse.md)

void SetExplore(bool explore)

[Corpse::GetPlayer](class_corpse.md)

Player GetPlayer()

[Corpse::ExploreItem](class_corpse.md)

bool ExploreItem(int slot)

[Corpse::GetModel](class_corpse.md)

int GetModel()

[Corpse::GetIndex](class_corpse.md)

int GetIndex()

[Door](class_door.md)

**Definition** all.h:62

[Door::GetOpenState](class_door.md)

float GetOpenState()

[Door::SetOpen](class_door.md)

void SetOpen(bool)

[Door::Decompose](class_door.md)

void Decompose()

[Door::GetDoorType](class_door.md)

int GetDoorType()

[Door::GetKeycard](class_door.md)

int GetKeycard()

[Door::GetButton](class_door.md)

Entity GetButton(int index)

[Door::IsOpened](class_door.md)

bool IsOpened()

[Door::GetDoorAccess](class_door.md)

int GetDoorAccess()

[Door::Use](class_door.md)

void Use()

[Door::GetEntity](class_door.md)

Entity GetEntity()

[Door::GetLockState](class_door.md)

int GetLockState()

[Door::BreakDoor](class_door.md)

bool BreakDoor(float x, float y, float z)

[Door::GetIndex](class_door.md)

int GetIndex()

[Door::IsBreak](class_door.md)

bool IsBreak()

[Door::SetKeycard](class_door.md)

void SetKeycard(int)

[Door::SetLockState](class_door.md)

void SetLockState(int)

[Entity](class_entity.md)

**Definition** all.h:82

[Entity::CollisionTime](class_entity.md)

float CollisionTime(int index) const

[Entity::GetType](class_entity.md)

int GetType() const

[Entity::Yaw](class_entity.md)

float Yaw(bool global=false, float tween=1.0)

[Entity::Collided](class_entity.md)

bool Collided(int colltype)

[Entity::SetAngularDamping](class_entity.md)

void SetAngularDamping(float damping)

[Entity::CollisionY](class_entity.md)

float CollisionY(int index)

[Entity::DistanceSquared](class_entity.md)

float DistanceSquared(Entity target)

[Entity::ClearForces](class_entity.md)

void ClearForces()

[Entity::Impulse](class_entity.md)

void Impulse(float x, float y, float z)

[Entity::Translate](class_entity.md)

void Translate(float x, float y, float z, bool global=false)

[Entity::IsFreezed](class_entity.md)

bool IsFreezed() const

[Entity::Reset](class_entity.md)

void Reset()

[Entity::CollisionNY](class_entity.md)

float CollisionNY(int index)

[Entity::CollisionImpulse](class_entity.md)

float CollisionImpulse(int index) const

[Entity::PositionX](class_entity.md)

float PositionX(bool global=false, float tween=1.0)

[Entity::Pitch](class_entity.md)

float Pitch(bool global=false, float tween=1.0)

[Entity::CollisionTriangle](class_entity.md)

int CollisionTriangle(int index) const

[Entity::PositionZ](class_entity.md)

float PositionZ(bool global=false, float tween=1.0)

[Entity::Distance](class_entity.md)

float Distance(Entity target)

[Entity::SetRestitution](class_entity.md)

void SetRestitution(float res)

[Entity::SetAngularVelocity](class_entity.md)

void SetAngularVelocity(float x, float y, float z)

[Entity::ScaleZ](class_entity.md)

float ScaleZ(bool global=false, float tween=1.0)

[Entity::CollisionEntity](class_entity.md)

Entity CollisionEntity(int index) const

[Entity::SetPhysics](class_entity.md)

void SetPhysics(bool enable)

[Entity::Freeze](class_entity.md)

void Freeze(bool enable)

[Entity::IsActive](class_entity.md)

bool IsActive() const

[Entity::Point](class_entity.md)

float Point(Entity target, float roll=0.0)

[Entity::SetRollFriction](class_entity.md)

void SetRollFriction(float friction)

[Entity::Remove](class_entity.md)

void Remove()

[Entity::CollisionNX](class_entity.md)

float CollisionNX(int index)

[Entity::SetRotation](class_entity.md)

void SetRotation(float pitch, float yaw, float roll, bool global=false)

[Entity::SetGravity](class_entity.md)

void SetGravity(float factor)

[Entity::Roll](class_entity.md)

float Roll(bool global=false, float tween=1.0)

[Entity::CollisionX](class_entity.md)

float CollisionX(int index)

[Entity::CollisionNZ](class_entity.md)

float CollisionNZ(int index)

[Entity::CountChildren](class_entity.md)

int CountChildren()

[Entity::Show](class_entity.md)

void Show()

[Entity::SetParent](class_entity.md)

void SetParent(Entity target, bool retain=true)

[Entity::SetAnimTime](class_entity.md)

void SetAnimTime(float time, int sequence=0)

[Entity::SetConstraint](class_entity.md)

void SetConstraint(float normalAngle, float planeAngle, float twistMinAngle, float twistMaxAngle, float torqueFriction)

[Entity::GetParent](class_entity.md)

Entity GetParent()

[Entity::SetKinematic](class_entity.md)

void SetKinematic(bool enable)

[Entity::SetMass](class_entity.md)

void SetMass(float mass)

[Entity::Turn](class_entity.md)

float Turn(float pitch, float yaw, float roll, bool global=false)

[Entity::CountCollisions](class_entity.md)

int CountCollisions()

[Entity::SetLinearCast](class_entity.md)

void SetLinearCast(bool enable)

[Entity::Torque](class_entity.md)

void Torque(float x, float y, float z)

[Entity::SetPosition](class_entity.md)

void SetPosition(float x, float y, float z, bool global=false)

[Entity::SetRadius](class_entity.md)

void SetRadius(float x, float y=0.0)

[Entity::SetLinearDamping](class_entity.md)

void SetLinearDamping(float damping)

[Entity::Move](class_entity.md)

void Move(float x, float y, float z, bool global=false)

[Entity::GetName](class_entity.md)

string & GetName()

[Entity::ScaleX](class_entity.md)

float ScaleX(bool global=false, float tween=1.0)

[Entity::Hide](class_entity.md)

void Hide()

[Entity::GetAngularVelocity](class_entity.md)

void GetAngularVelocity(float &out x, float &out y, float &out z) const

[Entity::CollisionZ](class_entity.md)

float CollisionZ(int index)

[Entity::SetPickMode](class_entity.md)

void SetPickMode(int pickmode, bool obscurer=false)

[Entity::SetBox](class_entity.md)

void SetBox(float x, float y, float z, float w, float h, float d)

[Entity::Visible](class_entity.md)

bool Visible(Entity target, float radius=0.0f)

[Entity::GetLinearVelocity](class_entity.md)

void GetLinearVelocity(float &out x, float &out y, float &out z) const

[Entity::Pick](class_entity.md)

Entity Pick(float distance)

[Entity::SetAngularFactor](class_entity.md)

void SetAngularFactor(float x, float y, float z)

[Entity::SetScale](class_entity.md)

void SetScale(float x, float y, float z, bool global=false)

[Entity::GetShape](class_entity.md)

int GetShape(float &out x, float &out y, float &out z, float &out width, float &out height, float &out depth) const

[Entity::SetCylinder](class_entity.md)

void SetCylinder(float x\_radius, float y\_radius=0.0)

[Entity::ScaleY](class_entity.md)

float ScaleY(bool global=false, float tween=1.0)

[Entity::SetType](class_entity.md)

void SetType(int colltype, bool recursive=false)

[Entity::SetFriction](class_entity.md)

void SetFriction(float friction)

[Entity::GetAnimTime](class_entity.md)

float GetAnimTime()

[Entity::CollisionDistance](class_entity.md)

float CollisionDistance(int index) const

[Entity::InView](class_entity.md)

bool InView(Entity target)

[Entity::PositionY](class_entity.md)

float PositionY(bool global=false, float tween=1.0)

[Entity::Activate](class_entity.md)

void Activate(bool enable)

[Entity::GetChild](class_entity.md)

Entity GetChild(int)

[Entity::SetLinearVelocity](class_entity.md)

void SetLinearVelocity(float x, float y, float z)

[Entity::Sleep](class_entity.md)

void Sleep(bool enable)

[Entity::SetName](class_entity.md)

void SetName(string &in name)

[Entity::SetCenter](class_entity.md)

void SetCenter(float x, float y, float z)

[Entity::SetLinearFactor](class_entity.md)

void SetLinearFactor(float x, float y, float z)

[Event](class_event.md)

**Definition** all.h:165

[Event::GetState3](class_event.md)

float GetState3()

[Event::SetState2](class_event.md)

float SetState2(float state)

[Event::GetIdentifier](class_event.md)

int GetIdentifier()

[Event::SetState3](class_event.md)

float SetState3(float state)

[Event::GetState2](class_event.md)

float GetState2()

[Event::SetState](class_event.md)

float SetState(float state)

[Event::SetState4](class_event.md)

float SetState4(float state)

[Event::GetState](class_event.md)

float GetState()

[Event::GetState4](class_event.md)

float GetState4()

[Event::GetRoom](class_event.md)

Room GetRoom()

[Event::GetIndex](class_event.md)

int GetIndex()

[Event::Remove](class_event.md)

void Remove()

[GUIElement](class_g_u_i_element.md)

**Definition** all.h:181

[GUIElement::GetData](class_g_u_i_element.md)

string & GetData()

[GUIElement::SetAttach](class_g_u_i_element.md)

void SetAttach(bool enable, float x=0.0, float y=0.0, float z=0.0)

[GUIElement::SetCallback](class_g_u_i_element.md)

void SetCallback(string &in funcname)

[GUIElement::GetAttach](class_g_u_i_element.md)

bool GetAttach(float &out x, float &out y, float &out z)

[GUIElement::SetOpacity](class_g_u_i_element.md)

void SetOpacity(float target, float lerp)

[GUIElement::IsSelectable](class_g_u_i_element.md)

bool IsSelectable()

[GUIElement::SetData](class_g_u_i_element.md)

void SetData(string &in data)

[GUIElement::SetAttach](class_g_u_i_element.md)

void SetAttach(Player player)

[GUIElement::GetScale](class_g_u_i_element.md)

void GetScale(float &out width, float &out height)

[GUIElement::SetScale](class_g_u_i_element.md)

void SetScale(float width, float height)

[GUIElement::Show](class_g_u_i_element.md)

void Show()

[GUIElement::SetShadow](class_g_u_i_element.md)

void SetShadow(bool shadowed)

[GUIElement::SetRotation](class_g_u_i_element.md)

void SetRotation(int degrees)

[GUIElement::Hide](class_g_u_i_element.md)

void Hide()

[GUIElement::SetTechnique](class_g_u_i_element.md)

void SetTechnique(string &in technique)

[GUIElement::GetRotation](class_g_u_i_element.md)

void GetRotation(int &out degrees)

[GUIElement::SetText](class_g_u_i_element.md)

void SetText(string &in text)

[GUIElement::SetColor](class_g_u_i_element.md)

void SetColor(int r, int g, int b)

[GUIElement::Remove](class_g_u_i_element.md)

void Remove()

[GUIElement::IsHidden](class_g_u_i_element.md)

bool IsHidden()

[GUIElement::SetPosition](class_g_u_i_element.md)

void SetPosition(float x, float y)

[GUIElement::GetPlayer](class_g_u_i_element.md)

Player GetPlayer()

[GUIElement::GetPosition](class_g_u_i_element.md)

void GetPosition(float &out x, float &out y)

[GUIElement::GetAttach](class_g_u_i_element.md)

Player GetAttach()

[GUIElement::SetSelectable](class_g_u_i_element.md)

void SetSelectable(bool selectable)

[GUIElement::SetCallback](class_g_u_i_element.md)

void SetCallback(GUICALLBACK @gc)

[GUIElement::SetAspect](class_g_u_i_element.md)

void SetAspect(bool keep)

[GUIElement::GetText](class_g_u_i_element.md)

string & GetText()

[Graphics](class_graphics.md)

**Definition** all.h:213

[Graphics::CreateImage](class_graphics.md)

GUIElement CreateImage(Player player, string &in filename, float x, float y, float width, float height, bool align=false)

[Graphics::CreateText](class_graphics.md)

GUIElement CreateText(Player player, int fontid, string &in text, float x, float y, bool align=false)

[Graphics::CreateProgressBar](class_graphics.md)

GUIElement CreateProgressBar(Player player, float time, float x, float y, float width, float height, bool align=false)

[Graphics::CreateProgressBar](class_graphics.md)

GUIElement CreateProgressBar(Player player, float time, float x, float y, float width, float height, bool align, ref &in callback)

[Graphics::CreateRect](class_graphics.md)

GUIElement CreateRect(Player player, float x, float y, float width, float height, bool align=false)

[Graphics::CreateProgressBar](class_graphics.md)

GUIElement CreateProgressBar(Player player, float time, float x, float y, float width, float height, bool align, string &in callback)

[Graphics::CreateOval](class_graphics.md)

GUIElement CreateOval(Player player, float x, float y, float width, float height, bool align=false)

[Graphics::CreatePostEffect](class_graphics.md)

GUIElement CreatePostEffect(Player player, string &in filename, string &in defines="")

[Items](class_items.md)

**Definition** all.h:225

[Items::GetSlotItem](class_items.md)

Items GetSlotItem(int)

[Items::GetSlots](class_items.md)

int GetSlots()

[Items::SetState](class_items.md)

void SetState(float state)

[Items::GetState3](class_items.md)

float GetState3()

[Items::SetState2](class_items.md)

void SetState2(float state)

[Items::GetParentItem](class_items.md)

Items GetParentItem()

[Items::IsWeapon](class_items.md)

bool IsWeapon()

[Items::GetIndex](class_items.md)

int GetIndex()

[Items::PushItem](class_items.md)

bool PushItem(Items)

[Items::Remove](class_items.md)

void Remove()

[Items::IsPicked](class_items.md)

bool IsPicked()

[Items::GetName](class_items.md)

string & GetName()

[Items::RemoveSlotItem](class_items.md)

bool RemoveSlotItem(int)

[Items::SetPicker](class_items.md)

bool SetPicker(Player player, float throwforce=0.0)

[Items::GetEntity](class_items.md)

Entity GetEntity()

[Items::GetTemplateName](class_items.md)

string & GetTemplateName()

[Items::GetState](class_items.md)

float GetState()

[Items::GetTemplateIndex](class_items.md)

int GetTemplateIndex()

[Items::GetPicker](class_items.md)

Player GetPicker()

[Items::GetState2](class_items.md)

float GetState2()

[Items::SetState3](class_items.md)

void SetState3(float state)

[Items::Fine](class_items.md)

Items Fine(int)

[Light](class_light.md)

**Definition** all.h:251

[Light::SetIntensity](class_light.md)

void SetIntensity(float intensity)

[Light::GetScattering](class_light.md)

float GetScattering()

[Light::SetLength](class_light.md)

void SetLength(float length)

[Light::SetScattering](class_light.md)

void SetScattering(float scattering)

[Light::GetIntensity](class_light.md)

float GetIntensity()

[Light::GetRange](class_light.md)

float GetRange()

[Light::SetRange](class_light.md)

void SetRange(float range)

[Light::GetRoom](class_light.md)

Room GetRoom()

[Light::GetLight](class_light.md)

Entity GetLight()

[Light::SetCastShadows](class_light.md)

void SetCastShadows(bool shadows)

[Light::GetCastShadows](class_light.md)

bool GetCastShadows()

[Light::SetMovement](class_light.md)

void SetMovement(float speed, float maxdistance)

[Light::SetRoom](class_light.md)

void SetRoom(Room)

[Light::GetFOV](class_light.md)

float GetFOV()

[Light::GetAttach](class_light.md)

Player GetAttach()

[Light::GetIndex](class_light.md)

int GetIndex()

[Light::Remove](class_light.md)

void Remove()

[Light::SetColor](class_light.md)

void SetColor(int r, int g, int b)

[Light::SetFOV](class_light.md)

void SetFOV(float fov)

[Light::GetEntity](class_light.md)

Entity GetEntity()

[Light::SetAttach](class_light.md)

void SetAttach(Player player)

[Light::GetLength](class_light.md)

float GetLength()

[Light::GetColor](class_light.md)

void GetColor(int &out r, int &out g, int &out b)

[ModelPreset](class_model_preset.md)

**Definition** all.h:278

[NPC](class_n_p_c.md)

**Definition** all.h:330

[NPC::GetState2](class_n_p_c.md)

float GetState2()

[NPC::Remove](class_n_p_c.md)

void Remove()

[NPC::GetState3](class_n_p_c.md)

float GetState3()

[NPC::SetState1](class_n_p_c.md)

void SetState1(float state)

[NPC::GetModel](class_n_p_c.md)

Entity GetModel()

[NPC::IsDead](class_n_p_c.md)

bool IsDead()

[NPC::GetIdle](class_n_p_c.md)

float GetIdle()

[NPC::SetIdle](class_n_p_c.md)

void SetIdle(float state)

[NPC::SetState3](class_n_p_c.md)

void SetState3(float state)

[NPC::GetHealth](class_n_p_c.md)

int GetHealth()

[NPC::SetHealth](class_n_p_c.md)

void SetHealth(int health)

[NPC::GetEntity](class_n_p_c.md)

Entity GetEntity()

[NPC::SetPickable](class_n_p_c.md)

void SetPickable(bool pickable)

[NPC::SetDead](class_n_p_c.md)

void SetDead(bool state)

[NPC::SetState2](class_n_p_c.md)

void SetState2(float state)

[NPC::GetState1](class_n_p_c.md)

float GetState1()

[Object](class_object.md)

**Definition** all.h:350

[Object::Remove](class_object.md)

void Remove()

[Object::SetClickCallback](class_object.md)

void SetClickCallback(OBJECTCALLBACK@ callback)

[Object::SetMovement](class_object.md)

void SetMovement(float speed, float maxdistance)

[Object::GetRoom](class_object.md)

Room GetRoom()

[Object::GetIndex](class_object.md)

int GetIndex()

[Object::SetTouchable](class_object.md)

void SetTouchable(bool val)

[Object::GetEntity](class_object.md)

Entity GetEntity()

[Object::SetAttach](class_object.md)

void SetAttach(Player player)

[Object::SetRoom](class_object.md)

void SetRoom(Room)

[Object::GetModel](class_object.md)

Entity GetModel()

[Object::GetAttach](class_object.md)

Player GetAttach()

[Object::SetTexture](class_object.md)

void SetTexture(int textureid)

[Player](class_player.md)

**Definition** all.h:366

[Player::SetSpectatePlayer](class_player.md)

void SetSpectatePlayer(Player target)

[Player::SetCollisionRadius](class_player.md)

void SetCollisionRadius(float)

[Player::GetTagColors](class_player.md)

void GetTagColors(int index, uint &out start, uint &out end)

[Player::GetModel](class_player.md)

int GetModel()

[Player::GetSpectatePlayer](class_player.md)

Player GetSpectatePlayer()

[Player::SetTagText](class_player.md)

void SetTagText(int index, string &in)

[Player::GetStaminaMultiplier](class_player.md)

float GetStaminaMultiplier()

[Player::GetBlinkTimer](class_player.md)

float GetBlinkTimer()

[Player::SendVoice](class_player.md)

bool SendVoice(int bank, int radio=0, bool global=false, Player target=NULL)

[Player::SetBlinkEffect](class_player.md)

void SetBlinkEffect(float effectvalue, float time)

[Player::GetModelSize](class_player.md)

float GetModelSize()

[Player::MovePlayer](class_player.md)

void MovePlayer(float speedmult, float angle)

[Player::IsInvisibleForPlayer](class_player.md)

bool IsInvisibleForPlayer(Player player)

[Player::IsBot](class_player.md)

bool IsBot()

[Player::GetKeyState](class_player.md)

bool GetKeyState(int keytype)

[Player::SetModel](class_player.md)

void SetModel(int modelid, int textureid=-1)

[Player::GetInjuries](class_player.md)

float GetInjuries()

[Player::GetCollisionRadius](class_player.md)

float GetCollisionRadius()

[Player::Respawn](class_player.md)

bool Respawn()

[Player::SetTagOffset](class_player.md)

void SetTagOffset(int index, float)

[Player::GetEntity](class_player.md)

Entity GetEntity()

[Player::SetTagColors](class_player.md)

void SetTagColors(int index, int, int)

[Player::SetAttach](class_player.md)

void SetAttach(int bodyindex, int attachmodelindex, Items item=NULL)

[Player::SetName](class_player.md)

void SetName(string &in name)

[Player::SetShootsCount](class_player.md)

void SetShootsCount(int count)

[Player::IsDesync](class_player.md)

bool IsDesync()

[Player::SetBloodloss](class_player.md)

void SetBloodloss(float val)

[Player::SetInvisible](class_player.md)

void SetInvisible(bool inv)

[Player::SetAdmin](class_player.md)

void SetAdmin(bool val)

[Player::HideDialog](class_player.md)

void HideDialog()

[Player::SetWearData](class_player.md)

void SetWearData(int bodyindex, Items item)

[Player::SetStaminaMultiplier](class_player.md)

void SetStaminaMultiplier(float multiplier)

[Player::SetGodmode](class_player.md)

void SetGodmode(bool val)

[Player::GetIndex](class_player.md)

int GetIndex()

[Player::SetPosition](class_player.md)

void SetPosition(float x, float y, float z, Room room=NULL, bool updatepivot=true)

[Player::Kill](class_player.md)

bool Kill(bool bloody=false, bool createcorpse=true)

[Player::Teleport](class_player.md)

void Teleport(Room room, float x, float y, float z, bool updatepivot=true)

[Player::GetIP](class_player.md)

string & GetIP()

[Player::GetSpeedMultiplier](class_player.md)

float GetSpeedMultiplier()

[Player::SetBlinkTimer](class_player.md)

void SetBlinkTimer(float time)

[Player::SendDamage](class_player.md)

void SendDamage(Player player, float force, bool headshot, float offsetx, float offsety, float offsetz)

[Player::GetTagScales](class_player.md)

void GetTagScales(int index, float &out scalex, float &out scaley)

[Player::SetInjuries](class_player.md)

void SetInjuries(float val)

[Player::GetSteamID](class_player.md)

string & GetSteamID()

[Player::IsBlinkingEnabled](class_player.md)

bool IsBlinkingEnabled()

[Player::SetNetworkPosition](class_player.md)

void SetNetworkPosition(float x, float y, float z)

[Player::SetSpeedMultiplier](class_player.md)

void SetSpeedMultiplier(float multiplier)

[Player::GetHead](class_player.md)

Entity GetHead()

[Player::GetRoom](class_player.md)

Room GetRoom()

[Player::SetAnimation](class_player.md)

void SetAnimation(int animid)

[Player::SetRotation](class_player.md)

void SetRotation(float pitch, float yaw)

[Player::GetTagFont](class_player.md)

string & GetTagFont(int index)

[Player::GetPing](class_player.md)

int GetPing()

[Player::IsDead](class_player.md)

bool IsDead()

[Player::GetInventory](class_player.md)

Items GetInventory(int)

[Player::GetGravity](class_player.md)

float GetGravity()

[Player::GetNetworkRotation](class_player.md)

void GetNetworkRotation(float &out pitch, float &out yaw)

[Player::GetItemsCount](class_player.md)

int GetItemsCount()

[Player::SetSpectateMode](class_player.md)

void SetSpectateMode(int mode)

[Player::Console](class_player.md)

void Console(string &in message)

[Player::GetDialogData](class_player.md)

string & GetDialogData()

[Player::ShowDialog](class_player.md)

void ShowDialog(int type, DIALOGCALLBACK@ callback, string &in header, string &in message, string &in leftbutton, string &in rightbutton="", bool align=true)

[Player::SetRoom](class_player.md)

void SetRoom(Room room)

[Player::SetLocalInvisible](class_player.md)

void SetLocalInvisible(Player player, bool inv)

[Player::IsCrouch](class_player.md)

bool IsCrouch()

[Player::Explode](class_player.md)

void Explode(bool thrust=false)

[Player::SetTagScales](class_player.md)

void SetTagScales(int index, float, float)

[Player::GetVolume](class_player.md)

float GetVolume()

[Player::SetGravity](class_player.md)

void SetGravity(float multiplier)

[Player::SetSteamID](class_player.md)

void SetSteamID(string &in steamid64)

[Player::Desync](class_player.md)

void Desync(bool value)

[Player::GetBlinkEffect](class_player.md)

void GetBlinkEffect(float &out effectvalue, float &out time)

[Player::GetScreenSize](class_player.md)

void GetScreenSize(int &out width, int &out height)

[Player::GetTime](class_player.md)

int GetTime()

[Player::IsBlinking](class_player.md)

bool IsBlinking()

[Player::GetName](class_player.md)

string & GetName()

[Player::IsGlobalTransmission](class_player.md)

bool IsGlobalTransmission()

[Player::GetModelTexture](class_player.md)

int GetModelTexture()

[Player::RedirectMove](class_player.md)

void RedirectMove(bool move)

[Player::GetAttach](class_player.md)

int GetAttach(int bodyindex)

[Player::SetPositionBounds](class_player.md)

void SetPositionBounds(Room room, float x=0.0, float y=0.0, float z=0.0, float distance=0.0)

[Player::GetTagOffset](class_player.md)

float GetTagOffset(int index)

[Player::GetNetworkPosition](class_player.md)

void GetNetworkPosition(float &out x, float &out y, float &out z)

[Player::IsAiming](class_player.md)

bool IsAiming()

[Player::GetTagText](class_player.md)

string & GetTagText(int index)

[Player::GetSpectateMode](class_player.md)

int GetSpectateMode()

[Player::IsInvisible](class_player.md)

bool IsInvisible()

[Player::IgnoreProximity](class_player.md)

void IgnoreProximity(bool value)

[Player::SendMessage](class_player.md)

void SendMessage(string &in message, float time=6.0, bool localized=false)

[Player::ShowDialog](class_player.md)

void ShowDialog(int type, int index, string &in header, string &in message, string &in leftbutton, string &in rightbutton="", bool align=true)

[Player::GetColor](class_player.md)

uint GetColor()

[Player::EnableBlinking](class_player.md)

void EnableBlinking(bool blink)

[Player::IsAdmin](class_player.md)

bool IsAdmin()

[Player::SetNetworkRotation](class_player.md)

void SetNetworkRotation(float pitch, float yaw)

[Player::SetModelTexture](class_player.md)

void SetModelTexture(int textureid)

[Player::SetModelSize](class_player.md)

void SetModelSize(float)

[Player::GetRadio](class_player.md)

int GetRadio()

[Player::GetHitbox](class_player.md)

Entity GetHitbox()

[Player::GetHWID](class_player.md)

string & GetHWID(int wmid=0)

[Player::Kick](class_player.md)

void Kick(int code=0, string &in custom="")

[Player::GetAnimation](class_player.md)

int GetAnimation()

[Player::GetAttachItem](class_player.md)

Items GetAttachItem(int bodyindex)

[Player::GetSelectedItem](class_player.md)

Items GetSelectedItem()

[Player::SetGlobalTransmission](class_player.md)

void SetGlobalTransmission(bool val)

[Player::SetColor](class_player.md)

void SetColor(uint hx)

[Player::PlayAnimation](class_player.md)

void PlayAnimation(int animid)

[Player::GetBloodloss](class_player.md)

float GetBloodloss()

[Player::SetNetworkAnimation](class_player.md)

void SetNetworkAnimation(int animid)

[Player::GetShootsCount](class_player.md)

int GetShootsCount()

[Player::SetDialogData](class_player.md)

void SetDialogData(string &in data)

[Player::SetTagFont](class_player.md)

void SetTagFont(int index, string &in)

[Player::GetGodmode](class_player.md)

bool GetGodmode()

[Player::GetLanguage](class_player.md)

string & GetLanguage()

[Player::GetVersion](class_player.md)

string & GetVersion()

[Room](class_room.md)

**Definition** all.h:485

[Room::GetLever](class_room.md)

Entity GetLever(int index)

[Room::GetName](class_room.md)

string & GetName()

[Room::GetDoor](class_room.md)

Door GetDoor(int)

[Room::GetEntity](class_room.md)

Entity GetEntity()

[Room::GetObject](class_room.md)

Entity GetObject(int index)

[Room::IsAdjacent](class_room.md)

bool IsAdjacent(Room)

[Room::IsInside](class_room.md)

bool IsInside(Entity)

[Room::GetIndex](class_room.md)

int GetIndex()

[Room::GetIdentifier](class_room.md)

int GetIdentifier()

[Room::GetAdjacentDoor](class_room.md)

Door GetAdjacentDoor(int index)

[Room::GetAdjacentRoom](class_room.md)

Room GetAdjacentRoom(int index)

[Server](class_server.md)

**Definition** all.h:500

[Server::hostname](class_server.md)

string & hostname

**Definition** all.h:509

[Server::improvedgates](class_server.md)

bool improvedgates

**Definition** all.h:529

[Server::RemoveVersion](class_server.md)

void RemoveVersion(string &in version)

[Server::voicebitrate](class_server.md)

int voicebitrate

**Definition** all.h:515

[Server::respawntime](class_server.md)

int respawntime

**Definition** all.h:526

[Server::GetUPS](class_server.md)

int GetUPS()

[Server::steam\_auth](class_server.md)

bool steam\_auth

**Definition** all.h:543

[Server::mapbounds](class_server.md)

float mapbounds

**Definition** all.h:525

[Server::AddVersion](class_server.md)

void AddVersion(string &in version)

[Server::description](class_server.md)

string & description

**Definition** all.h:532

[Server::contenturl](class_server.md)

string & contenturl

**Definition** all.h:527

[Server::chat](class_server.md)

bool chat

**Definition** all.h:513

[Server::fastslots](class_server.md)

bool fastslots

**Definition** all.h:533

[Server::addonsfile](class_server.md)

string & addonsfile

**Definition** all.h:536

[Server::difficulty](class_server.md)

int difficulty

**Definition** all.h:519

[Server::ParseConfig](class_server.md)

Config ParseConfig(string &in filename)

[Server::disablenpcs](class_server.md)

bool disablenpcs

**Definition** all.h:523

[Server::emptybehaviour](class_server.md)

int emptybehaviour

**Definition** all.h:521

[Server::adminpassword](class_server.md)

string & adminpassword

**Definition** all.h:518

[Server::enablehud](class_server.md)

bool enablehud

**Definition** all.h:537

[Server::holiday](class_server.md)

int holiday

**Definition** all.h:535

[Server::Restart](class_server.md)

void Restart()

[Server::max\_lights](class_server.md)

int max\_lights

**Definition** all.h:541

[Server::password](class_server.md)

string & password

**Definition** all.h:528

[Server::GetVersion](class_server.md)

string & GetVersion()

[Server::port](class_server.md)

int port

**Definition** all.h:510

[Server::player\_culling](class_server.md)

bool player\_culling

**Definition** all.h:542

[Server::mapsize](class_server.md)

int mapsize

**Definition** all.h:530

[Server::allowjump](class_server.md)

bool allowjump

**Definition** all.h:531

[Server::gamemode](class_server.md)

string & gamemode

**Definition** all.h:520

[Server::fall\_damage](class_server.md)

bool fall\_damage

**Definition** all.h:544

[Server::max\_corpses](class_server.md)

int max\_corpses

**Definition** all.h:540

[Server::gravity](class_server.md)

float gravity

**Definition** all.h:534

[Server::console](class_server.md)

bool console

**Definition** all.h:514

[Server::scriptsautoload](class_server.md)

bool scriptsautoload

**Definition** all.h:522

[Server::max\_items](class_server.md)

int max\_items

**Definition** all.h:538

[Server::corpsealivetime](class_server.md)

int corpsealivetime

**Definition** all.h:511

[Server::proximityplayers](class_server.md)

float proximityplayers

**Definition** all.h:524

[Server::Console](class_server.md)

void Console(string &in)

[Server::maxplayers](class_server.md)

int maxplayers

**Definition** all.h:516

[Server::mapseed](class_server.md)

string & mapseed

**Definition** all.h:517

[Server::max\_objects](class_server.md)

int max\_objects

**Definition** all.h:539

[Server::timeout](class_server.md)

int timeout

**Definition** all.h:512

[Shell](class_shell.md)

**Definition** all.h:547

[Shell::GetSpeed](class_shell.md)

float GetSpeed()

[Shell::GetDamage](class_shell.md)

float GetDamage()

[Shell::SetVelocity](class_shell.md)

void SetVelocity(float x, float y, float z)

[Shell::GetVelocity](class_shell.md)

void GetVelocity(float &out x, float &out y, float &out z)

[Shell::GetGravity](class_shell.md)

float GetGravity()

[Shell::SetActionSound](class_shell.md)

void SetActionSound(string &in sound)

[Shell::GetCollisionRadius](class_shell.md)

float GetCollisionRadius()

[Shell::GetTimeout](class_shell.md)

float GetTimeout()

[Shell::GetWeapon](class_shell.md)

int GetWeapon()

[Shell::SetSound](class_shell.md)

void SetSound(string &in sound)

[Shell::SetImpactTime](class_shell.md)

void SetImpactTime(float time)

[Shell::SetTimeout](class_shell.md)

void SetTimeout(float time)

[Shell::GetRestitution](class_shell.md)

float GetRestitution()

[Shell::GetShooter](class_shell.md)

Player GetShooter()

[Shell::SetShooter](class_shell.md)

void SetShooter(Player player)

[Shell::GetStickFlags](class_shell.md)

uint GetStickFlags()

[Shell::Remove](class_shell.md)

void Remove(bool action=false)

[Shell::GetCollisionSound](class_shell.md)

string & GetCollisionSound()

[Shell::GetIndex](class_shell.md)

int GetIndex()

[Shell::GetSound](class_shell.md)

string & GetSound()

[Shell::GetEmitter](class_shell.md)

int GetEmitter()

[Shell::SetRestitution](class_shell.md)

void SetRestitution(float restitution)

[Shell::GetForce](class_shell.md)

float GetForce()

[Shell::SetCollisionSound](class_shell.md)

void SetCollisionSound(string &in sound)

[Shell::GetAction](class_shell.md)

int GetAction()

[Shell::SetSpeed](class_shell.md)

void SetSpeed(float speed)

[Shell::GetStickIndex](class_shell.md)

int GetStickIndex()

[Shell::GetImpactTime](class_shell.md)

float GetImpactTime()

[Shell::GetActionSound](class_shell.md)

string & GetActionSound()

[Shell::SetDamage](class_shell.md)

void SetDamage(float damage)

[Shell::SetAction](class_shell.md)

void SetAction(int action)

[Shell::IsSticky](class_shell.md)

bool IsSticky()

[Shell::SetActionRadius](class_shell.md)

void SetActionRadius(float radius)

[Shell::SetActionEmitter](class_shell.md)

void SetActionEmitter(string &in emitters)

[Shell::GetActionRadius](class_shell.md)

float GetActionRadius()

[Shell::SetGravity](class_shell.md)

void SetGravity(float gravity)

[Shell::GetActionEmitter](class_shell.md)

string & GetActionEmitter()

[Shell::Unstick](class_shell.md)

void Unstick()

[Shell::SetCollisionRadius](class_shell.md)

void SetCollisionRadius(float radius)

[Shell::SetForce](class_shell.md)

void SetForce(float force)

[Shell::SetEmitter](class_shell.md)

void SetEmitter(int id)

[Shell::SetSticky](class_shell.md)

void SetSticky(bool sticky)

[Sound](class_sound.md)

**Definition** all.h:594

[Sound::Stop](class_sound.md)

void Stop()

[Sound::Seek](class_sound.md)

void Seek(float time)

[Sound::SetVolume](class_sound.md)

void SetVolume(float vol)

[World](class_world.md)

**Definition** all.h:601

[World::RaycastItems](class_world.md)

void RaycastItems()

[World::GetEventByIdentifier](class_world.md)

Event GetEventByIdentifier(int index)

[World::GetEvent](class_world.md)

Event GetEvent(int index)

[World::GetNPC](class_world.md)

NPC GetNPC(int index)

[World::CreateItem](class_world.md)

Items CreateItem(string &in templatename, bool collision=true, float x=0, float y=0, float z=0, int r=0, int g=0, int b=0, float alpha=1.0, int invslots=0)

[World::CreateDecal](class_world.md)

void CreateDecal(int decalid, float x, float y, float z, float pitch, float yaw, float roll, Room room=NULL, float lifetime=1.0f, float alpha=1.0f, float size=1.0f, float sizechange=0.0f, float maxsize=1.0f, float alphachange=0.0f, int r=0, int g=0, int b=0, float timer=0.0)

[World::GetRoomByIdentifier](class_world.md)

Room GetRoomByIdentifier(int)

[World::CreateEmitter](class_world.md)

void CreateEmitter(Player target, int id, float x, float y, float z, Player attachPlayer)

[World::CreateNPC](class_world.md)

NPC CreateNPC(int npctype, float x, float y, float z)

[World::CreateItem](class_world.md)

Items CreateItem(int templateindex, bool collision=true, float x=0, float y=0, float z=0, int r=0, int g=0, int b=0, float alpha=1.0, int invslots=0)

[World::GetZone](class_world.md)

int GetZone(float x, float y, float z)

[World::GetItem](class_world.md)

Items GetItem(int index)

[World::CreateShell](class_world.md)

Shell CreateShell(int weaponid, Player shooter=NULL)

[World::CreateLight](class_world.md)

Light CreateLight(int type, float range=10.0, Room room=NULL)

[World::GetDoor](class_world.md)

Door GetDoor(int)

[World::CreateObject](class_world.md)

Object CreateObject(int objectid, Room room=NULL, bool animated=false)

[World::GetRoomByIndex](class_world.md)

Room GetRoomByIndex(int)

[World::GetCorpse](class_world.md)

Corpse GetCorpse(int index)

[World::CreateEmitter](class_world.md)

void CreateEmitter(Player target, int id, float x, float y, float z)

[World::CreateBot](class_world.md)

Player CreateBot(string &in)

[World::GetObject](class_world.md)

Object GetObject(int index)

[World::CreateEmitter](class_world.md)

void CreateEmitter(Player target, int id, float x, float y, float z, Object attachObject)

[World::GetRoomByName](class_world.md)

Room GetRoomByName(string &in)

[Сhat](class_xD0_xA1hat.md)

**Definition** all.h:14

[Сhat::Send](class_xD0_xA1hat.md)

void Send(string &in message)

[Сhat::SendPlayer](class_xD0_xA1hat.md)

void SendPlayer(Player player, string &in message)

- **all.h**
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
