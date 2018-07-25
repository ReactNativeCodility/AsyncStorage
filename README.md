# AsyncStorage
React Native Application to save data i.e. [AsyncStorage](https://facebook.github.io/react-native/docs/asyncstorage) which is  unencrypted, persistent, key-value storage system that is global to the app.

It is recommended that you use an abstraction on top of AsyncStorage instead of AsyncStorage directly for anything more than light usage since it operates globally.

This JS code is a simple facade over the native iOS implementation to provide a clear JS API, real Error objects, and simple non-multi functions. Each method returns a Promise object.

Async 1     |  Async 2 |  Async 3 |
:---------:|:----------:|:---------:
![](https://github.com/ReactNativeCodility/AsyncStorage/blob/master/design/main.png?raw=true)  |  ![](https://github.com/ReactNativeCodility/AsyncStorage/blob/master/design/store.png?raw=true) |  ![](https://github.com/ReactNativeCodility/AsyncStorage/blob/master/design/retrieve.png?raw=true) 

# Play Video
[![](https://github.com/ReactNativeCodility/AsyncStorage/blob/master/design/async.png?raw=true)](https://youtu.be/Re65jZLorQo "Click here to watch")

# Like Facebook Page
[![](https://github.com/AndroidCodility/Barchart-Graph/blob/master/design/fb.png?raw=true)](https://www.facebook.com/androidcodility/ "Click here")