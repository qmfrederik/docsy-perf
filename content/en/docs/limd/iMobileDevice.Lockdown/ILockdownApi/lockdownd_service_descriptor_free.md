---
title: ILockdownApi.lockdownd_service_descriptor_free method
---

Frees memory of a service descriptor as returned by lockdownd_start_service()

```csharp
public LockdownError lockdownd_service_descriptor_free(IntPtr service)
```

| parameter | description |
| --- | --- |
| service | A service descriptor instance to free. |

## Return Value

LOCKDOWN_E_SUCCESS on success

## See Also

* enum [LockdownError](../LockdownError.md)
* interface [ILockdownApi](../ILockdownApi.md)
* namespace [iMobileDevice.Lockdown](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
