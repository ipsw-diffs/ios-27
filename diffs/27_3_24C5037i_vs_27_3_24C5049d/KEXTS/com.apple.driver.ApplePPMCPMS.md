## com.apple.driver.ApplePPMCPMS

> `com.apple.driver.ApplePPMCPMS`

```diff

-1191.60.10.0.0
+1191.60.11.0.0
   __TEXT.__const: 0x1150
   __TEXT.__cstring: 0xf905
-  __TEXT.__os_log: 0x3f85
-  __TEXT_EXEC.__text: 0x54c88
+  __TEXT.__os_log: 0x3fa9
+  __TEXT_EXEC.__text: 0x54cf8
   __TEXT_EXEC.__auth_stubs: 0x7c0
-  __DATA.__data: 0x164
+  __DATA.__data: 0x160
   __DATA.__common: 0x500
-  __DATA.__bss: 0x1c8
+  __DATA.__bss: 0x1c0
   __DATA_CONST.__mod_init_func: 0xe0
   __DATA_CONST.__mod_term_func: 0xb0
   __DATA_CONST.__const: 0x5b70
Functions:
~ __ZN35ApplePPMCPMSSystemCapabilityMonitor25consumeInternalSourceDataEP12OSDictionary : 3228 -> 3340
~ sub_fffffe000943ac90 -> sub_fffffe00093a7cd0 : 188 -> 196
~ sub_fffffe000944ee78 -> sub_fffffe00093bbec0 : 744 -> 736
CStrings:
+ "%s::%s:failed to get array entry for bank %u from key kBankBatteryDataDict\n"
+ "%s::%s:failed to get array entry for bank %u from key kLPEMDict\n"
- "%s::%s:failed to get array from key kBankBatteryDataDict\n"
- "%s::%s:failed to get array from key kLPEMDict\n"
```
