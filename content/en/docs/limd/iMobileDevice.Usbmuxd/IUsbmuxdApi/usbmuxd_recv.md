---
title: IUsbmuxdApi.usbmuxd_recv method
---

Receive data from the specified socket with a default timeout.

```csharp
public int usbmuxd_recv(int sfd, byte[] data, uint len, ref uint recvBytes)
```

| parameter | description |
| --- | --- |
| sfd | socket file descriptor returned by usbmuxd_connect() |
| data | buffer to put the data to |
| len | number of bytes to receive |
| recv_bytes | number of bytes received |

## Return Value

0 on success, a negative errno value otherwise.

## See Also

* interface [IUsbmuxdApi](../IUsbmuxdApi.md)
* namespace [iMobileDevice.Usbmuxd](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
