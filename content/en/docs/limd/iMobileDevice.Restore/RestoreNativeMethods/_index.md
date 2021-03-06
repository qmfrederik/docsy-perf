---
title: RestoreNativeMethods class
---

```csharp
public class RestoreNativeMethods
```

## Public Members

| name | description |
| --- | --- |
| [RestoreNativeMethods](RestoreNativeMethods/RestoreNativeMethods.md)() | The default constructor. |
| static [restored_client_free](RestoreNativeMethods/restored_client_free.md)(…) | Closes the restored client session if one is running and frees up the restored_client struct. |
| static [restored_client_new](RestoreNativeMethods/restored_client_new.md)(…) | Creates a new restored client for the device. |
| static [restored_client_set_label](RestoreNativeMethods/restored_client_set_label.md)(…) | Sets the label to send for requests to restored. |
| static [restored_get_value](RestoreNativeMethods/restored_get_value.md)(…) | Retrieves a value from information plist specified by a key. |
| static [restored_goodbye](RestoreNativeMethods/restored_goodbye.md)(…) | Sends the Goodbye request to restored signaling the end of communication. |
| static [restored_query_type](RestoreNativeMethods/restored_query_type.md)(…) | Query the type of the service daemon. Depending on whether the device is queried in normal mode or restore mode, different types will be returned. (2 methods) |
| static [restored_query_value](RestoreNativeMethods/restored_query_value.md)(…) | Queries a value from the device specified by a key. |
| static [restored_reboot](RestoreNativeMethods/restored_reboot.md)(…) | Requests device to reboot. |
| static [restored_receive](RestoreNativeMethods/restored_receive.md)(…) | Receives a plist from restored. |
| static [restored_send](RestoreNativeMethods/restored_send.md)(…) | Sends a plist to restored. |
| static [restored_start_restore](RestoreNativeMethods/restored_start_restore.md)(…) | Requests to start a restore and retrieve it's port on success. |

## See Also

* namespace [iMobileDevice.Restore](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
