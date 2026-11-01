# Cyberpunk Setting Rules

This campaign runs on the 5e chassis (d20, ability scores, levels, CR, conditions) in a **cyberpunk megacity at war**. This file overrides any fantasy default in the rest of the plugin. When something isn't covered here, reflavor the 5e rule into tech rather than importing fantasy content.

**There is no magic.** No elves, no gods, no spellbooks, no undead, no dragons. Everything "magical" is tech: quickhacks, cyberware, drugs, drones, prototype weapons.

---

## The World at a Glance

- **The City:** A vertical megacity of megabuildings, neon markets, flooded underpasses and corporate plazas, ringed by the irradiated **Badlands**. Name it during campaign creation.
- **The Corporate War:** Arasaka and Militech are in a shadow war over the city. Sabotage, assassinations, proxy gangs and deniable merc crews are everyday background. It is the campaign's master clock (see below).
- **The Net:** Fractured after an old catastrophe. Corporations wall off their subnets with **ICE**; **rogue AIs** live beyond the **Blackwall** and some have started wearing robot bodies.
- **Street level:** Gangs, fixers, ripperdocs, joytoy clubs, noodle stands, NCPD patrols that look the other way for the right price.

### Core Factions (seed `factions.md` from these)

| Faction | What they want | Typical assets |
|---|---|---|
| **Arasaka** | Total control of the city's security and cyberware markets | Corporate security, shadow operatives, Black ICE, prototype chrome |
| **Militech** | Win the war, sell weapons to everyone | Soldiers, exoskeleton troopers, combat mechs, drones |
| **NCPD** | Keep order, collect bribes, avoid blame | Patrol cops, detectives, armored response; **MaxTac** for cyberpsychos |
| **Trauma Team** | Profit from keeping subscribers alive | Armored AVs, medics with guns |
| **Street gangs** (create 2-3) | Turf, chrome, eddies | Gangers, boosters, gang netrunners |
| **Fixers** | Broker jobs between corps, gangs and edgerunners | Contacts, safehouses, intel |
| **Netwatch** | Police the Net, hold the Blackwall | Elite netrunners, kill-switch ICE |
| **Rogue AIs** | Break through the Blackwall and act in meatspace | Hijacked drones, android shells, combat frames, daemons |

---

## Money: Eurodollars (€$)

Eurodollars ("eddies") are the only currency. **Credits** are the same money held digitally on a credchip or bank account; treat €$ and credits as 1:1.

- **Conversion:** If you need the price of an SRD item, **1 gp = 10 €$**. Silver/copper/platinum don't exist.
- **Loot:** credchips, sellable chrome, weapons, data shards. Fences pay 30-50% of list price.

| Cost of living | €$ |
|---|---|
| Street noodles / synthcoffee | 5-10 |
| Night in a coffin hotel | 40 |
| Megabuilding apartment (month) | 1,500 |
| Bribe to make a beat cop look away | 100-500 |
| Fixer job pay (street / mid / corp-level) | 500-2,000 / 3,000-10,000 / 20,000+ |
| Ripperdoc install fee | 10% of the cyberware's price |

---

## Characters

### Origin (replaces race)

Everyone is human. Pick **Standard** (+1 to all six scores) or **Edgerunner** (+1 to two scores, one skill, one feat). Then pick a **Lifepath** (replaces background):

| Lifepath | Skills | Tool / Vehicle | Feature | Start €$ |
|---|---|---|---|---|
| **Streetkid** | Streetwise, Intimidation | Thieves' tools | *Street Cred:* gangs on home turf won't attack you on sight; you can always find a fence or a cheap bed | 500 |
| **Corpo** | History, Deception | Forgery kit | *Corporate Access:* you can talk your way into corporate lobbies and get one favor per session from an old colleague | 2,000 |
| **Nomad** | Survival, Driving | Mechanic's tools; motorcycle or car | *Clan Ties:* free shelter, fuel and repairs with any nomad clan; Badlands travel takes half the time | 800 + vehicle |
| **Ex-NCPD** | Investigation, Insight | Forensics kit | *Badge Memory:* you know how cops work; one informant inside the NCPD | 900 |
| **Ex-Militech** | Athletics, Perception | Vehicle (land) | *Chain of Command:* military hardware is familiar; buy Militech gear at 20% off | 1,000 |
| **Netrunner Kid** | Netrunning, Cybertech | Cyberdeck tools | *Net Rep:* other runners trade you exploits; adv. on checks to find a back door into a subnet | 700 |

Every character starts with **one Street-tier cyberware** of their choice, free.

### Roles (replace classes)

Use the 5e class as the mechanical chassis and reskin every feature. Spells become **quickhacks, gadgets, med-tech, implants or drugs**.

| Role | 5e chassis | Reskin |
|---|---|---|
| **Solo** | Fighter | Professional killer. Action Surge = combat stims. |
| **Netrunner** | Wizard | Spells = quickhacks run through a cyberdeck; spell slots = **RAM**. |
| **Techie** | Artificer (or Rogue) | Gadgets, drones, turrets, jury-rigged weapons. |
| **Medtech** | Cleric (Life) | Trauma surgeon; healing spells = med-tech, drugs, nanites. No deity. |
| **Fixer** | Rogue | Deals, connections, a gun under the table. |
| **Rockerboy** | Bard | Rebel musician; inspiration through performance and noise. |
| **Nomad Scout** | Ranger | Badlands tracker; favored enemy = a faction. |
| **Lawman** | Paladin | Oath = a personal code; smite = overcharged shots / shock baton. |
| **Street Samurai** | Monk | Blades and martial arts; ki = reflex-booster charge. |
| **Brawler** | Barbarian | Rage = Berserk implant or combat drugs. |
| **Corpo Agent** | Warlock | Patron = your corporation; pact boons are company implants. The corp can call in favors. |
| **Chrome-born** | Sorcerer | Born with a neural interface; innate quickhacks. |

Off-limits unless reflavored with a clear tech cost: resurrection, teleportation, summoning undead or fiends, wish-tier effects. Example: *Revivify* = defibrillator plus nanite shot within 1 minute, needs a medkit.

### Skill renames

The character sheet uses these. Abilities stay the same.

| 5e skill | Cyberpunk skill | Covers |
|---|---|---|
| Arcana (INT) | **Netrunning** | The Net, ICE, cyberdecks, AIs, breaching |
| Nature (INT) | **Cybertech** | Identifying, repairing, crafting cyberware, drones and gear |
| Religion (INT) | **Streetwise** | Gangs, fixers, black markets, who runs what block |
| Animal Handling (WIS) | **Driving** | Cars, bikes, AVs, chases, drones by remote |

### Damage types

Lightning = **electrical/EMP**. Fire = **thermal**. Psychic = **neural** (ICE, synapse burnout). Necrotic = **toxin/bio-weapon**. Radiant = **laser/plasma** (prototype only).

---

## Humanity & Cyberpsychosis

Chrome eats your empathy.

- **Humanity Max = WIS score × 5.** Example: WIS 12 gives 60.
- Installing cyberware reduces **current Humanity** by its Humanity cost.
- **Therapy** (one week of downtime and 500 €$) restores 2d6 Humanity, but never above **Max minus half the total Humanity cost of installed chrome**.

| Current Humanity | State | Effect |
|---|---|---|
| Above 50% of Max | Stable | None |
| 50% or less | **Chrome Strain** | Disadvantage on Insight and on Persuasion that relies on empathy |
| 25% or less | **Edge** | When dropped below half HP, rolling a nat 1, or witnessing an atrocity: DC 13 WIS save or a **Psycho Episode** (next turn you attack the nearest creature, friend or foe) |
| 0 | **Cyberpsychosis** | The character becomes an NPC. MaxTac is dispatched. Offer the player one final session to be talked down or put down. |

Track Humanity on the character sheet and in the session snapshot.

---

## Cyberware

Installed by a ripperdoc (fee: 10% of price; 1 hour per tier). **Black-market chrome** costs half price and +2 Humanity, and 1 in 20 pieces carries a corporate backdoor or glitch. That's a ready-made quest hook.

**Tiers:** Street (common), Mil-spec (uncommon/rare), Prototype (very rare; usually stolen from Arasaka or Militech).

**One per slot** unless noted. **EMP** (grenade, quickhack or arc weapon) forces a DC 13 CON save. On a failure, the target's active cyberware is offline until the end of its next turn.

### Operating System (pick one)

| Cyberware | Tier | €$ | Humanity | Effect |
|---|---|---|---|---|
| **Sandevistan** | Mil-spec | 5,000 | 14 | Bonus action, once per short rest: time slows; take one extra action this turn (Attack with one attack, Dash, Disengage, Hide or Use an Object). |
| **Sandevistan, Prototype** | Prototype | 15,000 | 18 | As above, plus your speed doubles until the end of your next turn. |
| **Berserk** | Mil-spec | 6,000 | 12 | Bonus action, once per long rest: for 1 minute, resistance to bludgeoning, piercing and slashing, and advantage on STR checks and saves. You can't take reactions. |
| **Cyberdeck, Street** | Street | 2,000 | 6 | Required for quickhacks. +1 to Netrunning checks. |
| **Cyberdeck, Mil-spec** | Mil-spec | 8,000 | 8 | +2 Netrunning, +1 quickhack save DC. |
| **Cyberdeck, Prototype** | Prototype | 20,000 | 10 | +3 Netrunning, +2 quickhack DC; once per long rest, regain one expended RAM slot of 3rd level or lower. |

### Frontal Cortex

| Cyberware | Tier | €$ | Humanity | Effect |
|---|---|---|---|---|
| **Chip Slot** | Street | 500 | 2 | Holds one **skill chip**. Swapping a chip takes an action. |
| Skill chip | Street | 200-1,000 | — | Proficiency in one skill, tool or language while slotted. |
| **Memory Boost** | Street | 1,500 | 3 | Advantage on INT checks to recall something you've seen or read. |
| **Ex-Disk** | Mil-spec | 3,000 | 4 | +1 first-level RAM slot (netrunners only). |
| **Personality Shard Port** | Prototype | 10,000 | 8 | Slot an engram: once per long rest, gain advantage on all checks of one skill for 1 hour, but make a DC 12 WIS save or lose 1d4 Humanity. |

### Ocular

| Cyberware | Tier | €$ | Humanity | Effect |
|---|---|---|---|---|
| **Cyberoptics: Low-Light** | Street | 500 | 2 | Darkvision 60 ft. |
| **Cyberoptics: Zoom** | Street | 800 | 2 | No disadvantage on ranged attacks at long range; advantage on Perception (sight) beyond 60 ft. |
| **Threat Scanner** | Mil-spec | 2,000 | 3 | Bonus action: learn one creature's AC, its rough HP state, and its listed Weakness. |
| **Target Analysis** | Mil-spec | 2,500 | 3 | +1 to attack rolls with smart weapons. |

### Arms (one arm system)

| Cyberware | Tier | €$ | Humanity | Effect |
|---|---|---|---|---|
| **Mantis Blades** (arm blades) | Mil-spec | 5,000 | 10 | Twin retractable blades: finesse melee weapons, 1d8 slashing each, light, can't be disarmed. If you move 20+ ft in a straight line, make one blade attack as a bonus action. |
| **Gorilla Arms** | Mil-spec | 4,000 | 8 | Unarmed strikes deal 1d8 bludgeoning; advantage on STR checks to break, lift or force doors. |
| **Monowire** | Mil-spec | 4,500 | 9 | Finesse melee weapon, reach 15 ft, 1d8 slashing. A netrunner can deliver a touch-range quickhack through it. |
| **Projectile Launch System** | Mil-spec | 6,000 | 9 | Once per short rest: an explosive round at a point within 60 ft. 20-ft radius, DEX save (DC 8 + prof + DEX), 4d6 thunder, half on a success. |

### Hands

| Cyberware | Tier | €$ | Humanity | Effect |
|---|---|---|---|---|
| **Smart Link** | Street | 1,500 | 3 | Unlocks smart weapons: their rounds ignore half and three-quarters cover. |
| **Ballistic Coprocessor** | Mil-spec | 2,500 | 3 | Ricochet shots: power weapons ignore half cover. |
| **Grip Pads** | Street | 800 | 1 | Advantage on climbing checks; can't be disarmed of a held weapon by a failed save. |

### Legs

| Cyberware | Tier | €$ | Humanity | Effect |
|---|---|---|---|---|
| **Reinforced Tendons** | Street | 2,000 | 4 | Jump distances doubled; once per turn, jump again mid-air (+10 ft). |
| **Fortified Ankles** | Mil-spec | 2,500 | 4 | Charged jump: high jump ×3; no falling damage from 30 ft or less. |
| **Lynx Paws** | Street | 1,500 | 3 | Silent footsteps: advantage on Stealth checks against hearing. |
| **Speed Boosters** | Street | 2,000 | 4 | +10 ft walking speed. |

### Skeleton & Body Frame

| Cyberware | Tier | €$ | Humanity | Effect |
|---|---|---|---|---|
| **Titanium Bones** | Street | 3,000 | 4 | Carrying capacity doubled; +1 max HP per level. |
| **Bionic Lungs** | Street | 1,000 | 2 | Advantage on CON saves against gas and toxins; hold your breath for 1 hour. |
| **Integrated Exoskeleton** | Prototype | 12,000 | 12 | Strength becomes 19 (if lower). +1 AC. −5 ft speed. Counts as wearing heavy armor for STR requirements. |

### Skin (Integumentary)

| Cyberware | Tier | €$ | Humanity | Effect |
|---|---|---|---|---|
| **Subdermal Armor Mk.I** | Street | 3,000 | 6 | +1 AC. |
| **Subdermal Armor Mk.II** | Mil-spec | 9,000 | 8 | +2 AC (replaces Mk.I). |
| **Optical Camo** | Prototype | 8,000 | 6 | Action, once per long rest: invisible for 1 minute (ends early if you attack). |
| **Heat Sink Weave** | Street | 1,500 | 2 | Resistance to fire (thermal). |

### Nervous System & Circulatory

| Cyberware | Tier | €$ | Humanity | Effect |
|---|---|---|---|---|
| **Reflex Booster (Kerenzikov)** | Mil-spec | 4,000 | 5 | +2 initiative; you can't be surprised while conscious. |
| **Synaptic Shielding** | Mil-spec | 3,500 | 4 | Resistance to psychic (neural) damage from ICE and quickhacks. |
| **Biomonitor** | Street | 1,500 | 2 | Once per long rest, the first time you drop below half HP, auto-inject: regain 2d4+2 HP. |
| **Blood Pump** | Mil-spec | 3,000 | 4 | Bonus action, once per short rest: regain 1d8 + CON mod HP. |
| **Second Heart** | Prototype | 15,000 | 8 | Once per long rest, when reduced to 0 HP but not killed outright, drop to 1 HP instead. |

---

## Gear

### Weapons (5e weapon rules + firearm properties)

**Ammunition:** a magazine holds the listed shots. **Reload** takes a bonus action (or an action without a free hand). **Burst fire:** spend 10 rounds; each creature in a 10-ft cube within normal range makes a DC 15 DEX save or takes the weapon's damage. **Smart** weapons need a Smart Link; with it, their rounds ignore half and three-quarters cover. **Tech** weapons can charge (bonus action) to shoot through thin walls and cover at disadvantage.

| Weapon | €$ | Damage | Range | Mag | Properties |
|---|---|---|---|---|---|
| Knife | 20 | 1d4 piercing | 20/60 | — | finesse, light, thrown |
| Bat / pipe | 15 | 1d6 bludgeoning | — | — | — |
| Machete | 60 | 1d6 slashing | — | — | light |
| Katana | 400 | 1d8 slashing | — | — | finesse, versatile (1d10) |
| Shock baton | 250 | 1d6 bludgeoning + 1d4 lightning | — | — | EMP on crit |
| Light pistol | 150 | 2d6 piercing | 50/150 | 15 | light |
| Heavy pistol / revolver | 300 | 2d8 piercing | 40/120 | 6 | — |
| Smart pistol | 600 | 2d6 piercing | 50/150 | 12 | smart |
| SMG | 450 | 2d6 piercing | 50/150 | 30 | burst fire, two-handed |
| Smart SMG | 900 | 2d6 piercing | 50/150 | 30 | burst fire, smart, two-handed |
| Assault rifle | 800 | 2d8 piercing | 80/240 | 30 | burst fire, two-handed |
| Shotgun | 500 | 2d8 piercing | 30/90 | 4 | two-handed; advantage vs. targets within 10 ft |
| Tech rifle | 1,800 | 2d8 lightning | 100/300 | 8 | tech, two-handed |
| Sniper rifle | 1,500 | 2d10 piercing | 150/600 | 5 | heavy, two-handed |
| Frag grenade | 100 | 3d6 slashing | 60 | — | 20-ft radius, DC 13 DEX for half |
| EMP grenade | 150 | 3d6 lightning to machines | 60 | — | 20-ft radius; cyberware goes offline (see EMP) |
| Flashbang | 80 | — | 60 | — | 20-ft radius; DC 13 CON or blinded and deafened until end of next turn |

### Armor

| Armor | €$ | AC | Notes |
|---|---|---|---|
| Armored jacket (light) | 100 | 11 + DEX | — |
| Kevlar armorjack (medium) | 400 | 13 + DEX (max 2) | — |
| Corporate tactical vest (medium) | 1,200 | 14 + DEX (max 2) | — |
| Militech tactical plate (heavy) | 1,500 | 16 | STR 13, Stealth disadvantage |
| Riot armor (heavy) | 4,000 | 18 | STR 15, Stealth disadvantage |
| **Militech Powered Exoskeleton** (heavy) | 20,000 | 17 | No Humanity cost. STR becomes 21 while worn. Takes 10 minutes to don; battery lasts 8 hours. EMP: DC 13 CON or speed 0 until end of next turn. |
| Ballistic shield | 300 | +2 | Takes a hand |

### Consumables (replace healing potions)

| Item | €$ | Effect |
|---|---|---|
| **MaxDoc** | 50 | Action (bonus action if self-applied): regain 2d4 + 2 HP. |
| **BounceBack** | 150 | Regain 4d4 + 4 HP. |
| **BounceBack Mk.III** | 500 | Regain 8d4 + 8 HP. |
| Combat stim | 200 | Bonus action: 1d10 temp HP and advantage on your next attack. Afterward, DC 12 CON save or poisoned for 1 hour. |
| Ammo (one magazine refill) | 10-40 | — |
| Medkit | 50 | 10 uses; stabilize without a check. |

MaxDocs are **common loot** and sold at every ripperdoc and vending machine, which is the solo-play healing guarantee.

### Trauma Team (replaces the out-of-combat safety net)

| Plan | €$ / month | Effect |
|---|---|---|
| Silver | 500 | When you fail your 2nd death save, roll d20: on 11+ an AV arrives, stabilizes you and extracts you (3,000 €$ bill). |
| Platinum | 5,000 | An armed team arrives within 1d4 rounds of you dropping to 0 HP, stabilizes you and extracts you, shooting anyone in the way. |

---

## Netrunning

### Quickhacks (Netrunner and Chrome-born spells)

Quickhacks need a **cyberdeck** and a target that is **networked**: it has cyberware, is a machine or drone, or is connected through a device you can see (a camera, terminal or turret). A creature with no chrome and no networked gear is immune unless the hack targets its surroundings.

Pick spells from the class list and **rename them**. Mechanics stay the same, flavor changes:

| Quickhack | Use this spell's mechanics |
|---|---|
| Ping | *Detect Magic*: reveals networked devices and chromed creatures within 30 ft, through walls |
| Short Circuit | *Shocking Grasp* at 60 ft (lightning; advantage vs. drones and robots) |
| Overheat | *Fire Bolt* (thermal) |
| Reboot Optics | *Blindness/Deafness* (blind only) |
| Cripple Movement | *Ray of Enfeeblement* or *Hold Person* (organics with cyberware only) |
| Weapon Glitch | *Heat Metal* on a smart or tech weapon |
| Synapse Burnout | *Phantasmal Killer* (neural damage) |
| Cyberware Malfunction | *Counterspell* against an implant activation, or forces EMP effect |
| System Reset | *Sleep* (target collapses as its implants reboot) |
| Memory Wipe | *Modify Memory* (last 10 minutes) |
| Camera Control | *Clairvoyance* through a networked camera |
| Distract | *Minor Illusion* via speakers, holos and screens |
| Contagion | *Cloudkill*, spreading between networked targets in range |
| Suicide | *Power Word Kill* (targets must have a neural link) |

### Breach Protocol

Anyone proficient in Netrunning with any cyberdeck can **breach**. It takes an action: an INT (Netrunning) check against the subnet's **ICE DC**.

- **Success:** Choose one: open a door or terminal, take a camera or turret offline, or **upload a daemon**. A daemon gives every enemy on that subnet −2 to saves against quickhacks for the encounter.
- **Failure:** The ICE strikes back.

| ICE | DC | Backlash on failure |
|---|---|---|
| Street ICE | 12 | 2d6 psychic |
| Corporate ICE | 15 | 4d6 psychic |
| Black ICE | 18 | 8d6 psychic, and INT save (same DC) or stunned 1 round |
| Arasaka Black ICE | 21 | 10d6 psychic; if you fail the check by 5+, drop to 0 HP (flatlined) |
| Beyond the Blackwall | 25 | A rogue AI notices you (start or advance its clock) |

---

## Campaign Clocks (create these at campaign start)

### Corporate War (8 segments, faction clock)

Advance when: the player completes a job for Arasaka or Militech, a war-related quest fails, or two in-world weeks pass.

| Filled | Stage | What the city looks like |
|---|---|---|
| 1-2 | **Cold War** | Sabotage, assassinations, strange explosions blamed on gangs |
| 3-4 | **Proxy War** | Corps arm gangs and hire merc crews; turf wars spike |
| 5-6 | **Open Skirmishes** | Corporate checkpoints, curfews, firefights in the streets; NCPD picks a side |
| 7-8 | **Full Corporate War** | Military occupation of districts, AV strikes, blackouts. The city burns unless someone ends it. |

### Heat (NCPD wanted level, 0-5)

Rises with public crimes, killing cops, and witnesses left alive.

| Heat | Response |
|---|---|
| 1 | Patrols remember your face |
| 2 | Stopped and searched on sight |
| 3 | A bounty is posted; mercs and bounty hunters come looking |
| 4 | Armored NCPD raid on your known locations |
| 5 | MaxTac or a corporate kill team is assigned to you |

Heat drops by 1 per week of lying low, or 1,000 €$ × your level in bribes per point.
