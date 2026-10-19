## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8150.RELEASE.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA.__auth_ptr`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`

```diff

 1777.40.37.0.0
-  __TEXT.__text: 0xe9d9ac
+  __TEXT.__text: 0xe9d904
   __TEXT.__lcxx_override: 0xe4
   __TEXT.__cstring: 0xb24d1
   __TEXT.__const: 0x1ba5c4

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x140
-  __TEXT.__eh_frame: 0x82fdc
+  __TEXT.__eh_frame: 0x82fd4
   __DATA.__TIGHTBEAM_VT: 0x1530
   __DATA.__TIGHTBEAM: 0x590
   __DATA.__const: 0x106140
Functions:
~ sub_85766b0 : 844 -> 752
~ sub_8577060 -> sub_8577004 : 1448 -> 1452
~ sub_8bcb14c -> sub_8bcb0f4 : 1444 -> 1436
~ sub_8c49990 -> sub_8c49930 : 904 -> 808
~ sub_8c4a3ac -> sub_8c4a2ec : 1276 -> 1300
CStrings:
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Wed Oct  7 23:12:48 PDT 2026; root:AppleImage4_exclavecore-374~19427/ExclaveImage4/RELEASE_ARM64E"
+ "Build Date: Wed Oct  7 22:49:55 PDT 2026"
+ "ExclaveOS Image4 Framework Version 7.0.0: Wed Oct  7 23:12:48 PDT 2026; root:AppleImage4_exclavecore-374~19427/ExclaveImage4/RELEASE_ARM64E"
+ "Wed Oct  7 23:46:57 PDT 2026"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Thu Oct  8 00:11:07 PDT 2026; root:AppleImage4_exclavecore-374~19439/ExclaveImage4/RELEASE_ARM64E"
- "Build Date: Wed Oct  7 23:45:10 PDT 2026"
- "ExclaveOS Image4 Framework Version 7.0.0: Thu Oct  8 00:11:07 PDT 2026; root:AppleImage4_exclavecore-374~19439/ExclaveImage4/RELEASE_ARM64E"
- "Thu Oct  8 00:48:12 PDT 2026"
```
