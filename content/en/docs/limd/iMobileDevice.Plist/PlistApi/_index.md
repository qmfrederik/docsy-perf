---
title: PlistApi class
---

```csharp
public class PlistApi : IPlistApi
```

## Public Members

| name | description |
| --- | --- |
| [PlistApi](PlistApi/PlistApi.md)(…) | Initializes a new instance of the [`PlistApi`](PlistApi.md) class |
| [Parent](PlistApi/Parent.md) { get; } |  |
| virtual [plist_access_path](PlistApi/plist_access_path.md)(…) | Get a node from its path. Each path element depends on the associated father node type. For Dictionaries, var args are casted to const char*, for arrays, var args are caster to uint32_t Search is breath first order. |
| virtual [plist_access_pathv](PlistApi/plist_access_pathv.md)(…) | Variadic version of #plist_access_path. |
| virtual [plist_array_append_item](PlistApi/plist_array_append_item.md)(…) | Append a new item at the end of a #PLIST_ARRAY node. |
| virtual [plist_array_get_item](PlistApi/plist_array_get_item.md)(…) | Get the nth item in a #PLIST_ARRAY node. |
| virtual [plist_array_get_item_index](PlistApi/plist_array_get_item_index.md)(…) | Get the index of an item. item must be a member of a #PLIST_ARRAY node. |
| virtual [plist_array_get_size](PlistApi/plist_array_get_size.md)(…) | Get size of a #PLIST_ARRAY node. |
| virtual [plist_array_insert_item](PlistApi/plist_array_insert_item.md)(…) | Insert a new item at position n in a #PLIST_ARRAY node. |
| virtual [plist_array_item_remove](PlistApi/plist_array_item_remove.md)(…) | Remove a node that is a child node of a #PLIST_ARRAY node. node will be freed using #plist_free. |
| virtual [plist_array_new_iter](PlistApi/plist_array_new_iter.md)(…) | Create an iterator of a #PLIST_ARRAY node. The allocated iterator should be freed with the standard free function. |
| virtual [plist_array_next_item](PlistApi/plist_array_next_item.md)(…) | Increment iterator of a #PLIST_ARRAY node. |
| virtual [plist_array_remove_item](PlistApi/plist_array_remove_item.md)(…) | Remove an existing position in a #PLIST_ARRAY node. Removed position will be freed using #plist_free. |
| virtual [plist_array_set_item](PlistApi/plist_array_set_item.md)(…) | Set the nth item in a #PLIST_ARRAY node. The previous item at index n will be freed using #plist_free |
| virtual [plist_compare_node_value](PlistApi/plist_compare_node_value.md)(…) | Compare two node values |
| virtual [plist_copy](PlistApi/plist_copy.md)(…) | Return a copy of passed node and it's children |
| virtual [plist_dict_get_item](PlistApi/plist_dict_get_item.md)(…) | Get the nth item in a #PLIST_DICT node. |
| virtual [plist_dict_get_item_key](PlistApi/plist_dict_get_item_key.md)(…) | Get key associated key to an item. Item must be member of a dictionary. |
| virtual [plist_dict_get_size](PlistApi/plist_dict_get_size.md)(…) | Get size of a #PLIST_DICT node. |
| virtual [plist_dict_insert_item](PlistApi/plist_dict_insert_item.md)(…) | Insert a new item into a #PLIST_DICT node. |
| virtual [plist_dict_item_get_key](PlistApi/plist_dict_item_get_key.md)(…) | Get key node associated to an item. Item must be member of a dictionary. |
| virtual [plist_dict_merge](PlistApi/plist_dict_merge.md)(…) | Merge a dictionary into another. This will add all key/value pairs from the source dictionary to the target dictionary, overwriting any existing key/value pairs that are already present in target. |
| virtual [plist_dict_new_iter](PlistApi/plist_dict_new_iter.md)(…) | Create an iterator of a #PLIST_DICT node. The allocated iterator should be freed with the standard free function. |
| virtual [plist_dict_next_item](PlistApi/plist_dict_next_item.md)(…) | Increment iterator of a #PLIST_DICT node. |
| virtual [plist_dict_remove_item](PlistApi/plist_dict_remove_item.md)(…) | Remove an existing position in a #PLIST_DICT node. Removed position will be freed using #plist_free |
| virtual [plist_dict_set_item](PlistApi/plist_dict_set_item.md)(…) | Set item identified by key in a #PLIST_DICT node. The previous item identified by key will be freed using #plist_free. If there is no item for the given key a new item will be inserted. |
| virtual [plist_free](PlistApi/plist_free.md)(…) | Destruct a plist_t node and all its children recursively |
| virtual [plist_from_bin](PlistApi/plist_from_bin.md)(…) | Import the #plist_t structure from binary format. |
| virtual [plist_from_memory](PlistApi/plist_from_memory.md)(…) | Import the #plist_t structure from memory data. This method will look at the first bytes of plist_data to determine if plist_data contains a binary or XML plist. |
| virtual [plist_from_xml](PlistApi/plist_from_xml.md)(…) | Import the #plist_t structure from XML format. |
| virtual [plist_get_bool_val](PlistApi/plist_get_bool_val.md)(…) | Get the value of a #PLIST_BOOLEAN node. This function does nothing if node is not of type #PLIST_BOOLEAN |
| virtual [plist_get_data_val](PlistApi/plist_get_data_val.md)(…) | Get the value of a #PLIST_DATA node. This function does nothing if node is not of type #PLIST_DATA |
| virtual [plist_get_date_val](PlistApi/plist_get_date_val.md)(…) | Get the value of a #PLIST_DATE node. This function does nothing if node is not of type #PLIST_DATE |
| virtual [plist_get_key_val](PlistApi/plist_get_key_val.md)(…) | Get the value of a #PLIST_KEY node. This function does nothing if node is not of type #PLIST_KEY |
| virtual [plist_get_node_type](PlistApi/plist_get_node_type.md)(…) | Get the #plist_type of a node. |
| virtual [plist_get_parent](PlistApi/plist_get_parent.md)(…) | Get the parent of a node |
| virtual [plist_get_real_val](PlistApi/plist_get_real_val.md)(…) | Get the value of a #PLIST_REAL node. This function does nothing if node is not of type #PLIST_REAL |
| virtual [plist_get_string_val](PlistApi/plist_get_string_val.md)(…) | Get the value of a #PLIST_STRING node. This function does nothing if node is not of type #PLIST_STRING |
| virtual [plist_get_uid_val](PlistApi/plist_get_uid_val.md)(…) | Get the value of a #PLIST_UID node. This function does nothing if node is not of type #PLIST_UID |
| virtual [plist_get_uint_val](PlistApi/plist_get_uint_val.md)(…) | Get the value of a #PLIST_UINT node. This function does nothing if node is not of type #PLIST_UINT |
| virtual [plist_is_binary](PlistApi/plist_is_binary.md)(…) | Test if in-memory plist data is binary or XML This method will look at the first bytes of plist_data to determine if plist_data contains a binary or XML plist. This method is not validating the whole memory buffer to check if the content is truly a plist, it's only using some heuristic on the first few bytes of plist_data. |
| virtual [plist_new_array](PlistApi/plist_new_array.md)() | Create a new root plist_t type #PLIST_ARRAY |
| virtual [plist_new_bool](PlistApi/plist_new_bool.md)(…) | Create a new plist_t type #PLIST_BOOLEAN |
| virtual [plist_new_data](PlistApi/plist_new_data.md)(…) | Create a new plist_t type #PLIST_DATA |
| virtual [plist_new_date](PlistApi/plist_new_date.md)(…) | Create a new plist_t type #PLIST_DATE |
| virtual [plist_new_dict](PlistApi/plist_new_dict.md)() | Create a new root plist_t type #PLIST_DICT |
| virtual [plist_new_real](PlistApi/plist_new_real.md)(…) | Create a new plist_t type #PLIST_REAL |
| virtual [plist_new_string](PlistApi/plist_new_string.md)(…) | Create a new plist_t type #PLIST_STRING |
| virtual [plist_new_uid](PlistApi/plist_new_uid.md)(…) | Create a new plist_t type #PLIST_UID |
| virtual [plist_new_uint](PlistApi/plist_new_uint.md)(…) | Create a new plist_t type #PLIST_UINT |
| virtual [plist_set_bool_val](PlistApi/plist_set_bool_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_BOOLEAN |
| virtual [plist_set_data_val](PlistApi/plist_set_data_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_DATA |
| virtual [plist_set_date_val](PlistApi/plist_set_date_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_DATE |
| virtual [plist_set_key_val](PlistApi/plist_set_key_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_KEY |
| virtual [plist_set_real_val](PlistApi/plist_set_real_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_REAL |
| virtual [plist_set_string_val](PlistApi/plist_set_string_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_STRING |
| virtual [plist_set_uid_val](PlistApi/plist_set_uid_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_UID |
| virtual [plist_set_uint_val](PlistApi/plist_set_uint_val.md)(…) | Set the value of a node. Forces type of node to #PLIST_UINT |
| virtual [plist_to_bin](PlistApi/plist_to_bin.md)(…) | Export the #plist_t structure to binary format. |
| virtual [plist_to_bin_free](PlistApi/plist_to_bin_free.md)(…) | Frees the memory allocated by plist_to_bin |
| virtual [plist_to_xml](PlistApi/plist_to_xml.md)(…) | Export the #plist_t structure to XML format. |
| virtual [plist_to_xml_free](PlistApi/plist_to_xml_free.md)(…) | Frees the memory allocated by plist_to_xml |

## See Also

* interface [IPlistApi](IPlistApi.md)
* namespace [iMobileDevice.Plist](../iMobileDevice-net.md)

<!-- DO NOT EDIT: generated by xmldocmd for iMobileDevice-net.dll -->
