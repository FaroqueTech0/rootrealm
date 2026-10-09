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
- ✉️ SMS & call-log backup — optional backup functionality using the relevant permissions. SMS restoration depends on the Android version and default-SMS-app requirements.
- 🧹 Debloating — disable or remove supported system apps where permissions allow.
- 🔋 Battery Manager — inspect charging status, voltage, current, power, and supported charging controls. Wired and wireless options depend on the device and kernel.
- 🧠 Memory information — view physical and usable RAM, ZRAM, disk swap, and RAM Expansion separately where system information is available.
- ⚙️ Device management — inspect system information and manage supported device-level settings.

Requirements

- Android 12 (API 31) or higher, subject to the actual minimum SDK of the installed build.
- Root access or Shizuku for features that require privileged operations.
- USB debugging for applicable ADB features.
- Supported hardware and kernel interfaces for charging controls.

Some features may be unavailable depending on the device, Android version, kernel, permissions, and access method.

Download

Official downloads are published through the RootRealm GitHub repository.

- Latest release: https://github.com/Omar9t5/rootrealm/releases/latest
- All releases: https://github.com/Omar9t5/rootrealm/releases
- Source repository: https://github.com/Omar9t5/rootrealm

For the safest installation experience, obtain RootRealm from the official releases page.

Official Downloads & APK Authenticity

RootRealm is developed and maintained by FaroqueTech. The official GitHub repository is the primary source for release announcements, APK downloads, release notes, and project information.

Third-party downloads

RootRealm APKs hosted on external websites, file-sharing services, or third-party repositories are not verified or controlled by FaroqueTech unless explicitly confirmed by the developer.

A third-party APK may be an unchanged copy of an official release, an outdated build, or a modified version. The hosting location alone does not establish whether a file is authentic or safe.

FaroqueTech cannot guarantee the integrity, authenticity, or safety of independently distributed or modified copies that have not been verified against an official release.

How to verify an APK

Before installing a RootRealm APK obtained from a third-party source:

1. Compare its SHA-256 checksum with the checksum published for the corresponding official release, when available.
2. Verify its signing certificate against the official release's signing-certificate fingerprint.
3. Check the package name, version name, and version code against the official release information.
4. Download future updates from the official GitHub repository whenever possible.

A matching SHA-256 checksum confirms that the files are identical to the trusted reference file. A matching signing certificate helps establish that the APK was signed with the same signing key. Neither check, by itself, guarantees that the software is free from vulnerabilities.

Important: Do not assume that an APK is official simply because it uses the RootRealm name, logo, package name, or screenshots.

Reporting suspicious copies

If you find an APK that appears to have been modified or distributed deceptively under the RootRealm name, please report it through:

https://github.com/Omar9t5/rootrealm/issues

Include the relevant download URL, version information, and available verification details. Do not upload private information or sensitive device data.

Build from Source

The source code is publicly viewable for reference and transparency. Public repository access does not grant permission to reuse, modify, redistribute, or incorporate the code into another project.

If you want to inspect the repository, you can clone it using Git:

git clone https://github.com/Omar9t5/rootrealm.git
cd rootrealm
./gradlew assembleDebug

Building successfully may require a compatible JDK, Android SDK, Android build tools, Gradle configuration, and any project-specific dependencies.

The resulting debug APK may differ from the official release APK in signing certificate, build configuration, or other build metadata.

Permissions & Privacy

RootRealm includes optional SMS and call-log backup functionality. The relevant permissions are intended for those features when the user chooses to use them.

- SMS permissions support the applicable SMS backup functionality.
- Call-log permissions support backing up call history.
- These permissions are not inherently required just to view battery or memory information.
- SMS restoration is subject to Android version-specific restrictions and, where applicable, default-SMS-app requirements.

Grant only the permissions required for the features you intend to use. Review Android permission prompts carefully.

Root access, ADB commands, app removal, and system-level settings can affect device operation or cause data loss. Back up important data before performing potentially destructive operations.

Feature availability and behavior may vary by device, Android version, root implementation, Shizuku configuration, and kernel support.

Developer

FaroqueTech
Independent Android app developer and YouTuber.

- YouTube: https://youtube.com/@faroquetech
- GitHub: https://github.com/Omar9t5/rootrealm
- Official releases: https://github.com/Omar9t5/rootrealm/releases

Proprietary License

Copyright © 2026 FaroqueTech. All rights reserved.

This repository is publicly accessible for viewing and reference purposes only. No license or permission is granted to copy, modify, redistribute, sublicense, or incorporate this source code, in whole or in part, into another project without prior written permission from the copyright holder, except where applicable law provides otherwise.

Public visibility does not grant permission to reuse the code. This notice states the intended restrictions on use; it does not technically prevent people from downloading or copying publicly accessible files.

Unless explicitly authorized in writing, all rights to the source code remain reserved by the copyright holder.

Support & Contributions

Bug reports and feature requests can be submitted through "GitHub Issues" (https://github.com/Omar9t5/rootrealm/issues).

When reporting an issue, include the RootRealm version, Android version, device model, and relevant error details where possible.

Do not include passwords, authentication tokens, private SMS contents, call history, personal documents, or other sensitive information in public reports.

Thank you for supporting RootRealm and FaroqueTech.
