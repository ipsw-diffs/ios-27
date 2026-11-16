## BaseBoard

> `/System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard`

```diff

 827.2.3.0.0
-  __TEXT.__text: 0xa1bbc
+  __TEXT.__text: 0xa1bac
   __TEXT.__objc_methlist: 0x713c
   __TEXT.__const: 0x310
   __TEXT.__dlopen_cstrs: 0xe8
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[_BSCompoundAssertionAcquisitionReference invalidate] : 976 -> 972
~ -[BSCompoundAssertion acquireForReason:withContext:] : 1356 -> 1352
~ -[BSCompoundAssertion dealloc] : 440 -> 436
~ -[BSCompoundAssertion invalidate] : 120 -> 116
```
