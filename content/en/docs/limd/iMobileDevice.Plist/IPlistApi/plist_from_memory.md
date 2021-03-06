---
title: IPlistApi.plist_from_memory method
---

Import the #plist_t structure from memory data. This method will look at the first bytes of plist_data to determine if plist_data contains a binary or XML plist.

```csharp
public void plist_from_memory(string plistData, uint length, out PlistHandle plist)
```

| parameter | description |
| --- | --- |
| plist_data | a pointer to the memory buffer containing plist data. |
| length | length of the buffer to read. |
| plist | a pointer to the imported plist. |

## See Also

* class [PlistHandle](../PlistHandle.md)
* interface [IPlistApi](../IPlistApi.md)
* namespace [iMobileDevice.Plist](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
