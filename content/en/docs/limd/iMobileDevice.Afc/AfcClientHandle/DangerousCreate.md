---
title: AfcClientHandle.DangerousCreate method (1 of 2)
---

Creates a new [`AfcClientHandle`](../AfcClientHandle.md) from a IntPtr.

```csharp
public static AfcClientHandle DangerousCreate(IntPtr unsafeHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |

## See Also

* class [AfcClientHandle](../AfcClientHandle.md)
* namespace [iMobileDevice.Afc](../../iMobileDevice-net.md)

---

---
title: AfcClientHandle.DangerousCreate method (2 of 2)
---

Creates a new [`AfcClientHandle`](../AfcClientHandle.md) from a IntPtr.

```csharp
public static AfcClientHandle DangerousCreate(IntPtr unsafeHandle, bool ownsHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |
| ownsHandle | `true` to reliably release the handle during the finalization phase; `false` to prevent reliable release (not recommended). |

## See Also

* class [AfcClientHandle](../AfcClientHandle.md)
* namespace [iMobileDevice.Afc](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
