## AuthenticationServices

> `/System/Library/Frameworks/AuthenticationServices.framework/AuthenticationServices`

```diff

-626.1.12.10.3
-  __TEXT.__text: 0x14d8e8
+626.1.17.0.0
+  __TEXT.__text: 0x14dce4
   __TEXT.__objc_methlist: 0x82d0
   __TEXT.__cstring: 0xb708
   __TEXT.__const: 0x14484
   __TEXT.__gcc_except_tab: 0x13a4
-  __TEXT.__oslogstring: 0x393b
+  __TEXT.__oslogstring: 0x3acb
   __TEXT.__dlopen_cstrs: 0x308
   __TEXT.__ustring: 0x6d36
   __TEXT.__swift5_typeref: 0x3662

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 8443
-  Symbols:   6663
-  CStrings:  1377
+  Symbols:   6662
+  CStrings:  1381
 
Symbols:
- ___87-[_ASPasswordManagerIconController _fetchTouchIconForDomain:requestID:responseHandler:]_block_invoke_3
Functions:
~ ___87-[_ASPasswordManagerIconController _fetchTouchIconForDomain:requestID:responseHandler:]_block_invoke_2 : 32 -> 188
~ ___97-[_ASPasswordManagerIconController _requestTouchIconForDomain:options:requestID:responseHandler:]_block_invoke : 852 -> 960
~ ___97-[_ASPasswordManagerIconController _requestTouchIconForDomain:options:requestID:responseHandler:]_block_invoke_2 : 740 -> 1020
~ -[ASAuthorizationController _convertCoreErrorToPublicError:] : 540 -> 608
~ sub_1af6e4df8 -> sub_1af82005c : 116 -> 128
~ sub_1af702c68 -> sub_1af83ded8 : 260 -> 284
~ sub_1af71ebb8 -> sub_1af859e40 : 284 -> 316
~ sub_1af71ef70 -> sub_1af85a218 : 484 -> 528
~ sub_1af71f154 -> sub_1af85a428 : 268 -> 292
~ sub_1af71f260 -> sub_1af85a54c : 268 -> 292
~ sub_1af71f36c -> sub_1af85a670 : 268 -> 284
~ sub_1af72efe4 -> sub_1af86a2f8 : 480 -> 524
~ sub_1af72f1c4 -> sub_1af86a504 : 264 -> 288
~ sub_1af72f2cc -> sub_1af86a624 : 280 -> 316
~ sub_1af72f3e4 -> sub_1af86a760 : 256 -> 280
~ sub_1af72f4e4 -> sub_1af86a878 : 264 -> 280
~ sub_1af72f5ec -> sub_1af86a990 : 280 -> 316
~ sub_1af74826c -> sub_1af883634 : 2092 -> 2104
~ sub_1af74bef0 -> sub_1af8872c4 : 3496 -> 3524
~ sub_1af74cd7c -> sub_1af88816c : 544 -> 556
CStrings:
+ "Checked for a local visit before fetching touch icon; domain=%{sensitive, mask.hash}@; foundLocalVisit=%{bool}d"
+ "Finished fetching touch icon; domain=%{sensitive, mask.hash}@; isGenerated=%{bool}d"
+ "Received generated touch icon; domain=%{sensitive, mask.hash}@"
+ "Skipping touch icon fetch until the retry date; domain=%{sensitive, mask.hash}@; retryDate=%{public}@"
+ "Will not retry touch icon fetch until the retry date; domain=%{sensitive, mask.hash}@; retryDate=%{public}@"
- "Finished fetching touch icon; domain=%{sensitive, mask.hash}@"
```
