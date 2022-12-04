---
title: RestoreApi.restored_client_new method
---

Creates a new restored client for the device.

```csharp
public virtual RestoreError restored_client_new(iDeviceHandle device, 
    out RestoreClientHandle client, string label)
```

| parameter | description |
| --- | --- |
| device | The device to create a restored client for |
| client | The pointer to the location of the new restored_client |
| label | The label to use for communication. Usually the program name. |

## Return Value

RESTORE_E_SUCCESS on success, RESTORE_E_INVALID_ARG when client is NULL

## See Also

* enum [RestoreError](../RestoreError.md)
* class [iDeviceHandle](../../iMobileDevice.iDevice/iDeviceHandle.md)
* class [RestoreClientHandle](../RestoreClientHandle.md)
* class [RestoreApi](../RestoreApi.md)
* namespace [iMobileDevice.Restore](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->