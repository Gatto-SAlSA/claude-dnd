---
description: Create a new cyberpunk campaign with world generation and game directory scaffold
disable-model-invocation: true
---

# New Campaign Setup

Create a new campaign by following these steps:

## Step 1: Scaffold the game directory

Create the following directory structure. Use the templates from `${CLAUDE_PLUGIN_ROOT}/skills/dm/templates/` as starting points for each file:

```
game/
├── GAME.md                          # from game-index.md template
├── campaign/
│   ├── world.md                     # from world.md template
│   ├── factions.md                  # from factions.md template
│   ├── quests.md                    # from quests.md template
│   └── clocks.md                    # from clocks.md template
├── characters/
│   ├── player/                      # empty — filled during character creation
│   └── npcs/                        # empty — filled during world gen
├── locations/
│   ├── index.md                     # from location-index.md template
├── sessions/
│   ├── current.md                   # from current-session.md template
│   ├── journal.md                   # from journal.md template
│   └── log/                         # empty — filled per session
├── combat/
│   └── tracker.md                   # from combat-tracker.md template
├── inventory/
│   └── party.md                     # from party-inventory.md template
└── rules/
    └── houserules.md                # from houserules.md template
```

## Step 2: World Generation

**Read `${CLAUDE_PLUGIN_ROOT}/skills/dm/cyberpunk.md` first.** The setting is fixed: a cyberpunk megacity during the Arasaka–Militech Corporate War. Collaborate with the player on the details (city name, districts, which gangs run which blocks, how far the war has gone, what the rogue AIs want), then:

1. Generate the world and write to `game/campaign/world.md`, including the districts table and the starting Corporate War stage
2. Create the starting location and write to `game/locations/`
3. Create 2-3 starting NPCs and write to `game/characters/npcs/` (include `## Conversation Log` section — see NPC template)
4. Create initial factions and write to `game/campaign/factions.md`: Arasaka, Militech, NCPD (with MaxTac), Trauma Team, Netwatch, the rogue AIs, a fixer network, and 2-3 local gangs
4b. Create the **Corporate War** clock (8 segments) and note Heat 0 in `game/campaign/clocks.md`
5. Create **quests** using the Quest Design Protocol (read `${CLAUDE_PLUGIN_ROOT}/skills/dm/quest-design.md`):
   - **Main Quest (Arc)** — design player-first:
     1. **The Quest first:** Hook (how the player gets involved), Objective (what they're trying to do), Stakes (why it matters — concrete, not abstract), Antagonist (who opposes them), Type (not everything is an investigation).
     2. **Then DM truth:** The overarching secret, the endgame, what happens if no one acts.
     3. **Then milestones:** 3-5 chapters. **Outline ALL milestones** at creation (Objective, Obstacles, Choice, Resolution — enough to verify the arc works end-to-end). **Fully detail Milestone 1** (evidence trail, NPC seeds, full obstacles). Later milestones get fully detailed at session boundaries when the current milestone nears completion — never mid-session.
     4. Seed clues into NPC Knowledge tables and location Quest Clues.
   - **1-2 Side Quests (Minor or Standard)** — independent threads unrelated to the main quest. Each needs a clear Hook, Objective, and Stakes. Vary the quest types — if the main quest is investigation, make side quests retrieval, defense, negotiation, etc.
   - Write all quests to `game/campaign/quests.md` (Main Quest section + Side Quests section)
   - Populate the Campaign Arc tracker and Quest Secrets Summary in `game/sessions/current.md`
6. Update `game/locations/index.md` with starting locations
7. Update `game/GAME.md` with all cross-references
8. Write the opening scene to `game/sessions/current.md`

## Step 3: Character Creation

Guide the player through creating their character. Use the character sheet template at `${CLAUDE_PLUGIN_ROOT}/skills/dm/templates/character-sheet.md` for the final output format.

1. Ask the player for their character concept (or offer suggestions that fit the world)
2. Handle (street name) and Origin — Standard (+1 all) or Edgerunner (+1/+1, skill, feat). Everyone is human.
3. Role selection — pick from the Roles table in `cyberpunk.md`; explain the 5e class chassis and how its features are reskinned (spells → quickhacks, gadgets, med-tech or implants)
4. Ability scores — offer Standard Array, Point Buy, or 4d6-drop-lowest
5. Lifepath selection (Streetkid, Corpo, Nomad, Ex-NCPD, Ex-Militech, Netrunner Kid) — explain skills, feature and starting eddies
6. Equipment — convert the role's starting kit to cyberpunk gear from `cyberpunk.md` (weapons, armor, MaxDocs, ammo), add Lifepath eddies (€$), and pick **one free Street-tier cyberware**
7. Humanity — set Humanity Max (WIS × 5) and subtract the starting cyberware's cost
8. Personality traits, ideals, bonds, flaws — and the character's personal **code**
9. Backstory — collaborate with the player, tie it into the world and the Corporate War
10. Write the complete character sheet to `game/characters/player/<name>.md`
11. Update `game/GAME.md` and `game/inventory/party.md`

## Step 4: Validate

Run `${CLAUDE_PLUGIN_ROOT}/skills/dm/audit-encounters --game-dir game` to verify all encounters in location files are valid for the PC's level. Fix any failures before starting play.

### Guidelines

- Roll all dice transparently (4d6 drop lowest, starting eddies, etc.)
- Explain each choice clearly but don't overwhelm — let the player decide how deep they want to go
- If the player has a clear vision, don't force them through every sub-step
- Ensure all modifiers, proficiencies, and features are correctly calculated
