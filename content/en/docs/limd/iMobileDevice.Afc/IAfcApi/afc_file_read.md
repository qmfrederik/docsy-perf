---
title: IAfcApi.afc_file_read method
---

Attempts to the read the given number of bytes from the given file.

```csharp
public AfcError afc_file_read(AfcClientHandle client, ulong handle, byte[] data, uint length, 
    ref uint bytesRead)
```

| parameter | description |
| --- | --- |
| client | The relevant AFC client |
| handle | File handle of a previously opened file |
| data | The pointer to the memory region to store the read data |
| length | The number of bytes to read |
| bytes_read | The number of bytes actually read. |

## Return Value

AFC_E_SUCCESS on success or an AFC_E_* error value.

## See Also

* enum [AfcError](../AfcError.md)
* class [AfcClientHandle](../AfcClientHandle.md)
* interface [IAfcApi](../IAfcApi.md)
* namespace [iMobileDevice.Afc](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
