# TLK Test Builds

Public distribution repository for TLK technical-feasibility APKs.

## Current U1 build

**TLK-U1-PoC-003** — recovery build for regression `U1-IME-002`.

- Version: `0.0.3` (versionCode 3)
- Build timestamp: `2026-09-10T05:35:06Z`
- SHA-256: `dee3c32066e9ec4fa6282b5e6d7c978877f12aaa49485f4b81798cb109c0ebd5`
- Purpose: restore the local U1 keyboard after PoC 002 startup regression; keep LAN initialization isolated from the core IME lifecycle.

### Direct download

[Download latest TLK U1 debug APK](https://github.com/TrocLoc81/TLK-Test-Builds/releases/download/tlk-test-latest/TLK-U1-latest-debug.apk)

Versioned asset:

[Download TLK-U1-PoC-003.apk](https://github.com/TrocLoc81/TLK-Test-Builds/releases/download/tlk-test-latest/TLK-U1-PoC-003.apk)

## Install and recovery test

1. Preserve the current PoC 002 failure state until any requested observations are recorded.
2. Install PoC 003 directly over PoC 002; do not uninstall, clear data, disable TLK, or change the selected IME.
3. Open a normal text editor and record whether TLK appears immediately.
4. If TLK does not appear, reboot once and test again.
5. Verify local keys, `TLK TEST`, Backspace, Space, and Enter.
6. Report whether Settings still lists TLK as the selected keyboard and whether the IP/status label appears.

Do not continue Phone ↔ U1 testing until the local IME is restored.
