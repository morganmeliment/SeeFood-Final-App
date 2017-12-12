SeeFood UIUC (READ DESCRIPTION TO GET THE ACTUAL FILE)
=======================

The file was to big to upload to git, so here is a dropbox link to it: https://www.dropbox.com/s/xeesdpue5x7loqm/cordova-plugin-camera-preview-sample-app-master%20copy.zip?dl=0

This is our final project for CS196.

## Install
```
cordova platform add android
cordova build android

cordova platform add ios
cordova build ios
```

## Reset / Update Plugin to Latest

If you last installed an older version of the plugin and want to ensure the sample app is up to date again just do the following to reset.

```
rm -rf platforms/ plugins/

cordova platform add android
cordova build android

cordova platform add ios
cordova build ios
```

## IOS Quirks

It is not possible to use your computers webcam during testing in the simulator, you must device test
