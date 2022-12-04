---
title: PropertyListServiceApi class
---

```csharp
public class PropertyListServiceApi : IPropertyListServiceApi
```

## Public Members

| name | description |
| --- | --- |
| [PropertyListServiceApi](PropertyListServiceApi/PropertyListServiceApi.md)(…) | Initializes a new instance of the [`PropertyListServiceApi`](PropertyListServiceApi.md) class |
| [Parent](PropertyListServiceApi/Parent.md) { get; } |  |
| virtual [property_list_service_client_free](PropertyListServiceApi/property_list_service_client_free.md)(…) | Frees a PropertyList service. |
| virtual [property_list_service_client_new](PropertyListServiceApi/property_list_service_client_new.md)(…) | Creates a new property list service for the specified port. |
| virtual [property_list_service_disable_ssl](PropertyListServiceApi/property_list_service_disable_ssl.md)(…) | Disable SSL for the given property list service client. |
| virtual [property_list_service_enable_ssl](PropertyListServiceApi/property_list_service_enable_ssl.md)(…) | Enable SSL for the given property list service client. |
| virtual [property_list_service_receive_plist](PropertyListServiceApi/property_list_service_receive_plist.md)(…) | Receives a plist using the given property list service client. Binary or XML plists are automatically handled. This function is like property_list_service_receive_plist_with_timeout using a timeout of 10 seconds. |
| virtual [property_list_service_receive_plist_with_timeout](PropertyListServiceApi/property_list_service_receive_plist_with_timeout.md)(…) | Receives a plist using the given property list service client with specified timeout. Binary or XML plists are automatically handled. |
| virtual [property_list_service_send_binary_plist](PropertyListServiceApi/property_list_service_send_binary_plist.md)(…) | Sends a binary plist. |
| virtual [property_list_service_send_xml_plist](PropertyListServiceApi/property_list_service_send_xml_plist.md)(…) | Sends an XML plist. |

## See Also

* interface [IPropertyListServiceApi](IPropertyListServiceApi.md)
* namespace [iMobileDevice.PropertyListService](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->