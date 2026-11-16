## backgroundassets.user

> `/usr/libexec/backgroundassets.user`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-279.52.2.0.0
-  __TEXT.__text: 0x5ae30
-  __TEXT.__auth_stubs: 0x1970
-  __TEXT.__objc_stubs: 0x7860
+279.60.2.0.0
+  __TEXT.__text: 0x5af70
+  __TEXT.__auth_stubs: 0x1960
+  __TEXT.__objc_stubs: 0x7840
   __TEXT.__objc_methlist: 0x3534
   __TEXT.__const: 0x1ae8
   __TEXT.__objc_classname: 0x84e
-  __TEXT.__objc_methtype: 0x19b2
+  __TEXT.__objc_methtype: 0x19a2
   __TEXT.__oslogstring: 0x6f94
   __TEXT.__cstring: 0x4230
-  __TEXT.__objc_methname: 0x9cde
+  __TEXT.__objc_methname: 0x9cce
   __TEXT.__gcc_except_tab: 0x14fc
   __TEXT.__dlopen_cstrs: 0x5a
   __TEXT.__constg_swiftt: 0x428

   __DATA_CONST.__objc_intobj: 0x18
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__objc_arrayobj: 0x30
-  __DATA_CONST.__auth_got: 0xcc8
+  __DATA_CONST.__auth_got: 0xcc0
   __DATA_CONST.__got: 0x5c8
   __DATA_CONST.__auth_ptr: 0x360
   __DATA.__objc_const: 0x5a30
-  __DATA.__objc_selrefs: 0x21c0
+  __DATA.__objc_selrefs: 0x21b8
   __DATA.__objc_ivar: 0x3b8
   __DATA.__objc_data: 0x1210
   __DATA.__data: 0x12e8

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   Functions: 1952
-  Symbols:   704
-  CStrings:  2620
+  Symbols:   703
+  CStrings:  2619
 
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
- _swift_retain_x27
Functions:
~ sub_100002864 : 2824 -> 2788
~ sub_100004750 -> sub_10000472c : 256 -> 260
~ sub_100012748 -> sub_100012728 : 396 -> 392
~ sub_100012ebc -> sub_100012e98 : 112 -> 108
~ sub_100012f2c -> sub_100012f04 : 116 -> 112
~ sub_1000132a8 -> sub_10001327c : 1380 -> 1376
~ sub_100013848 -> sub_100013818 : 84 -> 80
~ sub_10001389c -> sub_100013868 : 2092 -> 2088
~ sub_100014108 -> sub_1000140d0 : 1448 -> 1440
~ sub_100014880 -> sub_100014840 : 596 -> 592
~ sub_100014d8c -> sub_100014d48 : 360 -> 356
~ sub_100014ef4 -> sub_100014eac : 564 -> 560
~ sub_100015128 -> sub_1000150dc : 984 -> 980
~ sub_100015608 -> sub_1000155b8 : 292 -> 288
~ sub_10001572c -> sub_1000156d8 : 344 -> 340
~ sub_100015884 -> sub_10001582c : 424 -> 420
~ sub_100015a2c -> sub_1000159d0 : 192 -> 188
~ sub_100015aec -> sub_100015a8c : 296 -> 292
~ sub_100015c14 -> sub_100015bb0 : 296 -> 292
~ sub_100015d3c -> sub_100015cd4 : 124 -> 120
~ sub_1000161dc -> sub_100016170 : 292 -> 288
~ sub_100016438 -> sub_1000163c8 : 360 -> 356
~ sub_1000165a0 -> sub_10001652c : 416 -> 408
~ sub_10003ed50 -> sub_10003ecd4 : 11004 -> 11244
~ sub_1000441c8 -> sub_10004423c : 116 -> 128
~ sub_10004c098 -> sub_10004c118 : 480 -> 508
~ sub_10004e52c -> sub_10004e5c8 : 1888 -> 1904
~ sub_100054a50 -> sub_100054afc : 11488 -> 11584
~ sub_1000579b0 -> sub_100057abc : 476 -> 504
~ sub_100057b8c -> sub_100057cb4 : 264 -> 288
CStrings:
+ "_resetAllowsCellularAccess"
+ "_resetAllowsConstrainedNetworkAccess"
+ "_resetAllowsExpensiveNetworkAccess"
+ "{os_unfair_recursive_lock_s=\"_os_unfair_recursive_lock_opaque\"[2I]}"
- "allowsCellularAccess"
- "allowsConstrainedNetworkAccess"
- "allowsExpensiveNetworkAccess"
- "setAllowsConstrainedNetworkAccess:"
- "{os_unfair_recursive_lock_s=\"ourl_lock\"{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}\"ourl_count\"I}"
```
