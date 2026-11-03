## libcorecrypto.dylib

> `/usr/lib/system/libcorecrypto.dylib`

```diff

-2109.40.22.0.0
-  __TEXT.__text: 0x8c408
+2109.60.2.0.0
+  __TEXT.__text: 0x8c420
   __TEXT.__cstring: 0x5a03
   __TEXT.__const: 0x204e8
   __TEXT.__fips_hmacs: 0x20

   - /usr/lib/system/libsystem_platform.dylib
   - /usr/lib/system/libsystem_pthread.dylib
   - /usr/lib/system/libsystem_trace.dylib
-  Functions: 2656
+  Functions: 2655
   Symbols:   2969
   CStrings:  537
 
Functions:
~ _ccder_decode_rsa_pub : 264 -> 292
~ _ccn_add1_ws : 40 -> 44
- sub_1d38b7760
- _ccpad_pkcs7_ecb_decrypt
~ _ccsigma_session_clear : 84 -> 72
- _ccpad_pkcs7_decrypt
~ _ccaes_ecb_decrypt : 856 -> 860
+ _ccpad_pkcs7_ecb_decrypt
+ _ccpad_pkcs7_decrypt
```
