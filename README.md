# blaubot
Fork from original Blaubot 2.0.0-alpha.6 (Java) library to fix a few crashes. See commit logs for the fixes.

## Where does this come from?
* The latest source code on https://github.com/Blaubot/Blaubot is labelled as 2.0.0-alpha.2, while the latest Maven artifacts is labelled 2.0.0-alpha.6. So I decided to start with source codes obtained from Maven artifacts instead.
* I downloaded [blaubot-android-2.0.0-alpha.6-sources.jar](https://bintray.com/artifact/download/hgross/maven/eu/hgross/blaubot-android/2.0.0-alpha.6/blaubot-android-2.0.0-alpha.6-sources.jar) from *bintray.com*
* I renamed to .zip & extract its content to get .java files

## How to compile:
* You need JDK >= 1.7 to compile this library.
* Download JDK and configure JDK path
![JDK Path](https://raw.githubusercontent.com/torinnguyen/blaubot/master/docs/jdk_path.png)

## Output JAR:
* The compile JAR can be found in **blaubot/build/libs/blaubot.jar**.
![JDK Path](https://raw.githubusercontent.com/torinnguyen/blaubot/master/docs/output.png)

## Usage:
* If you don't want to compile yourself, simply download **blaubot.jar** file from [here](https://github.com/torinnguyen/blaubot/raw/master/blaubot/build/libs/blaubot.jar)
* Add **blaubot.jar** file to your project's **libs** folder
* Add following dependencies to your project's **build.gradle**
```
compile 'com.google.code.gson:gson:2.5'
compile 'javax.jmdns:jmdns:3.4.1'
```