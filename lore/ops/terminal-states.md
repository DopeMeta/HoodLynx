# Terminal States

## WL / counting policy (owner lock)

- Internally: ~100 early accounts, then wallet batches (~20 + ~20), plus collab WL — **do not publish running totals**
- Public Terminal: stay **vague** so bots / multi-accounts can be filtered and collab slots balanced
- Only show a number when it is a **new mission cap** (e.g. “20 new verified Hunters”)
- Never show cumulative `AUTHORIZED HUNTERS: 20 / 20` style scoreboards unless intentionally opening a fresh verified mission

---

## FULL TERMINAL WRITE-UP (current story: post-002 → 003)

### Screen 1 — before submit

```text
// HOODLYNX ARCHIVE TERMINAL
STATUS: ONLINE
----------------------------------------
FRAGMENT 001
STATUS: DECRYPTED
ARCHIVE ENTRY: STORED
----------------------------------------
FRAGMENT 002
STATUS: DECRYPTED
ARCHIVE ENTRY: STORED
----------------------------------------
TARGET: FRAGMENT 003
STATUS: TRACE UNSTABLE
SIGNAL STRENGTH: █████░░░░░
INTERFERENCE: DETECTED
SOURCE: UNKNOWN
----------------------------------------
AUTHORIZATION WINDOW: ACTIVE
ELIGIBLE: UNIDENTIFIED IDENTITIES
ACCESS: AUTHORIZED HUNTER ACCESS
Verification required.
----------------------------------------
AWAITING IDENTIFICATION...
@
ENTER X HANDLE
Ξ
EVM WALLET (0x...)
▸ SEND SIGNAL
```

### Screen 2 — after submit

```text
AUTHORIZATION WINDOW: ACTIVE
ELIGIBLE: UNIDENTIFIED IDENTITIES
ACCESS: AUTHORIZED HUNTER ACCESS
----------------------------------------
...IDENTIFICATION SIGNAL SENT
...WALLET LOCKED TO IDENTITY
----------------------------------------
A SINGLE NODE IS EASY TO SILENCE.
A NETWORK IS NOT.
----------------------------------------
STAND BY FOR VERIFICATION.
...TRACE RESUMING
FOLLOW THE SIGNAL.
```

### Optional later — only if opening a real capped mission

```text
NEW MISSION WINDOW: ACTIVE
VERIFIED HUNTERS NEEDED: 20
```

Use only when you will actually select ~20 and can stand behind the number.
