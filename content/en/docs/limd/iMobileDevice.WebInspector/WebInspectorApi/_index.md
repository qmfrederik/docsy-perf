---
title: WebInspectorApi class
---

```csharp
public class WebInspectorApi : IWebInspectorApi
```

## Public Members

| name | description |
| --- | --- |
| [WebInspectorApi](WebInspectorApi/WebInspectorApi.md)(…) | Initializes a new instance of the [`WebInspectorApi`](WebInspectorApi.md) class |
| [Parent](WebInspectorApi/Parent.md) { get; } |  |
| virtual [webinspector_client_free](WebInspectorApi/webinspector_client_free.md)(…) | Disconnects a webinspector client from the device and frees up the webinspector client data. |
| virtual [webinspector_client_new](WebInspectorApi/webinspector_client_new.md)(…) | Connects to the webinspector service on the specified device. |
| virtual [webinspector_client_start_service](WebInspectorApi/webinspector_client_start_service.md)(…) | Starts a new webinspector service on the specified device and connects to it. |
| virtual [webinspector_receive](WebInspectorApi/webinspector_receive.md)(…) | Receives a plist from the service. |
| virtual [webinspector_receive_with_timeout](WebInspectorApi/webinspector_receive_with_timeout.md)(…) | Receives a plist using the given webinspector client. |
| virtual [webinspector_send](WebInspectorApi/webinspector_send.md)(…) | Sends a plist to the service. |

## See Also

* interface [IWebInspectorApi](IWebInspectorApi.md)
* namespace [iMobileDevice.WebInspector](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
