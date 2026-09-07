# Betaflight Custom Presets — radiosimian

This is the `bf-presets` branch of the [fpv](https://github.com/radiosimian/fpv) repo.
It contains personal Betaflight presets and is not intended for the official preset repo.

## Adding as a custom source in Betaflight Configurator

1. Open Betaflight Configurator and go to **Presets**
2. Click **Preset Sources** (top right)
3. Add a new source:
   - **URL:** `https://github.com/radiosimian/fpv`
   - **Branch:** `bf-presets`
4. Click **Save** — your presets will appear in the search list alongside official ones

## Presets

| Title | Category | BF Version | Notes |
|---|---|---|---|
| Walksnail HD OSD Layout - radiosimian | OSD | 2026.6.1 | MSP DisplayPort, HD canvas |

## Structure

```
index.json                          ← preset catalogue (read by Configurator)
presets/
└── 4.6/
    └── osd/
        └── walksnail_osd_chonk20.txt
```

