## CoreGPSTest.dylib

> `/System/Library/PrivateFrameworks/CoreGPSTest.framework/CoreGPSTest.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-367.0.1.0.0
-  __TEXT.__text: 0x66dac
+367.0.2.0.0
+  __TEXT.__text: 0x66e18
   __TEXT.__init_offsets: 0xc
   __TEXT.__objc_methlist: 0x164
   __TEXT.__const: 0x6570
   __TEXT.__gcc_except_tab: 0x3974
-  __TEXT.__oslogstring: 0xaa6e
+  __TEXT.__oslogstring: 0xaa81
   __TEXT.__constg_swiftt: 0x408
   __TEXT.__swift5_typeref: 0x18a
   __TEXT.__swift5_reflstr: 0x8f

   - /usr/lib/swift/libswiftos.dylib
   Functions: 2684
   Symbols:   4318
-  CStrings:  1370
+  CStrings:  1371
 
Functions:
~ __ZN7GnssHal12GpioEmbedded12setResetHighEv : 104 -> 212
CStrings:
+ "#gpio,setResetHigh"
+ "#version,CoreGPS-367.0.2,machContSec,%{public}.3f,BuildTime,{Oct 10 2026,01:18:38}"
+ "01:18:35"
+ "01:21:19"
+ "Oct 10 2026"
- "#version,CoreGPS-367.0.1,machContSec,%{public}.3f,BuildTime,{Sep 27 2026,23:16:15}"
- "23:16:12"
- "23:19:36"
- "Sep 27 2026"
```
