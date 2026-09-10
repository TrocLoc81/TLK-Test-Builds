# TLK Sprint 2 test builds

## Dangbei U1 — TLK-U1-PoC-003

- Version: `0.0.3` (3)
- SHA-256: `dee3c32066e9ec4fa6282b5e6d7c978877f12aaa49485f4b81798cb109c0ebd5`

## Android phone — TLK-Phone-PoC-002

Risk-based regression build based on A's physical S23U test.

- Saves U1 IP/port and restores them before processing `ACTION_SEND`.
- Keeps the endpoint when Share → TLK replaces the payload.
- Moves READ CLIPBOARD / SEND TO U1 / CLEAR above the payload field so Samsung Keyboard does not cover the actions.
- Package/signing identity retained for an in-place update over Phone PoC 001.
- Version: `0.0.2` (2)
- Built: `2026-09-10T13:04:02Z`
- SHA-256: `8f51ecc3439f03549cbeb9412bd1b89e2a7602a00f7761f94e51544f2581caeb`

Lam independent static/build review: PASS. Physical S23U regression validation: pending.
