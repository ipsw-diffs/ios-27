## AirPlayMirroringModule

> `/System/Library/ControlCenter/Bundles/AirPlayMirroringModule.bundle/AirPlayMirroringModule`

```diff

-4026.300.11.0.0
-  __TEXT.__text: 0xf820
+4026.310.18.1.0
+  __TEXT.__text: 0x10158
   __TEXT.__objc_methlist: 0x56c
   __TEXT.__cstring: 0x1b6
-  __TEXT.__const: 0x288
+  __TEXT.__const: 0x298
   __TEXT.__gcc_except_tab: 0xc0
-  __TEXT.__oslogstring: 0x5a2
-  __TEXT.__swift5_typeref: 0x248
+  __TEXT.__oslogstring: 0x691
+  __TEXT.__swift5_typeref: 0x254
   __TEXT.__constg_swiftt: 0x16c
   __TEXT.__swift5_reflstr: 0x116
   __TEXT.__swift5_fieldmd: 0xe8

   __DATA_CONST.__objc_selrefs: 0x548
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x10
-  __DATA_CONST.__got: 0x250
+  __DATA_CONST.__got: 0x260
   __AUTH_CONST.__const: 0x3a0
   __AUTH_CONST.__cfstring: 0x160
   __AUTH_CONST.__objc_const: 0xe38
-  __AUTH_CONST.__auth_got: 0x758
+  __AUTH_CONST.__auth_got: 0x770
   __AUTH.__objc_data: 0x48
   __DATA.__objc_ivar: 0x18
-  __DATA.__data: 0x200
+  __DATA.__data: 0x220
   __DATA_DIRTY.__objc_data: 0x258
   __DATA_DIRTY.__data: 0x270
   __DATA_DIRTY.__common: 0x38

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 285
-  Symbols:   209
-  CStrings:  51
+  Symbols:   211
+  CStrings:  52
 
Symbols:
+ _swift_release_n
+ _swift_retain_n
Functions:
~ sub_24a9cb628 -> sub_24bb9c628 : 1480 -> 3408
~ sub_24a9cdfb8 -> sub_24bb9f740 : 116 -> 128
~ sub_24a9d1570 -> sub_24bba2d04 : 84 -> 72
~ sub_24a9d15c4 -> sub_24bba2d4c : 4 -> 84
~ sub_24a9d15c8 -> sub_24bba2da0 : 72 -> 4
~ sub_24a9d2880 -> sub_24bba4014 : 1828 -> 1976
~ sub_24a9d3794 -> sub_24bba4fbc : 1648 -> 1732
~ sub_24a9d5c6c -> sub_24bba74e8 : 1608 -> 1796
CStrings:
+ "[%{public}s] didBeginContextMenuPresentation"
+ "[%{public}s] didEndContextMenuPresentation"
+ "[%{public}s] interactionCompleted item:%{public}s"
+ "[%{public}s] interactionFailed item:%{public}s"
+ "[%{public}s] itemsUpdated count:%{public}ld hasSelected:%{bool,public}d pendingCount:%{public}ld"
+ "[%{public}s] routingModeChanged from:%{public}s to:%{public}s"
+ "[%{public}s] startMirroring item:%{public}s"
+ "[%{public}s] startMirroring item:%{public}s - blocked by external display"
+ "[%{public}s] stopMirroringNoSelectedItem: no selected item found in active session"
+ "[%{public}s] update items count: %{public}ld, additionalItems: %{bool,public}d discovery mode: %{public}s"
+ "[%{public}s] updatePendingItemIdentifiers - interaction delayed for %{public}s"
- "[%s] didBeginContextMenuPresentation"
- "[%s] didEndContextMenuPresentation"
- "[%s] interactionCompleted item:%{public}s"
- "[%s] interactionFailed item:%{public}s"
- "[%s] itemsUpdated count:%ld hasSelected:%{bool}d pendingCount:%ld"
- "[%s] routingModeChanged from:%s to:%s"
- "[%s] startMirroring item:%s"
- "[%s] startMirroring item:%s - blocked by external display"
- "[%s] stopMirroringNoSelectedItem: no selected item found in active session"
- "[%s] updatePendingItemIdentifiers - interaction delayed for %s"
```
