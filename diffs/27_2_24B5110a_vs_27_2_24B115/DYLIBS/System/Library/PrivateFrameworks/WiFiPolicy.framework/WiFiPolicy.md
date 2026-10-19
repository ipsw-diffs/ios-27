## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/WiFiPolicy`

```diff

 1072.4.0.0.0
-  __TEXT.__text: 0xe3c94
+  __TEXT.__text: 0xe3c90
   __TEXT.__objc_methlist: 0x13e88
   __TEXT.__const: 0x888
-  __TEXT.__cstring: 0x25deb
+  __TEXT.__cstring: 0x25e2b
   __TEXT.__oslogstring: 0x550e
   __TEXT.__gcc_except_tab: 0x190c
   __TEXT.__dlopen_cstrs: 0xa8

   __DATA_CONST.__objc_arraydata: 0x1530
   __DATA_CONST.__got: 0xbc0
   __AUTH_CONST.__const: 0x600
-  __AUTH_CONST.__cfstring: 0x20e40
+  __AUTH_CONST.__cfstring: 0x20e60
   __AUTH_CONST.__objc_const: 0x25bf0
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x1aa0

   __AUTH.__objc_data: 0x668
   __DATA.__objc_ivar: 0x259c
   __DATA.__data: 0x1ca0
-  __DATA.__bss: 0x49
+  __DATA.__bss: 0x48
   __DATA_DIRTY.__objc_data: 0x35a8
   __DATA_DIRTY.__data: 0x160
   __DATA_DIRTY.__bss: 0x390

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 7242
-  Symbols:   12038
-  CStrings:  5327
+  Symbols:   12037
+  CStrings:  5328
 
Symbols:
- __isSeedInstall
Functions:
~ -[WFMeasure initWithType:andReason:prevTestedOptions:prevTestedTrafficClass:andInterfaceName:] : 1572 -> 1560
~ -[WiFiUsageLinkSession performLinkTestFor:isTriggeredByFault:] : 932 -> 964
~ -[WiFiUsageSession _generateState] : 984 -> 988
~ +[WiFiUsagePrivacyFilter initialize] : 52 -> 40
~ +[WiFiUsagePrivacyFilter isInternalOrSeedInstall] : 28 -> 12
CStrings:
+ "%s Rejected due to [WiFiUsagePrivacyFilter isInternalInstall]\n"
```
