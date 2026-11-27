# ZPDF Releases

**ZPDF — The 100% Offline Document, Book & Manga Studio** *(PDF · EPUB · CBZ/CBR · CAD · Offline AI)*

Official desktop builds and installers for **Windows**, **macOS**, **Linux**, and the **Android Companion App**. Read, edit, permanently redact, OCR, translate books & manga, browse your local cover-art bookshelf, run press-room CMYK preflight, measure CAD blueprints, and chat with documents using your own local AI — with zero telemetry, zero cloud uploads, and zero subscriptions.

## Latest Release Downloads

Download the latest version from the [**Latest Release**](https://github.com/Tempura-446/ZPDF-releases/releases/latest) page (currently **`v0.84.0`**):

| Platform | Recommended Download | Alternative / Portable | Install Notes |
| --- | --- | --- | --- |
| **Windows (x64)** | [`ZPDF-0.84.0-windows-standalone.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.84.0/ZPDF-0.84.0-windows-standalone.zip) (no Python needed) | [`ZPDF-0.84.0-windows.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.84.0/ZPDF-0.84.0-windows.zip) (source installer) | Unzip and run `ZPDF.exe` (or `Install ZPDF.cmd` for the source installer). |
| **macOS (Apple Silicon / Intel)** | [`ZPDF-0.84.0-macos.dmg`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.84.0/ZPDF-0.84.0-macos.dmg) | [`ZPDF-0.84.0-macos.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.84.0/ZPDF-0.84.0-macos.zip) | Open `.dmg`, drag **ZPDF.app** to Applications. Since the app is unsigned, if Gatekeeper warns on first launch, run:<br>`xattr -cr /Applications/ZPDF.app` |
| **Linux (x86_64)** | [`zpdf_0.84.0_amd64.deb`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.84.0/zpdf_0.84.0_amd64.deb) (Debian / Ubuntu) | [`ZPDF-0.84.0-linux.zip`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.84.0/ZPDF-0.84.0-linux.zip) (portable archive) | Debian/Ubuntu: `sudo apt install ./zpdf_0.84.0_amd64.deb`<br>Portable: unzip and run `./ZPDF`. |
| **Android (Companion App)** | [`ZPDF-0.84.0-android.apk`](https://github.com/Tempura-446/ZPDF-releases/releases/download/v0.84.0/ZPDF-0.84.0-android.apk) (direct APK) | — | Install the APK on your Android phone/tablet and connect to ZPDF on your local Wi-Fi (`zpdf --lan`). |

Every download includes a matching `.sha256` checksum file on the release page.

## Why ZPDF?

- **100% Local & Private:** Zero telemetry, no accounts, no cloud uploads. Includes **true permanent redaction** (content-stream removal + post-write verification), AES-256 & certificate encryption, Digital ID signing (`pyHanko`), and tamper-evident audit logs.
- **Universal Document, E-Book & Manga Reader:** Open **PDF**, **`.epub`** (with clickable chapter bookmarks), **`.cbz` / `.cbr`** comic archives, **`.dxf` / `.dwg`** drawings, and image folders directly. Features a **Visual Cover-Art Bookshelf**, **`[` / `]` chapter navigation**, **True RTL Manga Spreads** with cover-page offset, 4 reading themes (Light, Smart Night, Warm Sepia, E-Ink), split view + diff viewer, Workspace Sessions, direct text editing, fillable forms, and annotations.
- **Offline Manga & Book Translation Studio:** Powered by commercial-safe Apache-2.0 MADLAD-400, OPUS-MT, or your local LLM — featuring the optional pure-ONNX **Manga AI Pack** (RT-DETR v2 neural bubble/borderless detector, Japanese `manga-ocr`, LaMa-Manga neural inpainting), **Live Manga Lens (`Shift+T`)** with hold-`Space` peek and an **Interactive Bubble Editor**, scanlation-grade stroked SFX, vertical CJK (*tategaki*) with furigana stripping, and live bilingual reading.
- **Built-in PP-OCRv6 & Vision-LLM OCR:** Shipped **PP-OCRv6 Medium** ONNX engine (50 languages, ~5× faster on CPU), in-place **Check OCR** typo editor, **Settings → Offline AI Models Manager**, plus optional **Vision-LLM OCR & visual translation** (Ollama `qwen2.5vl` / `gemma3`, LM Studio, or BYOK).
- **Local AI Document Assistant:** *Ask this PDF* with clickable `[p. N]` citations, Document/Chapter Summarizer, and structured JSON/CSV extraction using your own local or BYOK LLM.
- **Press-Room CMYK Preflight (No Ghostscript):** PDF/X-1a & PDF/X-4 audits, recursive Form XObject inspection, true C/M/Y/K plate separation, TAC heatmap, live ink-density eyedropper, and one-click pure-Python press fixes.
- **CAD, Blueprints & Publishing Automation:** Native PDF ↔ DXF, calibrated blueprint takeoff with vector snapping & Excel quantity schedules, CAD layers, LTR/RTL multi-signature booklet imposition, POD spine calculator, PDF/A & PDF/UA accessibility, Office/HTML/Markdown conversions, multi-step Recipes, Watch Folders, Smart Auto-Filing, and Local Semantic Folder Search.

## Updating

Already have ZPDF installed? Open **Settings → Updates** (or click the **Update** button in the app) to update automatically on Windows, macOS, or Linux (verified against each release's SHA-256 checksum).