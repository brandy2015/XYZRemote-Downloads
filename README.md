# XYZRemote Downloads

Official download information for the macOS host-capable edition of XYZRemote. Installers are hosted on the official XYZTech website. This repository contains download information only; the private application source is maintained separately.

## Current availability

**XYZRemote Host 1.0.2 (Build 1.0.13)** is available from the official website for Apple silicon Macs running macOS 15 or later.

- [Download the signed and notarized Host ZIP](https://www.xyztech.com.cn/downloads/xyzremote/1.0.13/XYZRemote-MacHost-1.0.2-1.0.13-arm64.zip)
- [Installation instructions](https://www.xyztech.com.cn/downloads/xyzremote/1.0.13/INSTALL.txt)
- [SHA-256 checksums](https://www.xyztech.com.cn/downloads/xyzremote/1.0.13/SHA256SUMS.txt)
- [Public verification summary](https://www.xyztech.com.cn/downloads/xyzremote/1.0.13/release.json)
- [Official support page with English and Chinese instructions](https://www.xyztech.com.cn/xyzremote-support/)

ZIP SHA-256: `b8bb2dd989dfb327e0d229efffc0aabe060457d507d64b5b93b5c68a8b185a29` (52,185,774 bytes).

Developer ID signatures, the stapled Apple notarization ticket, Gatekeeper acceptance, and the app re-extracted from the final ZIP have been checked. All four website files were downloaded without authentication and matched their local byte counts and SHA-256 values. These checks do not establish a completed two-Mac remote-control session.

The Mac App Store edition is a controller only. The separately distributed Host edition lets a Mac share its screen and receive input from an authorized controller.

## Installation and two-Mac setup

1. Use the Mac App Store controller on one Mac, and the host-capable edition on a second Mac. Keep both Macs on the same trusted local network for automatic discovery.
2. Download the official Host ZIP above and compare its SHA-256 with the checksums. Unzip it and copy XYZRemote.app to Applications on the host Mac.
3. On the host Mac, open XYZRemote and select “Share this Mac.” Grant its Screen Recording and Accessibility permissions, then choose “Set up and start automatically” (or “Start host” for an existing setup). These permissions belong to the separately distributed Host edition. Allow Local Network access on both Macs if prompted.
4. On the controller Mac, find the nearby host and choose “Request connection,” then “Allow this connection” on the Host. This flow does not require a cloud account or a preset password.
5. Test pointer movement, clicks, scrolling, keyboard tools and display switching. Press Esc to release the controller's pointer capture. Transfer an ordinary file and request it back using the remote file panel.
6. Disconnect or stop sharing on the host when finished.

The Host and store editions use the same app identity, so use separate Macs for this review setup rather than replacing one edition with the other on the same Mac.

## Access and file boundaries

Connect only to devices you own or are authorized to manage. Keep the host app running for the session. Automatic discovery is LAN-based; a public cloud relay or account service is not included. Clipboard sync is optional. Remote file access is limited to the app's shared transfer directory; do not place unrelated private files there. The controller receives files in a temporary cache, which can be revealed in Finder or dragged to Finder.

Do not disable Gatekeeper or remove quarantine to install the official Host download. Report a signing or notarization problem through the support page.

Support: https://xyztech.com.cn/xyzremote-support/
Privacy: https://xyztech.com.cn/xyzremote-privacy-policy/
