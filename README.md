# XYZRemote Downloads

Official binary distribution for the macOS host-capable edition of XYZRemote. This repository contains release information and installers; the private application source is maintained separately.

## Current availability

A newly signed and notarized Host installer is being prepared. No new verified Host installer is published here yet. A release asset will be linked here after Apple notarization, ticket stapling, signature checks and an anonymous download check have completed.

The Mac App Store edition is a controller only. The separately distributed Host edition lets a Mac share its screen and receive input from an authorized controller.

## Installation and two-Mac setup

1. Use the Mac App Store controller on one Mac, and the host-capable edition on a second Mac. Keep both Macs on the same trusted local network for automatic discovery.
2. Once a verified installer is available, download its release asset and compare its SHA-256 with the release checksums. Open the installer and copy XYZRemote to Applications on the host Mac.
3. On the host Mac, open XYZRemote and grant the requested Screen Recording and Accessibility permissions in System Settings. These permissions belong to the separately distributed Host edition.
4. Start sharing on the host. On the controller Mac, find the nearby host and request a connection; approve that request on the host Mac. This flow does not require a cloud account or a preset password.
5. Test pointer movement, clicks, scrolling, keyboard tools and display switching. Press Esc to release the controller's pointer capture. Transfer an ordinary file and request it back using the remote file panel.
6. Disconnect or stop sharing on the host when finished.

The Host and store editions use the same app identity, so use separate Macs for this review setup rather than replacing one edition with the other on the same Mac.

## Access and file boundaries

Connect only to devices you own or are authorized to manage. Keep the host app running for the session. Automatic discovery is LAN-based; a public cloud relay or account service is not included. Clipboard sync is optional. Remote file access is limited to the app's shared transfer directory; do not place unrelated private files there. The controller receives files in a temporary cache, which can be revealed in Finder or dragged to Finder.

Do not disable Gatekeeper or remove quarantine to install a release from this repository. Report a signing or notarization problem through the support page.

Support: https://xyztech.com.cn/xyzremote-support/
Privacy: https://xyztech.com.cn/xyzremote-privacy-policy/
