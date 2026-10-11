NEET BUDDY - ANDROID PROJECT (BEGINNER GUIDE)
==============================================

Is folder mein Android Studio project ka source code hai. App ka interface local HTML/JavaScript mein hai aur Android WebView ke andar chalta hai. Basic features internet ke bina chalne ke liye design kiye gaye hain.

FEATURES
- Class 11 daily Physics/Chemistry/Biology tasks
- Checklist and daily progress
- 25-minute focus timer and 5-minute break
- Practice MCQs with answer explanations
- Streak tracking
- Local device storage (WebView localStorage)

IMPORTANT
- MCQs are practice questions for common Class 11 concepts, not a complete NEET question bank or official NCERT reproduction.
- First version stores progress on this device. Uninstalling/clearing app data may erase it.
- Streaks use device date. Keep date/time correct.
- This is source code, not a precompiled APK.

HOW TO BUILD APK ON WINDOWS
1. Install Android Studio from the official Android Developers website.
2. Extract this ZIP.
3. Android Studio -> Open -> choose the NEET_Buddy_Android_Project folder.
4. Wait for Gradle sync. If asked, install Android SDK Platform 35 and a compatible JDK through Android Studio.
5. For testing: connect Android phone with USB debugging enabled, then press Run.
6. To make an APK: Build -> Build Bundle(s) / APK(s) -> Build APK(s).
7. When finished, Android Studio shows a notification with "locate". Click it to find app-debug.apk.
8. Transfer app-debug.apk to your Android phone and install it. Android may ask permission to install unknown apps for the app you used to open it. Only install your own build.

IF GRADLE SYNC FAILS
- Check internet connection.
- In Android Studio, install Android SDK Platform 35 via Tools -> SDK Manager.
- Use a current Android Studio version and its recommended Gradle JDK.
- Don't change package names unless you know the Android project structure.

PROJECT STRUCTURE
settings.gradle
build.gradle
gradle.properties
app/build.gradle
app/src/main/AndroidManifest.xml
app/src/main/java/com/neetbuddy/app/MainActivity.java
app/src/main/assets/index.html

NEXT UPGRADES WE CAN BUILD
- Full syllabus chapter selector
- Customizable daily targets and reminder notifications
- More reviewed MCQs and explanations
- Backup/export progress
- Proper Android notifications and a stronger app lock for focus sessions
