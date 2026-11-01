# Cyberpunk Bestiary

**Use these stat blocks instead of SRD monsters.** Every block follows the CR benchmarks in `encounter-guidelines.md`, so `validate-encounter` and `calc-xp` work unchanged. Use the slug in **bold-code** as the `name` in `name:CR` (e.g., `ganger:1/4`).

NPC weapons are already factored in. A ganger's "cheap pistol" hits for less than a PC's pistol on purpose.

Reskin freely: a `ganger` can be any gang's colors. Arasaka and Militech troops are interchangeable with smaller corp security at the same CR.

**Machines** (drones, turrets, androids, frames, mechs) are immune to poison, psychic, charmed, frightened and poisoned, and are **vulnerable to EMP**: lightning damage from EMP sources is doubled. Rogue AIs can be quickhacked like any networked target.

---

## CR 0-1/8: The Street

**Street Bystander** `bystander:0`. The random person on the street.
HP 4 | AC 10 | Speed 30 ft
Fists +2, 1d2 bludgeoning.
*Behavior:* Runs, screams, films you, calls NCPD (+1 Heat if you hurt them).
*Weakness:* Anything. Intimidation DC 8 makes them flee.

**Street Punk** `street-punk:1/8`. A random guy with a knife and a bad night.
HP 9 | AC 12 (jacket) | Speed 30 ft
Knife +3, 1d4+1 piercing.
*Special:* **Cheap Shot.** Advantage on the first attack if the target hasn't acted yet.
*Weakness:* Flees below half HP. DC 10 Intimidation ends the fight.

**Security Drone** `security-drone:1/8`. Small flying corporate or NCPD eye.
HP 10 | AC 13 | Speed fly 40 ft | Machine
Taser +3 (range 30 ft), 1d4+1 lightning.
*Special:* **Uplink.** Everything it sees is streamed to its owner; while it lives, alarms are raised.
*Weakness:* EMP vulnerable. Breach DC 12 turns it off.

---

## CR 1/4

**Ganger** `ganger:1/4`. Gang soldier with cheap chrome and a cheaper gun.
HP 16 | AC 12 | Speed 30 ft
Cheap pistol +4 (range 40/120), 1d6+1 piercing; or machete +4, 1d6+1 slashing.
*Special:* **Gang Colors.** Advantage on attacks against a target another ganger hit this round.
*Weakness:* Poor cover discipline: always only half cover. Morale breaks if the leader falls.

**Cyber-Hound** `cyber-hound:1/4`. Guard dog with chromed jaw and optic.
HP 15 | AC 12 | Speed 40 ft
Bite +4, 1d6+2 piercing; on hit, DC 11 STR save or knocked prone.
*Special:* Keen smell and thermal optic: advantage on Perception.
*Weakness:* Ultrasonic emitter or a food lure (Driving/WIS DC 12) distracts it.

**Hijacked Drone** `rogue-drone:1/4`. A delivery or maintenance drone puppeted by a rogue AI.
HP 14 | AC 13 | Speed fly 40 ft | Machine
Arc spark +4 (range 30 ft), 1d6+1 lightning.
*Special:* **Kamikaze.** When it drops to 0 HP it explodes: 10-ft radius, DC 11 DEX, 1d6 fire.
*Weakness:* Cutting the AI link (Breach DC 12) drops it out of the sky.

---

## CR 1/2

**NCPD Patrol Officer** `ncpd-officer:1/2`. Underpaid, overarmed, not your friend.
HP 24 | AC 14 (kevlar) | Speed 30 ft
Service pistol +4 (range 40/120), 1d8+2 piercing; shock baton +4, 1d4+2 bludgeoning plus 1d4 lightning.
*Special:* **Backup.** On its first turn, radios dispatch: another officer arrives in 1d4+1 rounds (+1 Heat).
*Weakness:* Bribeable. 200 €$ × your level and a DC 12 Persuasion ends the encounter.

**Gang Booster** `gang-booster:1/2`. Ganger on combat stims with gorilla arms.
HP 26 | AC 13 | Speed 30 ft
Gorilla fist +4, 1d8+2 bludgeoning; on hit, push 10 ft.
*Special:* **Stimmed.** Advantage on saves against being frightened.
*Weakness:* The stim crash: below half HP it has disadvantage on attacks.

**Sentry Turret** `sentry-turret:1/2`. Wall-mounted smart SMG.
HP 22 | AC 15 | Speed 0 | Machine
Smart SMG +4 (range 80 ft), 1d10+1 piercing; ignores half cover.
*Special:* **Arc of Fire.** Covers a 90° cone only. Coming from outside it gives advantage on attacks against it.
*Weakness:* Breach DC 13 turns it to your side for 1 minute.

---

## CR 1

**Arasaka Security Guard** `arasaka-guard:1`. Corporate security in polished armor.
HP 38 | AC 15 | Speed 30 ft
Smart pistol +5 (range 50/150), 2d6+2 piercing; ignores half cover.
*Special:* **Lockdown.** On its first turn, seals the nearest doors (Breach DC 15 to reopen).
*Weakness:* Corporate procedure: it won't leave its post to chase you beyond its zone.

**Gang Netrunner** `gang-netrunner:1`. Street-tier deck, scorched nerves.
HP 32 | AC 12 | Speed 30 ft
Short Circuit (60 ft), DC 12 CON save, 2d8 lightning (half on success; needs the target to have chrome or networked gear).
Knife +3, 1d4+1 piercing.
*Special:* **Overheat.** Once per encounter instead of attacking: 2d6 fire, DC 12 CON for half.
*Weakness:* Physically frail. While she's hacking she must be in sight of a camera or the target; break line of sight and she's blind.

**Scavenger Butcher** `scavenger:1`. Organ thief who harvests chrome from the living.
HP 40 | AC 13 | Speed 30 ft
Bone saw +5, 2d6+2 slashing.
*Special:* **Harvest.** If it hits a prone or restrained target, the target makes a DC 12 CON save or loses one random cyberware until repaired.
*Weakness:* Cowardly. If its companion falls it tries to flee with what it has.

---

## CR 2

**Militech Soldier** `militech-soldier:2`. Professional infantry.
HP 52 | AC 16 (tactical plate) | Speed 30 ft
**Multiattack:** two rifle shots.
Assault rifle +5 (range 80/240), 1d10+3 piercing each.
*Special:* **Suppressing Fire** (recharge 5-6): 10-ft cube, DC 13 DEX or 2d8 piercing, and the target can't move toward the soldier next turn.
*Weakness:* Trained to hold position. Flanking it from two sides gives advantage on attacks.

**Mercenary** `mercenary:2`. Hired gun, no loyalty past the paycheck.
HP 50 | AC 14 | Speed 30 ft
**Multiattack:** two heavy-pistol shots.
Heavy pistol +5 (range 40/120), 1d8+3 piercing.
*Special:* **Professional.** Advantage on initiative.
*Weakness:* Can be bought. Outbid their contract (1,000 €$ × CR) and they walk.

**Rogue AI Android** `rogue-android:2`. A service android whose mind was replaced from beyond the Blackwall.
HP 55 | AC 15 | Speed 30 ft | Machine
Crushing grip +5, 2d10+5 bludgeoning; on hit, grappled (escape DC 13).
*Special:* **Voice of the Machine.** Bonus action, recharge 6: speaks through every nearby screen; creatures with Humanity at Chrome Strain or below make a DC 12 WIS save or are frightened 1 round.
*Weakness:* The AI's uplink antenna (called shot at −5): destroying it shuts the body down.

**NCPD Sergeant** `ncpd-sergeant:2`. Veteran cop with a shotgun and a grudge.
HP 54 | AC 15 | Speed 30 ft
**Multiattack:** two shotgun blasts.
Shotgun +5 (range 30/90), 1d10+3 piercing; advantage within 10 ft.
*Special:* **Command.** One allied officer can use its reaction to move and attack.
*Weakness:* Wants to go home tonight. Surrendering, or a DC 14 Persuasion, makes it arrest rather than kill.

---

## CR 3-4

**Corporate Netrunner** `corpo-netrunner:3`. Arasaka or Militech runner in a cooling chair.
HP 66 | AC 13 | Speed 30 ft
**Multiattack:** two quickhacks.
Synapse Burnout (90 ft), DC 14 INT save, 3d6 psychic (half on success).
*Special:* **Black ICE.** The building's subnet runs Black ICE (DC 18). If you breach and fail, it also learns your location.
*Weakness:* Jacked in: her body is defenseless (AC 10 when reached in person). Pulling the plug deals 3d6 psychic to her.

**Arasaka Shadow Operative** `arasaka-shadow:4`. Optical camo, mantis blades, no face.
HP 90 | AC 16 | Speed 40 ft
**Multiattack:** two mantis blade strikes.
Mantis blade +6, 1d10+4 slashing.
*Special:* **Optical Camo.** Starts the fight invisible; the first attack against a target that hasn't seen it has advantage. **Leap Strike:** moves 20 ft then attacks as a bonus action.
*Weakness:* Camo flickers under EMP: it becomes visible and has disadvantage on its next attack.

**Cyberpsycho** `cyberpsycho:4`. A person who has lost themself to chrome.
HP 95 | AC 14 | Speed 40 ft
**Multiattack:** two attacks.
Gorilla arms +6, 2d6+4 bludgeoning; or improvised rifle +6, 2d8+2 piercing.
*Special:* **Berserk.** Resistance to bludgeoning, piercing and slashing while above half HP.
*Weakness:* A trace of the person remains. A DC 16 Persuasion naming someone it loved gives it disadvantage on attacks for 1 round. EMP shuts the Berserk off.
*Note:* Killing one fast brings MaxTac anyway. Taking one alive (non-lethal) earns serious NCPD reputation.

---

## CR 5-7

**Militech Exoskeleton Trooper** `exo-trooper:5`. Soldier in a powered exoskeleton.
HP 115 | AC 18 | Speed 25 ft
**Multiattack:** two attacks.
Hydraulic fist +7, 2d8+5 bludgeoning; or heavy MG +7 (range 100/300), 2d8+3 piercing.
*Special:* **Servo Strength.** Can throw cars, rip doors open and carry a fallen ally at full speed. **Shoulder Rocket** (once per encounter): 20-ft radius, DC 15 DEX, 4d6 fire.
*Weakness:* Exposed power cell on its back. Attacks from behind crit on 18-20. EMP: DC 13 CON or speed 0 for 1 round.

**Merc Solo** `merc-solo:5`. Top-tier edgerunner with a Sandevistan.
HP 110 | AC 16 | Speed 35 ft
**Multiattack:** three katana or pistol attacks.
Katana +7, 1d10+4 slashing; smart pistol +7 (50/150), 2d6+3 piercing, ignores half cover.
*Special:* **Sandevistan** (recharge 5-6): bonus action, one extra multiattack.
*Weakness:* Ego. Challenge it to a fair fight (DC 14 Intimidation or Persuasion) and it gives up its first turn's advantage. Sandevistan burnout: after using it, disadvantage on DEX saves until its next turn.

**MaxTac Operative** `maxtac-operative:6`. The NCPD's psycho-killers.
HP 180 | AC 18 | Speed 30 ft
**Multiattack:** two attacks.
Tech shotgun +7 (range 30/90), 3d8+4 piercing, shoots through cover at disadvantage; mantis blades +7, 2d8+4 slashing.
*Special:* **Psycho Protocol.** Advantage on attacks against anyone at the Edge or in cyberpsychosis. **Synaptic Shielding:** resistance to psychic.
*Weakness:* Only deployed in squads of 2. They're on a timer and leave after 5 rounds if the target isn't confirmed.

**Rogue AI Combat Frame** `rogue-frame:7`. A repurposed industrial or military robot driven from beyond the Blackwall.
HP 200 | AC 17 | Speed 30 ft, climb 30 ft | Machine
**Multiattack:** two attacks.
Hydraulic claw +7, 3d10+4 slashing; arc cannon +7 (range 60 ft), 3d8 lightning.
*Special:* **Network Swarm.** At the start of its turn it can wake one hijacked drone (rogue-drone stats) in range. **Adaptive:** after taking damage of one type, it gains resistance to that type until the end of its next turn.
*Weakness:* The Blackwall link. A successful Breach (DC 20) severs it for 1 round: the frame is stunned.

---

## CR 8+: War Bosses

**Arasaka Black-Ops Netrunner** `arasaka-blackops:8`. Arasaka's elite runner, with a bodyguard frame.
HP 210 | AC 16 | Speed 30 ft
**Multiattack:** three quickhacks.
Synapse Burnout (120 ft), DC 16 INT, 4d8 psychic; Cyberware Malfunction (60 ft), DC 16 CON or one implant offline for 1 minute.
*Special:* **Arasaka Black ICE** (DC 21) on the whole site. **Ghost Protocol:** once per encounter, teleport through the net, reappearing at any networked camera within 300 ft.
*Weakness:* Wired to a server room. Destroying the servers (AC 15, HP 60) makes all her quickhacks disadvantaged.

**Militech Combat Mech** `militech-mech:9`. Two-legged armored war machine.
HP 230 | AC 18 | Speed 30 ft | Machine
**Multiattack:** stomp and chaingun.
Stomp +8, 4d10+5 bludgeoning (one target within 5 ft, prone on hit); chaingun +8 (range 150/600), 4d8 piercing.
*Special:* **Missile Volley** (recharge 5-6): up to three 10-ft radius points within 300 ft, DC 16 DEX, 6d6 fire each. **Heavy Armor:** resistance to nonmagical piercing from pistols and SMGs.
*Weakness:* Leg actuators: 40 damage to one leg (AC 16) brings it to its knees (speed 0, attacks against it have advantage).

**Rogue AI Avatar** `rogue-ai-avatar:12`. A rogue AI wearing a war-chassis it built itself.
HP 270 | AC 19 | Speed 40 ft, fly 30 ft | Machine
**Multiattack:** three attacks.
Monowire lash +10 (reach 15 ft), 3d8+5 slashing; neural spike (90 ft), DC 18 INT, 5d10 psychic.
*Special:* **Legion.** Each round, one hijacked drone or android in range acts on its initiative. **Blackwall Breach:** once per long rest, every networked creature within 120 ft makes a DC 18 WIS save or is frightened for 1 minute (save at end of each turn).
*Weakness:* It needs the network. Killing power to the district or running a Netwatch kill-switch makes it lose Legion and disadvantage on its saves.

**Arasaka Cyber-Samurai Prototype** `arasaka-samurai:15`. Arasaka's war-champion, more chrome than human.
HP 320 | AC 20 | Speed 50 ft
**Multiattack:** four katana attacks.
Monoblade katana +11, 2d10+6 slashing.
*Special:* **Prototype Sandevistan** (recharge 5-6): takes a second full turn immediately. **Kerenzikov:** can't be surprised; reaction, once per round, imposes disadvantage on one attack against it.
*Weakness:* Neural overload. Each time it uses the Sandevistan it takes 3d10 psychic. Lure it into using it repeatedly.

---

## Quick Reference: Enemy by Level

| PC level | Easy | Medium | Hard | Deadly |
|---|---|---|---|---|
| 1 | bystander | street-punk, security-drone | ganger, cyber-hound, rogue-drone | ncpd-officer, gang-booster, sentry-turret |
| 2 | street-punk | ganger | ncpd-officer, gang-booster | arasaka-guard, gang-netrunner, scavenger |
| 3 | ganger | ncpd-officer | arasaka-guard, gang-netrunner | militech-soldier, mercenary, rogue-android |
| 4-5 | ncpd-officer, arasaka-guard | arasaka-guard, militech-soldier | mercenary, corpo-netrunner | arasaka-shadow, cyberpsycho, exo-trooper |
| 6-8 | militech-soldier | corpo-netrunner, cyberpsycho | exo-trooper, merc-solo | maxtac-operative, rogue-frame |
| 9-12 | cyberpsycho | merc-solo, maxtac-operative | rogue-frame, arasaka-blackops | militech-mech, rogue-ai-avatar |
| 13+ | maxtac-operative | rogue-frame | militech-mech | rogue-ai-avatar, arasaka-samurai |

Always confirm with `validate-encounter`; this table is a starting point.

When you need an enemy that isn't here, build it with "Improvising Creature Stats" in `encounter-guidelines.md` and add it to this file so it stays consistent.
