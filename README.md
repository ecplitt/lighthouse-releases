# Lighthouse releases

Signed release packages of Lighthouse. This repository holds releases only; there is no source code here.

Download from [Releases](https://github.com/ecplitt/lighthouse-releases/releases):

| File | For |
| --- | --- |
| `infserver_<version>_amd64.deb`, `_arm64.deb` | Linux servers (Debian 13, Ubuntu 24.04, Raspberry Pi OS 64-bit) |
| `infserver-guest_<version>_<arch>.deb` | Linux desktop: server and desktop app in one |
| `lighthouse-server-<version>-macos-universal.pkg` | macOS 13 or newer, Apple silicon and Intel |
| `infserver-<version>-windows-x64.zip` | Windows 10 and 11 |
| `latest.json`, `latest.json.sig` | The signed release list Lighthouse reads when you click Update |

Lighthouse checks the signature on `latest.json` with a key built into every copy, and every package against the
checksum in that list, so a copied or altered file is refused wherever it was downloaded from.

Installing and getting started: the tester guide you received with your invitation.
Questions: lighthousefleetservices@gmail.com
