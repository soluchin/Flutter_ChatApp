# chatApp

Learning flutter project by creatin an chat app.

Requirements:
- Flutter must already be installed on your computer. [click](https://docs.flutter.dev/get-started/install/windows) to see installataion.

## Getting Started

First you have to prepare a connection to your android device using USB.

### Build an APK
Command line:
- Enter `cd [project]`
- Run `flutter build apk --split-per-abi`

This command results in three APK files:
- [project]/build/app/outputs/apk/release/app-armeabi-v7a-release.apk
- [project]/build/app/outputs/apk/release/app-arm64-v8a-release.apk
- [project]/build/app/outputs/apk/release/app-x86_64-release.apk

### Install APK on an Android Device
Command line:
- Connect your Android device to your computer with a USB cable.
- Enter `cd [project]`
- Run `flutter install`
