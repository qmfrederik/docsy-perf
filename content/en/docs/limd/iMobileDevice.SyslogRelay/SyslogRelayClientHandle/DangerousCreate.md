---
title: SyslogRelayClientHandle.DangerousCreate method (1 of 2)
---

Creates a new [`SyslogRelayClientHandle`](../SyslogRelayClientHandle.md) from a IntPtr.

```csharp
public static SyslogRelayClientHandle DangerousCreate(IntPtr unsafeHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |

## See Also

* class [SyslogRelayClientHandle](../SyslogRelayClientHandle.md)
* namespace [iMobileDevice.SyslogRelay](../../iMobileDevice-net.md)

---

---
title: SyslogRelayClientHandle.DangerousCreate method (2 of 2)
---

Creates a new [`SyslogRelayClientHandle`](../SyslogRelayClientHandle.md) from a IntPtr.

```csharp
public static SyslogRelayClientHandle DangerousCreate(IntPtr unsafeHandle, bool ownsHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |
| ownsHandle | `true` to reliably release the handle during the finalization phase; `false` to prevent reliable release (not recommended). |

## See Also

* class [SyslogRelayClientHandle](../SyslogRelayClientHandle.md)
* namespace [iMobileDevice.SyslogRelay](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->