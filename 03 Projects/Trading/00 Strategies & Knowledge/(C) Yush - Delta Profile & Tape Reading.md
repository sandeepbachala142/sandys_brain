---
tags: [yush, delta, orderflow, tape-reading, absorption, trapped-traders]
created: 2026-05-07
source: Yush PDF (absorption_TrappedSelling.pdf) + Discord commentary
---

# (C) Yush — Delta Profile & Tape Reading

---

## The Three Layers of the Tape

Every setup Yush trades is read through three simultaneous lenses:

| Layer | Tool | Question It Answers |
|-------|------|-------------------|
| 1 | Big Trades (Bubbles) | Who got aggressive, when, and how big? |
| 2 | Volume Profile | Where was the real battleground? |
| 3 | Delta Volume Profile | Who actually WON the auction at each price? |

> *"Big trades tell you who got aggressive and when. Volume profile tells you where the real battleground is. Delta volume profile tells you which side actually won the auction at that price."*

---

## Layer 1 — Big Trades (The Bubbles)

Each bubble = a **single large trade** that crossed the spread with size. Not cumulative delta. Not a profile bar. One print of aggression.

| Bubble | What It Means |
|--------|--------------|
| 🟢 GREEN | Large buy order executed **at the offer**. Aggressive buyer paid up to take liquidity. They wanted in immediately. |
| 🔴 RED | Large sell order executed **at the bid**. Aggressive seller hit the bid to get filled. They wanted out (or short) immediately. |
| Number | Contract size of that single print |

**Key rule:** Big trades are real-time signals on their own but mean little without context. The read comes from combining them with the volume structure they landed in AND the delta imbalance they built.

**Yush's terms for big trades:**
- **"Tape bombs"** — sudden large prints at key levels signaling institutional activity
- **"Passive buyer/seller"** — large resting limit orders that absorb aggressive flow
- **"Iceberg order"** — hidden large order that doesn't show full size; only visible by watching fills at a level

---

## Layer 2 — Volume Profile (Where)

Volume Profile = **direction-blind**. Shows total volume at each price — buyers AND sellers combined.

- **HVN (High Volume Node)** = real battleground. Both edges identifiable. Price slows here.
- **LVN (Low Volume Node)** = thin pass-through. Price traveled fast. No resting orders. No friction.

**Critical insight:** A high-volume node could be 90% buying OR 90% selling and look identical on a volume profile. You cannot tell who won from volume alone. That's what Layer 3 is for.

---

## Layer 3 — Delta Volume Profile (Who Won)

Delta Volume Profile = Volume Profile **split by direction**.

Net delta at each price = ask volume minus bid volume.

| Color | Meaning |
|-------|---------|
| 🔵 Blue/Purple | Positive delta — aggressive buyers won the auction at this price |
| 🔴 Red/Pink | Negative delta — aggressive sellers won the auction at this price |
| Number | Size of the imbalance in contracts |

**This is the tool that separates information from noise.** Same price level, same volume — but was it buyers or sellers that controlled it? Delta answers that.

---

## Absorption — The Core Tell

**Definition:** Large delta imbalance at a price level, but price **does not move** in the direction of that flow.

> *"Over a thousand contracts of net sell aggression went into that level, and the market did not break lower — it returned to where the selling started. That is absorption. Passive buyers sitting on the bid soaked up every market sell that came through. The sellers got their fills. They did not get the move."*

### Bullish Absorption (at lows)
- Strong **negative** delta (heavy selling)
- Price **holds** — does not extend lower
- Big red bubbles printing but price doesn't break
- Passive buyers (large limit orders, often iceberg-style) absorbing every sell
- → Trapped sellers forming

### Bearish Absorption (at highs)
- Strong **positive** delta (heavy buying)
- Price **stalls** — does not extend higher
- Big green bubbles printing but price doesn't break out
- Passive sellers absorbing every buy
- → Trapped buyers forming

**Yush's tell in real time:** *"lot of buying but not going up"* / *"lot of selling but not going down"* — this is absorption.

---

## The Trapped Seller / Trapped Buyer Mechanic

### Trapped Sellers (bullish setup)

**Sequence:**
1. Large negative delta cluster forms at a level (e.g. -1,182 at 7338)
2. Big red prints confirm: sellers hit the bid hard (563 red, 984 red, 582 red)
3. Price returns to where selling started — doesn't break lower
4. That is absorption confirmed
5. Positive delta starts building ABOVE the trapped zone (+90, +222, +313, +643)
6. Fresh aggressive buyers turn on — they flip the tape
7. Trapped sellers are now offside → they MUST cover → forced to buy
8. Rally fires

### Trapped Buyers (bearish setup)
- Strong positive delta into resistance
- Breakout above highs fails
- Price snaps back below level
- Delta flips negative quickly
- Buyers chased highs → sellers absorbed → reversal

---

## Two Flows, Same Direction — Why These Moves Are Impulsive

A normal rally has **Flow 01 only** (willing buyers paying up). That's grindy.

A rally from a trapped-seller zone has **Flow 01 AND Flow 02**:

| Flow | What It Is | Why It Matters |
|------|-----------|----------------|
| Flow 01 | New aggressive buying — fresh longs lifting the offer | Adds upward pressure tick by tick |
| Flow 02 | Trapped shorts covering — FORCED buying | Their stops become buy orders. Those buy orders trigger more stops. Feedback loop. |

> *"This is the asymmetry. Flow 02 is forced. Trapped shorts do not get to wait for a better price. Take the loss now or take a bigger one later."*

This is why continuation moves out of absorption zones are **impulsive and low-pullback** — two flows pushing the same direction.

---

## The Re-Trap Inside the LVN

After the initial move fires, price pulls back. This is where the LVN model fires again:

1. Price pulls back into the LVN (thin zone above the original cluster)
2. Late sellers step in — they see a pullback and want to short
3. But they are stepping into an LVN — thin structure, no real volume shelf, no defended delta
4. The bid steps right back — nothing beneath the sellers structurally
5. They immediately become the **next trapped pool**
6. Their forced covering powers the next extension

> *"Aggressive sellers stepping into an LVN have nothing structural beneath them. The bid steps right back, and they immediately become the next trapped pool."*

---

## How the Setup FAILS — Invalidation Signals

The entire thesis lives or dies on the **no follow-through** condition:

❌ **Big red print DOES produce a lower low** → not absorption, that is real supply. Delta cluster keeps growing. Stand aside or flip bias.

❌ **Price slices back through the delta pivot on heavy two-sided rotation** → buyers who turned on get tapped out. Now they are the trapped pool. Fuel reverses.

❌ **Positive delta never builds above the trap** → only short-covering, no new buyers. Rally will fail on first real test of supply.

---

## Reading Absorption in Real Time — The Checklist

When at a key level, watch for:

- [ ] Big prints (bubbles) firing at the level
- [ ] Delta is heavy in one direction (large negative or positive)
- [ ] Price **not** following through in that direction
- [ ] Price holds or drifts back toward the level
- [ ] Delta starts flipping (negative → positive, or positive → negative)
- [ ] New aggressive flow fires in the opposite direction

When all of these line up → you're watching absorption → the trap is forming → next move is coming.

---

## Initiative vs Absorption — The Key Distinction

**Initiative Buying (real move):**
- Strong positive delta
- Price moves UP easily with little overlap
- Thin pullbacks
- Delta increases WITH price
- Volume expands on breaks
- Seen at: breaking highs/lows, leaving value areas, coming off LVNs

**Absorption (trap forming):**
- Strong delta in one direction
- Price does NOT follow through
- Heavy overlap / rotations
- Increasing delta, stagnant price
- → This becomes a trapped pool

**Signs initiative is FAILING:**
- Strong delta but no follow-through
- Heavy overlap / rotations
- Increasing delta, stagnant price
→ This is the moment to look for the opposing entry

---

## Yush's Real-Time Language for These Concepts

| What He Says | What It Means |
|-------------|--------------|
| "lot of buying but not going up" | Absorption — buyers trapped |
| "lot of selling but not going down" | Absorption — sellers trapped |
| "tape bombs at the spot" | Large prints at key level — pay attention |
| "passive seller at X" | Large resting sell limit order — price will struggle to get through |
| "passive buyer at X" | Large resting buy limit order — price will find support |
| "huge delta cluster" | Heavy one-sided flow accumulated at a price |
| "1k positive delta but price not moving" | Classic absorption tell |
| "buyers trapped above" | LAF setup forming — buyers who chased the high are offside |
| "sellers trapped now" | LBF setup resolving — short covering will fuel rally |
| "watch for acceleration under" | If price breaks the level cleanly, should accelerate — if it doesn't, thesis wrong |
| "totally random right?" | Sarcastic — pointing out the non-random nature of institutional flow |
