## terminusd

> `/usr/libexec/terminusd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_capture`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-914.60.11.0.0
-  __TEXT.__text: 0x213fa8
-  __TEXT.__auth_stubs: 0x4180
+914.60.12.0.3
+  __TEXT.__text: 0x21412c
+  __TEXT.__auth_stubs: 0x41a0
   __TEXT.__objc_stubs: 0x9680
   __TEXT.__objc_methlist: 0x5a04
-  __TEXT.__const: 0x73c
+  __TEXT.__const: 0x740
   __TEXT.__swift5_typeref: 0x4ce
-  __TEXT.__cstring: 0x560c5
+  __TEXT.__cstring: 0x56151
   __TEXT.__swift5_capture: 0x4a4
   __TEXT.__objc_methtype: 0x452a
   __TEXT.__oslogstring: 0x2de8

   __TEXT.__unwind_info: 0x3438
   __TEXT.__eh_frame: 0xeb8
   __DATA_CONST.__const: 0x5478
-  __DATA_CONST.__cfstring: 0xe9a0
+  __DATA_CONST.__cfstring: 0xe9e0
   __DATA_CONST.__objc_classlist: 0x620
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x1b0

   __DATA_CONST.__objc_arrayobj: 0x168
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_dictobj: 0x50
-  __DATA_CONST.__auth_got: 0x20d0
+  __DATA_CONST.__auth_got: 0x20e0
   __DATA_CONST.__got: 0xf28
   __DATA_CONST.__auth_ptr: 0x1d8
   __DATA.__objc_const: 0x1b0e0

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 4087
-  Symbols:   1592
-  CStrings:  12051
+  Symbols:   1594
+  CStrings:  12056
 
Symbols:
+ _nw_endpoint_copy_txt_record
+ _nw_txt_record_find_key
Functions:
~ sub_1000261f0 : 1016 -> 992
~ sub_10002f2f0 -> sub_10002f2d8 : 1124 -> 1152
~ sub_1001ee71c -> sub_1001ee720 : 548 -> 552
~ sub_1001ee940 -> sub_1001ee948 : 164 -> 316
~ sub_1001efdfc -> sub_1001efe9c : 484 -> 512
~ sub_1001f0050 -> sub_1001f010c : 1528 -> 1692
~ sub_100201e04 -> sub_100201f64 : 116 -> 128
~ sub_100210e3c -> sub_100210fa8 : 264 -> 288
CStrings:
+ "%@.%@"
+ "%s%.30s:%-4d %@: peer %@ has no listener for our service, not connecting"
+ "21:57:58"
+ "914.60.12.0.3"
+ "HasService"
+ "Nov 10 2026"
+ "TXT record changed"
+ "isBabelASQUICPeerListening"
- "02:54:08"
- "914.60.11"
- "Oct 24 2026"
```
