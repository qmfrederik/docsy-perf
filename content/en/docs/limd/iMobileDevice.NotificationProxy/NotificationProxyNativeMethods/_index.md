---
title: NotificationProxyNativeMethods class
---

```csharp
public class NotificationProxyNativeMethods
```

## Public Members

| name | description |
| --- | --- |
| [NotificationProxyNativeMethods](NotificationProxyNativeMethods/NotificationProxyNativeMethods.md)() | The default constructor. |
| static [np_client_free](NotificationProxyNativeMethods/np_client_free.md)(…) | Disconnects a notification_proxy client from the device and frees up the notification_proxy client data. |
| static [np_client_new](NotificationProxyNativeMethods/np_client_new.md)(…) | Connects to the notification_proxy on the specified device. |
| static [np_client_start_service](NotificationProxyNativeMethods/np_client_start_service.md)(…) | Starts a new notification proxy service on the specified device and connects to it. |
| static [np_observe_notification](NotificationProxyNativeMethods/np_observe_notification.md)(…) | Tells the device to send a notification on the specified event. |
| static [np_observe_notifications](NotificationProxyNativeMethods/np_observe_notifications.md)(…) | Tells the device to send a notification on specified events. (2 methods) |
| static [np_post_notification](NotificationProxyNativeMethods/np_post_notification.md)(…) | Sends a notification to the device's notification_proxy. |
| static [np_set_notify_callback](NotificationProxyNativeMethods/np_set_notify_callback.md)(…) | This function allows an application to define a callback function that will be called when a notification has been received. It will start a thread that polls for notifications and calls the callback function if a notification has been received. In case of an error condition when polling for notifications - e.g. device disconnect - the thread will call the callback function with an empty notification "" and terminate itself. |

## See Also

* namespace [iMobileDevice.NotificationProxy](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->