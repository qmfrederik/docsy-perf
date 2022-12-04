---
title: MobileBackupClientHandle class
---

Represents a wrapper class for MobileBackup handles.

```csharp
public class MobileBackupClientHandle : SafeHandleZeroOrMinusOneIsInvalid
```

## Public Members

| name | description |
| --- | --- |
| static [Zero](MobileBackupClientHandle/Zero.md) { get; } | Gets a value which represents a pointer or handle that has been initialized to zero. |
| static [DangerousCreate](MobileBackupClientHandle/DangerousCreate.md)(…) | Creates a new [`MobileBackupClientHandle`](MobileBackupClientHandle.md) from a IntPtr. (2 methods) |
| [Api](MobileBackupClientHandle/Api.md) { get; set; } | Gets or sets the API to use |
| override [Equals](MobileBackupClientHandle/Equals.md)(…) |  |
| override [GetHashCode](MobileBackupClientHandle/GetHashCode.md)() |  |
| override [ToString](MobileBackupClientHandle/ToString.md)() |  |
| [operator ==](MobileBackupClientHandle/op_Equality.md) | Determines whether two specified instances of [`MobileBackupClientHandle`](MobileBackupClientHandle.md) are equal. |
| [operator !=](MobileBackupClientHandle/op_Inequality.md) | Determines whether two specified instances of [`MobileBackupClientHandle`](MobileBackupClientHandle.md) are not equal. |

## Protected Members

| name | description |
| --- | --- |
| [MobileBackupClientHandle](MobileBackupClientHandle/MobileBackupClientHandle.md)() | Initializes a new instance of the [`MobileBackupClientHandle`](MobileBackupClientHandle.md) class. |
| [MobileBackupClientHandle](MobileBackupClientHandle/MobileBackupClientHandle.md)(…) | Initializes a new instance of the [`MobileBackupClientHandle`](MobileBackupClientHandle.md) class, specifying whether the handle is to be reliably released. |
| override [ReleaseHandle](MobileBackupClientHandle/ReleaseHandle.md)() |  |

## See Also

* namespace [iMobileDevice.MobileBackup](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->