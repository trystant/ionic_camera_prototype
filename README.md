Ionic Camera Proof of Concept
=====================

An Ionic camera application for iOS/Android.

## Status

This project currently builds correctly for both Android and iOS. The app has successfully
taken a picture in an Android environment.

## Installation

In order to run this project, you need to install the following prerequisites with these commands:
This installs:
* [Ionic](http://ionicframework.com)
* [Cordova Camera Plugin](https://github.com/apache/cordova-plugin-camera)
* [Cordova Android Platform](https://cordova.apache.org/docs/en/4.0.0/guide_platforms_android_index.md.html#Android%20Platform%20Guide)
* [Cordova iOS Platform](https://cordova.apache.org/docs/en/4.0.0/guide_platforms_ios_index.md.html#iOS%20Platform%20Guide)

```bash
$ npm install -g ionic cordova
$ cordova plugin add cordova-plugin-camera
$ cordova platform update ios
$ cordova platform update android
```


Then run:

```bash
$ ionic run <platform (ios|android) >
```

