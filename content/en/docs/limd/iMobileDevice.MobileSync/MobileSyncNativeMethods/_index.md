---
title: MobileSyncNativeMethods class
---

```csharp
public class MobileSyncNativeMethods
```

## Public Members

| name | description |
| --- | --- |
| [MobileSyncNativeMethods](MobileSyncNativeMethods/MobileSyncNativeMethods.md)() | The default constructor. |
| static [mobilesync_acknowledge_changes_from_device](MobileSyncNativeMethods/mobilesync_acknowledge_changes_from_device.md)(…) | Acknowledges to the device that the changes have been merged on the computer MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid |
| static [mobilesync_actions_add](MobileSyncNativeMethods/mobilesync_actions_add.md)(…) | Add one or more new key:value pairs to the given actions plist. |
| static [mobilesync_actions_free](MobileSyncNativeMethods/mobilesync_actions_free.md)(…) | Free actions plist. |
| static [mobilesync_actions_new](MobileSyncNativeMethods/mobilesync_actions_new.md)() | Create a new actions plist to use in mobilesync_send_changes(). |
| static [mobilesync_anchors_free](MobileSyncNativeMethods/mobilesync_anchors_free.md)(…) | Free memory used by anchors. MOBILESYNC_E_SUCCESS on success |
| static [mobilesync_anchors_new](MobileSyncNativeMethods/mobilesync_anchors_new.md)(…) | Allocates memory for a new anchors struct initialized with the passed anchors. MOBILESYNC_E_SUCCESS on success |
| static [mobilesync_cancel](MobileSyncNativeMethods/mobilesync_cancel.md)(…) | Cancels a running synchronization session with a device at any time. MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid |
| static [mobilesync_clear_all_records_on_device](MobileSyncNativeMethods/mobilesync_clear_all_records_on_device.md)(…) | Requests the device to delete all records of the current data class MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid MOBILESYNC_E_PLIST_ERROR if the received plist is not of valid form |
| static [mobilesync_client_free](MobileSyncNativeMethods/mobilesync_client_free.md)(…) | Disconnects a mobilesync client from the device and frees up the mobilesync client data. MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if is NULL. |
| static [mobilesync_client_new](MobileSyncNativeMethods/mobilesync_client_new.md)(…) | Connects to the mobilesync service on the specified device. MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one or more parameters are invalid DEVICE_LINK_SERVICE_E_BAD_VERSION if the mobilesync version on the device is newer. |
| static [mobilesync_client_start_service](MobileSyncNativeMethods/mobilesync_client_start_service.md)(…) | Starts a new mobilesync service on the specified device and connects to it. |
| static [mobilesync_finish](MobileSyncNativeMethods/mobilesync_finish.md)(…) | Finish a synchronization session of a data class on the device. A session must have previously been started using mobilesync_start(). MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid MOBILESYNC_E_PLIST_ERROR if the received plist is not of valid form |
| static [mobilesync_get_all_records_from_device](MobileSyncNativeMethods/mobilesync_get_all_records_from_device.md)(…) | Requests to receive all records of the currently set data class from the device. The actually changes are retrieved using mobilesync_receive_changes() after this request has been successful. MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid |
| static [mobilesync_get_changes_from_device](MobileSyncNativeMethods/mobilesync_get_changes_from_device.md)(…) | Requests to receive only changed records of the currently set data class from the device. The actually changes are retrieved using mobilesync_receive_changes() after this request has been successful. MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid |
| static [mobilesync_ready_to_send_changes_from_computer](MobileSyncNativeMethods/mobilesync_ready_to_send_changes_from_computer.md)(…) | Verifies if the device is ready to receive changes from the computer. This call changes the synchronization direction so that mobilesync_send_changes() can be used to send changes to the device. MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid MOBILESYNC_E_PLIST_ERROR if the received plist is not of valid form MOBILESYNC_E_WRONG_DIRECTION if the current sync direction does not permit this call MOBILESYNC_E_CANCELLED if the device explicitly cancelled the session MOBILESYNC_E_NOT_READY if the device is not ready to start receiving any changes |
| static [mobilesync_receive](MobileSyncNativeMethods/mobilesync_receive.md)(…) | Polls the device for mobilesync data. |
| static [mobilesync_receive_changes](MobileSyncNativeMethods/mobilesync_receive_changes.md)(…) | Receives changed entitites of the currently set data class from the device MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid MOBILESYNC_E_CANCELLED if the device explicitly cancelled the session |
| static [mobilesync_remap_identifiers](MobileSyncNativeMethods/mobilesync_remap_identifiers.md)(…) | Receives any remapped identifiers reported after the device merged submitted changes. MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid MOBILESYNC_E_PLIST_ERROR if the received plist is not of valid form MOBILESYNC_E_WRONG_DIRECTION if the current sync direction does not permit this call MOBILESYNC_E_CANCELLED if the device explicitly cancelled the session |
| static [mobilesync_send](MobileSyncNativeMethods/mobilesync_send.md)(…) | Sends mobilesync data to the device |
| static [mobilesync_send_changes](MobileSyncNativeMethods/mobilesync_send_changes.md)(…) | Sends changed entities of the currently set data class to the device MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid, MOBILESYNC_E_WRONG_DIRECTION if the current sync direction does not permit this call |
| static [mobilesync_start](MobileSyncNativeMethods/mobilesync_start.md)(…) | Requests starting synchronization of a data class with the device MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid MOBILESYNC_E_PLIST_ERROR if the received plist is not of valid form MOBILESYNC_E_SYNC_REFUSED if the device refused to sync MOBILESYNC_E_CANCELLED if the device explicitly cancelled the sync request (2 methods) |

## See Also

* namespace [iMobileDevice.MobileSync](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
