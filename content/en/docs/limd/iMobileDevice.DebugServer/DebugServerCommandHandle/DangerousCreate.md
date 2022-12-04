---
title: DebugServerCommandHandle.DangerousCreate method (1 of 2)
---

Creates a new [`DebugServerCommandHandle`](../DebugServerCommandHandle.md) from a IntPtr.

```csharp
public static DebugServerCommandHandle DangerousCreate(IntPtr unsafeHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |

## See Also

* class [DebugServerCommandHandle](../DebugServerCommandHandle.md)
* namespace [iMobileDevice.DebugServer](../../iMobileDevice-net.md)

---

---
title: DebugServerCommandHandle.DangerousCreate method (2 of 2)
---

Creates a new [`DebugServerCommandHandle`](../DebugServerCommandHandle.md) from a IntPtr.

```csharp
public static DebugServerCommandHandle DangerousCreate(IntPtr unsafeHandle, bool ownsHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |
| ownsHandle | `true` to reliably release the handle during the finalization phase; `false` to prevent reliable release (not recommended). |

## See Also

* class [DebugServerCommandHandle](../DebugServerCommandHandle.md)
* namespace [iMobileDevice.DebugServer](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->