---
title: AfcNativeMethods.afc_dictionary_free method
---

Frees up a char dictionary as returned by some AFC functions.

```csharp
public static AfcError afc_dictionary_free(IntPtr dictionary)
```

| parameter | description |
| --- | --- |
| dictionary | The char array terminated by an empty string. |

## Return Value

AFC_E_SUCCESS on success or an AFC_E_* error value.

## See Also

* enum [AfcError](../AfcError.md)
* class [AfcNativeMethods](../AfcNativeMethods.md)
* namespace [iMobileDevice.Afc](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
