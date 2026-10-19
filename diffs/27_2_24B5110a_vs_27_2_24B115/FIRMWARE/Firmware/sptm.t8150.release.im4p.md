## sptm.t8150.release.im4p

> `Firmware/sptm.t8150.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`

```diff

 820.40.24.0.0
-  __TEXT.__cstring: 0x1606e
+  __TEXT.__cstring: 0x16126
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7c00
   __LATE_CONST.__late_const: 0x8c890
-  __TEXT_EXEC.__text: 0x622cc
+  __TEXT_EXEC.__text: 0x625f0
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __BOOTDATA.__data: 0x18000
   Functions: 408
   Symbols:   1
-  CStrings:  2582
+  CStrings:  2585
 
Functions:
~ sub_fffffff0270e3e08 : 6620 -> 6992
~ sub_fffffff0270e5d90 -> sub_fffffff0270e5f04 : 2956 -> 3372
~ sub_fffffff0270ea9b0 -> sub_fffffff0270eacc4 : 3764 -> 3772
~ sub_fffffff0270eb864 -> sub_fffffff0270ebb80 : 13496 -> 13504
~ sub_fffffff027116288 -> sub_fffffff0271165ac : 72 -> 68
CStrings:
+ "%s: dart %p (%s:%u): Inconsistent unganged clock protection configuration"
+ "(&dart_gapf_ungang_map[state->gapf_ungang_map_index].lock)"
+ "SPTM-820.40.24|2026-10-03:14:50:35.671934|"
+ "sptm_t8110dart_skip_disable_clock_protection_write"
- "SPTM-820.40.24|2026-10-03:20:11:40.632663|"
```
