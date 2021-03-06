# From zero to app

`From zero to app` will be a series of basic tutorials for Axway Appcelerator to create your first mobile app for Android and iOS using the power of JavaScript. You just need some basic JavaScript knowledge and a Linux, Windows or Mac (for iOS development). The tutorials will guide you from zero to your first app!

## Tutorials
* **[Installation](./installation.md)** - How to install Axway Appcelerator
* **[First app](./first_app.md)** - Your first app!
* **[Map project](./map_project.md)** - Add a map with pins to your app.
* **[Use the camera](./camera.md)** - Record pictures and videos in your app.
* **[Ah, push it](./push.md)** - Extend you app with Firebase push notifications (work in progress)
* **[Where am I?](./geolocation.md)** - Use geolocation services in your app. (soon)
* Ready for the store? [_coming soon_]

_Video tutorials are planed, too!_

## Requirements
At the time this tutorial was written the current version of the needed tools are:

| Tool | Version |
| --- | --- |
| JDK | 1.8.0 (JDK 8) |
| NodeJS | 8.12.0 (v10.12.0 LTS will be supported with 7.5.x, 7.4.x can be patched[1]) |
| Titanium SDK | 7.4.1.GA |
| Appcelerator CLI | 7.0.7 |
| Titanium CLI |5.2.0 |  
| Alloy | 1.13.3 |

It will be updated and tested with future version. If you find anything that is not working anymore please file an issue.

[1] NodeJS: open `.titanium/mobilesdk/linux/7.4.1.GA/android/cli/hooks/aar-transform.js`, find `.exists()` and change it to `.existsSync()`

## Feedback
If you have any question or comments feel free to add an `issue` or contact me ([twitter](https://twitter.com/MichaelGangolf), [mail](miga@migaweb.de), [Ti-Slack](http://tislack.org/)).

## Author
- Michael Gangolf ([@MichaelGangolf](https://twitter.com/MichaelGangolf) / [Web](http://migaweb.de))
