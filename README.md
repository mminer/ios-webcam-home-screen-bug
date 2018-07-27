# iOS Webcam Home Screen Bug

In iOS there's a bug that prevents the webcam video feed from displaying when a website is added to the home screen and presents itself as web app capable. That is, when the `<meta name="apple-mobile-web-app-capable" content="yes">` tag is present, the video feed refuses to appear.

Working example [here](https://matthewminer.com/ios-webcam-home-screen-bug/working.html). Broken example [here](https://matthewminer.com/ios-webcam-home-screen-bug/broken.html). After visiting each page, choose "Add to Home Screen" from Safari's share button then open the web app from iOS' home screen.

Tested on iOS 12 public beta 3.
