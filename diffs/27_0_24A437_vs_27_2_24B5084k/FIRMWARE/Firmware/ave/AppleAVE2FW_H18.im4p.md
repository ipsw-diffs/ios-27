## AppleAVE2FW_H18.im4p

> `Firmware/ave/AppleAVE2FW_H18.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA.__const`

```diff

-  __TEXT.__text: 0x1172a4
-  __TEXT.__const: 0x17084
-  __TEXT.__cstring: 0x19815
+  __TEXT.__text: 0x117228
+  __TEXT.__const: 0x17094
+  __TEXT.__cstring: 0x19818
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x18
   __DATA._rtk_patchbay: 0x211
-  __DATA.__data: 0x1588
+  __DATA.__data: 0x1590
   __DATA._rtk_mtab: 0x2d0
   __DATA.__const: 0x4728
   __DATA._rtk_power: 0x3b8
Functions:
~ __ZN14CAVCController16PipePrepareParamEPv : 4464 -> 4472
~ __ZN15CHEVCController16PipePrepareParamEPv : 7928 -> 7936
~ __ZN15CHEVCController22InitEncodingParametersEPv : 29196 -> 29040
~ __Z14AVE_CSC_Uninitv : 184 -> 200
~ sub_e6b84 -> sub_e6b08 : 952 -> 964
~ _pow : 1216 -> 1200
~ sub_10d8c4 -> sub_10d844 : 384 -> 388
~ sub_117164 -> sub_1170e8 : 320 -> 328
CStrings:
+ "%s:%d stopping CtxSched time out %d %d 0x%x"
+ "9013.48.1"
- "%s:%d stopping CtxSched time out %d 0x%x"
- "9013.45.2"
```
