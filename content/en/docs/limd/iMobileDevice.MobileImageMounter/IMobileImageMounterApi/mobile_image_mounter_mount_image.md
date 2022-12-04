---
title: IMobileImageMounterApi.mobile_image_mounter_mount_image method
---

Mounts an image on the device.

```csharp
public MobileImageMounterError mobile_image_mounter_mount_image(
    MobileImageMounterClientHandle client, string imagePath, byte[] signature, 
    ushort signatureSize, string imageType, out PlistHandle result)
```

| parameter | description |
| --- | --- |
| client | The connected mobile_image_mounter client. |
| image_path | The absolute path of the image to mount. The image must be present before calling this function. |
| signature | Pointer to a buffer holding the images' signature |
| signature_size | Length of the signature image_signature points to |
| image_type | Type of image to mount |
| result | Pointer to a plist that will receive the result of the operation. |

## Return Value

MOBILE_IMAGE_MOUNTER_E_SUCCESS on success, MOBILE_IMAGE_MOUNTER_E_INVALID_ARG if on ore more parameters are invalid, or another error code otherwise.

## Remarks

This function may return MOBILE_IMAGE_MOUNTER_E_SUCCESS even if the operation has failed. Check the resulting plist for further information. Note that there is no unmounting function. The mount persists until the device is rebooted.

## See Also

* enum [MobileImageMounterError](../MobileImageMounterError.md)
* class [MobileImageMounterClientHandle](../MobileImageMounterClientHandle.md)
* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* interface [IMobileImageMounterApi](../IMobileImageMounterApi.md)
* namespace [iMobileDevice.MobileImageMounter](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->