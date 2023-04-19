# SM64EX Android Port
This is fork of [VDavid003's port](https://github.com/VDavid003/sm64-port-android/tree/ex/master). My goal is to use this repo to fix a few issues and maybe add a few features.

## ex/master branch vs ex/nightly branch
The Retroid Pocket 3 (non-plus version) can't run the app when built from ex/nightly for some reasaon. It was able to previously after and OTA update, but then another OTA update broke it again. This ex/master branch does work on the RP3, so I may do minimal maintaining of it for RP3 users. This branch does not support the 60 FPS or DynOS features.

## Building on an Android device
Use the helper script found here: [https://samutz.com/sm64/](https://samutz.com/sm64/)  
But add /rp3 to the generated script url to download the ex/master branch instead of ex/nightly.  
Or use the manual instructions found here: [Building Super Mario 64 on Android](https://samutz.com/docs/books/video-games/page/building-super-mario-64-on-android)

If you want to build SM64EX for Android on PC use [VDavid003's base repo](https://github.com/VDavid003/sm64-port-android-base) instead!
