# TLK Test Builds

Public distribution repository for TLK technical-feasibility APKs.

## Current builds

### Dangbei U1

**TLK-U1-PoC-003** — recovery build for the PoC 002 IME startup regression.

[Download latest TLK U1 debug APK](https://github.com/TrocLoc81/TLK-Test-Builds/releases/download/tlk-test-latest/TLK-U1-latest-debug.apk)

- Version: `0.0.3` (versionCode 3)
- Built: `2026-09-10T05:35:06Z`
- SHA-256: `dee3c32066e9ec4fa6282b5e6d7c978877f12aaa49485f4b81798cb109c0ebd5`

### Samsung S23 Ultra / Android phone

**TLK-Phone-PoC-001** — foreground LAN sender with editable text, clipboard read, Send and Android Sharesheet support.

[Download latest TLK Phone debug APK](https://github.com/TrocLoc81/TLK-Test-Builds/releases/download/tlk-test-latest/TLK-Phone-latest-debug.apk)

- Version: `0.0.1` (versionCode 1)
- Built as part of milestone: `2026-09-10T05:35:06Z`
- SHA-256: `03adff6f2a0e18931ab4aabe7404e349256ea59b77e5cfda45ceb0510cd04e05`

## Test order

1. Install U1 PoC 003 directly over PoC 002 without uninstalling, clearing data, disabling TLK, or changing the selected IME.
2. Confirm the local U1 keyboard appears and local keys work.
3. Only after the local/offline gate passes, install the Phone PoC and begin LAN testing.
4. If U1 is not ready, keep the payload on the phone and resend manually after refocusing the editor.

These are technical-feasibility builds, not production releases.
