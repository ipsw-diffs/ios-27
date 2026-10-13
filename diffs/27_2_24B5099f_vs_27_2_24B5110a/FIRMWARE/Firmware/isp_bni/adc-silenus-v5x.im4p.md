## adc-silenus-v5x.im4p

> `Firmware/isp_bni/adc-silenus-v5x.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA.__chain_starts`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0xb5b84c
-  __TEXT.__const: 0x8b7990
-  __TEXT.__cstring: 0xaf116
+  __TEXT.__text: 0xb5b904
+  __TEXT.__const: 0x8b7b10
+  __TEXT.__cstring: 0xaf1c0
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __TEXT.__eh_frame: 0x1bc
-  __DATA.__const: 0x62b98
+  __DATA.__const: 0x62c58
   __DATA._rtk_heap: 0x1000
   __DATA.__data: 0xfc2f8
   __DATA._rtk_power: 0x3f8

   __DATA.__zerofill: 0x5b2af8
   Functions: 9886
   Symbols:   0
-  CStrings:  19046
+  CStrings:  19050
 
Functions:
~ sub_58a278 : 856 -> 908
~ sub_58d7a4 -> sub_58d7d8 : 15252 -> 15272
~ sub_591b9c -> sub_591be4 : 404 -> 428
~ sub_591d30 -> sub_591d90 : 1492 -> 1504
~ sub_5949e8 -> sub_594a54 : 2080 -> 2108
~ sub_62b274 -> sub_62b2fc : 2828 -> 2876
~ sub_b5b714 -> sub_b5b7cc : 320 -> 312
CStrings:
+ "02:33:38"
+ "NVM header revision invalid %d - off %d\n"
+ "transition_mode019_to_mode550_revert_step0"
+ "transition_mode019_to_mode550_revert_step1"
+ "transition_mode019_to_mode550_step0"
+ "transition_mode019_to_mode550_step1"
- "21:29:55"
- "NVM header revision invalid\n"
```
