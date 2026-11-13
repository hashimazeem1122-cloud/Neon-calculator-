# Neon Calculator Android App

This repository contains a simple Android WebView app that loads the calculator UI from `app/src/main/assets/index.html`.

## Build Android APK

1. Install Android Studio.
2. Open this folder as a project.
3. Let Gradle sync finish.
4. Select `Build > Build Bundle(s) / APK(s) > Build APK`.
5. The APK will be generated at:
   - `app/build/outputs/apk/debug/app-debug.apk`
   - or `app/build/outputs/apk/release/app-release.apk`

## Files

- `app/src/main/assets/index.html` — calculator screen and JavaScript logic
- `app/src/main/java/com/neon/calculator/MainActivity.java` — loads the HTML in a WebView

