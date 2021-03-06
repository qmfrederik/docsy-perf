---
title: IInstallationProxyApi.instproxy_client_new method
---

Connects to the installation_proxy service on the specified device.

```csharp
public InstallationProxyError instproxy_client_new(iDeviceHandle device, 
    LockdownServiceDescriptorHandle service, out InstallationProxyClientHandle client)
```

| parameter | description |
| --- | --- |
| device | The device to connect to |
| service | The service descriptor returned by lockdownd_start_service. |
| client | Pointer that will be set to a newly allocated instproxy_client_t upon successful return. |

## Return Value

INSTPROXY_E_SUCCESS on success, or an INSTPROXY_E_* error value when an error occurred.

## See Also

* enum [InstallationProxyError](../InstallationProxyError.md)
* class [iDeviceHandle](../../iMobileDevice.iDevice/iDeviceHandle.md)
* class [LockdownServiceDescriptorHandle](../../iMobileDevice.Lockdown/LockdownServiceDescriptorHandle.md)
* class [InstallationProxyClientHandle](../InstallationProxyClientHandle.md)
* interface [IInstallationProxyApi](../IInstallationProxyApi.md)
* namespace [iMobileDevice.InstallationProxy](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
