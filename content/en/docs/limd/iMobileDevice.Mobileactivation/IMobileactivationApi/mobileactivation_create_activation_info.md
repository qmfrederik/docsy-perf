---
title: IMobileactivationApi.mobileactivation_create_activation_info method
---

Retrieves the activation info required for device activation.

```csharp
public MobileactivationError mobileactivation_create_activation_info(
    MobileactivationClientHandle client, out PlistHandle info)
```

| parameter | description |
| --- | --- |
| client | The mobileactivation client |
| info | Pointer to a plist_t variable that will be set to the activation info created by the mobileactivation service. The consumer is responsible for freeing the returned object using plist_free(). |

## Return Value

MOBILEACTIVATION_E_SUCCESS on success, or an MOBILEACTIVATION_E_* error code otherwise.

## See Also

* enum [MobileactivationError](../MobileactivationError.md)
* class [MobileactivationClientHandle](../MobileactivationClientHandle.md)
* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* interface [IMobileactivationApi](../IMobileactivationApi.md)
* namespace [iMobileDevice.Mobileactivation](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->