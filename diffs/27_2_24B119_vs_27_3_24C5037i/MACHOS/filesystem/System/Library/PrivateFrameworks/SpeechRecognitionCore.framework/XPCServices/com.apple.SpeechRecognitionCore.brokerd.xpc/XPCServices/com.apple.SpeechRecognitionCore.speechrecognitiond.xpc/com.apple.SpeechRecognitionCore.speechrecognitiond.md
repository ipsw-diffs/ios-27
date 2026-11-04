## com.apple.SpeechRecognitionCore.speechrecognitiond

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/XPCServices/com.apple.SpeechRecognitionCore.brokerd.xpc/XPCServices/com.apple.SpeechRecognitionCore.speechrecognitiond.xpc/com.apple.SpeechRecognitionCore.speechrecognitiond`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-41.1.3.0.0
-  __TEXT.__text: 0xcdb58
-  __TEXT.__auth_stubs: 0x2960
+41.1.10.0.0
+  __TEXT.__text: 0xcdd44
+  __TEXT.__auth_stubs: 0x2950
   __TEXT.__objc_stubs: 0x3de0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x16fc

   __TEXT.__gcc_except_tab: 0xabd4
   __TEXT.__objc_methname: 0x51a5
   __TEXT.__cstring: 0x34a2
-  __TEXT.__oslogstring: 0x618e
+  __TEXT.__oslogstring: 0x624e
   __TEXT.__objc_classname: 0x596
   __TEXT.__objc_methtype: 0x11eb
   __TEXT.__dlopen_cstrs: 0x6a

   __TEXT.__swift_as_ret: 0x5c
   __TEXT.__swift_as_cont: 0x78
   __TEXT.__unwind_info: 0x4ba8
-  __TEXT.__eh_frame: 0x32ec
+  __TEXT.__eh_frame: 0x3304
   __DATA_CONST.__const: 0x79e0
   __DATA_CONST.__cfstring: 0x1ca0
   __DATA_CONST.__objc_classlist: 0xc8

   __DATA_CONST.__objc_arraydata: 0x80
   __DATA_CONST.__objc_dictobj: 0x50
   __DATA_CONST.__objc_intobj: 0xa8
-  __DATA_CONST.__auth_got: 0x14d0
+  __DATA_CONST.__auth_got: 0x14c8
   __DATA_CONST.__got: 0x820
   __DATA_CONST.__auth_ptr: 0x1d0
   __DATA.__objc_const: 0x2780

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 3725
-  Symbols:   1161
-  CStrings:  2257
+  Symbols:   1160
+  CStrings:  2259
 
Symbols:
- _swift_retain_x24
Functions:
~ sub_100068614 : 1176 -> 1412
~ sub_100068be0 -> sub_100068ccc : 132 -> 388
CStrings:
+ "SpeechAnalyzer setModules finished with SpeechDetector (%{bool,public}d) for %{public}@"
+ "SpeechAnalyzer setModules started with SpeechDetector (%{bool,public}d) for %{public}@"
```
