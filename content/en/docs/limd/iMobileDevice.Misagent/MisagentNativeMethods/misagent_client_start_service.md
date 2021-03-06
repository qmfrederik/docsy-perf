---
title: MisagentNativeMethods.misagent_client_start_service method
---

Starts a new misagent service on the specified device and connects to it.

```csharp
public static MisagentError misagent_client_start_service(iDeviceHandle device, 
    out MisagentClientHandle client, string label)
```

| parameter | description |
| --- | --- |
| device | The device to connect to. |
| client | Pointer that will point to a newly allocated misagent_client_t upon successful return. Must be freed using misagent_client_free() after use. |
| label | The label to use for communication. Usually the program name. Pass NULL to disable sending the label in requests to lockdownd. |

## Return Value

MISAGENT_E_SUCCESS on success, or an MISAGENT_E_* error code otherwise.

## See Also

* enum [MisagentError](../MisagentError.md)
* class [iDeviceHandle](../../iMobileDevice.iDevice/iDeviceHandle.md)
* class [MisagentClientHandle](../MisagentClientHandle.md)
* class [MisagentNativeMethods](../MisagentNativeMethods.md)
* namespace [iMobileDevice.Misagent](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
