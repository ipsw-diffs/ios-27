## companiond

> `/usr/libexec/companiond`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`

```diff

-524.11.6.0.0
+524.11.10.0.0
   __TEXT.__text: 0x8dc2c
   __TEXT.__auth_stubs: 0x2d50
   __TEXT.__objc_stubs: 0x45a0

   __TEXT.__swift5_protos: 0x4
   __TEXT.__gcc_except_tab: 0x1c50
   __TEXT.__ustring: 0x40
-  __TEXT.__unwind_info: 0x25b0
+  __TEXT.__unwind_info: 0x25a8
   __TEXT.__eh_frame: 0x4eb8
   __DATA_CONST.__const: 0x2580
   __DATA_CONST.__cfstring: 0x1ce0
Functions:
~ sub_10002b5fc : 20 -> 108
~ sub_10002b6e8 -> sub_10002b740 : 108 -> 132
~ sub_10002b754 -> sub_10002b7c4 : 132 -> 20
```
