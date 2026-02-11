# XTunes

<div align="center">
  <img src="https://github.com/Arturo254/OpenTune/blob/master/fastlane/metadata/android/en-US/images/featureGraphic.png" alt="XTunes Banner" width="100%"/>
  
  ### Advanced YouTube Music Client (XTunes Fork) with Material Design 3
  
  [![Latest Version](https://img.shields.io/badge/Version-1.0.0--XTunes-orange?style=flat-square&logo=github&labelColor=161B22)](https://github.com/YOUR_USERNAME/OpenTune/releases)
  [![License](https://img.shields.io/badge/License-GPLv3-blue?style=flat-square&logo=gnu&labelColor=161B22)](https://github.com/YOUR_USERNAME/OpenTune/blob/main/LICENSE)
  [![Platform](https://img.shields.io/badge/Platform-Android%207.0+-3DDC84.svg?style=flat-square&logo=android&logoColor=white&labelColor=161B22)](https://www.android.com)
</div>

---

## Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Key Features](#key-features)
- [Installation](#installation)
- [Building from Source](#building-from-source)
- [License](#license)

---

## Overview

**XTunes** is an open-source YouTube Music client for Android, forked from OpenTune. It provides a premium, ad-free experience with a modern Material Design 3 interface, allowing you to explore, play, and manage music without the limitations of the official app.

### Key Benefits

- **Ad-Free Experience**: Enjoy uninterrupted music.
- **Background Playback**: Keep listening while using other apps.
- **Privacy Focused**: No data collection or tracking.
- **Customizable UI**: Personalize your player with dynamic themes.
- **Offline Support**: Download your favorite tracks for offline listening.

---

## Tech Stack

<div align="center">
  
| Frontend | Backend | Build Tools |
|:--------:|:-------:|:-----------:|
| ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white) | ![JVM 21](https://img.shields.io/badge/JVM-21-red?style=for-the-badge&logo=openjdk&logoColor=white) | ![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white) |
| ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white) | ![Hilt](https://img.shields.io/badge/Hilt-Injection-yellow?style=for-the-badge) | ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white) |

</div>

---

## Key Features

- **🎵 Ad-free Streaming**: No interruptions.
- **🎤 Synced Lyrics**: Real-time lyrics for your favorite songs.
- **🎨 Dynamic Themes**: UI adapts to album art colors.
- **🚗 Android Auto**: Full support for car infotainment systems.
- **🔊 Audio Enhancements**: Volume normalization and skip silence.
- **📚 Library Management**: Organize playlists and favorites effortlessly.

---

## Building from Source

### Prerequisites

| Tool | Recommended Version | Purpose |
|:-----|:-------------------|:--------|
| **JDK** | 21 | Runtime Environment |
| **Android Studio** | 2024.2+ (Ladybug/Koala) | IDE |
| **Android SDK** | API Level 35 | Development Tools |
| **Gradle** | 8.10+ | Build Automation |

### Build Steps

```bash
# 1. Clone your fork
git clone [https://github.com/YOUR_USERNAME/OpenTune.git](https://github.com/YOUR_USERNAME/OpenTune.git)

# 2. Navigate to directory
cd OpenTune

# 3. Build Signed Release APK
./gradlew assembleRelease
