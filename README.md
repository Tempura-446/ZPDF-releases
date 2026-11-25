# ZPDF Releases

Official desktop builds and installers for **ZPDF** — offline PDF reader, editor, redactor, OCR, and translator for **Windows**, **macOS**, and **Linux**.

## Latest Release Downloads

Download the latest version from the [**Latest Release**](https://github.com/Tempura-446/ZPDF-releases/releases/latest) page (currently **`v0.71.0`**):

| Platform | Recommended Download | Alternative / Portable | Install Notes |
| --- | --- | --- | --- |
| **Windows (x64)** | [`ZPDF-0.71.0-windows-standalone.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.71.0/ZPDF-0.71.0-windows-standalone.zip) (no Python needed) | [`ZPDF-0.71.0-windows.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.71.0/ZPDF-0.71.0-windows.zip) (source installer) | Unzip and run `ZPDF.exe` (or `Install ZPDF.cmd` for the source installer). |
| **macOS (Apple Silicon / Intel)** | [`ZPDF-0.71.0-macos.dmg`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.71.0/ZPDF-0.71.0-macos.dmg) | [`ZPDF-0.71.0-macos.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.71.0/ZPDF-0.71.0-macos.zip) | Open `.dmg`, drag **ZPDF.app** to Applications. Since the app is unsigned, if Gatekeeper warns on first launch, run:<br>`xattr -cr /Applications/ZPDF.app` |
| **Linux (x86_64)** | [`zpdf_0.71.0_amd64.deb`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.71.0/zpdf_0.71.0_amd64.deb) (Debian / Ubuntu) | [`ZPDF-0.71.0-linux.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.71.0/ZPDF-0.71.0-linux.zip) (portable archive) | Debian/Ubuntu: `sudo apt install ./zpdf_0.71.0_amd64.deb`<br>Portable: unzip and run `./ZPDF`. |

Every download includes a matching `.sha256` checksum file on the release page.

## Updating

Already have ZPDF installed? Open **Settings → Updates** (or click the **Update** button in the app) to update automatically on Windows, macOS, or Linux.