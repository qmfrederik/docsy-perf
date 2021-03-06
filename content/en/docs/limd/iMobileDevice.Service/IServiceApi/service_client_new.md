---
title: IServiceApi.service_client_new method
---

Creates a new service for the specified service descriptor.

```csharp
public ServiceError service_client_new(iDeviceHandle device, 
    LockdownServiceDescriptorHandle service, out ServiceClientHandle client)
```

| parameter | description |
| --- | --- |
| device | The device to connect to. |
| service | The service descriptor returned by lockdownd_start_service. |
| client | Pointer that will be set to a newly allocated service_client_t upon successful return. |

## Return Value

SERVICE_E_SUCCESS on success, SERVICE_E_INVALID_ARG when one of the arguments is invalid, or SERVICE_E_MUX_ERROR when connecting to the device failed.

## See Also

* enum [ServiceError](../ServiceError.md)
* class [iDeviceHandle](../../iMobileDevice.iDevice/iDeviceHandle.md)
* class [LockdownServiceDescriptorHandle](../../iMobileDevice.Lockdown/LockdownServiceDescriptorHandle.md)
* class [ServiceClientHandle](../ServiceClientHandle.md)
* interface [IServiceApi](../IServiceApi.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
