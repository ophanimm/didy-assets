# Asset sources

Every file here came from the owner's Left 4 Dead project (AIM MOD, `github.com/ophanimm/aimmod-assets` has the same
sources) and was converted for Quake Live by `tools/assets_repo.py` in DIDY MENU: skies and textures re-saved as JPG,
sounds made mono and re-encoded as Ogg Vorbis, crosshairs copied as they are.

## Skies (`skies/`): CC0

| Files | Source | Author | Licence |
|---|---|---|---|
| `sbs_04_clear_day`, `sbs_11_night_purple`, `sbs_14_toxic_green`, `sbs_15_dark_night`, `sbs_16_blue_sky`, `sbs_17_sunset`, `sbs_22_red_sunset`, `sbs_24_overcast` | "Cloudy Skyboxes" pack (panoramas), Terragen renders: https://screamingbrainstudios.itch.io/cloudy-skyboxes-pack and https://opengameart.org/content/cloudy-skyboxes-0 | Screaming Brain Studios | CC0 1.0 (Licence.txt inside the pack) |
| `ph_clear_day` | "Kloofendal 43d Clear (Pure Sky)": https://polyhaven.com/a/kloofendal_43d_clear_puresky | Poly Haven | CC0 (https://polyhaven.com/license) |
| `ph_partly_cloudy` | "Kloofendal 48d Partly Cloudy (Pure Sky)": https://polyhaven.com/a/kloofendal_48d_partly_cloudy_puresky | Poly Haven | CC0 |
| `ph_sunset` | "Belfast Sunset (Pure Sky)": https://polyhaven.com/a/belfast_sunset_puresky | Poly Haven | CC0 |
| `ph_overcast` | "Kloofendal Overcast (Pure Sky)": https://polyhaven.com/a/kloofendal_overcast_puresky | Poly Haven | CC0 |
| `ph_night_stars` | "Kloppenheim 02 (Pure Sky)": https://polyhaven.com/a/kloppenheim_02_puresky | Poly Haven | CC0 |
| `ph_moonrise` | "Qwantani Moonrise (Pure Sky)": https://polyhaven.com/a/qwantani_moonrise_puresky | Poly Haven | CC0 |
| `qlm_aurora`, `qlm_galaxy`, `qlm_rainbow`, `qlm_starfield`, `qlm_sunset_clouds` | Generated for the owner's projects (procedural FFT noise, wraps left to right; the scene names follow QL Menu's scene list, no QL Menu file is used) | this project | CC0 |

What we changed: Screaming Brain Studios panoramas are unmodified apart from the JPG re-save. Poly Haven skies were
downloaded as the 2k HDR originals and tonemapped to 8-bit (log tonemap, gamma 2.0). Previews are the same pictures
shrunk to 256×128.

## KovaaK's (`skies/kv_*`, `textures/kv_*`, `crosshairs/kv_*`, `sounds/kv_*`): NOT licensed for redistribution

KovaaK's (FPS Aim Trainer) is a paid game by The Meta. These files were read from the owner's own install:

| Files | Where in KovaaK's |
|---|---|
| `skies/kv_01` … `kv_10`, `kv_aurora_01`, `kv_aurora_02` | its .pak, `Content/GoodSky/SkyboxFlowPack_Bundle` sky images, unwrapped to 2:1 panoramas |
| `textures/kv_*` | its .pak, the map editor's grid textures and wall / floor albedos, 512×512 |
| `crosshairs/kv_*`, `crosshairs/big/kv_*` | its `crosshairs` folder (many are community-made crosshairs bundled with the game; `big/` holds its 9 full-screen overlay pictures, anime art and the like, by unknown community authors) |
| `sounds/kv_*` | its `sounds` folder (hit, kill, bell, tick and pop sounds, community sounds bundled with the game, and a few Quake 3 sounds by id Software: `kv_q3*`) |

The nine full-screen ones (1012×454 up to 2536×1440) are in `crosshairs/big/`, unchanged (owner 2026-11-05: "nah put
the anime pictures in there too").

## Hit sounds from other games (`sounds/`): NOT licensed for redistribution

| Files | Where they came from |
|---|---|
| `csgo_headshot` | Counter-Strike: Global Offensive |
| `cod_hitmarker` | Call of Duty |
| `mw2_hitmarker`, `mw3_hitmarker_headshot`, `mw3_hitmarker_kill` | Call of Duty: Modern Warfare 2 / 3 |
| `fortnite_headshot` | Fortnite |
| `overwatch_kill` | Overwatch |
| `rust_headshot` | Rust |
| `tf2_hitsound` | Team Fortress 2 |
| `valorant_kill` | VALORANT |
| `ns2_hit`, `ns2_kill` | Natural Selection 2 (from the owner's own port) |

A few of these were downloaded from myinstants.com rather than ripped from the game; where a file has a game's name,
it is that game's audio.

**These are other games' assets, not offered under any licence.** The owner chose to include them for his friends'
use with DIDY MENU (owner 2026-11-05: "other games are good to go"). If you are not one of those friends, don't
re-host them.

## Deliberately absent

- **GTA V** content (the L4D project's effect packs are cut from GTA V's archives).
- **QL Menu**'s bundled crosshairs and sounds: another author's menu.
