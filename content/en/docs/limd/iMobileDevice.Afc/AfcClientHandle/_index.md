---
title: AfcClientHandle class
---

Represents a wrapper class for Afc handles.

```csharp
public class AfcClientHandle : SafeHandleZeroOrMinusOneIsInvalid
```

## Public Members

| name | description |
| --- | --- |
| static [Zero](AfcClientHandle/Zero.md) { get; } | Gets a value which represents a pointer or handle that has been initialized to zero. |
| static [DangerousCreate](AfcClientHandle/DangerousCreate.md)(…) | Creates a new [`AfcClientHandle`](AfcClientHandle.md) from a IntPtr. (2 methods) |
| [Api](AfcClientHandle/Api.md) { get; set; } | Gets or sets the API to use |
| override [Equals](AfcClientHandle/Equals.md)(…) |  |
| override [GetHashCode](AfcClientHandle/GetHashCode.md)() |  |
| override [ToString](AfcClientHandle/ToString.md)() |  |
| [operator ==](AfcClientHandle/op_Equality.md) | Determines whether two specified instances of [`AfcClientHandle`](AfcClientHandle.md) are equal. |
| [operator !=](AfcClientHandle/op_Inequality.md) | Determines whether two specified instances of [`AfcClientHandle`](AfcClientHandle.md) are not equal. |

## Protected Members

| name | description |
| --- | --- |
| [AfcClientHandle](AfcClientHandle/AfcClientHandle.md)() | Initializes a new instance of the [`AfcClientHandle`](AfcClientHandle.md) class. |
| [AfcClientHandle](AfcClientHandle/AfcClientHandle.md)(…) | Initializes a new instance of the [`AfcClientHandle`](AfcClientHandle.md) class, specifying whether the handle is to be reliably released. |
| override [ReleaseHandle](AfcClientHandle/ReleaseHandle.md)() |  |

## See Also

* namespace [iMobileDevice.Afc](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->