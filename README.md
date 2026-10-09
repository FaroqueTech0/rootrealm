# RootRealm

Advanced Android system tools for root, Shizuku, ADB, backup, debloating, and device management.

![Kotlin](https://img.shields.io/badge/Kotlin-100%25-purple)
![Release](https://img.shields.io/badge/release-v1.2.0-brightgreen)
![License](https://img.shields.io/badge/license-Proprietary-red)

**Website:** [https://faroquetech0.github.io/rootrealm/](https://faroquetech0.github.io/rootrealm/)

## Features

- 🔓 **Root access management** — detect and use root access for supported privileged operations.
- 📱 **Shizuku integration** — access supported privileged operations through Shizuku.
- 🖥️ **ADB tools** — run supported shell commands and manage device settings.
- 💾 **Backup & restore** — back up and restore supported apps and data, subject to Android restrictions.
- ✉️ **SMS & call-log backup** — optional backup functionality using the relevant permissions. SMS restoration depends on the Android version and default-SMS-app requirements.
- 🧹 **Debloating** — disable or remove supported system apps where permissions allow.
- 🔋 **Battery Manager** — inspect charging status, voltage, current, power, and supported charging controls. Wired and wireless options depend on the device and kernel.
- 🧠 **Memory information** — view physical and usable RAM, ZRAM, disk swap, and RAM Expansion separately where system information is available.
- ⚙️ **Device management** — inspect system information and manage supported device-level settings.

## Requirements

- Android 12 (API 31) or higher, subject to the actual minimum SDK of the installed build.
- Root access or Shizuku for features that require privileged operations.
- USB debugging for applicable ADB features.
- Supported hardware and kernel interfaces for charging controls.

Some features may be unavailable depending on the device, Android version, kernel, permissions, and access method.

## Download

Official downloads are published through the RootRealm GitHub repository.

- [Latest release](https://github.com/FaroqueTech0/rootrealm/releases/latest)
- [All releases](https://github.com/FaroqueTech0/rootrealm/releases)
- [Source repository](https://github.com/FaroqueTech0/rootrealm)
- [Website](https://faroquetech0.github.io/rootrealm/)

For the safest installation experience, obtain RootRealm from the official releases page.

> **Note:** Starting from the next update, SHA-256 checksums will be published with every official release so you can easily verify the authenticity of the APK.

## Official Downloads & APK Authenticity

RootRealm is developed and maintained by FaroqueTech. The official GitHub repository is the primary source for release announcements, APK downloads, release notes, and project information.

### Third-party downloads

RootRealm APKs hosted on external websites, file-sharing services, or third-party repositories are not verified or controlled by FaroqueTech unless explicitly confirmed by the developer.

A third-party APK may be an unchanged copy of an official release, an outdated build, or a modified version. The hosting location alone does not establish whether a file is authentic or safe.

FaroqueTech cannot guarantee the integrity, authenticity, or safety of independently distributed or modified copies that have not been verified against an official release.

### How to verify an APK

Before installing a RootRealm APK obtained from a third-party source:

1. Compare its SHA-256 checksum with the checksum published for the corresponding official release, when available.
2. Verify its signing certificate against the official release's signing-certificate fingerprint.
3. Check the package name, version name, and version code against the official release information.
4. Download future updates from the official GitHub repository whenever possible.

A matching SHA-256 checksum confirms that the files are identical to the trusted reference file. A matching signing certificate helps establish that the APK was signed with the same signing key. Neither check, by itself, guarantees that the software is free from vulnerabilities.

**Important:** Do not assume that an APK is official simply because it uses the RootRealm name, logo, package name, or screenshots.

### Reporting suspicious copies

If you find an APK that appears to have been modified or distributed deceptively under the RootRealm name, please report it through:

[GitHub Issues](https://github.com/FaroqueTech0/rootrealm/issues)

Include the relevant download URL, version information, and available verification details. Do not upload private information or sensitive device data.

## Build from Source

The source code is publicly viewable for reference and transparency. Public repository access does not grant permission to reuse, modify, redistribute, or incorporate the code into another project.

If you want to inspect the repository, you can clone it using Git:

```bash
git clone https://github.com/FaroqueTech0/rootrealm.git
cd rootrealm
./gradlew assembleDebug
