## adc-silenus-v5x.im4p

> `Firmware/isp_bni/adc-silenus-v5x.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA.__data_copy`
- `__DATA._fwinfo`
- `__DATA._rtk_mtab`
- `__DATA.__chain_starts`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0xb5c200
-  __TEXT.__const: 0x8b7b10
-  __TEXT.__cstring: 0xaf29d
+  __TEXT.__text: 0xb5d27c
+  __TEXT.__const: 0x8b7b14
+  __TEXT.__cstring: 0xaf77e
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __TEXT.__eh_frame: 0x1bc
-  __DATA.__const: 0x62c58
+  __DATA.__const: 0x62c80
   __DATA._rtk_heap: 0x1000
   __DATA.__data: 0xfc2f8
   __DATA._rtk_power: 0x3f8

   __DATA.__chain_starts: 0x28
   __DATA.__mod_init_func: 0x8
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x5b2af8
-  Functions: 9886
+  __DATA.__zerofill: 0x5aeaf8
+  Functions: 9887
   Symbols:   0
-  CStrings:  19053
+  CStrings:  19081
 
CStrings:
+ "23:03:09"
+ "CISP_CMD_APPLE_MULTI_CHS_COMBINED_AF_WINDOW_PARAM_SET: Invalid chBitMask 0x%x, chTot %zu\n"
+ "CISP_CMD_APPLE_MULTI_CHS_COMBINED_AF_WINDOW_PARAM_SET: Invalid totalNumAFParamWin %u, max allowed %d\n"
+ "CISP_CMD_CH_MULTICAM_AE_WINDOW_PARAM_SET: Invalid chId %u at %u, chTot %zu\n"
+ "CISP_CMD_CH_MULTICAM_CAMERA_CONTROL_ROI_SET: Invalid chId %u at %u, chTot %zu\n"
+ "CISP_CMD_CH_MULTICAM_COMBINED_AF_WINDOW_PARAM_SET: Invalid chId %u numWin %u at %u, chTot %zu\n"
+ "MULTICAM_MASTER_SLAVE_PARAMS_SET: totalSlaves %u exceeds MAX_CH_PER_SYNCGROUP %d, rejecting\n"
+ "Quark isn't ready for start %llu, %u, pending %u, waited %llu us, serviced %u"
+ "StatsMasterSet: chId %d out of range (0..%d)"
+ "[%lu]: VIO LACC-match config alloc failed (%u)"
+ "[%lu]: VIO action config alloc failed (%u)"
+ "[%lu]: VIO config channel out of range"
+ "[%lu]: VIO operation config alloc failed (%u)"
+ "[%s] CH = 0x%zx VIO config size %u inconsistent with insize %u, rejecting"
+ "[%s] CMD = %#04x [%s]: chId %u mode %d out of range\n"
+ "bvc8"
+ "byc8"
+ "ch %zu: DUAL_PRIME pool drain timeout (%zu/%zu)"
+ "ch %zu: DUAL_PRIME_STILL pool drain timeout (%zu/%zu)"
+ "ch %zu: SLAVE_SHARE pool drain timeout (%zu/%zu)"
+ "ch %zu: raw pool drain timeout (%zu/%zu)"
+ "ch %zu: still raw pool drain timeout (%zu/%zu)"
+ "craw"
+ "pWinSet->winID >= CISP_APPLE_AE_WIN_0"
+ "raw10"
+ "raw12"
+ "raw14"
+ "raw16"
+ "raw8"
+ "rgp0"
- "01:47:47"
- "Quark isn't ready for start %llu, %u"
```
