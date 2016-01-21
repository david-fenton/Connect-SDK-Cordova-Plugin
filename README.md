# Connect SDK Cordova Plugin for Meteor.

This is a modified version of the Connect SDK Cordova plugin that has the entire Android files, except the Fling SDK, pulled in for use with Meteor. To see the real version, visit their repository: https://github.com/ConnectSDK/Connect-SDK-Cordova-Plugin.

## What's Different?

Meteor autogenerates a build.gradle file with its Cordova plugins on Android. Building the Connect SDK for Android does not work properly because of this. To circumvent the problem, this repository has already performed the Android install steps and includes those files in the Android folder already.

## How to Use?

When adding the plugin, the id has changed from cordova-plugin-connectsdk to cordova-plugin-connectsdk-meteor. We are currently pulling it into the project via the git url option https://github.com/david-fenton/Connect-SDK-Cordova-Plugin.git#COMMIT_HASH where COMMIT_HASH is the commit we are using.
