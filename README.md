## Sample Gradle Web Project

This is my project files and notes as I followed Dr. William Billingsley's video tutorial at http://www.youtube.com/watch?v=dA8pDjsQwtM.

## Install Gradle

The video does not mention about installing gradle. To install gradle, follow the documentation at http://www.gradle.org/installation. Gradle requires JDK 1.5 or higher.

I use Mac OSX and I prefer to install gradle via homebrew.

```
$ brew update
$ brew install gradle
$ gradle -version

------------------------------------------------------------
Gradle 2.0
------------------------------------------------------------

... (omitted for brevity)
```

## Run test
```
$ gradle test
```

## Serve web project using Jetty
```
$ gradle appRun

Open http://localhost:8080/sample_gradle_webproj/greet?name=YourNameHere in your web browser.
```
