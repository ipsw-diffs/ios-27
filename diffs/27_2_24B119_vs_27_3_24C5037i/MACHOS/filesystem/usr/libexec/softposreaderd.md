## softposreaderd

> `/usr/libexec/softposreaderd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__cstring`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
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

-51.5.0.0.0
-  __TEXT.__text: 0x41cc68
+52.2.0.0.0
+  __TEXT.__text: 0x41d010
   __TEXT.__auth_stubs: 0x42c0
   __TEXT.__objc_stubs: 0x2080
   __TEXT.__objc_methlist: 0xe7c

   __TEXT.__swift5_typeref: 0x24cc
   __TEXT.__cstring: 0x11b7b
   __TEXT.__objc_methtype: 0x1525
-  __TEXT.__oslogstring: 0xd11e
+  __TEXT.__oslogstring: 0xd17e
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constg_swiftt: 0x7984
   __TEXT.__swift5_proto: 0xcdc

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 6171
   Symbols:   1692
-  CStrings:  3606
+  CStrings:  3609
 
Functions:
~ sub_10006cc08 : 15964 -> 16228
~ sub_1000d6d30 -> sub_1000d6e38 : 596 -> 440
~ sub_100133ce0 -> sub_100133d4c : 324 -> 360
~ sub_1001453d0 -> sub_100145460 : 5208 -> 5564
~ sub_1001cd3f0 -> sub_1001cd5e4 : 5008 -> 5408
~ sub_100242c4c -> sub_100242fd0 : 5628 -> 5664
CStrings:
+ "Error validating time token: %@"
+ "NFC antenna is not present"
+ "NFC hardware not supported"
```
