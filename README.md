# TLK Test Builds

Public distribution repository for TLK technical-feasibility APKs.

## Current builds

### Dangbei U1

**TLK-U1-PoC-003** — recovery build for the PoC 002 IME startup regression.

[Short download link for U1](https://trocloc81.github.io/TLK-Test-Builds/u/)

- Version: `0.0.3` (versionCode 3)
- Built: `2026-09-10T05:35:06Z`
- SHA-256: `dee3c32066e9ec4fa6282b5e6d7c978877f12aaa49485f4b81798cb109c0ebd5`

### Samsung S23 Ultra / Android phone

**TLK-Phone-PoC-003** — automatic readiness probe and one-shot Share → TLK send.

[Short download link for phone](https://trocloc81.github.io/TLK-Test-Builds/p/)

- Normal app open probes the saved U1 endpoint without sending retained text.
- Share → TLK sends once when U1 is READY.
- Failure / NO_ACTIVE_EDITOR retains the payload with no automatic retry or future insertion.
- Manual clipboard and SEND TO U1 flows remain available.
- Version: `0.0.3` (versionCode 3)
- Built: `2026-09-10T13:35:32Z`
- SHA-256: `358fa399972ac8ab861ee1ff5afa03ed69d702922376b08941f54b76416f2b0d`

These are technical-feasibility builds, not production releases.
