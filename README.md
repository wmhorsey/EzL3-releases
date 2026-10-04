# EzL3 releases

This repository only hosts **EzL3 / NS-Display Windows installers** (see [Releases](https://github.com/wmhorsey/EzL3-releases/releases)).
It contains no source code; releases are published automatically by the build.

- `EzL3-Setup-x.y.z.exe`: per-user installer (no admin needed). Installs the app, a tray icon (Start / Stop / Open controller / Open OBS URL / Quit) and shortcuts.
- `EzL3-app-x.y.z.zip`: the same app files, used by the updater.
- `SHA256SUMS.txt`: checksums of both files.

Your settings, images and decks live in `%LOCALAPPDATA%\EzL3\data` and are kept when you update or uninstall.
