---
title: PlistApi.plist_dict_next_item method
---

Increment iterator of a #PLIST_DICT node.

```csharp
public virtual void plist_dict_next_item(PlistHandle node, PlistDictIterHandle iter, 
    out string key, out PlistHandle val)
```

| parameter | description |
| --- | --- |
| node | The node of type #PLIST_DICT |
| iter | Iterator of the dictionary |
| key | Location to store the key, or NULL. The caller is responsible for freeing the the returned string. |
| val | Location to store the value, or NULL. The caller must *not* free the returned value. Will be set to NULL when no more key/value pairs are left to iterate. |

## See Also

* class [PlistHandle](../PlistHandle.md)
* class [PlistDictIterHandle](../PlistDictIterHandle.md)
* class [PlistApi](../PlistApi.md)
* namespace [iMobileDevice.Plist](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
