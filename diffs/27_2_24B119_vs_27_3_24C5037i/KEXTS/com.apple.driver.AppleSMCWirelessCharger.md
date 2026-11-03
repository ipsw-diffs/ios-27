## com.apple.driver.AppleSMCWirelessCharger

> `com.apple.driver.AppleSMCWirelessCharger`

```diff

-155.40.5.0.0
+155.60.4.0.0
   __TEXT.__const: 0x8c
-  __TEXT.__cstring: 0x3850
+  __TEXT.__cstring: 0x38a0
   __TEXT.__os_log: 0x5f0
-  __TEXT_EXEC.__text: 0x11604
+  __TEXT_EXEC.__text: 0x11758
   __TEXT_EXEC.__auth_stubs: 0x5e0
   __DATA.__data: 0xcd
   __DATA.__common: 0x90

   __DATA_CONST.__auth_ptr: 0x8
   Functions: 212
   Symbols:   0
-  CStrings:  470
+  CStrings:  472
 
Functions:
~ sub_fffffe00096b9d48 -> sub_fffffe0009783ae8 : 5668 -> 5804
~ sub_fffffe00096c9cf4 -> sub_fffffe0009793b1c : 2136 -> 2336
~ sub_fffffe00096ca54c -> sub_fffffe000979443c : 112 -> 116
CStrings:
+ "%s: Failed to set WAEQ to %d (ret=%d)\n"
+ "chg-disable-inductive-fw-reload-on-crash"
```
