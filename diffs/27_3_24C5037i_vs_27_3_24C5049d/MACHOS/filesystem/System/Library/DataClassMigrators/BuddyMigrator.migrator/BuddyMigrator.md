## BuddyMigrator

> `/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-5412.2.3.101.0
-  __TEXT.__text: 0x2dbfc
+5412.2.5.0.100
+  __TEXT.__text: 0x2dcb4
   __TEXT.__auth_stubs: 0x1220
   __TEXT.__objc_stubs: 0x31e0
   __TEXT.__objc_methlist: 0x1c80

   __TEXT.__gcc_except_tab: 0x2ac
   __TEXT.__objc_methname: 0x4e53
   __TEXT.__cstring: 0x10b2
-  __TEXT.__oslogstring: 0x2f69
+  __TEXT.__oslogstring: 0x2fd9
   __TEXT.__objc_classname: 0xd9a
   __TEXT.__objc_methtype: 0xdbd
   __TEXT.__dlopen_cstrs: 0x254

   __TEXT.__swift_as_entry: 0x9c
   __TEXT.__swift_as_ret: 0xa0
   __TEXT.__swift_as_cont: 0xa8
-  __TEXT.__unwind_info: 0xd00
+  __TEXT.__unwind_info: 0xd08
   __TEXT.__eh_frame: 0x104c
   __DATA_CONST.__const: 0x12d8
   __DATA_CONST.__cfstring: 0xac0

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 1012
   Symbols:   424
-  CStrings:  1306
+  CStrings:  1308
 
Functions:
~ sub_296c : 8992 -> 9076
~ sub_10954 -> sub_109a8 : 324 -> 328
~ sub_10a98 -> sub_10af0 : 340 -> 352
~ sub_279b8 -> sub_27a1c : 268 -> 292
~ sub_27ac4 -> sub_27b40 : 132 -> 156
~ sub_27cfc -> sub_27d90 : 264 -> 288
~ sub_2e234 -> sub_2e2e0 : 116 -> 128
CStrings:
+ "BuddyMigrator: Queueing Safe Financing mini-buddy"
+ "BuddyMigrator: Queueing Safe Financing mini-buddy recovery flow"
```
