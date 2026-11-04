## replayd

> `/usr/libexec/replayd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-765.15.2.0.0
-  __TEXT.__text: 0xbaecc
-  __TEXT.__auth_stubs: 0x1920
+770.2.1.0.0
+  __TEXT.__text: 0xbafdc
+  __TEXT.__auth_stubs: 0x1930
   __TEXT.__objc_stubs: 0xf340
   __TEXT.__objc_methlist: 0x74b0
   __TEXT.__const: 0x3e4
   __TEXT.__gcc_except_tab: 0xfc8
-  __TEXT.__objc_methname: 0x15f9b
-  __TEXT.__oslogstring: 0x16809
+  __TEXT.__objc_methname: 0x15fe3
+  __TEXT.__oslogstring: 0x16863
   __TEXT.__cstring: 0x17d26
   __TEXT.__objc_classname: 0xa44
   __TEXT.__objc_methtype: 0x4410

   __DATA_CONST.__objc_doubleobj: 0x50
   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA_CONST.__auth_got: 0xca0
+  __DATA_CONST.__auth_got: 0xca8
   __DATA_CONST.__got: 0xc88
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x113b8
+  __DATA.__objc_const: 0x11418
   __DATA.__objc_selrefs: 0x4728
-  __DATA.__objc_ivar: 0xd88
+  __DATA.__objc_ivar: 0xd94
   __DATA.__objc_data: 0x18b0
   __DATA.__data: 0xe54
   __DATA.__bss: 0x268

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 3683
-  Symbols:   802
-  CStrings:  7391
+  Symbols:   803
+  CStrings:  7395
 
Symbols:
+ _MGGetLogicalDeviceDisplayCount
Functions:
~ sub_100015290 : 888 -> 880
~ sub_1000162fc -> sub_1000162f4 : 720 -> 712
~ sub_1000175b8 -> sub_1000175a8 : 752 -> 744
~ sub_100017b94 -> sub_100017b7c : 228 -> 220
~ sub_100028524 -> sub_100028504 : 100 -> 160
~ sub_100029180 -> sub_10002919c : 932 -> 1216
~ sub_100082dc8 -> sub_100082f00 : 448 -> 440
~ sub_100082fc0 -> sub_1000830f0 : 448 -> 440
~ sub_1000a31e0 -> sub_1000a3308 : 784 -> 776
~ sub_1000a40c4 -> sub_1000a41e4 : 556 -> 548
~ sub_1000a4c88 -> sub_1000a4da0 : 852 -> 844
CStrings:
+ " [DEBUG] %{public}s:%d dropping frame width:%zu heigth:%zu, expected width:%zu heigth:%zu"
+ "_dropsFramesWithUnexpectedSize"
+ "_expectedFrameHeight"
+ "_expectedFrameWidth"
```
