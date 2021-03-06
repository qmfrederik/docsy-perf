---
title: IDebugServerApi.debugserver_client_send method
---

Sends raw data using the given debugserver service client.

```csharp
public DebugServerError debugserver_client_send(DebugServerClientHandle client, byte[] data, 
    uint size, ref uint sent)
```

| parameter | description |
| --- | --- |
| client | The debugserver client to use for sending |
| data | Data to send |
| size | Size of the data to send |
| sent | Number of bytes sent (can be NULL to ignore) |

## Return Value

DEBUGSERVER_E_SUCCESS on success, DEBUGSERVER_E_INVALID_ARG when one or more parameters are invalid, or DEBUGSERVER_E_UNKNOWN_ERROR when an unspecified error occurs.

## See Also

* enum [DebugServerError](../DebugServerError.md)
* class [DebugServerClientHandle](../DebugServerClientHandle.md)
* interface [IDebugServerApi](../IDebugServerApi.md)
* namespace [iMobileDevice.DebugServer](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
