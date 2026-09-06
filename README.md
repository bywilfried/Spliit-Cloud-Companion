<div align="center">

# ☁️ Spliit Cloud Companion

### Spliit Cloud, directly on Android

A lightweight Android application based on a **Trusted Web Activity (TWA)** that lets you use [Spliit Cloud](https://spliit.cloud) as an Android app.

[Open Spliit Cloud](https://spliit.cloud) · [Spliit Cloud repository](https://github.com/antonio-ivanovski/spliit-cloud/)

</div>

---

## About

**Spliit Cloud Companion** is a companion Android application that provides access to the **Spliit Cloud** instance hosted at **https://spliit.cloud**.

The project is built as a **Trusted Web Activity (TWA)**. The Android application does not reimplement Spliit Cloud. Instead, it provides a dedicated Android container that displays the web application directly in a full-screen experience.

```text
Android
   │
   ▼
Spliit Cloud Companion
   │
   │ Trusted Web Activity
   ▼
https://spliit.cloud
   │
   ▼
Spliit Cloud
```

## Why a TWA?

This approach makes it possible to:

- use Spliit Cloud through a dedicated Android application;
- provide a full-screen experience close to a native application;
- keep the web application as the main source of the user experience;
- benefit from Spliit Cloud updates without reimplementing its interface on Android;
- keep the Android application lightweight.

## Spliit Cloud

The Spliit Cloud service used by this companion application is available at:

**https://spliit.cloud**

The source code of the Spliit Cloud web application is available here:

**https://github.com/antonio-ivanovski/spliit-cloud/**

This repository only contains **Spliit Cloud Companion and its Android/TWA integration**. For features, UI changes, or the implementation of the web application itself, please refer to the Spliit Cloud repository above.

## Trusted Web Activity

A **Trusted Web Activity** allows an Android application to display a web application/PWA in full screen using a compatible browser installed on the device.

Trust between the Android application and the web domain is established through **Digital Asset Links**.

## Credits

**Spliit Cloud Companion** is an independent companion project designed to make Spliit Cloud convenient to use on Android.

The **Spliit Cloud** web application is a separate project. All credit for Spliit Cloud, its source code, and its development belongs to its respective authors and contributors.

<div align="center">

**Spliit Cloud in your pocket.**

[🌐 spliit.cloud](https://spliit.cloud) · [💻 Spliit Cloud on GitHub](https://github.com/antonio-ivanovski/spliit-cloud/)

</div>
