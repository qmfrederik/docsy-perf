---
title: IPlistApi.plist_access_path method
---

Get a node from its path. Each path element depends on the associated father node type. For Dictionaries, var args are casted to const char*, for arrays, var args are caster to uint32_t Search is breath first order.

```csharp
public PlistHandle plist_access_path(PlistHandle plist, uint length)
```

| parameter | description |
| --- | --- |
| plist | the node to access result from. |
| length | length of the path to access |

## Return Value

the value to access.

## See Also

* class [PlistHandle](../PlistHandle.md)
* interface [IPlistApi](../IPlistApi.md)
* namespace [iMobileDevice.Plist](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->