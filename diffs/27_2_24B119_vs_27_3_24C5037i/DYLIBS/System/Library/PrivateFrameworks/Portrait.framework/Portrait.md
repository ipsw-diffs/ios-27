## Portrait

> `/System/Library/PrivateFrameworks/Portrait.framework/Portrait`

```diff

-560.40.5.0.0
-  __TEXT.__text: 0x93e14
+560.60.5.0.0
+  __TEXT.__text: 0x94110
   __TEXT.__delay_helper: 0x264
   __TEXT.__objc_methlist: 0x9af4
-  __TEXT.__const: 0x20af0
+  __TEXT.__const: 0x20b00
   __TEXT.__cstring: 0x5329
-  __TEXT.__oslogstring: 0x5ff3
+  __TEXT.__oslogstring: 0x6023
   __TEXT.__gcc_except_tab: 0x1b00
   __TEXT.__ustring: 0x30
   __TEXT.__unwind_info: 0x2088

   __AUTH_CONST.__auth_got: 0x0
   __DATA.__objc_ivar: 0x18a4
   __DATA.__data: 0x18
-  __DATA.__bss: 0x2bc
+  __DATA.__bss: 0x2c4
   __DATA_DIRTY.__objc_data: 0x3570
   __DATA_DIRTY.__data: 0x798
   __DATA_DIRTY.__bss: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3973
-  Symbols:   6787
-  CStrings:  1554
+  Functions: 3974
+  Symbols:   6789
+  CStrings:  1555
 
Symbols:
+ ___62-[PTTimedRenderingMetadataVersion2 initWithData:minorVersion:]_block_invoke
+ _initWithData:minorVersion:.onceToken
Functions:
~ +[PTRaytracingUtils createFocusObject:anamorphicFactor:radialObstructionFactor:colorSize:circleOfConfusionReference:fNumberLimitWeight:enableFocalLengthLimits:] : 744 -> 896
+ ___62-[PTTimedRenderingMetadataVersion2 initWithData:minorVersion:]_block_invoke
~ -[PTMonocularDisparityProvider disparityForColorBuffer:timedRenderingMetadata:time:outputBuffer:] : 256 -> 352
~ ___69-[PTCinematographyScript loadWithAsset:changesDictionary:completion:]_block_invoke.53 : 1884 -> 1972
~ -[PTTimedRenderingMetadataVersion2 initWithData:minorVersion:] : 636 -> 892
CStrings:
+ "Repairing adaptive overscan visCropFactor %f %f"
```
