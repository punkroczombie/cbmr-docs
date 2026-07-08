<!-- source: http://scpcbmr.42web.io/class_entity.html -->
# SCP: Containment Breach 2 Scripting: Entity Class Reference

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

[Public Member Functions](class_entity.md) |
[List of all members](class_entity-members.md)

Entity Class Reference

|  |  |
| --- | --- |
| Public Member Functions | |
| void | [SetPosition](class_entity.md) (float x, float y, float z, bool global=false) |
|  | |
| void | [SetRotation](class_entity.md) (float pitch, float yaw, float roll, bool global=false) |
|  | |
| void | [SetScale](class_entity.md) (float x, float y, float z, bool global=false) |
|  | |
| float | [PositionX](class_entity.md) (bool global=false, float tween=1.0) |
|  | |
| float | [PositionY](class_entity.md) (bool global=false, float tween=1.0) |
|  | |
| float | [PositionZ](class_entity.md) (bool global=false, float tween=1.0) |
|  | |
| void | [Translate](class_entity.md) (float x, float y, float z, bool global=false) |
|  | |
| void | [Move](class_entity.md) (float x, float y, float z, bool global=false) |
|  | |
| float | [Pitch](class_entity.md) (bool global=false, float tween=1.0) |
|  | |
| float | [Yaw](class_entity.md) (bool global=false, float tween=1.0) |
|  | |
| float | [Roll](class_entity.md) (bool global=false, float tween=1.0) |
|  | |
| float | [Turn](class_entity.md) (float pitch, float yaw, float roll, bool global=false) |
|  | |
| float | [ScaleX](class_entity.md) (bool global=false, float tween=1.0) |
|  | |
| float | [ScaleY](class_entity.md) (bool global=false, float tween=1.0) |
|  | |
| float | [ScaleZ](class_entity.md) (bool global=false, float tween=1.0) |
|  | |
| void | [SetAnimTime](class_entity.md) (float time, int sequence=0) |
|  | |
| float | [GetAnimTime](class_entity.md) () |
|  | |
| float | [Point](class_entity.md) ([Entity](class_entity.md) target, float roll=0.0) |
|  | |
| [Entity](class_entity.md) | [Pick](class_entity.md) (float distance) |
|  | |
| void | [SetPickMode](class_entity.md) (int pickmode, bool obscurer=false) |
|  | |
| bool | [Visible](class_entity.md) ([Entity](class_entity.md) target, float radius=0.0f) |
|  | |
| float | [Distance](class_entity.md) ([Entity](class_entity.md) target) |
|  | |
| float | [DistanceSquared](class_entity.md) ([Entity](class_entity.md) target) |
|  | |
| void | [SetParent](class_entity.md) ([Entity](class_entity.md) target, bool retain=true) |
|  | |
| [Entity](class_entity.md) | [GetParent](class_entity.md) () |
|  | |
| int | [CountChildren](class_entity.md) () |
|  | |
| [Entity](class_entity.md) | [GetChild](class_entity.md) (int) |
|  | |
| string & | [GetName](class_entity.md) () |
|  | |
| void | [SetName](class_entity.md) (string &in name) |
|  | |
| bool | [Collided](class_entity.md) (int colltype) |
|  | |
| int | [CountCollisions](class_entity.md) () |
|  | |
| float | [CollisionX](class_entity.md) (int index) |
|  | |
| float | [CollisionY](class_entity.md) (int index) |
|  | |
| float | [CollisionZ](class_entity.md) (int index) |
|  | |
| float | [CollisionNX](class_entity.md) (int index) |
|  | |
| float | [CollisionNY](class_entity.md) (int index) |
|  | |
| float | [CollisionNZ](class_entity.md) (int index) |
|  | |
| float | [CollisionImpulse](class_entity.md) (int index) const |
|  | |
| float | [CollisionDistance](class_entity.md) (int index) const |
|  | |
| float | [CollisionTime](class_entity.md) (int index) const |
|  | |
| [Entity](class_entity.md) | [CollisionEntity](class_entity.md) (int index) const |
|  | |
| int | [CollisionTriangle](class_entity.md) (int index) const |
|  | |
| void | [SetType](class_entity.md) (int colltype, bool recursive=false) |
|  | |
| void | [SetRadius](class_entity.md) (float x, float y=0.0) |
|  | |
| void | [SetCylinder](class_entity.md) (float x\_radius, float y\_radius=0.0) |
|  | |
| void | [SetBox](class_entity.md) (float x, float y, float z, float w, float h, float d) |
|  | |
| int | [GetType](class_entity.md) () const |
|  | |
| int | [GetShape](class_entity.md) (float &out x, float &out y, float &out z, float &out width, float &out height, float &out depth) const |
|  | |
| void | [Reset](class_entity.md) () |
|  | |
| bool | [InView](class_entity.md) ([Entity](class_entity.md) target) |
|  | |
| void | [Show](class_entity.md) () |
|  | |
| void | [Hide](class_entity.md) () |
|  | |
| void | [Remove](class_entity.md) () |
|  | |
| void | [SetMass](class_entity.md) (float mass) |
|  | |
| void | [SetPhysics](class_entity.md) (bool enable) |
|  | |
| void | [SetKinematic](class_entity.md) (bool enable) |
|  | |
| void | [SetCenter](class_entity.md) (float x, float y, float z) |
|  | |
| void | [SetLinearCast](class_entity.md) (bool enable) |
|  | |
| void | [SetFriction](class_entity.md) (float friction) |
|  | |
| void | [SetRollFriction](class_entity.md) (float friction) |
|  | |
| void | [SetRestitution](class_entity.md) (float res) |
|  | |
| void | [SetGravity](class_entity.md) (float factor) |
|  | |
| void | [SetLinearFactor](class_entity.md) (float x, float y, float z) |
|  | |
| void | [SetAngularFactor](class_entity.md) (float x, float y, float z) |
|  | |
| void | [SetLinearDamping](class_entity.md) (float damping) |
|  | |
| void | [SetAngularDamping](class_entity.md) (float damping) |
|  | |
| void | [SetConstraint](class_entity.md) (float normalAngle, float planeAngle, float twistMinAngle, float twistMaxAngle, float torqueFriction) |
|  | |
| void | [Activate](class_entity.md) (bool enable) |
|  | |
| void | [Sleep](class_entity.md) (bool enable) |
|  | |
| void | [Freeze](class_entity.md) (bool enable) |
|  | |
| bool | [IsFreezed](class_entity.md) () const |
|  | |
| bool | [IsActive](class_entity.md) () const |
|  | |
| void | [SetLinearVelocity](class_entity.md) (float x, float y, float z) |
|  | |
| void | [SetAngularVelocity](class_entity.md) (float x, float y, float z) |
|  | |
| void | [GetLinearVelocity](class_entity.md) (float &out x, float &out y, float &out z) const |
|  | |
| void | [GetAngularVelocity](class_entity.md) (float &out x, float &out y, float &out z) const |
|  | |
| void | [Impulse](class_entity.md) (float x, float y, float z) |
|  | |
| void | [Torque](class_entity.md) (float x, float y, float z) |
|  | |
| void | [ClearForces](class_entity.md) () |
|  | |

## Member Function Documentation

## [◆](class_entity.md)SetPosition()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetPosition | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | bool | *global* = false ) |

Set entity position

## [◆](class_entity.md)SetRotation()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetRotation | ( | float | *pitch*, |
|  |  | float | *yaw*, |
|  |  | float | *roll*, |
|  |  | bool | *global* = false ) |

Set entity rotation

## [◆](class_entity.md)SetScale()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetScale | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | bool | *global* = false ) |

Set entity scale

## [◆](class_entity.md)PositionX()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::PositionX | ( | bool | *global* = false, |
|  |  | float | *tween* = 1.0 ) |

Get entity pos X

## [◆](class_entity.md)PositionY()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::PositionY | ( | bool | *global* = false, |
|  |  | float | *tween* = 1.0 ) |

Get entity pos Y

## [◆](class_entity.md)PositionZ()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::PositionZ | ( | bool | *global* = false, |
|  |  | float | *tween* = 1.0 ) |

Get entity pos Z

## [◆](class_entity.md)Translate()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::Translate | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | bool | *global* = false ) |

Translate entity without rotation

## [◆](class_entity.md)Move()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::Move | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | bool | *global* = false ) |

Translate entity including rotation

## [◆](class_entity.md)Pitch()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::Pitch | ( | bool | *global* = false, |
|  |  | float | *tween* = 1.0 ) |

Get entity pitch

## [◆](class_entity.md)Yaw()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::Yaw | ( | bool | *global* = false, |
|  |  | float | *tween* = 1.0 ) |

Get entity yaw

## [◆](class_entity.md)Roll()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::Roll | ( | bool | *global* = false, |
|  |  | float | *tween* = 1.0 ) |

Get entity roll

## [◆](class_entity.md)Turn()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::Turn | ( | float | *pitch*, |
|  |  | float | *yaw*, |
|  |  | float | *roll*, |
|  |  | bool | *global* = false ) |

Rotate entity with specified angles

## [◆](class_entity.md)ScaleX()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::ScaleX | ( | bool | *global* = false, |
|  |  | float | *tween* = 1.0 ) |

Scale X

## [◆](class_entity.md)ScaleY()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::ScaleY | ( | bool | *global* = false, |
|  |  | float | *tween* = 1.0 ) |

Scale Y

## [◆](class_entity.md)ScaleZ()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::ScaleZ | ( | bool | *global* = false, |
|  |  | float | *tween* = 1.0 ) |

Scale Z

## [◆](class_entity.md)SetAnimTime()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetAnimTime | ( | float | *time*, |
|  |  | int | *sequence* = 0 ) |

Set entity anim time

## [◆](class_entity.md)GetAnimTime()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| float Entity::GetAnimTime | ( |  | ) |  |

Get entity anim time

## [◆](class_entity.md)Point()

|  |  |  |  |
| --- | --- | --- | --- |
| float Entity::Point | ( | [Entity](class_entity.md) | *target*, |
|  |  | float | *roll* = 0.0 ) |

Turn entity to specified entity

## [◆](class_entity.md)Pick()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Entity::Pick | ( | float | *distance* | ) |  |

Pick nearest entity by distance

## [◆](class_entity.md)SetPickMode()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetPickMode | ( | int | *pickmode*, |
|  |  | bool | *obscurer* = false ) |

Set entity pick mode to use with Pick functions

## [◆](class_entity.md)Visible()

|  |  |  |  |
| --- | --- | --- | --- |
| bool Entity::Visible | ( | [Entity](class_entity.md) | *target*, |
|  |  | float | *radius* = 0.0f ) |

Do the entities see each other (Collisions)

## [◆](class_entity.md)Distance()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::Distance | ( | [Entity](class_entity.md) | *target* | ) |  |

Distance from specified entity

## [◆](class_entity.md)DistanceSquared()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::DistanceSquared | ( | [Entity](class_entity.md) | *target* | ) |  |

Squared distance from specified entity

## [◆](class_entity.md)SetParent()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetParent | ( | [Entity](class_entity.md) | *target*, |
|  |  | bool | *retain* = true ) |

Set entity parent

## [◆](class_entity.md)GetParent()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Entity::GetParent | ( |  | ) |  |

Get entity parent

## [◆](class_entity.md)CountChildren()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Entity::CountChildren | ( |  | ) |  |

Count of entity children

## [◆](class_entity.md)GetChild()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Entity::GetChild | ( | int |  | ) |  |

Get entity child by index

## [◆](class_entity.md)GetName()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| string & Entity::GetName | ( |  | ) |  |

Get entity name

## [◆](class_entity.md)SetName()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetName | ( | string &in | *name* | ) |  |

Set entity name

## [◆](class_entity.md)Collided()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool Entity::Collided | ( | int | *colltype* | ) |  |

Is entity collide with colltype

## [◆](class_entity.md)CountCollisions()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Entity::CountCollisions | ( |  | ) |  |

Count of entity collisions

## [◆](class_entity.md)CollisionX()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::CollisionX | ( | int | *index* | ) |  |

Collision X

## [◆](class_entity.md)CollisionY()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::CollisionY | ( | int | *index* | ) |  |

Collision Y

## [◆](class_entity.md)CollisionZ()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::CollisionZ | ( | int | *index* | ) |  |

Collision Z

## [◆](class_entity.md)CollisionNX()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::CollisionNX | ( | int | *index* | ) |  |

Collision Normal X

## [◆](class_entity.md)CollisionNY()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::CollisionNY | ( | int | *index* | ) |  |

Collision Normal Y

## [◆](class_entity.md)CollisionNZ()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::CollisionNZ | ( | int | *index* | ) |  |

Collision Normal Z

## [◆](class_entity.md)CollisionImpulse()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::CollisionImpulse | ( | int | *index* | ) | const |

Get impulse force of the specified collision

## [◆](class_entity.md)CollisionDistance()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::CollisionDistance | ( | int | *index* | ) | const |

Get penetration distance of the specified collision

## [◆](class_entity.md)CollisionTime()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| float Entity::CollisionTime | ( | int | *index* | ) | const |

Get time of the specified collision

## [◆](class_entity.md)CollisionEntity()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| [Entity](class_entity.md) Entity::CollisionEntity | ( | int | *index* | ) | const |

Get entity instance involved in the specified collision

## [◆](class_entity.md)CollisionTriangle()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| int Entity::CollisionTriangle | ( | int | *index* | ) | const |

Get collided mesh triangle index

## [◆](class_entity.md)SetType()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetType | ( | int | *colltype*, |
|  |  | bool | *recursive* = false ) |

Set entity type collision

## [◆](class_entity.md)SetRadius()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetRadius | ( | float | *x*, |
|  |  | float | *y* = 0.0 ) |

Set entity collision radius if collision type is sphere

## [◆](class_entity.md)SetCylinder()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetCylinder | ( | float | *x\_radius*, |
|  |  | float | *y\_radius* = 0.0 ) |

Set cylinder or custom physics shape radius

## [◆](class_entity.md)SetBox()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetBox | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z*, |
|  |  | float | *w*, |
|  |  | float | *h*, |
|  |  | float | *d* ) |

Set box physics shape bounding

## [◆](class_entity.md)GetType()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| int Entity::GetType | ( |  | ) | const |

Get physics collision type

## [◆](class_entity.md)GetShape()

|  |  |  |  |
| --- | --- | --- | --- |
| int Entity::GetShape | ( | float &out | *x*, |
|  |  | float &out | *y*, |
|  |  | float &out | *z*, |
|  |  | float &out | *width*, |
|  |  | float &out | *height*, |
|  |  | float &out | *depth* ) const |

Get local physics bounding box dimensions

## [◆](class_entity.md)Reset()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Entity::Reset | ( |  | ) |  |

Reset entity collision

## [◆](class_entity.md)InView()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| bool Entity::InView | ( | [Entity](class_entity.md) | *target* | ) |  |

Can camera (target) see specified entity (Camera can be taken from [Player::GetHead](class_player.md))

## [◆](class_entity.md)Show()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Entity::Show | ( |  | ) |  |

Show entity

## [◆](class_entity.md)Hide()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Entity::Hide | ( |  | ) |  |

Hide entity

## [◆](class_entity.md)Remove()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Entity::Remove | ( |  | ) |  |

Remove entity

## [◆](class_entity.md)SetMass()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetMass | ( | float | *mass* | ) |  |

Set entity mass

## [◆](class_entity.md)SetPhysics()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetPhysics | ( | bool | *enable* | ) |  |

Enable or disable physics for entity

## [◆](class_entity.md)SetKinematic()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetKinematic | ( | bool | *enable* | ) |  |

Set entity kinematic status

## [◆](class_entity.md)SetCenter()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetCenter | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Set physics center offset

## [◆](class_entity.md)SetLinearCast()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetLinearCast | ( | bool | *enable* | ) |  |

Set linear casting for fast moving entities

## [◆](class_entity.md)SetFriction()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetFriction | ( | float | *friction* | ) |  |

Set entity friction

## [◆](class_entity.md)SetRollFriction()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetRollFriction | ( | float | *friction* | ) |  |

Set entity rolling friction

## [◆](class_entity.md)SetRestitution()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetRestitution | ( | float | *res* | ) |  |

Set entity bounciness restitution

## [◆](class_entity.md)SetGravity()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetGravity | ( | float | *factor* | ) |  |

Set gravity scale factor

## [◆](class_entity.md)SetLinearFactor()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetLinearFactor | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Set linear movement factor axis

## [◆](class_entity.md)SetAngularFactor()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetAngularFactor | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Set angular movement factor axis

## [◆](class_entity.md)SetLinearDamping()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetLinearDamping | ( | float | *damping* | ) |  |

Set linear damping

## [◆](class_entity.md)SetAngularDamping()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::SetAngularDamping | ( | float | *damping* | ) |  |

Set angular damping

## [◆](class_entity.md)SetConstraint()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetConstraint | ( | float | *normalAngle*, |
|  |  | float | *planeAngle*, |
|  |  | float | *twistMinAngle*, |
|  |  | float | *twistMaxAngle*, |
|  |  | float | *torqueFriction* ) |

Set physics constraint limits

## [◆](class_entity.md)Activate()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::Activate | ( | bool | *enable* | ) |  |

Force entity physics activation

## [◆](class_entity.md)Sleep()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::Sleep | ( | bool | *enable* | ) |  |

Put entity physics to sleep or wake it up

## [◆](class_entity.md)Freeze()

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| void Entity::Freeze | ( | bool | *enable* | ) |  |

Freeze or unfreeze entity physics

## [◆](class_entity.md)IsFreezed()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Entity::IsFreezed | ( |  | ) | const |

Check if entity physics is frozen

## [◆](class_entity.md)IsActive()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| bool Entity::IsActive | ( |  | ) | const |

Check if entity physics is simulation active

## [◆](class_entity.md)SetLinearVelocity()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetLinearVelocity | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Set linear velocity vector

## [◆](class_entity.md)SetAngularVelocity()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::SetAngularVelocity | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Set angular velocity vector

## [◆](class_entity.md)GetLinearVelocity()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::GetLinearVelocity | ( | float &out | *x*, |
|  |  | float &out | *y*, |
|  |  | float &out | *z* ) const |

Get linear velocity vector

## [◆](class_entity.md)GetAngularVelocity()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::GetAngularVelocity | ( | float &out | *x*, |
|  |  | float &out | *y*, |
|  |  | float &out | *z* ) const |

Get angular velocity vector

## [◆](class_entity.md)Impulse()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::Impulse | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Apply linear impulse

## [◆](class_entity.md)Torque()

|  |  |  |  |
| --- | --- | --- | --- |
| void Entity::Torque | ( | float | *x*, |
|  |  | float | *y*, |
|  |  | float | *z* ) |

Apply torque impulse

## [◆](class_entity.md)ClearForces()

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| void Entity::ClearForces | ( |  | ) |  |

Clear all applied forces and torques

- [Entity](class_entity.md)
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
