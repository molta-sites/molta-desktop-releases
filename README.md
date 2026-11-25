# Molta desktop downloads

[Molta](https://molta.ch) is your AI team for work and life: helpers that handle email, files, research, finances and websites for you. This repository only hosts the installers of the Molta desktop apps. It contains no source code.

The apps open your Molta office (https://app.molta.ch) in their own window, with a tray icon, a single instance and `molta://` links.

## Downloads

See the [Releases](../../releases) page.

- Linux: `.deb` (Debian, Ubuntu) and `.AppImage` (any distribution), x86_64.
- Windows: `.exe` installer, 64-bit. It is not code-signed yet, so Windows SmartScreen shows a warning on the first launch.

## Check your download

Every release has a `SHA256SUMS` file. Download it next to the installer and compare.

Linux and macOS:

```
sha256sum -c SHA256SUMS --ignore-missing
```

Windows (PowerShell):

```
Get-FileHash .\Molta_0.2.0_x64-setup.exe -Algorithm SHA256
```

The printed hash must match the line for that file in `SHA256SUMS`.

## Questions

https://molta.ch/support
