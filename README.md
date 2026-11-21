# JARVIS Beta 0.1 — Android Studio project

Target device: Samsung Galaxy A35 5G (8 GB RAM, Android 16)

## What this beta contains
- Jetpack Compose dark blue JARVIS-style dashboard
- Animated central reactor
- Home / Tasks / System / Settings navigation
- Microphone button visual-state prototype

## Not implemented yet
This is a UI beta only. The microphone button does not record audio. Offline speech recognition, wake word, calling, alarms, reminders, notifications, local AI, music, and sync will be added in later phases.

## Build an APK
1. Install the latest stable Android Studio: https://developer.android.com/studio
2. Extract this folder.
3. In Android Studio choose **Open** and select the extracted `JARVIS_Beta` folder.
4. Allow Gradle sync and install any requested Android SDK 36 components.
5. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. When the build completes, choose **locate**. The debug APK will be at `app/build/outputs/apk/debug/app-debug.apk`.
7. Transfer that APK to your Galaxy A35 and install it. Android may ask you to allow installation from that source.

The project uses Android Gradle Plugin 8.10.1, Kotlin 2.1.20, and Compose BOM 2025.04.01. Android Studio may download Gradle and dependencies on first sync, so internet is needed for the initial build. The installed app's current dashboard does not need internet.
