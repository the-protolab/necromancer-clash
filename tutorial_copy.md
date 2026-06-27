# Tutorial Copy — Necromancer's Clash

Copy ideas for a 3-step tutorial image. ~5 variants per step.
Voice: short, glanceable, strategy-first (each line should imply a *decision*, not just an instruction).

Ability legend (for any panel that shows the blocks):
`⚔️ ATTACK · ❤️ HEALTH · 🛡️ SHIELD · ❄️ ICE` — **type = what you do, length = how strong.**

---

## Step 1 — Make your move (action + choice)

Teaches the verb AND that matching is a decision, not just "attack".

1. **"Drag through 3+ matching blocks. The type is your move — the length is your power."**
2. **"Pick your play: link 3+ of a kind to attack, heal, shield, or freeze."**
3. **"Match 3+ blocks. Bigger chains hit harder."**
4. **"Every match is a choice — *what* you cast and *how hard*."**
5. **"Trace a path of 3+ same blocks. More blocks = more power."**

---

## Step 2 — You fight your ghost (the hook, as strategy)

Teaches the identity: the opponent is your last winning run — predictable *because* it's you.

1. **"Win once and your run becomes the enemy. From round 2, you face your ghost."**
2. **"Your ghost replays your last victory — move for move. Don't lose to yourself."**
3. **"The enemy is you, so it's predictable. Read its move, then counter."**
4. **"Beat the wraith and a ghost of your run rises. Now out-play your past self."**
5. **"Every move you make now, you'll have to beat later. Choose like it counts."**

---

## Step 3 — Outlast the loop (depth / the wraparound)

Teaches the wraparound: if your run lasts more rounds than the ghost has recorded moves,
the ghost loops back to move one and repeats. Keep it **simple and literal** — plain "if X, then Y".
No buzzwords (no "recycle / exploit / tricks / predict and punish"). Just state the rule.

1. **"If your run lasts longer than your last one, the ghost starts its moves over from the beginning."**
2. **"If you survive more rounds than last time, the ghost runs out of moves and repeats them from the start."**
3. **"If this run is longer than your last, the ghost loops back to its first move and repeats."**
4. **"If you outlast your previous run, the ghost replays the same moves again, in the same order."**
5. **"If the fight goes longer than your last run, the ghost repeats — same moves, same order."**

---

## Bonus — Just-in-time loop hint (recommended over putting Step 3 in the image)

Design note: Step 3 is *depth*, not onboarding. It answers a question a new player hasn't asked yet.
Stronger as an in-game message the first time the loop actually happens
(fires on the first wrap: `ghostActionIndex >= activeGhostActions.length`).
It lands at peak relevance and earns an "aha" instead of stealing attention up front.

1. **"Your ghost ran out of new moves — it's repeating. You've seen this."**
2. **"Loop! The ghost is replaying its run again. Predict and punish."**
3. **"You outlasted your last run — the ghost recycles from move one."**
4. **"Déjà vu? The ghost is repeating itself now."**
5. **"No new tricks — the ghost loops. Counter what you already know."**

---

## Suggested combos

- **Tightest (2 panels + JIT):** Step 1 (v1) + Step 2 (v2), drop Step 3 into the just-in-time hint.
- **Full 3-panel image:** Step 1 (v1) + Step 2 (v3, most strategic) + Step 3 (v1, advantage framing).
- **Punchiest:** Step 1 (v3) + Step 2 (v2) + Step 3 (v3).
