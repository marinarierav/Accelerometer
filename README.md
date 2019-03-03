# Accelerometer
Proves accelerometre del mobil

## Install
npm install

## Build (Android debug)

ionic cordova build android
adb install -r ./platforms/android/app/build/outputs/apk/debug/app-debug.apk

## Build (Android Release)

ionic cordova build android --prod --release

## Testing

ionic cordova run android -l
