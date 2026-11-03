## AccountsDaemon

> `/System/Library/PrivateFrameworks/AccountsDaemon.framework/AccountsDaemon`

```diff

-1125.0.0.0.0
-  __TEXT.__text: 0x840b8
+1127.0.0.0.0
+  __TEXT.__text: 0x842c0
   __TEXT.__objc_methlist: 0x3c8c
   __TEXT.__const: 0xd0a
-  __TEXT.__oslogstring: 0x916a
+  __TEXT.__oslogstring: 0x925a
   __TEXT.__cstring: 0x3e03
   __TEXT.__gcc_except_tab: 0x2504
   __TEXT.__dlopen_cstrs: 0x66

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 2431
+  Functions: 2432
   Symbols:   3215
-  CStrings:  1190
+  CStrings:  1192
 
Functions:
~ -[ACDAccountStore _setAccountManagedObjectRelationships:withAccount:oldAccount:error:] : 3372 -> 3840
~ -[ACDAccountStore _setAccountManagedObjectRelationships:withAccount:oldAccount:error:].cold.6 : 80 -> 52
+ -[ACDAccountStore _setAccountManagedObjectRelationships:withAccount:oldAccount:error:].cold.7
CStrings:
+ "\"%@: client %@ saved a credential against a stale username (%@, persisted is %@). Storing under the persisted username.\""
+ "\"Unable to build an account from the database for %@; falling back to the client's account to save its credential\""
```
