---
title: IiDeviceApi interface
---

```csharp
public interface IiDeviceApi
```

## Members

| name | description |
| --- | --- |
| [Parent](IiDeviceApi/Parent.md) { get; } | Gets or sets the !:ILibiMobileDeviceApi which owns this iDevice. |
| [idevice_connect](IiDeviceApi/idevice_connect.md)(…) | Set up a connection to the given device. |
| [idevice_connection_disable_ssl](IiDeviceApi/idevice_connection_disable_ssl.md)(…) | Disable SSL for the given connection. |
| [idevice_connection_enable_ssl](IiDeviceApi/idevice_connection_enable_ssl.md)(…) | Enables SSL for the given connection. |
| [idevice_connection_get_fd](IiDeviceApi/idevice_connection_get_fd.md)(…) | Get the underlying file descriptor for a connection |
| [idevice_connection_receive](IiDeviceApi/idevice_connection_receive.md)(…) | Receive data from a device via the given connection. This function is like idevice_connection_receive_timeout, but with a predefined reasonable timeout. |
| [idevice_connection_receive_timeout](IiDeviceApi/idevice_connection_receive_timeout.md)(…) | Receive data from a device via the given connection. This function will return after the given timeout even if no data has been received. |
| [idevice_connection_send](IiDeviceApi/idevice_connection_send.md)(…) | Send data to a device via the given connection. |
| [idevice_device_list_free](IiDeviceApi/idevice_device_list_free.md)(…) | Free a list of device udids. |
| [idevice_disconnect](IiDeviceApi/idevice_disconnect.md)(…) | Disconnect from the device and clean up the connection structure. |
| [idevice_event_subscribe](IiDeviceApi/idevice_event_subscribe.md)(…) | Register a callback function that will be called when device add/remove events occur. |
| [idevice_event_unsubscribe](IiDeviceApi/idevice_event_unsubscribe.md)() | Release the event callback function that has been registered with idevice_event_subscribe(). |
| [idevice_free](IiDeviceApi/idevice_free.md)(…) | Cleans up an idevice structure, then frees the structure itself. This is a library-level function; deals directly with the device to tear down relations, but otherwise is mostly internal. |
| [idevice_get_device_list](IiDeviceApi/idevice_get_device_list.md)(…) | Get a list of currently available devices. |
| [idevice_get_handle](IiDeviceApi/idevice_get_handle.md)(…) | Gets the handle or (usbmux device id) of the device. |
| [idevice_get_socket_type](IiDeviceApi/idevice_get_socket_type.md)(…) | Gets the socket type (Unix socket or TCP socket) libimobiledevice should use when connecting to usbmuxd. |
| [idevice_get_tcp_endpoint](IiDeviceApi/idevice_get_tcp_endpoint.md)(…) | Gets the TCP endpoint to which libimobiledevice will connect if the socket type is set to SOCKET_TYPE_TCP |
| [idevice_get_udid](IiDeviceApi/idevice_get_udid.md)(…) | Gets the unique id for the device. |
| [idevice_new](IiDeviceApi/idevice_new.md)(…) | Creates an idevice_t structure for the device specified by udid, if the device is available. |
| [idevice_set_debug_callback](IiDeviceApi/idevice_set_debug_callback.md)(…) | Sets the callback to invoke when writing out debug messages. If this callback is set, messages will be written to this callback instead of the standard output. |
| [idevice_set_debug_level](IiDeviceApi/idevice_set_debug_level.md)(…) | Set the level of debugging. |
| [idevice_set_socket_type](IiDeviceApi/idevice_set_socket_type.md)(…) | Sets the socket type (Unix socket or TCP socket) libimobiledevice should use when connecting to usbmuxd. |
| [idevice_set_tcp_endpoint](IiDeviceApi/idevice_set_tcp_endpoint.md)(…) | Sets the TCP endpoint to which libimobiledevice will connect if the socket type is set to SOCKET_TYPE_TCP |

## See Also

* namespace [iMobileDevice.iDevice](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->