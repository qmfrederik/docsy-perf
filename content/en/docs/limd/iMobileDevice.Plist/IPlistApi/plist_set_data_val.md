---
title: IPlistApi.plist_set_data_val method
---

Set the value of a node. Forces type of node to #PLIST_DATA

```csharp
public void plist_set_data_val(PlistHandle node, string val, ulong length)
```

| parameter | description |
| --- | --- |
| node | the node |
| val | the binary buffer. The buffer is copied when set and will be freed by the node. |
| length | the length of the buffer |

## See Also

* class [PlistHandle](../PlistHandle.md)
* interface [IPlistApi](../IPlistApi.md)
* namespace [iMobileDevice.Plist](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
