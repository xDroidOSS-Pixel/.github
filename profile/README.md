# xdroidOSS | Pixel 2 & Pixel 3

### Sync source ###
```bash
repo init -u https://github.com/xdroidOSS-Pixel/manifest -b thirteen
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build source ###
```bash
. build/envsetup.sh
```
```bash
lunch xdroid_$devicecodename-userdebug
```
```bash
make xd -j$(nproc --all)
```
### Pixel 2 & 2XL:
[![Download xDroid Pixel (Unofficial)](https://img.shields.io/sourceforge/dm/ar-build.svg)](https://sourceforge.net/projects/ar-build/files/latest/download) [![Download xDroid Pixel (Unofficial)](https://img.shields.io/sourceforge/dw/ar-build.svg)](https://sourceforge.net/projects/ar-build/files/latest/download) [![Download xDroid Pixel (Unofficial)](https://img.shields.io/sourceforge/dd/ar-build.svg)](https://sourceforge.net/projects/ar-build/files/latest/download) [![Download xDroid Pixel (Unofficial)](https://img.shields.io/sourceforge/dt/ar-build.svg)](https://sourceforge.net/projects/ar-build/files/latest/download)

### Pixel 3 & 3XL:
WIP

### Credits ###
 * [**xDroidOSS**](https://github.com/xdroid-oss)
 * [**AOSP**](https://android.googlesource.com)
 * [**CAF**](https://source.codeaurora.org)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**POSP**](https://github.com/PotatoProject)
 * [**StatixOS**](https://github.com/StatiXOS)
 * [**WeebProject**](https://github.com/WeebProject)
 * [**AOSPMasterVayu**](https://github.com/AOSP-Master-Vayu)
 * [**AEX**](https://github.com/AospExtended)
