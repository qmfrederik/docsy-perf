---
title: UsbmuxdApi.usbmuxd_read_buid method
---

Reads the SystemBUID

```csharp
public virtual int usbmuxd_read_buid(out string buid)
```

| parameter | description |
| --- | --- |
| buid | pointer to a variable that will be set to point to a newly allocated string with the System BUID returned by usbmuxd |

## Return Value

0 on success, a negative errno value otherwise.

## See Also

* class [UsbmuxdApi](../UsbmuxdApi.md)
* namespace [iMobileDevice.Usbmuxd](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
