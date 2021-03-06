---
title: LockdownApi.lockdownd_enter_recovery method
---

Tells the device to immediately enter recovery mode.

```csharp
public virtual LockdownError lockdownd_enter_recovery(LockdownClientHandle client)
```

| parameter | description |
| --- | --- |
| client | The lockdown client |

## Return Value

LOCKDOWN_E_SUCCESS on success, LOCKDOWN_E_INVALID_ARG when client is NULL

## See Also

* enum [LockdownError](../LockdownError.md)
* class [LockdownClientHandle](../LockdownClientHandle.md)
* class [LockdownApi](../LockdownApi.md)
* namespace [iMobileDevice.Lockdown](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
