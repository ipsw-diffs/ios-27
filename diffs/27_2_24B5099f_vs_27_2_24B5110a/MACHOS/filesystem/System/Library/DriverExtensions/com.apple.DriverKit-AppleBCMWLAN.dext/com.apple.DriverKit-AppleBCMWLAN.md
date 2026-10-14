## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-1582.8.0.0.0
-  __TEXT.__text: 0x291d04
+1582.9.0.0.0
+  __TEXT.__text: 0x291dec
   __TEXT.__auth_stubs: 0x25c0
   __TEXT.__init_offsets: 0x1bc
-  __TEXT.__cstring: 0x834c7
+  __TEXT.__cstring: 0x834d7
   __TEXT.__const: 0x7f168
   __TEXT.__oslogstring: 0x1f27
-  __TEXT.__unwind_info: 0x5ff0
+  __TEXT.__unwind_info: 0x5ff8
   __TEXT.__eh_frame: 0x38
   __DATA_CONST.__const: 0x211c0
   __DATA_CONST.__osclassinfo: 0x388

   - /System/DriverKit/usr/lib/libc++.dylib
   Functions: 14198
   Symbols:   12073
-  CStrings:  13143
+  CStrings:  13144
 
Functions:
~ __ZN28AppleBCMWLANBusInterfacePCIe24PortErrorMsgHandler_ImplEP8OSActionP8OSNumberS3_P6OSData : 1076 -> 1108
~ __ZN28AppleBCMWLANBusInterfacePCIe24PortEventMsgHandlerGatedEjP8OSNumberP6OSData : 1576 -> 1612
~ __ZN28AppleBCMWLANBusInterfacePCIe24PortErrorMsgHandlerGatedEjP6OSData : 788 -> 856
~ __ZN28AppleBCMWLANBusInterfacePCIe25SetPowerStateGated_InvokeE5IORPCP15OSMetaClassBasePFiS2_10PowerStateE : 156 -> 204
~ __ZN28AppleBCMWLANBusInterfacePCIe29SetPowerStateGatedAMFM_InvokeE5IORPCP15OSMetaClassBasePFiS2_10PowerStateE : 156 -> 204
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1582.9\""
+ "AppleBCMWLANV3_driverkit-1582.9"
+ "Oct  3 2026 20:55:39"
+ "af/link timeout"
- "\"AppleBCMWLANV3_driverkit-1582.8\""
- "AppleBCMWLANV3_driverkit-1582.8"
- "Sep 26 2026 03:37:36"
```
