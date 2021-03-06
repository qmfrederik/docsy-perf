---
title: PlistArrayIterHandle class
---

Represents a wrapper class for Plist handles.

```csharp
public class PlistArrayIterHandle : SafeHandleZeroOrMinusOneIsInvalid
```

## Public Members

| name | description |
| --- | --- |
| static [Zero](PlistArrayIterHandle/Zero.md) { get; } | Gets a value which represents a pointer or handle that has been initialized to zero. |
| static [DangerousCreate](PlistArrayIterHandle/DangerousCreate.md)(…) | Creates a new [`PlistArrayIterHandle`](PlistArrayIterHandle.md) from a IntPtr. (2 methods) |
| [Api](PlistArrayIterHandle/Api.md) { get; set; } | Gets or sets the API to use |
| override [Equals](PlistArrayIterHandle/Equals.md)(…) |  |
| override [GetHashCode](PlistArrayIterHandle/GetHashCode.md)() |  |
| override [ToString](PlistArrayIterHandle/ToString.md)() |  |
| [operator ==](PlistArrayIterHandle/op_Equality.md) | Determines whether two specified instances of [`PlistArrayIterHandle`](PlistArrayIterHandle.md) are equal. |
| [operator !=](PlistArrayIterHandle/op_Inequality.md) | Determines whether two specified instances of [`PlistArrayIterHandle`](PlistArrayIterHandle.md) are not equal. |

## Protected Members

| name | description |
| --- | --- |
| [PlistArrayIterHandle](PlistArrayIterHandle/PlistArrayIterHandle.md)() | Initializes a new instance of the [`PlistArrayIterHandle`](PlistArrayIterHandle.md) class. |
| [PlistArrayIterHandle](PlistArrayIterHandle/PlistArrayIterHandle.md)(…) | Initializes a new instance of the [`PlistArrayIterHandle`](PlistArrayIterHandle.md) class, specifying whether the handle is to be reliably released. |
| override [ReleaseHandle](PlistArrayIterHandle/ReleaseHandle.md)() |  |

## See Also

* namespace [iMobileDevice.Plist](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
