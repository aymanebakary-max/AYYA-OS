# AYYA OS Android app

This is an Android Studio project wrapping AYYA OS Vol. 3 in a WebView. The app keeps its workspace in local browser storage on the device. JSON import and export are supported.

## Build without installing Android Studio
1. Upload the **contents** of this folder to the root of a GitHub repository (not the ZIP file itself).
2. Open the repository's **Actions** tab.
3. Choose **Build AYYA OS APK** and press **Run workflow**.
4. When the workflow completes, open it and download the `AYYA-OS-APK` artifact.
5. Extract the artifact ZIP and install `app-debug.apk` on your Android phone. Allow installation from your browser/file manager if Android asks.

## Build locally
Open this folder in Android Studio and build the `app` debug variant. Requires JDK 17 and Android SDK 35.
