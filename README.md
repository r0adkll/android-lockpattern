android-lockpattern
===================

This is an AndroidStudio/Gradle port for the android-lockpattern
library hosted at: https://code.google.com/p/android-lockpattern/ 

how to use
==========

Set Android SDK path environment variable

```bash
$ export ANDROID_HOME='path to android sdk'
```

Push to your local maven repository

```bash
$ ./gradlew install
```

Now add the library to your project by adding ````compile 'com.haibison:androidLockPattern:1.0.0'```` to your dependencies.

**Note: Make sure you have mavenLocal under repositories**

```
repositories {
    mavenLocal()
    mavenCentral()
}
```
