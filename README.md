# Android device configuration for Misfit Vapor (mullet)

To initialize your local repository using the OMNIROM trees to build TWRP, use a command like this:

```
repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-8.1
repo sync

export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_mullet-eng
mka recoveryimage
```
