## IdleTimerHosting

> `/System/Library/PrivateFrameworks/IdleTimerHosting.framework/IdleTimerHosting`

```diff

 41.0.0.0.0
-  __TEXT.__text: 0x2cf4
+  __TEXT.__text: 0x2cdc
   __TEXT.__objc_methlist: 0x62c
   __TEXT.__const: 0x80
   __TEXT.__cstring: 0x50a
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[ITAttentionAwareIdleTimer setDescriptor:resettingTimer:] : 388 -> 384
~ -[ITAttentionAwareIdleTimer descriptor] : 84 -> 80
~ -[ITAttentionAwareIdleTimer reset] : 152 -> 148
~ -[ITAttentionAwareIdleTimer client:attentionLostTimeoutDidExpire:forContext:] : 168 -> 164
~ -[ITAttentionAwareIdleTimer clientDidReset:forUserAttentionEvent:withContext:] : 204 -> 200
~ -[ITAttentionAwareIdleTimer _context] : 84 -> 80
```
