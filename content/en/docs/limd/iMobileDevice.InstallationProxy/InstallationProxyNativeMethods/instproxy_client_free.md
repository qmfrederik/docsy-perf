---
title: InstallationProxyNativeMethods.instproxy_client_free method
---

Disconnects an installation_proxy client from the device and frees up the installation_proxy client data.

```csharp
public static InstallationProxyError instproxy_client_free(IntPtr client)
```

| parameter | description |
| --- | --- |
| client | The installation_proxy client to disconnect and free. |

## Return Value

INSTPROXY_E_SUCCESS on success or INSTPROXY_E_INVALID_ARG if client is NULL.

## See Also

* enum [InstallationProxyError](../InstallationProxyError.md)
* class [InstallationProxyNativeMethods](../InstallationProxyNativeMethods.md)
* namespace [iMobileDevice.InstallationProxy](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
