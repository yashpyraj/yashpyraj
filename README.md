## Yash Raj

React Native engineer in Bengaluru. I work on mobile performance and dense-data rendering — and I don't stop at the framework boundary.

At **BT Group** I own the charting layer of MyServices, the field-service platform Openreach engineers use daily across iOS, Android and web: GPU-accelerated Skia rendering, virtualized data windows, and on-device profiling that goes down to the Hermes runtime and the native app layer.

### What that looks like in practice

- Traced 13–27s of chart latency on a real Samsung A52 to a Hermes trap where `toLocaleDateString` rebuilt an `Intl` formatter ~2,700 times per open. An O(1) lookup table removed **23.6s** of hot-path cost — shipped once 37 suites / 822 tests proved it non-regressive.
- Built a virtualized chart window that renders ~60 of 1,344 bars at **constant cost**, past the platform texture ceiling (4096px Android / 16384px iOS), with no data hidden.
- Moved pan and pinch-zoom off the JS thread with React Native Skia + Reanimated 4 worklets, on a **non-autolinked** build — hand-declared Gradle and CocoaPods, ProGuard rules, Metro resolver fix.
- Went into `AppDelegate.mm` for an orientation bug the JS layer couldn't reach, and migrated a native module off AGP's eager task API ahead of its removal in 9.0.

### Open source

**[rn-app-exit](https://github.com/yashpyraj/rn-app-exit)** — exit or background a React Native app, with full New Architecture (TurboModule) support. Kotlin and Objective-C++. Built because [`react-native-exit-app`](https://www.npmjs.com/package/react-native-exit-app) had been unmaintained since 2021 and could never send an app to background.

```sh
npm install rn-app-exit
```

[![npm](https://img.shields.io/npm/v/rn-app-exit.svg?style=flat&color=cb3837&logo=npm)](https://www.npmjs.com/package/rn-app-exit)
[![downloads](https://img.shields.io/npm/dm/rn-app-exit.svg?style=flat&color=cb3837)](https://www.npmjs.com/package/rn-app-exit)
[![license](https://img.shields.io/npm/l/rn-app-exit.svg?style=flat)](https://github.com/yashpyraj/rn-app-exit/blob/main/LICENSE)

### Stack

**Language** TypeScript · JavaScript
**Mobile** React Native 0.83 (New Architecture) · Hermes · Skia · Reanimated 4 · Gesture Handler · MMKV · Expo
**Native** Swift/Objective-C++ · Kotlin · Gradle & AGP · CocoaPods · ProGuard · Metro
**State & data** Redux · Redux-Saga · Zustand · REST · GraphQL · Firebase
**Web** React · react-native-web · Astro · Qwik
**Testing** Jest · on-device instrumentation · Hermes runtime profiling

### Elsewhere

[Portfolio](https://yashraj20.netlify.app) · [LinkedIn](https://linkedin.com/in/yash-raj20) · [yraj20081999@gmail.com](mailto:yraj20081999@gmail.com)
