## coreidvd

> `/usr/libexec/coreidvd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-9.107.1.0.0
-  __TEXT.__text: 0x7002a0
+9.108.0.0.0
+  __TEXT.__text: 0x700448
   __TEXT.__auth_stubs: 0xd460
   __TEXT.__objc_stubs: 0x70e0
   __TEXT.__objc_methlist: 0x213c

   __TEXT.__swift5_acfuncs: 0x64
   __TEXT.__swift5_entry: 0x8
   __TEXT.__gcc_except_tab: 0xac
-  __TEXT.__unwind_info: 0x16b48
+  __TEXT.__unwind_info: 0x16710
   __TEXT.__eh_frame: 0x48210
   __DATA_CONST.__const: 0x255c0
   __DATA_CONST.__cfstring: 0xa0

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 18976
+  Functions: 18977
   Symbols:   6003
   CStrings:  8519
 
Symbols:
+ _$s13CoreIDVShared16BiometricsHelperC25deviceInformationProviderAcA06DeviceF9Providing_p_tcfc
- _$s13CoreIDVShared16BiometricsHelperCACycfc
```
