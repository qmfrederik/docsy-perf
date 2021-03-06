---
title: DebugServerNativeMethods.debugserver_client_receive_with_timeout method
---

Receives raw data using the given debugserver client with specified timeout.

```csharp
public static DebugServerError debugserver_client_receive_with_timeout(
    DebugServerClientHandle client, byte[] data, uint size, ref uint received, uint timeout)
```

| parameter | description |
| --- | --- |
| client | The debugserver client to use for receiving |
| data | Buffer that will be filled with the data received |
| size | Number of bytes to receive |
| received | Number of bytes received (can be NULL to ignore) |
| timeout | Maximum time in milliseconds to wait for data. |

## Return Value

DEBUGSERVER_E_SUCCESS on success, DEBUGSERVER_E_INVALID_ARG when one or more parameters are invalid, DEBUGSERVER_E_MUX_ERROR when a communication error occurs, or DEBUGSERVER_E_UNKNOWN_ERROR when an unspecified error occurs.

## See Also

* enum [DebugServerError](../DebugServerError.md)
* class [DebugServerClientHandle](../DebugServerClientHandle.md)
* class [DebugServerNativeMethods](../DebugServerNativeMethods.md)
* namespace [iMobileDevice.DebugServer](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
