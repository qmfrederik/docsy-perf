---
title: InstallationProxyApi class
---

```csharp
public class InstallationProxyApi : IInstallationProxyApi
```

## Public Members

| name | description |
| --- | --- |
| [InstallationProxyApi](InstallationProxyApi/InstallationProxyApi.md)(…) | Initializes a new instance of the [`InstallationProxyApi`](InstallationProxyApi.md) class |
| [Parent](InstallationProxyApi/Parent.md) { get; } |  |
| virtual [instproxy_archive](InstallationProxyApi/instproxy_archive.md)(…) | Archive an application on the device. This function tells the device to make an archive of the specified application. This results in the device creating a ZIP archive in the 'ApplicationArchives' directory and uninstalling the application. |
| virtual [instproxy_browse](InstallationProxyApi/instproxy_browse.md)(…) | List installed applications. This function runs synchronously. |
| virtual [instproxy_browse_with_callback](InstallationProxyApi/instproxy_browse_with_callback.md)(…) | List pages of installed applications in a callback. |
| virtual [instproxy_check_capabilities_match](InstallationProxyApi/instproxy_check_capabilities_match.md)(…) | Checks a device for certain capabilities. |
| virtual [instproxy_client_free](InstallationProxyApi/instproxy_client_free.md)(…) | Disconnects an installation_proxy client from the device and frees up the installation_proxy client data. |
| virtual [instproxy_client_get_path_for_bundle_identifier](InstallationProxyApi/instproxy_client_get_path_for_bundle_identifier.md)(…) | Queries the device for the path of an application. |
| virtual [instproxy_client_new](InstallationProxyApi/instproxy_client_new.md)(…) | Connects to the installation_proxy service on the specified device. |
| virtual [instproxy_client_options_add](InstallationProxyApi/instproxy_client_options_add.md)(…) | Adds one or more new key:value pairs to the given client_options. |
| [instproxy_client_options_add](InstallationProxyApi/instproxy_client_options_add.md)(…) |  |
| virtual [instproxy_client_options_free](InstallationProxyApi/instproxy_client_options_free.md)(…) | Frees client_options plist. |
| virtual [instproxy_client_options_new](InstallationProxyApi/instproxy_client_options_new.md)() | Creates a new client_options plist. |
| virtual [instproxy_client_options_set_return_attributes](InstallationProxyApi/instproxy_client_options_set_return_attributes.md)(…) | Adds attributes to the given client_options to filter browse results. |
| virtual [instproxy_client_start_service](InstallationProxyApi/instproxy_client_start_service.md)(…) | Starts a new installation_proxy service on the specified device and connects to it. |
| virtual [instproxy_command_get_name](InstallationProxyApi/instproxy_command_get_name.md)(…) | Gets the name from a command dictionary. |
| virtual [instproxy_install](InstallationProxyApi/instproxy_install.md)(…) | Install an application on the device. |
| virtual [instproxy_lookup](InstallationProxyApi/instproxy_lookup.md)(…) | Lookup information about specific applications from the device. |
| virtual [instproxy_lookup_archives](InstallationProxyApi/instproxy_lookup_archives.md)(…) | List archived applications. This function runs synchronously. |
| virtual [instproxy_remove_archive](InstallationProxyApi/instproxy_remove_archive.md)(…) | Removes a previously archived application from the device. This function removes the ZIP archive from the 'ApplicationArchives' directory. |
| virtual [instproxy_restore](InstallationProxyApi/instproxy_restore.md)(…) | Restore a previously archived application on the device. This function is the counterpart to instproxy_archive. |
| virtual [instproxy_status_get_current_list](InstallationProxyApi/instproxy_status_get_current_list.md)(…) | Gets total and current item information from a browse response if available. |
| virtual [instproxy_status_get_error](InstallationProxyApi/instproxy_status_get_error.md)(…) | Gets error name, code and description from a response if available. |
| virtual [instproxy_status_get_name](InstallationProxyApi/instproxy_status_get_name.md)(…) | Gets the name of a status. |
| virtual [instproxy_status_get_percent_complete](InstallationProxyApi/instproxy_status_get_percent_complete.md)(…) | Gets progress in percentage from a status if available. |
| virtual [instproxy_uninstall](InstallationProxyApi/instproxy_uninstall.md)(…) | Uninstall an application from the device. |
| virtual [instproxy_upgrade](InstallationProxyApi/instproxy_upgrade.md)(…) | Upgrade an application on the device. This function is nearly the same as instproxy_install; the difference is that the installation progress on the device is faster if the application is already installed. |

## See Also

* interface [IInstallationProxyApi](IInstallationProxyApi.md)
* namespace [iMobileDevice.InstallationProxy](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
