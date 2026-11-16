## csfdiagnose

> `/usr/bin/csfdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 301.24.2.1.0
-  __TEXT.__text: 0x15bf4
+  __TEXT.__text: 0x15c7c
   __TEXT.__auth_stubs: 0xd10
   __TEXT.__objc_stubs: 0x180
   __TEXT.__const: 0x15a2
Functions:
~ sub_100009ff8 : 1052 -> 1068
~ sub_100010f28 -> sub_100010f38 : 268 -> 292
~ sub_10001125c -> sub_100011284 : 280 -> 316
~ sub_100011374 -> sub_1000113c0 : 280 -> 316
~ sub_10001148c -> sub_1000114fc : 264 -> 288
```
