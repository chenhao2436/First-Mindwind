# First Mindwind Android

Personal Android English-learning application.

The Android source project is packaged in `FirstMindwind-source.tar.xz.b64`. GitHub Actions decodes and extracts the archive, builds a debug APK, verifies that it exists, and uploads it as the workflow artifact `First-Mindwind-Android-APK`.

## Build locally

- JDK 17
- Android SDK Platform 35
- Android Build Tools 35.0.0
- Gradle 8.9

The app does not contain an API key. Revoke any key previously pasted into chat and configure a newly created DeepSeek key in the app's Settings screen.

## Build artifact

After a successful run, open Actions → Build First Mindwind APK → Artifacts → First-Mindwind-Android-APK.
