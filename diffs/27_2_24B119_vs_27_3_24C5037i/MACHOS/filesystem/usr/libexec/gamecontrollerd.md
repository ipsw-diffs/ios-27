## gamecontrollerd

> `/usr/libexec/gamecontrollerd`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-14.1.2.0.0
-  __TEXT.__text: 0x207c
+14.2.2.0.0
+  __TEXT.__text: 0x20f4
   __TEXT.__auth_stubs: 0x380
-  __TEXT.__objc_stubs: 0x6e0
-  __TEXT.__objc_methlist: 0x4dc
+  __TEXT.__objc_stubs: 0x740
+  __TEXT.__objc_methlist: 0x4e4
   __TEXT.__objc_classname: 0xfb
-  __TEXT.__objc_methname: 0xcd5
+  __TEXT.__objc_methname: 0xcfd
   __TEXT.__objc_methtype: 0x6e8
   __TEXT.__cstring: 0x316
   __TEXT.__oslogstring: 0x19e

   __DATA_CONST.__auth_got: 0x1d0
   __DATA_CONST.__got: 0xd8
   __DATA.__objc_const: 0xc60
-  __DATA.__objc_selrefs: 0x3e8
+  __DATA.__objc_selrefs: 0x3f0
   __DATA.__objc_ivar: 0x54
   __DATA.__objc_data: 0xf0
   __DATA.__data: 0x308

   - /System/Library/PrivateFrameworks/GameControllerSettings.framework/GameControllerSettings
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 72
+  Functions: 73
   Symbols:   94
-  CStrings:  294
+  CStrings:  295
 
CStrings:
+ "_ensureGCPreferencesPaneVisibleIfNeeded"
```
