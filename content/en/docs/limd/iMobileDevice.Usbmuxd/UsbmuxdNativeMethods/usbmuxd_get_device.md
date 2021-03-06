---
title: UsbmuxdNativeMethods.usbmuxd_get_device method
---

Looks up the device specified by UDID with given options and returns device information.

```csharp
public static int usbmuxd_get_device(string udid, ref UsbmuxdDeviceInfo device, int options)
```

| parameter | description |
| --- | --- |
| udid | A device UDID of the device to look for. If udid is NULL, this function will return the first device found. |
| device | Pointer to a previously allocated (or static) usbmuxd_device_info_t that will be filled with the device info. |
| options | Specifying what device connection types should be considered during lookup. Accepts bitwise or'ed values of usbmux_lookup_options. If 0 (no option) is specified it will default to DEVICE_LOOKUP_USBMUX. To lookup both USB and network-connected devices, pass DEVICE_LOOKUP_USBMUX &#x7C; DEVICE_LOOKUP_NETWORK. If a device is available both via USBMUX *and* network, it will select the USB connection. This behavior can be changed by adding DEVICE_LOOKUP_PREFER_NETWORK to the options in which case it will select the network connection. |

## Return Value

0 if no matching device is connected, 1 if the device was found, or a negative value on error.

## See Also

* struct [UsbmuxdDeviceInfo](../UsbmuxdDeviceInfo.md)
* class [UsbmuxdNativeMethods](../UsbmuxdNativeMethods.md)
* namespace [iMobileDevice.Usbmuxd](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
