---
title: IMobileSyncApi.mobilesync_ready_to_send_changes_from_computer method
---

Verifies if the device is ready to receive changes from the computer. This call changes the synchronization direction so that mobilesync_send_changes() can be used to send changes to the device. MOBILESYNC_E_SUCCESS on success MOBILESYNC_E_INVALID_ARG if one of the parameters is invalid MOBILESYNC_E_PLIST_ERROR if the received plist is not of valid form MOBILESYNC_E_WRONG_DIRECTION if the current sync direction does not permit this call MOBILESYNC_E_CANCELLED if the device explicitly cancelled the session MOBILESYNC_E_NOT_READY if the device is not ready to start receiving any changes

```csharp
public MobileSyncError mobilesync_ready_to_send_changes_from_computer(MobileSyncClientHandle client)
```

| parameter | description |
| --- | --- |
| client | The mobilesync client |

## See Also

* enum [MobileSyncError](../MobileSyncError.md)
* class [MobileSyncClientHandle](../MobileSyncClientHandle.md)
* interface [IMobileSyncApi](../IMobileSyncApi.md)
* namespace [iMobileDevice.MobileSync](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->