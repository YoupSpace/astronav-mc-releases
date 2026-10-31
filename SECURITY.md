# Security policy

## Supported versions

Only the latest release of AstroNav Mission Control receives security fixes. Installed copies
update themselves, unless automatic update checks were turned off under
**Settings → Application** or the app was installed from the `.deb` or `.rpm` package.

| Version | Supported |
| --- | --- |
| Latest release | Yes |
| Older releases | No, please update |
| Pre-releases (`-beta`, `-rc`) | No |

## Reporting a vulnerability

Please do not report security problems in a public issue.

Email [youpspace@outlook.com](mailto:youpspace@outlook.com?subject=AstroNav%20MC%20security%20report)
with "AstroNav MC security report" in the subject, and include:

- the AstroNav MC version (shown in the **About** window) and your operating system;
- what an attacker can do, and what they need first (a crafted flight log, a crafted
  `Settings.ini` on a USB drive, a position on the network, local access);
- the steps or files needed to reproduce it.

You will get a reply within 7 days. Once the problem is confirmed, we aim to ship a fix within
30 days and will tell you when it is released. We are glad to credit you in the release notes,
if you want to be named.

## Scope

In scope:

- the AstroNav Mission Control app on Windows and Linux;
- how it reads files from a connected drive (`Settings.ini`, flight logs);
- the app's update, firmware download and firmware installation process.

Out of scope:

- the AstroNav Nano firmware itself (report those the same way, with "AstroNav Nano" in the
  subject);
- problems that require an attacker who already controls your user account;
- SmartScreen or antivirus warnings about the unsigned Windows installer.

## How the app protects you

- Updates are signed. The app verifies the signature before installing and refuses an update
  that does not match.
- Firmware is downloaded only after you confirm, and its SHA-256 checksum is verified before the
  Nano is touched.
- Files on the Nano are only read and written beneath the drive that was identified as a Nano.
  Nothing on the device is ever run.
- The app contacts only GitHub: for the update check, which you can turn off, and for the
  firmware check while a Nano is connected. It sends nothing else over the network.
