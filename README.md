android-lockpattern
===================

This is an AndroidStudio/Gradle port for the android-lockpattern
library hosted at: https://code.google.com/p/android-lockpattern/ 

how to use
==========

First set the ANDROID_HOME environment variable to point to your Android SDK location

    $ export ANDROID_HOME='path to sdk'

Push to your local maven repository

    $ ./gradlew install

Now add the library to your project by adding ````compile 'com.haibison:androidLockPattern:1.0'```` to your dependencies.

**Note: Make sure you have mavenLocalß under repositories**

repositories {
mavenLocal()
mavenCentral()
}
