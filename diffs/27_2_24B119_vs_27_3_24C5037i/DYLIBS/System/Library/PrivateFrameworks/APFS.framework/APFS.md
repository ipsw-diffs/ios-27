## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/APFS`

```diff

-3288.42.1.0.0
-  __TEXT.__text: 0x54714
+3288.60.7.0.0
+  __TEXT.__text: 0x54754
   __TEXT.__const: 0x8540
-  __TEXT.__cstring: 0xe88c
+  __TEXT.__cstring: 0xe8de
   __TEXT.__oslogstring: 0x11b8
   __TEXT.__gcc_except_tab: 0x1c
   __TEXT.__unwind_info: 0x9e8

   - /usr/lib/libutil.dylib
   Functions: 903
   Symbols:   1129
-  CStrings:  1407
+  CStrings:  1408
 
Functions:
~ _btree_node_child_id_update_cb : 32 -> 36
~ _spaceman_iterate_free_extents_internal : 3864 -> 3924
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
+ "3288.60.7"
- "3288.42.1"
```
