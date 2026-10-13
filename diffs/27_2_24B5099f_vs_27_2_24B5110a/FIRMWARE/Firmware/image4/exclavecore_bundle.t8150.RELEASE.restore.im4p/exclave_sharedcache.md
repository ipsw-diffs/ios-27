## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8150.RELEASE.restore.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__TEXT.__eh_frame`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__auth_ptr`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`

```diff

-1777.40.34.0.0
-  __TEXT.__text: 0x5feb44
+1777.40.37.0.0
+  __TEXT.__text: 0x5fef9c
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0x50e61
+  __TEXT.__cstring: 0x50f61
   __TEXT.__const: 0x124124
   __TEXT.__swift5_typeref: 0x1452c
-  __TEXT.__swift5_reflstr: 0x13508
+  __TEXT.__swift5_reflstr: 0x13528
   __TEXT.__swift5_assocty: 0x7d10
-  __TEXT.__swift5_fieldmd: 0x1cdf4
-  __TEXT.__constg_swiftt: 0x28aa8
+  __TEXT.__swift5_fieldmd: 0x1ce0c
+  __TEXT.__constg_swiftt: 0x28b08
   __TEXT.__swift5_protos: 0x998
   __TEXT.__swift5_proto: 0x3e98
   __TEXT.__swift5_types: 0x2524

   __TEXT.__eh_frame: 0x35fe8
   __DATA.__TIGHTBEAM_VT: 0x8a0
   __DATA.__TIGHTBEAM: 0x238
-  __DATA.__const: 0x3e798
-  __DATA.__data: 0x19150
+  __DATA.__const: 0x3e7a8
+  __DATA.__data: 0x191a0
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1a84b
   __DATA.__auth_ptr: 0x2498

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0xe6d0
+  __DATA.__bss: 0xe6e0
   __DATA.__common: 0x72a
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x6810

   __DATA_CONST.__mod_term_func: 0x0
   Functions: 23176
   Symbols:   1
-  CStrings:  7436
+  CStrings:  7442
 
Functions:
~ sub_8290b9c : 992 -> 1024
~ sub_8290f7c -> sub_8290f9c : 104 -> 156
~ sub_8291088 -> sub_82910dc : 272 -> 348
~ sub_8291198 -> sub_8291238 : 2024 -> 2448
~ sub_8292bc4 -> sub_8292e0c : 1204 -> 1472
~ sub_8293078 -> sub_82933cc : 360 -> 456
~ sub_8298e6c -> sub_8299220 : 128 -> 156
~ sub_82a5abc -> sub_82a5e8c : 228 -> 260
~ sub_82a5c54 -> sub_82a6044 : 180 -> 212
~ sub_85b8e94 -> sub_85b92a4 : 808 -> 904
~ sub_85b9850 -> sub_85b9cc0 : 1092 -> 1068
CStrings:
+ "Start not allowed: camera disabled by EDT policy"
+ "Status not allowed: camera disabled by EDT policy"
+ "])\n  deviceStateDisplayWake: allowance="
+ "fpwm-frequency-hz"
+ "policy-sil-disable"
+ "sil-disable-config"
+ "sil-disable-offset"
- "])\n  medinaStateDisplayWake: allowance="
```
