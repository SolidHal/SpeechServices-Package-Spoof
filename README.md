# Google App Stub

This app simulates Google's app being installed, useful for Android Auto


## Build

1) clone this repo
2) run `./gradlew`
3) get the Android sdk
4) set the SDK env var like this:
```
export ANDROID_SDK_ROOT=<PATH_TO_SDK>
```
5) run `./gradlew build`


## Sign
```
apksigner sign --key key.pk8 --cert key.x509.pem app/build/outputs/apk/release/app-release-unsigned.apk
```
