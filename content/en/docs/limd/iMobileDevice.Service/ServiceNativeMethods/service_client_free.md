---
title: ServiceNativeMethods.service_client_free method
---

Frees a service instance.

```csharp
public static ServiceError service_client_free(IntPtr client)
```

| parameter | description |
| --- | --- |
| client | The service instance to free. |

## Return Value

SERVICE_E_SUCCESS on success, SERVICE_E_INVALID_ARG when client is invalid, or a SERVICE_E_UNKNOWN_ERROR when another error occurred.

## See Also

* enum [ServiceError](../ServiceError.md)
* class [ServiceNativeMethods](../ServiceNativeMethods.md)
* namespace [iMobileDevice.Service](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
