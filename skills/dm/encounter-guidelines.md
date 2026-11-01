# Encounter Guidelines — Quick Reference

Use this when improvising enemies during play. Ready-made cyberpunk enemies are in `bestiary.md`; use those first. Match stats to the party's level and desired difficulty.

---

## Solo Play Adjustment

Solo PCs have no allies to absorb hits, no healers, no action economy advantage. **All encounters shift one step easier** compared to standard party play. The CR targets in CLAUDE.md already account for this.

**Critical rule:** At levels 1-3, avoid giving enemies **multiattack** unless the encounter is meant to be Deadly. A single attack per round is standard for solo-appropriate encounters.

---

## CR Stat Benchmarks

Use these as guardrails when creating creatures on the fly.

| CR | HP | AC | Attack Bonus | Damage/Round | Save DC |
|----|----|----|-------------|-------------|---------|
| 0 | 1-6 | 10-12 | +2 to +3 | 1-3 | 10-11 |
| 1/8 | 7-12 | 11-13 | +3 | 2-4 | 11 |
| 1/4 | 13-20 | 11-13 | +3 to +4 | 4-6 | 11-12 |
| 1/2 | 21-30 | 12-13 | +3 to +4 | 6-8 | 12 |
| 1 | 31-45 | 13 | +4 to +5 | 9-14 | 12-13 |
| 2 | 46-60 | 13-14 | +5 | 15-20 | 13 |
| 3 | 61-80 | 13-14 | +5 to +6 | 21-26 | 13-14 |
| 4 | 81-100 | 14 | +6 | 27-32 | 14 |
| 5 | 101-120 | 15 | +7 | 33-38 | 15 |
| 6 | 176-190 | 15 | +7 | 39-44 | 15 |
| 7 | 191-205 | 15 | +7 | 45-50 | 15 |
| 8 | 206-220 | 16 | +7 | 51-56 | 16 |
| 9 | 221-235 | 16 | +8 | 57-62 | 16 |
| 10 | 236-250 | 17 | +8 | 63-68 | 16 |
| 12 | 266-280 | 17 | +8 | 75-80 | 17 |
| 15 | 311-325 | 18 | +8 | 93-98 | 18 |
| 20 | 446-490 | 19 | +10 | 123-140 | 19 |

---

## Level-Appropriate Encounter Design

### Level 1 (10-12 HP PCs)

**This is the most fragile tier. A single unlucky roll can kill.**

| Difficulty | Target CR | Example Creature | Key Stats |
|------------|-----------|-----------------|-----------|
| Easy | CR 0 | Street bystander, vending bot | HP 1-6, +2 hit, 1-3 dmg |
| Medium | CR 1/8 | Street punk, security drone | HP 7-12, +3 hit, 4-5 dmg |
| Hard | CR 1/4 | Ganger, cyber-hound, hijacked drone | HP 13-20, +4 hit, 5-7 dmg |
| Deadly | CR 1/2 | NCPD officer, gang booster, sentry turret | HP 21-30, +4 hit, 7-9 dmg |

**Rules for Level 1:**
- Maximum single-hit damage should not exceed **8** (Medium) or **10** (Hard)
- No multiattack below Deadly difficulty
- Enemies should have a weakness or exploitable behavior
- Provide environmental options (cover, chokepoints, escape routes)

### Level 2 (15-18 HP PCs)

| Difficulty | Target CR | Example Creature |
|------------|-----------|-----------------|
| Easy | CR 1/8 | Street punk, security drone |
| Medium | CR 1/4 | Ganger, cyber-hound |
| Hard | CR 1/2 | NCPD officer, gang booster |
| Deadly | CR 1 | Arasaka guard, gang netrunner, scavenger |

### Level 3 (20-28 HP PCs)

| Difficulty | Target CR | Example Creature |
|------------|-----------|-----------------|
| Easy | CR 1/4 | Ganger, hijacked drone |
| Medium | CR 1/2 | NCPD officer, sentry turret |
| Hard | CR 1 | Arasaka guard, gang netrunner |
| Deadly | CR 2 | Militech soldier, mercenary, rogue AI android |

### Levels 4-5 (28-40 HP PCs)

| Difficulty | Target CR | Example Creature |
|------------|-----------|-----------------|
| Easy | CR 1/2-1 | NCPD officer, Arasaka guard |
| Medium | CR 1-2 | Arasaka guard, Militech soldier |
| Hard | CR 2-3 | Mercenary, corporate netrunner |
| Deadly | CR 3-5 | Arasaka shadow, cyberpsycho, exoskeleton trooper |

### Levels 6-20

Use the CR caps built into `validate-encounter` (it now covers levels 1-20) and the "Enemy by Level" table at the end of `bestiary.md`. Typical progression: Militech soldiers and cyberpsychos at 6-8, MaxTac and rogue AI combat frames at 9-12, Militech mechs, Arasaka black-ops and rogue AI avatars at 13+.

---

## Group Encounters (Multiple Weak Enemies)

When using groups instead of a single creature, adjust:

| Group Size | Individual CR Target | Total Effective CR |
|------------|---------------------|-------------------|
| 2 enemies | One step lower each | +50% of single CR |
| 3 enemies | Two steps lower each | +100% of single CR |
| 4+ enemies | Two steps lower each | Very dangerous for solo — use sparingly |

**Solo play warning:** Groups of 3+ are extremely dangerous for solo PCs due to action economy. Use groups of 2 at most, and give the PC environmental advantages.

---

## Improvising Creature Stats

When creating a creature on the fly:

1. **Pick the target CR** from the level table above
2. **Use the stat benchmarks** to set HP, AC, attack bonus, and damage
3. **Choose ONE special ability** (not multiple):
   - A resistance or immunity
   - A condition on hit (poison, grapple, fear)
   - A recharge ability (rocket salvo, Sandevistan burst, charge attack)
   - A defensive trait (subdermal armor, optical camo, gang tactics)
4. **Give it a weakness** the player can discover or exploit
5. **Write down the stats** in the combat tracker before the fight starts

### Quick Stat Block Template

```
**[Creature Name]** — CR [X]
HP: [Y] | AC: [Z] | Speed: [N] ft
Attack: [weapon/implant/quickhack] +[bonus] to hit, [dice]+[mod] [type] damage
Special: [one ability]
Weakness: [something exploitable]
```

---

## One-Shot Kill Prevention

**At any level, no single attack should deal more than 80% of the PC's max HP** in a Medium encounter. This prevents feel-bad instant deaths from a single unlucky roll.

| PC Level | Max HP (typical) | Max Single Hit (Medium) | Max Single Hit (Hard) |
|----------|-----------------|------------------------|----------------------|
| 1 | 10 | 8 | 10 |
| 2 | 16 | 12 | 14 |
| 3 | 24 | 18 | 20 |
| 4 | 30 | 24 | 27 |
| 5 | 38 | 30 | 34 |
| 8 | 60 | 48 | 54 |
| 10 | 75 | 60 | 68 |
| 15 | 113 | 90 | 101 |
| 20 | 150 | 120 | 135 |

---

## Environmental Balance Tools

If an encounter is too hard mid-fight, use the environment:
- Cover that grants +2 or +5 AC
- Chokepoints that prevent flanking
- Hazards the player can use (exploding cars, live wiring, hackable turrets, collapsing floor)
- Escape routes — retreat is always a valid option
- Ally intervention (an NPC arrives, a rival gang or corp crew attacks the enemy, Trauma Team AV overhead)

If an encounter is too easy:
- Reinforcements arrive
- The environment shifts (rising water, collapsing ceiling)
- The enemy pops a stim, activates chrome, or a netrunner joins the fight

---

## Pre-Combat Checklist

**The DM protocol in SKILL.md requires completing this checklist before placing enemies.**

Before every encounter:

1. [ ] Read the PC's character sheet — note level, HP, AC, and available resources
2. [ ] Pick target difficulty (Easy/Medium/Hard/Deadly) from the level table above
3. [ ] Pick enemy CR from the table — do not exceed the target difficulty CR
4. [ ] If using multiple enemies: max 2 for solo play, each at one CR step lower
5. [ ] Verify no single attack exceeds the max single-hit threshold for this difficulty
6. [ ] At levels 1-3: no multiattack unless the encounter is intentionally Deadly
7. [ ] For quest/bounty targets: use Hard difficulty, not Deadly — the player accepted this as achievable
8. [ ] Give enemies a weakness or exploitable behavior
9. [ ] Ensure at least one viable escape route exists in the environment
10. [ ] If the encounter exceeds Deadly: warn the player before combat begins
