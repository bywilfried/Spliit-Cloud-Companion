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

## APK signature verification

Official release APKs are signed with the **Spliit Cloud Companion** signing certificate.

You can verify that an APK was signed with the expected certificate by comparing its certificate fingerprint with the values below.

**Certificate SHA-256**

```text
4B:64:EB:C7:EB:E7:F7:0C:26:3C:68:1D:43:86:C9:CD:7B:39:9B:1D:24:5D:16:BC:CC:47:35:42:F5:BF:D5:2F
```

**Certificate SHA-1**

```text
73:61:6B:DC:FC:12:7F:8F:04:E6:4A:A6:0C:06:46:70:BA:23:08:14
```

To inspect an APK with the Android SDK build tools:

```bash
apksigner verify --verbose --print-certs app-release.apk
```

You can also inspect the signing certificate with Java's `keytool`:

```bash
keytool -printcert -jarfile app-release.apk
```

The **certificate fingerprint should remain the same across releases** as long as the same signing key is used.

For reference, the SHA-256 checksum of the currently verified APK build is:

```text
89b8336cec45e83dca2be96f46ccc2bfa49728dc209635947b2a1caa86d89410
```

Unlike the signing-certificate fingerprint, the APK file checksum changes whenever the APK contents change, so it is specific to that exact build.

## Credits

**Spliit Cloud Companion** is an independent companion project designed to make Spliit Cloud convenient to use on Android.

The **Spliit Cloud** web application is a separate project. All credit for Spliit Cloud, its source code, and its development belongs to its respective authors and contributors.

<div align="center">

**Spliit Cloud in your pocket.**

[🌐 spliit.cloud](https://spliit.cloud) · [💻 Spliit Cloud on GitHub](https://github.com/antonio-ivanovski/spliit-cloud/)

</div>
