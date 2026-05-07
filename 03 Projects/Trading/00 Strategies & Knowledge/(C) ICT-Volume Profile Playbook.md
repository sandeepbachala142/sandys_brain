# ICT + Volume Profile Trading Playbook

**Status:** Active | **Updated:** 2026-05-06 | **Focus:** Mechanical, rule-based system combining ICT concepts with Volume Profile for NQ and other liquid instruments.

---

## Quick Reference: The System in 3 Lines

1. **Daily Bias** — Use yesterday's RTH Volume Profile (VAH/VAL/POC) + how market opens to determine direction.
2. **Entry Confluence** — ICT setup (Order Block, FVG, or Liquidity sweep) must sit on a High Volume Node, POC, or Value Area edge.
3. **Target & Hold** — Trade to the next major liquidity zone or HVN; trail stops aggressively, don't take profits early.

---

## Part 1: Volume Profile Fundamentals

### What is Volume Profile?
Shows **volume by price level**, not by time. Reveals where institutions traded the most and where they found resistance.

### Key Components

| Term | Definition | What It Means |
|------|-----------|---------------|
| **POC** | Point of Control | Price with most traded volume; acts as magnet/support/resistance |
| **VA** | Value Area | ~70% of all volume traded here; fair value range |
| **VAH** | Value Area High | Top of value area = premium (watch for shorts) |
| **VAL** | Value Area Low | Bottom of value area = discount (watch for longs) |
| **HVN** | High Volume Node | Price area with heavy volume; market slows/consolidates |
| **LVN** | Low Volume Node | Price area with little volume; market moves fast (air pocket) |

### The 80% Rule (Mechanical Gold Rule)
**If price opens outside the value area and then re-enters it, ~80% chance it trades all the way to the opposite side.**

Example: Market opens above VAH, pulls back inside VA → likely to fill down to VAL.

### Critical Rule: Use RTH Profile Only
- **RTH = 9:30 AM – 4:00 PM Eastern** (where real institutional volume lives)
- **Not 24-hour profile** (overnight volume is noise; often gets faded)
- Big overnight gaps often reverse back into RTH value area

**Tool:** TradingView — Volume Profile fixed range or session profile (free account sufficient).

---

## Part 2: Daily Bias Determination (3-Step Mechanical Process)

Run this **every single morning before market open.** Same process, no exceptions.

### Step 1: Mark Yesterday's RTH Volume Profile
- Draw the Volume Profile on yesterday's 9:30 AM–4:00 PM session
- Identify and mark:
  - **VAH** (Value Area High)
  - **VAL** (Value Area Low)
  - **POC** (Point of Control)

### Step 2: Check Yesterday's Close
Where did price close relative to the value area?

| Close Position | Bias | Implication |
|---|---|---|
| **Inside VA** | Neutral | Market at fair value; expect rotation/chop |
| **Above VAH** | Bullish/Premium | Watch for shorts or continuation; resistance above |
| **Below VAL** | Bearish/Discount | Watch for longs or continuation; support below |

### Step 3: Check Today's Open & Price Action
Where did price open today relative to yesterday's VA?

| Open Position | Action | Bias Strength |
|---|---|---|
| **Inside VA** | Expect choppy/rotational movement | Lower confidence |
| **Outside VA, then re-enters** | **80% Rule activates** → Expect move to opposite VA edge | **Very High Confidence** |
| **Outside VA, stays outside** | Strong trend move; trade with the trend | High Confidence |

**Output:** You now have a mechanical daily bias for the session.

---

## Part 3: The Trade Setup — Confluence Checklist

**Every trade requires ALL of these:**

### 1. Daily Bias ✓
- Use the 3-step process above to confirm direction
- Trade with the bias, not against it

### 2. ICT Entry Signal ✓
Choose ONE of the three (or combination):

#### a) Order Block (OB)
- Last bullish/bearish candle before significant opposite move
- Represents institutional order flow
- **Volume Profile confirmation:**
  - **Strong OB:** Sitting on HVN, POC, or VA edge → High probability
  - **Weak OB:** Sitting in LVN → Price blasts through, avoid

#### b) Fair Value Gap (FVG)
- 3-candle pattern: candle 1 normal → candle 2 aggressive move → candle 3 retraces, leaving gap
- **Volume Profile confirmation:**
  - **Strong FVG:** In LVN → High probability fill (price moves fast through LVNs)
  - **Weak FVG:** In HVN → Lower probability, price may not fill easily

#### c) Liquidity Sweep
- Price sweeps above swing highs (buy-side liquidity) or below swing lows (sell-side liquidity)
- Institutions hunt these stops
- **Volume Profile confirmation:**
  - **Strong liquidity:** At HVN or POC → Very high likelihood market sweeps there
  - **Session liquidity:** London session high/low swept during NY = high confluence

### 3. Volume Profile Confirmation ✓
Entry level **MUST sit on one of these:**
- **High Volume Node (HVN)** ← Strongest
- **Point of Control (POC)** ← Strongest
- **Value Area edge (VAH or VAL)** ← Very Strong
- **Avoid LVN entries** unless using as "air pocket" to identify fast movement zones

### 4. Session/Time Confluence ✓
- **London Session:** 6:00 AM – ~9:30 AM Eastern (creates swing highs/lows)
- **New York Session:** 9:30 AM – 4:00 PM Eastern (primary trading window)
- **Strategy:** London high/low swept + aligns with volume profile level = extreme high-confidence entry

### 5. Risk Management ✓
- **Stop Loss:** Just beyond the order block or key volume level (protect capital)
- **Initial Target:** Next major liquidity pool or HVN

---

## Part 4: Trade Management Rules

### Position Entry
1. Confirm all 5 checkpoints above
2. Enter on the ICT signal (OB, FVG, or liquidity sweep)
3. Risk clearly defined: stop just beyond structure

### Profit Taking
**Do NOT take early profits.** This is the edge.
- Hold to the next significant **liquidity zone + HVN confluence**
- Let winners run until the setup breaks or profit target is hit

### Stop Management
- **Initial stop:** Just beyond the order block or key level
- **Trailing stops:** ONLY when price approaches the next major HVN + liquidity zone
- **Exit:** When the trade breaks below/above the original structure on invalid price action

### Position Sizing
- Risk a small % of account per trade (e.g., 1-2%)
- Scale out at major confluences if targeting multiple HVNs
- Aggressive trailing = potential for 5R, 10R+ moves

---

## Part 5: Real-World Setup Examples

### Example 1: 80% Rule Gap Reversal
1. Market opens above yesterday's VAH
2. Pulls back and re-enters the value area
3. **Setup triggers:** Expect 80% probability to reach VAL
4. Entry: As price enters VA and approaches HVN on the way down
5. Stop: Above the entry HVN
6. Target: VAL or next lower HVN

### Example 2: Order Block + POC Confluence
1. Identify a strong order block (last 1H candle before move down)
2. Order block sits exactly on the POC
3. Market retests the OB
4. **Entry:** At the OB candle close or bounce from OB
5. Stop: Below the OB
6. Target: Next HVN below or liquidity zone

### Example 3: London Liquidity + NY Session
1. Mark London session high and low (6:00 AM – 9:30 AM)
2. During NY session, price sweeps the London low
3. That London low sits on a High Volume Node from RTH
4. **Entry:** At the London low as price bounces
5. Stop: Below the low
6. Target: Next major HVN or liquidity above

---

## Part 6: Pre-Market Prep Checklist

Use this template **every morning before market open:**

```
Date: _______________

YESTERDAY'S RTH PROFILE (9:30 AM – 4:00 PM)
- VAH: ___________
- VAL: ___________
- POC: ___________
- Yesterday's close: __________ (Inside/Above/Below VA?)

TODAY'S SETUP
- Today's open: __________ (Inside/Outside VA?)
- Opening price action: [describe]
- Daily bias: [BULLISH / BEARISH / NEUTRAL]
- Confidence: [HIGH / MEDIUM / LOW]

KEY LEVELS TO WATCH
- Liquidity above: __________ (London high, previous highs)
- Liquidity below: __________ (London low, previous lows)
- HVN clusters: __________
- Order blocks: __________

TRADE PLAN
- Only take entries that align with daily bias + volume confirmation
- No trades in LVNs unless as air pockets
- Target confluences only
```

Save in `01 Premarket Prep/` each day.

---

## Part 7: Trade Journal Template

Use this **after each trade:**

```
Date & Time: _______________
Instrument: _____________

SETUP ANALYSIS
- Daily bias: [HOW IT WAS DETERMINED]
- ICT signal: [OB / FVG / LIQUIDITY SWEEP - describe]
- Volume profile level: [HVN / POC / VAH / VAL]
- Why this was high confidence: [confluence factors]

EXECUTION
- Entry price: ___________
- Entry time: ___________
- Stop loss: ___________ (why placed here?)
- Target: ___________ (next liquidity/HVN)
- Risk: ___________

RESULT
- Exit price: ___________
- Exit time: ___________
- Win/Loss: __________ R-multiple: __________
- What went right: ___________
- What went wrong: ___________
- Discipline check: [Did you follow the plan? Y/N]
```

Save in `02 Trade Journal/` with screenshot and annotations.

---

## Part 8: Weekly Review Template

Do this **end of week** to spot patterns:

```
Week of: _______________

OVERALL STATS
- Total trades: ___
- Winners: ___ Losers: ___
- Win rate: ___%
- Biggest win: ___ Biggest loss: ___
- P&L: ___________

MISTAKE ANALYSIS
- Most common mistake: ___________
  - Frequency this week: ___ trades
  - Cost: ___________ pips/points
  - Fix for next week: ___________

- Second most common mistake: ___________
  - Frequency this week: ___ trades
  - Cost: ___________ pips/points
  - Fix for next week: ___________

DISCIPLINE AUDIT
- Did I skip premarket prep? How many times?
- Did I chase entries outside my bias? How many times?
- Did I hold winners to target or took early? Frequency?
- Did I trade in LVNs? How many times?

NEXT WEEK'S FOCUS
- #1 thing to improve: ___________
- Specific action: ___________
- How I'll measure it: ___________
```

---

## Key Principles (The Why)

1. **Volume Profile is the objective truth filter** — It shows where institutions actually traded, removing emotion.
2. **Confluence > Single Signal** — Multiple factors aligning = higher probability.
3. **The 80% Rule is mechanical** — Remove guesswork; when conditions are met, act.
4. **Liquidity + HVN = Target** — Institutions placed orders here; price will reach it.
5. **Patience is the edge** — Most traders take profits early. Hold to the next major level.
6. **Session timing matters** — London creates liquidity; NY exploits it.

---

## Instrument-Specific Notes

### NQ Futures (Your Primary)
- Highly liquid; volume profile works perfectly
- RTH: 9:30 AM – 4:00 PM Eastern
- London: 6:00 AM – 9:30 AM Eastern
- Use 1H, 4H, and 15M timeframes for confluence

### Gold (Your Secondary — Once Personal Strategy Built)
- Same framework applies
- More volatile; watch LVN gaps carefully
- Higher range days = wider VA; adjust targets proportionally

---

## Common Mistakes to Avoid

| Mistake | Why It Kills | Fix |
|---------|-------------|-----|
| Trading without daily bias | No edge; fighting the market | Always run 3-step bias check first |
| Entering in LVNs | Price blasts through; no holding power | Only enter at HVN/POC/VA edge |
| Chasing entries | FOMO kills discipline | Wait for the setup to come to your level |
| Taking profits early | Missing the big moves that fund accounts | Trail to next HVN + liquidity zone |
| Ignoring volume profile | Trading blind; no objective confirmation | Check every entry against volume |
| Trading outside daily bias | Fighting uptrend with shorts, etc. | Respect the mechanical bias |

---

## How This Connects to Your Trading Journey

**The System Solves:**
- Overthinking → Mechanical 3-step daily bias removes emotion
- Fake setups → Volume profile filters out low-probability trades
- Small wins + big losses → Trailing aggressively captures 5R+ moves
- Lack of confidence → Multiple confluences = high-conviction entries

**From PJ's ICT Framework:** This playbook operationalizes order blocks, FVGs, and liquidity within the context of institutional volume trading.

**Next steps:**
1. Run the daily bias 3-step process every morning
2. Log premarket prep in `01 Premarket Prep/`
3. Take only trades with full confluence (all 5 checkpoints)
4. Post-trade review in `02 Trade Journal/`
5. Weekly analysis looking for mistake patterns
6. Iterate on the biggest leak each week in `07 Iteration Logs/`

---

**Created by Claude | Use this as your mechanical rule book. If a trade doesn't fit, don't take it.**
