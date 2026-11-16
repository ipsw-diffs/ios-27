## ScreenReaderCore

> `/System/Library/PrivateFrameworks/ScreenReaderCore.framework/ScreenReaderCore`

```diff

-285.0.10.0.0
-  __TEXT.__text: 0x252c4
+285.0.20.0.0
+  __TEXT.__text: 0x25974
   __TEXT.__objc_methlist: 0x2b0c
-  __TEXT.__cstring: 0x290d
-  __TEXT.__const: 0x798
+  __TEXT.__cstring: 0x2a11
+  __TEXT.__const: 0x7a8
   __TEXT.__ustring: 0x2a
+  __TEXT.__oslogstring: 0x1aa
   __TEXT.__gcc_except_tab: 0x1d0
-  __TEXT.__oslogstring: 0x136
   __TEXT.__dlopen_cstrs: 0x4f
-  __TEXT.__unwind_info: 0xa48
+  __TEXT.__unwind_info: 0xa50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_superrefs: 0x150
   __DATA_CONST.__objc_arraydata: 0x238
   __DATA_CONST.__got: 0x2d8
-  __AUTH_CONST.__const: 0x220
-  __AUTH_CONST.__cfstring: 0x4b60
+  __AUTH_CONST.__const: 0x240
+  __AUTH_CONST.__cfstring: 0x4cc0
   __AUTH_CONST.__objc_const: 0x4340
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x50

   __AUTH_CONST.__auth_got: 0x690
   __DATA.__objc_ivar: 0x2d4
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x1f0
+  __DATA.__bss: 0x200
   __DATA.__common: 0x38
   __DATA_DIRTY.__objc_data: 0x1130
   __DATA_DIRTY.__data: 0x2f0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 944
-  Symbols:   2035
-  CStrings:  648
+  Functions: 947
+  Symbols:   2039
+  CStrings:  662
 
Symbols:
+ _SCRCGestureLog
+ _SCRCGestureLog.Log
+ _SCRCGestureLog.onceToken
+ ___SCRCGestureLog_block_invoke
Functions:
~ -[SCRCGestureFactory _updateTapState] : 392 -> 508
+ _SCRCGestureLog
~ -[SCRCGestureFactory _enterTrackingMode:] : 152 -> 276
~ -[SCRCGestureFactory _handleSplitEvent:] : 1420 -> 1684
~ -[SCRCGestureFactory handleGestureEvent:] : 620 -> 860
~ -[SCRCGestureFactory _down:] : 1376 -> 1644
~ -[SCRCGestureFactory _drag:] : 2940 -> 3196
~ -[SCRCGestureFactory _up] : 376 -> 664
+ ___SCRCGestureLog_block_invoke
+ _SCRCDebugPrint.cold.1
CStrings:
+ "Cancel Event"
+ "Ignoring cancel after lift, tap count: %lu, factory: %p"
+ "SCRCGesture"
+ "Tap canceled: %@, tap count: %lu, fingers: %lu, factory: %p"
+ "_enterTrackingMode"
+ "fingers not related"
+ "horizontal flick"
+ "split fast track"
+ "split tap done"
+ "starting a split tap session"
+ "stolen by another gesture"
+ "unable to get finger information"
+ "vertical flick"
+ "wandered off pad and could not come back on"
```
