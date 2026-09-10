# TLK Test Builds

Public distribution repository for TLK technical-feasibility APKs.

## Current builds

### Dangbei U1

**TLK-U1-PoC-004** — LAN + Bluetooth Classic RFCOMM transport feasibility build.

[Short download link for U1](https://trocloc81.github.io/TLK-Test-Builds/u/)

- Keeps the proven local IME and LAN path.
- Adds an isolated secure RFCOMM listener for paired devices.
- Bluetooth failure/off state must not disable the local keyboard or LAN.
- Version: `0.0.4` (versionCode 4)
- Built: `2026-09-10T14:27:44Z`
- SHA-256: `4b7c53ff3b6267afa3dde28e00543f1328eed416b972023f7a612675c7082677`

### Samsung S23 Ultra / Android phone

**TLK-Phone-PoC-004** — selectable LAN / Bluetooth Classic RFCOMM sender.

[Short download link for phone](https://trocloc81.github.io/TLK-Test-Builds/p/)

- Keeps LAN, clipboard, manual Send and one-shot Share → TLK behavior.
- Uses an Android Settings-paired Bluetooth device and requests Nearby devices permission on Android 12+.
- Persists the selected transport/device.
- Keeps NO_ACTIVE_EDITOR payload retention with no automatic retry or future insertion.
- Version: `0.0.4` (versionCode 4)
- Built: `2026-09-10T14:27:44Z`
- SHA-256: `d4935bdb02c60d199968f8f9cee206e1eec7a1ce4ee4b3ef7886470d74e54767`

These are technical-feasibility builds, not production releases.
