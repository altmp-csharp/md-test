## `BaseObject`

```csharp
public abstract class AltV.Net.Elements.Entities.BaseObject
    : IBaseObject, IInternalBaseObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | Exists |  | 
| `IntPtr` | NativePointer |  | 
| `BaseObjectType` | Type |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | AddRef() |  | 
| `void` | CheckIfCallIsValid(`String` callerName = ) |  | 
| `void` | CheckIfEntityExists() |  | 
| `void` | ClearData() |  | 
| `void` | DeleteData(`String` key) |  | 
| `void` | DeleteMetaData(`String` key) |  | 
| `Boolean` | Equals(`Object` obj) |  | 
| `IEnumerable<String>` | GetAllDataKeys() |  | 
| `Boolean` | GetData(`String` key, `T&` result) |  | 
| `Int32` | GetHashCode() |  | 
| `void` | GetMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | GetMetaData(`String` key, `Int32&` result) |  | 
| `Boolean` | GetMetaData(`String` key, `UInt32&` result) |  | 
| `Boolean` | GetMetaData(`String` key, `Single&` result) |  | 
| `Boolean` | GetMetaData(`String` key, `T&` result) |  | 
| `Boolean` | HasData(`String` key) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `void` | InternalAddRef() |  | 
| `void` | InternalRemoveRef() |  | 
| `void` | OnRemove() |  | 
| `Boolean` | RemoveRef() |  | 
| `void` | SetData(`String` key, `Object` value) |  | 
| `void` | SetMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | SetMetaData(`String` key, `Object` value) |  | 


## `BaseObjectExtensions`

```csharp
public static class AltV.Net.Elements.Entities.BaseObjectExtensions

```

Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | GetMetaData(this `IBaseObject` baseObject, `String` key, `Int32&` result) |  | 
| `Boolean` | GetMetaData(this `IBaseObject` baseObject, `String` key, `UInt32&` result) |  | 
| `Boolean` | GetMetaData(this `IBaseObject` baseObject, `String` key, `Single&` result) |  | 


## `BaseObjectRemovedException`

```csharp
public class AltV.Net.Elements.Entities.BaseObjectRemovedException
    : Exception, ISerializable

```

## `BaseObjectType`

```csharp
public enum AltV.Net.Elements.Entities.BaseObjectType
    : Enum, IComparable, IFormattable, IConvertible

```

Enum

| Value | Name | Summary | 
| --- | --- | --- | 
| `0` | Player |  | 
| `1` | Vehicle |  | 
| `2` | Blip |  | 
| `3` | WebView |  | 
| `4` | VoiceChannel |  | 
| `5` | ColShape |  | 
| `6` | Checkpoint |  | 
| `255` | Undefined |  | 


## `Blip`

```csharp
public class AltV.Net.Elements.Entities.Blip
    : WorldObject, IBaseObject, IInternalBaseObject, IWorldObject, IBlip

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `IEntity` | AttachedTo |  | 
| `Byte` | BlipType |  | 
| `Byte` | Color |  | 
| `Int32` | Dimension |  | 
| `Boolean` | IsAttached |  | 
| `Boolean` | IsGlobal |  | 
| `Position` | Position |  | 
| `Boolean` | Route |  | 
| `Byte` | RouteColor |  | 
| `UInt16` | Sprite |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | DeleteMetaData(`String` key) |  | 
| `void` | GetMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `void` | InternalAddRef() |  | 
| `void` | InternalRemoveRef() |  | 
| `void` | Remove() |  | 
| `void` | SetMetaData(`String` key, `MValueConst&` value) |  | 


## `BlipType`

```csharp
public enum AltV.Net.Elements.Entities.BlipType
    : Enum, IComparable, IFormattable, IConvertible

```

Enum

| Value | Name | Summary | 
| --- | --- | --- | 
| `1` | Vehicle |  | 
| `2` | Ped |  | 
| `2` | Enemy |  | 
| `3` | Object |  | 
| `4` | Destination |  | 
| `5` | Cont |  | 
| `6` | Unk |  | 
| `7` | Radius |  | 
| `8` | Pickup |  | 
| `9` | Cop |  | 
| `11` | Area |  | 
| `12` | Gallery |  | 
| `13` | PickupObject |  | 


## `Checkpoint`

```csharp
public class AltV.Net.Elements.Entities.Checkpoint
    : WorldObject, IBaseObject, IInternalBaseObject, IWorldObject, ICheckpoint, IColShape

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Byte` | CheckpointType |  | 
| `Rgba` | Color |  | 
| `ColShapeType` | ColShapeType |  | 
| `Int32` | Dimension |  | 
| `Single` | Height |  | 
| `Position` | Position |  | 
| `Single` | Radius |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | DeleteMetaData(`String` key) |  | 
| `void` | GetMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `void` | InternalAddRef() |  | 
| `void` | InternalRemoveRef() |  | 
| `Boolean` | IsEntityIn(`IEntity` entity) |  | 
| `Boolean` | IsPlayerIn(`IPlayer` player) |  | 
| `Boolean` | IsVehicleIn(`IVehicle` vehicle) |  | 
| `void` | Remove() |  | 
| `void` | SetMetaData(`String` key, `MValueConst&` value) |  | 


## `CheckpointType`

```csharp
public enum AltV.Net.Elements.Entities.CheckpointType
    : Enum, IComparable, IFormattable, IConvertible

```

Enum

| Value | Name | Summary | 
| --- | --- | --- | 
| `0` | CylinderSingleArrow |  | 
| `1` | CylinderDoubleArrow |  | 
| `2` | CylinderTripleArrow |  | 
| `3` | CylinderCycleArrow |  | 
| `4` | CylinderCheckerboard |  | 
| `5` | CylinderSingleArrow2 |  | 
| `6` | CylinderDoubleArrow2 |  | 
| `7` | CylinderTripleArrow2 |  | 
| `8` | CylinderCycleArrow2 |  | 
| `9` | CylinderCheckerboard2 |  | 
| `10` | RingSingleArrow |  | 
| `11` | RingDoubleArrow |  | 
| `12` | RingTripleArrow |  | 
| `13` | RingCycleArrow |  | 
| `14` | RingCheckerboard |  | 
| `15` | SingleArrow |  | 
| `16` | DoubleArrow |  | 
| `17` | TripleArrow |  | 
| `18` | CycleArrow |  | 
| `19` | Checkerboard |  | 
| `20` | CylinderSingleArrow3 |  | 
| `21` | CylinderDoubleArrow3 |  | 
| `22` | CylinderTripleArrow3 |  | 
| `23` | CylinderCycleArrow3 |  | 
| `24` | CylinderCheckerboard3 |  | 
| `25` | CylinderSingleArrow4 |  | 
| `26` | CylinderDoubleArrow4 |  | 
| `27` | CylinderTripleArrow4 |  | 
| `28` | CylinderCycleArrow4 |  | 
| `29` | CylinderCheckerboard4 |  | 
| `30` | CylinderSingleArrow5 |  | 
| `31` | CylinderDoubleArrow5 |  | 
| `32` | CylinderTripleArrow5 |  | 
| `33` | CylinderCycleArrow5 |  | 
| `34` | CylinderCheckerboard5 |  | 
| `35` | RingPlaneUp |  | 
| `36` | RingPlaneLeft |  | 
| `37` | RingPlaneRight |  | 
| `38` | RingPlaneDown |  | 
| `39` | Empty |  | 
| `40` | Ring |  | 
| `41` | Empty2 |  | 
| `45` | Cyclinder |  | 
| `46` | Cyclinder2 |  | 
| `47` | Cyclinder3 |  | 


## `ColShape`

```csharp
public class AltV.Net.Elements.Entities.ColShape
    : WorldObject, IBaseObject, IInternalBaseObject, IWorldObject, IColShape

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `ColShapeType` | ColShapeType |  | 
| `Int32` | Dimension |  | 
| `Position` | Position |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | DeleteMetaData(`String` key) |  | 
| `void` | GetMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `void` | InternalAddRef() |  | 
| `void` | InternalRemoveRef() |  | 
| `Boolean` | IsEntityIn(`IEntity` entity) |  | 
| `Boolean` | IsPlayerIn(`IPlayer` player) |  | 
| `Boolean` | IsVehicleIn(`IVehicle` vehicle) |  | 
| `void` | Remove() |  | 
| `void` | SetMetaData(`String` key, `MValueConst&` value) |  | 


## `ColShapeType`

```csharp
public enum AltV.Net.Elements.Entities.ColShapeType
    : Enum, IComparable, IFormattable, IConvertible

```

Enum

| Value | Name | Summary | 
| --- | --- | --- | 
| `0` | Sphere |  | 
| `1` | Cylinder |  | 
| `2` | Circle |  | 
| `3` | Cube |  | 
| `4` | Rect |  | 


## `Entity`

```csharp
public abstract class AltV.Net.Elements.Entities.Entity
    : WorldObject, IBaseObject, IInternalBaseObject, IWorldObject, IEntity

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt16` | Id |  | 
| `UInt32` | Model |  | 
| `IPlayer` | NetworkOwner |  | 
| `Rotation` | Rotation |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | CheckIfEntityExists() |  | 
| `void` | DeleteStreamSyncedMetaData(`String` key) |  | 
| `void` | DeleteSyncedMetaData(`String` key) |  | 
| `void` | GetStreamSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | GetStreamSyncedMetaData(`String` key, `T&` result) |  | 
| `void` | GetSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | GetSyncedMetaData(`String` key, `T&` result) |  | 
| `Boolean` | HasStreamSyncedMetaData(`String` key) |  | 
| `Boolean` | HasSyncedMetaData(`String` key) |  | 
| `void` | SetStreamSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | SetStreamSyncedMetaData(`String` key, `Object` value) |  | 
| `void` | SetSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | SetSyncedMetaData(`String` key, `Object` value) |  | 


## `EntityExtensions`

```csharp
public static class AltV.Net.Elements.Entities.EntityExtensions

```

Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | GetStreamSyncedMetaData(this `IEntity` entity, `String` key, `Int32&` result) |  | 
| `Boolean` | GetStreamSyncedMetaData(this `IEntity` entity, `String` key, `UInt32&` result) |  | 
| `Boolean` | GetStreamSyncedMetaData(this `IEntity` entity, `String` key, `Single&` result) |  | 
| `Boolean` | GetSyncedMetaData(this `IEntity` entity, `String` key, `Int32&` result) |  | 
| `Boolean` | GetSyncedMetaData(this `IEntity` entity, `String` key, `UInt32&` result) |  | 
| `Boolean` | GetSyncedMetaData(this `IEntity` entity, `String` key, `Single&` result) |  | 


## `EntityRemovedException`

```csharp
public class AltV.Net.Elements.Entities.EntityRemovedException
    : WorldObjectRemovedException, ISerializable

```

## `IBaseObject`

```csharp
public interface AltV.Net.Elements.Entities.IBaseObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | Exists |  | 
| `IntPtr` | NativePointer |  | 
| `BaseObjectType` | Type |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | AddRef() |  | 
| `void` | CheckIfEntityExists() |  | 
| `void` | DeleteData(`String` key) |  | 
| `void` | DeleteMetaData(`String` key) |  | 
| `IEnumerable<String>` | GetAllDataKeys() |  | 
| `Boolean` | GetData(`String` key, `T&` result) |  | 
| `Boolean` | GetMetaData(`String` key, `T&` result) |  | 
| `void` | GetMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | HasData(`String` key) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `void` | OnRemove() |  | 
| `Boolean` | RemoveRef() |  | 
| `void` | SetData(`String` key, `Object` value) |  | 
| `void` | SetMetaData(`String` key, `Object` value) |  | 
| `void` | SetMetaData(`String` key, `MValueConst&` value) |  | 


## `IBlip`

```csharp
public interface AltV.Net.Elements.Entities.IBlip
    : IWorldObject, IBaseObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `IEntity` | AttachedTo |  | 
| `Byte` | BlipType |  | 
| `Byte` | Color |  | 
| `Boolean` | IsAttached |  | 
| `Boolean` | IsGlobal |  | 
| `Boolean` | Route |  | 
| `Byte` | RouteColor |  | 
| `UInt16` | Sprite |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | Remove() |  | 


## `ICheckpoint`

```csharp
public interface AltV.Net.Elements.Entities.ICheckpoint
    : IColShape, IWorldObject, IBaseObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Byte` | CheckpointType |  | 
| `Rgba` | Color |  | 
| `Single` | Height |  | 
| `Single` | Radius |  | 


## `IColShape`

```csharp
public interface AltV.Net.Elements.Entities.IColShape
    : IWorldObject, IBaseObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `ColShapeType` | ColShapeType |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | IsEntityIn(`IEntity` entity) |  | 
| `Boolean` | IsPlayerIn(`IPlayer` entity) |  | 
| `Boolean` | IsVehicleIn(`IVehicle` entity) |  | 
| `void` | Remove() |  | 


## `IEntity`

```csharp
public interface AltV.Net.Elements.Entities.IEntity
    : IWorldObject, IBaseObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt16` | Id |  | 
| `UInt32` | Model |  | 
| `IPlayer` | NetworkOwner |  | 
| `Rotation` | Rotation |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | DeleteStreamSyncedMetaData(`String` key) |  | 
| `void` | DeleteSyncedMetaData(`String` key) |  | 
| `Boolean` | GetStreamSyncedMetaData(`String` key, `T&` result) |  | 
| `void` | GetStreamSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | GetSyncedMetaData(`String` key, `T&` result) |  | 
| `void` | GetSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | HasStreamSyncedMetaData(`String` key) |  | 
| `Boolean` | HasSyncedMetaData(`String` key) |  | 
| `void` | SetStreamSyncedMetaData(`String` key, `Object` value) |  | 
| `void` | SetStreamSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | SetSyncedMetaData(`String` key, `Object` value) |  | 
| `void` | SetSyncedMetaData(`String` key, `MValueConst&` value) |  | 


## `IPlayer`

```csharp
public interface AltV.Net.Elements.Entities.IPlayer
    : IEntity, IWorldObject, IBaseObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Position` | AimPosition |  | 
| `UInt16` | Ammo |  | 
| `UInt16` | Armor |  | 
| `String` | AuthToken |  | 
| `UInt32` | CurrentWeapon |  | 
| `IEntity` | EntityAimingAt |  | 
| `Position` | EntityAimOffset |  | 
| `UInt64` | HardwareIdExHash |  | 
| `UInt64` | HardwareIdHash |  | 
| `Rotation` | HeadRotation |  | 
| `UInt16` | Health |  | 
| `String` | Ip |  | 
| `Boolean` | IsAiming |  | 
| `Boolean` | IsConnected |  | 
| `Boolean` | IsDead |  | 
| `Boolean` | IsFlashlightActive |  | 
| `Boolean` | IsInRagdoll |  | 
| `Boolean` | IsInVehicle |  | 
| `Boolean` | IsJumping |  | 
| `Boolean` | IsReloading |  | 
| `Boolean` | IsShooting |  | 
| `UInt16` | MaxArmor |  | 
| `UInt16` | MaxHealth |  | 
| `UInt32` | Model |  | 
| `Single` | MoveSpeed |  | 
| `String` | Name |  | 
| `UInt32` | Ping |  | 
| `Byte` | Seat |  | 
| `UInt64` | SocialClubId |  | 
| `IVehicle` | Vehicle |  | 
| `UInt32` | Weapon |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | AddWeaponComponent(`UInt32` weapon, `UInt32` weaponComponent) |  | 
| `void` | Despawn() |  | 
| `void` | Emit(`String` eventName, `Object[]` args) |  | 
| `void` | GetCurrentWeaponComponents(`UInt32[]&` weaponComponents) |  | 
| `Byte` | GetCurrentWeaponTintIndex() |  | 
| `void` | GiveWeapon(`UInt32` weapon, `Int32` ammo, `Boolean` selectWeapon) |  | 
| `void` | Kick(`String` reason) |  | 
| `void` | RemoveAllWeapons() |  | 
| `void` | RemoveWeapon(`UInt32` weapon) |  | 
| `void` | RemoveWeaponComponent(`UInt32` weapon, `UInt32` weaponComponent) |  | 
| `void` | SetDateTime(`Int32` day, `Int32` month, `Int32` year, `Int32` hour, `Int32` minute, `Int32` second) |  | 
| `void` | SetWeaponTintIndex(`UInt32` weapon, `Byte` tintIndex) |  | 
| `void` | SetWeather(`UInt32` weather) |  | 
| `void` | Spawn(`Position` position, `UInt32` delayMs = 0) |  | 
| `Boolean` | TryCreateRef(`PlayerRef&` playerRef) |  | 


## `IVehicle`

```csharp
public interface AltV.Net.Elements.Entities.IVehicle
    : IEntity, IWorldObject, IBaseObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `String` | AppearanceData |  | 
| `UInt32` | BodyAdditionalHealth |  | 
| `UInt32` | BodyHealth |  | 
| `Boolean` | CustomTires |  | 
| `String` | DamageData |  | 
| `Byte` | DashboardColor |  | 
| `Byte` | DirtLevel |  | 
| `IPlayer` | Driver |  | 
| `Int32` | EngineHealth |  | 
| `Boolean` | EngineOn |  | 
| `Boolean` | HasArmoredWindows |  | 
| `Byte` | HeadlightColor |  | 
| `String` | HealthData |  | 
| `Byte` | InteriorColor |  | 
| `Boolean` | IsDaylightOn |  | 
| `Boolean` | IsDestroyed |  | 
| `Boolean` | IsFlamethrowerActive |  | 
| `Boolean` | IsHandbrakeActive |  | 
| `Boolean` | IsNeonActive |  | 
| `Boolean` | IsNightlightOn |  | 
| `Boolean` | IsPrimaryColorRgb |  | 
| `Boolean` | IsSecondaryColorRgb |  | 
| `Boolean` | IsTireSmokeColorCustom |  | 
| `Single` | LightsMultiplier |  | 
| `Byte` | Livery |  | 
| `VehicleLockState` | LockState |  | 
| `Boolean` | ManualEngineControl |  | 
| `Byte` | ModKit |  | 
| `Byte` | ModKitsCount |  | 
| `Rgba` | NeonColor |  | 
| `UInt32` | NumberplateIndex |  | 
| `String` | NumberplateText |  | 
| `Byte` | PearlColor |  | 
| `Int32` | PetrolTankHealth |  | 
| `Byte` | PrimaryColor |  | 
| `Rgba` | PrimaryColorRgb |  | 
| `UInt32` | RadioStation |  | 
| `Byte` | RearWheel |  | 
| `Byte` | RepairsCount |  | 
| `Byte` | RoofLivery |  | 
| `Boolean` | RoofOpened |  | 
| `String` | ScriptData |  | 
| `Byte` | SecondaryColor |  | 
| `Rgba` | SecondaryColorRgb |  | 
| `Boolean` | SirenActive |  | 
| `Byte` | SpecialDarkness |  | 
| `String` | State |  | 
| `Rgba` | TireSmokeColor |  | 
| `Byte` | WheelColor |  | 
| `Byte` | WheelsCount |  | 
| `Byte` | WheelType |  | 
| `Byte` | WheelVariation |  | 
| `Byte` | WindowTint |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | DoesWheelHasTire(`Byte` wheelId) |  | 
| `Single` | GetArmoredWindowHealth(`Byte` windowId) |  | 
| `Byte` | GetArmoredWindowShootCount(`Byte` windowId) |  | 
| `Byte` | GetBumperDamageLevel(`Byte` bumperId) |  | 
| `Byte` | GetDoorState(`Byte` doorId) |  | 
| `Byte` | GetMod(`Byte` category) |  | 
| `Byte` | GetModsCount(`Byte` category) |  | 
| `void` | GetNeonActive(`Boolean&` left, `Boolean&` right, `Boolean&` top, `Boolean&` back) |  | 
| `Byte` | GetPartBulletHoles(`Byte` partId) |  | 
| `Byte` | GetPartDamageLevel(`Byte` partId) |  | 
| `Single` | GetWheelHealth(`Byte` wheelId) |  | 
| `Boolean` | IsExtraOn(`Byte` extraId) |  | 
| `Boolean` | IsLightDamaged(`Byte` lightId) |  | 
| `Boolean` | IsSpecialLightDamaged(`Byte` specialLightId) |  | 
| `Boolean` | IsWheelBurst(`Byte` wheelId) |  | 
| `Boolean` | IsWheelDetached(`Byte` wheelId) |  | 
| `Boolean` | IsWheelOnFire(`Byte` wheelId) |  | 
| `Boolean` | IsWindowDamaged(`Byte` windowId) |  | 
| `Boolean` | IsWindowOpened(`Byte` windowId) |  | 
| `void` | Remove() |  | 
| `void` | SetArmoredWindowHealth(`Byte` windowId, `Single` health) |  | 
| `void` | SetArmoredWindowShootCount(`Byte` windowId, `Byte` count) |  | 
| `void` | SetBumperDamageLevel(`Byte` bumperId, `Byte` damageLevel) |  | 
| `void` | SetDoorState(`Byte` doorId, `Byte` state) |  | 
| `void` | SetLightDamaged(`Byte` lightId, `Boolean` isDamaged) |  | 
| `Boolean` | SetMod(`Byte` category, `Byte` id) |  | 
| `void` | SetNeonActive(`Boolean` left, `Boolean` right, `Boolean` top, `Boolean` back) |  | 
| `void` | SetPartBulletHoles(`Byte` partId, `Byte` shootsCount) |  | 
| `void` | SetPartDamageLevel(`Byte` partId, `Byte` damage) |  | 
| `void` | SetSpecialLightDamaged(`Byte` specialLightId, `Boolean` isDamaged) |  | 
| `void` | SetWheelBurst(`Byte` wheelId, `Boolean` state) |  | 
| `void` | SetWheelDetached(`Byte` wheelId, `Boolean` state) |  | 
| `void` | SetWheelHasTire(`Byte` wheelId, `Boolean` state) |  | 
| `void` | SetWheelHealth(`Byte` wheelId, `Single` health) |  | 
| `void` | SetWheelOnFire(`Byte` wheelId, `Boolean` state) |  | 
| `void` | SetWheels(`Byte` type, `Byte` variation) |  | 
| `void` | SetWindowDamaged(`Byte` windowId, `Boolean` isDamaged) |  | 
| `void` | SetWindowOpened(`Byte` windowId, `Boolean` state) |  | 
| `void` | ToggleExtra(`Byte` extraId, `Boolean` state) |  | 


## `IVoiceChannel`

```csharp
public interface AltV.Net.Elements.Entities.IVoiceChannel
    : IBaseObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | IsSpatial |  | 
| `Single` | MaxDistance |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | AddPlayer(`IPlayer` player) |  | 
| `Boolean` | HasPlayer(`IPlayer` player) |  | 
| `Boolean` | IsPlayerMuted(`IPlayer` player) |  | 
| `void` | MutePlayer(`IPlayer` player) |  | 
| `void` | Remove() |  | 
| `void` | RemovePlayer(`IPlayer` player) |  | 
| `void` | UnmutePlayer(`IPlayer` player) |  | 


## `IWorldObject`

```csharp
public interface AltV.Net.Elements.Entities.IWorldObject
    : IBaseObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Int32` | Dimension |  | 
| `Position` | Position |  | 


## `Player`

```csharp
public class AltV.Net.Elements.Entities.Player
    : Entity, IBaseObject, IInternalBaseObject, IWorldObject, IEntity, IPlayer

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Position` | AimPosition |  | 
| `UInt16` | Ammo |  | 
| `UInt16` | Armor |  | 
| `String` | AuthToken |  | 
| `UInt32` | CurrentWeapon |  | 
| `Int32` | Dimension |  | 
| `IEntity` | EntityAimingAt |  | 
| `Position` | EntityAimOffset |  | 
| `UInt64` | HardwareIdExHash |  | 
| `UInt64` | HardwareIdHash |  | 
| `Rotation` | HeadRotation |  | 
| `UInt16` | Health |  | 
| `String` | Ip |  | 
| `Boolean` | IsAiming |  | 
| `Boolean` | IsConnected |  | 
| `Boolean` | IsDead |  | 
| `Boolean` | IsFlashlightActive |  | 
| `Boolean` | IsInRagdoll |  | 
| `Boolean` | IsInVehicle |  | 
| `Boolean` | IsJumping |  | 
| `Boolean` | IsReloading |  | 
| `Boolean` | IsShooting |  | 
| `UInt16` | MaxArmor |  | 
| `UInt16` | MaxHealth |  | 
| `UInt32` | Model |  | 
| `Single` | MoveSpeed |  | 
| `String` | Name |  | 
| `IPlayer` | NetworkOwner |  | 
| `UInt32` | Ping |  | 
| `Position` | Position |  | 
| `Rotation` | Rotation |  | 
| `Byte` | Seat |  | 
| `UInt64` | SocialClubId |  | 
| `IVehicle` | Vehicle |  | 
| `UInt32` | Weapon |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | AddWeaponComponent(`UInt32` weapon, `UInt32` weaponComponent) |  | 
| `void` | DeleteMetaData(`String` key) |  | 
| `void` | DeleteStreamSyncedMetaData(`String` key) |  | 
| `void` | DeleteSyncedMetaData(`String` key) |  | 
| `void` | Despawn() |  | 
| `void` | Emit(`String` eventName, `Object[]` args) |  | 
| `void` | GetCurrentWeaponComponents(`UInt32[]&` weaponComponents) |  | 
| `Byte` | GetCurrentWeaponTintIndex() |  | 
| `void` | GetMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | GetStreamSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | GetSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | GiveWeapon(`UInt32` weapon, `Int32` ammo, `Boolean` selectWeapon) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `Boolean` | HasStreamSyncedMetaData(`String` key) |  | 
| `Boolean` | HasSyncedMetaData(`String` key) |  | 
| `void` | InternalAddRef() |  | 
| `void` | InternalRemoveRef() |  | 
| `void` | Kick(`String` reason) |  | 
| `void` | RemoveAllWeapons() |  | 
| `void` | RemoveWeapon(`UInt32` weapon) |  | 
| `void` | RemoveWeaponComponent(`UInt32` weapon, `UInt32` weaponComponent) |  | 
| `void` | SetDateTime(`Int32` day, `Int32` month, `Int32` year, `Int32` hour, `Int32` minute, `Int32` second) |  | 
| `void` | SetMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | SetStreamSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | SetSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | SetWeaponTintIndex(`UInt32` weapon, `Byte` tintIndex) |  | 
| `void` | SetWeather(`UInt32` weather) |  | 
| `void` | Spawn(`Position` position, `UInt32` delayMs) |  | 
| `Boolean` | TryCreateRef(`PlayerRef&` playerRef) |  | 


Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt16` | GetId(`IntPtr` playerPointer) |  | 


## `PlayerExtensions`

```csharp
public static class AltV.Net.Elements.Entities.PlayerExtensions

```

Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | AddWeaponComponent(this `IPlayer` player, `WeaponModel` weaponModel, `UInt32` weaponComponent) |  | 
| `void` | GiveWeapon(this `IPlayer` player, `WeaponModel` weaponModel, `Int32` ammo, `Boolean` selectWeapon) |  | 
| `void` | RemoveWeapon(this `IPlayer` player, `WeaponModel` weaponModel) |  | 
| `void` | RemoveWeaponComponent(this `IPlayer` player, `WeaponModel` weaponModel, `UInt32` weaponComponent) |  | 
| `void` | SetDateTime(this `IPlayer` player, `DateTime` dateTime) |  | 
| `void` | SetWeaponTintIndex(this `IPlayer` player, `WeaponModel` weaponModel, `Byte` tintIndex) |  | 
| `void` | SetWeather(this `IPlayer` player, `WeatherType` weatherType) |  | 


## `Vehicle`

```csharp
public class AltV.Net.Elements.Entities.Vehicle
    : Entity, IBaseObject, IInternalBaseObject, IWorldObject, IEntity, IVehicle

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `String` | AppearanceData |  | 
| `UInt32` | BodyAdditionalHealth |  | 
| `UInt32` | BodyHealth |  | 
| `Boolean` | CustomTires |  | 
| `String` | DamageData |  | 
| `Byte` | DashboardColor |  | 
| `Int32` | Dimension |  | 
| `Byte` | DirtLevel |  | 
| `IPlayer` | Driver |  | 
| `Int32` | EngineHealth |  | 
| `Boolean` | EngineOn |  | 
| `Boolean` | HasArmoredWindows |  | 
| `Byte` | HeadlightColor |  | 
| `String` | HealthData |  | 
| `Byte` | InteriorColor |  | 
| `Boolean` | IsDaylightOn |  | 
| `Boolean` | IsDestroyed |  | 
| `Boolean` | IsFlamethrowerActive |  | 
| `Boolean` | IsHandbrakeActive |  | 
| `Boolean` | IsNeonActive |  | 
| `Boolean` | IsNightlightOn |  | 
| `Boolean` | IsPrimaryColorRgb |  | 
| `Boolean` | IsSecondaryColorRgb |  | 
| `Boolean` | IsTireSmokeColorCustom |  | 
| `Single` | LightsMultiplier |  | 
| `Byte` | Livery |  | 
| `VehicleLockState` | LockState |  | 
| `Boolean` | ManualEngineControl |  | 
| `UInt32` | Model |  | 
| `Byte` | ModKit |  | 
| `Byte` | ModKitsCount |  | 
| `Rgba` | NeonColor |  | 
| `IPlayer` | NetworkOwner |  | 
| `UInt32` | NumberplateIndex |  | 
| `String` | NumberplateText |  | 
| `Byte` | PearlColor |  | 
| `Int32` | PetrolTankHealth |  | 
| `Position` | Position |  | 
| `Byte` | PrimaryColor |  | 
| `Rgba` | PrimaryColorRgb |  | 
| `UInt32` | RadioStation |  | 
| `Byte` | RearWheel |  | 
| `Byte` | RepairsCount |  | 
| `Byte` | RoofLivery |  | 
| `Boolean` | RoofOpened |  | 
| `Rotation` | Rotation |  | 
| `String` | ScriptData |  | 
| `Byte` | SecondaryColor |  | 
| `Rgba` | SecondaryColorRgb |  | 
| `Boolean` | SirenActive |  | 
| `Byte` | SpecialDarkness |  | 
| `String` | State |  | 
| `Rgba` | TireSmokeColor |  | 
| `Byte` | WheelColor |  | 
| `Byte` | WheelsCount |  | 
| `Byte` | WheelType |  | 
| `Byte` | WheelVariation |  | 
| `Byte` | WindowTint |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | DeleteMetaData(`String` key) |  | 
| `void` | DeleteStreamSyncedMetaData(`String` key) |  | 
| `void` | DeleteSyncedMetaData(`String` key) |  | 
| `Boolean` | DoesWheelHasTire(`Byte` wheelId) |  | 
| `Single` | GetArmoredWindowHealth(`Byte` windowId) |  | 
| `Byte` | GetArmoredWindowShootCount(`Byte` windowId) |  | 
| `Byte` | GetBumperDamageLevel(`Byte` bumperId) |  | 
| `Byte` | GetDoorState(`Byte` doorId) |  | 
| `void` | GetMetaData(`String` key, `MValueConst&` value) |  | 
| `Byte` | GetMod(`Byte` category) |  | 
| `Byte` | GetModsCount(`Byte` category) |  | 
| `void` | GetNeonActive(`Boolean&` left, `Boolean&` right, `Boolean&` front, `Boolean&` back) |  | 
| `Byte` | GetPartBulletHoles(`Byte` partId) |  | 
| `Byte` | GetPartDamageLevel(`Byte` partId) |  | 
| `void` | GetStreamSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | GetSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `Single` | GetWheelHealth(`Byte` wheelId) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `Boolean` | HasStreamSyncedMetaData(`String` key) |  | 
| `Boolean` | HasSyncedMetaData(`String` key) |  | 
| `void` | InternalAddRef() |  | 
| `void` | InternalRemoveRef() |  | 
| `Boolean` | IsExtraOn(`Byte` extraId) |  | 
| `Boolean` | IsLightDamaged(`Byte` lightId) |  | 
| `Boolean` | IsSpecialLightDamaged(`Byte` specialLightId) |  | 
| `Boolean` | IsWheelBurst(`Byte` wheelId) |  | 
| `Boolean` | IsWheelDetached(`Byte` wheelId) |  | 
| `Boolean` | IsWheelOnFire(`Byte` wheelId) |  | 
| `Boolean` | IsWindowDamaged(`Byte` windowId) |  | 
| `Boolean` | IsWindowOpened(`Byte` windowId) |  | 
| `void` | Remove() |  | 
| `void` | SetArmoredWindowHealth(`Byte` windowId, `Single` health) |  | 
| `void` | SetArmoredWindowShootCount(`Byte` windowId, `Byte` count) |  | 
| `void` | SetBumperDamageLevel(`Byte` bumperId, `Byte` damageLevel) |  | 
| `void` | SetDoorState(`Byte` doorId, `Byte` state) |  | 
| `void` | SetLightDamaged(`Byte` lightId, `Boolean` isDamaged) |  | 
| `void` | SetMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | SetMod(`Byte` category, `Byte` id) |  | 
| `void` | SetNeonActive(`Boolean` left, `Boolean` right, `Boolean` front, `Boolean` back) |  | 
| `void` | SetPartBulletHoles(`Byte` partId, `Byte` shootsCount) |  | 
| `void` | SetPartDamageLevel(`Byte` partId, `Byte` damage) |  | 
| `void` | SetStreamSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | SetSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | SetWheelBurst(`Byte` wheelId, `Boolean` state) |  | 
| `void` | SetWheelDetached(`Byte` wheelId, `Boolean` state) |  | 
| `void` | SetWheelHasTire(`Byte` wheelId, `Boolean` state) |  | 
| `void` | SetWheelHealth(`Byte` wheelId, `Single` health) |  | 
| `void` | SetWheelOnFire(`Byte` wheelId, `Boolean` state) |  | 
| `void` | SetWheels(`Byte` type, `Byte` variation) |  | 
| `void` | SetWindowDamaged(`Byte` windowId, `Boolean` isDamaged) |  | 
| `void` | SetWindowOpened(`Byte` windowId, `Boolean` state) |  | 
| `void` | ToggleExtra(`Byte` extraId, `Boolean` state) |  | 


Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt16` | GetId(`IntPtr` vehiclePointer) |  | 


## `VehicleEnumExtensions`

```csharp
public static class AltV.Net.Elements.Entities.VehicleEnumExtensions

```

Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `VehicleBumperDamage` | GetBumperDamageLevel(this `IVehicle` vehicle, `VehicleBumper` bumper) |  | 
| `VehicleDoorState` | GetDoorState(this `IVehicle` vehicle, `VehicleDoor` door) |  | 
| `Byte` | GetMod(this `IVehicle` vehicle, `VehicleModType` category) |  | 
| `Byte` | GetModsCount(this `IVehicle` vehicle, `VehicleModType` category) |  | 
| `NumberPlateStyle` | GetNumberPlateStyle(this `IVehicle` vehicle) |  | 
| `Byte` | GetPartBulletHoles(this `IVehicle` vehicle, `VehiclePart` part) |  | 
| `VehiclePartDamage` | GetPartDamageLevel(this `IVehicle` vehicle, `VehiclePart` part) |  | 
| `RadioStation` | GetRadioStation(this `IVehicle` vehicle) |  | 
| `WindowTint` | GetWindowTint(this `IVehicle` vehicle) |  | 
| `void` | SetBumperDamageLevel(this `IVehicle` vehicle, `VehicleBumper` bumper, `VehicleBumperDamage` damageLevel) |  | 
| `void` | SetDoorState(this `IVehicle` vehicle, `VehicleDoor` door, `VehicleDoorState` state) |  | 
| `Boolean` | SetMod(this `IVehicle` vehicle, `VehicleModType` category, `Byte` id) |  | 
| `void` | SetNumberPlateStyle(this `IVehicle` vehicle, `NumberPlateStyle` numberPlateStyle) |  | 
| `void` | SetPartBulletHoles(this `IVehicle` vehicle, `VehiclePart` part, `Byte` shootsCount) |  | 
| `void` | SetPartDamageLevel(this `IVehicle` vehicle, `VehiclePart` part, `Byte` damage) |  | 
| `void` | SetPartDamageLevel(this `IVehicle` vehicle, `VehiclePart` part, `VehiclePartDamage` damage) |  | 
| `void` | SetRadioStation(this `IVehicle` vehicle, `RadioStation` radioStation) |  | 
| `void` | SetWindowTint(this `IVehicle` vehicle, `WindowTint` windowTint) |  | 


## `VoiceChannel`

```csharp
public class AltV.Net.Elements.Entities.VoiceChannel
    : BaseObject, IBaseObject, IInternalBaseObject, IVoiceChannel

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | IsSpatial |  | 
| `Single` | MaxDistance |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | AddPlayer(`IPlayer` player) |  | 
| `void` | DeleteMetaData(`String` key) |  | 
| `void` | GetMetaData(`String` key, `MValueConst&` value) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `Boolean` | HasPlayer(`IPlayer` player) |  | 
| `void` | InternalAddRef() |  | 
| `void` | InternalRemoveRef() |  | 
| `Boolean` | IsPlayerMuted(`IPlayer` player) |  | 
| `void` | MutePlayer(`IPlayer` player) |  | 
| `void` | Remove() |  | 
| `void` | RemovePlayer(`IPlayer` player) |  | 
| `void` | SetMetaData(`String` key, `MValueConst&` value) |  | 
| `void` | UnmutePlayer(`IPlayer` player) |  | 


## `WorldObject`

```csharp
public abstract class AltV.Net.Elements.Entities.WorldObject
    : BaseObject, IBaseObject, IInternalBaseObject, IWorldObject

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Int32` | Dimension |  | 
| `Position` | Position |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | CheckIfEntityExists() |  | 


## `WorldObjectExtensions`

```csharp
public static class AltV.Net.Elements.Entities.WorldObjectExtensions

```

Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `ValueTuple<Single, Single, Single>` | GetPosition(this `IWorldObject` worldObject) |  | 
| `void` | SetPosition(this `IWorldObject` worldObject, `ValueTuple<Single, Single, Single>` position) |  | 
| `void` | SetPosition(this `IWorldObject` worldObject, `Single` x, `Single` y, `Single` z) |  | 


## `WorldObjectRemovedException`

```csharp
public class AltV.Net.Elements.Entities.WorldObjectRemovedException
    : BaseObjectRemovedException, ISerializable

```

