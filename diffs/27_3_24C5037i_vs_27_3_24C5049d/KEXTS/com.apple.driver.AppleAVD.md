## com.apple.driver.AppleAVD

> `com.apple.driver.AppleAVD`

```diff

-995.0.0.0.0
-  __TEXT.__os_log: 0x1d318
+996.0.0.0.0
+  __TEXT.__os_log: 0x1d452
   __TEXT.__cstring: 0x8588
   __TEXT.__const: 0xf53cc
-  __TEXT_EXEC.__text: 0x68a1c
+  __TEXT_EXEC.__text: 0x68cb4
   __TEXT_EXEC.__auth_stubs: 0x6f0
   __DATA.__data: 0x1334
   __DATA.__common: 0x78

   __DATA_CONST.__auth_ptr: 0x10
   Functions: 2328
   Symbols:   0
-  CStrings:  1794
+  CStrings:  1796
 
Functions:
~ __ZN10CAvdApComm14validateFieldsEPhj : 324 -> 464
~ __ZN13PriorityQueue24insertDecodeFrameCommandEP8sPQEntry : 604 -> 672
~ sub_fffffe0008745768 -> sub_fffffe0008735968 : 716 -> 832
~ sub_fffffe00087464e0 -> sub_fffffe0008736754 : 400 -> 508
~ sub_fffffe000874f68c -> sub_fffffe000873f96c : 716 -> 832
~ __ZN15CAvdApCommViola18patchSliceDataSizeEPh28_DecryptSliceDataSizePatcherj : 716 -> 832
CStrings:
+ "AppleAVD: ERROR: %s(): Invalid workOffset=%u, numWorks=%u\n"
+ "AppleAVD: ERROR: %s(): Validation failed - buffer codec %u, session codec %u\n"
```
