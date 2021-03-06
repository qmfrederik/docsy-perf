---
title: MobileactivationNativeMethods.mobileactivation_create_activation_session_info method
---

Retrieves a session blob required for 'drmHandshake' via albert.apple.com.

```csharp
public static MobileactivationError mobileactivation_create_activation_session_info(
    MobileactivationClientHandle client, out PlistHandle blob)
```

| parameter | description |
| --- | --- |
| client | The mobileactivation client |
| blob | Pointer to a plist_t variable that will be set to the session blob created by the mobielactivation service. The consumer is responsible for freeing the returned object using plist_free(). |

## Return Value

MOBILEACTIVATION_E_SUCCESS on success, or an MOBILEACTIVATION_E_* error code otherwise.

## See Also

* enum [MobileactivationError](../MobileactivationError.md)
* class [MobileactivationClientHandle](../MobileactivationClientHandle.md)
* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* class [MobileactivationNativeMethods](../MobileactivationNativeMethods.md)
* namespace [iMobileDevice.Mobileactivation](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
