---
title: ScreenshotrApi.screenshotr_client_start_service method
---

Starts a new screenshotr service on the specified device and connects to it.

```csharp
public virtual ScreenshotrError screenshotr_client_start_service(iDeviceHandle device, 
    out ScreenshotrClientHandle client, string label)
```

| parameter | description |
| --- | --- |
| device | The device to connect to. |
| client | Pointer that will point to a newly allocated screenshotr_client_t upon successful return. Must be freed using screenshotr_client_free() after use. |
| label | The label to use for communication. Usually the program name. Pass NULL to disable sending the label in requests to lockdownd. |

## Return Value

SCREENSHOTR_E_SUCCESS on success, or an SCREENSHOTR_E_* error code otherwise.

## See Also

* enum [ScreenshotrError](../ScreenshotrError.md)
* class [iDeviceHandle](../../iMobileDevice.iDevice/iDeviceHandle.md)
* class [ScreenshotrClientHandle](../ScreenshotrClientHandle.md)
* class [ScreenshotrApi](../ScreenshotrApi.md)
* namespace [iMobileDevice.Screenshotr](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
