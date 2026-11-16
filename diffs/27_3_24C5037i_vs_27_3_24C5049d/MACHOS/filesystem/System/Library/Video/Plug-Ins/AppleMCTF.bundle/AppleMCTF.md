## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-913.64.1.0.0
-  __TEXT.__text: 0x89294
+913.72.1.0.0
+  __TEXT.__text: 0x892cc
   __TEXT.__auth_stubs: 0xdc0
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0x4
Functions:
~ sub_2600c : 3640 -> 3652
~ sub_79ab0 -> sub_79abc : 756 -> 800
CStrings:
+ "21:54:08"
+ "913.72.1"
+ "Nov 10 2026"
- "01:49:05"
- "913.64.1"
- "Oct 24 2026"
```
