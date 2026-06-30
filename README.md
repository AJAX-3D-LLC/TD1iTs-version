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

## Recommended URLs after GitHub Pages is enabled

Replace `YOUR_GITHUB_USERNAME` and `td1-version` with your real account/repo names.

```text
https://YOUR_GITHUB_USERNAME.github.io/td1-version/version.json
https://YOUR_GITHUB_USERNAME.github.io/td1-version/td1-interface-standalone.json
https://YOUR_GITHUB_USERNAME.github.io/td1-version/td1-firmware.json
https://YOUR_GITHUB_USERNAME.github.io/td1-version/downloads/TD1_Firmware_v1.0.4.zip
```

If you add a custom domain, replace the base URL with your domain, for example:

```text
https://version.ajax-3d.com/version.json
```

## Updating versions

1. Replace the firmware ZIP in `downloads/`.
2. Update `latestVersion`, `downloadUrl`, `fileName`, `fileSize`, and `sha256` in `td1-firmware.json` and `version.json`.
3. Update `latestVersion` in `td1-interface-standalone.json` and `version.json` when the standalone interface tool changes.
4. Commit and push.

