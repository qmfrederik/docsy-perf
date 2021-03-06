---
title: FileRelayNativeMethods.file_relay_request_sources method (1 of 2)
---

Request data for the given sources.

```csharp
public static FileRelayError file_relay_request_sources(FileRelayClientHandle client, 
    out IntPtr sources, out iDeviceConnectionHandle connection)
```

| parameter | description |
| --- | --- |
| client | The connected file_relay client. |
| sources | A NULL-terminated list of sources to retrieve. Valid sources are: - AppleSupport - Network - VPN - WiFi - UserDatabases - CrashReporter - tmp - SystemConfiguration |
| connection | The connection that has to be used for receiving the data using idevice_connection_receive(). The connection will be closed automatically by the device, but use file_relay_client_free() to clean up properly. |
| timeout | Maximum time in milliseconds to wait for data. |

## Return Value

FILE_RELAY_E_SUCCESS on succes, FILE_RELAY_E_INVALID_ARG when one or more parameters are invalid, FILE_RELAY_E_MUX_ERROR if a communication error occurs, FILE_RELAY_E_PLIST_ERROR when the received result is NULL or is not a valid plist, FILE_RELAY_E_INVALID_SOURCE if one or more sources are invalid, FILE_RELAY_E_STAGING_EMPTY if no data is available for the given sources, or FILE_RELAY_E_UNKNOWN_ERROR otherwise.

## Remarks

WARNING: Don't call this function without reading the data afterwards. A directory mobile_file_relay.XXXX used for creating the archive will remain in the /tmp directory otherwise.

## See Also

* enum [FileRelayError](../FileRelayError.md)
* class [FileRelayClientHandle](../FileRelayClientHandle.md)
* class [iDeviceConnectionHandle](../../iMobileDevice.iDevice/iDeviceConnectionHandle.md)
* class [FileRelayNativeMethods](../FileRelayNativeMethods.md)
* namespace [iMobileDevice.FileRelay](../../iMobileDevice-net.md)

---

---
title: FileRelayNativeMethods.file_relay_request_sources method (2 of 2)
---

```csharp
public static FileRelayError file_relay_request_sources(FileRelayClientHandle client, 
    out string sources, out iDeviceConnectionHandle connection)
```

## See Also

* enum [FileRelayError](../FileRelayError.md)
* class [FileRelayClientHandle](../FileRelayClientHandle.md)
* class [iDeviceConnectionHandle](../../iMobileDevice.iDevice/iDeviceConnectionHandle.md)
* class [FileRelayNativeMethods](../FileRelayNativeMethods.md)
* namespace [iMobileDevice.FileRelay](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
