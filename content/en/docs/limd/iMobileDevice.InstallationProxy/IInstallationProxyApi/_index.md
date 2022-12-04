---
title: IInstallationProxyApi interface
---

```csharp
public interface IInstallationProxyApi
```

## Members

| name | description |
| --- | --- |
| [Parent](IInstallationProxyApi/Parent.md) { get; } | Gets or sets the !:ILibiMobileDeviceApi which owns this InstallationProxy. |
| [instproxy_archive](IInstallationProxyApi/instproxy_archive.md)(…) | Archive an application on the device. This function tells the device to make an archive of the specified application. This results in the device creating a ZIP archive in the 'ApplicationArchives' directory and uninstalling the application. |
| [instproxy_browse](IInstallationProxyApi/instproxy_browse.md)(…) | List installed applications. This function runs synchronously. |
| [instproxy_browse_with_callback](IInstallationProxyApi/instproxy_browse_with_callback.md)(…) | List pages of installed applications in a callback. |
| [instproxy_check_capabilities_match](IInstallationProxyApi/instproxy_check_capabilities_match.md)(…) | Checks a device for certain capabilities. |
| [instproxy_client_free](IInstallationProxyApi/instproxy_client_free.md)(…) | Disconnects an installation_proxy client from the device and frees up the installation_proxy client data. |
| [instproxy_client_get_path_for_bundle_identifier](IInstallationProxyApi/instproxy_client_get_path_for_bundle_identifier.md)(…) | Queries the device for the path of an application. |
| [instproxy_client_new](IInstallationProxyApi/instproxy_client_new.md)(…) | Connects to the installation_proxy service on the specified device. |
| [instproxy_client_options_add](IInstallationProxyApi/instproxy_client_options_add.md)(…) | Adds one or more new key:value pairs to the given client_options. (2 methods) |
| [instproxy_client_options_free](IInstallationProxyApi/instproxy_client_options_free.md)(…) | Frees client_options plist. |
| [instproxy_client_options_new](IInstallationProxyApi/instproxy_client_options_new.md)() | Creates a new client_options plist. |
| [instproxy_client_options_set_return_attributes](IInstallationProxyApi/instproxy_client_options_set_return_attributes.md)(…) | Adds attributes to the given client_options to filter browse results. |
| [instproxy_client_start_service](IInstallationProxyApi/instproxy_client_start_service.md)(…) | Starts a new installation_proxy service on the specified device and connects to it. |
| [instproxy_command_get_name](IInstallationProxyApi/instproxy_command_get_name.md)(…) | Gets the name from a command dictionary. |
| [instproxy_install](IInstallationProxyApi/instproxy_install.md)(…) | Install an application on the device. |
| [instproxy_lookup](IInstallationProxyApi/instproxy_lookup.md)(…) | Lookup information about specific applications from the device. |
| [instproxy_lookup_archives](IInstallationProxyApi/instproxy_lookup_archives.md)(…) | List archived applications. This function runs synchronously. |
| [instproxy_remove_archive](IInstallationProxyApi/instproxy_remove_archive.md)(…) | Removes a previously archived application from the device. This function removes the ZIP archive from the 'ApplicationArchives' directory. |
| [instproxy_restore](IInstallationProxyApi/instproxy_restore.md)(…) | Restore a previously archived application on the device. This function is the counterpart to instproxy_archive. |
| [instproxy_status_get_current_list](IInstallationProxyApi/instproxy_status_get_current_list.md)(…) | Gets total and current item information from a browse response if available. |
| [instproxy_status_get_error](IInstallationProxyApi/instproxy_status_get_error.md)(…) | Gets error name, code and description from a response if available. |
| [instproxy_status_get_name](IInstallationProxyApi/instproxy_status_get_name.md)(…) | Gets the name of a status. |
| [instproxy_status_get_percent_complete](IInstallationProxyApi/instproxy_status_get_percent_complete.md)(…) | Gets progress in percentage from a status if available. |
| [instproxy_uninstall](IInstallationProxyApi/instproxy_uninstall.md)(…) | Uninstall an application from the device. |
| [instproxy_upgrade](IInstallationProxyApi/instproxy_upgrade.md)(…) | Upgrade an application on the device. This function is nearly the same as instproxy_install; the difference is that the installation progress on the device is faster if the application is already installed. |

## See Also

* namespace [iMobileDevice.InstallationProxy](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->