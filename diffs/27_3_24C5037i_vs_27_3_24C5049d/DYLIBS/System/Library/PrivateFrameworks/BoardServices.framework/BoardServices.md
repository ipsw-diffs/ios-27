## BoardServices

> `/System/Library/PrivateFrameworks/BoardServices.framework/BoardServices`

```diff

 827.2.3.0.0
-  __TEXT.__text: 0x8007c
+  __TEXT.__text: 0x8009c
   __TEXT.__objc_methlist: 0x255c
   __TEXT.__const: 0x1af8
   __TEXT.__constg_swiftt: 0x94c
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[BSXPCServiceConnection activeMessageBatch] : 96 -> 92
~ -[BSXPCServiceConnection _lock_disconnect] : 464 -> 460
~ -[BSXPCServiceConnection shouldSendMessage:] : 1164 -> 1160
~ -[BSXPCServiceConnection sendBarrierBlock:] : 840 -> 836
~ sub_18fc4ad30 -> sub_18fd0cd20 : 324 -> 360
~ sub_18fc5d77c -> sub_18fd1f790 : 116 -> 128
```
