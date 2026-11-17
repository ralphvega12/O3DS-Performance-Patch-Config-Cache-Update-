# O3DS Performance Patch Installation

If you already have the game installed on your SD card, you only need to update your performance settings and clear your cache. Your `UserData` progress will remain safe because it is not included in this patch.

## How to Update Your Files

1. **Delete old cache files:** Go to `sdmc:/3ds/sims/cache/` on your SD card and delete the old `.cache` files (keep `cache_version.txt`).
2. **Replace the settings file:** Copy the new `sims_options.txt` from the patch and paste it directly into `sdmc:/3ds/sims/Saves/`, replacing your old settings file.
3. **Copy the new cache files:** Copy the new cache files from the patch and paste them directly into `sdmc:/3ds/sims/cache/`.

---

## SD Card File Structure

Make sure your individual files are placed directly in these exact locations:

```text
sdmc:/
└── 3ds/
    └── sims/
        ├── sims.3dsx
        ├── cache/
        │   ├── cache_version.txt
        │   └── (new cache files)
        └── Saves/
            ├── sims_options.txt   <-- Replace this file
            ├── UserData/          <-- Your existing progress (Untouched)
            └── UserData2/         <-- Your existing progress (Untouched)
