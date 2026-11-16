## libEmbeddedSystemAUs.dylib

> `/System/Library/Frameworks/AudioToolbox.framework/libEmbeddedSystemAUs.dylib`

```diff

-1638.304.1.0.0
-  __TEXT.__text: 0xd14ac
-  __TEXT.__realtime: 0x38dd0
+1638.308.0.0.0
+  __TEXT.__text: 0xd1460
+  __TEXT.__realtime: 0x38db4
   __TEXT.__const: 0xb328
   __TEXT.__dlopen_cstrs: 0x2c1
   __TEXT.__gcc_except_tab: 0x77bc
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ __ZNK13SampleManager15SearchForSampleEm : 256 -> 252
~ __ZN13SampleManager12InsertSampleEmP6Sample : 280 -> 276
~ __ZN13SampleManager13AcquireSampleEm : 380 -> 376
~ __ZN13SampleManager9GetSampleEm : 256 -> 252
~ __ZN13SampleManager13ReleaseSampleEm : 728 -> 720
~ __ZN17AudioStreamerImplD0Ev : 208 -> 204
~ __ZN17AudioStreamerImpl16sIOWorkerProcessEPv : 1156 -> 1152
~ __ZN13SampleManager7DestroyEv : 380 -> 376
~ __ZNK11GlobalState4SaveER14CACFDictionary : 2588 -> 2580
~ __ZN14DLSBankManager7AddBankEPK7__CFURLb : 1088 -> 1076
~ __ZN14DLSBankManager11AcquireBankEPK10__CFString : 520 -> 516
~ __ZN14DLSBankManager11ReleaseBankEPK10__CFString : 812 -> 808
~ __ZN10FileSample12ReadFromFileExyPv : 372 -> 368
~ __ZN9AUVoiceIO28InitializeEncoderAndMetadataERK24CAStreamBasicDescriptionj : 6876 -> 6872
~ __ZN15InstrumentState7CleanupEv : 1288 -> 1284
~ __ZN11SamplerNote6RenderEyjPP15AudioBufferListjj : 5480 -> 5476
~ __ZN9VoiceZonedlEPv : 204 -> 200
~ __ZN9VoiceZone12NewVoiceZoneEP11SamplerNoteP9ZoneStateffj : 5264 -> 5256
~ __ZN17AudioStreamerImpl18HandleInvalidCacheEy : 280 -> 276
~ __ZN17AudioStreamerImpl12RefillBufferEj : 844 -> 840
~ __ZN16VPEncoderWrapper11SetPropertyEjPKvj : 620 -> 616
```
