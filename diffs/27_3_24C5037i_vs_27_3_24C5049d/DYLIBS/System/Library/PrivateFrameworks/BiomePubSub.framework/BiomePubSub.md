## BiomePubSub

> `/System/Library/PrivateFrameworks/BiomePubSub.framework/BiomePubSub`

```diff

-259.2.0.2.0
-  __TEXT.__text: 0x406b0
+259.5.0.0.0
+  __TEXT.__text: 0x4060c
   __TEXT.__objc_methlist: 0x5894
   __TEXT.__const: 0x1000
   __TEXT.__cstring: 0x116f
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[BPSSink completeWithError:] : 584 -> 580
~ -[BPSSink requestNextEvents] : 268 -> 264
~ -[BPSDrivableSink requestNextEvents] : 304 -> 300
~ -[BPSDrivableSink completeWithError:] : 336 -> 332
~ -[BPSSink subscribeTo:] : 344 -> 340
~ -[BPSDrivableSink subscribeTo:] : 344 -> 340
~ -[BPSSink cancel] : 312 -> 308
~ -[_BPSMerged applyDownstreamWhileLocked:apply:] : 244 -> 240
~ -[_BPSAbstractOrderedMerge _completeWhileLockedWithCompletion:] : 288 -> 284
~ -[_BPSAbstractOrderedMerge receiveCompletion:atIndex:] : 596 -> 592
~ -[_BPSAbstractOrderedMerge flushBufferAndRequestMoreWhileLocked] : 668 -> 664
~ -[_BPSFlatMapOuter receiveCompletion:] : 820 -> 812
~ -[_BPSFlatMapOuter requestDemand:] : 1516 -> 1504
~ -[_BPSFlatMapOuter receiveInnerInput:index:] : 528 -> 520
~ -[_BPSFlatMapOuter receiveInnerCompletion:index:] : 1036 -> 1028
~ -[_BPSAbstractCombineLatest receiveInput:atIndex:] : 716 -> 712
~ -[_BPSAbstractCombineLatest receiveCompletion:atIndex:] : 1008 -> 1000
~ -[BPSSink _cancel] : 108 -> 104
~ -[BPSDrivableSink cancel] : 312 -> 308
~ -[BPSDrivableSink _cancel] : 108 -> 104
~ -[_BPSAbstractZip receiveSubscription:index:] : 668 -> 664
~ -[_BPSAbstractZip receiveInput:index:] : 1328 -> 1324
~ -[_BPSAbstractZip lockSendCompletion:index:] : 472 -> 468
~ -[_BPSInnerConduit offerInput:] : 272 -> 268
~ -[BPSPassThroughSubject startWithSubscriber:] : 96 -> 92
~ -[BPSPassThroughSubject nextEvent] : 192 -> 188
~ -[BPSPassThroughSubject reset] : 128 -> 124
~ -[BPSPassThroughSubject bookmark] : 104 -> 100
~ -[BPSPassThroughSubject applyBookmark:] : 104 -> 100
~ -[BPSPassThroughSubject sendCompletion] : 116 -> 112
~ -[BPSPassThroughSubject sendEvent:] : 144 -> 140
~ -[_BPSAbstractCorrelateOrderedMerge _completeWhileLockedWithCompletion:] : 288 -> 284
~ -[_BPSAbstractCorrelateOrderedMerge receiveCompletion:atIndex:] : 596 -> 592
~ -[_BPSAbstractCorrelateOrderedMerge flushBufferAndRequestMoreWhileLocked] : 812 -> 808
~ ___38-[BPSFuture initWithAttemptToFulfill:]_block_invoke : 468 -> 464
~ -[BPSFuture startWithSubscriber:] : 96 -> 92
~ -[BPSFuture nextEvent] : 176 -> 172
~ -[BPSFuture completed] : 84 -> 80
~ -[BPSFuture reset] : 96 -> 92
~ -[_BPSInnerFutureConduit requestDemand:] : 464 -> 460
~ -[_BPSInnerFutureConduit fulfill:] : 356 -> 352
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFyp_Tg5 : 268 -> 292
```
