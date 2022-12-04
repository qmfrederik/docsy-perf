---
title: IAfcApi.afc_make_link method
---

Creates a hard link or symbolic link on the device.

```csharp
public AfcError afc_make_link(AfcClientHandle client, AfcLinkType linktype, string target, 
    string linkname)
```

| parameter | description |
| --- | --- |
| client | The client to use for making a link |
| linktype | 1 = hard link, 2 = symlink |
| target | The file to be linked. |
| linkname | The name of link. |

## Return Value

AFC_E_SUCCESS on success or an AFC_E_* error value.

## See Also

* enum [AfcError](../AfcError.md)
* class [AfcClientHandle](../AfcClientHandle.md)
* enum [AfcLinkType](../AfcLinkType.md)
* interface [IAfcApi](../IAfcApi.md)
* namespace [iMobileDevice.Afc](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->