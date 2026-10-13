## ReplicatorDependencies

> `/System/Library/PrivateFrameworks/ReplicatorDependencies.framework/ReplicatorDependencies`

```diff

-176.2.5.0.0
-  __TEXT.__text: 0x29efc
+176.2.6.0.0
+  __TEXT.__text: 0x2a160
   __TEXT.__objc_methlist: 0x314
-  __TEXT.__const: 0x1ce4
+  __TEXT.__const: 0x1d14
   __TEXT.__swift5_typeref: 0xbbe
-  __TEXT.__swift5_reflstr: 0x898
+  __TEXT.__swift5_reflstr: 0x8a8
   __TEXT.__swift5_assocty: 0x180
   __TEXT.__constg_swiftt: 0x111c
   __TEXT.__swift5_fieldmd: 0xa5c
   __TEXT.__swift5_builtin: 0x3c
   __TEXT.__swift5_proto: 0x130
   __TEXT.__swift5_types: 0xac
-  __TEXT.__oslogstring: 0x11e1
+  __TEXT.__oslogstring: 0x1311
   __TEXT.__cstring: 0x5e1
   __TEXT.__swift5_capture: 0x4e0
   __TEXT.__swift_as_entry: 0x28
   __TEXT.__swift_as_ret: 0x28
   __TEXT.__swift_as_cont: 0x18
   __TEXT.__swift5_protos: 0x44
-  __TEXT.__unwind_info: 0xb50
+  __TEXT.__unwind_info: 0xb48
   __TEXT.__eh_frame: 0xa58
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x2210
-  __AUTH_CONST.__objc_const: 0x12c8
+  __AUTH_CONST.__objc_const: 0x12a8
   __AUTH_CONST.__auth_got: 0xba0
   __DATA.__data: 0x260
   __DATA.__bss: 0x1610
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x3f0
-  __DATA_DIRTY.__data: 0x1328
+  __DATA_DIRTY.__data: 0x1318
   __DATA_DIRTY.__bss: 0x900
   __DATA_DIRTY.__common: 0x30
   - /System/Library/Frameworks/Accounts.framework/Accounts
Functions:
~ sub_2a42782ac -> sub_2a55282ac : 760 -> 764
~ sub_2a427bbac -> sub_2a552bbb0 : 1528 -> 1540
~ sub_2a427cc24 -> sub_2a552cc34 : 152 -> 192
~ sub_2a4280c04 -> sub_2a5530c3c : 152 -> 192
~ sub_2a4280c9c -> sub_2a5530cfc : 8 -> 16
~ sub_2a428ee0c -> sub_2a553ee74 : 216 -> 224
~ sub_2a4290768 -> sub_2a55407d8 : 48 -> 112
~ sub_2a4291528 -> sub_2a55415d8 : 1528 -> 1668
~ sub_2a4291b78 -> sub_2a5541cb4 : 1788 -> 1892
~ sub_2a4292274 -> sub_2a5542418 : 2552 -> 2680
~ sub_2a4292c6c -> sub_2a5542e90 : 792 -> 864
~ sub_2a4292f84 -> sub_2a55431f0 : 1900 -> 2016
~ sub_2a4293798 -> sub_2a5543a78 : 712 -> 788
~ sub_2a4293a60 -> sub_2a5543d8c : 4448 -> 4748
~ sub_2a4294c24 -> sub_2a554507c : 100 -> 92
~ sub_2a4294c88 -> sub_2a55450d8 : 124 -> 116
~ sub_2a4294f38 -> sub_2a5545380 : 52 -> 116
~ sub_2a4294f7c -> sub_2a5545404 : 2744 -> 2492
~ sub_2a4295a34 -> sub_2a5545dc0 : 2772 -> 2512
~ sub_2a4296e94 -> sub_2a554711c : 36 -> 28
~ sub_2a4298638 -> sub_2a55488b8 : 3200 -> 3132
~ sub_2a429f640 -> sub_2a554f87c : 380 -> 420
CStrings:
+ "%{public}llu:%{private}s: Cannot create NWConnection from nw_connection_t"
+ "%{public}llu:%{private}s: Connection cancelled"
+ "%{public}llu:%{private}s: Connection failed and entered waiting state: %{public}s"
+ "%{public}llu:%{private}s: Connection failed with no reported error"
+ "%{public}llu:%{private}s: Connection failed: %{public}s"
+ "%{public}llu:%{private}s: Connection ready"
+ "%{public}llu:%{private}s: Connection state changed; state: %{public}s"
+ "%{public}llu:%{private}s: Connection state changed; state: %{public}s; error: %{public}s"
+ "%{public}llu:%{private}s: Failed to send file %{public}s error: %{public}s"
+ "%{public}llu:%{private}s: Failed to send message data: %{public}s"
+ "%{public}llu:%{private}s: New outgoing connection created to %{public}s"
+ "%{public}llu:%{private}s: Ready to receive %{public}u bytes"
+ "%{public}llu:%{private}s: Received %{public}ld bytes"
+ "%{public}llu:%{private}s: Received error: %{public}s"
+ "%{public}llu:%{private}s: Received nil data"
+ "%{public}llu:%{private}s: Sending file %{public}s; maximumLength: %{public}ld"
+ "%{public}llu:%{private}s: Sent %{public}ld bytes"
+ "%{public}llu:%{private}s: Sent file %{public}s; maximumLength: %{public}ld; totalBytesSent: %{public}ld"
+ "%{public}llu:%{private}s: Starting connection"
+ "%{public}s: %{public}s %{private}s will be used for connection: %{public}s"
+ "%{public}s: Browser found device with ID: %{private}s; name: %{private}s; isMeDevice: %{bool,public}d"
+ "%{public}s: Monitor found remote device with ID %{private}s but it is not the 'me' device"
+ "%{public}s: Monitor found remote device with ID: %{private}s"
+ "%{public}s: Received new connection: %{public}s: DeviceID: %{private}s"
+ "%{public}s: Unable to get DeviceID from connection: %{public}s: Using uuidString %{private}s instead"
+ "Fetched IDS device: %{private}s; isCloudPaired: %{bool,public}d"
+ "Finding active paired device in devices: %{private}s"
+ "IDS PairedDevice is %{private}s"
+ "Updating paired device from %{private}s to %{private}s"
+ "[?:%{private}s]: Creating %{public}s connection for %{public}s"
- "%{public}s: %{public}s %{public}s will be used for connection: %{public}s"
- "%{public}s: Browser found device with ID: %{public}s; name: %{public}s; isMeDevice: %{bool,public}d"
- "%{public}s: Cannot create NWConnection from nw_connection_t"
- "%{public}s: Connection cancelled"
- "%{public}s: Connection failed and entered waiting state: %{public}s"
- "%{public}s: Connection failed with no reported error"
- "%{public}s: Connection failed: %{public}s"
- "%{public}s: Connection ready"
- "%{public}s: Connection state changed; state: %{public}s"
- "%{public}s: Connection state changed; state: %{public}s; error: %{public}s"
- "%{public}s: Failed to send file %{public}s error: %{public}s"
- "%{public}s: Failed to send message data: %{public}s"
- "%{public}s: Monitor found remote device with ID %{public}s but it is not the 'me' device"
- "%{public}s: Monitor found remote device with ID: %{public}s"
- "%{public}s: New outgoing connection created to %{public}s; deviceID: %{public}s"
- "%{public}s: Ready to receive %u bytes"
- "%{public}s: Received %{public}ld bytes"
- "%{public}s: Received error: %{public}s"
- "%{public}s: Received new connection: %{public}s: DeviceID: %{public}s"
- "%{public}s: Received nil data"
- "%{public}s: Sending file %{public}s; maximumLength: %{public}ld"
- "%{public}s: Sent %ld bytes"
- "%{public}s: Sent file %{public}s; maximumLength: %{public}ld; totalBytesSent: %{public}ld"
- "%{public}s: Starting connection"
- "%{public}s: Unable to get DeviceID from connection: %{public}s: Using uuidString %{public}s instead"
- "Fetched IDS device: %{public}s; isCloudPaired: %{bool,public}d"
- "Finding active paired device in devices: %{public}s"
- "IDS PairedDevice is %{public}s"
- "Updating paired device from %{public}s to %{public}s"
- "[?:%s]: Creating %s connection for %{public}s"
```
