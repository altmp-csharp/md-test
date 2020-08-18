## `DefaultMValueAdapters`

```csharp
public static class AltV.Net.Elements.Args.DefaultMValueAdapters

```

Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `IMValueAdapter<List<T>>` | GetArrayAdapter(`IMValueAdapter<T>` elementAdapter) |  | 
| `IMValueAdapter<IDictionary<String, T>>` | GetDictionaryAdapter(`IMValueAdapter<T>` elementAdapter) |  | 


## `MValueAdapters`

```csharp
public static class AltV.Net.Elements.Args.MValueAdapters

```

Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | FromMValue(`MValueConst&` mValue, `Type` type, `Object&` obj) |  | 
| `Boolean` | FromObject(`Object` obj, `Type` type, `Object&` result) |  | 
| `Boolean` | IsConvertible(`Type` type) |  | 
| `void` | Register(`IMValueAdapter<T>` adapter) |  | 
| `Boolean` | ToMValue(`Object` obj, `Type` type, `MValueConst&` mValue) |  | 


## `MValueBuffer2`

```csharp
public struct AltV.Net.Elements.Args.MValueBuffer2

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Int32` | size |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | GetNext(`MValueConst&` mValue) |  | 
| `Boolean` | GetNext(`Boolean&` value) |  | 
| `Boolean` | GetNext(`Int32&` value) |  | 
| `Boolean` | GetNext(`UInt32&` value) |  | 
| `Boolean` | GetNext(`Int64&` value) |  | 
| `Boolean` | GetNext(`UInt64&` value) |  | 
| `Boolean` | GetNext(`Single&` value) |  | 
| `Boolean` | GetNext(`Double&` value) |  | 
| `Boolean` | GetNext(`String&` value) |  | 
| `Boolean` | GetNext(`Position&` value) |  | 
| `Boolean` | GetNext(`Rgba&` value) |  | 
| `Boolean` | GetNext(`Byte[]&` value) |  | 
| `Boolean` | GetNext(`MValueConst[]&` valuesList) |  | 
| `Boolean` | GetNext(`TEntity&` value) |  | 
| `Type` | GetPreviousType() |  | 
| `Boolean` | HasNext() |  | 
| `void` | Peek(`MValueConst&` mValue) |  | 
| `void` | SkipValue() |  | 


## `MValueConst`

```csharp
public struct AltV.Net.Elements.Args.MValueConst
    : IDisposable

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `IntPtr` | nativePointer |  | 
| `Type` | type |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | AddRef() |  | 
| `void` | CallFunction(`MValueConst[]` args, `MValueConst&` result) |  | 
| `void` | Dispose() |  | 
| `IBaseObject` | GetBaseObject() |  | 
| `Boolean` | GetBool() |  | 
| `Byte[]` | GetByteArray() |  | 
| `Dictionary<String, MValueConst>` | GetDictionary() |  | 
| `Double` | GetDouble() |  | 
| `IntPtr` | GetEntityPointer(`BaseObjectType&` baseObjectType) |  | 
| `Int64` | GetInt() |  | 
| `MValueConst[]` | GetList() |  | 
| `void` | GetRgba(`Rgba&` rgba) |  | 
| `Rgba` | GetRgba() |  | 
| `String` | GetString() |  | 
| `UInt64` | GetUint() |  | 
| `void` | GetVector3(`Position&` position) |  | 
| `Position` | GetVector3() |  | 
| `void` | RemoveRef() |  | 
| `Object` | ToObject() |  | 
| `String` | ToString() |  | 


Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `MValueConst` | Nil |  | 
| `MValueConst` | None |  | 


Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `MValueConst[]` | CreateFrom(`IntPtr[]` pointers) |  | 


## `MValueReaderToken`

```csharp
public enum AltV.Net.Elements.Args.MValueReaderToken
    : Enum, IComparable, IFormattable, IConvertible

```

Enum

| Value | Name | Summary | 
| --- | --- | --- | 
| `0` | Object |  | 
| `1` | Array |  | 
| `2` | Name |  | 
| `3` | Value |  | 
| `4` | Nil |  | 
| `5` | Unknown |  | 


## `MValueWriter2`

```csharp
public class AltV.Net.Elements.Args.MValueWriter2
    : IMValueWriter

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | BeginArray() |  | 
| `void` | BeginObject() |  | 
| `void` | EndArray() |  | 
| `void` | EndObject() |  | 
| `void` | Name(`String` name) |  | 
| `Boolean` | ToMValue(`MValueConst&` mValue) |  | 
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
| `void` | Value(`Position` value) |  | 
| `void` | Value(`Rgba` value) |  | 


