---
title: MisagentClientHandle class
---

Represents a wrapper class for Misagent handles.

```csharp
public class MisagentClientHandle : SafeHandleZeroOrMinusOneIsInvalid
```

## Public Members

| name | description |
| --- | --- |
| static [Zero](MisagentClientHandle/Zero.md) { get; } | Gets a value which represents a pointer or handle that has been initialized to zero. |
| static [DangerousCreate](MisagentClientHandle/DangerousCreate.md)(…) | Creates a new [`MisagentClientHandle`](MisagentClientHandle.md) from a IntPtr. (2 methods) |
| [Api](MisagentClientHandle/Api.md) { get; set; } | Gets or sets the API to use |
| override [Equals](MisagentClientHandle/Equals.md)(…) |  |
| override [GetHashCode](MisagentClientHandle/GetHashCode.md)() |  |
| override [ToString](MisagentClientHandle/ToString.md)() |  |
| [operator ==](MisagentClientHandle/op_Equality.md) | Determines whether two specified instances of [`MisagentClientHandle`](MisagentClientHandle.md) are equal. |
| [operator !=](MisagentClientHandle/op_Inequality.md) | Determines whether two specified instances of [`MisagentClientHandle`](MisagentClientHandle.md) are not equal. |

## Protected Members

| name | description |
| --- | --- |
| [MisagentClientHandle](MisagentClientHandle/MisagentClientHandle.md)() | Initializes a new instance of the [`MisagentClientHandle`](MisagentClientHandle.md) class. |
| [MisagentClientHandle](MisagentClientHandle/MisagentClientHandle.md)(…) | Initializes a new instance of the [`MisagentClientHandle`](MisagentClientHandle.md) class, specifying whether the handle is to be reliably released. |
| override [ReleaseHandle](MisagentClientHandle/ReleaseHandle.md)() |  |

## See Also

* namespace [iMobileDevice.Misagent](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
