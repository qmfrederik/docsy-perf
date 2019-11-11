---
title: LockdownNativeMethods class
---

```csharp
public class LockdownNativeMethods
```

## Public Members

| name | description |
| --- | --- |
| [LockdownNativeMethods](LockdownNativeMethods/LockdownNativeMethods.md)() | The default constructor. |
| static [lockdownd_activate](LockdownNativeMethods/lockdownd_activate.md)(…) | Activates the device. Only works within an open session. The ActivationRecord plist dictionary must be obtained using the activation protocol requesting from Apple's https webservice. |
| static [lockdownd_client_free](LockdownNativeMethods/lockdownd_client_free.md)(…) | Closes the lockdownd client session if one is running and frees up the lockdownd_client struct. |
| static [lockdownd_client_new](LockdownNativeMethods/lockdownd_client_new.md)(…) | Creates a new lockdownd client for the device. |
| static [lockdownd_client_new_with_handshake](LockdownNativeMethods/lockdownd_client_new_with_handshake.md)(…) | Creates a new lockdownd client for the device and starts initial handshake. The handshake consists out of query_type, validate_pair, pair and start_session calls. It uses the internal pairing record management. |
| static [lockdownd_client_set_label](LockdownNativeMethods/lockdownd_client_set_label.md)(…) | Sets the label to send for requests to lockdownd. |
| static [lockdownd_data_classes_free](LockdownNativeMethods/lockdownd_data_classes_free.md)(…) | Frees memory of an allocated array of data classes as returned by lockdownd_get_sync_data_classes() |
| static [lockdownd_deactivate](LockdownNativeMethods/lockdownd_deactivate.md)(…) | Deactivates the device, returning it to the locked â€œActivate with iTunesâ€ screen. |
| static [lockdownd_enter_recovery](LockdownNativeMethods/lockdownd_enter_recovery.md)(…) | Tells the device to immediately enter recovery mode. |
| static [lockdownd_get_device_name](LockdownNativeMethods/lockdownd_get_device_name.md)(…) | Retrieves the name of the device from lockdownd set by the user. (2 methods) |
| static [lockdownd_get_device_udid](LockdownNativeMethods/lockdownd_get_device_udid.md)(…) | Returns the unique id of the device from lockdownd. (2 methods) |
| static [lockdownd_get_sync_data_classes](LockdownNativeMethods/lockdownd_get_sync_data_classes.md)(…) |  (2 methods) |
| static [lockdownd_get_value](LockdownNativeMethods/lockdownd_get_value.md)(…) | Retrieves a preferences plist using an optional domain and/or key name. |
| static [lockdownd_goodbye](LockdownNativeMethods/lockdownd_goodbye.md)(…) | Sends the Goodbye request to lockdownd signaling the end of communication. |
| static [lockdownd_pair](LockdownNativeMethods/lockdownd_pair.md)(…) | Pairs the device using the supplied pair record. |
| static [lockdownd_pair_with_options](LockdownNativeMethods/lockdownd_pair_with_options.md)(…) | Pairs the device using the supplied pair record and passing the given options. |
| static [lockdownd_query_type](LockdownNativeMethods/lockdownd_query_type.md)(…) | Query the type of the service daemon. Depending on whether the device is queried in normal mode or restore mode, different types will be returned. (2 methods) |
| static [lockdownd_receive](LockdownNativeMethods/lockdownd_receive.md)(…) | Receives a plist from lockdownd. |
| static [lockdownd_remove_value](LockdownNativeMethods/lockdownd_remove_value.md)(…) | Removes a preference node by domain and/or key name. |
| static [lockdownd_send](LockdownNativeMethods/lockdownd_send.md)(…) | Sends a plist to lockdownd. |
| static [lockdownd_service_descriptor_free](LockdownNativeMethods/lockdownd_service_descriptor_free.md)(…) | Frees memory of a service descriptor as returned by lockdownd_start_service() |
| static [lockdownd_set_value](LockdownNativeMethods/lockdownd_set_value.md)(…) | Sets a preferences value using a plist and optional by domain and/or key name. |
| static [lockdownd_start_service](LockdownNativeMethods/lockdownd_start_service.md)(…) | Requests to start a service and retrieve it's port on success. |
| static [lockdownd_start_service_with_escrow_bag](LockdownNativeMethods/lockdownd_start_service_with_escrow_bag.md)(…) | Requests to start a service and retrieve it's port on success. Sends the escrow bag from the device's pair record. |
| static [lockdownd_start_session](LockdownNativeMethods/lockdownd_start_session.md)(…) | Opens a session with lockdownd and switches to SSL mode if device wants it. (2 methods) |
| static [lockdownd_stop_session](LockdownNativeMethods/lockdownd_stop_session.md)(…) | Closes the lockdownd session by sending the StopSession request. |
| static [lockdownd_unpair](LockdownNativeMethods/lockdownd_unpair.md)(…) | Unpairs the device with the given HostID and removes the pairing records from the device and host if the internal pairing record management is used. |
| static [lockdownd_validate_pair](LockdownNativeMethods/lockdownd_validate_pair.md)(…) | Validates if the device is paired with the given HostID. If successful the specified host will become trusted host of the device indicated by the lockdownd preference named TrustedHostAttached. Otherwise the host must be paired using lockdownd_pair() first. |

## See Also

* namespace [iMobileDevice.Lockdown](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
