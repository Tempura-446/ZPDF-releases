# ZPDF Releases

Official desktop builds and installers for **ZPDF** — a **100% offline, zero-telemetry PDF studio** for **Windows**, **macOS**, and **Linux**. Read, edit, permanently redact, OCR, translate books & manga, run press-room CMYK preflight, measure CAD blueprints, and chat with PDFs using your own local AI — with no cloud uploads and no subscriptions.

## Latest Release Downloads

Download the latest version from the [**Latest Release**](https://github.com/Tempura-446/ZPDF-releases/releases/latest) page (currently **`v0.80.1`**):

| Platform | Recommended Download | Alternative / Portable | Install Notes |
| --- | --- | --- | --- |
| **Windows (x64)** | [`ZPDF-0.80.1-windows-standalone.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.80.1/ZPDF-0.80.1-windows-standalone.zip) (no Python needed) | [`ZPDF-0.80.1-windows.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.80.1/ZPDF-0.80.1-windows.zip) (source installer) | Unzip and run `ZPDF.exe` (or `Install ZPDF.cmd` for the source installer). |
| **macOS (Apple Silicon / Intel)** | [`ZPDF-0.80.1-macos.dmg`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.80.1/ZPDF-0.80.1-macos.dmg) | [`ZPDF-0.80.1-macos.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.80.1/ZPDF-0.80.1-macos.zip) | Open `.dmg`, drag **ZPDF.app** to Applications. Since the app is unsigned, if Gatekeeper warns on first launch, run:<br>`xattr -cr /Applications/ZPDF.app` |
| **Linux (x86_64)** | [`zpdf_0.80.1_amd64.deb`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.80.1/zpdf_0.80.1_amd64.deb) (Debian / Ubuntu) | [`ZPDF-0.80.1-linux.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.80.1/ZPDF-0.80.1-linux.zip) (portable archive) | Debian/Ubuntu: `sudo apt install ./zpdf_0.80.1_amd64.deb`<br>Portable: unzip and run `./ZPDF`. |
| **Android (Companion App)** | [`ZPDF-0.80.1-android.apk`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.80.1/ZPDF-0.80.1-android.apk) (direct APK) | — | Install the APK on your Android phone/tablet and connect to ZPDF on your local Wi-Fi (`zpdf --lan`). |

Every download includes a matching `.sha256` checksum file on the release page.

## Why ZPDF?

- **100% Local & Private:** Zero telemetry, no accounts, no cloud uploads. Includes **true permanent redaction** (content-stream removal + post-write verification), AES-256 & certificate encryption, Digital ID signing (`pyHanko`), and tamper-evident audit logs.
- **Fast Power-User Reader & Editor:** Streams 200 MB+ files smoothly, with 4 reading themes (Light, Smart Night, Warm Sepia, E-Ink), split view + interactive diff viewer, Workspace Sessions, direct text editing with paragraph reflow, interactive forms with calculations, and annotations.
- **Offline Book, Document & Manga Translation:** Powered by commercial-safe Apache-2.0 MADLAD-400, OPUS-MT, or your local LLM — featuring vertical CJK (*tategaki*) with furigana stripping, shape-aware **Manga / Comic Speech-Bubble Mode v2**, `bilingual-pages` book mode, and a live bilingual reading pane.
- **Local AI Document Assistant:** *Ask this PDF* with clickable `[p. N]` citations, Document/Chapter Summarizer, and structured JSON/CSV extraction using your own Ollama, LM Studio, or OpenAI-compatible endpoint.
- **Press-Room CMYK Preflight (No Ghostscript):** PDF/X-1a & PDF/X-4 audits, recursive Form XObject inspection, true C/M/Y/K plate separation, TAC heatmap, live ink-density eyedropper, and one-click pure-Python press fixes.
- **CAD, Blueprints & Publishing Studio:** Native PDF ↔ DXF, calibrated blueprint takeoff with vector snapping & Excel quantity schedules, CAD layers, sheet-set tools, `.cbz` ↔ PDF, LTR/RTL multi-signature booklet imposition, and a POD spine calculator.
- **Built-in OCR & Full Automation:** Shipped PP-OCR/ONNX engine + in-place **Check OCR** typo editor, PDF/A & PDF/UA accessibility tools, Word/Excel/PowerPoint/HTML/Markdown conversions, multi-step Recipes, Watch Folders, Smart Auto-Filing, and Local Semantic Folder Search.

## Updating

Already have ZPDF installed? Open **Settings → Updates** (or click the **Update** button in the app) to update automatically on Windows, macOS, or Linux (verified against each release's SHA-256 checksum).