---
title: WebInspectorNativeMethods.webinspector_send method
---

Sends a plist to the service.

```csharp
public static WebInspectorError webinspector_send(WebInspectorClientHandle client, 
    PlistHandle plist)
```

| parameter | description |
| --- | --- |
| client | The webinspector client |
| plist | The plist to send |

## Return Value

DIAGNOSTICS_RELAY_E_SUCCESS on success, DIAGNOSTICS_RELAY_E_INVALID_ARG when client or plist is NULL

## See Also

* enum [WebInspectorError](../WebInspectorError.md)
* class [WebInspectorClientHandle](../WebInspectorClientHandle.md)
* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* class [WebInspectorNativeMethods](../WebInspectorNativeMethods.md)
* namespace [iMobileDevice.WebInspector](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
