<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:7aa2f7,100:bb9af7&height=220&section=header&text=Yash%20Raj&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=React%20Native%20Engineer%20%C2%B7%20Bengaluru&descAlignY=53&descSize=16" width="100%" alt="Yash Raj" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=800&color=BB9AF7&center=true&vCenter=true&width=650&lines=%E3%83%A2%E3%83%90%E3%82%A4%E3%83%AB%E3%83%BB%E3%83%91%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%B3%E3%82%B9;Hermes+runtime+profiling;Skia+%C2%B7+Reanimated+%C2%B7+TurboModules;Beyond+the+framework+boundary" alt="typing" />

<br/>

<a href="https://giphy.com/gifs/5NE2L7vdWZ9V39Sjq8">
  <img src="https://media.giphy.com/media/5NE2L7vdWZ9V39Sjq8/giphy.gif" width="480" alt="" />
</a>

<br/><br/>

<a href="https://yashraj20.netlify.app"><img src="https://img.shields.io/badge/Portfolio-BB9AF7?style=for-the-badge&logo=vercel&logoColor=1A1B27&labelColor=1A1B27" alt="Portfolio"/></a>
<a href="https://linkedin.com/in/yash-raj20"><img src="https://img.shields.io/badge/LinkedIn-7AA2F7?style=for-the-badge&logo=linkedin&logoColor=1A1B27&labelColor=1A1B27" alt="LinkedIn"/></a>
<a href="https://www.npmjs.com/~pixelcube"><img src="https://img.shields.io/badge/npm-F7768E?style=for-the-badge&logo=npm&logoColor=1A1B27&labelColor=1A1B27" alt="npm"/></a>
<a href="mailto:yraj20081999@gmail.com"><img src="https://img.shields.io/badge/Email-9ECE6A?style=for-the-badge&logo=gmail&logoColor=1A1B27&labelColor=1A1B27" alt="Email"/></a>

<img src="https://img.shields.io/github/followers/yashpyraj?style=for-the-badge&color=BB9AF7&labelColor=1A1B27&logo=github" alt="followers"/>

</div>

<!-- Header GIF: hosted by GIPHY, embedded via their share URL (giphy.com/gifs/5NE2L7vdWZ9V39Sjq8). Swap the id to change it. -->

---

## 「自己紹介」 &nbsp;About Me

```yaml
name:      Yash Raj
role:      React Native Engineer
company:   BT Group
location:  Bengaluru, India

focus:
  - mobile performance
  - dense-data rendering
  - native modules

currently: >
  The charting layer of MyServices — the field-service platform
  Openreach engineers use daily across iOS, Android and web.
  GPU-accelerated Skia rendering, virtualized data windows, and
  on-device profiling down to the Hermes runtime.

philosophy: "The framework boundary is not the end of the stack."
```

---

## 「実績」 &nbsp;In Practice

> Numbers from real devices, not benchmarks.

<table>
<tr><td width="50%" valign="top">

### 🔥 &nbsp;−23.6s of hot-path cost

Traced 13–27s of chart latency on a real Samsung A52 to a Hermes trap where `toLocaleDateString` rebuilt an `Intl` formatter **~2,700 times per open**.

An O(1) lookup table removed it — shipped once **37 suites / 822 tests** proved it non-regressive.

</td><td width="50%" valign="top">

### 📊 &nbsp;1,344 bars at constant cost

Built a virtualized chart window rendering **~60 of 1,344 bars** at constant cost — past the platform texture ceiling (4096px Android / 16384px iOS), with no data hidden.

</td></tr>
<tr><td width="50%" valign="top">

### ⚡ &nbsp;Gestures off the JS thread

Moved pan and pinch-zoom to **Skia + Reanimated 4 worklets** on a *non-autolinked* build — hand-declared Gradle and CocoaPods, ProGuard rules, Metro resolver fix.

</td><td width="50%" valign="top">

### 🧩 &nbsp;Into the native layer

Went into `AppDelegate.mm` for an orientation bug the JS layer couldn't reach, and migrated a native module off AGP's eager task API ahead of its removal in 9.0.

</td></tr>
</table>

---

## 「作品」 &nbsp;Open Source

### [rn-app-exit](https://github.com/yashpyraj/rn-app-exit)

Exit **or background** a React Native app — full New Architecture (TurboModule) support, Kotlin and Objective-C++.

Built because [`react-native-exit-app`](https://www.npmjs.com/package/react-native-exit-app) had been unmaintained since 2021 and could never send an app to background.

[![npm](https://img.shields.io/npm/v/rn-app-exit?style=flat-square&color=F7768E&labelColor=1A1B27&logo=npm)](https://www.npmjs.com/package/rn-app-exit)
[![downloads](https://img.shields.io/npm/dm/rn-app-exit?style=flat-square&color=7AA2F7&labelColor=1A1B27)](https://www.npmjs.com/package/rn-app-exit)
[![CI](https://img.shields.io/github/actions/workflow/status/yashpyraj/rn-app-exit/ci.yml?branch=main&style=flat-square&label=CI&color=9ECE6A&labelColor=1A1B27)](https://github.com/yashpyraj/rn-app-exit/actions/workflows/ci.yml)
[![license](https://img.shields.io/npm/l/rn-app-exit?style=flat-square&color=BB9AF7&labelColor=1A1B27)](https://github.com/yashpyraj/rn-app-exit/blob/main/LICENSE)

```sh
npm install rn-app-exit
```

### [CustomSwitch](https://github.com/yashpyraj/CustomSwitch)

A styleable, animated switch for React Native — colour, size, label, thumb images and timing through a fully typed prop API.

[![npm](https://img.shields.io/npm/v/@pixelcube/customswitch?style=flat-square&color=F7768E&labelColor=1A1B27&logo=npm)](https://www.npmjs.com/package/@pixelcube/customswitch)
[![license](https://img.shields.io/badge/license-ISC-BB9AF7?style=flat-square&labelColor=1A1B27)](https://github.com/yashpyraj/CustomSwitch/blob/main/LICENSE)

---

## 「武器」 &nbsp;Stack

<div align="center">

**Languages & Core**

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="42" height="42" alt="TypeScript"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="42" height="42" alt="JavaScript"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" width="42" height="42" alt="Kotlin"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/swift/swift-original.svg" width="42" height="42" alt="Swift"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/objectivec/objectivec-plain.svg" width="42" height="42" alt="Objective-C"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="42" height="42" alt="Node.js"/>

**Mobile & Native**

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="42" height="42" alt="React Native"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg" width="42" height="42" alt="Android"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="42" height="42" alt="iOS"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gradle/gradle-original.svg" width="42" height="42" alt="Gradle"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" width="42" height="42" alt="Jest"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="42" height="42" alt="Git"/>

**State, Data & Web**

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redux/redux-original.svg" width="42" height="42" alt="Redux"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" width="42" height="42" alt="GraphQL"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" width="42" height="42" alt="Firebase"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/supabase/supabase-original.svg" width="42" height="42" alt="Supabase"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vitejs/vitejs-original.svg" width="42" height="42" alt="Vite"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" width="42" height="42" alt="Tailwind"/>

</div>

<details>
<summary><b>Full stack, in words</b></summary>

<br/>

| | |
|---|---|
| **Mobile** | React Native 0.83 (New Architecture) · Hermes · Skia · Reanimated 4 · Gesture Handler · MMKV · Expo |
| **Native** | Swift / Objective-C++ · Kotlin · Gradle & AGP · CocoaPods · ProGuard · Metro |
| **State & data** | Redux · Redux-Saga · Zustand · REST · GraphQL · Firebase · Supabase |
| **Web** | React · react-native-web · Astro · Qwik |
| **Testing** | Jest · on-device instrumentation · Hermes runtime profiling |

</details>

---

## 「記録」 &nbsp;Stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=yashpyraj&theme=tokyonight&hide_border=true&background=1A1B27&ring=BB9AF7&fire=F7768E&currStreakLabel=7AA2F7" alt="streak" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yashpyraj/yashpyraj/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yashpyraj/yashpyraj/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/yashpyraj/yashpyraj/output/github-snake.svg" alt="contribution snake" />
</picture>

</div>

---

<div align="center">

### 「連絡」 &nbsp;Get in touch

**[Portfolio](https://yashraj20.netlify.app)** &nbsp;·&nbsp; **[LinkedIn](https://linkedin.com/in/yash-raj20)** &nbsp;·&nbsp; **[yraj20081999@gmail.com](mailto:yraj20081999@gmail.com)**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:bb9af7,50:7aa2f7,100:1a1b27&height=140&section=footer" width="100%" alt="" />

</div>
