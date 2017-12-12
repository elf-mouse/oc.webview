iOS-WebView-App
===============

Simple iOS app that loads a web page created to ease debugging a `uiWebView`.

Unfortunately you cannot directly debug [Chrome on iOS](https://developer.chrome.com/multidevice/ios/overview) as debugging hooks are not available in published apps. This is the next best thing. If your issue reproduces the same in Mobile Safari, you can debug there. It's easier.

You'll need to [install XCode](https://developer.apple.com/xcode/downloads/).

1. "Download Zip" or clone this project
2. Open XCode, open existing project, and choose the project you just downloaded.
3. Open WebViewAppDelegate.m and change the `urlString` to be the URL you want to test.
4. Run the app in the iOS Simulator.
5. Open Safari, Open the *Develop* Menu, Choose *iOS Simulator* and select your webview.
6. Safari Inspector will now be inspecting your uiWebView.
