# Tilta Lens Profiles

[![Viltrox](https://img.shields.io/badge/Viltrox-EPIC%201.33x-e05d44)](https://github.com/ZClassified/tilta-lens-profiles/releases/tag/v1.0.0)
[![Sony](https://img.shields.io/badge/Sony-CineAlta-555555?labelColor=000000)](https://github.com/ZClassified/tilta-lens-profiles/releases/tag/v1.1.0)

![Adapter](https://img.shields.io/badge/Adapter-Nucleus%20AF%20(E%20to%20PL)-007ec6)
![Firmware](https://img.shields.io/badge/Firmware-1.8.6-2ea44f)

Lens profiles (`.tl`) for the **Tilta Nucleus Auto Focus Adapter – Dual Nano II Motor Kit (E to PL)**.
Created and tested on firmware **1.8.6**.

## Profiles

| Lens                                         | Folder     | Files                                                                       | Unit   | `af_optimize` |
|----------------------------------------------|------------|-----------------------------------------------------------------------------|--------|---------------|
| Viltrox EPIC 35 / 50 / 75mm 1.33x            | `VILTROX/` | `EPIC_35.tl`, `EPIC_50.tl`, `EPIC_75.tl`                                    | feet   | `-3`          |
| Sony CineAlta MK1 35 / 50 / 85mm, MK2 25mm   | `SONY_M/`  | `CINEALTA_MK1_35_M.tl`, `CINEALTA_MK1_50_M.tl`, `CINEALTA_MK1_85_M.tl`, `CINEALTA_MK2_25_M.tl` | metric | `0`           |

Lenses with both metric and imperial marks get separate folders (`_M` / `_FT`) – copy only the one you want.

## Installation

1. Connect the adapter via USB-C to the **PD IN** port.
2. In the adapter menu, select **IMPORT DATA** – the adapter mounts as a USB drive.
3. Copy the whole folder (e.g. `VILTROX/` incl. all `.tl` files) into the root of the drive.

Note: a firmware update erases the lens library – re-import the profiles afterwards.

## AF behaviour (`af_optimize`)

`af_optimize` is not documented by Tilta. Observations so far:

- **Viltrox EPIC:** `0` felt too aggressive, `-3` gives smoother transitions.
- **Sony CineAlta:** left at `0`, but the 85mm felt very slow at `0`.

The value can be edited in the `.tl` file with any text editor before importing.

## License

See [LICENSE](LICENSE). Free to use on your own equipment – please link to this repo instead of re-uploading the files.

Not affiliated with Tilta, Viltrox or Sony.
