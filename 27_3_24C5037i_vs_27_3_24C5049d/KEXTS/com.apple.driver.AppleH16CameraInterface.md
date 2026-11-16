## com.apple.driver.AppleH16CameraInterface

> `com.apple.driver.AppleH16CameraInterface`

```diff

-6.201.0.0.0
+6.203.1.0.0
   __TEXT.__const: 0xa1b0
-  __TEXT.__cstring: 0x1a044
-  __TEXT.__os_log: 0x15c60
-  __TEXT_EXEC.__text: 0x9ddc8
+  __TEXT.__cstring: 0x1a07e
+  __TEXT.__os_log: 0x15cb0
+  __TEXT_EXEC.__text: 0x9df34
   __TEXT_EXEC.__auth_stubs: 0x10e0
   __DATA.__data: 0x2a8
   __DATA.__common: 0x4f0

   __DATA_CONST.__auth_ptr: 0x18
   Functions: 1822
   Symbols:   0
-  CStrings:  2400
+  CStrings:  2403
 
Functions:
~ __ZN13AppleH16CamIn26ISP_InitialSensorDetectionEv : 12352 -> 12468
~ sub_fffffe0008ee3098 -> sub_fffffe0008e4fdfc : 36 -> 24
~ __ZN23AppleH16CamInUserClient4initEP4taskP12OSDictionary : 1148 -> 1228
~ sub_fffffe0008ee45b8 -> sub_fffffe0008e51360 : 24 -> 204
CStrings:
+ "AppleH16CamInUserClient:%s - Process %s (pid %d) not permitted to load setfile\n"
+ "ISP_LoadSetfile"
+ "com.apple.private.camera.isp-setfile-load"
```
