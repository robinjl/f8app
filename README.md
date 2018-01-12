# F8 App 2017

This is the entire source code of the official [F8](https://fbf8.com/) app of 2017, available on [Google Play](https://play.google.com/store/apps/details?id=com.facebook.f8) and the [App Store](https://itunes.apple.com/us/app/f8/id853467066).

<img src=".github/screenshot-app@2x.png" width="800">


## How We Build It

We've created a series of tutorials at http://makeitopen.com/ that explain how we built the app, and that dive into how we used React Native, Redux, Relay, GraphQL, and more.

Check out how to set the app up for local development [here](http://makeitopen.com/docs/en/1-A1-local-setup.html)!



## 本地部署注意事项
### iOS 
1. 更改 Bundle Identifier, 区分原有id
2. 字体报错，修改"basis"为react native可识别的字体库
3. react-native-native-video-player 可能报错，参考github配置说明
4. Falling back to storing access token in NSUserDefaults because of simulator bug
