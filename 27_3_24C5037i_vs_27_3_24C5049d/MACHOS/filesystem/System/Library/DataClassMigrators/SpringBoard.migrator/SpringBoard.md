## SpringBoard

> `/System/Library/DataClassMigrators/SpringBoard.migrator/SpringBoard`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-4637.2.11.104.0
-  __TEXT.__text: 0xfb60
+4637.2.17.3.0
+  __TEXT.__text: 0xfc00
   __TEXT.__auth_stubs: 0x6c0
   __TEXT.__objc_stubs: 0x1d60
   __TEXT.__objc_methlist: 0x714
   __TEXT.__const: 0x140
-  __TEXT.__cstring: 0x1933
+  __TEXT.__cstring: 0x193e
   __TEXT.__objc_methname: 0x1db0
   __TEXT.__oslogstring: 0x179f
   __TEXT.__objc_classname: 0x141
   __TEXT.__objc_methtype: 0x389
   __TEXT.__gcc_except_tab: 0x14c
   __TEXT.__unwind_info: 0x2a8
-  __DATA_CONST.__const: 0x16d8
+  __DATA_CONST.__const: 0x16f8
   __DATA_CONST.__cfstring: 0xf20
   __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_catlist: 0x8

   __DATA.__objc_ivar: 0x5c
   __DATA.__objc_data: 0x2d0
   __DATA.__data: 0x128
-  __DATA.__bss: 0xa70
+  __DATA.__bss: 0xa80
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
   - /System/Library/Frameworks/CoreServices.framework/CoreServices

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 679
-  Symbols:   403
-  CStrings:  755
+  Functions: 682
+  Symbols:   404
+  CStrings:  756
 
Symbols:
+ _SBLogLockOnFold
CStrings:
+ "LockOnFold"
```
