---
title: ServiceClientHandle.DangerousCreate method (1 of 2)
---

Creates a new [`ServiceClientHandle`](../ServiceClientHandle.md) from a IntPtr.

```csharp
public static ServiceClientHandle DangerousCreate(IntPtr unsafeHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |

## See Also

* class [ServiceClientHandle](../ServiceClientHandle.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

---

---
title: ServiceClientHandle.DangerousCreate method (2 of 2)
---

Creates a new [`ServiceClientHandle`](../ServiceClientHandle.md) from a IntPtr.

```csharp
public static ServiceClientHandle DangerousCreate(IntPtr unsafeHandle, bool ownsHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |
| ownsHandle | `true` to reliably release the handle during the finalization phase; `false` to prevent reliable release (not recommended). |

## See Also

* class [ServiceClientHandle](../ServiceClientHandle.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
