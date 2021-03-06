---
title: IMobileSyncApi.mobilesync_client_start_service method
---

Starts a new mobilesync service on the specified device and connects to it.

```csharp
public MobileSyncError mobilesync_client_start_service(iDeviceHandle device, 
    out MobileSyncClientHandle client, string label)
```

| parameter | description |
| --- | --- |
| device | The device to connect to. |
| client | Pointer that will point to a newly allocated mobilesync_client_t upon successful return. Must be freed using mobilesync_client_free() after use. |
| label | The label to use for communication. Usually the program name. Pass NULL to disable sending the label in requests to lockdownd. |

## Return Value

MOBILESYNC_E_SUCCESS on success, or an MOBILESYNC_E_* error code otherwise.

## See Also

* enum [MobileSyncError](../MobileSyncError.md)
* class [iDeviceHandle](../../iMobileDevice.iDevice/iDeviceHandle.md)
* class [MobileSyncClientHandle](../MobileSyncClientHandle.md)
* interface [IMobileSyncApi](../IMobileSyncApi.md)
* namespace [iMobileDevice.MobileSync](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
