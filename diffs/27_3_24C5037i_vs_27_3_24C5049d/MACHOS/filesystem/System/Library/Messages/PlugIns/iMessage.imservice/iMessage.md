## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/iMessage`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1491.300.43.0.0
-  __TEXT.__text: 0x120a74
-  __TEXT.__auth_stubs: 0x2750
-  __TEXT.__objc_stubs: 0xfb20
+1491.300.74.0.0
+  __TEXT.__text: 0x1211b4
+  __TEXT.__auth_stubs: 0x2760
+  __TEXT.__objc_stubs: 0xfb40
   __TEXT.__objc_methlist: 0x38f8
   __TEXT.__const: 0x16c8
-  __TEXT.__gcc_except_tab: 0x9880
+  __TEXT.__gcc_except_tab: 0x98e0
   __TEXT.__cstring: 0x4479
-  __TEXT.__oslogstring: 0x1d02b
+  __TEXT.__oslogstring: 0x1d0db
   __TEXT.__objc_classname: 0x9af
-  __TEXT.__objc_methname: 0x16eaf
+  __TEXT.__objc_methname: 0x16f0f
   __TEXT.__objc_methtype: 0x3b78
   __TEXT.__ustring: 0x4
   __TEXT.__swift5_typeref: 0xf86

   __TEXT.__swift5_builtin: 0x78
   __TEXT.__swift5_mpenum: 0x38
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x2ee8
+  __TEXT.__unwind_info: 0x2ef8
   __TEXT.__eh_frame: 0x1e48
-  __DATA_CONST.__const: 0x5730
-  __DATA_CONST.__cfstring: 0x3f60
+  __DATA_CONST.__const: 0x5760
+  __DATA_CONST.__cfstring: 0x3f80
   __DATA_CONST.__objc_classlist: 0x168
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0xe0

   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x60
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA_CONST.__auth_got: 0x13b8
-  __DATA_CONST.__got: 0x13a0
+  __DATA_CONST.__auth_got: 0x13c0
+  __DATA_CONST.__got: 0x13a8
   __DATA_CONST.__auth_ptr: 0x3d8
   __DATA.__objc_const: 0x4dc8
-  __DATA.__objc_selrefs: 0x46a8
+  __DATA.__objc_selrefs: 0x46b0
   __DATA.__objc_ivar: 0x29c
   __DATA.__objc_data: 0x1138
   __DATA.__data: 0x12f0

   - /System/Library/PrivateFrameworks/FTServices.framework/FTServices
   - /System/Library/PrivateFrameworks/IDS.framework/IDS
   - /System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation
-  - /System/Library/PrivateFrameworks/IMCore.framework/IMCore
   - /System/Library/PrivateFrameworks/IMDPersistence.framework/IMDPersistence
   - /System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore
   - /System/Library/PrivateFrameworks/IMFoundation.framework/IMFoundation

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 2661
-  Symbols:   995
-  CStrings:  5659
+  Symbols:   996
+  CStrings:  5664
 
Symbols:
+ _objc_sync_enter
+ _objc_sync_exit
- _IMChatRegistryLogHandle
Functions:
~ sub_4d90 -> sub_4d38 : 1356 -> 1372
~ __ReplaceExtensionPayloadDataWithAttachmentForIncomingMessage : 1264 -> 1268
~ sub_241e8 -> sub_241a4 : 9852 -> 9856
~ sub_26e30 -> sub_26df0 : 9284 -> 9288
~ sub_2e4cc -> sub_2e490 : 536 -> 540
~ sub_3954c -> sub_39514 : 1884 -> 1904
~ sub_48fc0 -> sub_48f9c : 9212 -> 9216
~ sub_56250 -> sub_56230 : 4996 -> 5020
~ sub_5a93c -> sub_5a934 : 6908 -> 7112
~ sub_67484 -> sub_67548 : 1992 -> 2084
~ sub_67c4c -> sub_67d6c : 28 -> 144
~ sub_67c68 -> sub_67dfc : 28 -> 580
~ sub_68fb8 -> sub_69374 : 1280 -> 1336
~ sub_69f44 -> sub_6a338 : 148 -> 160
~ sub_69fd8 -> sub_6a3d8 : 440 -> 456
~ sub_6a434 -> sub_6a844 : 352 -> 364
~ sub_6a594 -> sub_6a9b0 : 640 -> 800
~ sub_7c644 -> sub_7cb00 : 2536 -> 2540
~ sub_ae7c4 -> sub_aec84 : 268 -> 292
~ sub_ae988 -> sub_aee60 : 268 -> 292
~ sub_aea94 -> sub_aef84 : 320 -> 356
~ sub_b17a0 -> sub_b1cb4 : 116 -> 128
~ sub_d066c -> sub_d0b8c : 1580 -> 1636
~ sub_d0c98 -> sub_d11f0 : 5364 -> 5436
~ sub_d27dc -> sub_d2d7c : 1296 -> 1364
~ sub_d2cec -> sub_d32d0 : 1636 -> 1656
~ sub_d3ea8 -> sub_d44a0 : 1900 -> 1896
~ sub_d4614 -> sub_d4c08 : 212 -> 216
~ sub_d6f98 -> sub_d7590 : 504 -> 532
~ sub_d7190 -> sub_d77a4 : 284 -> 320
~ sub_d7470 -> sub_d7aa8 : 264 -> 288
~ sub_d7e10 -> sub_d8460 : 304 -> 328
~ sub_e490c -> sub_e4f74 : 308 -> 332
~ sub_f1b78 -> sub_f21f8 : 1916 -> 1932
~ sub_1164f0 -> sub_116b80 : 480 -> 508
~ sub_1166d0 -> sub_116d7c : 284 -> 320
~ sub_11f31c -> sub_11f9ec : 132 -> 156
CStrings:
+ "Acquisition failure for message %@; failing send."
+ "Not sending gradient for message %@, attachment acquisition failed. %@"
+ "Sending scheduled message update flags 0x%lx for message %@"
+ "Transfer %@ on message %@ finished acquisition without a file. %@"
+ "guidsForStoredAttachmentPayloadData:messageGUID:isIncoming:"
+ "guidsForStoredAttachmentPayloadDataURLs:messageGUID:isIncoming:"
+ "sU"
+ "scheduledMessageUpdateFlagsForDateEdited:"
- "Unrecoverable acquisition failure for message %@; failing send."
- "guidsForStoredAttachmentPayloadData:messageGUID:"
- "guidsForStoredAttachmentPayloadDataURLs:messageGUID:"
```
