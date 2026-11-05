# DIDY MENU assets

Downloadable content for **DIDY MENU** (a Quake Live companion menu for friends). **Assets only** — the menu itself
is not here: there is no executable, no source code, no script and no DLL in this repository.

The DIDY MENU Loader reads `manifest.json`, downloads what it needs into its own folder (`<DIDY folder>\assets\`,
never into the Quake Live folder), checks each file's SHA-256 and size against the manifest, and only then keeps it.
If a check fails the file is deleted. Nothing in this repository is ever run as a program; every file is data
(`.jpg` / `.png` pictures, `.ogg` audio, `.md` / `.json` text).

## What's here

| Folder | Contents |
|---|---|
| `skies/` | 31 sky panoramas, 2048×1024 JPG (2:1, wraps left to right). DIDY uses them for **Animated sky**, **Drifting sky** and the Textures tab's sky. Also attached to release **v1**. |
| `skies/previews/` | 256×128 previews of the same skies, for the menu's pickers. |
| `sounds/` | 178 hit / kill sounds as **mono** Ogg Vorbis (Quake Live refuses stereo sounds). For DIDY's **Hit sound** and **Kill sound**. |
| `textures/` | 35 wall / floor / grid textures, 512×512 JPG, for the Textures tab's **My picture**. |
| `crosshairs/` | 58 crosshair pictures (PNG with transparency) for **Animated crosshair**. A few are marked "off-centre" in the manifest: their shape doesn't sit on the aim point. |
| `crosshairs/big/` | 9 large KovaaK's crosshair pictures (anime pictures and other full-screen overlays, PNG with transparency, up to 2536×1440), marked `"overlay": true`. DIDY fits them centred into the crosshair square without stretching; they also work as pictures elsewhere (sky, textures). |
| `CREDITS.md` | Where every file came from, and its licence (or lack of one). |
| `manifest.json` | Every file with its size, SHA-256, kind and label. |

In the menu all of these show up as **DIDY pack**: in the Library tab's file list and in the pickers of the boxes above.

## Licence

The Poly Haven and Screaming Brain Studios skies are **CC0 / public domain**. The `qlm_*` skies were generated for
this project (procedural noise) and are CC0 as well. The `README.md`, `CREDITS.md` and `manifest.json` text may be
reused freely.

**Everything else is NOT licensed for redistribution:** the KovaaK's skies, textures, crosshairs and sounds, and the
hit sounds from other games (Call of Duty, CS:GO, Fortnite, Overwatch, Rust, TF2, VALORANT, Natural Selection 2) are
other people's work, included by the owner's choice for his friends' use with DIDY MENU. `CREDITS.md` lists every
source. Don't re-host them, and read nothing here as a grant of rights.

## Not here, on purpose

The menu, the helper, the loader and all source code; QL Menu's bundled crosshairs and sounds (another author's
menu); GTA V content.
