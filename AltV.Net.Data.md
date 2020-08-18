## `BodyPart`

```csharp
public enum AltV.Net.Data.BodyPart
    : Enum, IComparable, IFormattable, IConvertible

```

Enum

| Value | Name | Summary | 
| --- | --- | --- | 
| `-1` | Unknown |  | 
| `0` | Pelvis |  | 
| `1` | LeftHip |  | 
| `2` | LeftLeg |  | 
| `3` | LeftFoot |  | 
| `4` | RightHip |  | 
| `5` | RightLeg |  | 
| `6` | RightFoot |  | 
| `7` | LowerTorso |  | 
| `8` | UpperTorso |  | 
| `9` | Chest |  | 
| `10` | UnderNeck |  | 
| `11` | LeftShoulder |  | 
| `12` | LeftUpperArm |  | 
| `13` | LeftElbow |  | 
| `14` | LeftWrist |  | 
| `15` | RightShoulder |  | 
| `16` | RightUpperArm |  | 
| `17` | RightElbow |  | 
| `18` | RightWrist |  | 
| `19` | Neck |  | 
| `20` | Head |  | 


## `DegreeRotation`

```csharp
public struct AltV.Net.Data.DegreeRotation

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Single` | Pitch |  | 
| `Single` | Roll |  | 
| `Single` | Yaw |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `String` | ToString() |  | 


Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `DegreeRotation` | Zero |  | 


## `Dimension`

```csharp
public static class AltV.Net.Data.Dimension

```

Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Int32` | DefaultDimension |  | 
| `Int32` | GlobalDimension |  | 


## `ExplosionType`

```csharp
public enum AltV.Net.Data.ExplosionType
    : Enum, IComparable, IFormattable, IConvertible

```

Enum

| Value | Name | Summary | 
| --- | --- | --- | 
| `-1` | Unknown |  | 
| `0` | Grenade |  | 
| `1` | GrenadeLauncher |  | 
| `2` | StickyBomb |  | 
| `3` | Molotov |  | 
| `4` | Rocket |  | 
| `5` | TankShell |  | 
| `6` | HiOctane |  | 
| `7` | Car |  | 
| `8` | Plane |  | 
| `9` | PetrolPump |  | 
| `10` | Bike |  | 
| `11` | DirSteam |  | 
| `12` | DirFlame |  | 
| `13` | DirWaterHydrant |  | 
| `14` | DirGasCanister |  | 
| `15` | Boat |  | 
| `16` | ShipDestroy |  | 
| `17` | Truck |  | 
| `18` | Bullet |  | 
| `19` | SmokeGrenadeLauncher |  | 
| `20` | SmokeGrenade |  | 
| `21` | BzGas |  | 
| `22` | Flare |  | 
| `23` | GasCanister |  | 
| `24` | Extinguisher |  | 
| `25` | Programmablear |  | 
| `26` | Train |  | 
| `27` | Barrel |  | 
| `28` | Propane |  | 
| `29` | Blimp |  | 
| `30` | DirFlameExplode |  | 
| `31` | Tanker |  | 
| `32` | PlaneRocket |  | 
| `33` | VehicleBullet |  | 
| `34` | GasTank |  | 
| `35` | Firework |  | 
| `36` | Snowball |  | 
| `37` | ProxMine |  | 
| `38` | ValkyrieCannon |  | 


## `Position`

```csharp
public struct AltV.Net.Data.Position
    : IEquatable<Position>

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Single` | X |  | 
| `Single` | Y |  | 
| `Single` | Z |  | 


Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Position` | Normalized |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Single` | Distance(`Position` b) |  | 
| `Boolean` | Equals(`Object` obj) |  | 
| `Boolean` | Equals(`Position` other) |  | 
| `Int32` | GetHashCode() |  | 
| `Single` | GetMagnitude() |  | 
| `void` | Normalize() |  | 
| `String` | ToString() |  | 


Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Single` | KEpsilon |  | 
| `Single` | TOLERANCE |  | 
| `Position` | Zero |  | 


Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Position` | Cross(`Position` lhs, `Position` rhs) |  | 
| `Position` | LerpUnclamped(`Position` a, `Position` b, `Single` t) |  | 
| `Position` | MoveTowards(`Position` current, `Position` target, `Single` maxDistanceDelta) |  | 
| `Position` | Normalize(`Position` value) |  | 
| `Position` | Scale(`Position` a, `Position` b) |  | 


## `Rgba`

```csharp
public struct AltV.Net.Data.Rgba
    : IEquatable<Rgba>

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Byte` | A |  | 
| `Byte` | B |  | 
| `Byte` | G |  | 
| `Byte` | R |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | Equals(`Object` obj) |  | 
| `Boolean` | Equals(`Rgba` other) |  | 
| `Int32` | GetHashCode() |  | 
| `String` | ToString() |  | 


Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Rgba` | Zero |  | 


## `Rotation`

```csharp
public struct AltV.Net.Data.Rotation
    : IEquatable<Rotation>

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Single` | Pitch |  | 
| `Single` | Roll |  | 
| `Single` | Yaw |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | Equals(`Object` obj) |  | 
| `Boolean` | Equals(`Rotation` other) |  | 
| `Int32` | GetHashCode() |  | 
| `String` | ToString() |  | 


Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Rotation` | Zero |  | 


## `VehicleConstants`

```csharp
public static class AltV.Net.Data.VehicleConstants

```

Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Byte` | MaxLights |  | 
| `Byte` | MaxSpecialLights |  | 
| `Byte` | MaxWindows |  | 


## `Weapons`

```csharp
public static class AltV.Net.Data.Weapons

```

Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt32` | AssaultRifle |  | 
| `UInt32` | BarbedWire |  | 
| `UInt32` | Bat |  | 
| `UInt32` | Bleeding |  | 
| `UInt32` | Bottle |  | 
| `UInt32` | CarbineRifle |  | 
| `UInt32` | CombatPdw |  | 
| `UInt32` | Drowning |  | 
| `UInt32` | DrowningInVehicle |  | 
| `UInt32` | ElectricFence |  | 
| `UInt32` | Exhaustion |  | 
| `UInt32` | Explosion |  | 
| `UInt32` | Fall |  | 
| `UInt32` | Fire |  | 
| `UInt32` | Grenade |  | 
| `UInt32` | HeavyPistol |  | 
| `UInt32` | Knife |  | 
| `UInt32` | MicroSmg |  | 
| `UInt32` | Pistol |  | 
| `UInt32` | PumpShotgun |  | 
| `UInt32` | RammedByCar |  | 
| `UInt32` | Revolver |  | 
| `UInt32` | RunOverByCar |  | 
| `UInt32` | Smg |  | 
| `UInt32` | Wrench |  | 


