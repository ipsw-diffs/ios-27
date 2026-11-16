## SpatialAudioServices

> `/System/Library/PrivateFrameworks/SpatialAudioServices.framework/SpatialAudioServices`

```diff

-23.40.1.0.0
-  __TEXT.__text: 0x4b664
+23.60.1.0.0
+  __TEXT.__text: 0x4b5a0
   __TEXT.__lazy_helpers: 0x24c
   __TEXT.__objc_methlist: 0x2474
   __TEXT.__const: 0x396c
-  __TEXT.__gcc_except_tab: 0x5b20
+  __TEXT.__gcc_except_tab: 0x5b1c
   __TEXT.__cstring: 0x2567
   __TEXT.__oslogstring: 0x162c
   __TEXT.__dlopen_cstrs: 0x6a
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ __ZN3SAS3AAS10DuplexPipeD2Ev : 128 -> 124
~ __ZN3SAS3AAS10DuplexPipe18swapImplementationENSt3__110shared_ptrINS1_14DuplexPipeImplEEE : 160 -> 156
~ __ZN3SAS3AAS10DuplexPipe16beginTransactionEjPKvm : 148 -> 144
~ __ZN3SAS3AAS10DuplexPipe14reserveMessageEjmRNS1_11Transaction7Message15DeallocStrategyE : 144 -> 140
~ __ZN3SAS3AAS10DuplexPipe13commitMessageEPvNS1_11Transaction7Message15DeallocStrategyE : 140 -> 136
~ __ZN3SAS3AAS10DuplexPipe17commitTransactionEj : 124 -> 120
~ -[SCSXPCClient permissions] : 88 -> 84
~ ___47-[SCSXPCClient bootstrapConnection:completion:]_block_invoke : 244 -> 240
~ -[SCSXPCClient addFulfiller:] : 144 -> 140
~ -[SCSXPCClient removeFulfiller:] : 548 -> 544
~ -[SCSXPCClient addRequester:] : 164 -> 160
~ -[SCSXPCClient removeRequester:] : 496 -> 492
~ -[SCSXPCClient didChangeStatus:] : 484 -> 480
~ -[SCSXPCClient currentStreamConfiguration:] : 292 -> 288
~ -[SCSXPCClient startOrUpdateControlForStream:configuration:completion:] : 468 -> 464
~ -[SCSXPCClient stopControlForStream:] : 312 -> 308
~ -[SCSXPCClient streamControlWasInvalidated:details:] : 268 -> 264
~ -[SCSXPCClient startOrUpdateControlCompletedForStream:configuration:withResult:] : 348 -> 344
~ -[SCSXPCClient receivedStartOrUpdateControlForStream:configuration:completion:] : 776 -> 772
~ -[SCSXPCClient receivedStopControlForStream:] : 468 -> 464
~ -[SCSXPCClient receivedStreamControlWasInvalidated:details:] : 560 -> 556
~ -[SCSXPCClient receivedStartOrUpdateControlCompletedForStream:configuration:withResult:] : 312 -> 308
~ __ZN3SAS17LockableContainerIU8__strongPU29objcproto18SASConnectionEntry11objc_objectNS_17ObjectPointerHashEE5_lockEv : 244 -> 240
~ ___47-[RCSXPCClient bootstrapConnection:completion:]_block_invoke : 180 -> 176
~ -[RCSXPCClient permissions] : 88 -> 84
~ -[RCSXPCClient roomCongruenceInformation] : 112 -> 108
~ -[RCSXPCClient addSubscriber:] : 216 -> 212
~ -[RCSXPCClient removeSubscriber:] : 144 -> 140
~ -[RCSXPCClient didChangeStatus:] : 248 -> 244
~ -[RCSXPCClient updateRoomCongruenceInformation:] : 264 -> 260
~ -[RCSXPCClient didUpdateRoomCongruenceInformation:] : 132 -> 128
~ -[SASXPCClient handleSuccessfulConnection:] : 568 -> 564
~ -[SASXPCClient remoteObjectProxyWithErrorHandler:] : 516 -> 512
~ -[SASXPCClient clearConnectionAndUpdateStatus:] : 160 -> 156
~ -[SpatialAudioService operateUnderLock:] : 136 -> 132
~ -[SpatialAudioService clearAndInvalidateConnectionEntries] : 228 -> 224
~ __ZN7Service23initializeSharedServiceEv : 132 -> 128
~ -[SASAnchorServiceXPCConnectionEntry outgoingChannelFilter] : 156 -> 152
~ -[SASAnchorServiceXPCConnectionEntry setOutgoingChannelFilter:] : 140 -> 136
~ -[SASAnchorServiceXPCConnectionEntry configureSharedMemoryChannel:completion:] : 224 -> 220
~ -[SASAnchorServiceXPCConnectionEntry sendFilterUpdateReplyToClient:messageID:] : 328 -> 324
~ -[SASAnchorServiceXPCConnectionEntry sendHasAnySubscriberRequestedFrontAnchoringToClient:] : 260 -> 256
~ -[SASAnchorServiceXPCConnectionEntry sendAnchorUpdates:publisherID:transactionInformation:properties:] : 196 -> 192
~ -[SASAnchorServiceXPCConnectionEntry invalidate] : 268 -> 264
~ __ZN3SAS3AAS17AASXPCClient_Impl29beginTransactionFromPublisherEyyy : 144 -> 140
~ __ZNK3SAS3AAS17AASXPCClient_Impl18getSubscriberStateERK14AASAudioAnchoryP27AASAudioAnchorPropertyStatePU15__autoreleasingP34AASAudioAnchorRenderingPreferences : 144 -> 140
~ __ZNK3SAS3AAS17AASXPCClient_Impl18getStatusForAnchorERK14AASAudioAnchor : 108 -> 104
~ __ZNK3SAS3AAS17AASXPCClient_Impl20findAnyTrackedAnchorE18AASAudioAnchorTypey : 136 -> 132
~ __ZNK3SAS3AAS17AASXPCClient_Impl22findAnchorMatchingUUIDEP6NSUUID : 132 -> 128
~ __ZN3SAS3AAS17AASXPCClient_Impl23subscriberIDWillDeallocEy : 112 -> 108
~ __ZN3SAS3AAS17AASXPCClient_Impl28beginFilterUpdateTransactionEP20AASAudioAnchorFilterNSt3__112basic_stringIcNS4_11char_traitsIcEENS4_9allocatorIcEEEE : 112 -> 108
~ __ZN3SAS3AAS17AASXPCClient_Impl27beginFilterReplyTransactionENSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE : 12 -> 8
~ __ZThn24_N3SAS3AAS17AASXPCClient_Impl27beginFilterReplyTransactionENSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE : 12 -> 8
~ __ZN3SAS3AAS17AASXPCClient_Impl11applyUpdateERKNS0_22SubscriberAnchorUpdateE : 160 -> 156
~ __ZN3SAS3AAS17AASXPCClient_Impl15onServerConnectEv : 596 -> 592
~ __ZN3SAS17LockableContainerIU8__strongP24AASAudioAnchorSubscriberNS_17ObjectPointerHashEE5_lockEv : 244 -> 240
~ -[SCSDirectClientConnection addRequester:] : 96 -> 92
~ -[SCSDirectClientConnection removeRequester:] : 104 -> 100
~ -[SCSDirectClientConnection addFulfiller:] : 96 -> 92
~ -[SCSDirectClientConnection removeFulfiller:] : 104 -> 100
~ -[SCSDirectClientConnection startOrUpdateControlForStream:configuration:completion:] : 364 -> 360
~ -[SCSDirectClientConnection stopControlForStream:] : 256 -> 252
~ -[SCSDirectClientConnection receivedStreamControlWasInvalidated:details:] : 264 -> 260
~ -[SCSDirectClientConnection receivedStartOrUpdateControlCompletedForStream:configuration:withResult:] : 244 -> 240
~ sub_2b88f9c80 -> sub_2bad23b80 : 268 -> 292
~ sub_2b88f9d8c -> sub_2bad23ca4 : 260 -> 284
~ sub_2b89018d8 -> sub_2bad2b808 : 116 -> 128
```
