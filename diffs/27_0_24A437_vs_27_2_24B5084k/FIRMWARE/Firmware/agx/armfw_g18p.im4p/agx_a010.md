## agx_a010

> `Firmware/agx/armfw_g18p.im4p/agx_a010`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3cc14
+  __TEXT.__text: 0x3cc28
   __TEXT.__gxf_code: 0x4f40
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x1068
+  __TEXT.__const: 0x107d
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
   __TEXT.__cstring: 0x23fc
Functions:
~ sub_fffffc000000b3d8 : 316 -> 332
~ sub_fffffc0000033f9c -> sub_fffffc0000033fac : 384 -> 388
~ sub_fffffc000003cad0 -> sub_fffffc000003cae4 : 324 -> 332
CStrings:
+ "Sep  4 2026 23:17:32"
- "Aug 13 2026 21:40:48"
```
