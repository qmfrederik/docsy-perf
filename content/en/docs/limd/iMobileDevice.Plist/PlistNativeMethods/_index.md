---
title: PlistNativeMethods class
---

```csharp
public class PlistNativeMethods
```

## Public Members

| name | description |
| --- | --- |
| [PlistNativeMethods](PlistNativeMethods/PlistNativeMethods.md)() | The default constructor. |
| static [plist_access_path](PlistNativeMethods/plist_access_path.md)(…) | Get a node from its path. Each path element depends on the associated father node type. For Dictionaries, var args are casted to const char*, for arrays, var args are caster to uint32_t Search is breath first order. |
| static [plist_access_pathv](PlistNativeMethods/plist_access_pathv.md)(…) | Variadic version of #plist_access_path. |
| static [plist_array_append_item](PlistNativeMethods/plist_array_append_item.md)(…) | Append a new item at the end of a #PLIST_ARRAY node. |
| static [plist_array_get_item](PlistNativeMethods/plist_array_get_item.md)(…) | Get the nth item in a #PLIST_ARRAY node. |
| static [plist_array_get_item_index](PlistNativeMethods/plist_array_get_item_index.md)(…) | Get the index of an item. item must be a member of a #PLIST_ARRAY node. |
| static [plist_array_get_size](PlistNativeMethods/plist_array_get_size.md)(…) | Get size of a #PLIST_ARRAY node. |
| static [plist_array_insert_item](PlistNativeMethods/plist_array_insert_item.md)(…) | Insert a new item at position n in a #PLIST_ARRAY node. |
| static [plist_array_item_remove](PlistNativeMethods/plist_array_item_remove.md)(…) | Remove a node that is a child node of a #PLIST_ARRAY node. node will be freed using #plist_free. |
| static [plist_array_new_iter](PlistNativeMethods/plist_array_new_iter.md)(…) | Create an iterator of a #PLIST_ARRAY node. The allocated iterator should be freed with the standard free function. |
| static [plist_array_next_item](PlistNativeMethods/plist_array_next_item.md)(…) | Increment iterator of a #PLIST_ARRAY node. |
| static [plist_array_remove_item](PlistNativeMethods/plist_array_remove_item.md)(…) | Remove an existing position in a #PLIST_ARRAY node. Removed position will be freed using #plist_free. |
| static [plist_array_set_item](PlistNativeMethods/plist_array_set_item.md)(…) | Set the nth item in a #PLIST_ARRAY node. The previous item at index n will be freed using #plist_free |
| static [plist_compare_node_value](PlistNativeMethods/plist_compare_node_value.md)(…) | Compare two node values |
| static [plist_copy](PlistNativeMethods/plist_copy.md)(…) | Return a copy of passed node and it's children |
| static [plist_dict_get_item](PlistNativeMethods/plist_dict_get_item.md)(…) | Get the nth item in a #PLIST_DICT node. |
| static [plist_dict_get_item_key](PlistNativeMethods/plist_dict_get_item_key.md)(…) |  (2 methods) |
| static [plist_dict_get_size](PlistNativeMethods/plist_dict_get_size.md)(…) | Get size of a #PLIST_DICT node. |
| static [plist_dict_insert_item](PlistNativeMethods/plist_dict_insert_item.md)(…) | Insert a new item into a #PLIST_DICT node. |
| static [plist_dict_item_get_key](PlistNativeMethods/plist_dict_item_get_key.md)(…) | Get key node associated to an item. Item must be member of a dictionary. |
| static [plist_dict_merge](PlistNativeMethods/plist_dict_merge.md)(…) | Merge a dictionary into another. This will add all key/value pairs from the source dictionary to the target dictionary, overwriting any existing key/value pairs that are already present in target. |
| static [plist_dict_new_iter](PlistNativeMethods/plist_dict_new_iter.md)(…) | Create an iterator of a #PLIST_DICT node. The allocated iterator should be freed with the standard free function. |
| static [plist_dict_next_item](PlistNativeMethods/plist_dict_next_item.md)(…) |  (2 methods) |
| static [plist_dict_remove_item](PlistNativeMethods/plist_dict_remove_item.md)(…) | Remove an existing position in a #PLIST_DICT node. Removed position will be freed using #plist_free |
| static [plist_dict_set_item](PlistNativeMethods/plist_dict_set_item.md)(…) | Set item identified by key in a #PLIST_DICT node. The previous item identified by key will be freed using #plist_free. If there is no item for the given key a new item will be inserted. |
| static [plist_free](PlistNativeMethods/plist_free.md)(…) | Destruct a plist_t node and all its children recursively |
| static [plist_from_bin](PlistNativeMethods/plist_from_bin.md)(…) | Import the #plist_t structure from binary format. |
| static [plist_from_memory](PlistNativeMethods/plist_from_memory.md)(…) | Import the #plist_t structure from memory data. This method will look at the first bytes of plist_data to determine if plist_data contains a binary or XML plist. |
| static [plist_from_xml](PlistNativeMethods/plist_from_xml.md)(…) | Import the #plist_t structure from XML format. |
| static [plist_get_bool_val](PlistNativeMethods/plist_get_bool_val.md)(…) | Get the value of a #PLIST_BOOLEAN node. This function does nothing if node is not of type #PLIST_BOOLEAN |
| static [plist_get_data_val](PlistNativeMethods/plist_get_data_val.md)(…) |  (2 methods) |
| static [plist_get_date_val](PlistNativeMethods/plist_get_date_val.md)(…) | Get the value of a #PLIST_DATE node. This function does nothing if node is not of type #PLIST_DATE |
| static [plist_get_key_val](PlistNativeMethods/plist_get_key_val.md)(…) |  (2 methods) |
| static [plist_get_node_type](PlistNativeMethods/plist_get_node_type.md)(…) | Get the #plist_type of a node. |
| static [plist_get_parent](PlistNativeMethods/plist_get_parent.md)(…) | Get the parent of a node |
| static [plist_get_real_val](PlistNativeMethods/plist_get_real_val.md)(…) | Get the value of a #PLIST_REAL node. This function does nothing if node is not of type #PLIST_REAL |
| static [plist_get_string_val](PlistNativeMethods/plist_get_string_val.md)(…) |  (2 methods) |
| static [plist_get_uid_val](PlistNativeMethods/plist_get_uid_val.md)(…) | Get the value of a #PLIST_UID node. This function does nothing if node is not of type #PLIST_UID |
| static [plist_get_uint_val](PlistNativeMethods/plist_get_uint_val.md)(…) | Get the value of a #PLIST_UINT node. This function does nothing if node is not of type #PLIST_UINT |
| static [plist_is_binary](PlistNativeMethods/plist_is_binary.md)(…) | Test if in-memory plist data is binary or XML This method will look at the first bytes of plist_data to determine if plist_data contains a binary or XML plist. This method is not validating the whole memory buffer to check if the content is truly a plist, it's only using some heuristic on the first few bytes of plist_data. |
| static [plist_new_array](PlistNativeMethods/plist_new_array.md)() | Create a new root plist_t type #PLIST_ARRAY |
| static [plist_new_bool](PlistNativeMethods/plist_new_bool.md)(…) | Create a new plist_t type #PLIST_BOOLEAN |
| static [plist_new_data](PlistNativeMethods/plist_new_data.md)(…) | Create a new plist_t type #PLIST_DATA |
| static [plist_new_date](PlistNativeMethods/plist_new_date.md)(…) | Create a new plist_t type #PLIST_DATE |
| static [plist_new_dict](PlistNativeMethods/plist_new_dict.md)() | Create a new root plist_t type #PLIST_DICT |
| static [plist_new_real](PlistNativeMethods/plist_new_real.md)(…) | Create a new plist_t type #PLIST_REAL |
| static [plist_new_string](PlistNativeMethods/plist_new_string.md)(…) | Create a new plist_t type #PLIST_STRING |
| static [plist_new_uid](PlistNativeMethods/plist_new_uid.md)(…) | Create a new plist_t type #PLIST_UID |
| static [plist_new_uint](PlistNativeMethods/plist_new_uint.md)(…) | Create a new plist_t type #PLIST_UINT |
| static [plist_set_bool_val](PlistNativeMethods/plist_set_bool_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_BOOLEAN |
| static [plist_set_data_val](PlistNativeMethods/plist_set_data_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_DATA |
| static [plist_set_date_val](PlistNativeMethods/plist_set_date_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_DATE |
| static [plist_set_key_val](PlistNativeMethods/plist_set_key_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_KEY |
| static [plist_set_real_val](PlistNativeMethods/plist_set_real_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_REAL |
| static [plist_set_string_val](PlistNativeMethods/plist_set_string_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_STRING |
| static [plist_set_uid_val](PlistNativeMethods/plist_set_uid_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_UID |
| static [plist_set_uint_val](PlistNativeMethods/plist_set_uint_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_UINT |
| static [plist_to_bin](PlistNativeMethods/plist_to_bin.md)(…) |  (2 methods) |
| static [plist_to_bin_free](PlistNativeMethods/plist_to_bin_free.md)(…) | Frees the memory allocated by plist_to_bin |
| static [plist_to_xml](PlistNativeMethods/plist_to_xml.md)(…) |  (2 methods) |
| static [plist_to_xml_free](PlistNativeMethods/plist_to_xml_free.md)(…) | Frees the memory allocated by plist_to_xml |

## See Also

* namespace [iMobileDevice.Plist](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
