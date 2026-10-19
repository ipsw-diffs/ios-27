## AudioCodecs

> `/System/Library/Frameworks/AudioToolbox.framework/AudioCodecs`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 818.205.0.0.0
-  __TEXT.__text: 0x6967ec
+  __TEXT.__text: 0x69689c
   __TEXT.__realtime: 0x1254
   __TEXT.__const: 0x33e14c
   __TEXT.__cstring: 0xfe74
   __TEXT.__gcc_except_tab: 0x11fcc
-  __TEXT.__oslogstring: 0x1bbc3
+  __TEXT.__oslogstring: 0x1bc49
   __TEXT.__ustring: 0x20
   __TEXT.__unwind_info: 0x9c58
   __TEXT.__eh_frame: 0x6a8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 9826
+  Functions: 9827
   Symbols:   17169
-  CStrings:  3599
+  CStrings:  3600
 
Functions:
~ __ZN14APACHOADecoder10InitializeERK11ACParamListN4apac12observer_ptrINS3_10IASCConfigEEE : 7448 -> 7552
+ sub_1bd17e528
~ __ZN17HOASpatialDecoder11DeserializeER16TBitstreamReaderIjE : 6516 -> 6580
CStrings:
+ "%25s:%-5d  Failed to initialize: mNumHOAcoeffs exceeds kMaxNumSCs_DynSelSCs4EachSB array dimension in HOASpatialDecoder::Initialize()"
+ "17:02:43"
- "22:15:45"
```
