---
title: SpringBoardServicesNativeMethods.sbservices_client_new method
---

Connects to the springboardservices service on the specified device.

```csharp
public static SpringBoardServicesError sbservices_client_new(iDeviceHandle device, 
    LockdownServiceDescriptorHandle service, out SpringBoardServicesClientHandle client)
```

| parameter | description |
| --- | --- |
| device | The device to connect to. |
| service | The service descriptor returned by lockdownd_start_service. |
| client | Pointer that will point to a newly allocated sbservices_client_t upon successful return. |

## Return Value

SBSERVICES_E_SUCCESS on success, SBSERVICES_E_INVALID_ARG when client is NULL, or an SBSERVICES_E_* error code otherwise.

## See Also

* enum [SpringBoardServicesError](../SpringBoardServicesError.md)
* class [iDeviceHandle](../../iMobileDevice.iDevice/iDeviceHandle.md)
* class [LockdownServiceDescriptorHandle](../../iMobileDevice.Lockdown/LockdownServiceDescriptorHandle.md)
* class [SpringBoardServicesClientHandle](../SpringBoardServicesClientHandle.md)
* class [SpringBoardServicesNativeMethods](../SpringBoardServicesNativeMethods.md)
* namespace [iMobileDevice.SpringBoardServices](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->