## ansf.t8150.release.im4p

> `Firmware/ansf.t8150.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA.__const`

```diff

   __TEXT.text_first: 0x45a0
-  __TEXT.__text: 0x1f1578
-  __TEXT.shared: 0xeac8
+  __TEXT.__text: 0x1f1b00
+  __TEXT.shared: 0xec14
   __TEXT.read: 0x73f4
-  __TEXT.__const: 0x5e08
-  __TEXT.__cstring: 0x26207
+  __TEXT.__const: 0x6008
+  __TEXT.__cstring: 0x2620a
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x18
   __DATA._rtk_boot: 0x8000

   __DATA._rtk_patchbay: 0x474
   __DATA._rtk_tunables: 0x6a0
   __DATA._rtk_mtab: 0x380
-  __DATA.__data: 0x5c30
+  __DATA.__data: 0x5c28
   __DATA.__const: 0x1b70
   __DATA.__gxf_data: 0x10
-  __DATA.core_globals: 0x163
+  __DATA.core_globals: 0x165
   __DATA._rtk_init_stack: 0x1000
   __DATA._rtk_irq_stack: 0x1000
   __DATA._rtk_exc_stack: 0x1000

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x2a5b18
-  Functions: 2035
+  __DATA.__zerofill: 0x2a5b48
+  Functions: 2036
   Symbols:   0
-  CStrings:  4085
+  CStrings:  4084
 
CStrings:
+ "241.40.4"
+ "241.40.4~95"
+ "AppleStorageFirmwareASP3-241.40.4~95"
+ "Sanitize Failed"
+ "Sweep stuck detected - aborting - channel %d, die %d, plane %d"
+ "Sweep was aborted - rejecting continuation command"
+ "sanitize cmd drop - not init"
- "241.0.12"
- "241.0.12~645"
- "Abort Pad: Flow %u , Band: %u"
- "AppleStorageFirmwareASP3-241.0.12~645"
- "Sanitize already in progress, phase=%d"
- "Sanitize drop - device in shutdown"
- "mark invalid band %u S %u"
- "mark valid band %u M %u"
```
