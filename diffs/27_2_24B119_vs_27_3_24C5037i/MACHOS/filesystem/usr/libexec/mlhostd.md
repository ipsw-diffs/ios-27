## mlhostd

> `/usr/libexec/mlhostd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3.7.24.0.0
-  __TEXT.__text: 0x7189c
+3.9.1.0.0
+  __TEXT.__text: 0x71b28
   __TEXT.__auth_stubs: 0x26b0
   __TEXT.__objc_stubs: 0xd20
   __TEXT.__objc_methlist: 0x290

   __TEXT.__objc_methname: 0x1189
   __TEXT.__objc_methtype: 0x53e
   __TEXT.__cstring: 0x938e
-  __TEXT.__oslogstring: 0x309a
+  __TEXT.__oslogstring: 0x30ea
   __TEXT.__swift5_capture: 0x3cc
   __TEXT.__swift_as_entry: 0x74
   __TEXT.__swift_as_ret: 0x44

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 848
   Symbols:   972
-  CStrings:  1660
+  CStrings:  1661
 
Functions:
~ sub_100030194 : 25516 -> 25540
~ sub_1000366a0 -> sub_1000366b8 : 5136 -> 5152
~ sub_100037ab0 -> sub_100037ad8 : 4888 -> 4896
~ sub_100038f18 -> sub_100038f48 : 7932 -> 7956
~ sub_10003cd10 -> sub_10003cd58 : 13840 -> 13864
~ sub_100040320 -> sub_100040380 : 13368 -> 13392
~ sub_100046604 -> sub_10004667c : 624 -> 636
~ sub_100046b64 -> sub_100046be8 : 4052 -> 4572
CStrings:
+ "Task %s is on-demand and cannot be retried, marking DAS task as completed."
```
