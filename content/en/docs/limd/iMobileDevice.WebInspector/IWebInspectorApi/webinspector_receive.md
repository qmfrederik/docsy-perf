---
title: IWebInspectorApi.webinspector_receive method
---

Receives a plist from the service.

```csharp
public WebInspectorError webinspector_receive(WebInspectorClientHandle client, 
    out PlistHandle plist)
```

| parameter | description |
| --- | --- |
| client | The webinspector client |
| plist | The plist to store the received data |

## Return Value

DIAGNOSTICS_RELAY_E_SUCCESS on success, DIAGNOSTICS_RELAY_E_INVALID_ARG when client or plist is NULL

## See Also

* enum [WebInspectorError](../WebInspectorError.md)
* class [WebInspectorClientHandle](../WebInspectorClientHandle.md)
* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* interface [IWebInspectorApi](../IWebInspectorApi.md)
* namespace [iMobileDevice.WebInspector](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->