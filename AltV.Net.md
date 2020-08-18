## `Alt`

```csharp
public static class AltV.Net.Alt

```

Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Module` | Module |  | 


Static Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `IEnumerable<Assembly>` | Assemblies |  | 
| `IServer` | Core |  | 
| `Boolean` | IsDebug |  | 
| `IServer` | Server |  | 


Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `IBlip` | CreateBlip(`IPlayer` player, `Byte` type, `Position` pos) |  | 
| `IBlip` | CreateBlip(`IPlayer` player, `Byte` type, `IEntity` entityAttach) |  | 
| `IBlip` | CreateBlip(`IPlayer` player, `BlipType` type, `Position` pos) |  | 
| `IBlip` | CreateBlip(`IPlayer` player, `BlipType` type, `IEntity` entityAttach) |  | 
| `IBlip` | CreateBlip(`Byte` type, `Position` pos) |  | 
| `IBlip` | CreateBlip(`Byte` type, `IEntity` entityAttach) |  | 
| `IBlip` | CreateBlip(`BlipType` type, `Position` pos) |  | 
| `IBlip` | CreateBlip(`BlipType` type, `IEntity` entityAttach) |  | 
| `ICheckpoint` | CreateCheckpoint(`Byte` type, `Position` pos, `Single` radius, `Single` height, `Rgba` color) |  | 
| `ICheckpoint` | CreateCheckpoint(`CheckpointType` type, `Position` pos, `Single` radius, `Single` height, `Rgba` color) |  | 
| `IColShape` | CreateColShapeCircle(`Position` pos, `Single` radius) |  | 
| `IColShape` | CreateColShapeCube(`Position` pos, `Position` pos2) |  | 
| `IColShape` | CreateColShapeCylinder(`Position` pos, `Single` radius, `Single` height) |  | 
| `IColShape` | CreateColShapeRectangle(`Single` x1, `Single` y1, `Single` x2, `Single` y2, `Single` z) |  | 
| `IColShape` | CreateColShapeSphere(`Position` pos, `Single` radius) |  | 
| `IVehicle` | CreateVehicle(`VehicleModel` model, `Position` pos, `Rotation` rotation) |  | 
| `IVehicle` | CreateVehicle(`String` model, `Position` pos, `Rotation` rotation) |  | 
| `IVehicle` | CreateVehicle(`UInt32` model, `Position` pos, `Rotation` rotation) |  | 
| `IVoiceChannel` | CreateVoiceChannel(`Boolean` spatial, `Single` maxDistance) |  | 
| `void` | DeleteMetaData(`String` key) |  | 
| `void` | DeleteSyncedMetaData(`String` key) |  | 
| `void` | Emit(`String` eventName, `Object[]` args) |  | 
| `void` | EmitAllClients(`String` eventName, `Object[]` args) |  | 
| `void` | Export(`String` key, `Func<T1, T2>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7, T8>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` value) |  | 
| `void` | Export(`String` key, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` value) |  | 
| `void` | Export(`String` key, `Object` value) |  | 
| `void` | Export(`String` key, `Boolean` value) |  | 
| `void` | Export(`String` key, `Int32` value) |  | 
| `void` | Export(`String` key, `Int64` value) |  | 
| `void` | Export(`String` key, `UInt32` value) |  | 
| `void` | Export(`String` key, `UInt64` value) |  | 
| `void` | Export(`String` key, `Double` value) |  | 
| `void` | Export(`String` key, `String` value) |  | 
| `void` | Export(`String` key, `Delegate` value) |  | 
| `void` | Export(`String` key, `Action` value) |  | 
| `void` | Export(`String` key, `Action<T1>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6, T7>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6, T7, T8>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` value) |  | 
| `void` | Export(`String` key, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` value) |  | 
| `void` | Export(`String` key, `Func<T1>` value) |  | 
| `void` | ForEachBlips(`IBaseObjectCallback<IBlip>` baseObjectCallback) |  | 
| `Task` | ForEachBlips(`IAsyncBaseObjectCallback<IBlip>` baseObjectCallback) |  | 
| `void` | ForEachCheckpoints(`IBaseObjectCallback<ICheckpoint>` baseObjectCallback) |  | 
| `Task` | ForEachCheckpoints(`IAsyncBaseObjectCallback<ICheckpoint>` baseObjectCallback) |  | 
| `void` | ForEachColShapes(`IBaseObjectCallback<IColShape>` baseObjectCallback) |  | 
| `Task` | ForEachColShapes(`IAsyncBaseObjectCallback<IColShape>` baseObjectCallback) |  | 
| `void` | ForEachPlayers(`IBaseObjectCallback<IPlayer>` baseObjectCallback) |  | 
| `Task` | ForEachPlayers(`IAsyncBaseObjectCallback<IPlayer>` baseObjectCallback) |  | 
| `void` | ForEachVehicles(`IBaseObjectCallback<IVehicle>` baseObjectCallback) |  | 
| `Task` | ForEachVehicles(`IAsyncBaseObjectCallback<IVehicle>` baseObjectCallback) |  | 
| `void` | ForEachVoiceChannels(`IBaseObjectCallback<IVoiceChannel>` baseObjectCallback) |  | 
| `Task` | ForEachVoiceChannels(`IAsyncBaseObjectCallback<IVoiceChannel>` baseObjectCallback) |  | 
| `ICollection<IBlip>` | GetAllBlips() |  | 
| `ICollection<ICheckpoint>` | GetAllCheckpoints() |  | 
| `ICollection<IColShape>` | GetAllColShapes() |  | 
| `ICollection<IPlayer>` | GetAllPlayers() |  | 
| `ICollection<IVehicle>` | GetAllVehicles() |  | 
| `ICollection<IVoiceChannel>` | GetAllVoiceChannels() |  | 
| `KeyValuePair`2[]` | GetBlipsArray() |  | 
| `KeyValuePair`2[]` | GetCheckpointsArray() |  | 
| `KeyValuePair`2[]` | GetColShapesArray() |  | 
| `Boolean` | GetMetaData(`String` key, `Int32&` result) |  | 
| `Boolean` | GetMetaData(`String` key, `UInt32&` result) |  | 
| `Boolean` | GetMetaData(`String` key, `Single&` result) |  | 
| `Boolean` | GetMetaData(`String` key, `T&` result) |  | 
| `KeyValuePair`2[]` | GetPlayersArray() |  | 
| `Boolean` | GetSyncedMetaData(`String` key, `Int32&` result) |  | 
| `Boolean` | GetSyncedMetaData(`String` key, `UInt32&` result) |  | 
| `Boolean` | GetSyncedMetaData(`String` key, `Single&` result) |  | 
| `Boolean` | GetSyncedMetaData(`String` key, `T&` result) |  | 
| `KeyValuePair`2[]` | GetVehiclesArray() |  | 
| `KeyValuePair`2[]` | GetVoiceChannelsArray() |  | 
| `UInt32` | Hash(`String` stringToHash) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `Boolean` | HasSyncedMetaData(`String` key) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`2&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`3&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`4&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`5&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`6&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`7&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`8&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`9&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`10&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`11&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`12&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`13&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`14&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`15&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`16&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`17&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Boolean&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Int32&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Int64&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `UInt32&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `UInt64&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Double&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Object&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `String&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `MValueConst&` mValue) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Type` type, `MValueConst&` mValue) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`1&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`2&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`3&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`4&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`5&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`6&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`7&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`8&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`9&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`10&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`11&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`12&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`13&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`14&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`15&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Action`16&` value) |  | 
| `Boolean` | Import(`String` resourceName, `String` key, `Func`1&` value) |  | 
| `void` | Init(`Module` module) |  | 
| `Assembly` | LoadAssemblyFromName(`AssemblyName` assemblyName) |  | 
| `Assembly` | LoadAssemblyFromNativeImagePath(`String` nativeImagePath, `String` assemblyPath) |  | 
| `Assembly` | LoadAssemblyFromPath(`String` path) |  | 
| `Assembly` | LoadAssemblyFromStream(`Stream` stream) |  | 
| `Assembly` | LoadAssemblyFromStream(`Stream` stream, `Stream` assemblySymbols) |  | 
| `void` | Log(`String` message) |  | 
| `void` | LogColored(`ColoredMessage` message) |  | 
| `void` | LogFast(`String` message) |  | 
| `void` | OffClient(`String` eventName, `Action` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` action) |  | 
| `void` | OffClient(`String` eventName, `Action` action, `ClientEventParser<Action>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1>` action, `ClientEventParser<Action<T1>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2>` action, `ClientEventParser<Action<T1, T2>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3>` action, `ClientEventParser<Action<T1, T2, T3>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4>` action, `ClientEventParser<Action<T1, T2, T3, T4>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1>` action, `ClientEventParser<Func<T1>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2>` action, `ClientEventParser<Func<T1, T2>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3>` action, `ClientEventParser<Func<T1, T2, T3>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4>` action, `ClientEventParser<Func<T1, T2, T3, T4>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>>` parser) |  | 
| `void` | OffClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` action) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4>` action, `ClientEventParser<Func<T1, T2, T3, T4>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action` action, `ServerEventParser<Action>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1>` action, `ServerEventParser<Action<T1>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2>` action, `ServerEventParser<Action<T1, T2>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3>` action, `ServerEventParser<Action<T1, T2, T3>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4>` action, `ServerEventParser<Action<T1, T2, T3, T4>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1>` action, `ServerEventParser<Func<T1>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2>` action, `ServerEventParser<Func<T1, T2>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3>` action, `ServerEventParser<Func<T1, T2, T3>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4>` action, `ServerEventParser<Func<T1, T2, T3, T4>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action` action, `ClientEventParser<Action>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1>` action, `ClientEventParser<Action<T1>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2>` action, `ClientEventParser<Action<T1, T2>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3>` action, `ClientEventParser<Action<T1, T2, T3>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4>` action, `ClientEventParser<Action<T1, T2, T3, T4>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1>` action, `ClientEventParser<Func<T1>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2>` action, `ClientEventParser<Func<T1, T2>>` parser) |  | 
| `void` | OffServer(`String` eventName, `Func<T1, T2, T3>` action, `ClientEventParser<Func<T1, T2, T3>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` action) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3>` action, `ClientEventParser<Func<T1, T2, T3>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4>` action, `ClientEventParser<Func<T1, T2, T3, T4>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` action, `ClientEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action` action, `ClientEventParser<Action>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1>` action, `ClientEventParser<Action<T1>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2>` action, `ClientEventParser<Action<T1, T2>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3>` action, `ClientEventParser<Action<T1, T2, T3>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4>` action, `ClientEventParser<Action<T1, T2, T3, T4>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action, `ClientEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1>` action, `ClientEventParser<Func<T1>>` parser) |  | 
| `void` | OnClient(`String` eventName, `Func<T1, T2>` action, `ClientEventParser<Func<T1, T2>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` action) |  | 
| `void` | OnServer(`String` eventName, `Action` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action) |  | 
| `void` | OnServer(`String` eventName, `Func<T1>` action) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3>` action, `ServerEventParser<Action<T1, T2, T3>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4>` action, `ServerEventParser<Action<T1, T2, T3, T4>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action, `ServerEventParser<Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1>` action, `ServerEventParser<Func<T1>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2>` action, `ServerEventParser<Func<T1, T2>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3>` action, `ServerEventParser<Func<T1, T2, T3>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4>` action, `ServerEventParser<Func<T1, T2, T3, T4>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` action, `ServerEventParser<Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action` action, `ServerEventParser<Action>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1>` action, `ServerEventParser<Action<T1>>` parser) |  | 
| `void` | OnServer(`String` eventName, `Action<T1, T2>` action, `ServerEventParser<Action<T1, T2>>` parser) |  | 
| `void` | RegisterEvents(`Object` target) |  | 
| `void` | RemoveBlip(`IBlip` blip) |  | 
| `void` | RemoveCheckpoint(`ICheckpoint` checkpoint) |  | 
| `void` | RemoveColShape(`IColShape` colShape) |  | 
| `void` | RemoveVehicle(`IVehicle` vehicle) |  | 
| `void` | RemoveVoiceChannel(`IVoiceChannel` channel) |  | 
| `void` | SetMetaData(`String` key, `Object` value) |  | 
| `void` | SetSyncedMetaData(`String` key, `Object` value) |  | 


Static Events

| Type | Name | Summary | 
| --- | --- | --- | 
| `ResourceEventDelegate` | OnAnyResourceError |  | 
| `ResourceEventDelegate` | OnAnyResourceStart |  | 
| `ResourceEventDelegate` | OnAnyResourceStop |  | 
| `CheckpointDelegate` | OnCheckpoint |  | 
| `ColShapeDelegate` | OnColShape |  | 
| `ConsoleCommandDelegate` | OnConsoleCommand |  | 
| `ExplosionDelegate` | OnExplosion |  | 
| `MetaDataChangeDelegate` | OnMetaDataChange |  | 
| `PlayerChangeVehicleSeatDelegate` | OnPlayerChangeVehicleSeat |  | 
| `PlayerConnectDelegate` | OnPlayerConnect |  | 
| `PlayerClientCustomEventDelegate` | OnPlayerCustomEvent |  | 
| `PlayerDamageDelegate` | OnPlayerDamage |  | 
| `PlayerDeadDelegate` | OnPlayerDead |  | 
| `PlayerDisconnectDelegate` | OnPlayerDisconnect |  | 
| `PlayerEnterVehicleDelegate` | OnPlayerEnterVehicle |  | 
| `PlayerClientEventDelegate` | OnPlayerEvent |  | 
| `PlayerLeaveVehicleDelegate` | OnPlayerLeaveVehicle |  | 
| `PlayerRemoveDelegate` | OnPlayerRemove |  | 
| `ServerCustomEventEventDelegate` | OnServerCustomEvent |  | 
| `ServerEventEventDelegate` | OnServerEvent |  | 
| `MetaDataChangeDelegate` | OnSyncedMetaDataChange |  | 
| `VehicleDestroyDelegate` | OnVehicleDestroy |  | 
| `VehicleRemoveDelegate` | OnVehicleRemove |  | 
| `WeaponDamageDelegate` | OnWeaponDamage |  | 


## `AltTrace`

```csharp
public static class AltV.Net.AltTrace

```

Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | Start(`String` traceFileName, `TraceFileFormat` traceFileFormat = NetTrace) |  | 
| `void` | Stop() |  | 


Static Events

| Type | Name | Summary | 
| --- | --- | --- | 
| `Action<Int64>` | OnTraceFileSizeChange |  | 


## `ClientEventAttribute`

```csharp
public class AltV.Net.ClientEventAttribute
    : Attribute

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `String` | Name |  | 


## `CSharpResourceImpl`

```csharp
public class AltV.Net.CSharpResourceImpl
    : IDisposable

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `IntPtr` | NativePointer |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `IntPtr` | CreateInvoker(`MValueFunctionCallback` function) |  | 
| `void` | DestroyInvoker(`IntPtr` invoker) |  | 
| `void` | Dispose() |  | 
| `void` | SetDelegates(`MainDelegate` onStart) |  | 


## `Function`

```csharp
public class AltV.Net.Function

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Object[]` | CalculateInvokeValues(`IPlayer` player, `MValueConst[]` values) |  | 
| `Object[]` | CalculateInvokeValues(`MValueConst[]` values) |  | 
| `Object[]` | CalculateInvokeValues(`Object[]` values) |  | 
| `Object[]` | CalculateInvokeValues(`IPlayer` player, `Object[]` values) |  | 
| `Object[]` | CalculateInvokeValues(`IPlayer` player, `String[]` values) |  | 
| `Object` | Call(`MValueConst[]` values) |  | 
| `Object` | Call(`IPlayer` player, `MValueConst[]` values) |  | 
| `Object` | Call(`IPlayer` player, `String[]` values) |  | 
| `IntPtr` | Call(`IntPtr` pointer, `Int64` size) |  | 
| `void` | Invoke(`Object[]` invokeValues, `MValueConst&` resultMValue) |  | 
| `Task<MValueConst>` | InvokeAsync(`Object[]` invokeValues) |  | 
| `void` | InvokeNoResult(`Object[]` invokeValues) |  | 
| `Task` | InvokeTaskOrNull(`Object[]` invokeValues) |  | 


Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Function` | Create(`Action` function) |  | 
| `Function` | Create(`Action<T1>` function) |  | 
| `Function` | Create(`Action<T1, T2>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6, T7>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6, T7, T8>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6, T7, T8, T9>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` function) |  | 
| `Function` | Create(`Action<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` function) |  | 
| `Function` | Create(`Func<T1>` function) |  | 
| `Function` | Create(`Func<T1, T2>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7, T8>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7, T8, T9>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16>` function) |  | 
| `Function` | Create(`Func<T1, T2, T3, T4, T5, T6, T7, T8, T9, T10, T11, T12, T13, T14, T15, T16, TResult>` function) |  | 
| `Function` | Create(`T` func) |  | 


## `IBaseBaseObjectPool`

```csharp
public interface AltV.Net.IBaseBaseObjectPool

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | Get(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `IBaseObject&` baseObject) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `UInt16` entityId, `IBaseObject&` baseObject) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `IBaseObject&` baseObject) |  | 
| `Boolean` | Remove(`IBaseObject` baseObject) |  | 
| `Boolean` | Remove(`IntPtr` entityPointer, `BaseObjectType` baseObjectType) |  | 


## `IBaseEntityPool`

```csharp
public interface AltV.Net.IBaseEntityPool

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | Get(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `IEntity&` baseObject) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `UInt16` entityId, `IEntity&` baseObject) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `BaseObjectType` baseObjectType, `IEntity&` baseObject) |  | 
| `Boolean` | Remove(`IEntity` baseObject) |  | 
| `Boolean` | Remove(`IntPtr` entityPointer, `BaseObjectType` baseObjectType) |  | 


## `IBaseObjectFactory<TBaseObject>`

```csharp
public interface AltV.Net.IBaseObjectFactory<TBaseObject>

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `TBaseObject` | Create(`IntPtr` baseObjectPointer) |  | 


## `IBaseObjectPool<TBaseObject>`

```csharp
public interface AltV.Net.IBaseObjectPool<TBaseObject>

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
| `Boolean` | Remove(`TBaseObject` entity) |  | 
| `Boolean` | Remove(`IntPtr` entityPointer) |  | 


## `IEntityFactory<TEntity>`

```csharp
public interface AltV.Net.IEntityFactory<TEntity>

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `TEntity` | Create(`IntPtr` entityPointer, `UInt16` id) |  | 


## `IEntityPool<TEntity>`

```csharp
public interface AltV.Net.IEntityPool<TEntity>

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
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `UInt16` entityId, `TEntity&` entity) |  | 
| `Boolean` | GetOrCreate(`IntPtr` entityPointer, `TEntity&` entity) |  | 
| `void` | OnAdd(`TEntity` entity) |  | 
| `void` | OnRemove(`TEntity` entity) |  | 
| `Boolean` | Remove(`TEntity` entity) |  | 
| `Boolean` | Remove(`IntPtr` entityPointer) |  | 


## `IModule`

```csharp
public interface AltV.Net.IModule

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | OnScriptsStarted(`IScript[]` scripts) |  | 
| `void` | OnStop() |  | 


## `IMValueAdapter<T>`

```csharp
public interface AltV.Net.IMValueAdapter<T>
    : IMValueBaseAdapter

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `T` | FromMValue(`IMValueReader` reader) |  | 
| `void` | ToMValue(`T` value, `IMValueWriter` writer) |  | 


## `IMValueBaseAdapter`

```csharp
public interface AltV.Net.IMValueBaseAdapter

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Object` | FromMValue(`IMValueReader` reader) |  | 
| `void` | ToMValue(`Object` obj, `IMValueWriter` writer) |  | 


## `IMValueConvertible`

```csharp
public interface AltV.Net.IMValueConvertible

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `IMValueBaseAdapter` | GetAdapter() |  | 


## `IMValueDeserializer<T>`

```csharp
public interface AltV.Net.IMValueDeserializer<T>

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `T` | FromMValue(`IMValueReader` reader) |  | 


## `IMValueReader`

```csharp
public interface AltV.Net.IMValueReader
    : IDisposable

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | BeginArray() |  | 
| `void` | BeginObject() |  | 
| `void` | EndArray() |  | 
| `void` | EndObject() |  | 
| `Boolean` | HasNext() |  | 
| `Boolean` | NextBool() |  | 
| `Double` | NextDouble() |  | 
| `Int32` | NextInt() |  | 
| `Int64` | NextLong() |  | 
| `String` | NextName() |  | 
| `String` | NextString() |  | 
| `UInt32` | NextUInt() |  | 
| `UInt64` | NextULong() |  | 
| `MValueReaderToken` | Peek() |  | 
| `void` | SkipName() |  | 
| `void` | SkipValue() |  | 


## `IMValueSerializer<T>`

```csharp
public interface AltV.Net.IMValueSerializer<T>

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | ToMValue(`T` value, `IMValueWriter` writer) |  | 


## `IMValueWriter`

```csharp
public interface AltV.Net.IMValueWriter

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | BeginArray() |  | 
| `void` | BeginObject() |  | 
| `void` | EndArray() |  | 
| `void` | EndObject() |  | 
| `void` | Name(`String` name) |  | 
| `void` | Value(`Boolean` value) |  | 
| `void` | Value(`Int32` value) |  | 
| `void` | Value(`Int64` value) |  | 
| `void` | Value(`UInt32` value) |  | 
| `void` | Value(`UInt64` value) |  | 
| `void` | Value(`Double` value) |  | 
| `void` | Value(`String` value) |  | 
| `void` | Value(`ICheckpoint` value) |  | 
| `void` | Value(`IBlip` value) |  | 
| `void` | Value(`IVehicle` value) |  | 
| `void` | Value(`IPlayer` value) |  | 


## `INativeResource`

```csharp
public interface AltV.Net.INativeResource

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `CSharpResourceImpl` | CSharpResourceImpl |  | 
| `String[]` | Dependants |  | 
| `String[]` | Dependencies |  | 
| `Boolean` | IsStarted |  | 
| `String` | Main |  | 
| `String` | Name |  | 
| `String` | Path |  | 
| `IntPtr` | ResourceImplPtr |  | 
| `String` | Type |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Object` | GetExport(`String` key) |  | 
| `Boolean` | GetExport(`String` key, `MValueConst&` mValue) |  | 
| `void` | SetExport(`String` key, `Object` value) |  | 
| `void` | SetExport(`String` key, `MValueConst&` value) |  | 
| `void` | Start() |  | 
| `void` | Stop() |  | 


## `INativeResourceFactory`

```csharp
public interface AltV.Net.INativeResourceFactory

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `INativeResource` | Create(`IntPtr` corePointer, `IntPtr` resourcePointer) |  | 


## `INativeResourcePool`

```csharp
public interface AltV.Net.INativeResourcePool

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | GetOrCreate(`IntPtr` corePointer, `IntPtr` resourcePointer, `INativeResource&` resource) |  | 


## `InvalidImportException`

```csharp
public class AltV.Net.InvalidImportException
    : Exception, ISerializable

```

## `IResource`

```csharp
public interface AltV.Net.IResource

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `IBaseBaseObjectPool` | GetBaseBaseObjectPool(`IEntityPool<IPlayer>` playerPool, `IEntityPool<IVehicle>` vehiclePool, `IBaseObjectPool<IBlip>` blipPool, `IBaseObjectPool<ICheckpoint>` checkpointPool, `IBaseObjectPool<IVoiceChannel>` voiceChannelPool, `IBaseObjectPool<IColShape>` colShapePool) |  | 
| `IBaseEntityPool` | GetBaseEntityPool(`IEntityPool<IPlayer>` playerPool, `IEntityPool<IVehicle>` vehiclePool) |  | 
| `IBaseObjectFactory<IBlip>` | GetBlipFactory() |  | 
| `IBaseObjectPool<IBlip>` | GetBlipPool(`IBaseObjectFactory<IBlip>` blipFactory) |  | 
| `IBaseObjectFactory<ICheckpoint>` | GetCheckpointFactory() |  | 
| `IBaseObjectPool<ICheckpoint>` | GetCheckpointPool(`IBaseObjectFactory<ICheckpoint>` checkpointFactory) |  | 
| `IBaseObjectFactory<IColShape>` | GetColShapeFactory() |  | 
| `IBaseObjectPool<IColShape>` | GetColShapePool(`IBaseObjectFactory<IColShape>` colShapeFactory) |  | 
| `Module` | GetModule(`IServer` server, `AssemblyLoadContext` assemblyLoadContext, `INativeResource` cSharpNativeResource, `IBaseBaseObjectPool` baseBaseObjectPool, `IBaseEntityPool` baseEntityPool, `IEntityPool<IPlayer>` playerPool, `IEntityPool<IVehicle>` vehiclePool, `IBaseObjectPool<IBlip>` blipPool, `IBaseObjectPool<ICheckpoint>` checkpointPool, `IBaseObjectPool<IVoiceChannel>` voiceChannelPool, `IBaseObjectPool<IColShape>` colShapePool, `INativeResourcePool` resourcePool) |  | 
| `INativeResourceFactory` | GetNativeResourceFactory() |  | 
| `INativeResourcePool` | GetNativeResourcePool(`INativeResourceFactory` nativeResourceFactory) |  | 
| `IEntityFactory<IPlayer>` | GetPlayerFactory() |  | 
| `IEntityPool<IPlayer>` | GetPlayerPool(`IEntityFactory<IPlayer>` playerFactory) |  | 
| `IEntityFactory<IVehicle>` | GetVehicleFactory() |  | 
| `IEntityPool<IVehicle>` | GetVehiclePool(`IEntityFactory<IVehicle>` vehicleFactory) |  | 
| `IBaseObjectFactory<IVoiceChannel>` | GetVoiceChannelFactory() |  | 
| `IBaseObjectPool<IVoiceChannel>` | GetVoiceChannelPool(`IBaseObjectFactory<IVoiceChannel>` voiceChannelFactory) |  | 
| `void` | OnStart(`IntPtr` serverPointer, `IntPtr` resourcePointer, `String` resourceName, `String` entryPoint) |  | 
| `void` | OnStart() |  | 
| `void` | OnStop() |  | 
| `void` | OnTick() |  | 


## `IScript`

```csharp
public interface AltV.Net.IScript

```

## `IServer`

```csharp
public interface AltV.Net.IServer

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | IsDebug |  | 
| `IntPtr` | NativePointer |  | 
| `Int32` | NetTime |  | 
| `INativeResource` | Resource |  | 
| `String` | RootDirectory |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `IBlip` | CreateBlip(`IPlayer` player, `Byte` type, `Position` pos) |  | 
| `IBlip` | CreateBlip(`IPlayer` player, `Byte` type, `IEntity` entityAttach) |  | 
| `ICheckpoint` | CreateCheckpoint(`Byte` type, `Position` pos, `Single` radius, `Single` height, `Rgba` color) |  | 
| `IColShape` | CreateColShapeCircle(`Position` pos, `Single` radius) |  | 
| `IColShape` | CreateColShapeCube(`Position` pos, `Position` pos2) |  | 
| `IColShape` | CreateColShapeCylinder(`Position` pos, `Single` radius, `Single` height) |  | 
| `IColShape` | CreateColShapeRectangle(`Single` x1, `Single` y1, `Single` x2, `Single` y2, `Single` z) |  | 
| `IColShape` | CreateColShapeSphere(`Position` pos, `Single` radius) |  | 
| `void` | CreateMValue(`MValueConst&` mValue, `Object` obj) |  | 
| `void` | CreateMValueBlip(`MValueConst&` mValue, `IBlip` value) |  | 
| `void` | CreateMValueBool(`MValueConst&` mValue, `Boolean` value) |  | 
| `void` | CreateMValueByteArray(`MValueConst&` mValue, `Byte[]` value) |  | 
| `void` | CreateMValueCheckpoint(`MValueConst&` mValue, `ICheckpoint` value) |  | 
| `void` | CreateMValueDict(`MValueConst&` mValue, `String[]` keys, `MValueConst[]` val, `UInt64` size) |  | 
| `void` | CreateMValueDouble(`MValueConst&` mValue, `Double` value) |  | 
| `void` | CreateMValueFunction(`MValueConst&` mValue, `IntPtr` value) |  | 
| `void` | CreateMValueInt(`MValueConst&` mValue, `Int64` value) |  | 
| `void` | CreateMValueList(`MValueConst&` mValue, `MValueConst[]` val, `UInt64` size) |  | 
| `void` | CreateMValueNil(`MValueConst&` mValue) |  | 
| `void` | CreateMValuePlayer(`MValueConst&` mValue, `IPlayer` value) |  | 
| `void` | CreateMValueRgba(`MValueConst&` mValue, `Rgba` value) |  | 
| `void` | CreateMValues(`MValueConst[]` mValues, `Object[]` objects) |  | 
| `void` | CreateMValueString(`MValueConst&` mValue, `String` value) |  | 
| `void` | CreateMValueUInt(`MValueConst&` mValue, `UInt64` value) |  | 
| `void` | CreateMValueVector3(`MValueConst&` mValue, `Position` value) |  | 
| `void` | CreateMValueVehicle(`MValueConst&` mValue, `IVehicle` value) |  | 
| `void` | CreateMValueVoiceChannel(`MValueConst&` mValue, `IVoiceChannel` value) |  | 
| `IVehicle` | CreateVehicle(`UInt32` model, `Position` pos, `Rotation` rotation) |  | 
| `IntPtr` | CreateVehicleEntity(`UInt16&` id, `UInt32` model, `Position` pos, `Rotation` rotation) |  | 
| `IVoiceChannel` | CreateVoiceChannel(`Boolean` spatial, `Single` maxDistance) |  | 
| `void` | DeleteMetaData(`String` key) |  | 
| `void` | DeleteSyncedMetaData(`String` key) |  | 
| `IEntity` | GetEntityById(`UInt16` id) |  | 
| `void` | GetMetaData(`String` key, `MValueConst&` value) |  | 
| `IEnumerable<IPlayer>` | GetPlayers() |  | 
| `INativeResource` | GetResource(`String` name) |  | 
| `INativeResource` | GetResource(`IntPtr` resourcePointer) |  | 
| `void` | GetSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `IEnumerable<IVehicle>` | GetVehicles() |  | 
| `UInt32` | Hash(`String` hash) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `Boolean` | HasSyncedMetaData(`String` key) |  | 
| `void` | LogColored(`String` message) |  | 
| `void` | LogColored(`IntPtr` message) |  | 
| `void` | LogDebug(`String` message) |  | 
| `void` | LogDebug(`IntPtr` message) |  | 
| `void` | LogError(`String` message) |  | 
| `void` | LogError(`IntPtr` message) |  | 
| `void` | LogInfo(`String` message) |  | 
| `void` | LogInfo(`IntPtr` message) |  | 
| `void` | LogWarning(`String` message) |  | 
| `void` | LogWarning(`IntPtr` message) |  | 
| `void` | RemoveBlip(`IBlip` blip) |  | 
| `void` | RemoveCheckpoint(`ICheckpoint` checkpoint) |  | 
| `void` | RemoveColShape(`IColShape` colShape) |  | 
| `void` | RemoveVehicle(`IVehicle` vehicle) |  | 
| `void` | RemoveVoiceChannel(`IVoiceChannel` channel) |  | 
| `void` | RestartResource(`String` name) |  | 
| `void` | SetMetaData(`String` key, `Object` value) |  | 
| `void` | SetSyncedMetaData(`String` key, `Object` value) |  | 
| `void` | StartResource(`String` name) |  | 
| `void` | StopResource(`String` name) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `IntPtr` eventNamePtr, `MValueConst[]` args) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `String` eventName, `MValueConst[]` args) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `IntPtr` eventNamePtr, `IntPtr[]` args) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `String` eventName, `IntPtr[]` args) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `IntPtr` eventNamePtr, `Object[]` args) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `String` eventName, `Object[]` args) |  | 
| `void` | TriggerServerEvent(`String` eventName, `MValueConst[]` args) |  | 
| `void` | TriggerServerEvent(`IntPtr` eventNamePtr, `MValueConst[]` args) |  | 
| `void` | TriggerServerEvent(`String` eventName, `IntPtr[]` args) |  | 
| `void` | TriggerServerEvent(`IntPtr` eventNamePtr, `IntPtr[]` args) |  | 
| `void` | TriggerServerEvent(`IntPtr` eventNamePtr, `Object[]` args) |  | 
| `void` | TriggerServerEvent(`String` eventName, `Object[]` args) |  | 


## `IWritable`

```csharp
public interface AltV.Net.IWritable

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | OnWrite(`IMValueWriter` writer) |  | 


## `Module`

```csharp
public class AltV.Net.Module
    : IDisposable

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `IBaseBaseObjectPool` | BaseBaseObjectPool |  | 
| `IBaseEntityPool` | BaseEntityPool |  | 
| `IBaseObjectPool<IBlip>` | BlipPool |  | 
| `IEventHandler<CheckpointDelegate>` | CheckpointEventHandler |  | 
| `IBaseObjectPool<ICheckpoint>` | CheckpointPool |  | 
| `IEventHandler<ColShapeDelegate>` | ColShapeEventHandler |  | 
| `IBaseObjectPool<IColShape>` | ColShapePool |  | 
| `IEventHandler<ConsoleCommandDelegate>` | ConsoleCommandEventHandler |  | 
| `IEventHandler<ExplosionDelegate>` | ExplosionEventHandler |  | 
| `LinkedList<GCHandle>` | functionExportHandles |  | 
| `IDictionary<String, Function>` | functionExports |  | 
| `IEventHandler<MetaDataChangeDelegate>` | MetaDataChangeEventHandler |  | 
| `INativeResource` | ModuleResource |  | 
| `INativeResourcePool` | NativeResourcePool |  | 
| `IEventHandler<PlayerChangeVehicleSeatDelegate>` | PlayerChangeVehicleSeatEventHandler |  | 
| `IEventHandler<PlayerClientCustomEventDelegate>` | PlayerClientCustomEventEventHandler |  | 
| `IEventHandler<PlayerClientEventDelegate>` | PlayerClientEventEventHandler |  | 
| `IEventHandler<PlayerConnectDelegate>` | PlayerConnectEventHandler |  | 
| `IEventHandler<PlayerDamageDelegate>` | PlayerDamageEventHandler |  | 
| `IEventHandler<PlayerDeadDelegate>` | PlayerDeadEventHandler |  | 
| `IEventHandler<PlayerDisconnectDelegate>` | PlayerDisconnectEventHandler |  | 
| `IEventHandler<PlayerEnterVehicleDelegate>` | PlayerEnterVehicleEventHandler |  | 
| `IEventHandler<PlayerLeaveVehicleDelegate>` | PlayerLeaveVehicleEventHandler |  | 
| `IEntityPool<IPlayer>` | PlayerPool |  | 
| `IEventHandler<PlayerRemoveDelegate>` | PlayerRemoveEventHandler |  | 
| `IEventHandler<ResourceEventDelegate>` | ResourceErrorEventHandler |  | 
| `IEventHandler<ResourceEventDelegate>` | ResourceStartEventHandler |  | 
| `IEventHandler<ResourceEventDelegate>` | ResourceStopEventHandler |  | 
| `IServer` | Server |  | 
| `IEventHandler<ServerCustomEventEventDelegate>` | ServerCustomEventEventHandler |  | 
| `IEventHandler<ServerEventEventDelegate>` | ServerEventEventHandler |  | 
| `IEventHandler<MetaDataChangeDelegate>` | SyncedMetaDataChangeEventHandler |  | 
| `IEventHandler<VehicleDestroyDelegate>` | VehicleDestroyEventHandler |  | 
| `IEntityPool<IVehicle>` | VehiclePool |  | 
| `IEventHandler<VehicleRemoveDelegate>` | VehicleRemoveEventHandler |  | 
| `IBaseObjectPool<IVoiceChannel>` | VoiceChannelPool |  | 
| `IEventHandler<WeaponDamageDelegate>` | WeaponDamageEventHandler |  | 


Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `IEnumerable<Assembly>` | Assemblies |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | CountDownRefForCurrentThread(`IBaseObject` baseObject) |  | 
| `void` | CountUpRefForCurrentThread(`IBaseObject` baseObject) |  | 
| `void` | Dispose() |  | 
| `Boolean` | HasRefForCurrentThread(`IBaseObject` baseObject) |  | 
| `Boolean` | IsMainThread() |  | 
| `Assembly` | LoadAssemblyFromName(`AssemblyName` assemblyName) |  | 
| `Assembly` | LoadAssemblyFromNativeImagePath(`String` nativeImagePath, `String` assemblyPath) |  | 
| `Assembly` | LoadAssemblyFromPath(`String` path) |  | 
| `Assembly` | LoadAssemblyFromStream(`Stream` stream) |  | 
| `Assembly` | LoadAssemblyFromStream(`Stream` stream, `Stream` assemblySymbols) |  | 
| `void` | Off(`String` eventName, `TFunc` func, `ClientEventParser<TFunc>` parser) |  | 
| `void` | Off(`String` eventName, `TFunc` func, `ServerEventParser<TFunc>` parser) |  | 
| `void` | OffClient(`String` eventName, `Function` function) |  | 
| `void` | OffServer(`String` eventName, `Function` function) |  | 
| `void` | On(`String` eventName, `TFunc` func, `ClientEventParser<TFunc>` parser) |  | 
| `void` | On(`String` eventName, `TFunc` func, `ServerEventParser<TFunc>` parser) |  | 
| `void` | OnCheckpoint(`IntPtr` checkpointPointer, `IntPtr` entityPointer, `BaseObjectType` baseObjectType, `Boolean` state) |  | 
| `void` | OnCheckPointEvent(`ICheckpoint` checkpoint, `IEntity` entity, `Boolean` state) |  | 
| `void` | OnClient(`String` eventName, `Function` function) |  | 
| `void` | OnClientEvent(`IntPtr` playerPointer, `String` name, `IntPtr[]` args) |  | 
| `void` | OnClientEventEvent(`IPlayer` player, `String` name, `IntPtr[]` args, `MValueConst[]` mValues, `Object[]` objects) |  | 
| `void` | OnColShape(`IntPtr` colShapePointer, `IntPtr` targetEntityPointer, `BaseObjectType` entityType, `Boolean` state) |  | 
| `void` | OnColShapeEvent(`IColShape` colShape, `IEntity` entity, `Boolean` state) |  | 
| `void` | OnConsoleCommand(`String` name, `String[]` args) |  | 
| `void` | OnConsoleCommandEvent(`String` name, `String[]` args) |  | 
| `void` | OnCreateBlip(`IntPtr` blipPointer) |  | 
| `void` | OnCreateCheckpoint(`IntPtr` checkpointPointer) |  | 
| `void` | OnCreateColShape(`IntPtr` colShapePointer) |  | 
| `void` | OnCreatePlayer(`IntPtr` playerPointer, `UInt16` playerId) |  | 
| `void` | OnCreateVehicle(`IntPtr` vehiclePointer, `UInt16` vehicleId) |  | 
| `void` | OnCreateVoiceChannel(`IntPtr` channelPointer) |  | 
| `void` | OnExplosion(`IntPtr` eventPointer, `IntPtr` playerPointer, `ExplosionType` explosionType, `Position` position, `UInt32` explosionFx) |  | 
| `void` | OnExplosionEvent(`IntPtr` eventPointer, `IPlayer` sourcePlayer, `ExplosionType` explosionType, `Position` position, `UInt32` explosionFx) |  | 
| `void` | OnMetaDataChange(`IntPtr` entityPointer, `BaseObjectType` entityType, `String` key, `IntPtr` value) |  | 
| `void` | OnMetaDataChangeEvent(`IEntity` entity, `String` key, `Object` value) |  | 
| `void` | OnModuleLoaded(`IModule` module) |  | 
| `void` | OnModulesLoaded(`IModule[]` modules) |  | 
| `void` | OnPlayerChangeVehicleSeat(`IntPtr` vehiclePointer, `IntPtr` playerPointer, `Byte` oldSeat, `Byte` newSeat) |  | 
| `void` | OnPlayerChangeVehicleSeatEvent(`IVehicle` vehicle, `IPlayer` player, `Byte` oldSeat, `Byte` newSeat) |  | 
| `void` | OnPlayerConnect(`IntPtr` playerPointer, `UInt16` playerId, `String` reason) |  | 
| `void` | OnPlayerConnectEvent(`IPlayer` player, `String` reason) |  | 
| `void` | OnPlayerDamage(`IntPtr` playerPointer, `IntPtr` attackerEntityPointer, `BaseObjectType` attackerBaseObjectType, `UInt16` attackerEntityId, `UInt32` weapon, `UInt16` damage) |  | 
| `void` | OnPlayerDamageEvent(`IPlayer` player, `IEntity` attacker, `UInt32` weapon, `UInt16` damage) |  | 
| `void` | OnPlayerDeath(`IntPtr` playerPointer, `IntPtr` killerEntityPointer, `BaseObjectType` killerBaseObjectType, `UInt32` weapon) |  | 
| `void` | OnPlayerDeathEvent(`IPlayer` player, `IEntity` killer, `UInt32` weapon) |  | 
| `void` | OnPlayerDisconnect(`IntPtr` playerPointer, `String` reason) |  | 
| `void` | OnPlayerDisconnectEvent(`IPlayer` player, `String` reason) |  | 
| `void` | OnPlayerEnterVehicle(`IntPtr` vehiclePointer, `IntPtr` playerPointer, `Byte` seat) |  | 
| `void` | OnPlayerEnterVehicleEvent(`IVehicle` vehicle, `IPlayer` player, `Byte` seat) |  | 
| `void` | OnPlayerLeaveVehicle(`IntPtr` vehiclePointer, `IntPtr` playerPointer, `Byte` seat) |  | 
| `void` | OnPlayerLeaveVehicleEvent(`IVehicle` vehicle, `IPlayer` player, `Byte` seat) |  | 
| `void` | OnPlayerRemove(`IntPtr` playerPointer) |  | 
| `void` | OnPlayerRemoveEvent(`IPlayer` player) |  | 
| `void` | OnRemoveBlip(`IntPtr` blipPointer) |  | 
| `void` | OnRemoveCheckpoint(`IntPtr` checkpointPointer) |  | 
| `void` | OnRemoveColShape(`IntPtr` colShapePointer) |  | 
| `void` | OnRemovePlayer(`IntPtr` playerPointer) |  | 
| `void` | OnRemoveVehicle(`IntPtr` vehiclePointer) |  | 
| `void` | OnRemoveVoiceChannel(`IntPtr` channelPointer) |  | 
| `void` | OnResourceError(`IntPtr` resourcePointer) |  | 
| `void` | OnResourceErrorEvent(`INativeResource` resource) |  | 
| `void` | OnResourceStart(`IntPtr` resourcePointer) |  | 
| `void` | OnResourceStartEvent(`INativeResource` resource) |  | 
| `void` | OnResourceStop(`IntPtr` resourcePointer) |  | 
| `void` | OnResourceStopEvent(`INativeResource` resource) |  | 
| `void` | OnScriptLoaded(`IScript` script) |  | 
| `void` | OnScriptsLoaded(`IScript[]` scripts) |  | 
| `void` | OnServer(`String` eventName, `Function` function) |  | 
| `void` | OnServerEvent(`String` name, `IntPtr[]` args) |  | 
| `void` | OnServerEventEvent(`String` name, `IntPtr[]` args, `MValueConst[]` mValues, `Object[]` objects) |  | 
| `void` | OnSyncedMetaDataChange(`IntPtr` entityPointer, `BaseObjectType` entityType, `String` key, `IntPtr` value) |  | 
| `void` | OnSyncedMetaDataChangeEvent(`IEntity` entity, `String` key, `Object` value) |  | 
| `void` | OnVehicleDestroy(`IntPtr` vehiclePointer) |  | 
| `void` | OnVehicleDestroyEvent(`IVehicle` vehicle) |  | 
| `void` | OnVehicleRemove(`IntPtr` vehiclePointer) |  | 
| `void` | OnVehicleRemoveEvent(`IVehicle` vehicle) |  | 
| `void` | OnWeaponDamage(`IntPtr` eventPointer, `IntPtr` playerPointer, `IntPtr` entityPointer, `BaseObjectType` entityType, `UInt32` weapon, `UInt16` damage, `Position` shotOffset, `BodyPart` bodyPart) |  | 
| `void` | OnWeaponDamageEvent(`IntPtr` eventPointer, `IPlayer` sourcePlayer, `IEntity` targetEntity, `UInt32` weapon, `UInt16` damage, `Position` shotOffset, `BodyPart` bodyPart) |  | 
| `void` | SetExport(`String` key, `Function` function) |  | 


## `NativeResource`

```csharp
public class AltV.Net.NativeResource
    : INativeResource

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `IntPtr` | NativePointer |  | 


Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `CSharpResourceImpl` | CSharpResourceImpl |  | 
| `String[]` | Dependants |  | 
| `String[]` | Dependencies |  | 
| `Boolean` | IsStarted |  | 
| `String` | Main |  | 
| `String` | Name |  | 
| `String` | Path |  | 
| `IntPtr` | ResourceImplPtr |  | 
| `String` | Type |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Object` | GetExport(`String` key) |  | 
| `Boolean` | GetExport(`String` key, `MValueConst&` mValue) |  | 
| `void` | SetExport(`String` key, `Object` value) |  | 
| `void` | SetExport(`String` key, `MValueConst&` value) |  | 
| `void` | Start() |  | 
| `void` | Stop() |  | 


## `Resource`

```csharp
public abstract class AltV.Net.Resource
    : IResource

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `IBaseBaseObjectPool` | GetBaseBaseObjectPool(`IEntityPool<IPlayer>` playerPool, `IEntityPool<IVehicle>` vehiclePool, `IBaseObjectPool<IBlip>` blipPool, `IBaseObjectPool<ICheckpoint>` checkpointPool, `IBaseObjectPool<IVoiceChannel>` voiceChannelPool, `IBaseObjectPool<IColShape>` colShapePool) |  | 
| `IBaseEntityPool` | GetBaseEntityPool(`IEntityPool<IPlayer>` playerPool, `IEntityPool<IVehicle>` vehiclePool) |  | 
| `IBaseObjectFactory<IBlip>` | GetBlipFactory() |  | 
| `IBaseObjectPool<IBlip>` | GetBlipPool(`IBaseObjectFactory<IBlip>` blipFactory) |  | 
| `IBaseObjectFactory<ICheckpoint>` | GetCheckpointFactory() |  | 
| `IBaseObjectPool<ICheckpoint>` | GetCheckpointPool(`IBaseObjectFactory<ICheckpoint>` checkpointFactory) |  | 
| `IBaseObjectFactory<IColShape>` | GetColShapeFactory() |  | 
| `IBaseObjectPool<IColShape>` | GetColShapePool(`IBaseObjectFactory<IColShape>` colShapeFactory) |  | 
| `Module` | GetModule(`IServer` server, `AssemblyLoadContext` assemblyLoadContext, `INativeResource` cSharpNativeResource, `IBaseBaseObjectPool` baseBaseObjectPool, `IBaseEntityPool` baseEntityPool, `IEntityPool<IPlayer>` playerPool, `IEntityPool<IVehicle>` vehiclePool, `IBaseObjectPool<IBlip>` blipPool, `IBaseObjectPool<ICheckpoint>` checkpointPool, `IBaseObjectPool<IVoiceChannel>` voiceChannelPool, `IBaseObjectPool<IColShape>` colShapePool, `INativeResourcePool` nativeResourcePool) |  | 
| `INativeResourceFactory` | GetNativeResourceFactory() |  | 
| `INativeResourcePool` | GetNativeResourcePool(`INativeResourceFactory` nativeResourceFactory) |  | 
| `IEntityFactory<IPlayer>` | GetPlayerFactory() |  | 
| `IEntityPool<IPlayer>` | GetPlayerPool(`IEntityFactory<IPlayer>` playerFactory) |  | 
| `IEntityFactory<IVehicle>` | GetVehicleFactory() |  | 
| `IEntityPool<IVehicle>` | GetVehiclePool(`IEntityFactory<IVehicle>` vehicleFactory) |  | 
| `IBaseObjectFactory<IVoiceChannel>` | GetVoiceChannelFactory() |  | 
| `IBaseObjectPool<IVoiceChannel>` | GetVoiceChannelPool(`IBaseObjectFactory<IVoiceChannel>` voiceChannelFactory) |  | 
| `void` | OnStart() |  | 
| `void` | OnStart(`IntPtr` serverPointer, `IntPtr` resourcePointer, `String` resourceName, `String` entryPoint) |  | 
| `void` | OnStop() |  | 
| `void` | OnTick() |  | 


## `ResourceSharedAssembliesAttribute`

```csharp
public class AltV.Net.ResourceSharedAssembliesAttribute
    : Attribute

```

## `ScriptEventAttribute`

```csharp
public class AltV.Net.ScriptEventAttribute
    : Attribute

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `ScriptEventType` | EventType |  | 


## `ScriptEventType`

```csharp
public enum AltV.Net.ScriptEventType
    : Enum, IComparable, IFormattable, IConvertible

```

Enum

| Value | Name | Summary | 
| --- | --- | --- | 
| `0` | Checkpoint |  | 
| `1` | PlayerConnect |  | 
| `2` | PlayerDamage |  | 
| `3` | PlayerDead |  | 
| `4` | PlayerDisconnect |  | 
| `5` | PlayerRemove |  | 
| `6` | VehicleRemove |  | 
| `7` | PlayerChangeVehicleSeat |  | 
| `8` | PlayerEnterVehicle |  | 
| `9` | PlayerLeaveVehicle |  | 
| `10` | PlayerEvent |  | 
| `11` | PlayerCustomEvent |  | 
| `12` | ServerEvent |  | 
| `13` | ServerCustomEvent |  | 
| `14` | ConsoleCommand |  | 
| `15` | MetaDataChange |  | 
| `16` | SyncedMetaDataChange |  | 
| `17` | ColShape |  | 
| `18` | WeaponDamage |  | 
| `19` | VehicleDestroy |  | 
| `20` | Explosion |  | 


## `Server`

```csharp
public class AltV.Net.Server
    : IServer

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | IsDebug |  | 
| `IntPtr` | NativePointer |  | 
| `Int32` | NetTime |  | 
| `INativeResource` | Resource |  | 
| `String` | RootDirectory |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | CheckIfCallIsValid(`String` callerName = ) |  | 
| `IBlip` | CreateBlip(`IPlayer` player, `Byte` type, `Position` pos) |  | 
| `IBlip` | CreateBlip(`IPlayer` player, `Byte` type, `IEntity` entityAttach) |  | 
| `ICheckpoint` | CreateCheckpoint(`Byte` type, `Position` pos, `Single` radius, `Single` height, `Rgba` color) |  | 
| `IColShape` | CreateColShapeCircle(`Position` pos, `Single` radius) |  | 
| `IColShape` | CreateColShapeCube(`Position` pos, `Position` pos2) |  | 
| `IColShape` | CreateColShapeCylinder(`Position` pos, `Single` radius, `Single` height) |  | 
| `IColShape` | CreateColShapeRectangle(`Single` x1, `Single` y1, `Single` x2, `Single` y2, `Single` z) |  | 
| `IColShape` | CreateColShapeSphere(`Position` pos, `Single` radius) |  | 
| `void` | CreateMValue(`MValueConst&` mValue, `Object` obj) |  | 
| `void` | CreateMValueBlip(`MValueConst&` mValue, `IBlip` value) |  | 
| `void` | CreateMValueBool(`MValueConst&` mValue, `Boolean` value) |  | 
| `void` | CreateMValueByteArray(`MValueConst&` mValue, `Byte[]` value) |  | 
| `void` | CreateMValueCheckpoint(`MValueConst&` mValue, `ICheckpoint` value) |  | 
| `void` | CreateMValueDict(`MValueConst&` mValue, `String[]` keys, `MValueConst[]` val, `UInt64` size) |  | 
| `void` | CreateMValueDouble(`MValueConst&` mValue, `Double` value) |  | 
| `void` | CreateMValueFunction(`MValueConst&` mValue, `IntPtr` value) |  | 
| `void` | CreateMValueInt(`MValueConst&` mValue, `Int64` value) |  | 
| `void` | CreateMValueList(`MValueConst&` mValue, `MValueConst[]` val, `UInt64` size) |  | 
| `void` | CreateMValueNil(`MValueConst&` mValue) |  | 
| `void` | CreateMValuePlayer(`MValueConst&` mValue, `IPlayer` value) |  | 
| `void` | CreateMValueRgba(`MValueConst&` mValue, `Rgba` value) |  | 
| `void` | CreateMValues(`MValueConst[]` mValues, `Object[]` objects) |  | 
| `void` | CreateMValueString(`MValueConst&` mValue, `String` value) |  | 
| `void` | CreateMValueUInt(`MValueConst&` mValue, `UInt64` value) |  | 
| `void` | CreateMValueVector3(`MValueConst&` mValue, `Position` value) |  | 
| `void` | CreateMValueVehicle(`MValueConst&` mValue, `IVehicle` value) |  | 
| `void` | CreateMValueVoiceChannel(`MValueConst&` mValue, `IVoiceChannel` value) |  | 
| `IVehicle` | CreateVehicle(`UInt32` model, `Position` pos, `Rotation` rotation) |  | 
| `IntPtr` | CreateVehicleEntity(`UInt16&` id, `UInt32` model, `Position` pos, `Rotation` rotation) |  | 
| `IVoiceChannel` | CreateVoiceChannel(`Boolean` spatial, `Single` maxDistance) |  | 
| `void` | DeleteMetaData(`String` key) |  | 
| `void` | DeleteSyncedMetaData(`String` key) |  | 
| `IEntity` | GetEntityById(`UInt16` id) |  | 
| `void` | GetMetaData(`String` key, `MValueConst&` value) |  | 
| `IEnumerable<IPlayer>` | GetPlayers() |  | 
| `INativeResource` | GetResource(`String` name) |  | 
| `INativeResource` | GetResource(`IntPtr` resourcePointer) |  | 
| `void` | GetSyncedMetaData(`String` key, `MValueConst&` value) |  | 
| `IEnumerable<IVehicle>` | GetVehicles() |  | 
| `UInt32` | Hash(`String` stringToHash) |  | 
| `Boolean` | HasMetaData(`String` key) |  | 
| `Boolean` | HasSyncedMetaData(`String` key) |  | 
| `void` | LogColored(`IntPtr` messagePtr) |  | 
| `void` | LogColored(`String` message) |  | 
| `void` | LogDebug(`IntPtr` messagePtr) |  | 
| `void` | LogDebug(`String` message) |  | 
| `void` | LogError(`IntPtr` messagePtr) |  | 
| `void` | LogError(`String` message) |  | 
| `void` | LogInfo(`IntPtr` messagePtr) |  | 
| `void` | LogInfo(`String` message) |  | 
| `void` | LogWarning(`IntPtr` messagePtr) |  | 
| `void` | LogWarning(`String` message) |  | 
| `void` | RemoveBlip(`IBlip` blip) |  | 
| `void` | RemoveCheckpoint(`ICheckpoint` checkpoint) |  | 
| `void` | RemoveColShape(`IColShape` colShape) |  | 
| `void` | RemoveVehicle(`IVehicle` vehicle) |  | 
| `void` | RemoveVoiceChannel(`IVoiceChannel` channel) |  | 
| `void` | RestartResource(`String` name) |  | 
| `void` | SetMetaData(`String` key, `Object` value) |  | 
| `void` | SetSyncedMetaData(`String` key, `Object` value) |  | 
| `void` | StartResource(`String` name) |  | 
| `void` | StopResource(`String` name) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `IntPtr` eventNamePtr, `MValueConst[]` args) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `String` eventName, `MValueConst[]` args) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `IntPtr` eventNamePtr, `IntPtr[]` args) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `String` eventName, `IntPtr[]` args) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `IntPtr` eventNamePtr, `Object[]` args) |  | 
| `void` | TriggerClientEvent(`IPlayer` player, `String` eventName, `Object[]` args) |  | 
| `void` | TriggerServerEvent(`String` eventName, `MValueConst[]` args) |  | 
| `void` | TriggerServerEvent(`IntPtr` eventNamePtr, `MValueConst[]` args) |  | 
| `void` | TriggerServerEvent(`String` eventName, `IntPtr[]` args) |  | 
| `void` | TriggerServerEvent(`IntPtr` eventNamePtr, `IntPtr[]` args) |  | 
| `void` | TriggerServerEvent(`IntPtr` eventNamePtr, `Object[]` args) |  | 
| `void` | TriggerServerEvent(`String` eventName, `Object[]` args) |  | 


## `ServerEventAttribute`

```csharp
public class AltV.Net.ServerEventAttribute
    : Attribute

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `String` | Name |  | 


## `TraceFileFormat`

```csharp
public enum AltV.Net.TraceFileFormat
    : Enum, IComparable, IFormattable, IConvertible

```

Enum

| Value | Name | Summary | 
| --- | --- | --- | 
| `0` | NetTrace |  | 
| `1` | Speedscope |  | 


