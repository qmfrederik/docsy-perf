---
title: PlistApi.plist_to_xml method
---

Export the #plist_t structure to XML format.

```csharp
public virtual void plist_to_xml(PlistHandle plist, out string plistXml, ref uint length)
```

| parameter | description |
| --- | --- |
| plist | the root node to export |
| plist_xml | a pointer to a C-string. This function allocates the memory, caller is responsible for freeing it. Data is UTF-8 encoded. |
| length | a pointer to an uint32_t variable. Represents the length of the allocated buffer. |

## See Also

* class [PlistHandle](../PlistHandle.md)
* class [PlistApi](../PlistApi.md)
* namespace [iMobileDevice.Plist](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->