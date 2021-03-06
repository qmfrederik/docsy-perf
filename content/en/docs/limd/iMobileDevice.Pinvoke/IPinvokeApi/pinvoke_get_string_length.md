---
title: IPinvokeApi.pinvoke_get_string_length method
---

Gets the size of a string that was previously allocated by libimobiledevice.

```csharp
public PinvokeError pinvoke_get_string_length(IntPtr @string, out ulong length)
```

| parameter | description |
| --- | --- |
| string | The string of which to get its size. |
| length | The length of the string, in bytes. |

## Return Value

Always returns PINVOKE_E_SUCCESS.

## See Also

* enum [PinvokeError](../PinvokeError.md)
* interface [IPinvokeApi](../IPinvokeApi.md)
* namespace [iMobileDevice.Pinvoke](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
