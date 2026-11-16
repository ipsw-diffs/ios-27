## AddDevicesToAutomatedDeviceEnrollmentExtension

> `/System/Library/Frameworks/AutomatedDeviceEnrollment.framework/PlugIns/AddDevicesToAutomatedDeviceEnrollmentExtension.appex/AddDevicesToAutomatedDeviceEnrollmentExtension`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-42.0.0.0.0
-  __TEXT.__text: 0x97668
+42.60.2.0.0
+  __TEXT.__text: 0x97830
   __TEXT.__auth_stubs: 0x25e0
   __TEXT.__objc_stubs: 0x1100
   __TEXT.__objc_methlist: 0x55c

   __TEXT.__objc_methname: 0x24a5
   __TEXT.__objc_methtype: 0x873
   __TEXT.__oslogstring: 0x21a0
-  __TEXT.__cstring: 0x4175
+  __TEXT.__cstring: 0x4275
   __TEXT.__swift5_capture: 0xb24
   __TEXT.__swift_as_entry: 0x178
   __TEXT.__swift_as_ret: 0x184

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 3054
   Symbols:   284
-  CStrings:  962
+  CStrings:  964
 
Functions:
~ sub_10000c1d8 : 116 -> 128
~ sub_10000c4ac -> sub_10000c4b8 : 280 -> 316
~ sub_10000c5c4 -> sub_10000c5f4 : 480 -> 524
~ sub_10000c7a4 -> sub_10000c800 : 264 -> 288
~ sub_100017848 -> sub_1000178bc : 2996 -> 3004
~ sub_100019088 -> sub_100019104 : 1904 -> 1924
~ sub_10003c83c -> sub_10003c8cc : 1420 -> 1456
~ sub_10003d6a0 -> sub_10003d754 : 484 -> 528
~ sub_10003d884 -> sub_10003d964 : 268 -> 292
~ sub_10007afec -> sub_10007b0e4 : 260 -> 404
~ sub_10008464c -> sub_1000847d4 : 528 -> 540
~ sub_100087e94 -> sub_100088028 : 1300 -> 1352
CStrings:
+ "Message for the alert shown when the device cannot be enrolled because no WLAN or network configuration is available to share."
+ "There is no WLAN or network configuration to share with the device. Please check your network selection and try again."
```
