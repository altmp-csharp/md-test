## `PlayerPointerArray`

```csharp
public struct AltV.Net.Native.PlayerPointerArray
    : IDisposable

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt64` | capacity |  | 
| `IntPtr` | data |  | 
| `UInt64` | size |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | Dispose() |  | 
| `IntPtr[]` | ToArrayAndFree() |  | 


Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `PlayerPointerArray` | Nil |  | 


## `StringArray`

```csharp
public struct AltV.Net.Native.StringArray
    : IDisposable

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt64` | capacity |  | 
| `IntPtr` | data |  | 
| `UInt64` | size |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | Dispose() |  | 
| `String` | GetNextWithOffset(`IntPtr&` offset) |  | 
| `void` | SkipValueWithOffset(`IntPtr&` offset) |  | 
| `String[]` | ToArray() |  | 


Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `StringArray` | Nil |  | 


## `StringView`

```csharp
public struct AltV.Net.Native.StringView

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `String` | Text |  | 


Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `StringView` | Empty |  | 
| `Int32` | Size |  | 


## `StringViewArray`

```csharp
public struct AltV.Net.Native.StringViewArray
    : IDisposable

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt64` | capacity |  | 
| `IntPtr` | data |  | 
| `UInt64` | size |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | Dispose() |  | 
| `String` | GetNextWithOffset(`IntPtr&` offset) |  | 
| `String[]` | ToArray() |  | 


Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `StringViewArray` | Nil |  | 


## `UIntArray`

```csharp
public struct AltV.Net.Native.UIntArray
    : IDisposable

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt64` | capacity |  | 
| `IntPtr` | data |  | 
| `UInt64` | size |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | Dispose() |  | 
| `UInt32[]` | ToArrayAndFree() |  | 


Static Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `UIntArray` | Nil |  | 


Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `UInt32` | ReadUInt32(`Byte[]` buffer, `IntPtr` ptr, `Int32` ofs) |  | 


