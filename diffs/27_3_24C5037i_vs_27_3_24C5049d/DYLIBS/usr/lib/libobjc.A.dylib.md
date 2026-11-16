## libobjc.A.dylib

> `/usr/lib/libobjc.A.dylib`

```diff

 973.2.0.0.0
-  __TEXT.__text: 0x3caa0
+  __TEXT.__text: 0x3cae0
   __TEXT.__lazy_helpers: 0xa8
   __TEXT.__objc_methlist: 0x5ec
   __TEXT.__const: 0x4130
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ _objc_retainAutoreleasedReturnValue : 160 -> 168
~ __objc_rootAllocWithZone : 324 -> 332
~ __ZN19AutoreleasePoolPage3addEP11objc_object : 360 -> 352
~ _objc_destructInstance : 72 -> 68
~ __object_remove_associations : 1140 -> 1144
~ __ZL38objc_destructInstance_nonnull_realizedP11objc_object : 164 -> 156
~ __ZN4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrIK11objc_objectEmN12_GLOBAL__N_125RefcountMapValuePurgeableENS_12DenseMapInfoIS5_EENS_6detail12DenseMapPairIS5_mEEEES5_mS7_S9_SC_E4findERKS5_ : 116 -> 124
~ _class_createInstance : 324 -> 332
~ _object_getIndexedIvars : 212 -> 204
~ _objc_lookUpImpOrForward : 816 -> 824
~ __ZNK8method_t3impEb : 320 -> 312
~ __objc_sync_enter_kind : 132 -> 128
~ _objc_sync_exit : 196 -> 184
~ _objc_sync_enter : 36 -> 32
~ __ZL11fetch_cacheb : 272 -> 268
~ _weak_unregister_no_lock : 500 -> 504
~ __ZN12locker_mixinIN9lockdebug10lock_mixinI16objc_lock_base_tEEE8lockWithERS3_ : 208 -> 204
~ __ZL17weak_entry_insertP12weak_table_tP12weak_entry_t : 200 -> 204
~ __ZN12locker_mixinIN9lockdebug10lock_mixinI16objc_lock_base_tEEE10unlockWithERS3_ : 148 -> 144
~ -[NSObject mutableCopy] : 24 -> 16
~ __ZN13list_array_ttIm15protocol_list_t6RawPtrE12iteratorImplILb0EE14skipEmptyListsEv : 588 -> 580
~ -[NSObject class] : 12 -> 4
~ __ZL34protocol_conformsToProtocol_nolockP10protocol_tS0_ : 236 -> 228
~ _object_getClass : 204 -> 196
~ __ZN13list_array_ttIm15protocol_list_t6RawPtrE12iteratorImplILb0EEC2ENS2_12ListIteratorES5_ : 392 -> 400
~ -[NSObject copy] : 24 -> 16
~ __ZN13list_array_ttIm15protocol_list_t6RawPtrE12ListIteratorC2ERKS3_ : 100 -> 96
~ _objc_setProperty_nonatomic_copy : 124 -> 128
~ _class_getName : 28 -> 36
~ __ZL27object_cxxDestructFromClassP11objc_objectP10objc_class : 228 -> 220
~ _lookupMethodInClassAndLoadCache : 304 -> 312
~ _object_isClass : 32 -> 40
~ _lookUpImpOrNilTryCache : 272 -> 264
~ +[NSObject resolveInstanceMethod:] : 8 -> 16
~ _lookUpImpOrForwardTryCache : 272 -> 280
~ __ZL20grow_refs_and_insertP12weak_entry_tPP11objc_object : 292 -> 284
~ _objc_getAssociatedObject : 392 -> 400
~ _object_cxxConstructFromClass : 364 -> 368
~ _objc_getProperty : 220 -> 232
~ _look_up_class : 472 -> 464
~ _objc_lookUpClass : 16 -> 24
~ __ZL10remapClassP10objc_class : 236 -> 244
~ _sel_registerName : 20 -> 12
~ +[NSObject self] : 4 -> 12
~ __ZL18__sel_registerNamePKcbb : 372 -> 380
~ _objc_allocWithZone : 56 -> 48
~ __ZN13list_array_ttIm15protocol_list_t6RawPtrE12iteratorImplILb0EEppEv : 808 -> 800
~ +[NSObject isProxy] : 16 -> 8
~ _objc_setAssociatedObject : 1688 -> 1680
~ __ZNK11objc_object24sidetable_isDeallocatingEv : 136 -> 140
~ _objc_setProperty_atomic_copy : 224 -> 220
~ _objc_storeWeakOrNil : 592 -> 600
~ _objc_sync_nil : 12 -> 4
~ +[NSObject instancesRespondToSelector:] : 16 -> 24
~ _method_getImplementation : 60 -> 68
~ __ZN4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrIK11objc_objectEmN12_GLOBAL__N_125RefcountMapValuePurgeableENS_12DenseMapInfoIS5_EENS_6detail12DenseMapPairIS5_mEEEES5_mS7_S9_SC_EixEOS5_ : 96 -> 104
~ _method_getTypeEncoding : 56 -> 48
~ _objc_exception_throw : 572 -> 580
~ __method_getImplementationAndName : 248 -> 240
~ +[NSObject isEqual:] : 12 -> 20
~ _sel_hash : 8 -> 16
~ +[NSObject hash] : 4 -> 12
~ _sel_getUid : 16 -> 24
~ __ZN19AutoreleasePoolPage19autoreleaseFullPageEP11objc_objectPS_ : 208 -> 200
~ _class_copyProtocolList : 1148 -> 1144
~ _objc_setProperty_atomic : 264 -> 260
~ -[NSObject retainCount] : 12 -> 16
~ _objc_setProperty_nonatomic : 140 -> 136
~ __ZNK11objc_object16sidetable_unlockEv : 60 -> 68
~ __ZN4objc12DenseMapBaseINS_8DenseMapIPKcNS_6detail13DenseSetEmptyENS_17DenseMapValueInfoIS5_EENS_12DenseMapInfoIS3_EENS4_12DenseSetPairIS3_EEEES3_S5_S7_S9_SB_E11try_emplaceIJRS5_EEENSt3__14pairINS_16DenseMapIteratorIS3_S5_S7_S9_SB_Lb0EEEbEERKS3_DpOT_ : 312 -> 320
~ ___objc_personality_v0 : 212 -> 204
~ _class_getInstanceMethod : 312 -> 304
~ -[NSObject retain] : 12 -> 4
~ __Z18protocol_getMethodP10protocol_tP13objc_selectorbbb : 308 -> 316
~ -[NSObject allowsWeakReference] : 40 -> 48
~ __ZNK4objc12DenseMapBaseINS_8DenseMapIPKcNS_6detail13DenseSetEmptyENS_17DenseMapValueInfoIS5_EENS_12DenseMapInfoIS3_EENS4_12DenseSetPairIS3_EEEES3_S5_S7_S9_SB_E15LookupBucketForIS3_EEbRKT_RPKSB_ : 320 -> 312
~ -[NSObject performSelector:] : 88 -> 80
~ __ZNK13list_array_ttI10property_t15property_list_t6RawPtrE5beginEv : 532 -> 524
~ __objc_rootTryRetain : 152 -> 144
~ _protocol_copyMethodDescriptionList : 668 -> 676
~ __ZN15entsize_list_ttI8method_t13method_list_tLj4294901763ENS0_16pointer_modifierEE3endEv : 108 -> 100
~ _sel_isEqual : 20 -> 12
~ __ZL25getMethodFromRelativeListP20relative_list_list_tI13method_list_tEP13objc_selector : 1736 -> 1744
~ __ZN15entsize_list_ttI10property_t15property_list_tLj0E18PointerModifierNopE3endEv : 80 -> 72
~ _object_getIvar : 116 -> 124
~ __class_getVariable : 288 -> 280
~ _method_getNumberOfArguments : 188 -> 192
~ __ZL13SkipFirstTypePKc : 208 -> 220
~ _map_images : 324 -> 312
~ _map_images_nolock : 8380 -> 8392
~ __ZNK11header_info9classlistEPm : 152 -> 140
~ __ZL24hasSignedClassROPointersPK14mach_header_64P29_dyld_section_location_info_s : 88 -> 100
~ __ZL12allocBucketsj : 88 -> 96
~ __ZL9protocolsv : 192 -> 200
~ __ZNK11header_info9nlclslistEPm : 140 -> 148
~ __ZL20classSlotForTagIndex16objc_tag_index_t : 108 -> 116
~ __ZL33realizeClassMaybeSwiftMaybeRelockP10objc_classR12locker_mixinIN9lockdebug10lock_mixinI16objc_lock_base_tEEEb : 552 -> 560
~ __ZN4objc7Scanner18scanAddedClassImplEP10objc_classNS0_11metaclass_tE : 2648 -> 2656
~ __ZN7cache_t26maybeConvertToPreoptimizedEv : 372 -> 364
~ __ZN23tls_autoptr_direct_implI18_objc_pthread_dataL7tls_key0EE5dtor_EPv : 160 -> 152
~ _method_copyReturnType : 132 -> 136
~ __ZL12SubtypeUntilPKcc : 152 -> 156
~ _sel_lookUpByName : 288 -> 280
~ __ZN13list_array_ttIm15protocol_list_t6RawPtrE11attachListsEPKPS0_jbPKc : 1276 -> 1268
~ __ZL27internal_class_getImageNameP10objc_classPPKc : 56 -> 48
~ __ZN7cache_t11eraseNolockEPKc : 564 -> 556
~ __ZN4objc7Scanner13isSwiftObjectEP10objc_class : 124 -> 116
~ +[NSObject retain] : 16 -> 8
~ _objc_getClass : 24 -> 16
~ +[NSObject superclass] : 68 -> 60
~ __ZN4objc12DenseMapBaseINS_8DenseMapIPKcNS_6detail13DenseSetEmptyENS_17DenseMapValueInfoIS5_EENS_12DenseMapInfoIS3_EENS4_12DenseSetPairIS3_EEEES3_S5_S7_S9_SB_E4findES3_ : 140 -> 132
~ __ZN11objc_object21rootRelease_underflowEb : 624 -> 616
~ __ZL11getProtocolPKc : 148 -> 140
~ -[NSObject performSelector:withObject:] : 104 -> 108
~ _encoding_getArgumentInfo : 412 -> 408
~ _objc_moveWeak : 284 -> 276
~ _class_replaceMethod : 316 -> 324
~ __ZL11flushCachesP10objc_classPKcU13block_pointerFbS0_E : 240 -> 248
~ _class_addMethod : 252 -> 244
~ __ZZL22load_categories_nolockP11header_infoENK3$_0clEPKP10category_tb : 1084 -> 1080
~ __ZL19schedule_class_loadP10objc_class : 388 -> 400
~ __ZN10objc_class13getLoadMethodEv : 3448 -> 3440
~ __ZN4objc7Scanner17scanChangedMethodEP10objc_classPK8method_t : 940 -> 948
~ __ZL33objc_initializeClassPair_internalP10objc_classPKcS0_S0_ : 1792 -> 1800
~ __ZL27_allocateTrampolinesAndDatav : 664 -> 656
~ __ZN13list_array_ttI8method_t13method_list_t24method_list_t_authed_ptrE12iteratorImplILb1EEC2ENS3_12ListIteratorES6_ : 940 -> 948
~ __ZNK8method_t20getCachedDescriptionEv : 656 -> 648
~ _method_getDescription : 88 -> 80
~ __ZL13addNamedClassP10objc_classPKcS0_ : 592 -> 600
~ _objc_getProtocol : 180 -> 188
~ __ZNK11header_info7catlistEPm : 140 -> 148
~ __category_getLoadMethod : 1660 -> 1668
~ _objc_getFutureClass : 628 -> 620
~ ____ZL13setSuperclassP10objc_classS0__block_invoke : 8 -> 20
~ __ZN17loadImageCallbackaSERKS_ : 188 -> 176
~ _class_setVersion : 352 -> 344
~ __ZN4objc8DenseMapI12DisguisedPtrI10objc_classEP17PendingInitializeNS_17DenseMapValueInfoIS5_EENS_12DenseMapInfoIS3_EENS_6detail12DenseMapPairIS3_S5_EEE4initEj : 244 -> 236
~ __objc_getClassForTag : 84 -> 92
~ __ZN10objc_class11mangledNameEv : 96 -> 88
~ _property_copyAttributeValue : 268 -> 260
~ _gdb_objc_class_changed : 12 -> 4
~ _class_copyIvarList : 416 -> 408
~ __ZN4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrIK11objc_objectEmN12_GLOBAL__N_125RefcountMapValuePurgeableENS_12DenseMapInfoIS5_EENS_6detail12DenseMapPairIS5_mEEEES5_mS7_S9_SC_E4growEj : 496 -> 504
~ _property_copyAttributeList : 412 -> 404
~ __ZL9readClassP10objc_classbb : 1696 -> 1704
~ _objc_readClassPair : 668 -> 676
~ __ZNSt3__113__stable_sortINS_17_ClassicAlgPolicyERN8method_t16SortBySELAddressEPNS2_9bigSignedEEEvT1_S7_T0_NS_15iterator_traitsIS7_E15difference_typeEPNSA_10value_typeEl : 2144 -> 2136
~ ____class_setCustomDeallocInitiation_block_invoke : 32 -> 24
~ _class_initialize : 112 -> 120
~ _protocol_conformsToProtocol : 192 -> 200
~ ____ZN4objc7Scanner20propagateCustomFlagsEP10objc_classjNS0_11inherited_tE_block_invoke : 492 -> 500
~ __ZL10addMethodsP10objc_classPKP13objc_selectorPKPFvvEPPKcjbPj : 732 -> 724
~ -[NSObject self] : 4 -> 12
~ _class_addMethodsBulk : 332 -> 324
~ __ZN13method_list_t16sortBySELAddressEv : 464 -> 472
~ _protocol_isEqual : 116 -> 124
~ __ZN4objc8DenseMapIPK8method_tP23objc_method_descriptionNS_17DenseMapValueInfoIS5_EENS_12DenseMapInfoIS3_EENS_6detail12DenseMapPairIS3_S5_EEE4growEj : 504 -> 508
~ -[Protocol isEqual:] : 208 -> 204
~ __ZL16addRemappedClassP10objc_classS0_ : 468 -> 476
~ __ZL13remapClassRefPP10objc_classjbU13block_pointerFvjE : 484 -> 492
~ __ZL25pageAndIndexContainingIMPPFvvEPm : 308 -> 316
~ _method_exchangeImplementations : 944 -> 936
~ __ZN4objc8DenseMapIPK8method_tPvNS_17DenseMapValueInfoIS4_EENS_12DenseMapInfoIS3_EENS_6detail12DenseMapPairIS3_S4_EEE4growEj : 516 -> 524
~ __objc_beginClassEnumeration : 468 -> 476
~ _objc_claimAutoreleasedReturnValue : 148 -> 140
~ __objc_enumerateNextClass : 624 -> 632
~ _object_getInstanceVariable : 136 -> 128
~ __ZN4objc8DenseMapIPKcNS_6detail13DenseSetEmptyENS_17DenseMapValueInfoIS4_EENS_12DenseMapInfoIS2_EENS3_12DenseSetPairIS2_EEE4growEj : 536 -> 528
~ __ZL12_NXMapRehashP11_NXMapTable : 236 -> 244
~ __ZL27namedClassTableHashCallbackP11_NXMapTablePKv : 8 -> 16
~ -[NSObject isFault] : 20 -> 12
~ _object_dispose : 68 -> 76
~ -[NSObject debugDescription] : 20 -> 12
~ __ZL23fixupProtocolMethodListP10protocol_tP13method_list_tbbbPPP13objc_selector : 668 -> 660
~ +[NSObject performSelector:withObject:] : 108 -> 100
~ _protocol_copyProtocolList : 420 -> 428
~ +[NSObject copyWithZone:] : 16 -> 4
~ -[Protocol hash] : 16 -> 20
~ _method_setImplementation : 480 -> 488
~ __ZN19AutoreleasePoolPage12popPageDebugEPvPS_PP11objc_object : 268 -> 276
~ _sel_getName : 24 -> 20
~ _objc_copyCppObjectAtomic : 152 -> 156
~ _protocol_getProperty : 236 -> 244
~ __objc_deallocOnMainThreadHelper : 12 -> 20
~ _objc_removeAssociatedObjects : 44 -> 36
~ __ZL11_mapPtrHashP11_NXMapTablePKv : 16 -> 20
~ __ZN4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrI11objc_objectENS_13SmallDenseMapIPKvNS_15ObjcAssociationELj1ENS_17DenseMapValueInfoIS8_EENS_12DenseMapInfoIS7_EENS_6detail12DenseMapPairIS7_S8_EEEENS9_ISG_EENSB_IS4_EENSE_IS4_SG_EEEES4_SG_SH_SI_SJ_E5eraseENS_16DenseMapIteratorIS4_SG_SH_SI_SJ_Lb0EEE : 380 -> 384
~ ____ZL13setSuperclassP10objc_classS0__block_invoke.204 : 16 -> 12
~ __ZN4objc8DenseMapI12DisguisedPtrI11objc_objectENS_13SmallDenseMapIPKvNS_15ObjcAssociationELj1ENS_17DenseMapValueInfoIS7_EENS_12DenseMapInfoIS6_EENS_6detail12DenseMapPairIS6_S7_EEEENS8_ISF_EENSA_IS3_EENSD_IS3_SF_EEE4growEj : 596 -> 600
~ _class_getVersion : 172 -> 180
~ __ZL12_objc_fatalvyyPKcPc : 172 -> 164
~ __ZNK4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrI10objc_classENS_6detail13DenseSetEmptyENS_17DenseMapValueInfoIS6_EENS_12DenseMapInfoIS4_EENS5_12DenseSetPairIS4_EEEES4_S6_S8_SA_SC_E15LookupBucketForIS4_EEbRKT_RPKSC_ : 248 -> 256
~ __ZN10objc_class14nameForLoggingEv : 460 -> 468
~ _property_getAttributes : 8 -> 16
~ __ZNK19AutoreleasePoolPage10busted_dieEv : 40 -> 48
~ _ivar_getOffset : 20 -> 28
~ __ZN19AutoreleasePoolPage18autoreleaseNewPageEP11objc_object : 100 -> 108
~ _method_getName : 192 -> 200
~ -[NSObject performSelector:withObject:withObject:] : 116 -> 108
~ __ZL17realizeAllClassesv : 500 -> 508
~ ____objc_map_images_block_invoke : 16 -> 12
~ _unmap_image : 1848 -> 1844
~ _protocol_addProperty : 632 -> 640
~ ___copy_helper_block_e8_32c49_ZTSKZL33objc_copyRealizedClassList_nolockPjE3$_1 : 12 -> 20
~ __objc_endClassEnumeration : 32 -> 24
~ __ZL35foreach_realized_class_and_subclassP10objc_classU13block_pointerFbS0_E : 196 -> 204
~ _gdb_object_getClass : 200 -> 192
~ ___copy_helper_block_e8_32c69_ZTSKZN10objc_class39setDisallowPreoptInlinedSelsRecursivelyEPKcE3$_0 : 12 -> 20
~ __objc_getFreedObjectClass : 16 -> 8
~ ___copy_helper_block_e8_32c67_ZTSKZL25_method_setImplementationP10objc_classP8method_tPFvvEE3$_0 : 24 -> 16
~ __ZNSt3__16vectorIPK14mach_header_64NS_9allocatorIS3_EEE24__emplace_back_slow_pathIJS3_EEEPS3_DpOT_ : 216 -> 224
~ ___copy_helper_block_e8_32c60_ZTSKZL17addMethods_finishP10objc_classP13method_list_tE3$_0 : 8 -> 16
~ _sel_isMapped : 300 -> 296
~ __objc_atfork_prepare : 832 -> 828
~ __ZNK4objc12DenseMapBaseINS_8DenseMapIPK8method_tP23objc_method_descriptionNS_17DenseMapValueInfoIS6_EENS_12DenseMapInfoIS4_EENS_6detail12DenseMapPairIS4_S6_EEEES4_S6_S8_SA_SD_E22FatalCorruptHashTablesEPKSD_j : 88 -> 96
~ __Z26objc_defaultForwardHandlerP11objc_objectP13objc_selector : 112 -> 108
~ __ZNK4objc12DenseMapBaseINS_13SmallDenseMapIPKvNS_15ObjcAssociationELj1ENS_17DenseMapValueInfoIS4_EENS_12DenseMapInfoIS3_EENS_6detail12DenseMapPairIS3_S4_EEEES3_S4_S6_S8_SB_E22FatalCorruptHashTablesEPKSB_j : 92 -> 104
```
