# UIN Sunan Kalijaga Surat Information System  

UIN Sunan Kalijaga Surat Information System is base final project for RPL study. This is an android aplication using react native for base. Please follow this instructions below.

## React-Native
With `React Native`, you don't build a “mobile web app”, an “HTML5 app”, or a “hybrid app”. You build a real mobile app that's indistinguishable from an app built using Objective-C or Java. React Native uses the same fundamental UI building blocks as regular iOS and Android apps. You just put those building blocks together using JavaScript and React.

## Requirements

* `Node.js` (Download [Node.js](https://nodejs.org/en/download/))
* Git command (Download [Git Installer](https://git-scm.com/downloads))
* Java Development Kit 8 (Download [Jdk Installer](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html))
* `Android SDK` or can be installed by Android Studio

## How to Use

### Configuration

You can follow the step below to configure requirements such as SDK tools and Setting up the environtment variable. Open your Android Studio and find `SDK Manager` .Select the "SDK Platforms" tab from within the `SDK Manager`, then check the box next to "Show Package Details" in the bottom right corner. Look for and expand the `Android 6.0` (Marshmallow) entry, then make sure the following items are all checked:

* `Google APIs`
* `Android SDK Platform 23`
* `Intel x86 Atom_64 System Image`
* `Google APIs Intel x86 Atom_64 System Image`

![SDK Platform](https://facebook.github.io/react-native/img/AndroidSDKManagerWindows.png)

Next, select the "SDK Tools" tab and check the box next to "Show Package Details" here as well. Look for and expand the "Android SDK Build-Tools" entry, then make sure that `23.0.1` is selected.

![SDK Platform](https://facebook.github.io/react-native/img/AndroidSDKManagerSDKToolsWindows.png)

Then, you need to add Android SDK user variable to build apps with native code. Type `Edit The System Environment Variables` on your searchbox and choose the result. Open the Advanced tab and click on Environment Variables.... Click on New... to create a new ANDROID_HOME user variable that points to the path to your Android SDK:

![ANDROID_HOME](https://facebook.github.io/react-native/img/AndroidEnvironmentVariableANDROID_HOME.png)

The SDK is installed, by default, at the following location:
```
c:\Users\YOUR_USERNAME\AppData\Local\Android\Sdk
``` 

### Installation

After you download or clone this application and the requirements are ready, and modules and add React Native comand line interface by using this `comand`  

```
$ npm install
$ npm install -g react-native-cli
```

### Run The App

Make sure that you're already connect to android emulator device or use real device ( see this [Documentation](https://facebook.github.io/react-native/docs/running-on-device.html)) . You can run using this comand 

```
$ react-native run-android
```

Wait the procces, it will take a several minutes. `Happy Code`