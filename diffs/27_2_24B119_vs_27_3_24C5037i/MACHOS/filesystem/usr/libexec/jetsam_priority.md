## jetsam_priority

> `/usr/libexec/jetsam_priority`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

-10848.40.6.0.0
-  __TEXT.__text: 0xb414
+10848.60.3.0.0
+  __TEXT.__text: 0xb4c8
   __TEXT.__auth_stubs: 0x610
   __TEXT.__objc_stubs: 0x1e0
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x89
-  __TEXT.__gcc_except_tab: 0xd20
-  __TEXT.__cstring: 0x135f
+  __TEXT.__gcc_except_tab: 0xd34
+  __TEXT.__cstring: 0x139c
   __TEXT.__objc_methname: 0x14a
   __TEXT.__unwind_info: 0x2e0
   __DATA_CONST.__const: 0x178

   __DATA_CONST.__got: 0xf8
   __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_selrefs: 0x78
-  __DATA.__data: 0x50
+  __DATA.__data: 0xb4
   __DATA.__bss: 0xa0
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/libobjc.A.dylib
   Functions: 104
   Symbols:   135
-  CStrings:  196
+  CStrings:  199
 
Symbols:
+ _getopt_long
+ _objc_release_x24
- _getopt
- _objc_release_x25
Functions:
~ sub_100000b7c : 28260 -> 28436
~ sub_100008258 -> sub_100008308 : 580 -> 604
~ sub_10000bbac -> sub_10000bc74 : 184 -> 164
CStrings:
+ "   --coalitions: Print process coalitions.\n"
+ "   --freezer: Print frozen info\n"
+ ":kd:n:hcelifs:w:rxp:z::"
+ "coalitions"
+ "freezer"
- "   -g: Print process coalitions.\n"
- ":kd:n:hcelifgs:w:rxp:z::"
```
