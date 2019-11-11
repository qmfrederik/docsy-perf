---
title: LockdownApi class
---

```csharp
public class LockdownApi : ILockdownApi
```

## Public Members

| name | description |
| --- | --- |
| [LockdownApi](LockdownApi/LockdownApi.md)(…) | Initializes a new instance of the [`LockdownApi`](LockdownApi.md) class |
| [Parent](LockdownApi/Parent.md) { get; } |  |
| virtual [lockdownd_activate](LockdownApi/lockdownd_activate.md)(…) | Activates the device. Only works within an open session. The ActivationRecord plist dictionary must be obtained using the activation protocol requesting from Apple's https webservice. |
| virtual [lockdownd_client_free](LockdownApi/lockdownd_client_free.md)(…) | Closes the lockdownd client session if one is running and frees up the lockdownd_client struct. |
| virtual [lockdownd_client_new](LockdownApi/lockdownd_client_new.md)(…) | Creates a new lockdownd client for the device. |
| virtual [lockdownd_client_new_with_handshake](LockdownApi/lockdownd_client_new_with_handshake.md)(…) | Creates a new lockdownd client for the device and starts initial handshake. The handshake consists out of query_type, validate_pair, pair and start_session calls. It uses the internal pairing record management. |
| virtual [lockdownd_client_set_label](LockdownApi/lockdownd_client_set_label.md)(…) | Sets the label to send for requests to lockdownd. |
| virtual [lockdownd_data_classes_free](LockdownApi/lockdownd_data_classes_free.md)(…) | Frees memory of an allocated array of data classes as returned by lockdownd_get_sync_data_classes() |
| virtual [lockdownd_deactivate](LockdownApi/lockdownd_deactivate.md)(…) | Deactivates the device, returning it to the locked â€œActivate with iTunesâ€ screen. |
| virtual [lockdownd_enter_recovery](LockdownApi/lockdownd_enter_recovery.md)(…) | Tells the device to immediately enter recovery mode. |
| virtual [lockdownd_get_device_name](LockdownApi/lockdownd_get_device_name.md)(…) | Retrieves the name of the device from lockdownd set by the user. |
| virtual [lockdownd_get_device_udid](LockdownApi/lockdownd_get_device_udid.md)(…) | Returns the unique id of the device from lockdownd. |
| virtual [lockdownd_get_sync_data_classes](LockdownApi/lockdownd_get_sync_data_classes.md)(…) | Calculates and returns the data classes the device supports from lockdownd. |
| virtual [lockdownd_get_value](LockdownApi/lockdownd_get_value.md)(…) | Retrieves a preferences plist using an optional domain and/or key name. |
| virtual [lockdownd_goodbye](LockdownApi/lockdownd_goodbye.md)(…) | Sends the Goodbye request to lockdownd signaling the end of communication. |
| virtual [lockdownd_pair](LockdownApi/lockdownd_pair.md)(…) | Pairs the device using the supplied pair record. |
| virtual [lockdownd_pair_with_options](LockdownApi/lockdownd_pair_with_options.md)(…) | Pairs the device using the supplied pair record and passing the given options. |
| virtual [lockdownd_query_type](LockdownApi/lockdownd_query_type.md)(…) | Query the type of the service daemon. Depending on whether the device is queried in normal mode or restore mode, different types will be returned. |
| virtual [lockdownd_receive](LockdownApi/lockdownd_receive.md)(…) | Receives a plist from lockdownd. |
| virtual [lockdownd_remove_value](LockdownApi/lockdownd_remove_value.md)(…) | Removes a preference node by domain and/or key name. |
| virtual [lockdownd_send](LockdownApi/lockdownd_send.md)(…) | Sends a plist to lockdownd. |
| virtual [lockdownd_service_descriptor_free](LockdownApi/lockdownd_service_descriptor_free.md)(…) | Frees memory of a service descriptor as returned by lockdownd_start_service() |
| virtual [lockdownd_set_value](LockdownApi/lockdownd_set_value.md)(…) | Sets a preferences value using a plist and optional by domain and/or key name. |
| virtual [lockdownd_start_service](LockdownApi/lockdownd_start_service.md)(…) | Requests to start a service and retrieve it's port on success. |
| virtual [lockdownd_start_service_with_escrow_bag](LockdownApi/lockdownd_start_service_with_escrow_bag.md)(…) | Requests to start a service and retrieve it's port on success. Sends the escrow bag from the device's pair record. |
| virtual [lockdownd_start_session](LockdownApi/lockdownd_start_session.md)(…) | Opens a session with lockdownd and switches to SSL mode if device wants it. |
| virtual [lockdownd_stop_session](LockdownApi/lockdownd_stop_session.md)(…) | Closes the lockdownd session by sending the StopSession request. |
| virtual [lockdownd_unpair](LockdownApi/lockdownd_unpair.md)(…) | Unpairs the device with the given HostID and removes the pairing records from the device and host if the internal pairing record management is used. |
| virtual [lockdownd_validate_pair](LockdownApi/lockdownd_validate_pair.md)(…) | Validates if the device is paired with the given HostID. If successful the specified host will become trusted host of the device indicated by the lockdownd preference named TrustedHostAttached. Otherwise the host must be paired using lockdownd_pair() first. |

## See Also

* interface [ILockdownApi](ILockdownApi.md)
* namespace [iMobileDevice.Lockdown](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
