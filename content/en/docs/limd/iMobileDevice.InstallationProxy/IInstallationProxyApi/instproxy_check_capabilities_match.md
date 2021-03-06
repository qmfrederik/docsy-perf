---
title: IInstallationProxyApi.instproxy_check_capabilities_match method
---

Checks a device for certain capabilities.

```csharp
public InstallationProxyError instproxy_check_capabilities_match(
    InstallationProxyClientHandle client, out string capabilities, PlistHandle clientOptions, 
    out PlistHandle result)
```

| parameter | description |
| --- | --- |
| client | The connected installation_proxy client |
| capabilities | An array of char* with capability names that MUST have a terminatingÂ NULL entry. |
| client_options | The client options to use, as PLIST_DICT, or NULL. Currently there are no known client options, so pass NULL here. |
| result | Pointer that will be set to a plist containing a PLIST_DICT holding information if the capabilities matched or NULL on errors. |

## Return Value

INSTPROXY_E_SUCCESS on success or an INSTPROXY_E_* error value if an error occurred.

## See Also

* enum [InstallationProxyError](../InstallationProxyError.md)
* class [InstallationProxyClientHandle](../InstallationProxyClientHandle.md)
* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* interface [IInstallationProxyApi](../IInstallationProxyApi.md)
* namespace [iMobileDevice.InstallationProxy](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
