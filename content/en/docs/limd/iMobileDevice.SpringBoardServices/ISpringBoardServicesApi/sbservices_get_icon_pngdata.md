---
title: ISpringBoardServicesApi.sbservices_get_icon_pngdata method
---

Get the icon of the specified app as PNG data.

```csharp
public SpringBoardServicesError sbservices_get_icon_pngdata(SpringBoardServicesClientHandle client, 
    string bundleid, ref IntPtr pngdata, ref ulong pngsize)
```

| parameter | description |
| --- | --- |
| client | The connected sbservices client to use. |
| bundleId | The bundle identifier of the app to retrieve the icon for. |
| pngdata | Pointer that will point to a newly allocated buffer containing the PNG data upon successful return. It is up to the caller to free the memory. |
| pngsize | Pointer to a uint64_t that will be set to the size of the buffer pngdata points to upon successful return. |

## Return Value

SBSERVICES_E_SUCCESS on success, SBSERVICES_E_INVALID_ARG when client, bundleId, or pngdata are invalid, or an SBSERVICES_E_* error code otherwise.

## See Also

* enum [SpringBoardServicesError](../SpringBoardServicesError.md)
* class [SpringBoardServicesClientHandle](../SpringBoardServicesClientHandle.md)
* interface [ISpringBoardServicesApi](../ISpringBoardServicesApi.md)
* namespace [iMobileDevice.SpringBoardServices](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->