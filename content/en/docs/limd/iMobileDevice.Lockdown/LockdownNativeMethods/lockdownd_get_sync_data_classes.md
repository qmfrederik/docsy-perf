---
title: LockdownNativeMethods.lockdownd_get_sync_data_classes method (1 of 2)
---

Calculates and returns the data classes the device supports from lockdownd.

```csharp
public static LockdownError lockdownd_get_sync_data_classes(LockdownClientHandle client, 
    out IntPtr classes, ref int count)
```

| parameter | description |
| --- | --- |
| client | An initialized lockdownd client. |
| classes | A pointer to store an array of class names. The caller is responsible for freeing the memory which can be done using mobilesync_data_classes_free(). |
| count | The number of items in the classes array. |

## Return Value

LOCKDOWN_E_SUCCESS on success, LOCKDOWN_E_INVALID_ARG when client is NULL, LOCKDOWN_E_NO_RUNNING_SESSION if no session is open, LOCKDOWN_E_PLIST_ERROR if the received plist is broken

## See Also

* enum [LockdownError](../LockdownError.md)
* class [LockdownClientHandle](../LockdownClientHandle.md)
* class [LockdownNativeMethods](../LockdownNativeMethods.md)
* namespace [iMobileDevice.Lockdown](../../iMobileDevice-net.md)

---

---
title: LockdownNativeMethods.lockdownd_get_sync_data_classes method (2 of 2)
---

```csharp
public static LockdownError lockdownd_get_sync_data_classes(LockdownClientHandle client, 
    out ReadOnlyCollection<string> classes, ref int count)
```

## See Also

* enum [LockdownError](../LockdownError.md)
* class [LockdownClientHandle](../LockdownClientHandle.md)
* class [LockdownNativeMethods](../LockdownNativeMethods.md)
* namespace [iMobileDevice.Lockdown](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
