---
title: IPlistApi.plist_array_new_iter method
---

Create an iterator of a #PLIST_ARRAY node. The allocated iterator should be freed with the standard free function.

```csharp
public void plist_array_new_iter(PlistHandle node, out PlistArrayIterHandle iter)
```

| parameter | description |
| --- | --- |
| node | The node of type #PLIST_ARRAY |
| iter | Location to store the iterator for the array. |

## See Also

* class [PlistHandle](../PlistHandle.md)
* class [PlistArrayIterHandle](../PlistArrayIterHandle.md)
* interface [IPlistApi](../IPlistApi.md)
* namespace [iMobileDevice.Plist](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->