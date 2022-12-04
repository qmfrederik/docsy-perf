---
title: MobileBackupClientHandle.DangerousCreate method (1 of 2)
---

Creates a new [`MobileBackupClientHandle`](../MobileBackupClientHandle.md) from a IntPtr.

```csharp
public static MobileBackupClientHandle DangerousCreate(IntPtr unsafeHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |

## See Also

* class [MobileBackupClientHandle](../MobileBackupClientHandle.md)
* namespace [iMobileDevice.MobileBackup](../../iMobileDevice-net.md)

---

---
title: MobileBackupClientHandle.DangerousCreate method (2 of 2)
---

Creates a new [`MobileBackupClientHandle`](../MobileBackupClientHandle.md) from a IntPtr.

```csharp
public static MobileBackupClientHandle DangerousCreate(IntPtr unsafeHandle, bool ownsHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |
| ownsHandle | `true` to reliably release the handle during the finalization phase; `false` to prevent reliable release (not recommended). |

## See Also

* class [MobileBackupClientHandle](../MobileBackupClientHandle.md)
* namespace [iMobileDevice.MobileBackup](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->