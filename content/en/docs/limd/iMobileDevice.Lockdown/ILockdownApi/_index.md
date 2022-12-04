---
title: ILockdownApi interface
---

```csharp
public interface ILockdownApi
```

## Members

| name | description |
| --- | --- |
| [Parent](ILockdownApi/Parent.md) { get; } | Gets or sets the !:ILibiMobileDeviceApi which owns this Lockdown. |
| [lockdownd_activate](ILockdownApi/lockdownd_activate.md)(…) | Activates the device. Only works within an open session. The ActivationRecord plist dictionary must be obtained using the activation protocol requesting from Apple's https webservice. |
| [lockdownd_client_free](ILockdownApi/lockdownd_client_free.md)(…) | Closes the lockdownd client session if one is running and frees up the lockdownd_client struct. |
| [lockdownd_client_new](ILockdownApi/lockdownd_client_new.md)(…) | Creates a new lockdownd client for the device. |
| [lockdownd_client_new_with_handshake](ILockdownApi/lockdownd_client_new_with_handshake.md)(…) | Creates a new lockdownd client for the device and starts initial handshake. The handshake consists out of query_type, validate_pair, pair and start_session calls. It uses the internal pairing record management. |
| [lockdownd_client_set_label](ILockdownApi/lockdownd_client_set_label.md)(…) | Sets the label to send for requests to lockdownd. |
| [lockdownd_data_classes_free](ILockdownApi/lockdownd_data_classes_free.md)(…) | Frees memory of an allocated array of data classes as returned by lockdownd_get_sync_data_classes() |
| [lockdownd_deactivate](ILockdownApi/lockdownd_deactivate.md)(…) | Deactivates the device, returning it to the locked â€œActivate with iTunesâ€ screen. |
| [lockdownd_enter_recovery](ILockdownApi/lockdownd_enter_recovery.md)(…) | Tells the device to immediately enter recovery mode. |
| [lockdownd_get_device_name](ILockdownApi/lockdownd_get_device_name.md)(…) | Retrieves the name of the device from lockdownd set by the user. |
| [lockdownd_get_device_udid](ILockdownApi/lockdownd_get_device_udid.md)(…) | Returns the unique id of the device from lockdownd. |
| [lockdownd_get_sync_data_classes](ILockdownApi/lockdownd_get_sync_data_classes.md)(…) | Calculates and returns the data classes the device supports from lockdownd. |
| [lockdownd_get_value](ILockdownApi/lockdownd_get_value.md)(…) | Retrieves a preferences plist using an optional domain and/or key name. |
| [lockdownd_goodbye](ILockdownApi/lockdownd_goodbye.md)(…) | Sends the Goodbye request to lockdownd signaling the end of communication. |
| [lockdownd_pair](ILockdownApi/lockdownd_pair.md)(…) | Pairs the device using the supplied pair record. |
| [lockdownd_pair_with_options](ILockdownApi/lockdownd_pair_with_options.md)(…) | Pairs the device using the supplied pair record and passing the given options. |
| [lockdownd_query_type](ILockdownApi/lockdownd_query_type.md)(…) | Query the type of the service daemon. Depending on whether the device is queried in normal mode or restore mode, different types will be returned. |
| [lockdownd_receive](ILockdownApi/lockdownd_receive.md)(…) | Receives a plist from lockdownd. |
| [lockdownd_remove_value](ILockdownApi/lockdownd_remove_value.md)(…) | Removes a preference node by domain and/or key name. |
| [lockdownd_send](ILockdownApi/lockdownd_send.md)(…) | Sends a plist to lockdownd. |
| [lockdownd_service_descriptor_free](ILockdownApi/lockdownd_service_descriptor_free.md)(…) | Frees memory of a service descriptor as returned by lockdownd_start_service() |
| [lockdownd_set_value](ILockdownApi/lockdownd_set_value.md)(…) | Sets a preferences value using a plist and optional by domain and/or key name. |
| [lockdownd_start_service](ILockdownApi/lockdownd_start_service.md)(…) | Requests to start a service and retrieve it's port on success. |
| [lockdownd_start_service_with_escrow_bag](ILockdownApi/lockdownd_start_service_with_escrow_bag.md)(…) | Requests to start a service and retrieve it's port on success. Sends the escrow bag from the device's pair record. |
| [lockdownd_start_session](ILockdownApi/lockdownd_start_session.md)(…) | Opens a session with lockdownd and switches to SSL mode if device wants it. |
| [lockdownd_stop_session](ILockdownApi/lockdownd_stop_session.md)(…) | Closes the lockdownd session by sending the StopSession request. |
| [lockdownd_unpair](ILockdownApi/lockdownd_unpair.md)(…) | Unpairs the device with the given HostID and removes the pairing records from the device and host if the internal pairing record management is used. |
| [lockdownd_validate_pair](ILockdownApi/lockdownd_validate_pair.md)(…) | Validates if the device is paired with the given HostID. If successful the specified host will become trusted host of the device indicated by the lockdownd preference named TrustedHostAttached. Otherwise the host must be paired using lockdownd_pair() first. |

## See Also

* namespace [iMobileDevice.Lockdown](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->