---
title: iDeviceNativeMethods.idevice_get_socket_type method
---

Gets the socket type (Unix socket or TCP socket) libimobiledevice should use when connecting to usbmuxd.

```csharp
public static iDeviceError idevice_get_socket_type(ref int value)
```

| parameter | description |
| --- | --- |
| value | A pointer to an integer which will reveive the current socket type |

## Return Value

0 on success or negative on error

## See Also

* enum [iDeviceError](../iDeviceError.md)
* class [iDeviceNativeMethods](../iDeviceNativeMethods.md)
* namespace [iMobileDevice.iDevice](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->