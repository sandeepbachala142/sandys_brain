---
tags: [yush, absorption, orderflow, playbook, reference]
created: 2026-05-11
source: Yush Capital — "Spotting Absorption with Big Trades & Delta Profile"
---

# (C) Yush — Absorption Playbook

---

## The One-Line Definition

> **Absorption** = a big aggressive trade prints (large bubble) and the delta profile lights up at that level — but price refuses to follow. Someone passive ate the order. The next move usually goes *against* the side that just got eaten.

---

## Mental Model

> *"Picture a wall and someone hurling baseballs at it. Each ball is a market order. The wall is a stack of resting limit orders. If the wall doesn't crack despite a barrage of balls, you've just witnessed absorption. The thrower — exhausted and out of inventory — usually walks away. That walk-away is the move you trade."*

---

## The Two Tools

### 1. Big-Trade Bubbles
Circles drawn on the chart at the price and time where a large aggressive order printed.
- 🟢 **Green bubble** = aggressive BUY (market order lifted the offer)
- 🔴 **Red bubble** = aggressive SELL (market order hit the bid)
- **Number** = exact contract count
- **Size** = scales with number of contracts
- Set a minimum threshold (e.g. 100 contracts on ES) so chart only lights up when something meaningful happens

### 2. Delta Profile (bars on the right)
Net delta at every price level traded during the visible window.
- Each row = one price level
- Bar length = magnitude of the delta
- 🟢 Green bar = positive delta (more aggressive buying than selling at that price)
- 🔴 Red bar = negative delta (more aggressive selling than buying)
- Number = exact net delta in contracts

### The Key Insight
> *"Either tool alone is noise. Together they tell the whole story: the bubble shows how hard one side hit the level, the profile shows the net result of the fight at that level, and the candles show whether price actually moved as a result. When the first two scream and the third yawns, that's absorption."*

---

## The Four Conditions — The Absorption Signature

All four must line up. This is the entire discipline.

**Condition 1 — A big bubble fires at the level**
An unusually large aggressive trade — well above your threshold for the instrument. Multiple bubbles stacked at the same level count as one event.

**Condition 2 — Delta profile confirms the aggression**
The bar at that exact price shows heavy delta matching the bubble color. Big red bubble → heavily negative delta row. Big green bubble → heavily positive delta row.

**Condition 3 — Price refuses to follow**
Despite all that aggression, price doesn't extend. The candle wicks the level and closes back through, or barely moves at all.

**Condition 4 — A reversal or stall follows shortly after**
The aggressors run out of inventory. The passive side starts pushing back, often within a few bars.

> **THREE OUT OF FOUR IS A QUESTION. FOUR OUT OF FOUR IS A SIGNAL.**
> Single-condition matches happen all day and mean nothing. The edge comes from waiting for the full stack to line up. Discipline here is the entire skill.

---

## Bullish Absorption — Full Walkthrough

**Setup:** NQ sells off into prior session low at 28,650. Sellers aggressive on the tape. Then:

- **Big bubble:** 367-contract red bubble fires at 28,650 — major player dumping into the prior low
- **Delta profile:** row at 28,652 shows **-394** — by far the heaviest negative delta in the visible window
- **Price action:** despite all that selling, price wicked down, DIDN'T break the level, closed back up green
- **Confirmation:** the very next bubble is a small green print above — buyers stepping in once seller's inventory was gone

Every one of those 367 sells was filled by a passive buyer who didn't budge. That passive buyer IS the absorption.

**Trade:**
- **Entry:** Reclaim of the mid of the absorption bar, OR break of bar high
- **Stop:** 2-3 ticks below the absorption low (28,645)
- **Target:** First liquidity pocket above — overhead VAL or prior swing. Manage at +1R.
- **Invalidation:** Second test where another big red bubble fires AND price ticks through the absorption low → the absorbing bid was lifted → exit immediately

---

## Bearish Absorption — Full Walkthrough

**Setup:** ES rallies into prior session high at 25,690. Buyers chasing aggressively. Then:

- **Big bubbles:** TWO 250-contract green bubbles stacked at 25,690 = 500 contracts of aggressive buying at the prior high
- **Delta profile:** +448 at the level — massive net buying pressure concentrated in one tick
- **Price action:** tagged 25,690, didn't advance, closed back down. All that buy aggression got nothing.
- **Confirmation:** next bar prints a small red bubble below — buyers giving up, sellers returning

> *"When you see multiple bubbles stacked at the same level AND the delta profile shows the heaviest reading in the window, that's the strongest version of the signal. Single bubbles can be one-off events; stacked bubbles + extreme profile = a passive iceberg sitting there waiting to be hit. That iceberg defines the level."*

**Trade:**
- **Entry:** Loss of mid of the absorption bar, OR break of bar low
- **Stop:** 1-2 ticks above the absorption high
- **Target:** Underside VAH / nearest market-generated level / prior swing
- **Invalidation:** Another big green bubble retests AND price ticks through the absorption high

---

## The Combo Matrix — Reading Bubble + Profile + Price Together

| Bubble | Profile at Level | Price | Read |
|--------|-----------------|-------|------|
| Big red bubble at low | Heavy negative delta | **Holds** | ✅ Bullish absorption |
| Big green bubble at high | Heavy positive delta | **Stalls** | ✅ Bearish absorption |
| Big bubble (any side) | Heavy delta same side | **Breaks through** | Continuation — pass |
| Big bubble at level | Profile is flat | Holds | Suspect — wait for more confirmation |
| No bubbles | Heavy delta on profile | Anything | Passive flow only — no edge |
| Bubbles on both sides | Profile near zero | Choppy | Two-way fight — stay out |

### The 'Profile is Flat' Trap
If a giant bubble fires but the delta profile barely registers at that level — be skeptical. Real absorption requires **sustained pressure** that shows up on the profile, not a single drive-by print.

---

## Filters — When to Trust It

✅ Happens at a **known structural level** — VAH, VAL, LVN, prior session high/low, opening range
✅ Comes **after a stretched move** — the further price has extended, the more meaningful absorption becomes
✅ **Multiple bubbles stack** at same level — fingerprint of an iceberg order quietly refilling
✅ Level delta is **at least 2-3x the size** of any other delta row in the visible window (relative size matters more than absolute)

## Filters — When to Be Skeptical

❌ Happens **mid-range with no level nearby** — price has nothing to lean against
❌ Volume looks heavy but is actually **average for time of day** (open, close, news minutes)
❌ **No follow-through within 2-3 bars** — real absorption produces a reaction quickly
❌ Bubble fires but **delta profile barely shows it**

---

## Trade Plan Template

| Step | Bullish Absorption | Bearish Absorption |
|------|-------------------|-------------------|
| **Trigger** | Big red bubble + heavy negative delta at support, price holds | Big green bubble + heavy positive delta at resistance, price stalls |
| **Confirmation** | Next bar holds; small green bubble appears; offers pull back | Next bar holds; small red bubble appears; bids pull back |
| **Entry** | Reclaim of mid of absorption bar OR break of bar high | Loss of mid of absorption bar OR break of bar low |
| **Stop** | 1-2 ticks below absorption low | 1-2 ticks above absorption high |
| **First Target** | Overhead VAL / nearest market-generated level / prior swing | Underside VAH / nearest level / prior swing |
| **Invalidation** | Another big red bubble retests AND price ticks through | Another big green bubble retests AND price ticks through |

---

## Pre-Trade Checklist — 60 Seconds

Before every absorption trade, answer these:

- [ ] **1.** Is there a known level nearby? (VAH/VAL/LVN/prior session high/low/opening range)
- [ ] **2.** Is there a big bubble at the level?
- [ ] **3.** Does the delta profile row show **2-3x** the average magnitude in the visible window?
- [ ] **4.** Did price **fail to extend** through the level?
- [ ] **5.** Is my stop < 1.5x ATR(5)?

**4-5 YES → Take the trade**
**2 or fewer YES → Pass and wait**

---

## Common Mistakes That Kill the Edge

❌ **Trading bubbles without a level** — no structure = no edge. The level gives the passive side a reason to defend.
❌ **Trusting the bubble alone** — a single big print without supporting delta-profile depth is just one trade.
❌ **Trusting the profile alone** — heavy delta with no big bubble = volume from many small participants, not a committed aggressor. Less predictive.
❌ **Front-running the read** — entering inside the absorption bar before it closes is gambling on a snapshot.
❌ **Holding past the first liquidity pocket** without a reason — absorption trades are mean-reversion in their first leg.

---

## Glossary

| Term | Definition |
|------|-----------|
| Absorption | Aggressive flow into a level being eaten by passive limit orders, with little or no price movement |
| Aggressor | The party that crosses the spread with a market order |
| Big-trade bubble | A circle on the chart showing a single large aggressive trade. Color = side, size = contracts |
| Delta | Ask volume minus bid volume; positive = net buying aggression, negative = net selling aggression |
| Delta profile | Net delta plotted per price level over a window, shown as horizontal bars on the right edge |
| Iceberg order | A large limit order that displays only a small size and auto-replenishes as it fills. Common cause of stacked-bubble absorption |
| Level delta | The single delta value at one specific price row on the delta profile |
| Liquidity pocket | An area of the chart with little resting volume where price tends to travel quickly |
| Low volume node | A price where very little volume traded — price tends to slice through these quickly |
| Passive order | A resting limit order waiting in the book |
| Stacked bubbles | Multiple big-trade bubbles printing at the same or nearly the same price — strong signature of an iceberg defending a level |
| Trapped traders | Aggressors who entered late and find themselves offside as the move reverses |
| Value Area | The price range where ~70% of a session's volume traded. Edges (VAH/VAL) are mean-reversion magnets |
