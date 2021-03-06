---
title: LockdownServiceDescriptorHandle class
---

Represents a wrapper class for Lockdown handles.

```csharp
public class LockdownServiceDescriptorHandle : SafeHandleZeroOrMinusOneIsInvalid
```

## Public Members

| name | description |
| --- | --- |
| static [Zero](LockdownServiceDescriptorHandle/Zero.md) { get; } | Gets a value which represents a pointer or handle that has been initialized to zero. |
| static [DangerousCreate](LockdownServiceDescriptorHandle/DangerousCreate.md)(…) | Creates a new [`LockdownServiceDescriptorHandle`](LockdownServiceDescriptorHandle.md) from a IntPtr. (2 methods) |
| [Api](LockdownServiceDescriptorHandle/Api.md) { get; set; } | Gets or sets the API to use |
| virtual [Value](LockdownServiceDescriptorHandle/Value.md) { get; } |  |
| override [Equals](LockdownServiceDescriptorHandle/Equals.md)(…) |  |
| override [GetHashCode](LockdownServiceDescriptorHandle/GetHashCode.md)() |  |
| override [ToString](LockdownServiceDescriptorHandle/ToString.md)() |  |
| [operator ==](LockdownServiceDescriptorHandle/op_Equality.md) | Determines whether two specified instances of [`LockdownServiceDescriptorHandle`](LockdownServiceDescriptorHandle.md) are equal. |
| [operator !=](LockdownServiceDescriptorHandle/op_Inequality.md) | Determines whether two specified instances of [`LockdownServiceDescriptorHandle`](LockdownServiceDescriptorHandle.md) are not equal. |

## Protected Members

| name | description |
| --- | --- |
| [LockdownServiceDescriptorHandle](LockdownServiceDescriptorHandle/LockdownServiceDescriptorHandle.md)() | Initializes a new instance of the [`LockdownServiceDescriptorHandle`](LockdownServiceDescriptorHandle.md) class. |
| [LockdownServiceDescriptorHandle](LockdownServiceDescriptorHandle/LockdownServiceDescriptorHandle.md)(…) | Initializes a new instance of the [`LockdownServiceDescriptorHandle`](LockdownServiceDescriptorHandle.md) class, specifying whether the handle is to be reliably released. |
| override [ReleaseHandle](LockdownServiceDescriptorHandle/ReleaseHandle.md)() |  |

## See Also

* namespace [iMobileDevice.Lockdown](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
