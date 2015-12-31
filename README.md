# blaubot
Fork from original Blaubot 2.0.0-alpha.6 (Java) library to fix a few crashes

## Initial commit:
* Download JAR from [here](https://bintray.com/artifact/download/hgross/maven/eu/hgross/blaubot-android/2.0.0-alpha.6/blaubot-android-2.0.0-alpha.6-sources.jar)
* Rename to .zip & extract its content

## Compile:
* You need JDK >= 1.7 to compile this library.
* Download JDK and configure JDK path
![JDK Path](https://raw.githubusercontent.com/torinnguyen/blaubot/master/docs/jdk_path.png)

## Output JAR:
* The compile JAR can be found in **blaubot/build/libs/blaubot.jar**.
![JDK Path](https://raw.githubusercontent.com/torinnguyen/blaubot/master/docs/output.png)

## Usage:
* If you don't want to compile yourself, simply download **blaubot.jar** file from [here](https://raw.githubusercontent.com/torinnguyen/blaubot/blaubot/build/libs/blaubot.jar)
* Add **blaubot.jar** file to your project's **libs** folder
* Add following dependencies to your project's **build.gradle**
```
compile 'com.google.code.gson:gson:2.5'
compile 'javax.jmdns:jmdns:3.4.1'
```