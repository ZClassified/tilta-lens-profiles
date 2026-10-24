# Tilta Lens Profiles

Lens profiles (`.tl`) for the **Tilta Nucleus Auto Focus Adapter – Dual Nano II Motor Kit (E to PL)**.
Created and tested on firmware **1.8.6**.

## Profiles

| Lens                                | Folder     | Files                                       |
|-------------------------------------|------------|---------------------------------------------|
| Viltrox EPIC 35 / 50 / 75mm 1.33x   | `VILTROX/` | `EPIC_35.tl`, `EPIC_50.tl`, `EPIC_75.tl`    |

## Installation

1. Connect the adapter via USB-C to the **PD IN** port.
2. In the adapter menu, select **IMPORT DATA** – the adapter mounts as a USB drive.
3. Copy the whole brand folder (e.g. `VILTROX/` incl. all `.tl` files) into the lens profile directory on the drive.

## AF speed

All profiles are set to `"af_optimize": -3`, as `0` felt too aggressive.
Edit the value in the `.tl` file with any text editor before importing – lower = smoother/slower transitions, higher = faster.

## License

See [LICENSE](LICENSE). Free to use on your own equipment – please link to this repo instead of re-uploading the files.

Not affiliated with Tilta or Viltrox.
