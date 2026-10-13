## com.apple.driver.AppleH16CameraInterface

> `com.apple.driver.AppleH16CameraInterface`

```diff

-6.103.0.0.0
+6.104.0.0.0
   __TEXT.__const: 0xa1b0
-  __TEXT.__cstring: 0x19f97
-  __TEXT.__os_log: 0x15bb4
-  __TEXT_EXEC.__text: 0x9dc84
+  __TEXT.__cstring: 0x19ff7
+  __TEXT.__os_log: 0x15c13
+  __TEXT_EXEC.__text: 0x9dcf8
   __TEXT_EXEC.__auth_stubs: 0x10e0
   __DATA.__data: 0x2a8
   __DATA.__common: 0x4f0

   __DATA_CONST.__auth_ptr: 0x18
   Functions: 1822
   Symbols:   0
-  CStrings:  2398
+  CStrings:  2399
 
Functions:
~ __ZN13AppleH16CamIn26processSharedMallocRequestEyyyPv : 1144 -> 1344
~ sub_fffffe0008e1d540 -> sub_fffffe0008e1f758 : 100 -> 104
~ sub_fffffe0008e1d5a4 -> sub_fffffe0008e1f7c0 : 100 -> 8
~ sub_fffffe0008e1d950 -> sub_fffffe0008e1fb10 : 136 -> 140
CStrings:
+ "1221211112112"
+ "AppleH16CamIn:%s - ERROR: ISP free request for address %#llx that it does not own - rejecting\n"
- "122121111211"
```
