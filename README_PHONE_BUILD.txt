ArchCalc - Android Project
==========================

This project was reconstructed from ArchCalc_Android_Source.txt.
The missing Gradle project configuration was added so the source has a standard
Android Studio/AndroidIDE project structure.

Phone build (AndroidIDE-style workflow):
1. Extract this ZIP to a normal folder.
2. Open the extracted ArchCalc folder as an Android/Gradle project.
3. Allow Gradle sync/dependency downloads to finish.
4. Build the app as a debug APK.
5. The debug APK will normally be under app/build/outputs/apk/debug/.

Important:
- This package is source code, not an APK.
- A full APK build requires an Android SDK, JDK 17-compatible build environment,
  Gradle/Android Gradle Plugin, and network access for dependencies on the first build.
- The original source uses compileSdk/targetSdk 34 and Java/Kotlin JVM target 17.
