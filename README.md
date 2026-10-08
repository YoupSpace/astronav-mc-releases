# AstroNav Mission Control

**English** · [Nederlands](README.nl.md)

AstroNav Mission Control (AstroNav MC) is the official Windows desktop application for the **AstroNav Nano** flight controller by [YoupSpace](https://youpspace.com). Use it to configure your Nano, import its flight logs, and replay your missions, all offline.

**[Download the latest version](https://github.com/YoupSpace/astronav-mc-releases/releases/latest)**

## About YoupSpace

[YoupSpace](https://youpspace.com) is Youp's space for projects, products, and more. YoupSpace builds and sells hardware kits, such as the AstroNav flight controller kit, and shares the build process online. The motto: *anything is possible, you decide your limits.*

AstroNav started as a model rocketry project to build a rocket that flies 200+ meters. It grew into the **AstroNav Nano**: a compact flight controller and flight-data logger for model rockets and similar vehicles. The Nano measures motion and environment, detects flight phases, logs the mission, and can trigger apogee deployment when enabled and configured.

Visit [youpspace.com](https://youpspace.com) for the shop, other projects, videos, and the AstroNav Nano tester program.

## What AstroNav MC does

AstroNav MC works with an AstroNav Nano in USB storage mode. It is a file-based tool. It does not provide live telemetry and does not send serial commands.

- **Discover** an AstroNav Nano connected over USB, also when more than one is connected.
- **Inspect** identity, health, runtime state, and recorded-flight summaries.
- **Configure** flight-estimation and launch-detection settings with validation, a local recovery copy, and read-back verification.
- **Import** flight logs into a local archive that stays available without a device.
- **Replay** missions with synchronized charts for altitude, velocity, acceleration, roll/pitch, temperature, and pressure, plus an indicative attitude view.
- **Overlay** telemetry on your launch video and export it as an MP4.
- **Export** archived flights as CSV files.

## Install

1. Open the [latest release](https://github.com/YoupSpace/astronav-mc-releases/releases/latest).
2. Download the Windows installer (`*-setup.exe`).
3. Run the installer. No administrator rights are needed.

Requirements: Windows 10 or 11 (64-bit) with Microsoft Edge WebView2. WebView2 is included in current Windows versions.

## Updates

AstroNav MC checks this repository for new versions and shows a banner when an update is available. Updates are signed and verified before installation. You can turn off update checks under **Settings → Updates**. The update check is the only network request the app makes. Your flights and settings stay on your computer.

## Documentation

- [YoupSpace Wiki](https://wiki.youpspace.com/): AstroNav Nano hardware, safety, getting started, configuration, flight states, pre-flight checks, flight logs, and troubleshooting.
- [AstroNav MC software manual](https://wiki.youpspace.com/software/astronav-mc/): the complete guide to this application.

> **Safety:** the AstroNav Nano can control ignition and deployment hardware. Read the [safety documentation](https://wiki.youpspace.com/) before you connect a battery, E-match, or other pyro hardware. Keep **Fire apogee pyro** disabled unless your recovery system is connected and configured for that output.

## Support

Read the [troubleshooting guide](https://wiki.youpspace.com/) first. For other questions, contact YoupSpace through [youpspace.com](https://youpspace.com).

## License

AstroNav Mission Control is free to use, but it is **closed-source, proprietary software**. You may not redistribute, modify, or reverse engineer it. Share the link to this page instead of the installer. See [LICENSE](LICENSE) ([Nederlands](LICENSE.nl)).

Copyright © 2026 [YoupSpace](https://youpspace.com). All rights reserved.
