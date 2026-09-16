## IMTransferAgent

> `/System/Library/PrivateFrameworks/IMTransferAgent.framework/IMTransferAgent`

```diff

-1491.100.1.2.25
-  __TEXT.__text: 0x16c1c
+1491.200.63.2.1
+  __TEXT.__text: 0x16d14
   __TEXT.__objc_methlist: 0xa84
   __TEXT.__const: 0x110
-  __TEXT.__gcc_except_tab: 0x1720
+  __TEXT.__gcc_except_tab: 0x1748
   __TEXT.__cstring: 0xbb3
-  __TEXT.__oslogstring: 0x2a69
+  __TEXT.__oslogstring: 0x2a99
   __TEXT.__unwind_info: 0x588
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd70
+  __DATA_CONST.__objc_selrefs: 0xd80
   __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__got: 0x390

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 250
-  Symbols:   263
-  CStrings:  352
+  Symbols:   264
+  CStrings:  353
 
Symbols:
+ _IMStringFromCommSafetyEnablementGroup
Functions:
~ sub_286c8f3f4 -> sub_28c67c3f4 : 2476 -> 2644
~ sub_286c8fea4 -> sub_28c67cf4c : 1184 -> 1192
~ sub_286c90344 -> sub_28c67d3f4 : 532 -> 536
~ sub_286c92970 -> sub_28c67fa24 : 1056 -> 1064
~ sub_286c999c0 -> sub_28c686a7c : 5536 -> 5596
CStrings:
+ "About to construct the nickname with contentSafetyEnablementGroup: %@"
+ "Avatar image safety check was skipped, comm safety check group setting: %@. Creating IMNicknameAvatarImage."
+ "Download %@ file size %llu -> request priority %ld"
+ "Wallpaper safety check was skipped, comm safety check group setting: %@. Creating IMWallpaper."
- "About to construct the nickname with contentSafetyEnablementGroup: %ld"
- "Avatar image safety check was skipped, comm safety check group setting: %ld. Creating IMNicknameAvatarImage."
- "Wallpaper safety check was skipped, comm safety check group setting: %ld. Creating IMWallpaper."
```
