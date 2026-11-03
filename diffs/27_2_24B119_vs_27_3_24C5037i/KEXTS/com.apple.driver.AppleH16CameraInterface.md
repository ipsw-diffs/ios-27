## com.apple.driver.AppleH16CameraInterface

> `com.apple.driver.AppleH16CameraInterface`

```diff

-6.104.0.0.0
+6.201.0.0.0
   __TEXT.__const: 0xa1b0
-  __TEXT.__cstring: 0x19ff7
-  __TEXT.__os_log: 0x15c13
-  __TEXT_EXEC.__text: 0x9dcf8
+  __TEXT.__cstring: 0x1a044
+  __TEXT.__os_log: 0x15c60
+  __TEXT_EXEC.__text: 0x9ddc8
   __TEXT_EXEC.__auth_stubs: 0x10e0
   __DATA.__data: 0x2a8
   __DATA.__common: 0x4f0

   __DATA_CONST.__auth_ptr: 0x18
   Functions: 1822
   Symbols:   0
-  CStrings:  2399
+  CStrings:  2400
 
Functions:
~ __ZN13AppleH16CamIn21ISP_SendBuffers_gatedEP26H16ISPSendBufferArgsStructjP12IOUserClientPy : 3344 -> 3396
~ __ZN13AppleH16CamIn43ISP_CompleteFirmwareWorkProcessorItem_gatedEPyPvjP4task : 2052 -> 2208
CStrings:
+ "AppleH16CamIn:%s - numWorkItemsInProgress underflow guarded for wakePort=%p\n"
```
