---
title: IServiceApi.service_receive_with_timeout method
---

Receives data using the given service client with specified timeout.

```csharp
public ServiceError service_receive_with_timeout(ServiceClientHandle client, byte[] data, 
    uint size, ref uint received, uint timeout)
```

| parameter | description |
| --- | --- |
| client | The service client to use for receiving |
| data | Buffer that will be filled with the data received |
| size | Number of bytes to receive |
| received | Number of bytes received (can be NULL to ignore) |
| timeout | Maximum time in milliseconds to wait for data. |

## Return Value

SERVICE_E_SUCCESS on success, SERVICE_E_INVALID_ARG when one or more parameters are invalid, SERVICE_E_MUX_ERROR when a communication error occurs, or SERVICE_E_UNKNOWN_ERROR when an unspecified error occurs.

## See Also

* enum [ServiceError](../ServiceError.md)
* class [ServiceClientHandle](../ServiceClientHandle.md)
* interface [IServiceApi](../IServiceApi.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
