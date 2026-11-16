## libfabric.dylib

> `/usr/lib/libfabric.dylib`

```diff

-21.0.0.0.0
-  __TEXT.__text: 0xaa00c
+23.0.0.0.0
+  __TEXT.__text: 0xa9fb8
   __TEXT.__const: 0xa28
-  __TEXT.__cstring: 0x18a60
+  __TEXT.__cstring: 0x18a33
   __TEXT.__oslogstring: 0x3ce6
   __TEXT.__unwind_info: 0x1820
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/librdma.dylib
   Functions: 3589
   Symbols:   3557
-  CStrings:  3824
+  CStrings:  3823
 
Functions:
~ _vrb_fini : 72 -> 68
~ _vrb_init : 1912 -> 1832
CStrings:
- "failed in OS specific device initialization\n"
```
