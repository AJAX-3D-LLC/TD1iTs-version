# TD1 Version Manifest

Static version manifest server for TD1 Interface Tool and TD1 firmware.

This repo is intended to be published with GitHub Pages.

## Files

| File | Purpose |
|------|---------|
| `version.json` | Combined manifest for TD1 Interface Tool standalone and TD1 firmware |
| `td1-interface-standalone.json` | Standalone TD1 Interface Tool version-check endpoint |
| `td1-firmware.json` | TD1 firmware version-check endpoint and firmware download URL |
| `downloads/TD1_Firmware_v1.0.4.zip` | Firmware ZIP download placeholder; replace with your real firmware ZIP |
| `.nojekyll` | Tells GitHub Pages to serve files as plain static files |

```text
https://version.ajax-3d.com/version.json
```

## Updating versions

1. Replace the firmware ZIP in `Releases`.
2. Update `latestVersion`, `downloadUrl`, `fileName`, `fileSize`, and `sha256` in  `version.json`.
3. Commit and push.


## Replacing TD1iTs Installers

1. Replace TD1iTs Installers for each platform in 'Releases'.Update `latestVersion` in `version.json` when the standalone interface tool changes.
2. Update `latestVersion` in `version.json` when the standalone interface tool changes.
3. Commit and push.
