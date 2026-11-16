## libsystem_platform.dylib

> `/usr/lib/system/libsystem_platform.dylib`

```diff

-402.40.3.0.0
-  __TEXT.__text: 0x6eec
+402.60.2.0.0
+  __TEXT.__text: 0x6fc8
   __TEXT.__resolver_help: 0x288
   __TEXT.__const: 0xb0
   __TEXT.__cstring: 0x815

   __TPRO_CONST.__data: 0x8
   - /usr/lib/system/libdyld.dylib
   - /usr/lib/system/libsystem_kernel.dylib
-  Functions: 287
-  Symbols:   322
+  Functions: 291
+  Symbols:   326
   CStrings:  67
 
Symbols:
+ _os_unfair_recursive_lock_assert_not_owned_by_self
+ _os_unfair_recursive_lock_assert_owned_by_self
+ _os_unfair_recursive_lock_lock
+ _os_unfair_recursive_lock_lock_with_flags
```
