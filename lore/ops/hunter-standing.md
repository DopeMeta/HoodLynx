# Hunter Standing (Authorized Hunter reputation)

## Does this make sense?

**Yes — if kept soft.**  
It rewards people who keep playing, without promising an automatic scoreboard that bots can farm or that locks you into “5 submits = 5 mints.”

## What it is

Internal + Terminal flavor for how trusted / active a Hunter identity is.

Public name options (pick one and stick to it):
- **HUNTER STANDING** (recommended)
- Network Trust
- Clearance

Avoid “XP” / “points” language.

## How it actually works (ops)

You track standing **off-Terminal** (sheet / Notion / chat notes). Terminal only *displays* flavor.

Signals that raise standing (manual):
- Real Terminal reconnects across missions (same handle + wallet)
- Useful replies / theories / helping others
- In Hood Lynx Hunters chat
- Not obvious multi-account behavior

Signals that lower / block:
- Botty / duplicate wallets
- Spam replies
- Same person farming many handles

### Suggested private tiers

| Standing | Meaning | Mint lean |
|----------|---------|-----------|
| SIGNAL DETECTED | First-time / thin history | Maybe 1 if solid |
| LINKED | Repeat player, looks real | Priority for mission slots |
| TRUSTED | Consistent Hunter | Strong GTD candidate; possible +1 later if you want |
| NETWORK NODE | Core community | Best access / possible multi later |

**Important:** multi-spots are a **manual reward**, not an automatic Terminal counter. Only grant extras when you’re sure.

## How to show it in Terminal (without overbuilding)

### Option A — simplest (recommended for tonight)

Same screen for everyone on entry.  
After submit, add one standing line you can later make dynamic:

```text
...RECONNECT SIGNAL SENT
...WALLET LOCKED TO IDENTITY
HUNTER STANDING: UNDER REVIEW
```

Later, if your Terminal tool can branch by returning wallet/handle:
- first time → `HUNTER STANDING: SIGNAL DETECTED`
- returning → `HUNTER STANDING: LINKED` or `TRUSTED`

### Option B — static story tease (no backend needed)

Add to after-submit for everyone:

```text
REPEAT SIGNALS INCREASE STANDING.
STANDING AFFECTS FUTURE AUTHORIZATION WEIGHT.
```

This teaches the system without showing personal scores.

### Option C — full dynamic (only if Terminal supports logic)

On submit, look up handle/wallet:
1. new → SIGNAL DETECTED + intercept crumb  
2. returning → higher standing line + same/extra crumb  
3. flagged → `STANDING: FLAGGED // VERIFICATION DELAYED`

## What NOT to do

- Don’t show `STANDING SCORE: 47` publicly  
- Don’t say “every reconnect = +1 mint”  
- Don’t require new people only for standing to matter  
- Don’t update Terminal copy every day just to rename tiers  

## Fit with tonight’s 30

- Everyone (new + returning) can reconnect  
- Standing helps **you** choose which ~30 are verified  
- Returning trusted Hunters can be favored without excluding newcomers  
- Terminal can hint that repeat Signals matter, without publishing a leaderboard  
