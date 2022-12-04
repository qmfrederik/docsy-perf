---
title: IMobileSyncApi.mobilesync_receive method
---

Polls the device for mobilesync data.

```csharp
public MobileSyncError mobilesync_receive(MobileSyncClientHandle client, out PlistHandle plist)
```

| parameter | description |
| --- | --- |
| client | The mobilesync client |
| plist | A pointer to the location where the plist should be stored |

## Return Value

an error code

## See Also

* enum [MobileSyncError](../MobileSyncError.md)
* class [MobileSyncClientHandle](../MobileSyncClientHandle.md)
* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* interface [IMobileSyncApi](../IMobileSyncApi.md)
* namespace [iMobileDevice.MobileSync](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->