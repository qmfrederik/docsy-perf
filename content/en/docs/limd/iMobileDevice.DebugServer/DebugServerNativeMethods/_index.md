---
title: DebugServerNativeMethods class
---

```csharp
public class DebugServerNativeMethods
```

## Public Members

| name | description |
| --- | --- |
| [DebugServerNativeMethods](DebugServerNativeMethods/DebugServerNativeMethods.md)() | The default constructor. |
| static [debugserver_client_free](DebugServerNativeMethods/debugserver_client_free.md)(…) | Disconnects a debugserver client from the device and frees up the debugserver client data. |
| static [debugserver_client_new](DebugServerNativeMethods/debugserver_client_new.md)(…) | Connects to the debugserver service on the specified device. |
| static [debugserver_client_receive](DebugServerNativeMethods/debugserver_client_receive.md)(…) | Receives raw data from the debugserver service. |
| static [debugserver_client_receive_response](DebugServerNativeMethods/debugserver_client_receive_response.md)(…) | Receives and parses response of debugserver service. (2 methods) |
| static [debugserver_client_receive_with_timeout](DebugServerNativeMethods/debugserver_client_receive_with_timeout.md)(…) | Receives raw data using the given debugserver client with specified timeout. |
| static [debugserver_client_send](DebugServerNativeMethods/debugserver_client_send.md)(…) | Sends raw data using the given debugserver service client. |
| static [debugserver_client_send_command](DebugServerNativeMethods/debugserver_client_send_command.md)(…) | Sends a command to the debugserver service. (2 methods) |
| static [debugserver_client_set_ack_mode](DebugServerNativeMethods/debugserver_client_set_ack_mode.md)(…) | Controls status of ACK mode when sending commands or receiving responses. |
| static [debugserver_client_set_argv](DebugServerNativeMethods/debugserver_client_set_argv.md)(…) | Sets the argv which launches an app. (2 methods) |
| static [debugserver_client_set_environment_hex_encoded](DebugServerNativeMethods/debugserver_client_set_environment_hex_encoded.md)(…) | Adds or sets an environment variable. (2 methods) |
| static [debugserver_client_start_service](DebugServerNativeMethods/debugserver_client_start_service.md)(…) | Starts a new debugserver service on the specified device and connects to it. |
| static [debugserver_command_free](DebugServerNativeMethods/debugserver_command_free.md)(…) | Frees memory of command object. |
| static [debugserver_command_new](DebugServerNativeMethods/debugserver_command_new.md)(…) | Creates and initializes a new command object. (2 methods) |
| static [debugserver_decode_string](DebugServerNativeMethods/debugserver_decode_string.md)(…) | Decodes a hex encoded string. (2 methods) |
| static [debugserver_encode_string](DebugServerNativeMethods/debugserver_encode_string.md)(…) | Encodes a string into hex notation. (2 methods) |

## See Also

* namespace [iMobileDevice.DebugServer](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
