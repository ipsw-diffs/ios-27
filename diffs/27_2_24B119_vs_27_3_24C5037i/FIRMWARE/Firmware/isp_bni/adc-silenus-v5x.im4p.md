## adc-silenus-v5x.im4p

> `Firmware/isp_bni/adc-silenus-v5x.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0xb5b904
+  __TEXT.__text: 0xb5c200
   __TEXT.__const: 0x8b7b10
-  __TEXT.__cstring: 0xaf1c0
+  __TEXT.__cstring: 0xaf29d
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __TEXT.__eh_frame: 0x1bc

   __DATA.__zerofill: 0x5b2af8
   Functions: 9886
   Symbols:   0
-  CStrings:  19050
+  CStrings:  19053
 
Functions:
~ sub_221f88 : 63256 -> 64188
~ sub_242a08 -> sub_242dac : 59068 -> 59912
~ sub_462d50 -> sub_463440 : 5120 -> 5104
~ sub_470a68 -> sub_471148 : 102796 -> 103224
~ sub_4cd4cc -> sub_4cdd58 : 3044 -> 3048
~ sub_83b018 -> sub_83b8a8 : 3720 -> 3840
~ sub_97951c -> sub_979e24 : 5152 -> 5156
~ sub_99c0f8 -> sub_99ca04 : 6448 -> 6444
~ sub_99e9d4 -> sub_99f2dc : 3600 -> 3604
~ sub_9ba12c -> sub_9baa38 : 652 -> 656
~ sub_9c00f0 -> sub_9c0a00 : 5576 -> 5572
~ sub_9ddc20 -> sub_9de52c : 3244 -> 3216
~ sub_9df484 -> sub_9dfd74 : 6540 -> 6552
CStrings:
+ "%s: SharedRawBufferPoolInfoGet: chBitMask 0x%x has no WIDE/TELE/SWIDE channel"
+ "01:47:47"
+ "Invalid LTM gamma curve 0x%08x\n"
+ "MULTICAM_MASTER_SLAVE_PARAMS_SET: totalSlaves=%u previewMasterCh=%u statsMasterCh=%u out of range (chTot=%zu)\n"
- "22:24:17"
```
