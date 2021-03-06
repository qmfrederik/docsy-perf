---
title: IDiagnosticsRelayApi.diagnostics_relay_client_start_service method
---

Starts a new diagnostics_relay service on the specified device and connects to it.

```csharp
public DiagnosticsRelayError diagnostics_relay_client_start_service(iDeviceHandle device, 
    out DiagnosticsRelayClientHandle client, string label)
```

| parameter | description |
| --- | --- |
| device | The device to connect to. |
| client | Pointer that will point to a newly allocated diagnostics_relay_client_t upon successful return. Must be freed using diagnostics_relay_client_free() after use. |
| label | The label to use for communication. Usually the program name. Pass NULL to disable sending the label in requests to lockdownd. |

## Return Value

DIAGNOSTICS_RELAY_E_SUCCESS on success, or an DIAGNOSTICS_RELAY_E_* error code otherwise.

## See Also

* enum [DiagnosticsRelayError](../DiagnosticsRelayError.md)
* class [iDeviceHandle](../../iMobileDevice.iDevice/iDeviceHandle.md)
* class [DiagnosticsRelayClientHandle](../DiagnosticsRelayClientHandle.md)
* interface [IDiagnosticsRelayApi](../IDiagnosticsRelayApi.md)
* namespace [iMobileDevice.DiagnosticsRelay](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
