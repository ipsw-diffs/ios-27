## Bom

> `/System/Library/PrivateFrameworks/Bom.framework/Bom`

```diff

-280.0.0.0.0
-  __TEXT.__text: 0x5bad8
-  __TEXT.__cstring: 0x129e3
+282.0.0.0.0
+  __TEXT.__text: 0x5bb14
+  __TEXT.__cstring: 0x12a6b
   __TEXT.__const: 0x1728
   __TEXT.__oslogstring: 0x103e
   __TEXT.__unwind_info: 0xad8

   - /usr/lib/libz.1.dylib
   Functions: 1101
   Symbols:   1562
-  CStrings:  2392
+  CStrings:  2394
 
Functions:
~ _create_entry_filesystem : 6900 -> 6916
~ _BOMCopierCopySourceEntryToDestinationSet : 4068 -> 4004
~ __copyFile : 9068 -> 9080
~ _BOMStorageCopyFromBlock : 240 -> 288
~ _BOMStorageCopyFromBlockRange : 664 -> 712
CStrings:
+ "BOMStorageCopyFromBlock: bid >= storage->blockTableCount"
+ "BOMStorageCopyRangeFromBlockRange: bad block (bid >= storage->blockTableCount)"
+ "Nov 10 2026"
- "Oct 22 2026"
```
