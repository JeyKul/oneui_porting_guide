# Debloat

## to make System not fuck itself completly, we gotta debloat many stuff.

### we mainly do it for your partition, but also for knox and crypto stuff, bleh


System

| app  | priv-app | framework | others |
| ---- | -------- | --------- | ------ |
|ARCore|AREmoji|boot***.vdex|system/bin/fabric_crypto|
|ARDrawing|AREmojiEditor|FabricCryptoLib.jar|system/etc/init/fabric_crypto.rc|
|FBAppManager_NS|CIDManager||system/etc/vintf/manifest/fabric_crypto_manifest.xml
|KidsHome_Installer|CSC||system/etc/permissions/FabricCryptoLib.xml|
|PlayAutoInstallConfig|DevGPUDriver-****||system/etc/permissions/privapp-permissions-com.samsung.android.kmxservice.xml|
|SamsungPassAutofill_v1|GameDriver****||system/lib64/com.samsung.security.fabric.cryptod-V1-cpp.so|
|WebManual|DiagMonAgent91||system/lib64/vendor.samsung.hardware.security.fkeymaster-V1-cpp.so|
||FBInstaller_NS||system/lib64/vendor.samsung.hardware.security.fkeymaster-V1-ndk.so|
||FBServices||system/dpolicy_system
||FotaAgent||
||KmxService||
||OMCAgent5||
||OneDrive_Samsung_v3||
||PaymentFramework||
||SamsungBilling||
||SamsungPass||
||YourPhone_P1_5||
||Upday||
||SPPPushClient||


Product

| app  | priv-app |
| ------- | ------| 
|Chrome|Messages|
|Gmail2|
|Maps|
|YouTube|

# Next up:

# [Step Five: Product ](./product.md)

# Previous:

## [Step Three: Get Partition Sizes | Firmware you wanna port (and then we cry) ](./prtsiz2.md)
