# Printwright releases

Installers for Printwright, a desktop 3D-printing workbench. This repository holds only releases; the source isn't here.

Download the newest from the [latest release](../../releases/latest). Check a download against the release's `SHA256SUMS.txt`.

## Which file do I need?

| System                     | Download                                         |
| -------------------------- | ------------------------------------------------ |
| Mac with Apple silicon (M1 and later) | `Printwright-<version>-mac-arm64.dmg` |
| Mac with an Intel processor | `Printwright-<version>-mac-x64.dmg`             |
| Windows 10 or 11           | `Printwright-<version>-win-x64.exe`              |
| Linux (x86-64)             | `Printwright-<version>-linux-x86_64.AppImage`    |

The `.zip` files, `latest.json` and `latest.json.sig` are for the built-in updater; you don't need them. The updater only installs releases signed with Printwright's key.

## Installing

- **macOS:** open the DMG and drag Printwright to Applications. If macOS says it cannot verify the app, open System Settings, then Privacy & Security, and click **Open Anyway**.
- **Windows:** run the installer. If SmartScreen appears, choose **More info**, then **Run anyway**.
- **Linux:** `chmod +x Printwright-*.AppImage`, then run it.

## Updates

Printwright updates itself from this repository's releases. It downloads new versions in the background and asks before restarting. You can turn this off in Settings, then Updates.

Report bugs at [printwright-issues](https://github.com/DarrellBest-Org/printwright-issues/issues), or from inside the app.
