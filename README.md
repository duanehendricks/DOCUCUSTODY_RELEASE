# DOCUCUSTODY for Android

Public APK downloads for the DOCUCUSTODY document custody and handover companion. An assigned DOCUCUSTODY staff account and an internet connection are required.

[Download version 0.1.3](https://github.com/duanehendricks/DOCUCUSTODY_RELEASE/releases/tag/android-v0.1.3) · [DOCUCUSTODY website](https://dtk.abis.gov.jm/)

## What the app does

- Tracks documents and movement history related to your account.
- Shows incoming, outgoing and assigned bearer handovers.
- Supports collection, delivery, signed receipts and returns using your assigned permissions.
- Offers optional fingerprint or supported face sign-in.
- Sends 2–100 documents as a batch with one signature per stage; receive or reject the entire batch. Existing single-document handovers remain available.

Android 8.0 or later is required. This is a signed APK distributed outside Google Play; no Google Play listing or iOS app is available here. This repository contains public downloads and installation guidance, not the application source or staff data.

## Install on your phone

1. Open the release page on your Android phone and download **DOCUCUSTODY-0.1.3.apk** from **Assets**. You do not need a GitHub account. If you downloaded on a computer, transfer the APK to your phone.
2. Open the APK from the browser's downloads or **Files → Downloads**.
3. If Android blocks installation from this source, select **Settings** and enable **Allow from this source** for the browser or Files app you used. Return to the APK and select **Install**.
4. Open **DOCUCUSTODY** and sign in using the account assigned by your administrator. Complete a password change if requested. The app connects to the DTK service automatically.
5. Turn off **Allow from this source** afterward, under **Settings → Apps → Special app access → Install unknown apps**. Names vary by manufacturer.

Keep Google Play Protect enabled and allow its scan. If installation is blocked by work-device policy or Android reports a problem, contact your IT team. [Android's guidance on downloads from other sources](https://support.google.com/android/answer/9457058?hl=en).

To update a release installation, install the newer APK over the existing app. Version 0.1.3 uses the same signing identity and package as 0.1.2; keep the existing app installed. If Android reports a signature mismatch for an older development build, contact IT before uninstalling it.

## Release verification

- Version: **0.1.3 (4)**; package: `jm.gov.rada.docucustody`.
- Minimum Android: **8.0 (API 26)**; supports ARM and x86 phones/emulators.
- APK SHA-256: `34cc81d098a7c66a72371cb4aa448825c6d62f84a071d45cb4c66deb0a5245e6`.
- Signing certificate SHA-256: `5240629fc08a48ae2af56d43973758a4446f8d68ec526858cd2377ad7c0eba1f`.
- Release build, 13 Android JVM tests, lint and APK signature verification passed. Physical-device acceptance remains pending.

