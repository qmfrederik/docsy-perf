---
title: IInstallationProxyApi.instproxy_client_get_path_for_bundle_identifier method
---

Queries the device for the path of an application.

```csharp
public InstallationProxyError instproxy_client_get_path_for_bundle_identifier(
    InstallationProxyClientHandle client, string bundleId, out string path)
```

| parameter | description |
| --- | --- |
| client | The connected installation proxy client. |
| appid | ApplicationIdentifier of app to retrieve the path for. |
| path | Pointer to store the device path for the application which is set to NULL if it could not be determined. |

## Return Value

INSTPROXY_E_SUCCESS on success, INSTPROXY_E_OP_FAILED if the path could not be determined or an INSTPROXY_E_* error value if an error occurred.

## See Also

* enum [InstallationProxyError](../InstallationProxyError.md)
* class [InstallationProxyClientHandle](../InstallationProxyClientHandle.md)
* interface [IInstallationProxyApi](../IInstallationProxyApi.md)
* namespace [iMobileDevice.InstallationProxy](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
