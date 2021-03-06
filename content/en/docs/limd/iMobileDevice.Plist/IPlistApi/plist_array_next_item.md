---
title: IPlistApi.plist_array_next_item method
---

Increment iterator of a #PLIST_ARRAY node.

```csharp
public void plist_array_next_item(PlistHandle node, PlistArrayIterHandle iter, out PlistHandle item)
```

| parameter | description |
| --- | --- |
| node | The node of type #PLIST_ARRAY. |
| iter | Iterator of the array |
| item | Location to store the item. The caller must *not* free the returned item. Will be set to NULL when no more items are left to iterate. |

## See Also

* class [PlistHandle](../PlistHandle.md)
* class [PlistArrayIterHandle](../PlistArrayIterHandle.md)
* interface [IPlistApi](../IPlistApi.md)
* namespace [iMobileDevice.Plist](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
