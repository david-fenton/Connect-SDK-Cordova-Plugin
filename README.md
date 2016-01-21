# Connect SDK Cordova Plugin for Meteor.

This is a modified version of the real Connect SDK Cordova plugin that already has the entire Android files, except the Fling SDK, pulled in for use with Meteor. To see the real version, visit their repository: https://github.com/ConnectSDK/Connect-SDK-Cordova-Plugin.

## What's Different?

Meteor autogenerates a build.gradle file with its Cordova plugins on Android. Building the Connect SDK for Android does not work properly because of this. To circumvent the problem, this repository has already performed the Android install steps and includes those files in the Android folder already.
