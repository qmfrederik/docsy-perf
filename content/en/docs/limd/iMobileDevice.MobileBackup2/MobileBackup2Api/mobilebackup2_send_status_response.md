---
title: MobileBackup2Api.mobilebackup2_send_status_response method
---

Sends a DLMessageStatusResponse to the device.

```csharp
public virtual MobileBackup2Error mobilebackup2_send_status_response(
    MobileBackup2ClientHandle client, int statusCode, string status1, PlistHandle status2)
```

| parameter | description |
| --- | --- |
| client | The MobileBackup client to use. |
| status_code | The status code to send. |
| status1 | A status message to send. Can be NULL if not required. |
| status2 | An additional status plist to attach to the response. Can be NULL if not required. |

## Return Value

MOBILEBACKUP2_E_SUCCESS on success, MOBILEBACKUP2_E_INVALID_ARG if client is invalid, or another MOBILEBACKUP2_E_* otherwise.

## See Also

* enum [MobileBackup2Error](../MobileBackup2Error.md)
* class [MobileBackup2ClientHandle](../MobileBackup2ClientHandle.md)
* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* class [MobileBackup2Api](../MobileBackup2Api.md)
* namespace [iMobileDevice.MobileBackup2](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
