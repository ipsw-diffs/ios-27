## adc-silenus-v5x.im4p

> `Firmware/isp_bni/adc-silenus-v5x.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA.__data_copy`
- `__DATA._fwinfo`
- `__DATA._rtk_smp_main`
- `__DATA._rtk_mtab`
- `__DATA.__chain_starts`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0xb5b300
-  __TEXT.__const: 0x8b47f8
-  __TEXT.__cstring: 0xaeca3
+  __TEXT.__text: 0xb5b7b8
+  __TEXT.__const: 0x8b7990
+  __TEXT.__cstring: 0xaf116
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __TEXT.__eh_frame: 0x1bc
-  __DATA.__const: 0x62a48
+  __DATA.__const: 0x62b98
   __DATA._rtk_heap: 0x1000
   __DATA.__data: 0xfc2f8
   __DATA._rtk_power: 0x3f8

   __DATA.__chain_starts: 0x28
   __DATA.__mod_init_func: 0x8
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x5b6af8
+  __DATA.__zerofill: 0x5b2af8
   Functions: 9883
   Symbols:   0
-  CStrings:  19031
+  CStrings:  19046
 
Functions:
~ sub_2dd30 : 11204 -> 11208
~ sub_32fcc -> sub_32fd0 : 22012 -> 22016
~ sub_e0554 -> sub_e055c : 19252 -> 19144
~ sub_e9fb8 -> sub_e9f54 : 4064 -> 3900
~ sub_457508 -> sub_457400 : 2232 -> 2900
~ sub_524734 -> sub_5248c8 : 6268 -> 6368
~ sub_5fcf84 -> sub_5fd17c : 4012 -> 4120
~ sub_612d8c -> sub_612ff0 : 180 -> 196
~ sub_612e40 -> sub_6130b4 : 440 -> 516
~ sub_86f0b8 -> sub_86f378 : 3124 -> 3308
~ sub_86fcec -> sub_870064 : 7260 -> 7424
~ sub_9bb248 -> sub_9bb664 : 3500 -> 3524
~ sub_9c11cc -> sub_9c1600 : 21904 -> 21920
~ sub_9e87f0 -> sub_9e8c34 : 1532 -> 1652
~ sub_b033c0 -> sub_b0387c : 188 -> 180
~ sub_b4a6e8 -> sub_b4ab9c : 328 -> 332
~ sub_b5b1c8 -> sub_b5b680 : 312 -> 320
CStrings:
+ "21:38:13"
+ "IC[%zu] frameSkip set to 1 at ic stopping\n"
+ "Summerville_CHS_B1_v016_mode001_60fps_pri_p0a_4896x4896_sec_skip_raw10"
+ "Summerville_CHS_B1_v016_mode002_sifr_30fps_pri_p0a_4896x4896_sec_p0a_4896x4896_raw10"
+ "Summerville_CHS_B1_v016_mode003_sifr_30fps_pri_p0a_4896x4896_sec_q0a_2448x2448_raw10"
+ "Summerville_CHS_B1_v016_mode009_120fps_pri_q0a_2448x2448_sec_skip_raw10"
+ "Summerville_CHS_B1_v016_mode011_sifr_60fps_pri_q0a_2448x2448_sec_q0a_2448x2448_raw10"
+ "Summerville_CHS_B1_v016_mode061_60fps_pri_p0a_3680x4896_sec_skip_raw10"
+ "Summerville_CHS_B1_v016_mode063_sifr_30fps_pri_p0a_3680x4896_sec_p0a_3680x4896_raw10"
+ "Summerville_CHS_B1_v016_mode065_60fps_pri_p0a_3072x4896_sec_skip_raw10"
+ "Summerville_CHS_B1_v016_mode068_120fps_pri_q0a_2448x1392_sec_skip_raw10"
+ "Summerville_CHS_B1_v016_mode069_120fps_pri_q0a_1392x2448_sec_skip_raw10"
+ "Summerville_CHS_B1_v016_mode071_sifr_60fps_pri_q0a_1392x2448_sec_q0a_1392x2448_raw10"
+ "Summerville_CHS_B1_v016_mode075_sifr_60fps_pri_q0a_1840x2448_sec_q0a_1840x2448_raw10"
+ "Summerville_CHS_B1_v016_mode077_sifr_60fps_pri_p0a_2400x4224_sec_s0a_600x1056_raw10"
+ "Summerville_CHS_B1_v016_mode090_sifr_60fps_pri_q0a_2448x2448_sec_s0a_1224x1224_raw10"
+ "ch%zu wasPaused %d now %f RVsync %f FVsync %f\n"
- "20:40:26"
- "ch %zu FC: %d Full Res Host Meta Data buffer not available"
```
