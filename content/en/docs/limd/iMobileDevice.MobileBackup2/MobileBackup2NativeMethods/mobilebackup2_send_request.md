---
title: MobileBackup2NativeMethods.mobilebackup2_send_request method
---

Send a request to the connected mobilebackup2 service.

```csharp
public static MobileBackup2Error mobilebackup2_send_request(MobileBackup2ClientHandle client, 
    string request, string targetIdentifier, string sourceIdentifier, PlistHandle options)
```

| parameter | description |
| --- | --- |
| request | The request to send to the backup service. Currently, this is one of "Backup", "Restore", "Info", or "List". |
| target_identifier | UDID of the target device. |
| source_identifier | UDID of backup data? |
| options | Additional options in a plist of type PLIST_DICT. |

## Return Value

MOBILEBACKUP2_E_SUCCESS if the request was successfully sent, or a MOBILEBACKUP2_E_* error value otherwise.

## See Also

* enum [MobileBackup2Error](../MobileBackup2Error.md)
* class [MobileBackup2ClientHandle](../MobileBackup2ClientHandle.md)
* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* class [MobileBackup2NativeMethods](../MobileBackup2NativeMethods.md)
* namespace [iMobileDevice.MobileBackup2](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->