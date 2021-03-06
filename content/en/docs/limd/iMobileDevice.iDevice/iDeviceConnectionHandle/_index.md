---
title: iDeviceConnectionHandle class
---

Represents a wrapper class for iDevice handles.

```csharp
public class iDeviceConnectionHandle : SafeHandleZeroOrMinusOneIsInvalid
```

## Public Members

| name | description |
| --- | --- |
| static [Zero](iDeviceConnectionHandle/Zero.md) { get; } | Gets a value which represents a pointer or handle that has been initialized to zero. |
| static [DangerousCreate](iDeviceConnectionHandle/DangerousCreate.md)(…) | Creates a new [`iDeviceConnectionHandle`](iDeviceConnectionHandle.md) from a IntPtr. (2 methods) |
| [Api](iDeviceConnectionHandle/Api.md) { get; set; } | Gets or sets the API to use |
| override [Equals](iDeviceConnectionHandle/Equals.md)(…) |  |
| override [GetHashCode](iDeviceConnectionHandle/GetHashCode.md)() |  |
| override [ToString](iDeviceConnectionHandle/ToString.md)() |  |
| [operator ==](iDeviceConnectionHandle/op_Equality.md) | Determines whether two specified instances of [`iDeviceConnectionHandle`](iDeviceConnectionHandle.md) are equal. |
| [operator !=](iDeviceConnectionHandle/op_Inequality.md) | Determines whether two specified instances of [`iDeviceConnectionHandle`](iDeviceConnectionHandle.md) are not equal. |

## Protected Members

| name | description |
| --- | --- |
| [iDeviceConnectionHandle](iDeviceConnectionHandle/iDeviceConnectionHandle.md)() | Initializes a new instance of the [`iDeviceConnectionHandle`](iDeviceConnectionHandle.md) class. |
| [iDeviceConnectionHandle](iDeviceConnectionHandle/iDeviceConnectionHandle.md)(…) | Initializes a new instance of the [`iDeviceConnectionHandle`](iDeviceConnectionHandle.md) class, specifying whether the handle is to be reliably released. |
| override [ReleaseHandle](iDeviceConnectionHandle/ReleaseHandle.md)() |  |

## See Also

* namespace [iMobileDevice.iDevice](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
