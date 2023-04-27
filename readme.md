https://docs.expo.dev/develop/development-builds/create-a-build/



I test this library on expo dev build and get it works at least on ios. I used expo 48 and I first install react-native-webrtc and also add the expo plugin to app.json . I then add this library. Finally just rebuild your expo dev client and it should work. Haven't test it on Android but on IOS it works, so guess it should also work on Android. If you see the source code for this library, it's pretty simple with limited native code, so usually it won't have many issue with expo dev build
