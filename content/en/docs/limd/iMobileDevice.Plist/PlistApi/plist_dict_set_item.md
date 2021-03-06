---
title: PlistApi.plist_dict_set_item method
---

Set item identified by key in a #PLIST_DICT node. The previous item identified by key will be freed using #plist_free. If there is no item for the given key a new item will be inserted.

```csharp
public virtual void plist_dict_set_item(PlistHandle node, string key, PlistHandle item)
```

| parameter | description |
| --- | --- |
| node | the node of type #PLIST_DICT |
| item | the new item associated to key |
| key | the identifier of the item to set. |

## See Also

* class [PlistHandle](../PlistHandle.md)
* class [PlistApi](../PlistApi.md)
* namespace [iMobileDevice.Plist](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
