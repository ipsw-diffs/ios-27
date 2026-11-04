## apfs_condenser

> `/System/Library/Filesystems/apfs.fs/apfs_condenser`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.42.1.0.0
-  __TEXT.__text: 0x4d3c8
+3288.60.7.0.0
+  __TEXT.__text: 0x4d354
   __TEXT.__auth_stubs: 0x780
-  __TEXT.__cstring: 0xf7c4
+  __TEXT.__cstring: 0xf816
   __TEXT.__const: 0x220
-  __TEXT.__unwind_info: 0x840
+  __TEXT.__unwind_info: 0x850
   __DATA_CONST.__const: 0x8f8
   __DATA_CONST.__cfstring: 0x120
   __DATA_CONST.__auth_got: 0x3c0

   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libutil.dylib
-  Functions: 682
+  Functions: 685
   Symbols:   134
-  CStrings:  1266
+  CStrings:  1267
 
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
+ "3288.60.7"
- "3288.42.1"
```
