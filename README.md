# HelloCompat
# Android fundamentals 03.3: Support libraries

## App overview

In this practical you'll create an app called HelloCompat with one  `TextView`  that displays "Hello World" on the screen, and one  `Button`  that changes the color of the text. There are 20 possible colors, defined as resources in the  `color.xml`  file, and each button click randomly picks one of those colors.
The methods to get a color value from the app's resources have changed with different versions for the Android framework. This example uses the  `ContextCompat`  class in the Android Support Library, which allows you to use a method that works for all versions.

## What you'll learn

-   How to verify that the Android Support Library is available in your Android Studio installation.
-   How to indicate support library classes in your app.
-   How to tell the difference between the values for  `compileSdkVersion`,  `targetSdkVersion`, and  `minSdkVersion`.
-   How to recognize deprecated or unavailable APIs in your code.
-   More about the Android support libraries.

## What you'll do

-   Create a new app with one  `TextView`  and one  `Button`.
-   Verify that the Android Support Repository (containing the Android Support Library) is available in your Android Studio installation.
-   Explore the  `build.gradle`  files for your app project.
-   Manage class or method calls that are unavailable for the version of Android your app supports.
-   Use a compatibility class from the support library to provide backward-compatibility for your app.
