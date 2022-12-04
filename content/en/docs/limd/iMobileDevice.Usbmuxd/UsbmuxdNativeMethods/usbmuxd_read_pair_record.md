---
title: UsbmuxdNativeMethods.usbmuxd_read_pair_record method (1 of 2)
---

Read a pairing record

```csharp
public static int usbmuxd_read_pair_record(string recordId, out IntPtr recordData, 
    ref uint recordSize)
```

| parameter | description |
| --- | --- |
| record_id | the record identifier of the pairing record to retrieve |
| record_data | pointer to a variable that will be set to point to a newly allocated buffer containing the pairing record data |
| record_size | pointer to a variable that will be set to the size of the buffer returned in record_data |

## Return Value

0 on success, a negative error value otherwise.

## See Also

* class [UsbmuxdNativeMethods](../UsbmuxdNativeMethods.md)
* namespace [iMobileDevice.Usbmuxd](../../iMobileDevice-net.md)

---

---
title: UsbmuxdNativeMethods.usbmuxd_read_pair_record method (2 of 2)
---

```csharp
public static int usbmuxd_read_pair_record(string recordId, out string recordData, 
    ref uint recordSize)
```

## See Also

* class [UsbmuxdNativeMethods](../UsbmuxdNativeMethods.md)
* namespace [iMobileDevice.Usbmuxd](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->