---
title: IMobileImageMounterApi interface
---

```csharp
public interface IMobileImageMounterApi
```

## Members

| name | description |
| --- | --- |
| [Parent](IMobileImageMounterApi/Parent.md) { get; } | Gets or sets the !:ILibiMobileDeviceApi which owns this MobileImageMounter. |
| [mobile_image_mounter_free](IMobileImageMounterApi/mobile_image_mounter_free.md)(…) | Disconnects a mobile_image_mounter client from the device and frees up the mobile_image_mounter client data. |
| [mobile_image_mounter_hangup](IMobileImageMounterApi/mobile_image_mounter_hangup.md)(…) | Hangs up the connection to the mobile_image_mounter service. This functions has to be called before freeing up a mobile_image_mounter instance. If not, errors appear in the device's syslog. |
| [mobile_image_mounter_lookup_image](IMobileImageMounterApi/mobile_image_mounter_lookup_image.md)(…) | Tells if the image of ImageType is already mounted. |
| [mobile_image_mounter_mount_image](IMobileImageMounterApi/mobile_image_mounter_mount_image.md)(…) | Mounts an image on the device. |
| [mobile_image_mounter_new](IMobileImageMounterApi/mobile_image_mounter_new.md)(…) | Connects to the mobile_image_mounter service on the specified device. |
| [mobile_image_mounter_start_service](IMobileImageMounterApi/mobile_image_mounter_start_service.md)(…) | Starts a new mobile_image_mounter service on the specified device and connects to it. |
| [mobile_image_mounter_upload_image](IMobileImageMounterApi/mobile_image_mounter_upload_image.md)(…) | Uploads an image with an optional signature to the device. |

## See Also

* namespace [iMobileDevice.MobileImageMounter](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
