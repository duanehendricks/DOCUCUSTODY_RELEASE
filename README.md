# DOCUCUSTODY for Android

Public APK downloads for the DOCUCUSTODY document custody and handover companion. An assigned DOCUCUSTODY staff account and an internet connection are required.

[Download version 0.1.5](https://github.com/duanehendricks/DOCUCUSTODY_RELEASE/releases/download/android-v0.1.5/DOCUCUSTODY-0.1.5.apk) · [Release notes](https://github.com/duanehendricks/DOCUCUSTODY_RELEASE/releases/tag/android-v0.1.5) · [DOCUCUSTODY website](https://dtk.abis.gov.jm/)

## What the app does

- Tracks documents and movement history related to your account.
- Shows incoming, outgoing and assigned bearer handovers.
- Supports collection, delivery, signed receipts and returns using your assigned permissions.
- Offers optional fingerprint or supported face sign-in.
- Sends 2–100 documents as a batch with one signature per stage; receive or reject the entire batch.
- Provides a personal notification inbox, unread counts and phone notification support for handover updates.

Android 8.0 or later is required. This signed APK is distributed outside Google Play. No Google Play listing or iOS app is available here. This repository contains public downloads and installation guidance, not application source or staff data.

## Install or update

1. On your Android phone, download **DOCUCUSTODY-0.1.5.apk** using the link above. No GitHub account is needed. If you download on a computer, transfer the APK to your phone.
2. Open the APK from your browser's downloads or **Files → Downloads**.
3. If Android blocks installation from this source, enable **Allow from this source** for the browser or Files app you used. Return to the APK and select **Install**.
4. Install over the existing DOCUCUSTODY release; keep the existing app installed. Version 0.1.5 uses the same package and signing identity as the previous public releases.
5. Open **DOCUCUSTODY**. If updating, sign out and sign in again. Use the account assigned by your administrator and complete any required password change.
6. Choose **Allow phone notifications** and grant Android's notification permission.
7. Turn off **Allow from this source** afterward, under **Settings → Apps → Special app access → Install unknown apps**. Names vary by phone.

Keep Google Play Protect enabled and allow its scan. If your work-device policy blocks installation or Android reports a signature mismatch, contact IT before uninstalling anything. [Android installation guidance](https://support.google.com/android/answer/9457058?hl=en).

## Test phone notifications

After signing in and allowing notifications, an administrator can open **Notifications → Phone** on the website, select your registered phone and choose **Send test to selected phone**. Physical-device delivery acceptance remains pending. Email delivery is configured separately.

## Release verification

- Version: **0.1.5 (6)**; package: `jm.gov.rada.docucustody`.
- Minimum Android: **8.0 (API 26)**.
- APK SHA-256: `19a58e37f083e509cccdd815d0fe72b907c8061f98031323e2f287c3fb1e9d64`.
- Signing certificate SHA-256: `5240629fc08a48ae2af56d43973758a4446f8d68ec526858cd2377ad7c0eba1f`.
- Release build, 15 Android JVM tests, lint with no errors, APK signature verification and anonymous public download checksum verification passed.
