# RootRealm

Advanced Android system tools for root, Shizuku, ADB, backup, debloating, and device management.

![Kotlin](https://img.shields.io/badge/Kotlin-100%25-purple)
![Release](https://img.shields.io/badge/release-v1.1.0-brightgreen)
![License](https://img.shields.io/badge/license-Proprietary-red)

## Features

- 🔓 **Root access management** — detect and use root access for supported privileged operations.
- 📱 **Shizuku integration** — access supported privileged operations through Shizuku.
- 🖥️ **ADB tools** — run supported shell commands and manage device settings.
- 💾 **Backup & restore** — back up and restore supported apps and data, subject to Android restrictions.
- ✉️ **SMS & call-log backup** — optional backup functionality using the relevant permissions. SMS restoration depends on Android version and SMS-role requirements.
- 🧹 **Debloating** — disable or remove supported system apps where permissions allow.
- 🔋 **Battery Manager** — inspect charging status, voltage, current, power, and supported charging controls. Wired and wireless options depend on the device and kernel.
- 🧠 **Memory information** — view physical and usable RAM, ZRAM, disk swap, and RAM Expansion separately where system information is available.
- ⚙️ **Device management** — inspect system information and manage supported device-level settings.

## Requirements

- Android 12 (API 31) or higher, subject to the current build's actual minimum SDK.
- Root access or Shizuku for features that require privileged operations.
- USB debugging for applicable ADB features.
- Supported hardware and kernel interfaces for charging controls.

## Download

Download the APK from the [latest GitHub release](https://github.com/Omar9t5/rootrealm/releases/latest).

## Build from source

The source is publicly viewable for reference. Build instructions are provided for transparency, but viewing this repository does not grant permission to reuse its code.

```bash
git clone https://github.com/Omar9t5/rootrealm.git
cd rootrealm
./gradlew assembleDebug
```

## Permissions and privacy

Root Realm includes optional SMS and call-log backup functionality. SMS and call-log permissions should be used only for the related features when the user chooses to use them. These permissions are not needed merely to view battery or memory information. SMS restoration is subject to Android's default-SMS-app and version-specific restrictions.

Root and ADB operations can affect system behavior or data. Review prompts carefully and back up important data before making system-level changes. Features vary by device, Android version, root method, and kernel.

## Developer

**Faroque Tech** — Independent Android app developer and YouTuber.

- YouTube: https://youtube.com/@faroquetech
- GitHub: https://github.com/Omar9t5/rootrealm

## Proprietary License

Copyright © 2026 Faroque Tech. All rights reserved.

This repository is public for viewing and reference purposes only. No permission is granted to copy, modify, distribute, sublicense, or use this source code, in whole or in part, without prior written permission from the copyright holder.

Public visibility does not grant a license to reuse the code. This notice does not prevent people from technically downloading or copying publicly accessible files; it states the restrictions under which the code is made available.

## Support

Report bugs and request features through the repository's GitHub Issues. Do not post private information, SMS contents, call history, or other sensitive data.
