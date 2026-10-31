# Reverbly phone app

Native Android + iOS app built with Capacitor from the web editor.

## Setup

```bash
npm install
npx cap sync
```

## Android

```bash
npx cap open android
```

Or build APK:

```bash
cd android && ./gradlew assembleDebug
```

APK: `android/app/build/outputs/apk/debug/app-debug.apk`

## iOS

Requires Xcode on macOS:

```bash
npx cap open ios
```

## Web assets

The app UI lives in `www/`. After changing it, run `npx cap sync`.
