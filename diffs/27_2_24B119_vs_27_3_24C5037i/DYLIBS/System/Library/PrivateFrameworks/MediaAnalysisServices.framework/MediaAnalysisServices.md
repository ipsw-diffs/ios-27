## MediaAnalysisServices

> `/System/Library/PrivateFrameworks/MediaAnalysisServices.framework/MediaAnalysisServices`

```diff

-460.14.1.2.0
-  __TEXT.__text: 0x3cf70
+470.4.2.0.0
+  __TEXT.__text: 0x3cf80
   __TEXT.__objc_methlist: 0x5034
   __TEXT.__const: 0xf8
-  __TEXT.__cstring: 0x399e
+  __TEXT.__cstring: 0x399f
   __TEXT.__gcc_except_tab: 0x44e4
   __TEXT.__oslogstring: 0x2309
   __TEXT.__dlopen_cstrs: 0x417

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xa78
+  __DATA_CONST.__const: 0xa80
   __DATA_CONST.__objc_classlist: 0x430
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ +[MADTextInput csuTokenizerRevision] : 56 -> 52
~ -[MADImageEmbeddingRequest init] : 164 -> 168
~ -[MADTextTokenizationRequest init] : 124 -> 128
~ +[MADTextTokenizationRequest maxTokenSize] : 100 -> 104
~ -[MADService(Text) activeTextEmbeddingVersions:] : 348 -> 352
~ -[MADTextEmbeddingRequest init] : 140 -> 144
CStrings:
+ "SearchUnifiedEmbeddingMD10"
- "SearchUnifiedEmbeddingMD8"
```
