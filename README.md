# 🐦 Bluebird OS

> **Free, open-source Android OS simulator & launcher with real desktop mode.**  
> Built in Uganda by the LAMN-NOBERT team. 🇺🇬

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.3%20Stable-green.svg)](releases)
[![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-brightgreen.svg)](releases)
[![Made in Uganda](https://img.shields.io/badge/Made%20in-Uganda%20🇺🇬-FCDC04.svg)](#)
[![Open Source](https://img.shields.io/badge/Open%20Source-Yes-red.svg)](#)

---

## What is Bluebird?

Bluebird is an Android OS simulator and launcher that makes your phone feel like a real desktop computer — without rooting. It runs a full Android environment inside your device, complete with windowed apps, a taskbar, built-in app suite, and a desktop mode that works on any phone.

It is not just a launcher. It is a layer that transforms how Android works — giving you a proper OS experience on hardware you already own.

---

## ✨ Features

- 🖥️ **Desktop Mode** — Real windowed experience with taskbar, window controls, and multitasking. Works with external monitors or in-hand.
- 📱 **OS Simulator + Launcher** — Use as your home launcher or run as a full environment simulator. No root required.
- 📦 **Built-in App Suite** — Browser, file manager, terminal, notes, music player, calculator, and more — all designed for the Bluebird environment.
- ⚡ **Lightweight** — Engineered to run smoothly on budget and mid-range Android devices.
- 🔓 **100% Free & Open Source** — MIT license. No ads, no telemetry, no tracking. Ever.
- 🌍 **Built for Everyone** — Designed with East Africa and the global majority in mind. Works great on affordable hardware.

---

## 📱 Screenshots

> _Screenshots coming soon. Contributors welcome to add them!_

---

## 🚀 Getting Started

### Requirements
- Android 8.0+ (API 26 or higher)
- ARM64 or ARMv7 architecture
- No root required

### Installation

**Option 1 — Direct APK (Recommended)**
1. Download the latest APK from the [Releases page](../../releases)
2. Enable "Install from unknown sources" in your Android settings
3. Open the downloaded APK and install
4. Set Bluebird as your default launcher when prompted

**Option 2 — ADB Install**
```bash
# Connect your device via USB with USB debugging enabled
adb install bluebird-v1.3-arm64.apk

# Verify installation
adb shell pm list packages | grep bluebird
```

### Enable Desktop Mode
1. Open Bluebird Settings
2. Go to **Display → Desktop Mode**
3. Toggle on — or connect to an external monitor via USB-C/HDMI and it activates automatically

---

## 📦 Releases

| Version | Status | Android API | Notes |
|---------|--------|-------------|-------|
| v1.4 | 🚧 In Development | 26+ | Coming soon |
| **v1.3** | ✅ **Stable (Latest)** | 26+ | Current recommended release |
| v1.2 | ✅ Stable | 26+ | Desktop mode introduced |
| v1.1 | ✅ Stable | 24+ | OS simulator improvements |
| v1.0 | ✅ Stable | 24+ | First public release |

→ [View all releases and changelogs](../../releases)

---

## 🏗️ Building from Source

```bash
# Clone the repository
git clone https://github.com/lamn-nobert/bluebird-os.git
cd bluebird-os

# Open in Android Studio
# File → Open → select the project folder

# Build debug APK
./gradlew assembleDebug

# Build release APK
./gradlew assembleRelease

# Install directly to connected device
./gradlew installDebug
```

### Prerequisites
- Android Studio Hedgehog (2023.1.1) or newer
- JDK 17+
- Android SDK with API 26–35

---

## 🤝 Contributing

We welcome contributions of all kinds — code, bug reports, translations, documentation, and app submissions.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

**Quick contribution guide:**
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add: your feature description"`
4. Push to your fork: `git push origin feature/your-feature-name`
5. Open a Pull Request — describe what you changed and why

---

## 📚 Documentation

Full documentation is available in the [Wiki](../../wiki) and on our website.

- [Getting Started Guide](../../wiki/Getting-Started)
- [Desktop Mode Guide](../../wiki/Desktop-Mode)
- [Building Apps for Bluebird](../../wiki/Building-Apps)
- [API Reference](../../wiki/API-Reference)
- [FAQ & Troubleshooting](../../wiki/FAQ)

---

## 🌐 Community

| Platform | Link |
|----------|------|
| 💬 Telegram | [Join our group](#) |
| 🎮 Discord | [Join the server](#) |
| 🔴 Reddit | [r/BluebirdOS](#) |
| 📺 YouTube | [Watch tutorials](#) |
| 𝕏 Twitter | [Follow us](#) |
| 🌍 Website | [bluebird-os.github.io](#) |

---

## 📋 Apps by LAMN-NOBERT

Apps built by our team that run inside the Bluebird environment:

| App | Description | Status |
|-----|-------------|--------|
| 🌐 Bluebird Browser | Lightweight privacy-first browser | Available |
| 📁 Bluebird Files | File manager with windowed mode support | Available |
| 💻 Bluebird Terminal | Shell terminal with SSH support | Available |
| 📝 Bluebird Notes | Markdown note-taking, local storage only | Available |
| 🎵 Bluebird Music | Local music player | Available |

Want to submit your own app? See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 🇺🇬 Made in Uganda

Bluebird is proudly built by the **LAMN-NOBERT team** in Uganda. We are part of the growing East African tech movement, proving that world-class, impactful software is being built right here on the continent.

No VC funding. No investors. Just developers who love Android and believe in open source.

---

## 📄 License

```
MIT License

Copyright (c) 2024–2026 LAMN-NOBERT Team, Uganda

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

→ [Read full license](LICENSE)

---

<div align="center">
  <strong>Built with ❤️ in Uganda 🇺🇬</strong><br>
  <sub>© 2024–2026 LAMN-NOBERT Team</sub>
</div>
