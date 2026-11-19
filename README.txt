Excel Formulas - Android app project (version 1.3)

Build the APK (free, one time setup):
1. Install Android Studio on a PC or Mac: developer.android.com/studio
2. Unzip this folder. In Android Studio choose File > Open and pick the folder.
3. Wait for the Gradle sync. Accept any prompt to install the Android SDK or Gradle.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s), then click "locate".
5. Copy app-debug.apk to your phone, open it and allow "Install unknown apps". Needs Android 10 or newer.

Or connect your phone with USB debugging on and press Run.

Updating later: replace app/src/main/assets/index.html with the newer file,
raise versionCode and versionName in app/build.gradle, and build again.
