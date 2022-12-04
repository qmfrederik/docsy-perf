---
title: IPlistApi.plist_dict_get_item method
---

Get the nth item in a #PLIST_DICT node.

```csharp
public PlistHandle plist_dict_get_item(PlistHandle node, string key)
```

| parameter | description |
| --- | --- |
| node | the node of type #PLIST_DICT |
| key | the identifier of the item to get. |

## Return Value

the item or NULL if node is not of type #PLIST_DICT. The caller should not free the returned node.

## See Also

* class [PlistHandle](../PlistHandle.md)
* interface [IPlistApi](../IPlistApi.md)
* namespace [iMobileDevice.Plist](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->