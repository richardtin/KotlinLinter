# KotlinLinter

KotlinLinter is a sample Android project (kotlin)

## Development Environment

You will require Android Studio 4.0 and Android SDK Level 29

The most straightforward way to build and run this application is to:

-   Install Android Studio: https://developer.android.com/studio/install
-   Install NDK in the SDK Manager, or download NDK manually: https://developer.android.com/ndk/downloads
-   Open the project in the Android Studio (**Note**: it should be opened, NOT imported)
-   Build and run the app directly in Android Studio

## Coding Conventions

-   [Kotlin style guide](https://developer.android.com/kotlin/style-guide)
    -   Add `kotlin.code.style=official` property to the **gradle.properties** file at the project root and commit the file to VCS.
-   [Code Style Migration Guide](https://kotlinlang.org/docs/reference/code-style-migration-guide.html)
    -   Switching to the Kotlin Coding Conventions code style can be done in `Settings → Editor → Code Style → Kotlin` dialog. Switch scheme to Project and activate `Set from... → Predefined Style → Kotlin Style Guide`.

## Linter

-   [ktlint](https://ktlint.github.io/)
-   [ktlint-gradle](https://github.com/JLLeitschuh/ktlint-gradle)
