## Security

> `/System/Library/Frameworks/Security.framework/Security`

```diff

-62460.40.74.0.0
-  __TEXT.__text: 0x182790
+62460.40.78.0.0
+  __TEXT.__text: 0x1827ac
   __TEXT.__lazy_helpers: 0x54
   __TEXT.__objc_methlist: 0x67cc
-  __TEXT.__const: 0x1b9c8
+  __TEXT.__const: 0x1b9e8
   __TEXT.__dlopen_cstrs: 0xbc
   __TEXT.__cstring: 0x1965d
   __TEXT.__gcc_except_tab: 0x7db4

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 7143
-  Symbols:   13685
+  Symbols:   13686
   CStrings:  5772
 
Symbols:
+ _SecKeyCopySystemKey.gsmakObjectIDBytes
Functions:
~ sub_18954fba8 -> sub_189550ba8 : 60 -> 64
~ _SecKeyCopySystemKey : 684 -> 708
```
