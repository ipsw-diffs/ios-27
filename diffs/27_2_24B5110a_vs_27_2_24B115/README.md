# 27.2 (24B5110a) .vs 27.2 (24B115)

## Inputs

- `iPhone18,1_27.2_24B5110a_Restore.ipsw`
- `iPhone18,1_27.2_24B115_Restore.ipsw`

## Kernel

### Version

| iOS | Version | Build | Date |
| :-- | :------ | :---- | :--- |
| 27.2 *(24B5110a)* | 27.2.0 | 13432.42.3~13 | Sat, 10Oct2026 01:31:39 PDT |
| 27.2 *(24B115)* | 27.2.0 | 13432.42.3~28 | Tue, 13Oct2026 21:26:58 PDT |

### Kexts

#### ❌ Removed (1)

- `com.apple.kec.AppleEncryptedArchive`

#### ⬆️ Updated (33)

<details>
  <summary><i>View Updated</i></summary>

- [com.apple.AGXG18P](KEXTS/com.apple.AGXG18P.md)
- [com.apple.AUC](KEXTS/com.apple.AUC.md)
- [com.apple.driver.AppleAOPAudio](KEXTS/com.apple.driver.AppleAOPAudio.md)
- [com.apple.driver.AppleAVE2](KEXTS/com.apple.driver.AppleAVE2.md)
- [com.apple.driver.AppleHPM](KEXTS/com.apple.driver.AppleHPM.md)
- [com.apple.driver.AppleMSG](KEXTS/com.apple.driver.AppleMSG.md)
- [com.apple.driver.AppleMobileFileIntegrity](KEXTS/com.apple.driver.AppleMobileFileIntegrity.md)
- [com.apple.driver.AppleSEPCredentialManager](KEXTS/com.apple.driver.AppleSEPCredentialManager.md)
- [com.apple.driver.AppleSEPKeyStore](KEXTS/com.apple.driver.AppleSEPKeyStore.md)
- [com.apple.driver.AppleSMC](KEXTS/com.apple.driver.AppleSMC.md)
- [com.apple.driver.AppleSPMIPMU](KEXTS/com.apple.driver.AppleSPMIPMU.md)
- [com.apple.driver.AppleSmartIO2](KEXTS/com.apple.driver.AppleSmartIO2.md)
- [com.apple.driver.AppleT8110DART](KEXTS/com.apple.driver.AppleT8110DART.md)
- [com.apple.driver.AppleT8150CLPC](KEXTS/com.apple.driver.AppleT8150CLPC.md)
- [com.apple.driver.AppleThunderboltNHI](KEXTS/com.apple.driver.AppleThunderboltNHI.md)
- [com.apple.driver.AppleUSBDeviceMux](KEXTS/com.apple.driver.AppleUSBDeviceMux.md)
- [com.apple.driver.AudioDMACLLTEscalationDetector-T8150](KEXTS/com.apple.driver.AudioDMACLLTEscalationDetector-T8150.md)
- [com.apple.driver.AudioDMAController-T8150](KEXTS/com.apple.driver.AudioDMAController-T8150.md)
- [com.apple.driver.AudioDMAFamily](KEXTS/com.apple.driver.AudioDMAFamily.md)
- [com.apple.driver.IOAudioCodecs](KEXTS/com.apple.driver.IOAudioCodecs.md)
- [com.apple.driver.IOPAudioVoiceTriggerDevice](KEXTS/com.apple.driver.IOPAudioVoiceTriggerDevice.md)
- [com.apple.driver.RTBuddy](KEXTS/com.apple.driver.RTBuddy.md)
- [com.apple.driver.corecapture](KEXTS/com.apple.driver.corecapture.md)
- [com.apple.filesystems.apfs](KEXTS/com.apple.filesystems.apfs.md)
- [com.apple.iokit.AppleARMIISAudio](KEXTS/com.apple.iokit.AppleARMIISAudio.md)
- [com.apple.iokit.IOBiometricFamily](KEXTS/com.apple.iokit.IOBiometricFamily.md)
- [com.apple.iokit.IOHIDFamily](KEXTS/com.apple.iokit.IOHIDFamily.md)
- [com.apple.iokit.IOPCIFamily](KEXTS/com.apple.iokit.IOPCIFamily.md)
- [com.apple.iokit.IOThunderboltFamily](KEXTS/com.apple.iokit.IOThunderboltFamily.md)
- [com.apple.kernel](KEXTS/com.apple.kernel.md)
- [com.apple.security.AKSAnalytics](KEXTS/com.apple.security.AKSAnalytics.md)
- [com.apple.security.AppleImage4](KEXTS/com.apple.security.AppleImage4.md)
- [com.apple.security.sandbox](KEXTS/com.apple.security.sandbox.md)

</details>

## MachO

### filesystem

#### 🆕 NEW (2)

- `/System/ExclaveCore/usr/share/exclavecore_sharedcache/t8150.RELEASE.restore.stripped.sharedcache`
- `/System/ExclaveCore/usr/share/exclavecore_sharedcache/t8150.RELEASE.stripped.sharedcache`

#### ❌ Removed (1)

- `/usr/libexec/memoryanalyticsd`

#### ⬆️ Updated (383)

<details>
  <summary><i>View Updated</i></summary>

- [/Applications/CheckerBoard.app/CheckerBoard](MACHOS/filesystem/Applications/CheckerBoard.app/CheckerBoard.md)
- [/Applications/ColorPickerUIService.app/ColorPickerUIService](MACHOS/filesystem/Applications/ColorPickerUIService.app/ColorPickerUIService.md)
- [/Applications/CompanionSetup.app/CompanionSetup](MACHOS/filesystem/Applications/CompanionSetup.app/CompanionSetup.md)
- [/Applications/DiagnosticsReporter.app/DiagnosticsReporter](MACHOS/filesystem/Applications/DiagnosticsReporter.app/DiagnosticsReporter.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-7004.appex/Diagnostic-7004](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-7004.appex/Diagnostic-7004.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8185.appex/Diagnostic-8185](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8185.appex/Diagnostic-8185.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8268.appex/Diagnostic-8268](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8268.appex/Diagnostic-8268.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8340.appex/Diagnostic-8340](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8340.appex/Diagnostic-8340.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8343.appex/Diagnostic-8343](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8343.appex/Diagnostic-8343.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9006.appex/Diagnostic-9006](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9006.appex/Diagnostic-9006.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9008.appex/Diagnostic-9008](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9008.appex/Diagnostic-9008.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9010.appex/Diagnostic-9010](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9010.appex/Diagnostic-9010.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9012.appex/Diagnostic-9012](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9012.appex/Diagnostic-9012.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9013.appex/Diagnostic-9013](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9013.appex/Diagnostic-9013.md)
- [/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9016.appex/Diagnostic-9016](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9016.appex/Diagnostic-9016.md)
- [/Applications/DiagnosticsService.app/PlugIns/SystemReport-AirPods.appex/SystemReport-AirPods](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/SystemReport-AirPods.appex/SystemReport-AirPods.md)
- [/Applications/DiagnosticsService.app/PlugIns/SystemReport-BatteryCase.appex/SystemReport-BatteryCase](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/SystemReport-BatteryCase.appex/SystemReport-BatteryCase.md)
- [/Applications/DiagnosticsService.app/PlugIns/SystemReport.appex/SystemReport](MACHOS/filesystem/Applications/DiagnosticsService.app/PlugIns/SystemReport.appex/SystemReport.md)
- [/Applications/FontPickerUIService.app/FontPickerUIService](MACHOS/filesystem/Applications/FontPickerUIService.app/FontPickerUIService.md)
- [/Applications/HDSViewService.app/HDSViewService](MACHOS/filesystem/Applications/HDSViewService.app/HDSViewService.md)
- [/Applications/LocalAuthenticationUIService.app/LocalAuthenticationUIService](MACHOS/filesystem/Applications/LocalAuthenticationUIService.app/LocalAuthenticationUIService.md)
- [/Applications/MobilePhone.app/MobilePhone](MACHOS/filesystem/Applications/MobilePhone.app/MobilePhone.md)
- [/Applications/MomentsUIService.app/MomentsUIService](MACHOS/filesystem/Applications/MomentsUIService.app/MomentsUIService.md)
- [/Applications/Preferences.app/Preferences](MACHOS/filesystem/Applications/Preferences.app/Preferences.md)
- [/Applications/RecoverDeviceUI.app/RecoverDeviceUI](MACHOS/filesystem/Applications/RecoverDeviceUI.app/RecoverDeviceUI.md)
- [/Applications/Setup.app/Setup](MACHOS/filesystem/Applications/Setup.app/Setup.md)
- [/Applications/Sidecar.app/PlugIns/ContinuityDisplay.appex/ContinuityDisplay](MACHOS/filesystem/Applications/Sidecar.app/PlugIns/ContinuityDisplay.appex/ContinuityDisplay.md)
- [/Applications/Sidecar.app/Sidecar](MACHOS/filesystem/Applications/Sidecar.app/Sidecar.md)
- [/Applications/Siri.app/Siri](MACHOS/filesystem/Applications/Siri.app/Siri.md)
- [/Applications/StoreKitUISceneService.app/StoreKitUISceneService](MACHOS/filesystem/Applications/StoreKitUISceneService.app/StoreKitUISceneService.md)
- [/Applications/TVSetupUIService.app/TVSetupUIService](MACHOS/filesystem/Applications/TVSetupUIService.app/TVSetupUIService.md)
- [/Applications/Tamale.app/Tamale](MACHOS/filesystem/Applications/Tamale.app/Tamale.md)
- [/Applications/WritingToolsUIService.app/WritingToolsUIService](MACHOS/filesystem/Applications/WritingToolsUIService.app/WritingToolsUIService.md)
- [/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio](MACHOS/filesystem/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio.md)
- [/System/Library/AccessibilityBundles/AXImageExplorerServer.axuiservice/AXImageExplorerServer](MACHOS/filesystem/System/Library/AccessibilityBundles/AXImageExplorerServer.axuiservice/AXImageExplorerServer.md)
- [/System/Library/AppRemovalServices/com.apple.Translate.appremoval.xpc/com.apple.Translate.appremoval](MACHOS/filesystem/System/Library/AppRemovalServices/com.apple.Translate.appremoval.xpc/com.apple.Translate.appremoval.md)
- [/System/Library/AppleMediaServices/DynamicUI/PlugIns/CoreDynamicUIPlugin.bundle/CoreDynamicUIPlugin](MACHOS/filesystem/System/Library/AppleMediaServices/DynamicUI/PlugIns/CoreDynamicUIPlugin.bundle/CoreDynamicUIPlugin.md)
- [/System/Library/Assistant/Plugins/activity.assistantBundle/activity](MACHOS/filesystem/System/Library/Assistant/Plugins/activity.assistantBundle/activity.md)
- [/System/Library/Audio/Plug-Ins/HAL/AppleAOPAudioPlugin.driver/AppleAOPAudioPlugin](MACHOS/filesystem/System/Library/Audio/Plug-Ins/HAL/AppleAOPAudioPlugin.driver/AppleAOPAudioPlugin.md)
- [/System/Library/BulletinDistributor/PingSubscribers/NanoCalendarPingSubscriber.bundle/NanoCalendarPingSubscriber](MACHOS/filesystem/System/Library/BulletinDistributor/PingSubscribers/NanoCalendarPingSubscriber.bundle/NanoCalendarPingSubscriber.md)
- [/System/Library/CoreImage/PortraitFilters.cifilter/portrait_filters_archive_bin.metallib](MACHOS/filesystem/System/Library/CoreImage/PortraitFilters.cifilter/portrait_filters_archive_bin.metallib.md)
- [/System/Library/CoreImage/PortraitFilters.cifilter/portrait_filters_fullsize_archive_bin.metallib](MACHOS/filesystem/System/Library/CoreImage/PortraitFilters.cifilter/portrait_filters_fullsize_archive_bin.metallib.md)
- [/System/Library/CoreServices/BluetoothUIService.app/BluetoothUIService](MACHOS/filesystem/System/Library/CoreServices/BluetoothUIService.app/BluetoothUIService.md)
- [/System/Library/CoreServices/ClarityBoard.app/ClarityBoard](MACHOS/filesystem/System/Library/CoreServices/ClarityBoard.app/ClarityBoard.md)
- [/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0001.bundle/MobileDevices-0001](MACHOS/filesystem/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0001.bundle/MobileDevices-0001.md)
- [/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0003.bundle/MobileDevices-0003](MACHOS/filesystem/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0003.bundle/MobileDevices-0003.md)
- [/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0004.bundle/MobileDevices-0004](MACHOS/filesystem/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0004.bundle/MobileDevices-0004.md)
- [/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0005.bundle/MobileDevices-0005](MACHOS/filesystem/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0005.bundle/MobileDevices-0005.md)
- [/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices.bundle/MobileDevices](MACHOS/filesystem/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices.bundle/MobileDevices.md)
- [/System/Library/CoreServices/HangHUD.app/HangHUD](MACHOS/filesystem/System/Library/CoreServices/HangHUD.app/HangHUD.md)
- [/System/Library/CoreServices/osanalyticshelper](MACHOS/filesystem/System/Library/CoreServices/osanalyticshelper.md)
- [/System/Library/DataClassMigrators/AppUserDataMigrator.migrator/AppUserDataMigrator](MACHOS/filesystem/System/Library/DataClassMigrators/AppUserDataMigrator.migrator/AppUserDataMigrator.md)
- [/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator](MACHOS/filesystem/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator.md)
- [/System/Library/DataClassMigrators/SpringBoard.migrator/SpringBoard](MACHOS/filesystem/System/Library/DataClassMigrators/SpringBoard.migrator/SpringBoard.md)
- [/System/Library/DataClassMigrators/SystemAppMigrator.migrator/SystemAppMigrator](MACHOS/filesystem/System/Library/DataClassMigrators/SystemAppMigrator.migrator/SystemAppMigrator.md)
- [/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN](MACHOS/filesystem/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN.md)
- [/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetE1000.dext/com.apple.DriverKit-AppleEthernetE1000](MACHOS/filesystem/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetE1000.dext/com.apple.DriverKit-AppleEthernetE1000.md)
- [/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetIXGBE.dext/com.apple.DriverKit-AppleEthernetIXGBE](MACHOS/filesystem/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetIXGBE.dext/com.apple.DriverKit-AppleEthernetIXGBE.md)
- [/System/Library/ExtensionKit/Extensions/AppStoreEvalLighthouseWorker.appex/AppStoreEvalLighthouseWorker](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/AppStoreEvalLighthouseWorker.appex/AppStoreEvalLighthouseWorker.md)
- [/System/Library/ExtensionKit/Extensions/CloudWorker.appex/CloudWorker](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/CloudWorker.appex/CloudWorker.md)
- [/System/Library/ExtensionKit/Extensions/InferenceExtension.appex/InferenceExtension](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/InferenceExtension.appex/InferenceExtension.md)
- [/System/Library/ExtensionKit/Extensions/IntelligenceFlowAppIntentsExtension.appex/IntelligenceFlowAppIntentsExtension](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/IntelligenceFlowAppIntentsExtension.appex/IntelligenceFlowAppIntentsExtension.md)
- [/System/Library/ExtensionKit/Extensions/LighthouseAVExtension.appex/LighthouseAVExtension](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/LighthouseAVExtension.appex/LighthouseAVExtension.md)
- [/System/Library/ExtensionKit/Extensions/LighthouseAVShadowEval.appex/LighthouseAVShadowEval](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/LighthouseAVShadowEval.appex/LighthouseAVShadowEval.md)
- [/System/Library/ExtensionKit/Extensions/MercuryPosterExtension.appex/Celosia.metallib](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/MercuryPosterExtension.appex/Celosia.metallib.md)
- [/System/Library/ExtensionKit/Extensions/MercuryPosterExtension.appex/Space.metallib](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/MercuryPosterExtension.appex/Space.metallib.md)
- [/System/Library/ExtensionKit/Extensions/ProductPageExtension.appex/ProductPageExtension](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/ProductPageExtension.appex/ProductPageExtension.md)
- [/System/Library/ExtensionKit/Extensions/SubscribePageExtension.appex/SubscribePageExtension](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/SubscribePageExtension.appex/SubscribePageExtension.md)
- [/System/Library/ExtensionKit/Extensions/TranslationAPIExtension.appex/TranslationAPIExtension](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/TranslationAPIExtension.appex/TranslationAPIExtension.md)
- [/System/Library/ExtensionKit/Extensions/TranslationAPISupportExtension.appex/TranslationAPISupportExtension](MACHOS/filesystem/System/Library/ExtensionKit/Extensions/TranslationAPISupportExtension.appex/TranslationAPISupportExtension.md)
- [/System/Library/Extensions/AppleThunderboltSAT.kext/AppleThunderboltSAT](MACHOS/filesystem/System/Library/Extensions/AppleThunderboltSAT.kext/AppleThunderboltSAT.md)
- [/System/Library/Extensions/AppleThunderboltSAT_TS.kext/AppleThunderboltSAT_TS](MACHOS/filesystem/System/Library/Extensions/AppleThunderboltSAT_TS.kext/AppleThunderboltSAT_TS.md)
- [/System/Library/Filesystems/hfs.fs/CopyHFSMeta](MACHOS/filesystem/System/Library/Filesystems/hfs.fs/CopyHFSMeta.md)
- [/System/Library/Filesystems/hfs.fs/fsck_hfs](MACHOS/filesystem/System/Library/Filesystems/hfs.fs/fsck_hfs.md)
- [/System/Library/Filesystems/hfs.fs/hfs.util](MACHOS/filesystem/System/Library/Filesystems/hfs.fs/hfs.util.md)
- [/System/Library/Filesystems/hfs.fs/mount_hfs](MACHOS/filesystem/System/Library/Filesystems/hfs.fs/mount_hfs.md)
- [/System/Library/Filesystems/hfs.fs/newfs_hfs](MACHOS/filesystem/System/Library/Filesystems/hfs.fs/newfs_hfs.md)
- [/System/Library/FlowTools/Tools/GeoFlowTools.flowtool/GeoFlowTools](MACHOS/filesystem/System/Library/FlowTools/Tools/GeoFlowTools.flowtool/GeoFlowTools.md)
- [/System/Library/FlowTools/Tools/GetCurrentLocationFlowToolPlugin.flowtool/GetCurrentLocationFlowToolPlugin](MACHOS/filesystem/System/Library/FlowTools/Tools/GetCurrentLocationFlowToolPlugin.flowtool/GetCurrentLocationFlowToolPlugin.md)
- [/System/Library/FlowTools/Tools/SiriPhoneFlowTools.flowtool/SiriPhoneFlowTools](MACHOS/filesystem/System/Library/FlowTools/Tools/SiriPhoneFlowTools.flowtool/SiriPhoneFlowTools.md)
- [/System/Library/Frameworks/ClassKit.framework/progressd](MACHOS/filesystem/System/Library/Frameworks/ClassKit.framework/progressd.md)
- [/System/Library/Frameworks/CoreImage.framework/coreui_archive_bin.metallib](MACHOS/filesystem/System/Library/Frameworks/CoreImage.framework/coreui_archive_bin.metallib.md)
- [/System/Library/Frameworks/CoreImage.framework/photo_style_archive_bin.metallib](MACHOS/filesystem/System/Library/Frameworks/CoreImage.framework/photo_style_archive_bin.metallib.md)
- [/System/Library/Frameworks/CoreImage.framework/redeye_repair_archive_bin.metallib](MACHOS/filesystem/System/Library/Frameworks/CoreImage.framework/redeye_repair_archive_bin.metallib.md)
- [/System/Library/Frameworks/CoreImage.framework/ubershader_archive_bin.metallib](MACHOS/filesystem/System/Library/Frameworks/CoreImage.framework/ubershader_archive_bin.metallib.md)
- [/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter](MACHOS/filesystem/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter.md)
- [/System/Library/Frameworks/Security.framework/XPCServices/TrustedPeersHelper.xpc/TrustedPeersHelper](MACHOS/filesystem/System/Library/Frameworks/Security.framework/XPCServices/TrustedPeersHelper.xpc/TrustedPeersHelper.md)
- [/System/Library/Frameworks/Speech.framework/XPCServices/localspeechrecognition.xpc/localspeechrecognition](MACHOS/filesystem/System/Library/Frameworks/Speech.framework/XPCServices/localspeechrecognition.xpc/localspeechrecognition.md)
- [/System/Library/Frameworks/StoreKit.framework/Support/storekitd](MACHOS/filesystem/System/Library/Frameworks/StoreKit.framework/Support/storekitd.md)
- [/System/Library/Frameworks/Translation.framework/translationd](MACHOS/filesystem/System/Library/Frameworks/Translation.framework/translationd.md)
- [/System/Library/Frameworks/UIKit.framework/PlugIns/com.apple.UIKit.ShareUI.appex/com.apple.UIKit.ShareUI](MACHOS/filesystem/System/Library/Frameworks/UIKit.framework/PlugIns/com.apple.UIKit.ShareUI.appex/com.apple.UIKit.ShareUI.md)
- [/System/Library/Frameworks/UIKit.framework/PlugIns/com.apple.UIKit.screenpicker.appex/com.apple.UIKit.screenpicker](MACHOS/filesystem/System/Library/Frameworks/UIKit.framework/PlugIns/com.apple.UIKit.screenpicker.appex/com.apple.UIKit.screenpicker.md)
- [/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd](MACHOS/filesystem/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd.md)
- [/System/Library/Messages/iMessageBalloons/ASMessagesProvider.bundle/ASMessagesProvider](MACHOS/filesystem/System/Library/Messages/iMessageBalloons/ASMessagesProvider.bundle/ASMessagesProvider.md)
- [/System/Library/Messages/iMessageBalloons/DigitalTouchBalloonProvider.bundle/DigitalTouchBalloonProvider](MACHOS/filesystem/System/Library/Messages/iMessageBalloons/DigitalTouchBalloonProvider.bundle/DigitalTouchBalloonProvider.md)
- [/System/Library/NanoPreferenceBundles/Applications/NanoCalendarBridgeSettings.bundle/NanoCalendarBridgeSettings](MACHOS/filesystem/System/Library/NanoPreferenceBundles/Applications/NanoCalendarBridgeSettings.bundle/NanoCalendarBridgeSettings.md)
- [/System/Library/NanoTimeKit/ComplicationBundles/NanoCalendarComplicationsCompanion.bundle/NanoCalendarComplicationsCompanion](MACHOS/filesystem/System/Library/NanoTimeKit/ComplicationBundles/NanoCalendarComplicationsCompanion.bundle/NanoCalendarComplicationsCompanion.md)
- [/System/Library/NanoTimeKit/FaceBundles/KaleidoscopeFaceBundle.bundle/NTKKaleidoscopeShaders.metallib](MACHOS/filesystem/System/Library/NanoTimeKit/FaceBundles/KaleidoscopeFaceBundle.bundle/NTKKaleidoscopeShaders.metallib.md)
- [/System/Library/NanoTimeKit/FaceBundles/NTKWarlockFaceBundle.bundle/warlock.metallib](MACHOS/filesystem/System/Library/NanoTimeKit/FaceBundles/NTKWarlockFaceBundle.bundle/warlock.metallib.md)
- [/System/Library/PreferenceBundles/HomeSettings.bundle/HomeSettings](MACHOS/filesystem/System/Library/PreferenceBundles/HomeSettings.bundle/HomeSettings.md)
- [/System/Library/PreferenceBundles/KeyboardSettings.bundle/KeyboardSettings](MACHOS/filesystem/System/Library/PreferenceBundles/KeyboardSettings.bundle/KeyboardSettings.md)
- [/System/Library/PreferenceBundles/KeyboardSettingsBundle.bundle/KeyboardSettingsBundle](MACHOS/filesystem/System/Library/PreferenceBundles/KeyboardSettingsBundle.bundle/KeyboardSettingsBundle.md)
- [/System/Library/PreferenceBundles/NotificationsSettings.bundle/NotificationsSettings](MACHOS/filesystem/System/Library/PreferenceBundles/NotificationsSettings.bundle/NotificationsSettings.md)
- [/System/Library/PreferenceBundles/TranslateSettings.bundle/TranslateSettings](MACHOS/filesystem/System/Library/PreferenceBundles/TranslateSettings.bundle/TranslateSettings.md)
- [/System/Library/PrivateFrameworks/ACTFramework.framework/binaryArchive.g18p](MACHOS/filesystem/System/Library/PrivateFrameworks/ACTFramework.framework/binaryArchive.g18p.md)
- [/System/Library/PrivateFrameworks/ACTFramework.framework/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/PrivateFrameworks/ACTFramework.framework/binaryArchive.g18p_a0.md)
- [/System/Library/PrivateFrameworks/AXAssetLoader.framework/Support/axassetsd](MACHOS/filesystem/System/Library/PrivateFrameworks/AXAssetLoader.framework/Support/axassetsd.md)
- [/System/Library/PrivateFrameworks/AppConduit.framework/Support/appconduitd](MACHOS/filesystem/System/Library/PrivateFrameworks/AppConduit.framework/Support/appconduitd.md)
- [/System/Library/PrivateFrameworks/AppIntentsServices.framework/XPCServices/AppIntentsRunnerXPCService.xpc/AppIntentsRunnerXPCService](MACHOS/filesystem/System/Library/PrivateFrameworks/AppIntentsServices.framework/XPCServices/AppIntentsRunnerXPCService.xpc/AppIntentsRunnerXPCService.md)
- [/System/Library/PrivateFrameworks/AppStoreDaemon.framework/Support/appstored](MACHOS/filesystem/System/Library/PrivateFrameworks/AppStoreDaemon.framework/Support/appstored.md)
- [/System/Library/PrivateFrameworks/AppleCVAPhoto.framework/Resources/binaryArchive.g18p](MACHOS/filesystem/System/Library/PrivateFrameworks/AppleCVAPhoto.framework/Resources/binaryArchive.g18p.md)
- [/System/Library/PrivateFrameworks/AppleCVAPhoto.framework/Resources/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/PrivateFrameworks/AppleCVAPhoto.framework/Resources/binaryArchive.g18p_a0.md)
- [/System/Library/PrivateFrameworks/AppleMediaDiscovery.framework/PlugIns/AppStoreEvalLighthousePlugin.appex/AppStoreEvalLighthousePlugin](MACHOS/filesystem/System/Library/PrivateFrameworks/AppleMediaDiscovery.framework/PlugIns/AppStoreEvalLighthousePlugin.appex/AppStoreEvalLighthousePlugin.md)
- [/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/amsengagementd](MACHOS/filesystem/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/amsengagementd.md)
- [/System/Library/PrivateFrameworks/AskPermission.framework/Support/askpermissiond](MACHOS/filesystem/System/Library/PrivateFrameworks/AskPermission.framework/Support/askpermissiond.md)
- [/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd](MACHOS/filesystem/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd.md)
- [/System/Library/PrivateFrameworks/AuthKit.framework/akd](MACHOS/filesystem/System/Library/PrivateFrameworks/AuthKit.framework/akd.md)
- [/System/Library/PrivateFrameworks/BookDataStore.framework/Support/bookdatastored](MACHOS/filesystem/System/Library/PrivateFrameworks/BookDataStore.framework/Support/bookdatastored.md)
- [/System/Library/PrivateFrameworks/BookLibraryCore.framework/Support/bookassetd](MACHOS/filesystem/System/Library/PrivateFrameworks/BookLibraryCore.framework/Support/bookassetd.md)
- [/System/Library/PrivateFrameworks/CMCapture.framework/BWPreviewStitcherNodeCoreImageArchive_bin.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/CMCapture.framework/BWPreviewStitcherNodeCoreImageArchive_bin.metallib.md)
- [/System/Library/PrivateFrameworks/CMCapture.framework/BWVideoPIPOverlayNodeCoreImageArchive_bin.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/CMCapture.framework/BWVideoPIPOverlayNodeCoreImageArchive_bin.metallib.md)
- [/System/Library/PrivateFrameworks/CMImaging.framework/binaryArchive.g18p](MACHOS/filesystem/System/Library/PrivateFrameworks/CMImaging.framework/binaryArchive.g18p.md)
- [/System/Library/PrivateFrameworks/CMImaging.framework/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/PrivateFrameworks/CMImaging.framework/binaryArchive.g18p_a0.md)
- [/System/Library/PrivateFrameworks/CacheDelete.framework/deleted_helper](MACHOS/filesystem/System/Library/PrivateFrameworks/CacheDelete.framework/deleted_helper.md)
- [/System/Library/PrivateFrameworks/CallIntelligence.framework/callintelligenced](MACHOS/filesystem/System/Library/PrivateFrameworks/CallIntelligence.framework/callintelligenced.md)
- [/System/Library/PrivateFrameworks/CameraColorProcessing.framework/binaryArchive.g18p](MACHOS/filesystem/System/Library/PrivateFrameworks/CameraColorProcessing.framework/binaryArchive.g18p.md)
- [/System/Library/PrivateFrameworks/CameraColorProcessing.framework/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/PrivateFrameworks/CameraColorProcessing.framework/binaryArchive.g18p_a0.md)
- [/System/Library/PrivateFrameworks/CameraUI.framework/FRSVCoreImageArchive_bin.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/CameraUI.framework/FRSVCoreImageArchive_bin.metallib.md)
- [/System/Library/PrivateFrameworks/CinematicCommunication.framework/binaryArchive.g18p](MACHOS/filesystem/System/Library/PrivateFrameworks/CinematicCommunication.framework/binaryArchive.g18p.md)
- [/System/Library/PrivateFrameworks/CinematicCommunication.framework/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/PrivateFrameworks/CinematicCommunication.framework/binaryArchive.g18p_a0.md)
- [/System/Library/PrivateFrameworks/CinematicFraming.framework/binaryArchive.g18p](MACHOS/filesystem/System/Library/PrivateFrameworks/CinematicFraming.framework/binaryArchive.g18p.md)
- [/System/Library/PrivateFrameworks/CinematicFraming.framework/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/PrivateFrameworks/CinematicFraming.framework/binaryArchive.g18p_a0.md)
- [/System/Library/PrivateFrameworks/CinematicUtil.framework/binaryArchive.g18p](MACHOS/filesystem/System/Library/PrivateFrameworks/CinematicUtil.framework/binaryArchive.g18p.md)
- [/System/Library/PrivateFrameworks/CinematicUtil.framework/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/PrivateFrameworks/CinematicUtil.framework/binaryArchive.g18p_a0.md)
- [/System/Library/PrivateFrameworks/CloudDocsUI.framework/PlugIns/com.apple.CloudDocsUI.CloudSharing.appex/com.apple.CloudDocsUI.CloudSharing](MACHOS/filesystem/System/Library/PrivateFrameworks/CloudDocsUI.framework/PlugIns/com.apple.CloudDocsUI.CloudSharing.appex/com.apple.CloudDocsUI.CloudSharing.md)
- [/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/Support/cloudphotod](MACHOS/filesystem/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/Support/cloudphotod.md)
- [/System/Library/PrivateFrameworks/CloudTelemetry.framework/Support/cloudtelemetryd](MACHOS/filesystem/System/Library/PrivateFrameworks/CloudTelemetry.framework/Support/cloudtelemetryd.md)
- [/System/Library/PrivateFrameworks/CommunicationTrust.framework/Support/communicationtrustd](MACHOS/filesystem/System/Library/PrivateFrameworks/CommunicationTrust.framework/Support/communicationtrustd.md)
- [/System/Library/PrivateFrameworks/CompanionCamera.framework/Support/companioncamerad](MACHOS/filesystem/System/Library/PrivateFrameworks/CompanionCamera.framework/Support/companioncamerad.md)
- [/System/Library/PrivateFrameworks/CompanionInferenceCore.framework/companioninferenceserviced](MACHOS/filesystem/System/Library/PrivateFrameworks/CompanionInferenceCore.framework/companioninferenceserviced.md)
- [/System/Library/PrivateFrameworks/ContinuousDialogManagerService.framework/assistant_cdmd](MACHOS/filesystem/System/Library/PrivateFrameworks/ContinuousDialogManagerService.framework/assistant_cdmd.md)
- [/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd](MACHOS/filesystem/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd.md)
- [/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsagent](MACHOS/filesystem/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsagent.md)
- [/System/Library/PrivateFrameworks/CoreParsec.framework/parsec-fbf](MACHOS/filesystem/System/Library/PrivateFrameworks/CoreParsec.framework/parsec-fbf.md)
- [/System/Library/PrivateFrameworks/CoreParsec.framework/parsecd](MACHOS/filesystem/System/Library/PrivateFrameworks/CoreParsec.framework/parsecd.md)
- [/System/Library/PrivateFrameworks/CoreRE.framework/default-binaryarchive.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/CoreRE.framework/default-binaryarchive.metallib.md)
- [/System/Library/PrivateFrameworks/CoreRE.framework/mxi-binaryarchive.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/CoreRE.framework/mxi-binaryarchive.metallib.md)
- [/System/Library/PrivateFrameworks/CoreRE3DGSFoundation.framework/archive.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/CoreRE3DGSFoundation.framework/archive.metallib.md)
- [/System/Library/PrivateFrameworks/CoreThreadCommissionerService.framework/CoreThreadCommissionerServiced](MACHOS/filesystem/System/Library/PrivateFrameworks/CoreThreadCommissionerService.framework/CoreThreadCommissionerServiced.md)
- [/System/Library/PrivateFrameworks/CoreThreadRadio.framework/threadradiod](MACHOS/filesystem/System/Library/PrivateFrameworks/CoreThreadRadio.framework/threadradiod.md)
- [/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/DTServiceHub](MACHOS/filesystem/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/DTServiceHub.md)
- [/System/Library/PrivateFrameworks/DeviceRecovery.framework/Support/devicerecoveryd](MACHOS/filesystem/System/Library/PrivateFrameworks/DeviceRecovery.framework/Support/devicerecoveryd.md)
- [/System/Library/PrivateFrameworks/DeviceRecoveryBrainSupport.framework/XPCServices/com.apple.DeviceRecoveryBuiltinBrain.xpc/com.apple.DeviceRecoveryBuiltinBrain](MACHOS/filesystem/System/Library/PrivateFrameworks/DeviceRecoveryBrainSupport.framework/XPCServices/com.apple.DeviceRecoveryBuiltinBrain.xpc/com.apple.DeviceRecoveryBuiltinBrain.md)
- [/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/AirPlayDiagnosticExtension.appex/AirPlayDiagnosticExtension](MACHOS/filesystem/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/AirPlayDiagnosticExtension.appex/AirPlayDiagnosticExtension.md)
- [/System/Library/PrivateFrameworks/EcosystemAnalytics.framework/Support/ecosystemanalyticsd](MACHOS/filesystem/System/Library/PrivateFrameworks/EcosystemAnalytics.framework/Support/ecosystemanalyticsd.md)
- [/System/Library/PrivateFrameworks/FaceTimeMessageStore.framework/facetimemessagestored](MACHOS/filesystem/System/Library/PrivateFrameworks/FaceTimeMessageStore.framework/facetimemessagestored.md)
- [/System/Library/PrivateFrameworks/GPUToolsCapture.framework/GPUToolsCapture](MACHOS/filesystem/System/Library/PrivateFrameworks/GPUToolsCapture.framework/GPUToolsCapture.md)
- [/System/Library/PrivateFrameworks/GenerationalStorage.framework/revisiond](MACHOS/filesystem/System/Library/PrivateFrameworks/GenerationalStorage.framework/revisiond.md)
- [/System/Library/PrivateFrameworks/GeoServices.framework/geod](MACHOS/filesystem/System/Library/PrivateFrameworks/GeoServices.framework/geod.md)
- [/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/HangLogsDiagnosticExtension.appex/HangLogsDiagnosticExtension](MACHOS/filesystem/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/HangLogsDiagnosticExtension.appex/HangLogsDiagnosticExtension.md)
- [/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/PerformanceLoggingDiagnosticExtension.appex/PerformanceLoggingDiagnosticExtension](MACHOS/filesystem/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/PerformanceLoggingDiagnosticExtension.appex/PerformanceLoggingDiagnosticExtension.md)
- [/System/Library/PrivateFrameworks/HealthPluginHost.framework/healthappd](MACHOS/filesystem/System/Library/PrivateFrameworks/HealthPluginHost.framework/healthappd.md)
- [/System/Library/PrivateFrameworks/HomeEnergyDaemon.framework/Support/homeenergyd](MACHOS/filesystem/System/Library/PrivateFrameworks/HomeEnergyDaemon.framework/Support/homeenergyd.md)
- [/System/Library/PrivateFrameworks/HomeKitDaemon.framework/Support/homed](MACHOS/filesystem/System/Library/PrivateFrameworks/HomeKitDaemon.framework/Support/homed.md)
- [/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd](MACHOS/filesystem/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd.md)
- [/System/Library/PrivateFrameworks/IMCore.framework/imagent.app/imagent](MACHOS/filesystem/System/Library/PrivateFrameworks/IMCore.framework/imagent.app/imagent.md)
- [/System/Library/PrivateFrameworks/IconRendering.framework/binary.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/IconRendering.framework/binary.metallib.md)
- [/System/Library/PrivateFrameworks/InstallCoordination.framework/Support/installcoordination_proxy](MACHOS/filesystem/System/Library/PrivateFrameworks/InstallCoordination.framework/Support/installcoordination_proxy.md)
- [/System/Library/PrivateFrameworks/InstallCoordination.framework/Support/installcoordinationd](MACHOS/filesystem/System/Library/PrivateFrameworks/InstallCoordination.framework/Support/installcoordinationd.md)
- [/System/Library/PrivateFrameworks/IntelligenceFlowContextRuntime.framework/intelligencecontextd](MACHOS/filesystem/System/Library/PrivateFrameworks/IntelligenceFlowContextRuntime.framework/intelligencecontextd.md)
- [/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/PlugIns/IntelligenceFlowCustomerDiagnostics.appex/IntelligenceFlowCustomerDiagnostics](MACHOS/filesystem/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/PlugIns/IntelligenceFlowCustomerDiagnostics.appex/IntelligenceFlowCustomerDiagnostics.md)
- [/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/PlugIns/IntelligenceFlowDiagnostics.appex/IntelligenceFlowDiagnostics](MACHOS/filesystem/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/PlugIns/IntelligenceFlowDiagnostics.appex/IntelligenceFlowDiagnostics.md)
- [/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/intelligenceflowd](MACHOS/filesystem/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/intelligenceflowd.md)
- [/System/Library/PrivateFrameworks/JetCore.framework/Support/jetpackassetd](MACHOS/filesystem/System/Library/PrivateFrameworks/JetCore.framework/Support/jetpackassetd.md)
- [/System/Library/PrivateFrameworks/MXI.framework/mxi_archive.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/MXI.framework/mxi_archive.metallib.md)
- [/System/Library/PrivateFrameworks/MapsSuggestions.framework/destinationd](MACHOS/filesystem/System/Library/PrivateFrameworks/MapsSuggestions.framework/destinationd.md)
- [/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd](MACHOS/filesystem/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd.md)
- [/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd-service](MACHOS/filesystem/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd-service.md)
- [/System/Library/PrivateFrameworks/MediaRemote.framework/Support/mediaremoted](MACHOS/filesystem/System/Library/PrivateFrameworks/MediaRemote.framework/Support/mediaremoted.md)
- [/System/Library/PrivateFrameworks/MentalHealthUI.framework/archive.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/MentalHealthUI.framework/archive.metallib.md)
- [/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/Support/accessoryupdaterd](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/Support/accessoryupdaterd.md)
- [/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/EAUpdaterService.xpc/EAUpdaterService](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/EAUpdaterService.xpc/EAUpdaterService.md)
- [/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/UARPUpdaterServiceHID.xpc/UARPUpdaterServiceHID](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/UARPUpdaterServiceHID.xpc/UARPUpdaterServiceHID.md)
- [/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/UARPUpdaterServiceLegacyAudio.xpc/UARPUpdaterServiceLegacyAudio](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/UARPUpdaterServiceLegacyAudio.xpc/UARPUpdaterServiceLegacyAudio.md)
- [/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/UARPUpdaterServiceUSBPD.xpc/UARPUpdaterServiceUSBPD](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/UARPUpdaterServiceUSBPD.xpc/UARPUpdaterServiceUSBPD.md)
- [/System/Library/PrivateFrameworks/MobileAsset.framework/XPCServices/ManifestStorageService.xpc/ManifestStorageService](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileAsset.framework/XPCServices/ManifestStorageService.xpc/ManifestStorageService.md)
- [/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/XPCServices/com.apple.MobileAsset.DownloadService.Builtin.xpc/com.apple.MobileAsset.DownloadService.Builtin](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/XPCServices/com.apple.MobileAsset.DownloadService.Builtin.xpc/com.apple.MobileAsset.DownloadService.Builtin.md)
- [/System/Library/PrivateFrameworks/MobileBackup.framework/backupd](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileBackup.framework/backupd.md)
- [/System/Library/PrivateFrameworks/MobileInstallation.framework/XPCServices/com.apple.MobileInstallationHelperService.xpc/com.apple.MobileInstallationHelperService](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileInstallation.framework/XPCServices/com.apple.MobileInstallationHelperService.xpc/com.apple.MobileInstallationHelperService.md)
- [/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Support/softwareupdated](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Support/softwareupdated.md)
- [/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/XPCServices/com.apple.MobileSoftwareUpdate.CleanupPreparePathService.xpc/com.apple.MobileSoftwareUpdate.CleanupPreparePathService](MACHOS/filesystem/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/XPCServices/com.apple.MobileSoftwareUpdate.CleanupPreparePathService.xpc/com.apple.MobileSoftwareUpdate.CleanupPreparePathService.md)
- [/System/Library/PrivateFrameworks/NanoBackup.framework/nanobackupd](MACHOS/filesystem/System/Library/PrivateFrameworks/NanoBackup.framework/nanobackupd.md)
- [/System/Library/PrivateFrameworks/NanoPreferencesSync.framework/nanoprefsyncd](MACHOS/filesystem/System/Library/PrivateFrameworks/NanoPreferencesSync.framework/nanoprefsyncd.md)
- [/System/Library/PrivateFrameworks/NanoSystemSettings.framework/nanosystemsettingsd](MACHOS/filesystem/System/Library/PrivateFrameworks/NanoSystemSettings.framework/nanosystemsettingsd.md)
- [/System/Library/PrivateFrameworks/NanoUniverse.framework/NUNICalliopeShadersCompanion.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/NanoUniverse.framework/NUNICalliopeShadersCompanion.metallib.md)
- [/System/Library/PrivateFrameworks/OmniSearch.framework/searchtoold](MACHOS/filesystem/System/Library/PrivateFrameworks/OmniSearch.framework/searchtoold.md)
- [/System/Library/PrivateFrameworks/PassKitCore.framework/passd](MACHOS/filesystem/System/Library/PrivateFrameworks/PassKitCore.framework/passd.md)
- [/System/Library/PrivateFrameworks/PersonalizedSensing.framework/XPCServices/PersonalizedSensingService.xpc/PersonalizedSensingService](MACHOS/filesystem/System/Library/PrivateFrameworks/PersonalizedSensing.framework/XPCServices/PersonalizedSensingService.xpc/PersonalizedSensingService.md)
- [/System/Library/PrivateFrameworks/PhotoAnalysis.framework/Support/photoanalysisd](MACHOS/filesystem/System/Library/PrivateFrameworks/PhotoAnalysis.framework/Support/photoanalysisd.md)
- [/System/Library/PrivateFrameworks/Portrait.framework/binaryArchive.g18p](MACHOS/filesystem/System/Library/PrivateFrameworks/Portrait.framework/binaryArchive.g18p.md)
- [/System/Library/PrivateFrameworks/Portrait.framework/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/PrivateFrameworks/Portrait.framework/binaryArchive.g18p_a0.md)
- [/System/Library/PrivateFrameworks/Recon3D.framework/Reconstruction_Gpu_Archive.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/Recon3D.framework/Reconstruction_Gpu_Archive.metallib.md)
- [/System/Library/PrivateFrameworks/RenderBox.framework/archive.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/RenderBox.framework/archive.metallib.md)
- [/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeAgent](MACHOS/filesystem/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeAgent.md)
- [/System/Library/PrivateFrameworks/SiriUICore.framework/archive.metallib](MACHOS/filesystem/System/Library/PrivateFrameworks/SiriUICore.framework/archive.metallib.md)
- [/System/Library/PrivateFrameworks/SiriVOX.framework/SiriHeadlessService](MACHOS/filesystem/System/Library/PrivateFrameworks/SiriVOX.framework/SiriHeadlessService.md)
- [/System/Library/PrivateFrameworks/SleepDaemon.framework/sleepd](MACHOS/filesystem/System/Library/PrivateFrameworks/SleepDaemon.framework/sleepd.md)
- [/System/Library/PrivateFrameworks/StreamingExtractor.framework/XPCServices/STExtractionService.privileged.xpc/STExtractionService.privileged](MACHOS/filesystem/System/Library/PrivateFrameworks/StreamingExtractor.framework/XPCServices/STExtractionService.privileged.xpc/STExtractionService.privileged.md)
- [/System/Library/PrivateFrameworks/StreamingExtractor.framework/XPCServices/STExtractionService.xpc/STExtractionService](MACHOS/filesystem/System/Library/PrivateFrameworks/StreamingExtractor.framework/XPCServices/STExtractionService.xpc/STExtractionService.md)
- [/System/Library/PrivateFrameworks/StreamingZip.framework/XPCServices/com.apple.StreamingUnzipService.privileged.xpc/com.apple.StreamingUnzipService.privileged](MACHOS/filesystem/System/Library/PrivateFrameworks/StreamingZip.framework/XPCServices/com.apple.StreamingUnzipService.privileged.xpc/com.apple.StreamingUnzipService.privileged.md)
- [/System/Library/PrivateFrameworks/StreamingZip.framework/XPCServices/com.apple.StreamingUnzipService.xpc/com.apple.StreamingUnzipService](MACHOS/filesystem/System/Library/PrivateFrameworks/StreamingZip.framework/XPCServices/com.apple.StreamingUnzipService.xpc/com.apple.StreamingUnzipService.md)
- [/System/Library/PrivateFrameworks/SuggestedImage.framework/Support/imageplaygroundd](MACHOS/filesystem/System/Library/PrivateFrameworks/SuggestedImage.framework/Support/imageplaygroundd.md)
- [/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd](MACHOS/filesystem/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd.md)
- [/System/Library/PrivateFrameworks/TextToSpeechVoiceBankingSupport.framework/Support/voicebankingd](MACHOS/filesystem/System/Library/PrivateFrameworks/TextToSpeechVoiceBankingSupport.framework/Support/voicebankingd.md)
- [/System/Library/PrivateFrameworks/TranslationUIServices.framework/PlugIns/TranslationUIService.appex/TranslationUIService](MACHOS/filesystem/System/Library/PrivateFrameworks/TranslationUIServices.framework/PlugIns/TranslationUIService.appex/TranslationUIService.md)
- [/System/Library/PrivateFrameworks/UIKitCore.framework/Artwork.bundle/Artwork](MACHOS/filesystem/System/Library/PrivateFrameworks/UIKitCore.framework/Artwork.bundle/Artwork.md)
- [/System/Library/PrivateFrameworks/UIKitCore.framework/BoundingPathData.bundle/BoundingPathData](MACHOS/filesystem/System/Library/PrivateFrameworks/UIKitCore.framework/BoundingPathData.bundle/BoundingPathData.md)
- [/System/Library/PrivateFrameworks/UIKitCore.framework/CarPlayArtwork.bundle/CarPlayArtwork](MACHOS/filesystem/System/Library/PrivateFrameworks/UIKitCore.framework/CarPlayArtwork.bundle/CarPlayArtwork.md)
- [/System/Library/PrivateFrameworks/UIKitCore.framework/TextEffectsCatalog.bundle/TextEffectsCatalog](MACHOS/filesystem/System/Library/PrivateFrameworks/UIKitCore.framework/TextEffectsCatalog.bundle/TextEffectsCatalog.md)
- [/System/Library/PrivateFrameworks/UIKitCore.framework/XPCServices/SecureControlService.xpc/SecureControlService](MACHOS/filesystem/System/Library/PrivateFrameworks/UIKitCore.framework/XPCServices/SecureControlService.xpc/SecureControlService.md)
- [/System/Library/PrivateFrameworks/UserActivity.framework/Agents/useractivityd](MACHOS/filesystem/System/Library/PrivateFrameworks/UserActivity.framework/Agents/useractivityd.md)
- [/System/Library/PrivateFrameworks/VisualIntelligenceServices.framework/visualintelligenced](MACHOS/filesystem/System/Library/PrivateFrameworks/VisualIntelligenceServices.framework/visualintelligenced.md)
- [/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Support/siriactionsd](MACHOS/filesystem/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Support/siriactionsd.md)
- [/System/Library/PrivateFrameworks/WeatherDaemon.framework/weatherd](MACHOS/filesystem/System/Library/PrivateFrameworks/WeatherDaemon.framework/weatherd.md)
- [/System/Library/PrivateFrameworks/homerecommendationutil](MACHOS/filesystem/System/Library/PrivateFrameworks/homerecommendationutil.md)
- [/System/Library/PrivateFrameworks/iCloudDriveCore.framework/bird](MACHOS/filesystem/System/Library/PrivateFrameworks/iCloudDriveCore.framework/bird.md)
- [/System/Library/PrivateFrameworks/iTunesCloud.framework/Support/itunescloudd](MACHOS/filesystem/System/Library/PrivateFrameworks/iTunesCloud.framework/Support/itunescloudd.md)
- [/System/Library/PrivateFrameworks/iTunesStore.framework/Support/itunesstored](MACHOS/filesystem/System/Library/PrivateFrameworks/iTunesStore.framework/Support/itunesstored.md)
- [/System/Library/SubFrameworks/ARKitCore.framework/deflicker-binary-applegpu_g18p.metallib](MACHOS/filesystem/System/Library/SubFrameworks/ARKitCore.framework/deflicker-binary-applegpu_g18p.metallib.md)
- [/System/Library/SubFrameworks/ARKitCore.framework/deflicker-binary.metallib](MACHOS/filesystem/System/Library/SubFrameworks/ARKitCore.framework/deflicker-binary.metallib.md)
- [/System/Library/SyncBundles/Books.syncBundle/Books](MACHOS/filesystem/System/Library/SyncBundles/Books.syncBundle/Books.md)
- [/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF](MACHOS/filesystem/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF.md)
- [/System/Library/Video/Plug-Ins/AppleVideoEncoder.bundle/AppleVideoEncoder](MACHOS/filesystem/System/Library/Video/Plug-Ins/AppleVideoEncoder.bundle/AppleVideoEncoder.md)
- [/System/Library/VideoProcessors/CCPortrait.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/CCPortrait.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/CCPortrait.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/CCPortrait.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/CCPortrait.bundle/ccportrait_archive_bin.metallib](MACHOS/filesystem/System/Library/VideoProcessors/CCPortrait.bundle/ccportrait_archive_bin.metallib.md)
- [/System/Library/VideoProcessors/ColourConstancyV1.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/ColourConstancyV1.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/ColourConstancyV1.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/ColourConstancyV1.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/DepthProcessorV2.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/DepthProcessorV2.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/DepthProcessorV2.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/DepthProcessorV2.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/DisparityV5.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/DisparityV5.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/DisparityV5.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/DisparityV5.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/GenIEV1.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/GenIEV1.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/GenIEV1.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/GenIEV1.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/IntelligentDistortionCorrectionV1.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/IntelligentDistortionCorrectionV1.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/IntelligentDistortionCorrectionV1.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/IntelligentDistortionCorrectionV1.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/MattingV2.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/MattingV2.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/MattingV2.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/MattingV2.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/MetalFilter.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/MetalFilter.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/MetalFilter.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/MetalFilter.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/NRFV4.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/NRFV4.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/NRFV4.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/NRFV4.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/RTSCV1.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/RTSCV1.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/RTSCV1.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/RTSCV1.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/STF.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/STF.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/STF.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/STF.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/SmartStyleV1.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/SmartStyleV1.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/SmartStyleV1.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/SmartStyleV1.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/SuperResolutionV2.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/SuperResolutionV2.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/SuperResolutionV2.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/SuperResolutionV2.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/VideoDeghostingV1.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/VideoDeghostingV1.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/VideoDeghostingV1.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/VideoDeghostingV1.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/VideoDeghostingV2.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/VideoDeghostingV2.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/VideoDeghostingV2.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/VideoDeghostingV2.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/VideoDeghostingV3.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/VideoDeghostingV3.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/VideoDeghostingV3.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/VideoDeghostingV3.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/VideoProcessors/VideoStabilizationV2.bundle/binaryArchive.g18p](MACHOS/filesystem/System/Library/VideoProcessors/VideoStabilizationV2.bundle/binaryArchive.g18p.md)
- [/System/Library/VideoProcessors/VideoStabilizationV2.bundle/binaryArchive.g18p_a0](MACHOS/filesystem/System/Library/VideoProcessors/VideoStabilizationV2.bundle/binaryArchive.g18p_a0.md)
- [/System/Library/iCloudSettings/com.apple.Dataclass.Siri.bundle/com.apple.Dataclass.Siri](MACHOS/filesystem/System/Library/iCloudSettings/com.apple.Dataclass.Siri.bundle/com.apple.Dataclass.Siri.md)
- [/private/var/staged_system_apps/AppStore.app/AppStore](MACHOS/filesystem/private/var/staged_system_apps/AppStore.app/AppStore.md)
- [/private/var/staged_system_apps/Freeform.app/Frameworks/AppsGen.framework/AppsGen](MACHOS/filesystem/private/var/staged_system_apps/Freeform.app/Frameworks/AppsGen.framework/AppsGen.md)
- [/private/var/staged_system_apps/Home.app/Home](MACHOS/filesystem/private/var/staged_system_apps/Home.app/Home.md)
- [/private/var/staged_system_apps/Home.app/PlugIns/HomeNotification.appex/HomeNotification](MACHOS/filesystem/private/var/staged_system_apps/Home.app/PlugIns/HomeNotification.appex/HomeNotification.md)
- [/private/var/staged_system_apps/Home.app/PlugIns/HomeWidget.appex/HomeWidget](MACHOS/filesystem/private/var/staged_system_apps/Home.app/PlugIns/HomeWidget.appex/HomeWidget.md)
- [/private/var/staged_system_apps/Journal.app/Journal](MACHOS/filesystem/private/var/staged_system_apps/Journal.app/Journal.md)
- [/private/var/staged_system_apps/KaleidoscopePosterApp.app/Extensions/KaleidoscopePoster.appex/NTKKaleidoscopeShaders.metallib](MACHOS/filesystem/private/var/staged_system_apps/KaleidoscopePosterApp.app/Extensions/KaleidoscopePoster.appex/NTKKaleidoscopeShaders.metallib.md)
- [/private/var/staged_system_apps/Measure.app/Measure](MACHOS/filesystem/private/var/staged_system_apps/Measure.app/Measure.md)
- [/private/var/staged_system_apps/SequoiaTranslator.app/PlugIns/TranslationWidgetsExtension.appex/TranslationWidgetsExtension](MACHOS/filesystem/private/var/staged_system_apps/SequoiaTranslator.app/PlugIns/TranslationWidgetsExtension.appex/TranslationWidgetsExtension.md)
- [/private/var/staged_system_apps/SequoiaTranslator.app/SequoiaTranslator](MACHOS/filesystem/private/var/staged_system_apps/SequoiaTranslator.app/SequoiaTranslator.md)
- [/private/var/staged_system_apps/Shortcuts.app/Shortcuts](MACHOS/filesystem/private/var/staged_system_apps/Shortcuts.app/Shortcuts.md)
- [/private/var/staged_system_apps/VoiceMemos.app/VoiceMemos](MACHOS/filesystem/private/var/staged_system_apps/VoiceMemos.app/VoiceMemos.md)
- [/sbin/launchd](MACHOS/filesystem/sbin/launchd.md)
- [/usr/bin/afktool](MACHOS/filesystem/usr/bin/afktool.md)
- [/usr/lib/dyld](MACHOS/filesystem/usr/lib/dyld.md)
- [/usr/libexec/DumpPanic](MACHOS/filesystem/usr/libexec/DumpPanic.md)
- [/usr/libexec/NRDUpdated](MACHOS/filesystem/usr/libexec/NRDUpdated.md)
- [/usr/libexec/ReportMemoryException](MACHOS/filesystem/usr/libexec/ReportMemoryException.md)
- [/usr/libexec/ValidUpdater](MACHOS/filesystem/usr/libexec/ValidUpdater.md)
- [/usr/libexec/airplayd](MACHOS/filesystem/usr/libexec/airplayd.md)
- [/usr/libexec/anomalydetectiond](MACHOS/filesystem/usr/libexec/anomalydetectiond.md)
- [/usr/libexec/aonsensed](MACHOS/filesystem/usr/libexec/aonsensed.md)
- [/usr/libexec/appleaccountd](MACHOS/filesystem/usr/libexec/appleaccountd.md)
- [/usr/libexec/applekeystored](MACHOS/filesystem/usr/libexec/applekeystored.md)
- [/usr/libexec/arkitd](MACHOS/filesystem/usr/libexec/arkitd.md)
- [/usr/libexec/assessmentagent](MACHOS/filesystem/usr/libexec/assessmentagent.md)
- [/usr/libexec/audioaccessoryd](MACHOS/filesystem/usr/libexec/audioaccessoryd.md)
- [/usr/libexec/avconferenced](MACHOS/filesystem/usr/libexec/avconferenced.md)
- [/usr/libexec/biometrickitd](MACHOS/filesystem/usr/libexec/biometrickitd.md)
- [/usr/libexec/bluetoothuserd](MACHOS/filesystem/usr/libexec/bluetoothuserd.md)
- [/usr/libexec/callverificationd](MACHOS/filesystem/usr/libexec/callverificationd.md)
- [/usr/libexec/cameracaptured](MACHOS/filesystem/usr/libexec/cameracaptured.md)
- [/usr/libexec/cameraispd](MACHOS/filesystem/usr/libexec/cameraispd.md)
- [/usr/libexec/checkpointd](MACHOS/filesystem/usr/libexec/checkpointd.md)
- [/usr/libexec/companion_proxy](MACHOS/filesystem/usr/libexec/companion_proxy.md)
- [/usr/libexec/companiond](MACHOS/filesystem/usr/libexec/companiond.md)
- [/usr/libexec/continuitycaptured](MACHOS/filesystem/usr/libexec/continuitycaptured.md)
- [/usr/libexec/coreidvd](MACHOS/filesystem/usr/libexec/coreidvd.md)
- [/usr/libexec/corerepaird](MACHOS/filesystem/usr/libexec/corerepaird.md)
- [/usr/libexec/cryptexd](MACHOS/filesystem/usr/libexec/cryptexd.md)
- [/usr/libexec/dasd](MACHOS/filesystem/usr/libexec/dasd.md)
- [/usr/libexec/deferredmediad](MACHOS/filesystem/usr/libexec/deferredmediad.md)
- [/usr/libexec/demod](MACHOS/filesystem/usr/libexec/demod.md)
- [/usr/libexec/devicesharingd](MACHOS/filesystem/usr/libexec/devicesharingd.md)
- [/usr/libexec/diskimagesiod](MACHOS/filesystem/usr/libexec/diskimagesiod.md)
- [/usr/libexec/dockaccessoryd](MACHOS/filesystem/usr/libexec/dockaccessoryd.md)
- [/usr/libexec/eligibilityd](MACHOS/filesystem/usr/libexec/eligibilityd.md)
- [/usr/libexec/enhancedloggingd](MACHOS/filesystem/usr/libexec/enhancedloggingd.md)
- [/usr/libexec/feedbackd](MACHOS/filesystem/usr/libexec/feedbackd.md)
- [/usr/libexec/gamed](MACHOS/filesystem/usr/libexec/gamed.md)
- [/usr/libexec/gpsd](MACHOS/filesystem/usr/libexec/gpsd.md)
- [/usr/libexec/hangreporter](MACHOS/filesystem/usr/libexec/hangreporter.md)
- [/usr/libexec/hangtelemetryd](MACHOS/filesystem/usr/libexec/hangtelemetryd.md)
- [/usr/libexec/hangtracerd](MACHOS/filesystem/usr/libexec/hangtracerd.md)
- [/usr/libexec/hybridsearchd](MACHOS/filesystem/usr/libexec/hybridsearchd.md)
- [/usr/libexec/icloudmailagent](MACHOS/filesystem/usr/libexec/icloudmailagent.md)
- [/usr/libexec/idcredd](MACHOS/filesystem/usr/libexec/idcredd.md)
- [/usr/libexec/installd](MACHOS/filesystem/usr/libexec/installd.md)
- [/usr/libexec/keychainsharingmessagingd](MACHOS/filesystem/usr/libexec/keychainsharingmessagingd.md)
- [/usr/libexec/locationd](MACHOS/filesystem/usr/libexec/locationd.md)
- [/usr/libexec/logd_helper](MACHOS/filesystem/usr/libexec/logd_helper.md)
- [/usr/libexec/magicswitchd](MACHOS/filesystem/usr/libexec/magicswitchd.md)
- [/usr/libexec/managedappsd](MACHOS/filesystem/usr/libexec/managedappsd.md)
- [/usr/libexec/mdmd](MACHOS/filesystem/usr/libexec/mdmd.md)
- [/usr/libexec/mdmuserd](MACHOS/filesystem/usr/libexec/mdmuserd.md)
- [/usr/libexec/merchantd](MACHOS/filesystem/usr/libexec/merchantd.md)
- [/usr/libexec/mobileactivationd](MACHOS/filesystem/usr/libexec/mobileactivationd.md)
- [/usr/libexec/mobileassetd](MACHOS/filesystem/usr/libexec/mobileassetd.md)
- [/usr/libexec/modelmanagerd](MACHOS/filesystem/usr/libexec/modelmanagerd.md)
- [/usr/libexec/momentsd](MACHOS/filesystem/usr/libexec/momentsd.md)
- [/usr/libexec/nanoregistryd](MACHOS/filesystem/usr/libexec/nanoregistryd.md)
- [/usr/libexec/networkserviceproxy](MACHOS/filesystem/usr/libexec/networkserviceproxy.md)
- [/usr/libexec/nptocompaniond](MACHOS/filesystem/usr/libexec/nptocompaniond.md)
- [/usr/libexec/perfdiagsselfenabled](MACHOS/filesystem/usr/libexec/perfdiagsselfenabled.md)
- [/usr/libexec/photosfaced](MACHOS/filesystem/usr/libexec/photosfaced.md)
- [/usr/libexec/proactiveeventtrackerd](MACHOS/filesystem/usr/libexec/proactiveeventtrackerd.md)
- [/usr/libexec/promotedcontentd](MACHOS/filesystem/usr/libexec/promotedcontentd.md)
- [/usr/libexec/ptpd](MACHOS/filesystem/usr/libexec/ptpd.md)
- [/usr/libexec/rapportd](MACHOS/filesystem/usr/libexec/rapportd.md)
- [/usr/libexec/remindd](MACHOS/filesystem/usr/libexec/remindd.md)
- [/usr/libexec/remoteappintentsd](MACHOS/filesystem/usr/libexec/remoteappintentsd.md)
- [/usr/libexec/remotepairingdeviced](MACHOS/filesystem/usr/libexec/remotepairingdeviced.md)
- [/usr/libexec/restorecameraispd](MACHOS/filesystem/usr/libexec/restorecameraispd.md)
- [/usr/libexec/riskdatad](MACHOS/filesystem/usr/libexec/riskdatad.md)
- [/usr/libexec/royacaptured](MACHOS/filesystem/usr/libexec/royacaptured.md)
- [/usr/libexec/rtcreportingd](MACHOS/filesystem/usr/libexec/rtcreportingd.md)
- [/usr/libexec/securityd](MACHOS/filesystem/usr/libexec/securityd.md)
- [/usr/libexec/securityuploadd](MACHOS/filesystem/usr/libexec/securityuploadd.md)
- [/usr/libexec/sensingpredictd](MACHOS/filesystem/usr/libexec/sensingpredictd.md)
- [/usr/libexec/seserviced](MACHOS/filesystem/usr/libexec/seserviced.md)
- [/usr/libexec/signpost_reporter](MACHOS/filesystem/usr/libexec/signpost_reporter.md)
- [/usr/libexec/spindump_fileparser](MACHOS/filesystem/usr/libexec/spindump_fileparser.md)
- [/usr/libexec/sportsd](MACHOS/filesystem/usr/libexec/sportsd.md)
- [/usr/libexec/srp-mdns-proxy](MACHOS/filesystem/usr/libexec/srp-mdns-proxy.md)
- [/usr/libexec/swtransparencyd](MACHOS/filesystem/usr/libexec/swtransparencyd.md)
- [/usr/libexec/symptomsd-diag](MACHOS/filesystem/usr/libexec/symptomsd-diag.md)
- [/usr/libexec/tailspind](MACHOS/filesystem/usr/libexec/tailspind.md)
- [/usr/libexec/terminusd](MACHOS/filesystem/usr/libexec/terminusd.md)
- [/usr/libexec/tipsd](MACHOS/filesystem/usr/libexec/tipsd.md)
- [/usr/libexec/transparencyd](MACHOS/filesystem/usr/libexec/transparencyd.md)
- [/usr/libexec/uarpassetmanagerd](MACHOS/filesystem/usr/libexec/uarpassetmanagerd.md)
- [/usr/libexec/uarpd](MACHOS/filesystem/usr/libexec/uarpd.md)
- [/usr/libexec/visioncompaniond](MACHOS/filesystem/usr/libexec/visioncompaniond.md)
- [/usr/libexec/wifianalyticsd](MACHOS/filesystem/usr/libexec/wifianalyticsd.md)
- [/usr/libexec/wifip2pd](MACHOS/filesystem/usr/libexec/wifip2pd.md)
- [/usr/libexec/wifivelocityd](MACHOS/filesystem/usr/libexec/wifivelocityd.md)
- [/usr/libexec/xpcproxy](MACHOS/filesystem/usr/libexec/xpcproxy.md)
- [/usr/libexec/xpcroleaccountd](MACHOS/filesystem/usr/libexec/xpcroleaccountd.md)
- [/usr/sbin/BlueTool](MACHOS/filesystem/usr/sbin/BlueTool.md)
- [/usr/sbin/WirelessRadioManagerd](MACHOS/filesystem/usr/sbin/WirelessRadioManagerd.md)
- [/usr/sbin/bluetoothd](MACHOS/filesystem/usr/sbin/bluetoothd.md)
- [/usr/sbin/mDNSResponder](MACHOS/filesystem/usr/sbin/mDNSResponder.md)
- [/usr/sbin/spindump](MACHOS/filesystem/usr/sbin/spindump.md)
- [/usr/sbin/wifid](MACHOS/filesystem/usr/sbin/wifid.md)

</details>

### SystemOS

#### ⬆️ Updated (1)

- [/usr/libexec/Moments.framework/Moments](MACHOS/SystemOS/usr/libexec/Moments.framework/Moments.md)

### AppOS

#### ⬆️ Updated (1)

- [/usr/libexec/browserkitd](MACHOS/AppOS/usr/libexec/browserkitd.md)

### ExclaveOS

#### ⬆️ Updated (2)

- [/System/ExclaveKit/System/Library/Frameworks/CodeCoverageDelegate.framework/CodeCoverageDelegate](MACHOS/ExclaveOS/System/ExclaveKit/System/Library/Frameworks/CodeCoverageDelegate.framework/CodeCoverageDelegate.md)
- [/System/ExclaveKit/System/Library/Frameworks/IISAudioOutputStreamClientNotifierComponent.framework/IISAudioOutputStreamClientNotifierComponent](MACHOS/ExclaveOS/System/ExclaveKit/System/Library/Frameworks/IISAudioOutputStreamClientNotifierComponent.framework/IISAudioOutputStreamClientNotifierComponent.md)

### 🔑 Entitlements

- [Entitlements DIFF](Entitlements.md)

## Firmware

### ⬆️ Updated (17)

- [Firmware/M3/bin/securem3fw-v5x.im4p](FIRMWARE/Firmware/M3/bin/securem3fw-v5x.im4p.md)
- [Firmware/agx/armfw_g18p.im4p/agx_a000](FIRMWARE/Firmware/agx/armfw_g18p.im4p/agx_a000.md)
- [Firmware/agx/armfw_g18p.im4p/agx_a010](FIRMWARE/Firmware/agx/armfw_g18p.im4p/agx_a010.md)
- [Firmware/agx/armfw_g18p.im4p/agx_b000](FIRMWARE/Firmware/agx/armfw_g18p.im4p/agx_b000.md)
- [Firmware/ane/h18_ane_fw_apollo_v5x.im4p](FIRMWARE/Firmware/ane/h18_ane_fw_apollo_v5x.im4p.md)
- [Firmware/ansf.t8150.release.im4p](FIRMWARE/Firmware/ansf.t8150.release.im4p.md)
- [Firmware/ave/AppleAVE2FW_H18.im4p](FIRMWARE/Firmware/ave/AppleAVE2FW_H18.im4p.md)
- [Firmware/image4/exclavecore_bundle.t8150.RELEASE.im4p/exclave_kernel](FIRMWARE/Firmware/image4/exclavecore_bundle.t8150.RELEASE.im4p/exclave_kernel.md)
- [Firmware/image4/exclavecore_bundle.t8150.RELEASE.im4p/exclave_sharedcache](FIRMWARE/Firmware/image4/exclavecore_bundle.t8150.RELEASE.im4p/exclave_sharedcache.md)
- [Firmware/image4/exclavecore_bundle.t8150.RELEASE.restore.im4p/exclave_kernel](FIRMWARE/Firmware/image4/exclavecore_bundle.t8150.RELEASE.restore.im4p/exclave_kernel.md)
- [Firmware/image4/exclavecore_bundle.t8150.RELEASE.restore.im4p/exclave_sharedcache](FIRMWARE/Firmware/image4/exclavecore_bundle.t8150.RELEASE.restore.im4p/exclave_sharedcache.md)
- [Firmware/isp_bni/adc-silenus-v5x.im4p](FIRMWARE/Firmware/isp_bni/adc-silenus-v5x.im4p.md)
- [Firmware/msr/t8150.msrf.im4p](FIRMWARE/Firmware/msr/t8150.msrf.im4p.md)
- [Firmware/msr/t8150.rmsr.im4p](FIRMWARE/Firmware/msr/t8150.rmsr.im4p.md)
- [Firmware/rans.t8150.release.im4p](FIRMWARE/Firmware/rans.t8150.release.im4p.md)
- [Firmware/sptm.t8150.release.im4p](FIRMWARE/Firmware/sptm.t8150.release.im4p.md)
- [Firmware/txm.iphoneos.release.im4p](FIRMWARE/Firmware/txm.iphoneos.release.im4p.md)

### iBoot

| iOS | Version |
| :-- | :------ |
| 27.2 *(24B5110a)* | mBoot-20457.42.4 |
| 27.2 *(24B115)* | mBoot-20457.42.5 |

## DSC

### WebKit

| iOS | Version |
| :-- | :------ |
| 27.2 *(24B5110a)* | 625.2.8.10.4 |
| 27.2 *(24B115)* | 625.2.8.10.6 |

### Dylibs

#### 🆕 NEW (1)

- `/System/Library/PrivateFrameworks/SpeakerGroupSetupKit.framework/SpeakerGroupSetupKit`

#### ⬆️ Updated (304)

<details>
  <summary><i>View Updated</i></summary>

- [/System/Library/AccessibilityBundles/Moments.axbundle/Moments](DYLIBS/System/Library/AccessibilityBundles/Moments.axbundle/Moments.md)
- [/System/Library/Frameworks/AVRouting.framework/AVRouting](DYLIBS/System/Library/Frameworks/AVRouting.framework/AVRouting.md)
- [/System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/vImage](DYLIBS/System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/vImage.md)
- [/System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBNNS.dylib](DYLIBS/System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBNNS.dylib.md)
- [/System/Library/Frameworks/AppIntents.framework/AppIntents](DYLIBS/System/Library/Frameworks/AppIntents.framework/AppIntents.md)
- [/System/Library/Frameworks/AudioToolbox.framework/AudioCodecs](DYLIBS/System/Library/Frameworks/AudioToolbox.framework/AudioCodecs.md)
- [/System/Library/Frameworks/AudioToolbox.framework/AudioToolbox](DYLIBS/System/Library/Frameworks/AudioToolbox.framework/AudioToolbox.md)
- [/System/Library/Frameworks/AudioToolbox.framework/libAudioDSP.dylib](DYLIBS/System/Library/Frameworks/AudioToolbox.framework/libAudioDSP.dylib.md)
- [/System/Library/Frameworks/CoreAudio.framework/CoreAudio](DYLIBS/System/Library/Frameworks/CoreAudio.framework/CoreAudio.md)
- [/System/Library/Frameworks/CoreGraphics.framework/CoreGraphics](DYLIBS/System/Library/Frameworks/CoreGraphics.framework/CoreGraphics.md)
- [/System/Library/Frameworks/CoreLocation.framework/CoreLocation](DYLIBS/System/Library/Frameworks/CoreLocation.framework/CoreLocation.md)
- [/System/Library/Frameworks/CoreMedia.framework/CoreMedia](DYLIBS/System/Library/Frameworks/CoreMedia.framework/CoreMedia.md)
- [/System/Library/Frameworks/CoreMediaIO.framework/CoreMediaIO](DYLIBS/System/Library/Frameworks/CoreMediaIO.framework/CoreMediaIO.md)
- [/System/Library/Frameworks/CoreMotion.framework/CoreMotion](DYLIBS/System/Library/Frameworks/CoreMotion.framework/CoreMotion.md)
- [/System/Library/Frameworks/CoreTelephony.framework/CoreTelephony](DYLIBS/System/Library/Frameworks/CoreTelephony.framework/CoreTelephony.md)
- [/System/Library/Frameworks/EventKit.framework/EventKit](DYLIBS/System/Library/Frameworks/EventKit.framework/EventKit.md)
- [/System/Library/Frameworks/FileProvider.framework/FileProvider](DYLIBS/System/Library/Frameworks/FileProvider.framework/FileProvider.md)
- [/System/Library/Frameworks/Foundation.framework/Foundation](DYLIBS/System/Library/Frameworks/Foundation.framework/Foundation.md)
- [/System/Library/Frameworks/HealthKit.framework/HealthKit](DYLIBS/System/Library/Frameworks/HealthKit.framework/HealthKit.md)
- [/System/Library/Frameworks/HomeKit.framework/HomeKit](DYLIBS/System/Library/Frameworks/HomeKit.framework/HomeKit.md)
- [/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit](DYLIBS/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit.md)
- [/System/Library/Frameworks/ImageIO.framework/ImageIO](DYLIBS/System/Library/Frameworks/ImageIO.framework/ImageIO.md)
- [/System/Library/Frameworks/JavaScriptCore.framework/JavaScriptCore](DYLIBS/System/Library/Frameworks/JavaScriptCore.framework/JavaScriptCore.md)
- [/System/Library/Frameworks/LinkPresentation.framework/LinkPresentation](DYLIBS/System/Library/Frameworks/LinkPresentation.framework/LinkPresentation.md)
- [/System/Library/Frameworks/MapKit.framework/MapKit](DYLIBS/System/Library/Frameworks/MapKit.framework/MapKit.md)
- [/System/Library/Frameworks/MediaToolbox.framework/MediaToolbox](DYLIBS/System/Library/Frameworks/MediaToolbox.framework/MediaToolbox.md)
- [/System/Library/Frameworks/Metal.framework/Metal](DYLIBS/System/Library/Frameworks/Metal.framework/Metal.md)
- [/System/Library/Frameworks/MultipeerConnectivity.framework/MultipeerConnectivity](DYLIBS/System/Library/Frameworks/MultipeerConnectivity.framework/MultipeerConnectivity.md)
- [/System/Library/Frameworks/Network.framework/Network](DYLIBS/System/Library/Frameworks/Network.framework/Network.md)
- [/System/Library/Frameworks/OpenGLES.framework/libGLProgrammability.dylib](DYLIBS/System/Library/Frameworks/OpenGLES.framework/libGLProgrammability.dylib.md)
- [/System/Library/Frameworks/PaperKit.framework/PaperKit](DYLIBS/System/Library/Frameworks/PaperKit.framework/PaperKit.md)
- [/System/Library/Frameworks/Photos.framework/Photos](DYLIBS/System/Library/Frameworks/Photos.framework/Photos.md)
- [/System/Library/Frameworks/PushKit.framework/PushKit](DYLIBS/System/Library/Frameworks/PushKit.framework/PushKit.md)
- [/System/Library/Frameworks/QuartzCore.framework/QuartzCore](DYLIBS/System/Library/Frameworks/QuartzCore.framework/QuartzCore.md)
- [/System/Library/Frameworks/SafariServices.framework/SafariServices](DYLIBS/System/Library/Frameworks/SafariServices.framework/SafariServices.md)
- [/System/Library/Frameworks/SceneKit.framework/SceneKit](DYLIBS/System/Library/Frameworks/SceneKit.framework/SceneKit.md)
- [/System/Library/Frameworks/Security.framework/Security](DYLIBS/System/Library/Frameworks/Security.framework/Security.md)
- [/System/Library/Frameworks/SoundAnalysis.framework/SoundAnalysis](DYLIBS/System/Library/Frameworks/SoundAnalysis.framework/SoundAnalysis.md)
- [/System/Library/Frameworks/StoreKit.framework/StoreKit](DYLIBS/System/Library/Frameworks/StoreKit.framework/StoreKit.md)
- [/System/Library/Frameworks/SwiftUI.framework/SwiftUI](DYLIBS/System/Library/Frameworks/SwiftUI.framework/SwiftUI.md)
- [/System/Library/Frameworks/VideoToolbox.framework/VideoToolbox](DYLIBS/System/Library/Frameworks/VideoToolbox.framework/VideoToolbox.md)
- [/System/Library/Frameworks/WebKit.framework/Frameworks/libWebKitSwift.dylib](DYLIBS/System/Library/Frameworks/WebKit.framework/Frameworks/libWebKitSwift.dylib.md)
- [/System/Library/Frameworks/WebKit.framework/WebKit](DYLIBS/System/Library/Frameworks/WebKit.framework/WebKit.md)
- [/System/Library/Frameworks/WidgetKit.framework/WidgetKit](DYLIBS/System/Library/Frameworks/WidgetKit.framework/WidgetKit.md)
- [/System/Library/Frameworks/_LocationEssentials.framework/_LocationEssentials](DYLIBS/System/Library/Frameworks/_LocationEssentials.framework/_LocationEssentials.md)
- [/System/Library/Frameworks/_StoreKit_SwiftUI.framework/_StoreKit_SwiftUI](DYLIBS/System/Library/Frameworks/_StoreKit_SwiftUI.framework/_StoreKit_SwiftUI.md)
- [/System/Library/PrivateFrameworks/APTransport.framework/APTransport](DYLIBS/System/Library/PrivateFrameworks/APTransport.framework/APTransport.md)
- [/System/Library/PrivateFrameworks/ASEProcessing.framework/ASEProcessing](DYLIBS/System/Library/PrivateFrameworks/ASEProcessing.framework/ASEProcessing.md)
- [/System/Library/PrivateFrameworks/AUDeveloperSettings.framework/AUDeveloperSettings](DYLIBS/System/Library/PrivateFrameworks/AUDeveloperSettings.framework/AUDeveloperSettings.md)
- [/System/Library/PrivateFrameworks/AUSettings.framework/AUSettings](DYLIBS/System/Library/PrivateFrameworks/AUSettings.framework/AUSettings.md)
- [/System/Library/PrivateFrameworks/AVConference.framework/AVConference](DYLIBS/System/Library/PrivateFrameworks/AVConference.framework/AVConference.md)
- [/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/ViceroyTrace](DYLIBS/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/ViceroyTrace.md)
- [/System/Library/PrivateFrameworks/AgentCanvasFoundation.framework/AgentCanvasFoundation](DYLIBS/System/Library/PrivateFrameworks/AgentCanvasFoundation.framework/AgentCanvasFoundation.md)
- [/System/Library/PrivateFrameworks/AirPlayReceiver.framework/AirPlayReceiver](DYLIBS/System/Library/PrivateFrameworks/AirPlayReceiver.framework/AirPlayReceiver.md)
- [/System/Library/PrivateFrameworks/AirPlaySender.framework/AirPlaySender](DYLIBS/System/Library/PrivateFrameworks/AirPlaySender.framework/AirPlaySender.md)
- [/System/Library/PrivateFrameworks/AirPlaySupport.framework/AirPlaySupport](DYLIBS/System/Library/PrivateFrameworks/AirPlaySupport.framework/AirPlaySupport.md)
- [/System/Library/PrivateFrameworks/AnnounceDaemon.framework/AnnounceDaemon](DYLIBS/System/Library/PrivateFrameworks/AnnounceDaemon.framework/AnnounceDaemon.md)
- [/System/Library/PrivateFrameworks/Anvil.framework/Anvil](DYLIBS/System/Library/PrivateFrameworks/Anvil.framework/Anvil.md)
- [/System/Library/PrivateFrameworks/AppIntentsServices.framework/AppIntentsServices](DYLIBS/System/Library/PrivateFrameworks/AppIntentsServices.framework/AppIntentsServices.md)
- [/System/Library/PrivateFrameworks/AppStoreComponentsDaemonKit.framework/AppStoreComponentsDaemonKit](DYLIBS/System/Library/PrivateFrameworks/AppStoreComponentsDaemonKit.framework/AppStoreComponentsDaemonKit.md)
- [/System/Library/PrivateFrameworks/AppStoreDaemon.framework/AppStoreDaemon](DYLIBS/System/Library/PrivateFrameworks/AppStoreDaemon.framework/AppStoreDaemon.md)
- [/System/Library/PrivateFrameworks/AppleCVAPhoto.framework/AppleCVAPhoto](DYLIBS/System/Library/PrivateFrameworks/AppleCVAPhoto.framework/AppleCVAPhoto.md)
- [/System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices](DYLIBS/System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices.md)
- [/System/Library/PrivateFrameworks/AppleMediaServicesKitInternal.framework/AppleMediaServicesKitInternal](DYLIBS/System/Library/PrivateFrameworks/AppleMediaServicesKitInternal.framework/AppleMediaServicesKitInternal.md)
- [/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/AppleMediaServicesUI](DYLIBS/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/AppleMediaServicesUI.md)
- [/System/Library/PrivateFrameworks/AppleMediaServicesUIKitInternal.framework/AppleMediaServicesUIKitInternal](DYLIBS/System/Library/PrivateFrameworks/AppleMediaServicesUIKitInternal.framework/AppleMediaServicesUIKitInternal.md)
- [/System/Library/PrivateFrameworks/AudioAccessoryServices.framework/AudioAccessoryServices](DYLIBS/System/Library/PrivateFrameworks/AudioAccessoryServices.framework/AudioAccessoryServices.md)
- [/System/Library/PrivateFrameworks/AudioAnalyticsBase.framework/AudioAnalyticsBase](DYLIBS/System/Library/PrivateFrameworks/AudioAnalyticsBase.framework/AudioAnalyticsBase.md)
- [/System/Library/PrivateFrameworks/AudioSessionServer.framework/AudioSessionServer](DYLIBS/System/Library/PrivateFrameworks/AudioSessionServer.framework/AudioSessionServer.md)
- [/System/Library/PrivateFrameworks/AudioToolboxCore.framework/AudioToolboxCore](DYLIBS/System/Library/PrivateFrameworks/AudioToolboxCore.framework/AudioToolboxCore.md)
- [/System/Library/PrivateFrameworks/AuthKit.framework/AuthKit](DYLIBS/System/Library/PrivateFrameworks/AuthKit.framework/AuthKit.md)
- [/System/Library/PrivateFrameworks/AutoBugCaptureCore.framework/AutoBugCaptureCore](DYLIBS/System/Library/PrivateFrameworks/AutoBugCaptureCore.framework/AutoBugCaptureCore.md)
- [/System/Library/PrivateFrameworks/AvatarKit.framework/AvatarKit](DYLIBS/System/Library/PrivateFrameworks/AvatarKit.framework/AvatarKit.md)
- [/System/Library/PrivateFrameworks/BiometricKit.framework/BiometricKit](DYLIBS/System/Library/PrivateFrameworks/BiometricKit.framework/BiometricKit.md)
- [/System/Library/PrivateFrameworks/BiometricSupport.framework/BiometricSupport](DYLIBS/System/Library/PrivateFrameworks/BiometricSupport.framework/BiometricSupport.md)
- [/System/Library/PrivateFrameworks/Bom.framework/Bom](DYLIBS/System/Library/PrivateFrameworks/Bom.framework/Bom.md)
- [/System/Library/PrivateFrameworks/CMCapture.framework/CMCapture](DYLIBS/System/Library/PrivateFrameworks/CMCapture.framework/CMCapture.md)
- [/System/Library/PrivateFrameworks/CMPhoto.framework/CMPhoto](DYLIBS/System/Library/PrivateFrameworks/CMPhoto.framework/CMPhoto.md)
- [/System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase](DYLIBS/System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase.md)
- [/System/Library/PrivateFrameworks/CalendarFoundation.framework/CalendarFoundation](DYLIBS/System/Library/PrivateFrameworks/CalendarFoundation.framework/CalendarFoundation.md)
- [/System/Library/PrivateFrameworks/CalendarUIKit.framework/CalendarUIKit](DYLIBS/System/Library/PrivateFrameworks/CalendarUIKit.framework/CalendarUIKit.md)
- [/System/Library/PrivateFrameworks/CallHistory.framework/CallHistory](DYLIBS/System/Library/PrivateFrameworks/CallHistory.framework/CallHistory.md)
- [/System/Library/PrivateFrameworks/CascadeSets.framework/CascadeSets](DYLIBS/System/Library/PrivateFrameworks/CascadeSets.framework/CascadeSets.md)
- [/System/Library/PrivateFrameworks/CentauriDiagnostic.framework/CentauriDiagnostic](DYLIBS/System/Library/PrivateFrameworks/CentauriDiagnostic.framework/CentauriDiagnostic.md)
- [/System/Library/PrivateFrameworks/ChatKit.framework/ChatKit](DYLIBS/System/Library/PrivateFrameworks/ChatKit.framework/ChatKit.md)
- [/System/Library/PrivateFrameworks/ChronoKit.framework/ChronoKit](DYLIBS/System/Library/PrivateFrameworks/ChronoKit.framework/ChronoKit.md)
- [/System/Library/PrivateFrameworks/CiderAudioServer.framework/CiderAudioServer](DYLIBS/System/Library/PrivateFrameworks/CiderAudioServer.framework/CiderAudioServer.md)
- [/System/Library/PrivateFrameworks/CloudDocsUI.framework/CloudDocsUI](DYLIBS/System/Library/PrivateFrameworks/CloudDocsUI.framework/CloudDocsUI.md)
- [/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/CloudPhotoLibrary](DYLIBS/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/CloudPhotoLibrary.md)
- [/System/Library/PrivateFrameworks/CloudTelemetryShared.framework/CloudTelemetryShared](DYLIBS/System/Library/PrivateFrameworks/CloudTelemetryShared.framework/CloudTelemetryShared.md)
- [/System/Library/PrivateFrameworks/CompanionCamera.framework/CompanionCamera](DYLIBS/System/Library/PrivateFrameworks/CompanionCamera.framework/CompanionCamera.md)
- [/System/Library/PrivateFrameworks/CompanionSetupKit.framework/CompanionSetupKit](DYLIBS/System/Library/PrivateFrameworks/CompanionSetupKit.framework/CompanionSetupKit.md)
- [/System/Library/PrivateFrameworks/ContainerManagerCommon.framework/ContainerManagerCommon](DYLIBS/System/Library/PrivateFrameworks/ContainerManagerCommon.framework/ContainerManagerCommon.md)
- [/System/Library/PrivateFrameworks/ContentKit.framework/ContentKit](DYLIBS/System/Library/PrivateFrameworks/ContentKit.framework/ContentKit.md)
- [/System/Library/PrivateFrameworks/ControlCenterUI.framework/ControlCenterUI](DYLIBS/System/Library/PrivateFrameworks/ControlCenterUI.framework/ControlCenterUI.md)
- [/System/Library/PrivateFrameworks/ControlCenterUIKit.framework/ControlCenterUIKit](DYLIBS/System/Library/PrivateFrameworks/ControlCenterUIKit.framework/ControlCenterUIKit.md)
- [/System/Library/PrivateFrameworks/CoreAUC.framework/CoreAUC](DYLIBS/System/Library/PrivateFrameworks/CoreAUC.framework/CoreAUC.md)
- [/System/Library/PrivateFrameworks/CoreCaptureDaemon.framework/CoreCaptureDaemon](DYLIBS/System/Library/PrivateFrameworks/CoreCaptureDaemon.framework/CoreCaptureDaemon.md)
- [/System/Library/PrivateFrameworks/CoreGPSTest.framework/CoreGPSTest.dylib](DYLIBS/System/Library/PrivateFrameworks/CoreGPSTest.framework/CoreGPSTest.dylib.md)
- [/System/Library/PrivateFrameworks/CoreRepairUI.framework/CoreRepairUI](DYLIBS/System/Library/PrivateFrameworks/CoreRepairUI.framework/CoreRepairUI.md)
- [/System/Library/PrivateFrameworks/CoreReporting.framework/CoreReporting](DYLIBS/System/Library/PrivateFrameworks/CoreReporting.framework/CoreReporting.md)
- [/System/Library/PrivateFrameworks/CoreUARP.framework/CoreUARP](DYLIBS/System/Library/PrivateFrameworks/CoreUARP.framework/CoreUARP.md)
- [/System/Library/PrivateFrameworks/CoreWiFi.framework/CoreWiFi](DYLIBS/System/Library/PrivateFrameworks/CoreWiFi.framework/CoreWiFi.md)
- [/System/Library/PrivateFrameworks/CoverSheet.framework/CoverSheet](DYLIBS/System/Library/PrivateFrameworks/CoverSheet.framework/CoverSheet.md)
- [/System/Library/PrivateFrameworks/CryptexKit.framework/CryptexKit](DYLIBS/System/Library/PrivateFrameworks/CryptexKit.framework/CryptexKit.md)
- [/System/Library/PrivateFrameworks/CryptexServer.framework/CryptexServer](DYLIBS/System/Library/PrivateFrameworks/CryptexServer.framework/CryptexServer.md)
- [/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DACalDAV.framework/DACalDAV](DYLIBS/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DACalDAV.framework/DACalDAV.md)
- [/System/Library/PrivateFrameworks/DesignLibrary.framework/DesignLibrary](DYLIBS/System/Library/PrivateFrameworks/DesignLibrary.framework/DesignLibrary.md)
- [/System/Library/PrivateFrameworks/DeviceExpertIntents.framework/DeviceExpertIntents](DYLIBS/System/Library/PrivateFrameworks/DeviceExpertIntents.framework/DeviceExpertIntents.md)
- [/System/Library/PrivateFrameworks/DiagnosticRequestService.framework/DiagnosticRequestService](DYLIBS/System/Library/PrivateFrameworks/DiagnosticRequestService.framework/DiagnosticRequestService.md)
- [/System/Library/PrivateFrameworks/DiagnosticsReporterServices.framework/DiagnosticsReporterServices](DYLIBS/System/Library/PrivateFrameworks/DiagnosticsReporterServices.framework/DiagnosticsReporterServices.md)
- [/System/Library/PrivateFrameworks/DialogEngine.framework/DialogEngine](DYLIBS/System/Library/PrivateFrameworks/DialogEngine.framework/DialogEngine.md)
- [/System/Library/PrivateFrameworks/DistributedEvaluation.framework/DistributedEvaluation](DYLIBS/System/Library/PrivateFrameworks/DistributedEvaluation.framework/DistributedEvaluation.md)
- [/System/Library/PrivateFrameworks/DistributedTimersDaemon.framework/DistributedTimersDaemon](DYLIBS/System/Library/PrivateFrameworks/DistributedTimersDaemon.framework/DistributedTimersDaemon.md)
- [/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/DoNotDisturbServer](DYLIBS/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/DoNotDisturbServer.md)
- [/System/Library/PrivateFrameworks/EchoRelay.framework/EchoRelay](DYLIBS/System/Library/PrivateFrameworks/EchoRelay.framework/EchoRelay.md)
- [/System/Library/PrivateFrameworks/EntityService.framework/EntityService](DYLIBS/System/Library/PrivateFrameworks/EntityService.framework/EntityService.md)
- [/System/Library/PrivateFrameworks/Feedback.framework/Feedback](DYLIBS/System/Library/PrivateFrameworks/Feedback.framework/Feedback.md)
- [/System/Library/PrivateFrameworks/FeedbackCore.framework/FeedbackCore](DYLIBS/System/Library/PrivateFrameworks/FeedbackCore.framework/FeedbackCore.md)
- [/System/Library/PrivateFrameworks/FeedbackService.framework/FeedbackService](DYLIBS/System/Library/PrivateFrameworks/FeedbackService.framework/FeedbackService.md)
- [/System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices](DYLIBS/System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices.md)
- [/System/Library/PrivateFrameworks/GPUCompiler.framework/Versions/32023/Libraries/libGPUCompilerUtils.dylib](DYLIBS/System/Library/PrivateFrameworks/GPUCompiler.framework/Versions/32023/Libraries/libGPUCompilerUtils.dylib.md)
- [/System/Library/PrivateFrameworks/GPUToolsPlayback.framework/GPUToolsPlayback](DYLIBS/System/Library/PrivateFrameworks/GPUToolsPlayback.framework/GPUToolsPlayback.md)
- [/System/Library/PrivateFrameworks/GPUToolsReplay.framework/GPUToolsReplay](DYLIBS/System/Library/PrivateFrameworks/GPUToolsReplay.framework/GPUToolsReplay.md)
- [/System/Library/PrivateFrameworks/GameKitServices.framework/GameKitServices](DYLIBS/System/Library/PrivateFrameworks/GameKitServices.framework/GameKitServices.md)
- [/System/Library/PrivateFrameworks/GameServicesCore.framework/GameServicesCore](DYLIBS/System/Library/PrivateFrameworks/GameServicesCore.framework/GameServicesCore.md)
- [/System/Library/PrivateFrameworks/Gestures.framework/Gestures](DYLIBS/System/Library/PrivateFrameworks/Gestures.framework/Gestures.md)
- [/System/Library/PrivateFrameworks/HangTracer.framework/HangTracer](DYLIBS/System/Library/PrivateFrameworks/HangTracer.framework/HangTracer.md)
- [/System/Library/PrivateFrameworks/Haptics.framework/Haptics](DYLIBS/System/Library/PrivateFrameworks/Haptics.framework/Haptics.md)
- [/System/Library/PrivateFrameworks/HeadphoneManager.framework/HeadphoneManager](DYLIBS/System/Library/PrivateFrameworks/HeadphoneManager.framework/HeadphoneManager.md)
- [/System/Library/PrivateFrameworks/HeadphoneSettingsUI.framework/HeadphoneSettingsUI](DYLIBS/System/Library/PrivateFrameworks/HeadphoneSettingsUI.framework/HeadphoneSettingsUI.md)
- [/System/Library/PrivateFrameworks/HealthExperienceUI.framework/HealthExperienceUI](DYLIBS/System/Library/PrivateFrameworks/HealthExperienceUI.framework/HealthExperienceUI.md)
- [/System/Library/PrivateFrameworks/HealthHearingDaemon.framework/HealthHearingDaemon](DYLIBS/System/Library/PrivateFrameworks/HealthHearingDaemon.framework/HealthHearingDaemon.md)
- [/System/Library/PrivateFrameworks/HearingModeService_Private.framework/HearingModeService_Private](DYLIBS/System/Library/PrivateFrameworks/HearingModeService_Private.framework/HearingModeService_Private.md)
- [/System/Library/PrivateFrameworks/HelpKit.framework/HelpKit](DYLIBS/System/Library/PrivateFrameworks/HelpKit.framework/HelpKit.md)
- [/System/Library/PrivateFrameworks/Home.framework/Home](DYLIBS/System/Library/PrivateFrameworks/Home.framework/Home.md)
- [/System/Library/PrivateFrameworks/HomeAccessoryControlUI.framework/HomeAccessoryControlUI](DYLIBS/System/Library/PrivateFrameworks/HomeAccessoryControlUI.framework/HomeAccessoryControlUI.md)
- [/System/Library/PrivateFrameworks/HomeDataModel.framework/HomeDataModel](DYLIBS/System/Library/PrivateFrameworks/HomeDataModel.framework/HomeDataModel.md)
- [/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup](DYLIBS/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup.md)
- [/System/Library/PrivateFrameworks/HomeEnergyDaemon.framework/HomeEnergyDaemon](DYLIBS/System/Library/PrivateFrameworks/HomeEnergyDaemon.framework/HomeEnergyDaemon.md)
- [/System/Library/PrivateFrameworks/HomeKitDaemon.framework/HomeKitDaemon](DYLIBS/System/Library/PrivateFrameworks/HomeKitDaemon.framework/HomeKitDaemon.md)
- [/System/Library/PrivateFrameworks/HomeKitDaemonLegacy.framework/HomeKitDaemonLegacy](DYLIBS/System/Library/PrivateFrameworks/HomeKitDaemonLegacy.framework/HomeKitDaemonLegacy.md)
- [/System/Library/PrivateFrameworks/HomePodSettings.framework/HomePodSettings](DYLIBS/System/Library/PrivateFrameworks/HomePodSettings.framework/HomePodSettings.md)
- [/System/Library/PrivateFrameworks/HomeRecommendationEngine.framework/HomeRecommendationEngine](DYLIBS/System/Library/PrivateFrameworks/HomeRecommendationEngine.framework/HomeRecommendationEngine.md)
- [/System/Library/PrivateFrameworks/HomeUI.framework/HomeUI](DYLIBS/System/Library/PrivateFrameworks/HomeUI.framework/HomeUI.md)
- [/System/Library/PrivateFrameworks/HomeUI2.framework/HomeUI2](DYLIBS/System/Library/PrivateFrameworks/HomeUI2.framework/HomeUI2.md)
- [/System/Library/PrivateFrameworks/HomeWidgetIntents.framework/HomeWidgetIntents](DYLIBS/System/Library/PrivateFrameworks/HomeWidgetIntents.framework/HomeWidgetIntents.md)
- [/System/Library/PrivateFrameworks/IDS.framework/IDS](DYLIBS/System/Library/PrivateFrameworks/IDS.framework/IDS.md)
- [/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore](DYLIBS/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore.md)
- [/System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities](DYLIBS/System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities.md)
- [/System/Library/PrivateFrameworks/IMTranscoderAgent.framework/IMTranscoderAgent](DYLIBS/System/Library/PrivateFrameworks/IMTranscoderAgent.framework/IMTranscoderAgent.md)
- [/System/Library/PrivateFrameworks/IconServices.framework/IconServices](DYLIBS/System/Library/PrivateFrameworks/IconServices.framework/IconServices.md)
- [/System/Library/PrivateFrameworks/ImagePlaygroundInternal.framework/ImagePlaygroundInternal](DYLIBS/System/Library/PrivateFrameworks/ImagePlaygroundInternal.framework/ImagePlaygroundInternal.md)
- [/System/Library/PrivateFrameworks/IntelligenceEngine.framework/IntelligenceEngine](DYLIBS/System/Library/PrivateFrameworks/IntelligenceEngine.framework/IntelligenceEngine.md)
- [/System/Library/PrivateFrameworks/IntelligenceFlowPlannerRuntime.framework/IntelligenceFlowPlannerRuntime](DYLIBS/System/Library/PrivateFrameworks/IntelligenceFlowPlannerRuntime.framework/IntelligenceFlowPlannerRuntime.md)
- [/System/Library/PrivateFrameworks/IntelligenceFlowPlannerSupport.framework/IntelligenceFlowPlannerSupport](DYLIBS/System/Library/PrivateFrameworks/IntelligenceFlowPlannerSupport.framework/IntelligenceFlowPlannerSupport.md)
- [/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/IntelligenceFlowRuntime](DYLIBS/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/IntelligenceFlowRuntime.md)
- [/System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared](DYLIBS/System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared.md)
- [/System/Library/PrivateFrameworks/IntelligencePlatformCore.framework/IntelligencePlatformCore](DYLIBS/System/Library/PrivateFrameworks/IntelligencePlatformCore.framework/IntelligencePlatformCore.md)
- [/System/Library/PrivateFrameworks/JetCore.framework/JetCore](DYLIBS/System/Library/PrivateFrameworks/JetCore.framework/JetCore.md)
- [/System/Library/PrivateFrameworks/JetEngine.framework/JetEngine](DYLIBS/System/Library/PrivateFrameworks/JetEngine.framework/JetEngine.md)
- [/System/Library/PrivateFrameworks/KeyboardSettings.framework/KeyboardSettings](DYLIBS/System/Library/PrivateFrameworks/KeyboardSettings.framework/KeyboardSettings.md)
- [/System/Library/PrivateFrameworks/KeyboardSettingsFeedback.framework/KeyboardSettingsFeedback](DYLIBS/System/Library/PrivateFrameworks/KeyboardSettingsFeedback.framework/KeyboardSettingsFeedback.md)
- [/System/Library/PrivateFrameworks/LighthouseInference.framework/LighthouseInference](DYLIBS/System/Library/PrivateFrameworks/LighthouseInference.framework/LighthouseInference.md)
- [/System/Library/PrivateFrameworks/LighthouseServicesAnalyticsFramework.framework/LighthouseServicesAnalyticsFramework](DYLIBS/System/Library/PrivateFrameworks/LighthouseServicesAnalyticsFramework.framework/LighthouseServicesAnalyticsFramework.md)
- [/System/Library/PrivateFrameworks/MDM.framework/MDM](DYLIBS/System/Library/PrivateFrameworks/MDM.framework/MDM.md)
- [/System/Library/PrivateFrameworks/MTLToolsDeviceSupport.framework/MTLToolsDeviceSupport](DYLIBS/System/Library/PrivateFrameworks/MTLToolsDeviceSupport.framework/MTLToolsDeviceSupport.md)
- [/System/Library/PrivateFrameworks/MagnifierSupport.framework/MagnifierSupport](DYLIBS/System/Library/PrivateFrameworks/MagnifierSupport.framework/MagnifierSupport.md)
- [/System/Library/PrivateFrameworks/MapsSuggestions.framework/MapsSuggestions](DYLIBS/System/Library/PrivateFrameworks/MapsSuggestions.framework/MapsSuggestions.md)
- [/System/Library/PrivateFrameworks/MediaAnalysis.framework/MediaAnalysis](DYLIBS/System/Library/PrivateFrameworks/MediaAnalysis.framework/MediaAnalysis.md)
- [/System/Library/PrivateFrameworks/MediaControls.framework/MediaControls](DYLIBS/System/Library/PrivateFrameworks/MediaControls.framework/MediaControls.md)
- [/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience](DYLIBS/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience.md)
- [/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/MediaPlaybackCore](DYLIBS/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/MediaPlaybackCore.md)
- [/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote](DYLIBS/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote.md)
- [/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/MobileAssetDaemon](DYLIBS/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/MobileAssetDaemon.md)
- [/System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup](DYLIBS/System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup.md)
- [/System/Library/PrivateFrameworks/MobileSafari.framework/MobileSafari](DYLIBS/System/Library/PrivateFrameworks/MobileSafari.framework/MobileSafari.md)
- [/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI](DYLIBS/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI.md)
- [/System/Library/PrivateFrameworks/ModelCatalogRuntime.framework/ModelCatalogRuntime](DYLIBS/System/Library/PrivateFrameworks/ModelCatalogRuntime.framework/ModelCatalogRuntime.md)
- [/System/Library/PrivateFrameworks/Moments.framework/Moments](DYLIBS/System/Library/PrivateFrameworks/Moments.framework/Moments.md)
- [/System/Library/PrivateFrameworks/MomentsIntelligence.framework/MomentsIntelligence](DYLIBS/System/Library/PrivateFrameworks/MomentsIntelligence.framework/MomentsIntelligence.md)
- [/System/Library/PrivateFrameworks/MomentsOnboardingAndSettings.framework/MomentsOnboardingAndSettings](DYLIBS/System/Library/PrivateFrameworks/MomentsOnboardingAndSettings.framework/MomentsOnboardingAndSettings.md)
- [/System/Library/PrivateFrameworks/NetworkServiceProxy.framework/NetworkServiceProxy](DYLIBS/System/Library/PrivateFrameworks/NetworkServiceProxy.framework/NetworkServiceProxy.md)
- [/System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics](DYLIBS/System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics.md)
- [/System/Library/PrivateFrameworks/OmniSearch.framework/OmniSearch](DYLIBS/System/Library/PrivateFrameworks/OmniSearch.framework/OmniSearch.md)
- [/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit](DYLIBS/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit.md)
- [/System/Library/PrivateFrameworks/PaperBoardUI.framework/PaperBoardUI](DYLIBS/System/Library/PrivateFrameworks/PaperBoardUI.framework/PaperBoardUI.md)
- [/System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore](DYLIBS/System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore.md)
- [/System/Library/PrivateFrameworks/PebblePlayCore.framework/PebblePlayCore](DYLIBS/System/Library/PrivateFrameworks/PebblePlayCore.framework/PebblePlayCore.md)
- [/System/Library/PrivateFrameworks/PebblePlayDaemon.framework/PebblePlayDaemon](DYLIBS/System/Library/PrivateFrameworks/PebblePlayDaemon.framework/PebblePlayDaemon.md)
- [/System/Library/PrivateFrameworks/PegasusConfiguration.framework/PegasusConfiguration](DYLIBS/System/Library/PrivateFrameworks/PegasusConfiguration.framework/PegasusConfiguration.md)
- [/System/Library/PrivateFrameworks/PersonalizedSensing.framework/PersonalizedSensing](DYLIBS/System/Library/PrivateFrameworks/PersonalizedSensing.framework/PersonalizedSensing.md)
- [/System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PhotoLibraryServices](DYLIBS/System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PhotoLibraryServices.md)
- [/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/PhotoLibraryServicesCore](DYLIBS/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/PhotoLibraryServicesCore.md)
- [/System/Library/PrivateFrameworks/PhotosIntelligence.framework/PhotosIntelligence](DYLIBS/System/Library/PrivateFrameworks/PhotosIntelligence.framework/PhotosIntelligence.md)
- [/System/Library/PrivateFrameworks/PhotosPosterUI.framework/PhotosPosterUI](DYLIBS/System/Library/PrivateFrameworks/PhotosPosterUI.framework/PhotosPosterUI.md)
- [/System/Library/PrivateFrameworks/PhotosSpatialMediaCore.framework/PhotosSpatialMediaCore](DYLIBS/System/Library/PrivateFrameworks/PhotosSpatialMediaCore.framework/PhotosSpatialMediaCore.md)
- [/System/Library/PrivateFrameworks/PhotosUICore.framework/PhotosUICore](DYLIBS/System/Library/PrivateFrameworks/PhotosUICore.framework/PhotosUICore.md)
- [/System/Library/PrivateFrameworks/PhotosUIPrivate.framework/PhotosUIPrivate](DYLIBS/System/Library/PrivateFrameworks/PhotosUIPrivate.framework/PhotosUIPrivate.md)
- [/System/Library/PrivateFrameworks/PnROnDeviceFramework.framework/PnROnDeviceFramework](DYLIBS/System/Library/PrivateFrameworks/PnROnDeviceFramework.framework/PnROnDeviceFramework.md)
- [/System/Library/PrivateFrameworks/Polaris.framework/Polaris](DYLIBS/System/Library/PrivateFrameworks/Polaris.framework/Polaris.md)
- [/System/Library/PrivateFrameworks/PolarisBufferService.framework/PolarisBufferService](DYLIBS/System/Library/PrivateFrameworks/PolarisBufferService.framework/PolarisBufferService.md)
- [/System/Library/PrivateFrameworks/PosterBoard.framework/PosterBoard](DYLIBS/System/Library/PrivateFrameworks/PosterBoard.framework/PosterBoard.md)
- [/System/Library/PrivateFrameworks/PosterKit.framework/PosterKit](DYLIBS/System/Library/PrivateFrameworks/PosterKit.framework/PosterKit.md)
- [/System/Library/PrivateFrameworks/Preferences.framework/Preferences](DYLIBS/System/Library/PrivateFrameworks/Preferences.framework/Preferences.md)
- [/System/Library/PrivateFrameworks/PrivacyPolicy.framework/PrivacyPolicy](DYLIBS/System/Library/PrivateFrameworks/PrivacyPolicy.framework/PrivacyPolicy.md)
- [/System/Library/PrivateFrameworks/PrivateCloudComputeDaemon.framework/PrivateCloudComputeDaemon](DYLIBS/System/Library/PrivateFrameworks/PrivateCloudComputeDaemon.framework/PrivateCloudComputeDaemon.md)
- [/System/Library/PrivateFrameworks/ProactiveSummarization.framework/ProactiveSummarization](DYLIBS/System/Library/PrivateFrameworks/ProactiveSummarization.framework/ProactiveSummarization.md)
- [/System/Library/PrivateFrameworks/Rapport.framework/Rapport](DYLIBS/System/Library/PrivateFrameworks/Rapport.framework/Rapport.md)
- [/System/Library/PrivateFrameworks/Recap.framework/Recap](DYLIBS/System/Library/PrivateFrameworks/Recap.framework/Recap.md)
- [/System/Library/PrivateFrameworks/RoyaCaptureCore.framework/RoyaCaptureCore](DYLIBS/System/Library/PrivateFrameworks/RoyaCaptureCore.framework/RoyaCaptureCore.md)
- [/System/Library/PrivateFrameworks/SDAPI.framework/SDAPI](DYLIBS/System/Library/PrivateFrameworks/SDAPI.framework/SDAPI.md)
- [/System/Library/PrivateFrameworks/SafariCore.framework/SafariCore](DYLIBS/System/Library/PrivateFrameworks/SafariCore.framework/SafariCore.md)
- [/System/Library/PrivateFrameworks/SafariFoundation.framework/SafariFoundation](DYLIBS/System/Library/PrivateFrameworks/SafariFoundation.framework/SafariFoundation.md)
- [/System/Library/PrivateFrameworks/SafariShared.framework/SafariShared](DYLIBS/System/Library/PrivateFrameworks/SafariShared.framework/SafariShared.md)
- [/System/Library/PrivateFrameworks/ScreenSharingKit.framework/ScreenSharingKit](DYLIBS/System/Library/PrivateFrameworks/ScreenSharingKit.framework/ScreenSharingKit.md)
- [/System/Library/PrivateFrameworks/SearchAssets.framework/SearchAssets](DYLIBS/System/Library/PrivateFrameworks/SearchAssets.framework/SearchAssets.md)
- [/System/Library/PrivateFrameworks/SensingAlgsPadHostServiceJ8xx.framework/SensingAlgsPadHostServiceJ8xx](DYLIBS/System/Library/PrivateFrameworks/SensingAlgsPadHostServiceJ8xx.framework/SensingAlgsPadHostServiceJ8xx.md)
- [/System/Library/PrivateFrameworks/SensingAlgsService.framework/SensingAlgsService](DYLIBS/System/Library/PrivateFrameworks/SensingAlgsService.framework/SensingAlgsService.md)
- [/System/Library/PrivateFrameworks/SensingAlgsTouchButtonHost.framework/SensingAlgsTouchButtonHost](DYLIBS/System/Library/PrivateFrameworks/SensingAlgsTouchButtonHost.framework/SensingAlgsTouchButtonHost.md)
- [/System/Library/PrivateFrameworks/Sentry.framework/Sentry](DYLIBS/System/Library/PrivateFrameworks/Sentry.framework/Sentry.md)
- [/System/Library/PrivateFrameworks/ServicesAnalyticsDaemon.framework/ServicesAnalyticsDaemon](DYLIBS/System/Library/PrivateFrameworks/ServicesAnalyticsDaemon.framework/ServicesAnalyticsDaemon.md)
- [/System/Library/PrivateFrameworks/Settings/PrivacySettingsUI.framework/PrivacySettingsUI](DYLIBS/System/Library/PrivateFrameworks/Settings/PrivacySettingsUI.framework/PrivacySettingsUI.md)
- [/System/Library/PrivateFrameworks/SettingsHost.framework/SettingsHost](DYLIBS/System/Library/PrivateFrameworks/SettingsHost.framework/SettingsHost.md)
- [/System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant](DYLIBS/System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant.md)
- [/System/Library/PrivateFrameworks/SidecarCore.framework/SidecarCore](DYLIBS/System/Library/PrivateFrameworks/SidecarCore.framework/SidecarCore.md)
- [/System/Library/PrivateFrameworks/SidecarUI.framework/SidecarUI](DYLIBS/System/Library/PrivateFrameworks/SidecarUI.framework/SidecarUI.md)
- [/System/Library/PrivateFrameworks/SiriAnalytics.framework/SiriAnalytics](DYLIBS/System/Library/PrivateFrameworks/SiriAnalytics.framework/SiriAnalytics.md)
- [/System/Library/PrivateFrameworks/SiriProcessing.framework/SiriProcessing](DYLIBS/System/Library/PrivateFrameworks/SiriProcessing.framework/SiriProcessing.md)
- [/System/Library/PrivateFrameworks/SiriSetup.framework/SiriSetup](DYLIBS/System/Library/PrivateFrameworks/SiriSetup.framework/SiriSetup.md)
- [/System/Library/PrivateFrameworks/SiriTTSService.framework/SiriTTSService](DYLIBS/System/Library/PrivateFrameworks/SiriTTSService.framework/SiriTTSService.md)
- [/System/Library/PrivateFrameworks/SoftwareUpdateController.framework/SoftwareUpdateController](DYLIBS/System/Library/PrivateFrameworks/SoftwareUpdateController.framework/SoftwareUpdateController.md)
- [/System/Library/PrivateFrameworks/SoftwareUpdateServices.framework/SoftwareUpdateServices](DYLIBS/System/Library/PrivateFrameworks/SoftwareUpdateServices.framework/SoftwareUpdateServices.md)
- [/System/Library/PrivateFrameworks/SpotlightDaemon.framework/SpotlightDaemon](DYLIBS/System/Library/PrivateFrameworks/SpotlightDaemon.framework/SpotlightDaemon.md)
- [/System/Library/PrivateFrameworks/SpotlightDiagnostics.framework/SpotlightDiagnostics](DYLIBS/System/Library/PrivateFrameworks/SpotlightDiagnostics.framework/SpotlightDiagnostics.md)
- [/System/Library/PrivateFrameworks/SpotlightIndex.framework/SpotlightIndex](DYLIBS/System/Library/PrivateFrameworks/SpotlightIndex.framework/SpotlightIndex.md)
- [/System/Library/PrivateFrameworks/SpotlightServices.framework/SpotlightServices](DYLIBS/System/Library/PrivateFrameworks/SpotlightServices.framework/SpotlightServices.md)
- [/System/Library/PrivateFrameworks/SpringBoard.framework/SpringBoard](DYLIBS/System/Library/PrivateFrameworks/SpringBoard.framework/SpringBoard.md)
- [/System/Library/PrivateFrameworks/SpringBoardFoundation.framework/SpringBoardFoundation](DYLIBS/System/Library/PrivateFrameworks/SpringBoardFoundation.framework/SpringBoardFoundation.md)
- [/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome](DYLIBS/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome.md)
- [/System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices](DYLIBS/System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices.md)
- [/System/Library/PrivateFrameworks/SpringBoardUIServices.framework/SpringBoardUIServices](DYLIBS/System/Library/PrivateFrameworks/SpringBoardUIServices.framework/SpringBoardUIServices.md)
- [/System/Library/PrivateFrameworks/StoreServices.framework/StoreServices](DYLIBS/System/Library/PrivateFrameworks/StoreServices.framework/StoreServices.md)
- [/System/Library/PrivateFrameworks/SwiftCRLite.framework/SwiftCRLite](DYLIBS/System/Library/PrivateFrameworks/SwiftCRLite.framework/SwiftCRLite.md)
- [/System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter](DYLIBS/System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter.md)
- [/System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomEvaluator.framework/SymptomEvaluator](DYLIBS/System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomEvaluator.framework/SymptomEvaluator.md)
- [/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore](DYLIBS/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore.md)
- [/System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities](DYLIBS/System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities.md)
- [/System/Library/PrivateFrameworks/TextInputCore.framework/TextInputCore](DYLIBS/System/Library/PrivateFrameworks/TextInputCore.framework/TextInputCore.md)
- [/System/Library/PrivateFrameworks/TipsCore.framework/TipsCore](DYLIBS/System/Library/PrivateFrameworks/TipsCore.framework/TipsCore.md)
- [/System/Library/PrivateFrameworks/TranslationInference.framework/TranslationInference](DYLIBS/System/Library/PrivateFrameworks/TranslationInference.framework/TranslationInference.md)
- [/System/Library/PrivateFrameworks/TrialServer.framework/TrialServer](DYLIBS/System/Library/PrivateFrameworks/TrialServer.framework/TrialServer.md)
- [/System/Library/PrivateFrameworks/UARPiCloud.framework/UARPiCloud](DYLIBS/System/Library/PrivateFrameworks/UARPiCloud.framework/UARPiCloud.md)
- [/System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore](DYLIBS/System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore.md)
- [/System/Library/PrivateFrameworks/UIKitServices.framework/UIKitServices](DYLIBS/System/Library/PrivateFrameworks/UIKitServices.framework/UIKitServices.md)
- [/System/Library/PrivateFrameworks/VFX.framework/VFX](DYLIBS/System/Library/PrivateFrameworks/VFX.framework/VFX.md)
- [/System/Library/PrivateFrameworks/VideoProcessing.framework/VideoProcessing](DYLIBS/System/Library/PrivateFrameworks/VideoProcessing.framework/VideoProcessing.md)
- [/System/Library/PrivateFrameworks/VideosUI.framework/VideosUI](DYLIBS/System/Library/PrivateFrameworks/VideosUI.framework/VideosUI.md)
- [/System/Library/PrivateFrameworks/VisualGeneration.framework/VisualGeneration](DYLIBS/System/Library/PrivateFrameworks/VisualGeneration.framework/VisualGeneration.md)
- [/System/Library/PrivateFrameworks/VisualIntelligenceCore.framework/VisualIntelligenceCore](DYLIBS/System/Library/PrivateFrameworks/VisualIntelligenceCore.framework/VisualIntelligenceCore.md)
- [/System/Library/PrivateFrameworks/VisualIntelligenceUI.framework/VisualIntelligenceUI](DYLIBS/System/Library/PrivateFrameworks/VisualIntelligenceUI.framework/VisualIntelligenceUI.md)
- [/System/Library/PrivateFrameworks/VisualMappingKit.framework/VisualMappingKit](DYLIBS/System/Library/PrivateFrameworks/VisualMappingKit.framework/VisualMappingKit.md)
- [/System/Library/PrivateFrameworks/VoiceProcessor.framework/VoiceProcessor](DYLIBS/System/Library/PrivateFrameworks/VoiceProcessor.framework/VoiceProcessor.md)
- [/System/Library/PrivateFrameworks/VoiceTrigger.framework/VoiceTrigger](DYLIBS/System/Library/PrivateFrameworks/VoiceTrigger.framework/VoiceTrigger.md)
- [/System/Library/PrivateFrameworks/WPDaemon.framework/WPDaemon](DYLIBS/System/Library/PrivateFrameworks/WPDaemon.framework/WPDaemon.md)
- [/System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks](DYLIBS/System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks.md)
- [/System/Library/PrivateFrameworks/WebCore.framework/Frameworks/libANGLE-shared.dylib](DYLIBS/System/Library/PrivateFrameworks/WebCore.framework/Frameworks/libANGLE-shared.dylib.md)
- [/System/Library/PrivateFrameworks/WebCore.framework/Frameworks/libwebrtc.dylib](DYLIBS/System/Library/PrivateFrameworks/WebCore.framework/Frameworks/libwebrtc.dylib.md)
- [/System/Library/PrivateFrameworks/WebCore.framework/WebCore](DYLIBS/System/Library/PrivateFrameworks/WebCore.framework/WebCore.md)
- [/System/Library/PrivateFrameworks/WebGPU.framework/WebGPU](DYLIBS/System/Library/PrivateFrameworks/WebGPU.framework/WebGPU.md)
- [/System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy](DYLIBS/System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy.md)
- [/System/Library/PrivateFrameworks/WiFiAnalytics.framework/WiFiAnalytics](DYLIBS/System/Library/PrivateFrameworks/WiFiAnalytics.framework/WiFiAnalytics.md)
- [/System/Library/PrivateFrameworks/WiFiCloudSyncEngine.framework/WiFiCloudSyncEngine](DYLIBS/System/Library/PrivateFrameworks/WiFiCloudSyncEngine.framework/WiFiCloudSyncEngine.md)
- [/System/Library/PrivateFrameworks/WiFiPolicy.framework/WiFiPolicy](DYLIBS/System/Library/PrivateFrameworks/WiFiPolicy.framework/WiFiPolicy.md)
- [/System/Library/PrivateFrameworks/WorkflowEditor.framework/WorkflowEditor](DYLIBS/System/Library/PrivateFrameworks/WorkflowEditor.framework/WorkflowEditor.md)
- [/System/Library/PrivateFrameworks/WorkflowUI.framework/WorkflowUI](DYLIBS/System/Library/PrivateFrameworks/WorkflowUI.framework/WorkflowUI.md)
- [/System/Library/PrivateFrameworks/WritingTools.framework/WritingTools](DYLIBS/System/Library/PrivateFrameworks/WritingTools.framework/WritingTools.md)
- [/System/Library/PrivateFrameworks/WritingToolsUI.framework/WritingToolsUI](DYLIBS/System/Library/PrivateFrameworks/WritingToolsUI.framework/WritingToolsUI.md)
- [/System/Library/PrivateFrameworks/_AppIntentsServices_ToolKit.framework/_AppIntentsServices_ToolKit](DYLIBS/System/Library/PrivateFrameworks/_AppIntentsServices_ToolKit.framework/_AppIntentsServices_ToolKit.md)
- [/System/Library/PrivateFrameworks/iCloudQuotaUI.framework/iCloudQuotaUI](DYLIBS/System/Library/PrivateFrameworks/iCloudQuotaUI.framework/iCloudQuotaUI.md)
- [/System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSApplication.framework/TSApplication](DYLIBS/System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSApplication.framework/TSApplication.md)
- [/System/Library/VideoCodecs/VCPHEVC.videocodec](DYLIBS/System/Library/VideoCodecs/VCPHEVC.videocodec.md)
- [/System/Library/VideoCodecs/ave.videoencoder](DYLIBS/System/Library/VideoCodecs/ave.videoencoder.md)
- [/System/Library/VideoDecoders/AVD.videodecoder](DYLIBS/System/Library/VideoDecoders/AVD.videodecoder.md)
- [/usr/lib/dyld](DYLIBS/usr/lib/dyld.md)
- [/usr/lib/libMemoryResourceException.dylib](DYLIBS/usr/lib/libMemoryResourceException.dylib.md)
- [/usr/lib/libMobileGestalt.dylib](DYLIBS/usr/lib/libMobileGestalt.dylib.md)
- [/usr/lib/libauthinstall.dylib](DYLIBS/usr/lib/libauthinstall.dylib.md)
- [/usr/lib/libchannel.dylib](DYLIBS/usr/lib/libchannel.dylib.md)
- [/usr/lib/libcoreroutine.dylib](DYLIBS/usr/lib/libcoreroutine.dylib.md)
- [/usr/lib/libcryptex.dylib](DYLIBS/usr/lib/libcryptex.dylib.md)
- [/usr/lib/libcryptex_core.dylib](DYLIBS/usr/lib/libcryptex_core.dylib.md)
- [/usr/lib/libcryptex_interface.dylib](DYLIBS/usr/lib/libcryptex_interface.dylib.md)
- [/usr/lib/libcryptex_trampoline.dylib](DYLIBS/usr/lib/libcryptex_trampoline.dylib.md)
- [/usr/lib/libfire7.dylib](DYLIBS/usr/lib/libfire7.dylib.md)
- [/usr/lib/libfire9.dylib](DYLIBS/usr/lib/libfire9.dylib.md)
- [/usr/lib/libimage4.dylib](DYLIBS/usr/lib/libimage4.dylib.md)
- [/usr/lib/libsandbox.1.dylib](DYLIBS/usr/lib/libsandbox.1.dylib.md)
- [/usr/lib/libswiftPrespecialized.dylib](DYLIBS/usr/lib/libswiftPrespecialized.dylib.md)
- [/usr/lib/system/libsystem_containermanager.dylib](DYLIBS/usr/lib/system/libsystem_containermanager.dylib.md)
- [/usr/lib/updaters/libAce3Updater.dylib](DYLIBS/usr/lib/updaters/libAce3Updater.dylib.md)
- [/usr/lib/updaters/libAppleTconUARPUpdater.dylib](DYLIBS/usr/lib/updaters/libAppleTconUARPUpdater.dylib.md)
- [/usr/lib/updaters/libVinylUpdater.dylib](DYLIBS/usr/lib/updaters/libVinylUpdater.dylib.md)
- [/usr/lib/usd/libusd_ms.dylib](DYLIBS/usr/lib/usd/libusd_ms.dylib.md)

</details>

## Files

### 🆕 New

#### filesystem (241)

- [View 241 new files](FILES/filesystem.NEW.md)

### ❌ Removed

#### filesystem (135)

- [View 135 removed files](FILES/filesystem.Removed.md)

## Feature Flags

### filesystem

#### 🆕 NEW (6)

<details>
  <summary><i>View New</i></summary>

##### SpeakerGroupSetupKit.plist

>  `Domain/SpeakerGroupSetupKit.plist`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>HomeTheaterSurround</key>
	<dict>
		<key>DevelopmentPhase</key>
		<string>FeatureComplete</string>
	</dict>
</dict>
</plist>

```
##### AONSense.plist

>  `Unified/Domain/AONSense.plist`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>localAmbientSensing</key>
	<dict>
		<key>Attributes</key>
		<dict>
			<key>TargetRelease</key>
			<string>27.A</string>
		</dict>
		<key>Description</key>
		<string>Ambient sensing using local camera/audio</string>
		<key>DevelopmentPhase</key>
		<string>UnderDevelopment</string>
		<key>DisplayName</key>
		<string>Ambient sensing using local camera/audio</string>
		<key>State</key>
		<string>dynamic</string>
	</dict>
	<key>vlOnLocationClient</key>
	<dict>
		<key>Attributes</key>
		<dict>
			<key>TargetRelease</key>
			<string>27.A</string>
		</dict>
		<key>Description</key>
		<string>Run visual localization in response to any high accuracy location client</string>
		<key>DevelopmentPhase</key>
		<string>UnderDevelopment</string>
		<key>DisplayName</key>
		<string>Visual Localization Client</string>
		<key>State</key>
		<string>dynamic</string>
	</dict>
</dict>
</plist>

```
##### AppleMediaServices.plist

>  `Unified/Domain/AppleMediaServices.plist`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>SubsForGroups</key>
	<dict>
		<key>Attributes</key>
		<dict>
			<key>TargetRelease</key>
			<string>27.C</string>
		</dict>
		<key>Description</key>
		<string>AMS Subs for groups support</string>
		<key>DevelopmentPhase</key>
		<string>UnderDevelopment</string>
		<key>DisplayName</key>
		<string>Subs For Groups</string>
		<key>State</key>
		<string>dynamic</string>
	</dict>
</dict>
</plist>

```
##### NaturalDictation.plist

>  `Unified/Domain/NaturalDictation.plist`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>AudioToEditOnServer</key>
	<dict>
		<key>Attributes</key>
		<dict>
			<key>TargetRelease</key>
			<string>28.A</string>
		</dict>
		<key>Description</key>
		<string>Enable natural dictation using server for early data collection</string>
		<key>DevelopmentPhase</key>
		<string>UnderDevelopment</string>
		<key>DisplayName</key>
		<string>Audio To Edit On Server</string>
		<key>State</key>
		<string>dynamic</string>
	</dict>
</dict>
</plist>

```
##### UnifiedFeatureFlagsDemo.plist

>  `Unified/Domain/UnifiedFeatureFlagsDemo.plist`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>DemoDynamic</key>
	<dict>
		<key>Attributes</key>
		<dict>
			<key>TargetRelease</key>
			<string>27.A</string>
		</dict>
		<key>Description</key>
		<string>Demonstrates a runtime-configurable feature flag with dynamic evaluation capabilities.</string>
		<key>DevelopmentPhase</key>
		<string>UnderDevelopment</string>
		<key>DisplayName</key>
		<string>Demo Dynamic Feature</string>
		<key>State</key>
		<string>dynamic</string>
	</dict>
</dict>
</plist>

```
##### WritingTools.plist

>  `Unified/Domain/WritingTools.plist`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>FormattingBar_macOS</key>
	<dict>
		<key>Attributes</key>
		<dict>
			<key>TargetRelease</key>
			<string>27.B</string>
		</dict>
		<key>Description</key>
		<string>Enables the Campo text suggestions view in the Text Formatting bar</string>
		<key>DevelopmentPhase</key>
		<string>UnderDevelopment</string>
		<key>DisplayName</key>
		<string>Formatting Bar (macOS)</string>
		<key>State</key>
		<string>dynamic</string>
	</dict>
</dict>
</plist>

```

</details>

#### ⬆️ Updated (8)

- [Domain/AirPlay.plist](FEATURES/filesystem/Domain/AirPlay.plist.md)
- [Domain/CompanionServices.plist](FEATURES/filesystem/Domain/CompanionServices.plist.md)
- [Domain/Home.plist](FEATURES/filesystem/Domain/Home.plist.md)
- [Domain/HomePodSettings.plist](FEATURES/filesystem/Domain/HomePodSettings.plist.md)
- [Domain/PebblePlay.plist](FEATURES/filesystem/Domain/PebblePlay.plist.md)
- [Domain/VirtualAudio.plist](FEATURES/filesystem/Domain/VirtualAudio.plist.md)
- [GlobalDisclosures.plist](FEATURES/filesystem/GlobalDisclosures.plist.md)
- [Unified/Domain/Wallet.plist](FEATURES/filesystem/Unified/Domain/Wallet.plist.md)

## EOF
