# TWRP device tree for Samsung Galaxy F41

Lisenced Under [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

## How to build
1. Set up the build environment following instructions from [here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni/blob/twrp-10.0/README.md#getting-started) (Fully compatible/tested)
2. Clone the device tree in the root of twrp source:
```
git clone -b android-11.0 https://github.com/soulr344/android_device_samsung_f41.git device/samsung/f41
```
3. To build:
```
export ALLOW_MISSING_DEPENDENCIES=true && . build/envsetup.sh && lunch omni_f41-eng && mka recoveryimage -j$(nproc)
```
