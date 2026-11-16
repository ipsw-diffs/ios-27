## AppleVideoEncoder

> `/System/Library/Video/Plug-Ins/AppleVideoEncoder.bundle/AppleVideoEncoder`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-913.64.1.0.0
-  __TEXT.__text: 0x1f3a58
+913.72.1.0.0
+  __TEXT.__text: 0x1f3bb8
   __TEXT.__auth_stubs: 0x10a0
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0xc
   __TEXT.__const: 0x25528
-  __TEXT.__cstring: 0x5c359
+  __TEXT.__cstring: 0x5c4b1
   __TEXT.__gcc_except_tab: 0x734
   __TEXT.__objc_methname: 0xb
   __TEXT.__unwind_info: 0xa20

   - /usr/lib/libobjc.A.dylib
   Functions: 1994
   Symbols:   501
-  CStrings:  7612
+  CStrings:  7617
 
Functions:
~ sub_13d6b0 : 3640 -> 3652
~ sub_1637d0 -> sub_1637dc : 2588 -> 2596
~ sub_166614 -> sub_166628 : 10244 -> 10288
~ sub_177534 -> sub_177574 : 2972 -> 2976
~ sub_1baa10 -> sub_1baa54 : 756 -> 800
~ sub_1c1f0c -> sub_1c1f7c : 1380 -> 1404
~ sub_1ef94c -> sub_1ef9d4 : 508 -> 724
CStrings:
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_AdjustStrength failed %p %p %lld %d %d"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_AdjustStrength failed %p %p %lld %d %d\n"
+ "%lld %d AVE %s: %s:%d %s | too many DRL entries %d (max %d)"
+ "%lld %d AVE %s: %s:%d %s | too many DRL entries %d (max %d)\n"
+ "21:53:34"
+ "21:53:37"
+ "21:53:38"
+ "21:53:39"
+ "913.72.1"
+ "Nov 10 2026"
+ "num <= 2"
+ "pInfo->num_negative_pics <= 16 && pInfo->num_positive_pics <= 16 && (pInfo->num_negative_pics + pInfo->num_positive_pics) <= 16"
- "01:48:30"
- "01:48:33"
- "01:48:34"
- "01:48:35"
- "913.64.1"
- "Oct 24 2026"
- "pInfo->num_negative_pics <= 16 && pInfo->num_positive_pics <= 16"
```
