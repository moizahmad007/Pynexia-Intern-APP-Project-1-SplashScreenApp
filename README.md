# Splash Screen App

A beginner-friendly Android Studio project using Kotlin and XML.

## Features
- Branded splash screen with a vector app logo
- Fade-in animation
- Two-second splash delay using `Handler`
- Navigation to `MainActivity` using an explicit `Intent`
- Removes the splash activity from the back stack with `finish()`

## Open and run
1. Extract `SplashScreenApp.zip`.
2. Open the extracted `SplashScreenApp` folder in Android Studio.
3. Allow Gradle to sync and install any requested Android SDK components.
4. Run the `app` configuration on an emulator or Android device.

## Customize
- Change the app name and welcome text in `app/src/main/res/values/strings.xml`.
- Change the splash background in `app/src/main/res/values/colors.xml`.
- Replace `ic_app_logo.xml` with your own logo if desired.
- Change `splashDelay` in `SplashActivity.kt` to adjust the delay.

## Project configuration
- Language: Kotlin
- UI: XML
- Minimum SDK: 23
- Compile/Target SDK: 35
- Android Gradle Plugin: 8.7.3
- Kotlin plugin: 2.0.21

A compatible Android Studio installation and JDK 17 are recommended.
