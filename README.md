# MyApp

This is an Android application built entirely using the command line, without Android Studio.

## Project Structure
```
└───myapp
    │   build.gradle
    │   gradle.properties
    │   gradlew
    │   gradlew.bat
    │   local.properties
    │   my-release-key.keystore
    │   settings.gradle
    │
    ├───.gradle
    │   │   file-system.probe
    │   │
    │   ├───8.2
    │   │   │   gc.properties
    │   │   │
    │   │   ├───checksums
    │   │   │       checksums.lock
    │   │   │       md5-checksums.bin
    │   │   │       sha1-checksums.bin
    │   │   │
    │   │   ├───dependencies-accessors
    │   │   │       dependencies-accessors.lock
    │   │   │       gc.properties
    │   │   │
    │   │   ├───executionHistory
    │   │   │       executionHistory.bin
    │   │   │       executionHistory.lock
    │   │   │
    │   │   ├───fileChanges
    │   │   │       last-build.bin
    │   │   │
    │   │   ├───fileHashes
    │   │   │       fileHashes.bin
    │   │   │       fileHashes.lock
    │   │   │       resourceHashesCache.bin
    │   │   │
    │   │   └───vcsMetadata
    │   ├───buildOutputCleanup
    │   │       buildOutputCleanup.lock
    │   │       cache.properties
    │   │       outputFiles.bin
    │   │
    │   └───vcs-1
    │           gc.properties
    │
    ├───app
    │   │   build.gradle
    │   │
    │   └───src
    │       └───main
    │           │   AndroidManifest.xml
    │           │
    │           ├───java
    │           │   └───com
    │           │       └───example
    │           │           └───myapp
    │           │                   MainActivity.java
    │           │
    │           └───res
    │               ├───layout
    │               │       activity_main.xml
    │               │
    │               └───values
    │                       strings.xml
    │
    ├───build
    │   └───reports
    │       └───problems
    │               problems-report.html
    │
    └───gradle
        └───wrapper
                gradle-wrapper.jar
                gradle-wrapper.properties


```

## Prerequisites

- Java Development Kit (JDK 17+)
- Android SDK (Set `ANDROID_HOME` environment variable)
- Gradle (Installed or use Gradle Wrapper)

### Clone the Repository
```sh
git clone https://github.com/yourusername/myapp.git
cd myapp
```

## Build and Run

./gradlew build

./gradlew assembleRelease --keystore my-release-key.jks --keyalias mykeyalias
