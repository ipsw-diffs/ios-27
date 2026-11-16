## AVFAudio

> `/System/Library/Frameworks/AVFAudio.framework/AVFAudio`

```diff

-794.303.0.0.0
-  __TEXT.__text: 0x1143bc
+794.305.1.0.0
+  __TEXT.__text: 0x114440
   __TEXT.__realtime: 0x1d20
   __TEXT.__objc_methlist: 0x5b2c
   __TEXT.__dlopen_cstrs: 0xa9

   __TEXT.__swift5_mpenum: 0x18
   __TEXT.__swift5_types2: 0x4
   __TEXT.__gcc_except_tab: 0x125e0
-  __TEXT.__oslogstring: 0x1830e
+  __TEXT.__oslogstring: 0x18319
   __TEXT.__unwind_info: 0x6328
   __TEXT.__eh_frame: 0x2e0
   __TEXT.__objc_stubs: 0x0

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 4137
-  Symbols:   8068
+  Symbols:   8069
   CStrings:  3377
 
Symbols:
+ _AVAudioSessionInterruptionEndLikelyToBeResumableKey
Functions:
~ -[AVAudioIONode setVoiceProcessingEnabled:error:] : 2664 -> 2668
~ -[AVAudioEngine mainMixerNode] : 380 -> 484
~ sub_1c1b50e5c -> sub_1c2106ec8 : 132 -> 156
CStrings:
+ "%25s:%-5d Engine#%p: error: couldn't connect mixer to output node, format: %s"
- "%25s:%-5d Engine#%p: error: couldn't connect mixer to output node!"
```
