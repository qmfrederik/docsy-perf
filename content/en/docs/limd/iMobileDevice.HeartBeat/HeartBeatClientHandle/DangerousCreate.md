---
title: HeartBeatClientHandle.DangerousCreate method (1 of 2)
---

Creates a new [`HeartBeatClientHandle`](../HeartBeatClientHandle.md) from a IntPtr.

```csharp
public static HeartBeatClientHandle DangerousCreate(IntPtr unsafeHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |

## See Also

* class [HeartBeatClientHandle](../HeartBeatClientHandle.md)
* namespace [iMobileDevice.HeartBeat](../../iMobileDevice-net.md)

---

---
title: HeartBeatClientHandle.DangerousCreate method (2 of 2)
---

Creates a new [`HeartBeatClientHandle`](../HeartBeatClientHandle.md) from a IntPtr.

```csharp
public static HeartBeatClientHandle DangerousCreate(IntPtr unsafeHandle, bool ownsHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |
| ownsHandle | `true` to reliably release the handle during the finalization phase; `false` to prevent reliable release (not recommended). |

## See Also

* class [HeartBeatClientHandle](../HeartBeatClientHandle.md)
* namespace [iMobileDevice.HeartBeat](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
