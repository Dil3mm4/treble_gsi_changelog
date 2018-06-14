# Global changelog
### ESPINOSA 
- FP gestures now supports only swipe up/down (to collapse/expand statusbar)

-June security patches (ROM side, if your vendor or kernel isn't patched to june patches, it will still show MAY)

- Minor improvements

### DELAHOYA
- ALL THE RELEASE FROM DELAHOYA ON WILL BE FLASHABLE TWRP ZIPS NO MATTER WHAT, IT WILL BE FLASHABLE VIA TWRP

- NFC has been fixed

- No more need to push adb commands for the fingerprint navigation, it is inherited in settings disabling navbar on screen 
 (LOS BASED ROMs)

- Improved overall stability

- Built-in styles are now fixed (LOS BASED ROMs)

- OTA updates (CrDroid) 


### CARNERA_r4
-Fingerprint navigation is now properly implemented with swipes up/down to collapse/expand statusbar
(if it's still not working launch this adb command, adb shell settings put secure system_navigation_keys_enabled 1)

-Upstreamed to r29 (AOSP)

-May security patches

### CARNERA_r3 
- Performance and stability fixes

### CARNERA_r2 
- V4A should now work

- Minor quirks fixing

### CARNERA_r1
- Fixing the rare issue about /system partition not mounting due to other devs 
 incompetence to keep a standard System Partition size over all roms

- Fixed camera shutter latency

### CARNERA
- Nightmode is now working

- Enhanced Doze mode 

- RROS boot animation

- F2FS fixes (some users that reported quirks about crashing apps should be now ok)

- Triple pressing the power button sets higher brightness

- All screen rotations

- Multiuser

- Security Patch Date is now fixed

- Fix for unacessible files over external SDCard

- Bluetooth Fixes for Kirin 65x devices

- The installer script is now even more intelligent

### BENVENUTI
- Fixed led issues while in charge (booted OS)

- There should be less Bluetooth quirks. (I don't have a lot device to test this out, so please do report)

- Better LTE overlay

- Adaptive Backlight support

- Intrusive LED

-  From this build on, it's flashable via TWRP! **(ONLY RROS)**


### ALI 
- Finally we should get rid of the incorrect signal displaying

- Enhancing EMUI 8 power profile

- Revert fingerprint navigation (it's not working and that's definitely low in my priority list)

- Enhancing compatibility matrix 

- inherit some Huawei stuff

- maybe RRos bootanimation

- solved a bug which was making RRos wallpaper to not work on the latest builds

- changing builds name to identify them easily (they will have alphabetic order) the first one is entitled to Muhammed Ali



### 13042018 Round 2
- Better headphones recognizing

- Some Bluetooth drops should be gone

### 13042018
- EMUI8 power profile enabled

- Offline charging fixed 

- There should be no more vendor related messages on boot

- Compatibility matrix from EMUI8 added 

- Fingerprint Gestures should be now supported

### 12042018 round 2
- Fixes for some in the hood Huawei quirks

- Ambient Display is now supported

- Gapps are now included 

- Facedetection should be there as well (untested)

- Upstreamed to r20

- Some more fixes for LTE signal (let's hope that's the final one)

- Built- in Google Assistant

### 12042018 
- VoLTE support added (may or may not work, that's definetely low on my priority list, don't even mind to report errors about it)

- Adaptive brightness is now working

- Sim hotswap enabled

- BLE is now supported

### 20180407
- initial build lot of quirks expected please do report if something strange happens

- wrong signal behaviour should be fixed






