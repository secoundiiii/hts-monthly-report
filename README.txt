HTS Monthly Report - Android project
====================================

This folder builds a debug APK of the HTS Monthly Report app.
The app works offline. It has no internet permission, and it saves its data on the phone.
Backups and CSV files are saved in the phone's Downloads folder.

WAY 1: Android Studio (on a computer)
  1. Install Android Studio (free) and choose File > Open, then pick this folder.
  2. Wait for the Gradle sync to finish.
  3. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
  4. Click "locate" in the pop-up. The file is app-debug.apk.

WAY 2: GitHub (no installation needed)
  1. Make a free account at github.com and create a new private repository.
  2. Upload everything in this folder, including the hidden .github folder.
  3. Open the repository's Actions tab. Run "Build debug APK" (or it starts by itself).
  4. When it finishes, open the run and download HTS-Report-debug-apk at the bottom.
  5. Unzip it to get app-debug.apk.

INSTALLING ON A PHONE
  Send app-debug.apk to the phone, open it, and allow "Install unknown apps" when asked.
  Android 10 or newer is needed.

A debug APK is for testing and for sharing with your own team. Google Play needs a
release bundle (.aab) instead.
