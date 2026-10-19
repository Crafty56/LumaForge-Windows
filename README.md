# LumaForge Hub for Windows

Published by **CADET**. Community: https://discord.gg/RK5dyBArdg

[Download the counted Release installer](https://github.com/Crafty56/LumaForge-Windows/releases/download/v0.10.0-preview.1/LumaForge-Hub-Setup-0.10.0-preview.1.exe)

[Direct file fallback](LumaForge-Hub-Setup-0.10.0-preview.1.exe) · [Release history](https://github.com/Crafty56/LumaForge-Windows/releases)

Windows 10/11 x64 and Microsoft WebView2. Unsigned preview installer.

The release workflow verifies the committed installer's SHA-256, creates a preview
Release and uploads the same bytes. Existing counted assets are never overwritten.
The workflow runs on relevant pushes or manually from Actions. New installer builds
should use a new version/tag to retain old counters and release history.

To enable the download website, open Settings → Pages → Deploy from a branch →
main → /(root), then save. Its URL is https://crafty56.github.io/LumaForge-Windows/ .

The page's primary link uses GitHub Releases, whose public API exposes asset
download_count. A direct-file fallback remains available while publishing is pending.
Counts include repeat requests and do not identify unique people or installs.
Previous raw-file downloads and clicks from a particular referring page cannot
be reconstructed. The optional LumaForge Discord stats app reads both public
platform repositories' Release counters.
