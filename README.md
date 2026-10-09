RootRealm

Advanced Android system tools for root, Shizuku, ADB, backup, debloating, and device management.

"Kotlin" (https://img.shields.io/badge/Kotlin-100%25-purple)
"Release" (https://img.shields.io/badge/release-v1.2.0-brightgreen)
"License" (https://img.shields.io/badge/license-Proprietary-red)

Features

- 🔓 Root access management — detect and use root access for supported privileged operations.
- 📱 Shizuku integration — access supported privileged operations through Shizuku.
- 🖥️ ADB tools — run supported shell commands and manage device settings.
- 💾 Backup & restore — back up and restore supported apps and data, subject to Android restrictions.
- ✉️ SMS & call-log backup — optional backup functionality using the relevant permissions. SMS restoration depends on Android version and default-SMS-app requirements.
- 🧹 Debloating — disable or remove supported system apps where permissions allow.
- 🔋 Battery Manager — inspect charging status, voltage, current, power, and supported charging controls. Wired and wireless options depend on the device and kernel.
- 🧠 Memory information — view physical and usable RAM, ZRAM, disk swap, and RAM Expansion separately where system information is available.
- ⚙️ Device management — inspect system information and manage supported device-level settings.

Requirements

- Android 12 (API 31) or higher, subject to the actual minimum SDK of the installed build.
- Root access or Shizuku for features that require privileged operations.
- USB debugging for applicable ADB features.
- Supported hardware and kernel interfaces for charging controls.

Feature availability may vary depending on the device, Android version, permissions, root implementation, and kernel.

Download

Get RootRealm from the official GitHub repository.

- Latest release: https://github.com/Omar9t5/rootrealm/releases/latest
- All releases: https://github.com/Omar9t5/rootrealm/releases
- Source repository: https://github.com/Omar9t5/rootrealm

GitHub is the official source for RootRealm release downloads, release notes, and updates.

Official Downloads & APK Authenticity

RootRealm is developed and maintained by FaroqueTech.

The official GitHub repository is the primary source for authentic RootRealm releases. APKs distributed through external websites, file-sharing services, or third-party repositories are not verified or controlled by FaroqueTech unless explicitly confirmed by the developer.

A third-party APK may be an unchanged copy, an outdated version, or a modified build. The hosting location alone does not establish whether an APK is authentic or safe.

Verify an APK

Before installing RootRealm from a third-party source:

1. Compare the APK's SHA-256 checksum with the checksum published for the corresponding official release, when available.
2. Verify the APK signing certificate against the official release's signing-certificate fingerprint.
3. Compare the package name, version name, and version code with the official release information.
4. Prefer downloading updates directly from the official GitHub releases page.

A matching SHA-256 checksum confirms that the file is identical to the trusted reference file. A matching signing certificate helps establish that the APK was signed with the same key. Neither check alone guarantees that software is free of vulnerabilities.

Important: The RootRealm name, logo, screenshots, or package name alone do not prove that an APK is an authentic official release.

Reporting Suspicious Copies

If you find a suspicious APK claiming to be an official RootRealm release, report it through:

https://github.com/Omar9t5/rootrealm/issues

Include the relevant download URL and version information when possible. Do not post private information or sensitive device data.

Build from Source

The source code is publicly viewable for reference and transparency. Public access does not grant permission to reuse, modify, redistribute, or incorporate the code into another project.

To clone the repository:

git clone https://github.com/Omar9t5/rootrealm.git
cd rootrealm
./gradlew assembleDebug

Building may require a compatible JDK, Android SDK, build tools, Gradle configuration, and project-specific dependencies.

A locally built debug APK may differ from the official release APK in signing certificate, build configuration, or other metadata.

Permissions & Privacy

RootRealm includes optional SMS and call-log backup functionality. The relevant permissions are intended for those features when the user chooses to use them.

- SMS permissions: Support the applicable SMS backup functionality.
- Call-log permissions: Support backing up call history.
- Battery and memory information: SMS and call-log permissions are not inherently required just to view these details.
- SMS restoration: Subject to Android version-specific restrictions and, where applicable, default-SMS-app requirements.

Grant only the permissions required for the features you intend to use. Review permission prompts carefully.

Root access, ADB commands, app removal, and system-level changes can affect device operation or cause data loss. Back up important data before performing potentially destructive operations.

Feature behavior may vary depending on the device, Android version, root method, Shizuku configuration, and kernel support.

Developer

FaroqueTech
Independent Android app developer and YouTuber.

- YouTube: https://youtube.com/@faroquetech
- GitHub: https://github.com/Omar9t5/rootrealm
- Official releases: https://github.com/Omar9t5/rootrealm/releases

Proprietary License

Copyright © 2026 FaroqueTech. All rights reserved.

This repository is publicly accessible for viewing and reference purposes only. No permission is granted to copy, modify, redistribute, sublicense, or incorporate this source code, in whole or in part, into another project without prior written permission from the copyright holder, except where applicable law provides otherwise.

Public visibility does not grant permission to reuse the code. This notice communicates the intended restrictions but does not technically prevent people from downloading or copying publicly accessible files.

All rights to the source code remain reserved by the copyright holder unless explicitly licensed or authorized in writing.

Support & Contributions

Report bugs and request features through "GitHub Issues" (https://github.com/Omar9t5/rootrealm/issues).

When reporting an issue, include the RootRealm version, Android version, device model, and relevant error details where possible.

Do not include passwords, authentication tokens, private SMS contents, call history, personal documents, or other sensitive information in public reports.

Thank you for supporting RootRealm and FaroqueTech.
