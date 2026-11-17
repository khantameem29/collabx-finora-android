# CollabX & Finora — Android Apps

Lightweight Android apps (WebView wrappers) for my two web projects, so they can be installed and opened like native apps on any Android phone.

| App | Opens | Download |
|---|---|---|
| CollabX | https://frontend-iota-liart-82.vercel.app | [`apk/CollabX.apk`](apk/CollabX.apk) |
| Finora | https://finora-app.netlify.app | [`apk/Finora.apk`](apk/Finora.apk) |

## Features

- Full-screen app experience with themed status/navigation bars
- Hardware back button navigates inside the app
- File uploads supported (for CollabX file sharing)
- Friendly offline screen with a retry button
- Minimum Android 7.0 (API 24)

## Install

Download the APK on an Android phone, open it, and allow "Install unknown apps" when prompted. An internet connection is required (the apps load the live sites).

## Build from source

Plain Java + Android SDK command-line tools, no Gradle:

```bash
KS=release.keystore KS_PASS=yourpass KS_ALIAS=youralias ./build.sh
```

---
Tameem Khan · [Portfolio](https://khantameem29.github.io) · ktameem2004@gmail.com
