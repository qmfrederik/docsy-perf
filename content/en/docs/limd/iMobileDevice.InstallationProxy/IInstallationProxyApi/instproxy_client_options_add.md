---
title: IInstallationProxyApi.instproxy_client_options_add method (1 of 2)
---

Adds one or more new key:value pairs to the given client_options.

```csharp
public void instproxy_client_options_add(PlistHandle clientOptions)
```

| parameter | description |
| --- | --- |
| client_options | The client options to modify. |
| ...... | KEY, VALUE, [KEY, VALUE], NULL |

## Remarks

The keys and values passed are expected to be strings, except for the keys "ApplicationSINF", "iTunesMetadata", "ReturnAttributes" which are expecting a plist_t node as value and "SkipUninstall" expects int.

## See Also

* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* interface [IInstallationProxyApi](../IInstallationProxyApi.md)
* namespace [iMobileDevice.InstallationProxy](../../iMobileDevice-net.md)

---

---
title: IInstallationProxyApi.instproxy_client_options_add method (2 of 2)
---

```csharp
public void instproxy_client_options_add(PlistHandle client_options, string key, string value, 
    byte term)
```

## See Also

* class [PlistHandle](../../iMobileDevice.Plist/PlistHandle.md)
* interface [IInstallationProxyApi](../IInstallationProxyApi.md)
* namespace [iMobileDevice.InstallationProxy](../../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
