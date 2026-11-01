# Cyberpunk 5e Campaign Engine

This project is a cyberpunk game engine plugin (D&D 5e rules) for Claude Code. All game state lives in markdown files under `game/`.

## Skills

- `skills/dm/` — Game Master engine for running cyberpunk campaigns on 5e rules
  - `cyberpunk.md` — setting rules (eddies, cyberware, Humanity, netrunning, gear, clocks)
  - `bestiary.md` — enemy stat blocks

## Commands

- `commands/new-campaign.md` — Create a new campaign
- `commands/start-session.md` — Resume a campaign session
- `commands/add-quest.md` — Add new quests to the campaign (accepts count argument)
- `commands/save.md` — Save current progress
- `commands/end-session.md` — End the session and save
