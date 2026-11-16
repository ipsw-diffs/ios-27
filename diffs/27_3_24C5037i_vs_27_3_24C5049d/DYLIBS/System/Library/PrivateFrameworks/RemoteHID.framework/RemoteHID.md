## RemoteHID

> `/System/Library/PrivateFrameworks/RemoteHID.framework/RemoteHID`

```diff

 224.40.2.0.0
-  __TEXT.__text: 0xae34
+  __TEXT.__text: 0xadfc
   __TEXT.__objc_methlist: 0x550
   __TEXT.__const: 0x260
   __TEXT.__gcc_except_tab: 0x5f4
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[HIDRemoteEndpoint getDevice:] : 136 -> 132
~ -[HIDRemoteEndpoint addDevice:] : 224 -> 220
~ -[HIDRemoteEndpoint _removeDeviceID:] : 364 -> 360
~ -[HIDRemoteEndpoint removeAllDevices] : 276 -> 272
~ -[HIDRemoteEndpoint logRemovedDevice:] : 160 -> 156
~ -[HIDRemoteEndpoint copyState] : 328 -> 324
~ -[HIDRemoteEndpoint devices] : 88 -> 84
~ -[HIDRemoteDeviceServer endpoints] : 88 -> 84
~ -[HIDRemoteDeviceServer getEndpoint:] : 136 -> 132
~ -[HIDRemoteDeviceServer connectEndpoint:] : 204 -> 200
~ -[HIDRemoteDeviceServer _disconnectEndpointID:] : 228 -> 224
~ -[HIDRemoteDeviceServer disconnectAll] : 144 -> 140
~ -[HIDRemoteDeviceServer getRefreshCountForEndpoint:deviceID:] : 344 -> 340
~ -[HIDRemoteDeviceServer setRefreshCountForEndpoint:deviceID:count:] : 396 -> 392
```
