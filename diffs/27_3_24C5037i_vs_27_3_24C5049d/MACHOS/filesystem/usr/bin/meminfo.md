## meminfo

> `/usr/bin/meminfo`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1071.40.9.0.0
-  __TEXT.__text: 0x138f4
+  __TEXT.__text: 0x13a40
   __TEXT.__auth_stubs: 0xb10
   __TEXT.__objc_stubs: 0x100
   __TEXT.__const: 0x9b4
Functions:
~ sub_100004d14 : 280 -> 316
~ sub_100004e2c -> sub_100004e50 : 288 -> 320
~ sub_100007a08 -> sub_100007a4c : 268 -> 292
~ sub_100007b14 -> sub_100007b70 : 284 -> 320
~ sub_100007c30 -> sub_100007cb0 : 268 -> 292
~ sub_100007d3c -> sub_100007dd4 : 268 -> 292
~ sub_100007e48 -> sub_100007ef8 : 308 -> 332
~ sub_10000f0c4 -> sub_10000f18c : 260 -> 284
~ sub_10000fb24 -> sub_10000fc04 : 264 -> 288
~ sub_10000fc2c -> sub_10000fd24 : 280 -> 316
~ sub_10000fd44 -> sub_10000fe60 : 304 -> 328
~ sub_10000fe74 -> sub_10000ffa8 : 264 -> 288
```
