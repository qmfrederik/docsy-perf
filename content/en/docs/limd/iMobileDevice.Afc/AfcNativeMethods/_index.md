---
title: AfcNativeMethods class
---

```csharp
public class AfcNativeMethods
```

## Public Members

| name | description |
| --- | --- |
| [AfcNativeMethods](AfcNativeMethods/AfcNativeMethods.md)() | The default constructor. |
| static [afc_client_free](AfcNativeMethods/afc_client_free.md)(…) | Frees up an AFC client. If the connection was created by the client itself, the connection will be closed. |
| static [afc_client_new](AfcNativeMethods/afc_client_new.md)(…) | Makes a connection to the AFC service on the device. |
| static [afc_client_start_service](AfcNativeMethods/afc_client_start_service.md)(…) | Starts a new AFC service on the specified device and connects to it. |
| static [afc_dictionary_free](AfcNativeMethods/afc_dictionary_free.md)(…) | Frees up a char dictionary as returned by some AFC functions. |
| static [afc_file_close](AfcNativeMethods/afc_file_close.md)(…) | Closes a file on the device. |
| static [afc_file_lock](AfcNativeMethods/afc_file_lock.md)(…) | Locks or unlocks a file on the device. Makes use of flock on the device. |
| static [afc_file_open](AfcNativeMethods/afc_file_open.md)(…) | Opens a file on the device. |
| static [afc_file_read](AfcNativeMethods/afc_file_read.md)(…) | Attempts to the read the given number of bytes from the given file. |
| static [afc_file_seek](AfcNativeMethods/afc_file_seek.md)(…) | Seeks to a given position of a pre-opened file on the device. |
| static [afc_file_tell](AfcNativeMethods/afc_file_tell.md)(…) | Returns current position in a pre-opened file on the device. |
| static [afc_file_truncate](AfcNativeMethods/afc_file_truncate.md)(…) | Sets the size of a file on the device. |
| static [afc_file_write](AfcNativeMethods/afc_file_write.md)(…) | Writes a given number of bytes to a file. |
| static [afc_get_device_info](AfcNativeMethods/afc_get_device_info.md)(…) | Get device information for a connected client. The device information returned is the device model as well as the free space, the total capacity and blocksize on the accessed disk partition. (2 methods) |
| static [afc_get_device_info_key](AfcNativeMethods/afc_get_device_info_key.md)(…) | Get a specific key of the device info list for a client connection. Known key values are: Model, FSTotalBytes, FSFreeBytes and FSBlockSize. This is a helper function for afc_get_device_info(). (2 methods) |
| static [afc_get_file_info](AfcNativeMethods/afc_get_file_info.md)(…) | Gets information about a specific file. (2 methods) |
| static [afc_make_directory](AfcNativeMethods/afc_make_directory.md)(…) | Creates a directory on the device. |
| static [afc_make_link](AfcNativeMethods/afc_make_link.md)(…) | Creates a hard link or symbolic link on the device. |
| static [afc_read_directory](AfcNativeMethods/afc_read_directory.md)(…) | Gets a directory listing of the directory requested. (2 methods) |
| static [afc_remove_path](AfcNativeMethods/afc_remove_path.md)(…) | Deletes a file or directory. |
| static [afc_remove_path_and_contents](AfcNativeMethods/afc_remove_path_and_contents.md)(…) | Deletes a file or directory including possible contents. |
| static [afc_rename_path](AfcNativeMethods/afc_rename_path.md)(…) | Renames a file or directory on the device. |
| static [afc_set_file_time](AfcNativeMethods/afc_set_file_time.md)(…) | Sets the modification time of a file on the device. |
| static [afc_truncate](AfcNativeMethods/afc_truncate.md)(…) | Sets the size of a file on the device without prior opening it. |

## See Also

* namespace [iMobileDevice.Afc](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
