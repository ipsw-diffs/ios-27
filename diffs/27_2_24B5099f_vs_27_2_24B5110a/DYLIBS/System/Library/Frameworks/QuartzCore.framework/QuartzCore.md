## QuartzCore

> `/System/Library/Frameworks/QuartzCore.framework/QuartzCore`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1223.10.16.0.0
-  __TEXT.__text: 0x4053a4
+1223.10.19.0.0
+  __TEXT.__text: 0x4053e0
   __TEXT.__objc_methlist: 0xbc94
   __TEXT.__const: 0x19c00
   __TEXT.__dlopen_cstrs: 0xe0
   __TEXT.__cstring: 0x29d4c
   __TEXT.__gcc_except_tab: 0xa09c
-  __TEXT.__oslogstring: 0x13a25
+  __TEXT.__oslogstring: 0x13a5f
   __TEXT.__unwind_info: 0x95c0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/libxml2.2.dylib
   Functions: 12863
   Symbols:   20010
-  CStrings:  8651
+  CStrings:  8652
 
Functions:
~ __ZN2CA12WindowServer12IOMFBDisplay13finish_updateEPNS_6Render6UpdateEjy : 19948 -> 19872
~ __ZN2CA12WindowServer13IOMFBFlipBook5_exitENS0_23FlipBookStateTransitionE : 384 -> 388
~ __ZN2CA12WindowServer8FlipBook5_exitENS0_23FlipBookStateTransitionE : 236 -> 368
CStrings:
+ "24B5104s"
+ "FlipBook::_exit from suspended, skip cancel (swapped %zu)"
- "24B5098u"
```
