# Sharide demo (Android)

The Sharide tap-through demo wrapped as an Android app. Everything runs offline
from `app/src/main/assets/index.html`.

## Build on GitHub (no installs)
1. Create a new repository on github.com and upload all files from this folder,
   including the `.github` folder.
2. Open the **Actions** tab. The "Build APK" job runs on its own (about 3–5 minutes).
3. Open the finished run and download **sharide-demo-apk** at the bottom.
   Unzip it to get `app-debug.apk`.

## Build with Android Studio
1. Open this folder in Android Studio and let it sync.
2. Build > Build App Bundle(s) / APK(s) > Build APK(s).
3. The APK is in `app/build/outputs/apk/debug/`.

## Install on a phone
Send the APK to the phone, open it, and allow "Install unknown apps" when asked.
