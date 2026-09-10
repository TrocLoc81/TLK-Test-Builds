# TLK Sprint 2 test builds

## Dangbei U1 — TLK-U1-PoC-004

Bluetooth Classic RFCOMM transport feasibility build.

- Retains the proven local IME and LAN listener.
- Adds secure RFCOMM service UUID `9d734f61-653b-4b0c-9a22-6cf5df2c6f4a`.
- Bluetooth init/listen/accept runs outside IME lifecycle/UI callbacks.
- Bluetooth failure is contained; local keys and LAN remain independent.
- Listener can restart at a keyboard-show lifecycle point after Bluetooth off/on or listener failure.
- Package/service/signing identity retained for an in-place update over U1 PoC 003.
- Version: `0.0.4` (4)
- Built: `2026-09-10T14:27:44Z`
- SHA-256: `4b7c53ff3b6267afa3dde28e00543f1328eed416b972023f7a612675c7082677`

## Android phone — TLK-Phone-PoC-004

Selectable LAN / Bluetooth Classic RFCOMM feasibility sender.

- Uses the list of devices already paired in Android Settings; no final pairing UX.
- Requests `BLUETOOTH_CONNECT` / Nearby devices permission on Android 12+.
- Persists selected transport and Bluetooth device.
- Shares the existing UTF-8 protocol and editor-session safety semantics with LAN.
- Keeps one-shot Share → TLK, manual Send, clipboard, NO_ACTIVE_EDITOR retention and no automatic retry.
- RFCOMM connect watchdog closes a stalled attempt after 8 seconds.
- Package/signing identity retained for an in-place update over Phone PoC 003.
- Version: `0.0.4` (4)
- Built: `2026-09-10T14:27:44Z`
- SHA-256: `d4935bdb02c60d199968f8f9cee206e1eec7a1ce4ee4b3ef7886470d74e54767`

Kha risk-based build/static validation: PASS. Physical S23U/U1 RFCOMM acceptance: pending.
