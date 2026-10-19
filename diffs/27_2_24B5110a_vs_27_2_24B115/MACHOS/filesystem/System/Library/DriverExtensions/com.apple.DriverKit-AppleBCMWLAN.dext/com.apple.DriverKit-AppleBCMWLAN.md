## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 1582.9.0.0.0
-  __TEXT.__text: 0x291dec
+  __TEXT.__text: 0x2920c8
   __TEXT.__auth_stubs: 0x25c0
   __TEXT.__init_offsets: 0x1bc
-  __TEXT.__cstring: 0x834d7
+  __TEXT.__cstring: 0x83612
   __TEXT.__const: 0x7f168
   __TEXT.__oslogstring: 0x1f27
   __TEXT.__unwind_info: 0x5ff8

   - /System/DriverKit/System/Library/PrivateFrameworks/IOFileValidation.framework/IOFileValidation
   - /System/DriverKit/System/Library/PrivateFrameworks/OLYHALDriverKit.framework/OLYHALDriverKit
   - /System/DriverKit/usr/lib/libc++.dylib
-  Functions: 14198
+  Functions: 14201
   Symbols:   12073
-  CStrings:  13144
+  CStrings:  13148
 
CStrings:
+ "Oct  3 2026 15:40:08"
+ "[dk] %s@%d:ERROR: NAN attribute header runs past the end of the attribute list\n"
+ "[dk] %s@%d:ERROR: NAN attribute length %u exceeds the remaining attribute list\n"
+ "[dk] %s@%d:ERROR: NAN shared key descriptor body %u too short, minimum %u\n"
+ "[dk] %s@%d:ERROR: NAN shared key descriptor key data length %u exceeds body %u\n"
- "Oct  3 2026 20:55:39"
```
