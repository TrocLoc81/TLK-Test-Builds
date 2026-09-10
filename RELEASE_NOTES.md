# TLK Sprint 2 test builds

## Dangbei U1 — TLK-U1-PoC-003

- Version: `0.0.3` (3)
- SHA-256: `dee3c32066e9ec4fa6282b5e6d7c978877f12aaa49485f4b81798cb109c0ebd5`

## Android phone — TLK-Phone-PoC-003

Risk-based feasibility build implementing A's approved connection/send policy.

- Normal app open probes the saved U1 endpoint and reports readiness without committing retained text.
- Share → TLK is treated as an explicit send action and attempts one commit when U1 is READY.
- NO_ACTIVE_EDITOR or connection failure retains the payload; there is no automatic retry or future insertion.
- Manual SEND TO U1, foreground clipboard, endpoint persistence, and keyboard-safe action placement remain.
- ACTION_SEND lifecycle guard prevents the same share intent from committing twice after Activity recreation.
- Package/signing identity retained for an in-place update over Phone PoC 001/002.
- Version: `0.0.3` (3)
- Built: `2026-09-10T13:35:32Z`
- SHA-256: `358fa399972ac8ab861ee1ff5afa03ed69d702922376b08941f54b76416f2b0d`

Kha risk-based build/static validation: PASS. Physical S23U/U1 acceptance: pending.
