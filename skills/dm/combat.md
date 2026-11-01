# Combat Flow

## Initiating Combat
1. Determine surprise (if applicable)
2. Roll initiative for all combatants: `d20(<roll>) + <DEX mod> = <total>`
3. Create/update `game/combat/tracker.md` with initiative order, HP, AC, conditions
4. Announce initiative order to the player

## Each Round
1. Process combatants in initiative order (highest to lowest)
2. For the player: present the situation, **then ask for their action and wait**. Never choose the player's action, quickhack, or target — even if the choice seems obvious. Each turn is a decision point.
3. For NPCs/monsters: determine their action based on personality/tactics from their `.md` file
4. Resolve all attacks, quickhacks, cyberware and abilities with transparent dice rolls
5. **Narrate first, then show mechanics.** Describe what happens in the fiction (the muzzle flash, the blade, the sparks off chrome), then present the mechanical results (damage, HP changes, conditions). The player should experience the story before the spreadsheet.
6. Update `game/combat/tracker.md` after each round

## Ending Combat
1. Narrate the outcome
2. Calculate XP using `${CLAUDE_SKILL_DIR}/calc-xp` — never calculate XP manually:
   ```
   ${CLAUDE_SKILL_DIR}/calc-xp --level <PC level> --current-xp <current XP> <CR> <CR> ...
   ```
3. Archive the combat to the session log
4. Clear `game/combat/tracker.md` (reset to "No active combat")
5. Update character sheet (HP, RAM, ammo, cyberware uses, Humanity changes)
6. Update `game/inventory/party.md` with any loot
7. Run a full state checkpoint

## Combat Rules (5e RAW)
- Actions: Attack, Run a Quickhack, Breach Protocol, Reload, Dash, Disengage, Dodge, Help, Hide, Ready, Search, Use an Object
- Bonus actions: only if a feature/spell grants one
- Reactions: one per round (resets at start of your turn)
- Movement: can split before/after actions
- Opportunity attacks: when leaving a hostile creature's reach without Disengaging
- Concentration (sustained quickhacks and gadgets): CON save (DC 10 or half damage, whichever is higher) when taking damage
- Death saves: d20 at start of each turn when at 0 HP; 10+ = success, 9- = failure; nat 20 = regain 1 HP; nat 1 = 2 failures

## Cyberpunk Combat Rules

See `${CLAUDE_SKILL_DIR}/cyberpunk.md` for full weapon, cyberware and netrunning rules.

- **Ammo & Reload:** Track magazines in the combat tracker. Reload is a bonus action (an action with no free hand). An empty gun clicks.
- **Cover is everything:** Half cover +2 AC, three-quarters +5. Smart weapons with a Smart Link ignore both; tech weapons can charge to shoot through cover at disadvantage.
- **Burst fire:** 10 rounds; each creature in a 10-ft cube makes a DC 15 DEX save or takes the weapon's damage.
- **Called shots:** −5 to hit to target a specific part (an AI uplink, a mech leg, an exo power cell). Enemy weaknesses in `bestiary.md` tell you when this matters.
- **Quickhacks:** Need line of sight or a networked device; the target must have chrome or be a machine. Breach first to give enemies −2 on saves.
- **EMP:** Doubles lightning damage against machines; chromed creatures make a DC 13 CON save or their active cyberware is offline until the end of their next turn.
- **Non-lethal:** Melee and stun weapons can knock out instead of kill. Bodies left alive matter for Heat and reputation.
- **Heat:** Loud public fights, dead cops and live witnesses raise Heat (see `cyberpunk.md`). Note Heat changes in `current.md`.
- **Humanity check:** If the PC is at the Edge (Humanity 25% or less) and drops below half HP or rolls a nat 1, call for the DC 13 WIS save.
