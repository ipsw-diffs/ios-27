## MPSCore

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSCore.framework/MPSCore`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-130.1.4.0.0
-  __TEXT.__text: 0x94eac
+130.2.2.0.0
+  __TEXT.__text: 0x94f30
   __TEXT.__objc_methlist: 0x27fc
   __TEXT.__const: 0x2974
   __TEXT.__cstring: 0xa85d

   __DATA_CONST.__objc_classlist: 0x198
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1410
+  __DATA_CONST.__objc_selrefs: 0x1418
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x188
   __DATA_CONST.__got: 0x208

   __AUTH_CONST.__cfstring: 0x3900
   __AUTH_CONST.__objc_const: 0x52c8
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__auth_got: 0x4d8
+  __AUTH_CONST.__auth_got: 0x4d0
   __DATA.__objc_ivar: 0x32c
   __DATA.__data: 0x400
   __DATA.__common: 0x28

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1732
-  Symbols:   800
+  Symbols:   799
   CStrings:  901
 
Symbols:
+ __ZN10MPSLibrary13MPSKey_CreateEPK17PrivateKernelInfoRK23MPSFunctionConstantListb30MPSThreadGroupSizeMultipleType24MPSDriverCompilerOptions23MPSForwardProgressUsagePFvPS0_EP8NSStringmym
+ __ZN10MPSLibrary19CreateUberShaderKeyEP8NSStringRK23MPSFunctionConstantListyPFPU22objcproto11MTLFunction11objc_objectPU21objcproto10MTLLibrary11objc_objectPK13MPSKernelInfoS4_RK33MPSFunctionConstructorExtraParamsPP7NSErrorEy30MPSThreadGroupSizeMultipleType24MPSDriverCompilerOptions23MPSForwardProgressUsageP18MPSKernelDAGObjectS1_mP20MPSKernelUserDAGInfoP7NSArrayIS6_EPSR_ISO_Em
- __ZN10MPSLibrary13MPSKey_CreateEPK17PrivateKernelInfoRK23MPSFunctionConstantListb30MPSThreadGroupSizeMultipleType24MPSDriverCompilerOptions23MPSForwardProgressUsagePFvPS0_EP8NSStringmy
- __ZN10MPSLibrary19CreateUberShaderKeyEP8NSStringRK23MPSFunctionConstantListyPFPU22objcproto11MTLFunction11objc_objectPU21objcproto10MTLLibrary11objc_objectPK13MPSKernelInfoS4_RK33MPSFunctionConstructorExtraParamsPP7NSErrorEy30MPSThreadGroupSizeMultipleType24MPSDriverCompilerOptions23MPSForwardProgressUsageP18MPSKernelDAGObjectS1_mP20MPSKernelUserDAGInfoP7NSArrayIS6_EPSR_ISO_E
- _objc_retain_x28
Functions:
~ sub_24e8df848 -> sub_252689848 : 2960 -> 2964
~ sub_24e8e03d8 -> sub_25268a3dc : 3436 -> 3440
~ sub_24e8e1214 -> sub_25268b21c : 4316 -> 4320
~ sub_24e8e237c -> sub_25268c388 : 4096 -> 4100
~ sub_24e8e337c -> sub_25268d38c : 3892 -> 3900
~ sub_24e8ed128 -> sub_252697140 : 3140 -> 3144
~ sub_24e8ffff4 -> sub_2526aa010 : 1496 -> 1500
~ sub_24e901a20 -> sub_2526aba40 : 488 -> 492
~ sub_24e902d50 -> sub_2526acd74 : 952 -> 956
~ __ZN10MPSLibrary13MPSKey_CreateEPK17PrivateKernelInfoRK23MPSFunctionConstantListb30MPSThreadGroupSizeMultipleType24MPSDriverCompilerOptions23MPSForwardProgressUsagePFvPS0_EP8NSStringmy -> __ZN10MPSLibrary13MPSKey_CreateEPK17PrivateKernelInfoRK23MPSFunctionConstantListb30MPSThreadGroupSizeMultipleType24MPSDriverCompilerOptions23MPSForwardProgressUsagePFvPS0_EP8NSStringmym : 348 -> 364
~ __ZN10MPSLibrary14MPSKey_CompileEP11MPSKey_data : 3920 -> 3936
~ __ZN10MPSLibrary19CreateUberShaderKeyEP8NSStringRK23MPSFunctionConstantListyPFPU22objcproto11MTLFunction11objc_objectPU21objcproto10MTLLibrary11objc_objectPK13MPSKernelInfoS4_RK33MPSFunctionConstructorExtraParamsPP7NSErrorEy30MPSThreadGroupSizeMultipleType24MPSDriverCompilerOptions23MPSForwardProgressUsageP18MPSKernelDAGObjectS1_mP20MPSKernelUserDAGInfoP7NSArrayIS6_EPSR_ISO_E -> __ZN10MPSLibrary19CreateUberShaderKeyEP8NSStringRK23MPSFunctionConstantListyPFPU22objcproto11MTLFunction11objc_objectPU21objcproto10MTLLibrary11objc_objectPK13MPSKernelInfoS4_RK33MPSFunctionConstructorExtraParamsPP7NSErrorEy30MPSThreadGroupSizeMultipleType24MPSDriverCompilerOptions23MPSForwardProgressUsageP18MPSKernelDAGObjectS1_mP20MPSKernelUserDAGInfoP7NSArrayIS6_EPSR_ISO_Em : 2416 -> 2476
CStrings:
+ "130.2.2"
- "130.1.4"
```
