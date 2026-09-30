<div align="center">

# MetaCSV Studio

**Local GPU AI image upscaling for photographers, artists & microstock contributors.**

_Free · Private by design · No cloud uploads — everything runs on your machine._

[![Latest Release](https://img.shields.io/github/v/release/Hasinur3813/metacsv-studio-releases?style=flat-square)](https://github.com/Hasinur3813/metacsv-studio-releases/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-x64-0078D6?style=flat-square&logo=windows)](https://github.com/Hasinur3813/metacsv-studio-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Hasinur3813/metacsv-studio-releases/total?style=flat-square)](https://github.com/Hasinur3813/metacsv-studio-releases/releases)

[⬇ Download Latest](https://github.com/Hasinur3813/metacsv-studio-releases/releases/latest) · [All Versions](#all-versions) · [Verify Integrity](#verify-your-download) · [Troubleshooting](#troubleshooting)

</div>

---

## ✨ What is MetaCSV Studio?

MetaCSV Studio is a lightweight native desktop app that upscales images with AI —
**Real-ESRGAN / Vulkan** running directly on your GPU. No subscriptions, no queues,
no uploading client work to a server.

| | |
|---|---|
| 🖼️ **Batch & single upscale** | Drag-and-drop JPEG, PNG, WEBP, TIFF — whole folders welcome |
| ⚡ **Local GPU first** | Real-ESRGAN via Vulkan, with automatic CPU fallback |
| 🎨 **Model choice** | General Photo, Digital Art / Anime, Fast enhance |
| 🔍 **Compare studio** | Side-by-side slider with zoom up to 500% |
| 📐 **Flexible output** | 2× → 16× scales, PNG / JPEG / WEBP export |

---

## 💻 System Requirements

| | Minimum | Recommended |
|---|---|---|
| **OS** | Windows 10 64-bit (21H2+) | Windows 11 64-bit |
| **RAM** | 8 GB | 16 GB+ |
| **GPU** | Any Vulkan-capable GPU | Discrete NVIDIA / AMD GPU |
| **Disk** | 1 GB free | 4 GB free (batch work) |
| **Network** | Required once for sign-in | Always-on for auto-updates |

> No Vulkan driver? The app falls back to CPU automatically — slower, but it works.

---

## 🚀 Install

1. Go to the [**latest release**](https://github.com/Hasinur3813/metacsv-studio-releases/releases/latest).
2. Download the latest **`MetaCSV-Studio-Setup-<version>.exe`** (check the release notes for the exact filename).
3. Run it — per-user install, **no admin rights needed**.
4. Sign in with your MetaCSV account when the app opens.

### 🔐 Verify your download

Each release ships a `SHA256SUMS.txt`. Compare before running:

```powershell
Get-FileHash .\MetaCSV-Studio-Setup-<version>.exe -Algorithm SHA256