---
title: SyslogRelayNativeMethods.syslog_relay_start_capture method
---

Starts capturing the syslog of the device using a callback. Use syslog_relay_stop_capture() to stop receiving the syslog.

```csharp
public static SyslogRelayError syslog_relay_start_capture(SyslogRelayClientHandle client, 
    SyslogRelayReceiveCallBack callback, IntPtr userData)
```

| parameter | description |
| --- | --- |
| client | The syslog_relay client to use |
| callback | Callback to receive each character from the syslog. |
| user_data | Custom pointer passed to the callback function. |

## Return Value

SYSLOG_RELAY_E_SUCCESS on success, SYSLOG_RELAY_E_INVALID_ARG when one or more parameters are invalid or SYSLOG_RELAY_E_UNKNOWN_ERROR when an unspecified error occurs or a syslog capture has already been started.

## See Also

* enum [SyslogRelayError](../SyslogRelayError.md)
* class [SyslogRelayClientHandle](../SyslogRelayClientHandle.md)
* delegate [SyslogRelayReceiveCallBack](../SyslogRelayReceiveCallBack.md)
* class [SyslogRelayNativeMethods](../SyslogRelayNativeMethods.md)
* namespace [iMobileDevice.SyslogRelay](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->