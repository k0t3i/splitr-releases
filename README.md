<div align="center">

# SplitR

**Fast, controlled media splitting and export — without the FFmpeg complexity.**

[![Latest Release](https://img.shields.io/github/v/release/k0t3i/splitr-releases?label=Latest&style=flat-square)](https://github.com/k0t3i/splitr-releases/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D4?logo=windows&logoColor=white&style=flat-square)](https://github.com/k0t3i/splitr-releases/releases/latest)
[![macOS](https://img.shields.io/badge/macOS-Intel%20%2F%20Apple%20Silicon-000000?logo=apple&logoColor=white&style=flat-square)](https://github.com/k0t3i/splitr-releases/releases/latest)

### [Download the latest release](https://github.com/k0t3i/splitr-releases/releases/latest)

</div>

---

## About SplitR

SplitR is a desktop application for splitting, processing and exporting media files through a focused graphical interface.

It is designed to keep common FFmpeg workflows simple, fast and repeatable — without requiring command-line usage.

> **Release repository only.**  
> This repository contains distributable builds and release notes. The SplitR source code is not published here.

---

## Downloads

Choose the build that matches your system:

| Platform | Build |
| --- | --- |
| **Windows 10 / 11** | `.exe` |
| **macOS — Apple Silicon** | `arm64.dmg` |
| **macOS — Intel** | `x64.dmg` |

**Apple Silicon** includes Macs using Apple M-series chips (M1, M2, M3, M4 and later).

[**View all releases →**](https://github.com/k0t3i/splitr-releases/releases)

---

## Installation notice

Current SplitR builds are distributed without paid Apple or Microsoft code-signing certificates.

Because of this, Windows SmartScreen or macOS Gatekeeper may display a security warning the first time you launch the application.

This is expected for unsigned builds downloaded outside the Microsoft Store or Mac App Store.

### Windows

If Windows displays **“Windows protected your PC”**:

1. Click **More info**
2. Confirm the application is **SplitR**
3. Click **Run anyway**

### macOS

If macOS prevents SplitR from opening:

1. Try to open SplitR once
2. Open **System Settings**
3. Go to **Privacy & Security**
4. Scroll to the **Security** section
5. Find the SplitR warning
6. Click **Open Anyway**
7. Authenticate with your password or Touch ID
8. Launch SplitR again

This authorization is normally required only once.

---

## macOS — advanced troubleshooting

If Gatekeeper still blocks the application, move SplitR to your **Applications** folder, open Terminal and run:

```bash
xattr -dr com.apple.quarantine "/Applications/SplitR.app"
```

Then launch SplitR again.

> Use this command only with a SplitR build downloaded from this official repository. It removes the macOS quarantine attribute from the application.

---

## Official distribution

For security, download SplitR only from:

**https://github.com/k0t3i/splitr-releases/releases**

Do not install builds redistributed by third-party download sites or unverified links.

---

## Support

If SplitR does not launch or behaves unexpectedly, open an issue and include:

- operating system and version
- SplitR version
- Mac architecture, if applicable: Intel or Apple Silicon
- exact error message
- screenshot, when useful

[**Open an issue →**](https://github.com/k0t3i/splitr-releases/issues)

---

<div align="center">

**SplitR**  
Less setup. More control.

[Download](https://github.com/k0t3i/splitr-releases/releases/latest) · [Releases](https://github.com/k0t3i/splitr-releases/releases) · [Support](https://github.com/k0t3i/splitr-releases/issues)

</div>
