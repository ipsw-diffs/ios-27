## EventKitUI

> `/System/Library/Frameworks/EventKitUI.framework/EventKitUI`

```diff

-1573.2.4.0.0
-  __TEXT.__text: 0x1fbd04
+1573.3.3.0.0
+  __TEXT.__text: 0x1fbf08
   __TEXT.__objc_methlist: 0x204bc
   __TEXT.__const: 0x2e94
   __TEXT.__cstring: 0xce64

   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x660
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xfce8
+  __DATA_CONST.__objc_selrefs: 0xfcf0
   __DATA_CONST.__objc_protorefs: 0xe0
   __DATA_CONST.__objc_superrefs: 0x8c8
   __DATA_CONST.__objc_arraydata: 0x1c0
Symbols:
+ +[EKUIAvailabilityParticipantList listWidthForCompact:aspectRatioType:safeAreaInsets:]
- +[EKUIAvailabilityParticipantList listWidthForCompact:orientation:]
Functions:
~ -[EKEventProposeNewTimeViewController viewAvailabilityTapped] : 292 -> 328
~ -[EKUIEventInviteesViewController availabilityTapped] : 304 -> 332
~ -[EKEventEditViewControllerModernImpl requestInviteeAvailabilityPresentationWithEvent:] : 292 -> 320
~ +[EKUIAvailabilityParticipantList listWidthForCompact:orientation:] -> +[EKUIAvailabilityParticipantList listWidthForCompact:aspectRatioType:safeAreaInsets:] : 48 -> 108
~ +[EKUIAvailabilityViewController presentAvailabilityViewControllerForEvent:fromViewController:] : 188 -> 216
~ -[EKUIAvailabilityViewController sizeWillBeCompact:] : 264 -> 296
~ -[EKUIAvailabilityViewController loadView] : 5252 -> 5276
~ -[EKUIAvailabilityViewController layout] : 1316 -> 1424
~ -[EKUIAvailabilityViewController viewPinched:] : 604 -> 640
~ sub_1de3a8664 -> sub_1deafd7e0 : 116 -> 128
~ sub_1de3be594 -> sub_1deb1371c : 108 -> 96
~ sub_1de3befc0 -> sub_1deb1413c : 480 -> 508
~ sub_1de3eec10 -> sub_1deb43da8 : 308 -> 332
~ sub_1de3efad0 -> sub_1deb44c80 : 4760 -> 4844
```
