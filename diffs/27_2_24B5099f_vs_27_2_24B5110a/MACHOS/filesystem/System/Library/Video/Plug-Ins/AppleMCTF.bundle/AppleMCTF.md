## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-913.63.1.0.0
-  __TEXT.__text: 0x89228
+913.64.1.0.0
+  __TEXT.__text: 0x89294
   __TEXT.__auth_stubs: 0xdc0
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x28d9b
+  __TEXT.__cstring: 0x28dcb
   __TEXT.__const: 0x22a98
   __TEXT.__gcc_except_tab: 0x62c
   __TEXT.__objc_methname: 0xb

   - /usr/lib/libobjc.A.dylib
   Functions: 678
   Symbols:   346
-  CStrings:  3474
+  CStrings:  3475
 
Functions:
~ sub_eb8 : 4856 -> 4884
~ sub_21b0 -> sub_21cc : 4588 -> 4616
~ sub_339c -> sub_33d4 : 7120 -> 7148
~ sub_3568c -> sub_356e0 : 1008 -> 1004
~ sub_48090 -> sub_480e0 : 11216 -> 11224
~ sub_4c574 -> sub_4c5cc : 7768 -> 7784
~ sub_7cf90 -> sub_7cff8 : 40 -> 44
CStrings:
+ "01:15:54"
+ "913.64.1"
+ "MachThreadPriorityForThreadEmittingFrames = %d\n"
+ "Oct 10 2026"
- "20:41:26"
- "913.63.1"
- "Sep 27 2026"
```
