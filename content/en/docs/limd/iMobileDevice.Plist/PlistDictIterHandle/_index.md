---
title: PlistDictIterHandle class
---

Represents a wrapper class for Plist handles.

```csharp
public class PlistDictIterHandle : SafeHandleZeroOrMinusOneIsInvalid
```

## Public Members

| name | description |
| --- | --- |
| static [Zero](PlistDictIterHandle/Zero.md) { get; } | Gets a value which represents a pointer or handle that has been initialized to zero. |
| static [DangerousCreate](PlistDictIterHandle/DangerousCreate.md)(…) | Creates a new [`PlistDictIterHandle`](PlistDictIterHandle.md) from a IntPtr. (2 methods) |
| [Api](PlistDictIterHandle/Api.md) { get; set; } | Gets or sets the API to use |
| override [Equals](PlistDictIterHandle/Equals.md)(…) |  |
| override [GetHashCode](PlistDictIterHandle/GetHashCode.md)() |  |
| override [ToString](PlistDictIterHandle/ToString.md)() |  |
| [operator ==](PlistDictIterHandle/op_Equality.md) | Determines whether two specified instances of [`PlistDictIterHandle`](PlistDictIterHandle.md) are equal. |
| [operator !=](PlistDictIterHandle/op_Inequality.md) | Determines whether two specified instances of [`PlistDictIterHandle`](PlistDictIterHandle.md) are not equal. |

## Protected Members

| name | description |
| --- | --- |
| [PlistDictIterHandle](PlistDictIterHandle/PlistDictIterHandle.md)() | Initializes a new instance of the [`PlistDictIterHandle`](PlistDictIterHandle.md) class. |
| [PlistDictIterHandle](PlistDictIterHandle/PlistDictIterHandle.md)(…) | Initializes a new instance of the [`PlistDictIterHandle`](PlistDictIterHandle.md) class, specifying whether the handle is to be reliably released. |
| override [ReleaseHandle](PlistDictIterHandle/ReleaseHandle.md)() |  |

## See Also

* namespace [iMobileDevice.Plist](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
