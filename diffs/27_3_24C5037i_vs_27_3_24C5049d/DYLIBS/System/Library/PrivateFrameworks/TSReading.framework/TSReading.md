## TSReading

> `/System/Library/PrivateFrameworks/TSReading.framework/TSReading`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-801.0.0.0.0
-  __TEXT.__text: 0x340b48
+811.0.0.0.0
+  __TEXT.__text: 0x340c9c
   __TEXT.__objc_methlist: 0x34128
   __TEXT.__const: 0x4778
   __TEXT.__cstring: 0x48711

   __DATA_CONST.__got: 0x1e18
   __AUTH_CONST.__const: 0x2958
   __AUTH_CONST.__cfstring: 0x20940
-  __AUTH_CONST.__objc_const: 0x861f8
+  __AUTH_CONST.__objc_const: 0x86218
   __AUTH_CONST.__weak_auth_got: 0x38
   __AUTH_CONST.__objc_arrayobj: 0x990
   __AUTH_CONST.__objc_intobj: 0xb58

   __AUTH_CONST.__auth_got: 0x1a10
   __AUTH.__objc_data: 0x94c0
   __AUTH.__data: 0x50
-  __DATA.__objc_ivar: 0x34f8
+  __DATA.__objc_ivar: 0x34fc
   __DATA.__data: 0x5b98
   __DATA.__bss: 0x40c8
   __DATA.__common: 0x89

   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libxml2.2.dylib
   Functions: 20644
-  Symbols:   33149
+  Symbols:   33150
   CStrings:  7226
 
Symbols:
+ _OBJC_IVAR_$_TSDTextInputResponder._pendingFirstResponderHandOff
Functions:
~ -[TSDTextInputResponder p_setFirstResponderAfterDelay] : 52 -> 112
~ -[TSDTextInputResponder setEditor:] : 328 -> 456
~ -[TSDTextInputResponder cancelDelayedResponderChange] : 140 -> 156
~ -[TSDTextInputResponder forceDelayedResponderChange] : 156 -> 244
~ -[TSDTextInputResponder editorDidChangeSelection:withFlags:] : 408 -> 456
CStrings:
+ "Nov 10 2026"
- "Oct 23 2026"
```
