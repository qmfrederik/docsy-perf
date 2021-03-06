---
title: iDeviceConnectionHandle.DangerousCreate method (1 of 2)
---

Creates a new [`iDeviceConnectionHandle`](../iDeviceConnectionHandle.md) from a IntPtr.

```csharp
public static iDeviceConnectionHandle DangerousCreate(IntPtr unsafeHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |

## See Also

* class [iDeviceConnectionHandle](../iDeviceConnectionHandle.md)
* namespace [iMobileDevice.iDevice](../../iMobileDevice-net.md)

---

---
title: iDeviceConnectionHandle.DangerousCreate method (2 of 2)
---

Creates a new [`iDeviceConnectionHandle`](../iDeviceConnectionHandle.md) from a IntPtr.

```csharp
public static iDeviceConnectionHandle DangerousCreate(IntPtr unsafeHandle, bool ownsHandle)
```

| parameter | description |
| --- | --- |
| unsafeHandle | The underlying IntPtr |
| ownsHandle | `true` to reliably release the handle during the finalization phase; `false` to prevent reliable release (not recommended). |

## See Also

* class [iDeviceConnectionHandle](../iDeviceConnectionHandle.md)
* namespace [iMobileDevice.iDevice](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
