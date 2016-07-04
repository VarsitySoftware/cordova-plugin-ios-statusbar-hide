# Cordova Hide Status Bar plugin

For iOS, by [Varsity Software](https://github.com/VarsitySoftware)

## Description

This plugin hides the IOS StatusBar upon launch by automatically adding the following keys to the `*-Info.plist` file during the build process.

    <key>UIStatusBarHidden</key>
    <true />
    <key>UIViewControllerBasedStatusBarAppearance</key>
    <false />
    
## Installation

```
cordova plugin add https://github.com/VarsitySoftware/cordova-plugin-ios-statusbar-hide
```

## Usage

There is nothing to do.  Just add this plugin and the statusbar will automatically be hidden during launch.  Use the Cordova StatusBar plyugin to control the status bar after launch.
