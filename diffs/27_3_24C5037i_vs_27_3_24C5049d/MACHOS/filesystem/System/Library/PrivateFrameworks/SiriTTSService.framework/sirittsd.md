## sirittsd

> `/System/Library/PrivateFrameworks/SiriTTSService.framework/sirittsd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_capture`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3610.9.1.0.0
-  __TEXT.__text: 0x5d68c
-  __TEXT.__auth_stubs: 0x2fe0
+3610.14.1.0.0
+  __TEXT.__text: 0x5d9e8
+  __TEXT.__auth_stubs: 0x3020
   __TEXT.__objc_stubs: 0xe60
   __TEXT.__objc_methlist: 0x650
   __TEXT.__const: 0x1240
   __TEXT.__swift5_typeref: 0xb2a
   __TEXT.__cstring: 0x8a3
-  __TEXT.__oslogstring: 0x25bd
+  __TEXT.__oslogstring: 0x25fd
   __TEXT.__swift5_entry: 0x8
   __TEXT.__swift5_capture: 0xb1c
   __TEXT.__objc_methtype: 0x9fd

   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x58
-  __DATA_CONST.__auth_got: 0x17f8
+  __DATA_CONST.__auth_got: 0x1818
   __DATA_CONST.__got: 0x900
   __DATA_CONST.__auth_ptr: 0x4e0
   __DATA.__objc_const: 0x1990

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 1103
-  Symbols:   1160
-  CStrings:  594
+  Symbols:   1164
+  CStrings:  595
 
Symbols:
+ _$s14SiriTTSService13MobileGestaltV9isHomePodSbvgZ
+ _$s14SiriTTSService24TTSFeatureFlagsContainerC6sharedACvgZ
+ _$s14SiriTTSService24TTSFeatureFlagsContainerCMa
+ _$s14SiriTTSService27SynthesizingRequestProtocolPAAE19containsAudioPromptSbvg
+ _$s14SiriTTSService9PCCClientC14isPCCSupported12featureFlagsSbAA010TTSFeatureG9ContainerC_tFZ
- _$s14SiriTTSService9PCCClientC14isPCCSupportedSbvgZ
Functions:
~ sub_100003a7c : 3352 -> 3360
~ sub_100004f60 -> sub_100004f68 : 1544 -> 1816
~ sub_100005710 -> sub_100005828 : 4328 -> 4456
~ sub_1000080c0 -> sub_100008258 : 272 -> 296
~ sub_1000082e0 -> sub_100008490 : 3008 -> 3024
~ sub_10000b344 -> sub_10000b504 : 116 -> 128
~ sub_10000e940 -> sub_10000eb0c : 3804 -> 3832
~ sub_10000f9c0 -> sub_10000fba8 : 4184 -> 4400
~ sub_100017dd8 -> sub_100018098 : 124 -> 148
~ sub_1000200dc -> sub_1000203b4 : 1960 -> 1956
~ sub_1000216b4 -> sub_100021988 : 876 -> 916
~ sub_100021a20 -> sub_100021d1c : 816 -> 840
~ sub_100022e88 -> sub_10002319c : 3232 -> 3228
~ sub_10003a9b4 -> sub_10003acc4 : 1060 -> 1040
~ sub_10003add8 -> sub_10003b0d4 : 868 -> 888
~ sub_10003b164 -> sub_10003b474 : 932 -> 936
~ sub_10005a8b4 -> sub_10005abc8 : 268 -> 292
~ sub_10005a9c0 -> sub_10005acec : 324 -> 360
~ sub_10005bcb8 -> sub_10005c008 : 1144 -> 1156
CStrings:
+ "#PrewarmRequest %llu skipping device engine prewarm since %s is preferred."
+ "PCC voice is not enabled due to audio prompt in text."
+ "PCC voice is not enabled since PCC is not supported on this platform."
- "#PrewarmRequest %llu skipping device engine prewarm since PCC is preferred."
- "PCC voice is not enabled due to disabled SiriTTSService/pcc feature."
```
