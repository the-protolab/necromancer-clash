# Necromancer's Clash — Feedback & Timing (TLDR)

> Each bullet = one moment in the game that needs clearer feedback / better timing.
> The combat *rules* are correct; this pass is purely about the player **understanding**
> what happened. P1 = explicitly requested.

- **[P1] Frozen (ice) has no clear feedback.** Today only a tiny "Cancel" chip shows.
  → Dynamic English message at the moment the cancelled action *would* fire, e.g.
  `"Frozen! Your Sword won't go off."` / `"Your Ghost is frozen — Heal cancelled."`,
  plus an ice-blue overlay on the frozen combatant held for ~600ms.

- **[P1] Shield timing reads as "nothing happened".** The shield rises and disappears
  (~620ms) *before* the attacker's projectile is even fired. → New model: the shield
  rises **first, with priority**, and **stays up**; the attacker **still fires**; on
  impact the shield **shatters/absorbs** (burst) and drops — reads as "the shot hit the
  shield". Message: `"Blocked by [Name]'s Shield!"`.

- **[P2] No damage / heal numbers.** The HP bar moves but there's no `-15` / `+15`.
  → Floating number on the target at impact (red for damage) and on heal (pink/green),
  rising and fading; scales with the number of blocks matched.

- **[P2] Intent reveal is too fast.** After a match both actions resolve almost instantly;
  hard to read "me vs ghost". → Reveal beat: both action cards "pop"/highlight with a
  short pause (~450ms) and a matchup message `"You: X  vs  [Name]: Y"` before effects fire.

- **[P2] Simultaneous resolution blurs cause→effect.** Both sides' effects fire together.
  → Subtle stagger: the target's reaction lands just after the projectile impact, and the
  states (shield up / frozen) appear *before* the consequence.

- **[P2] Blocked attack isn't legible.** Your sword on the enemy shield only shows a
  generic burst. → Reuse the shield-shatter (P1) + a "Blocked" message.

- **[P3] Reinforce the "fighting yourself" theme.** On run 2+, the moment the ghost acts
  doesn't say it's your past. → When the opponent is the real ghost, frame the reveal as
  an echo: `"Your echo: Sword x3"`.

- **[P3] Wasted heal at full HP.** Healing at max gives no response. → Subtle
  `"HP already full"` note (no floating number) when the heal changes nothing.
