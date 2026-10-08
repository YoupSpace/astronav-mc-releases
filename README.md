<div align="center">

<img src="logo.svg" width="96" alt="AstroNav Mission Control logo">

# AstroNav Mission Control

Configure, import, and replay your AstroNav Nano flights.

<img src="flags/gb.svg" height="11" alt=""> <b>English</b> &nbsp;|&nbsp; <img src="flags/nl.svg" height="11" alt=""> <a href="README.nl.md">Nederlands</a>

<br>

<a href="https://github.com/YoupSpace/astronav-mc-releases/releases/latest"><img src="download.svg" height="60" alt="Download for Windows"></a>

<a href="https://github.com/YoupSpace/astronav-mc-releases/releases/latest"><img src="https://img.shields.io/github/v/release/YoupSpace/astronav-mc-releases?style=flat&labelColor=071018&color=1b8f83&logo=github&label=Release" alt="Release"></a>
<a href="https://github.com/YoupSpace/astronav-mc-releases/releases"><img src="https://img.shields.io/github/downloads/YoupSpace/astronav-mc-releases/total?style=flat&labelColor=071018&color=1b8f83&label=Downloads" alt="Downloads"></a>
<img src="https://img.shields.io/badge/Windows-10%20%7C%2011-1b8f83?style=flat&labelColor=071018" alt="Windows 10 and 11">

</div>

<p align="center">
  <img src="screenshots/overview.png" alt="Vehicle overview in AstroNav Mission Control">
</p>

AstroNav Mission Control (AstroNav MC) is the official Windows desktop application for the **AstroNav Nano** flight controller by [YoupSpace](https://youpspace.com). Use it to configure your Nano, import its flight logs, and replay your missions, all offline.

## Features

<table>
  <tr>
    <td width="50%" valign="top"><h3>🔌 Automatic detection</h3>Finds your AstroNav Nano over USB, also when more than one is connected, and shows its identity, health, and last flight.</td>
    <td width="50%" valign="top"><h3>⚙️ Safe configuration</h3>Edit flight-estimation and launch-detection settings with validation, a local recovery copy, and read-back verification.</td>
  </tr>
  <tr>
    <td width="50%" valign="top"><h3>📈 Mission replay</h3>Replay flights with synchronized charts for altitude, velocity, acceleration, roll/pitch, temperature, and pressure, plus an attitude view.</td>
    <td width="50%" valign="top"><h3>🎬 Video overlay</h3>Put your telemetry on top of your launch video and export it as an MP4.</td>
  </tr>
  <tr>
    <td width="50%" valign="top"><h3>🗂️ Offline archive</h3>Import flight logs into a local library that stays available without a device, and export them as CSV.</td>
    <td width="50%" valign="top"><h3>🔒 Private by design</h3>Everything stays on your computer. The only network request is the optional update check.</td>
  </tr>
</table>

AstroNav MC works with an AstroNav Nano in USB storage mode. It is a file-based tool. It does not provide live telemetry and does not send serial commands.

## Quick start

1. **Install.** Download the installer (`*-setup.exe`) from the [latest release](https://github.com/YoupSpace/astronav-mc-releases/releases/latest) and run it. No administrator rights are needed.
2. **Connect.** Power your AstroNav Nano over USB and put it in USB storage mode. AstroNav MC finds it automatically.
3. **Fly and replay.** Configure your Nano under **Settings**, then open or import your flight logs under **Flights** to replay the mission.

The [AstroNav MC software manual](https://wiki.youpspace.com/software/astronav-mc/) explains every screen in detail.

> [!WARNING]
> The AstroNav Nano can control ignition and deployment hardware. Read the [safety documentation](https://wiki.youpspace.com/) before you connect a battery, E-match, or other pyro hardware. Keep **Fire apogee pyro** disabled unless your recovery system is connected and configured for that output.

## About YoupSpace

[YoupSpace](https://youpspace.com) is Youp's space for projects, products, and more. YoupSpace builds and sells hardware kits, such as the AstroNav flight controller kit, and shares the build process online. The motto: *anything is possible, you decide your limits.*

AstroNav started as a model rocketry project to build a rocket that flies 200+ meters. It grew into the **[AstroNav Nano](https://youpspace.com/astronav-nano/)**: a compact flight controller and flight-data logger for model rockets and similar vehicles. The Nano measures motion and environment, detects flight phases, logs the mission, and can trigger apogee deployment when enabled and configured.

## More information

<details>
<summary><b>System requirements</b></summary>

- Windows 10 or 11 (64-bit)
- Microsoft Edge WebView2 (included in current Windows versions)
- An AstroNav Nano with a USB cable, to configure the device or read new logs. Imported flights work without a device.

</details>

<details>
<summary><b>Updates</b></summary>

AstroNav MC checks this repository for new versions and shows a banner when an update is available. Updates are signed and verified before installation. You can turn off automatic update checks under **Settings → Application**.

</details>

<details>
<summary><b>Privacy</b></summary>

AstroNav MC makes no network requests except the optional update check against this repository. Your flight logs, settings, and recovery copies are stored only on your computer.

</details>

<details>
<summary><b>FAQ</b></summary>

**My Nano is not detected.**
Make sure the Nano is in USB storage mode and that Windows has mounted it. Check the [troubleshooting guide](https://wiki.youpspace.com/) for more steps.

**Can I use AstroNav MC without a Nano?**
Yes. Flights that you imported before stay available in the local library.

**Does AstroNav MC show live telemetry?**
No. AstroNav MC works with the files that the Nano stores in USB storage mode.

**Can I share the installer with a friend?**
Share the link to this page instead. The license does not allow redistribution of the installer.

</details>

## Support

Read the [troubleshooting guide](https://wiki.youpspace.com/) first. For other questions, email [youpspace@outlook.com](mailto:youpspace@outlook.com) or use the [support page](https://youpspace.com/support/).

## License

AstroNav Mission Control is free to use, but it is **closed-source, proprietary software**. You may not redistribute, modify, or reverse engineer it. See [LICENSE](LICENSE) ([Nederlands](LICENSE.nl)).

<br>

<div align="center">

[Website](https://youpspace.com) · [Wiki](https://wiki.youpspace.com/) · [Manual](https://wiki.youpspace.com/software/astronav-mc/) · [AstroNav Nano](https://youpspace.com/astronav-nano/) · [Shop](https://youpspace.com/shop/) · [Contact](https://youpspace.com/contact/)

Copyright © 2026 [YoupSpace](https://youpspace.com). All rights reserved.

</div>
