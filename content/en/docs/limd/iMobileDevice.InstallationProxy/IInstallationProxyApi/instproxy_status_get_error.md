---
title: IInstallationProxyApi.instproxy_status_get_error method
---

Gets error name, code and description from a response if available.

```csharp
public InstallationProxyError instproxy_status_get_error(PlistHandle status, out string name, 
    out string description, ref ulong code)
```

| parameter | description |
| --- | --- |
| status | The dictionary status response to use. |
| name | Pointer to store the name of an error. |
| description | Pointer to store error description text if available. The caller is reponsible for freeing the allocated buffer after use. If NULL is passed no description will be returned. |
| code | Pointer to store the returned error code if available. If NULL is passed no error code will be returned. |

## Return Value

INSTPROXY_E_SUCCESS if no error is found or an INSTPROXY_E_* error value matching the error that áºƒas found in the status.

## See Also

* enum [InstallationProxyError](../InstallationProxyError.md)
* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* interface [IInstallationProxyApi](../IInstallationProxyApi.md)
* namespace [iMobileDevice.InstallationProxy](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
