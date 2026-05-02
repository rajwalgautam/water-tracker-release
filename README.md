# HydroTrack

**A simple, distraction-free water intake tracker for Android.**

[![Download Latest APK](https://img.shields.io/github/v/release/rajwalgautam/water-tracker-release?label=Download%20Latest%20APK&style=for-the-badge&logo=android&color=2196F3)](https://github.com/rajwalgautam/water-tracker-release/releases/latest)

> This repository hosts the APK releases for HydroTrack. Every merge to `main` in the source repository automatically builds and publishes a new release here.

---

## Requirements

- Android 8.0 (Oreo, API 26) or higher
- ~30 MB of free storage

---

## Installation

Because HydroTrack is distributed as a sideloaded APK rather than through the Play Store, Android will prompt you to allow installation from unknown sources. This is normal and safe — you are installing directly from this repository.

1. **Download the APK** — tap the badge above, or go to [Releases](https://github.com/rajwalgautam/water-tracker-release/releases/latest) and tap the `.apk` file.

2. **Allow installation from this source** — when prompted by Android, tap **Settings**, enable **Install unknown apps** for your browser or Files app, then go back and tap **Install**.
   - On older Android versions (8–9) this setting is under **Settings → Security → Unknown sources**.

3. **Install** — tap **Install** on the confirmation screen. The app will appear in your launcher as **HydroTrack**.

4. **Open and set up** — on first launch, set your daily water goal and configure reminders if desired.

---

## Permissions

HydroTrack requests the following permissions. None of them access personal data or the internet.

| Permission | Why it's needed |
|---|---|
| `RECEIVE_BOOT_COMPLETED` | Restores scheduled reminders after the device restarts |
| `SCHEDULE_EXACT_ALARM` | Fires hydration reminders at precise times |
| `VIBRATE` | Produces haptic feedback when a reminder fires |

---

## Release Notes

Each release includes auto-generated notes summarising the changes merged since the previous build. You can read them on the [Releases page](https://github.com/rajwalgautam/water-tracker-release/releases).

---

## About

HydroTrack is built with [Expo](https://expo.dev) / React Native and compiled via GitHub Actions on every push to `main`.
