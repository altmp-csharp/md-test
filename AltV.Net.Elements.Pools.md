## `BaseBaseObjectPool`

```csharp
public class AltV.Net.Elements.Pools.BaseBaseObjectPool
    : IBaseBaseObjectPool

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | Get(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `IBaseObject&` entity) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `IBaseObject&` entity) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `UInt16` entityId, `IBaseObject&` entity) |  | 
| `Boolean` | Remove(`IBaseObject` entity) |  | 
| `Boolean` | Remove(`IntPtr` entityPointer, `BaseObjectType` baseObjectType) |  | 


## `BaseEntityPool`

```csharp
public class AltV.Net.Elements.Pools.BaseEntityPool
    : IBaseEntityPool

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | Get(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `IEntity&` entity) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `IEntity&` entity) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `UInt16` entityId, `IEntity&` entity) |  | 
| `Boolean` | Remove(`IEntity` entity) |  | 
| `Boolean` | Remove(`IntPtr` entityPointer, `BaseObjectType` baseObjectType) |  | 


## `BaseObjectPool<TBaseObject>`

```csharp
public abstract class AltV.Net.Elements.Pools.BaseObjectPool<TBaseObject>
    : IBaseObjectPool<TBaseObject>

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | Add(`TBaseObject` entity) |  | 
| `void` | Create(`IntPtr` entityPointer) |  | 
| `void` | Create(`IntPtr` entityPointer, `TBaseObject&` entity) |  | 
| `void` | ForEach(`IBaseObjectCallback<TBaseObject>` baseObjectCallback) |  | 
| `Task` | ForEach(`IAsyncBaseObjectCallback<TBaseObject>` asyncBaseObjectCallback) |  | 
| `Boolean` | Get(`IntPtr` entityPointer, `TBaseObject&` entity) |  | 
| `ICollection<TBaseObject>` | GetAllObjects() |  | 
| `KeyValuePair`2[]` | GetObjectsArray() |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `TBaseObject&` entity) |  | 
| `void` | OnAdd(`TBaseObject` entity) |  | 
| `void` | OnRemove(`TBaseObject` entity) |  | 
| `Boolean` | Remove(`TBaseObject` entity) |  | 
| `Boolean` | Remove(`IntPtr` entityPointer) |  | 


Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | SetEntityNoLongerExists(`TBaseObject` entity) |  | 


## `BlipPool`

```csharp
public class AltV.Net.Elements.Pools.BlipPool
    : BaseObjectPool<IBlip>, IBaseObjectPool<IBlip>

```

## `CheckpointPool`

```csharp
public class AltV.Net.Elements.Pools.CheckpointPool
    : BaseObjectPool<ICheckpoint>, IBaseObjectPool<ICheckpoint>

```

## `ColShapePool`

```csharp
public class AltV.Net.Elements.Pools.ColShapePool
    : BaseObjectPool<IColShape>, IBaseObjectPool<IColShape>

```

## `EntityPool<TEntity>`

```csharp
public abstract class AltV.Net.Elements.Pools.EntityPool<TEntity>
    : IEntityPool<TEntity>

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | Add(`TEntity` entity) |  | 
| `void` | Create(`IntPtr` entityPointer, `UInt16` id) |  | 
| `void` | Create(`IntPtr` entityPointer, `UInt16` id, `TEntity&` entity) |  | 
| `void` | Create(`IntPtr` entityPointer, `TEntity&` entity) |  | 
| `void` | ForEach(`IBaseObjectCallback<TEntity>` baseObjectCallback) |  | 
| `Task` | ForEach(`IAsyncBaseObjectCallback<TEntity>` asyncBaseObjectCallback) |  | 
| `Boolean` | Get(`IntPtr` entityPointer, `TEntity&` entity) |  | 
| `ICollection<TEntity>` | GetAllEntities() |  | 
| `KeyValuePair`2[]` | GetEntitiesArray() |  | 
| `UInt16` | GetId(`IntPtr` entityPointer) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `TEntity&` entity) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `UInt16` entityId, `TEntity&` entity) |  | 
| `void` | OnAdd(`TEntity` entity) |  | 
| `void` | OnRemove(`TEntity` entity) |  | 
| `Boolean` | Remove(`TEntity` entity) |  | 
| `Boolean` | Remove(`IntPtr` entityPointer) |  | 


## `IAsyncBaseObjectCallback<TBaseObject>`

```csharp
public interface AltV.Net.Elements.Pools.IAsyncBaseObjectCallback<TBaseObject>

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Task` | OnBaseObject(`TBaseObject` baseObject) |  | 


## `IBaseObjectCallback<TBaseObject>`

```csharp
public interface AltV.Net.Elements.Pools.IBaseObjectCallback<TBaseObject>

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | OnBaseObject(`TBaseObject` baseObject) |  | 


## `NativeResourcePool`

```csharp
public class AltV.Net.Elements.Pools.NativeResourcePool
    : INativeResourcePool

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | GetOrCreate(`IntPtr` corePointer, `IntPtr` resourcePointer, `INativeResource&` resource) |  | 


## `PlayerPool`

```csharp
public class AltV.Net.Elements.Pools.PlayerPool
    : EntityPool<IPlayer>, IEntityPool<IPlayer>

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt16` | GetId(`IntPtr` entityPointer) |  | 


## `VehiclePool`

```csharp
public class AltV.Net.Elements.Pools.VehiclePool
    : EntityPool<IVehicle>, IEntityPool<IVehicle>

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt16` | GetId(`IntPtr` entityPointer) |  | 


## `VoiceChannelPool`

```csharp
public class AltV.Net.Elements.Pools.VoiceChannelPool
    : BaseObjectPool<IVoiceChannel>, IBaseObjectPool<IVoiceChannel>

```

