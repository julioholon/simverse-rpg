# SIMVERSE RPG: AI Character Creation Guide
**Quick Reference for Creating Characters & NPCs**

---

## AI AGENT ROLE

When helping users create characters:
1. **Ask clarifying questions** - Power level? Concept? Playstyle?
2. **Suggest templates** - They save time and are balanced
3. **Show the math** - Be transparent about CP expenditure
4. **Present options** - "You have 20 CP left. You could: (a) boost DX to 14 (10 CP), (b) add 3 combat maneuvers (15 CP total), or (c) mix both"
5. **Check balance** - Ensure character is functional and fun
6. **Verify totals** - Always double-check CP math before finalizing
7. **Remaining zero** - Always make sure all CP is spent, never save for later

---

## CORE SYSTEM OVERVIEW

**Mechanic**: Roll 3d6 ≤ (Attribute + Skill + modifiers) = Success
**Character Building**: Point-buy using Character Points (CP)
**Standard Starting Power**: 100 CP base (up to 150 CP with flaws)

---

## CHARACTER CREATION STEPS

### 1. DETERMINE POWER LEVEL & CP BUDGET

| Power Level | Base CP | +Max Flaws | Total | Description |
|-------------|---------|------------|-------|-------------|
| Weaklings | 50 CP | +25 CP | 75 CP | Children, animals, familiars |
| Street Level | 75 CP | +35 CP | 110 CP | Thugs, militia, rookies |
| **Starting Adventurer** | **100 CP** | **+50 CP** | **150 CP** | **Beginning heroes (STANDARD)** |
| Experienced | 150 CP | +50 CP | 200 CP | Veterans, skilled warriors |
| Heroic | 200 CP | +50 CP | 250 CP | Champions, masters |
| Elite | 250 CP | +50 CP | 300 CP | Legendary heroes, master wizards |
| Superheroic | 400 CP | +50 CP | 450 CP | Demigods, archmages |
| Cosmic | 500+ CP | +50 CP | 550+ CP | Gods, apocalyptic threats |

### 2. CHOOSE TEMPLATES (OPTIONAL BUT RECOMMENDED)

**Always check reference files first:**
- Core Rules: Elf, Dwarf, Warrior, Scout, Wizard, Rogue
- Additional Templates: Halfling, Orc, Half-Elf, Dragonborn, Gnome, Tiefling, Cleric, Druid, Barbarian, Paladin, Monk, Bard, Necromancer, Artificer, Assassin, Ranger, Summoner

**Template Costs Stack**: Elf (50 CP) + Scout (29 CP) = 79 CP total

### 3. SET ATTRIBUTES

**All attributes start at 10 (human average)**

#### Major Attributes (DX, IN, WS, CH)
Cost per level using exponential formula:

| Level | Cost to Reach | Cumulative from 10 |
|-------|---------------|-------------------|
| 11 | 10 CP | 10 CP |
| 12 | 10 CP | 20 CP |
| 13 | 10 CP | 30 CP |
| 14 | 20 CP | 50 CP |
| 15 | 20 CP | 70 CP |
| 16 | 20 CP | 90 CP |
| 17 | 40 CP | 130 CP |
| 18 | 40 CP | 170 CP |
| 19 | 40 CP | 210 CP |

**Formula**: Cost = 10 × 2^⌊(n-11)/3⌋ where n = target level

#### Minor Attributes (ST, AW, EN)
Cost **half** of major attributes:

| Level | Cost to Reach | Cumulative from 10 |
|-------|---------------|-------------------|
| 11 | 5 CP | 5 CP |
| 12 | 5 CP | 10 CP |
| 13 | 5 CP | 15 CP |
| 14 | 10 CP | 25 CP |
| 15 | 10 CP | 35 CP |
| 16 | 10 CP | 45 CP |
| 17 | 20 CP | 65 CP |
| 18 | 20 CP | 85 CP |

**Formula**: Cost = 5 × 2^⌊(n-11)/3⌋ where n = target level

**Lowering Attributes**: Gain CP by reducing from 10 (negative FLAT cost, -10 for each level below 10 for major, -5 for each level for minor)

### 4. CALCULATE DERIVED STATISTICS

| Stat | Formula | Recovery |
|------|---------|----------|
| **Vitality** (living) | EN × 2 | AW/2 per long rest (8 hrs) |
| **Integrity** (constructs) | EN × 2 | Repair skill (Engineering, 1 hr per EN) |
| **Stamina** | ST × 2 | ST/2 per short rest (1 hr) |
| **Mana** | AW × 2 | AW/2 per short rest (1 hr) |
| **Speed** | (DX + EN) / 4 | Used for initiative & movement |
| **Perception** | (IN + AW) / 2 | Used for noticing things |
| **ST Damage Bonus** | (ST - 10) / 2 (round down) | Added to melee/thrown damage |
| **Carry Capacity** | ST × 2 kg | Max sustained load without penalties |

**Living Beings use Vitality**:
- At 0 Vitality: unconscious
- At -EN Vitality: death (unless Hard to Kill perk)
- At -2×EN Vitality: body destroyed (beyond normal resurrection)

**Constructs/Robots/Unliving use Integrity**:
- At 0 Integrity: glitches and malfunctions, random system failures
- At -EN Integrity: complete shutdown (can be repaired with time)
- At -2×EN Integrity: completely broken/destroyed (beyond normal repair)

**Other Thresholds**:
- At 0 Stamina: exhausted (-4 to all physical actions)
- At 0 Mana: depleted (-4 to all mental actions)

### 5. BUY SKILLS

**Sum Progression Formula**: Total cost to level N = N × (N+1) / 2
**Hard Skills**: Cost ×2 (no default, requires training)

#### Quick Cost Table

| Level | Regular (Increment) | Regular (Total) | Hard (Increment) | Hard (Total) |
|-------|---------------------|-----------------|------------------|--------------|
| 1 | +1 CP | 1 CP | +2 CP | 2 CP |
| 2 | +2 CP | 3 CP | +4 CP | 6 CP |
| 3 | +3 CP | 6 CP | +6 CP | 12 CP |
| 4 | +4 CP | 10 CP | +8 CP | 20 CP |
| 5 | +5 CP | 15 CP | +10 CP | 30 CP |
| 6 | +6 CP | 21 CP | +12 CP | 42 CP |
| 7 | +7 CP | 28 CP | +14 CP | 56 CP |
| 8 | +8 CP | 36 CP | +16 CP | 72 CP |

**Skill Types by Attribute**:
- **DX**: Swords, Axes, Spears, Bows, Crossbows, Throwing, Brawling, Shield, Stealth, Acrobatics, Sleight of Hand
- **IN**: History, Nature, Religion, Engineering*, Medicine*, Alchemy*, Research, Investigation
- **WS**: Spellcasting, Willpower, Meditation, Intuition, Animal Handling, Occult Knowledge*
- **CH**: Persuasion, Deception, Leadership, Performance, Divine Magic, Intimidation
- **AW**: Spotting, Tracking, Survival, Navigation, Search
- **ST/EN**: Wrestling, Climbing, Swimming, Athletics, Running
- **Multi-attribute**: Climbing (ST/DX), Swimming (ST/EN), Tracking (AW/WS), Survival (AW/IN)

\* = Hard skill

**Specializations**: At skill 5+, pick a specific specialty for +2 on rolls e.g. Swords (Longsword)

### 6. PURCHASE PERKS & FLAWS

**ALWAYS CHECK REFERENCE FILES FIRST** before creating custom perks/flaws!

#### Common Perks (See Simverse_Core_Rules.md:450-641)

**Combat Perks**:
- Combat Reflexes (5 CP): +2 Speed for initiative
- Weapon Master (10 CP): +2 attack/parry/damage with one weapon type
- Martial Arts Training (20 CP): Unarmed +2 damage, attack as minor action, +2 defense unarmored
- Ambidextrous (10 CP): No off-hand penalty
- Hard to Kill (15 CP): Don't fall unconscious until -2×Vitality
- Armor Familiarity (5 CP): Reduce armor penalties by 2

**Physical Perks**:
- Fast Healer (10 CP): Recover double Vitality per rest
- Night Vision (10 CP): No penalties in darkness
- Acute Senses (5 CP per sense): +2 Perception with chosen sense
- High Pain Threshold (10 CP): Ignore first -2 from injuries
- No Sense of Pain (5 CP): Immune to pain penalties, but -2 to notice injuries (constructs, undead)
- Natural Armor (10 CP): +2 AR from scales/thick skin
- Damage Resistance (15 CP per type): Half damage from fire/cold/lightning/acid/poison

**Mental Perks**:
- Eidetic Memory (15 CP): +4 to memory-based knowledge rolls
- Strong Willed (10 CP): +2 to resist mental effects
- Quick Learner (15 CP): Learn all skills 50% faster
- Natural Talent (5 CP): Learn one chosen skill at half CP cost

**Supernatural Perks**:
- Mage Gift (20 CP): **REQUIRED** to cast spells
- Psychic (20 CP): Can use psychic powers
- Magic Resistance (15 CP): +4 to resist spells
- Extra Mana (10 CP): +10 Mana pool
- Animal Companion (15 CP): ~50 CP creature ally
- Familiar (30 CP): ~100 CP magical creature bond (requires Mage Gift)

#### Common Flaws (Max -50 CP gain)

**Combat Flaws**:
- Slow Reflexes (-10 CP): -1 Speed
- Poor Vision (-5 CP): -1 to ranged attacks
- Pacifist (-15 CP): Won't kill except extreme self-defense

**Physical Flaws**:
- Low Vitality (-10 CP): -10 Vitality
- Low Stamina (-10 CP): -10 Stamina
- One Eye (-15 CP): -3 ranged attacks, -2 Perception
- Chronic Pain (-10 CP): -1 to all physical actions
- Fragile (-15 CP): Injuries take double time to heal

**Sensory Flaws**:
- Blind (-20 CP): Cannot see, -6 to attacks, automatically fail vision tasks
- Deaf (-10 CP): Cannot hear, -4 to Perception, immune to sonic attacks
- Mute (-5 CP): Cannot speak, can't use verbal spell components

**Mental Flaws**:
- Animal Intelligence (-20 CP): IN capped at 6, can't learn complex skills
- Phobia (-5 to -15 CP): Must roll WS vs 12 or freeze/flee
- Addiction (-10 to -20 CP): Need substance regularly
- Overconfident (-10 CP): Must roll WS to retreat
- Low Mana (-10 CP): -10 Mana pool

**Social Flaws**:
- Hideous Appearance (-10 CP): -2 to reaction rolls
- Enemy (-5 to -20 CP): Someone actively opposes you
- Code of Honor (-10 CP): Must follow strict personal rules
- Debt (-10 CP): Owe money/favors

#### CREATING CUSTOM PERKS & FLAWS

**Use existing as templates! Guidelines:**

**For Perks**:
- Small bonus (+1-2): 5 CP
- Moderate bonus (+3-4 or special ability): 10-15 CP
- Major bonus (+5+ or powerful ability): 20-30 CP
- Compare to similar existing perks for balance

**For Flaws**:
- Minor inconvenience: -5 CP
- Moderate limitation: -10 CP
- Major disability: -15 to -20 CP
- Frequency/severity affects value: common = less CP, rare = more CP

**Examples**:
- New Perk "Sure-Footed" (5 CP): +2 to resist being knocked prone → similar to small combat perks
- New Flaw "Claustrophobia" (-10 CP): Panic in enclosed spaces, must roll WS vs 12 → similar to Phobia

### 7. ACQUIRE POWERS, SPELLS & MANEUVERS

**PRIORITY: USE PRE-BUILT POWERS FROM Simverse_Powers_Library.md FIRST!**

The library contains 100+ ready-to-use powers including:
- Combat Maneuvers: Shield Bash, Disarm, Power Attack, Feint, Precision Strike, Sneak Attack, etc.
- Arcane Spells: Fire Bolt, Magic Missile, Invisibility, Teleport, etc.
- Divine Spells: Healing Touch, Bless, Turn Undead, Divine Smite, etc.
- Necromantic Spells: Animate Dead, Life Drain, Death Bolt, etc.
- Summoning Spells: Summon Elemental, Summon Beast, etc.

#### POWER CONSTRUCTION SYSTEM (For Custom Powers Only)

**Base Tiers**:

| Tier | Min Skill | CP Base | Resource Cost | Examples |
|------|-----------|---------|---------------|----------|
| Minor | 2 | 1 CP | 0-1 | Shield Bash, Trip, Disarm, Quick Draw |
| Moderate | 3 | 5 CP | 2 | 1d6 damage, minor healing, charm |
| Major | 5 | 15 CP | 6 | 3d6 damage, flight, invisibility |
| Epic | 8 | 30 CP | 12 | 6d6+ damage, teleport, raise dead |
| Legendary | 13 | 50 CP | Varies | World-altering effects |

**Enhancements** (increase cost by %):

| Enhancement | Modifier | Description |
|-------------|----------|-------------|
| Increased Damage | +50% per +1d6, +100% for +2d6 | More damage/healing |
| Extra Range | +20% (2×), +40% (4×) | Double or quadruple range |
| Extra Duration | +10% (2×), +20% (6×), +30% (12×) | Longer lasting |
| Area Effect | +50% (3m), +100% (6m) | Hit multiple targets in area |
| Multiple Targets | +50% (2), +75% (3), +125% (5) | Hit specific targets |
| Reduced Cost | +25% (half), +50% (quarter) | Costs less Stamina/Mana |
| Reliable Activation | +100% | No skill roll, auto-activates |
| Armor Piercing | +50% | Ignore 2 AR |
| Homing | +50% | Auto-hit, no roll needed |
| Silent Casting | +80% | No visible/audible effect |

**Limitations** (decrease cost by %):

| Limitation | Modifier | Description |
|------------|----------|-------------|
| Only in [Condition] | -5% to -40% | -5% common, -10% uncommon, -20% rare, -40% nearly impossible |
| Requires [Item] | -10% | Need tool/weapon/focus |
| Usage Limit | -15% (3/day), -30% (1/day), -40% (1/week) | Limited uses |
| Preparation Time | -10% (1 min), -20% (10 min), -30% (1 hr) | Must prepare first |
| Obvious/Loud | -10% | Clearly visible/audible |
| Concentration | -20% | Can't take other actions |
| Increased Cost | -25% (double), -50% (triple) | Costs more to use |
| Melee Range Only | -15% | Must be adjacent |
| Self Only | -25% | Cannot target others |
| Exhausting | -25% | Take 1 Vitality when used |
| Strenuous | -25% | -2 to actions for 10 min after |

**Construction Formula**:
```
Final CP = Base CP × (1 + Sum(Enhancements) - Sum(Limitations))
Round down, minimum 1 CP
Maximum reduction: -75% (can't go below 25% of base)
```

**Example - Custom "Lightning Strike" spell**:
1. Base: Moderate (5 CP, 2 Mana) - 1d6 damage
2. Enhancements: Increased Damage +100% (+2d6 = 3d6 total), Extra Range +20% (20m)
3. Limitations: Verbal Component -10%, Obvious/Loud -10%
4. Calculation: 5 × (1 + 1.00 + 0.20 - 0.10 - 0.10) = 5 × 2.00 = **10 CP**
5. Effect: 3d6 lightning damage at 20m range, requires verbal component, loud crack of thunder

**IMPORTANT NOTES**:
- Must have minimum skill level for tier (Moderate = skill 3+)
- Physical maneuvers cost Stamina, spells cost Mana
- By default, powers require skill roll to activate (Reliable Activation removes this)
- Always compare to existing powers in library for balance

### 8. EQUIPMENT & STARTING GEAR

**Starting Wealth by Background**:
- Poor: 50 sp
- Common: 100 sp
- Craftsman: 250 sp
- Wealthy Perk (5 CP): 500 sp

**Common Equipment** (See Simverse_Equipment_List.md for full list with weights):

**Weapons**:
- Dagger: 1d6-3, 5 sp, 0.3 kg
- Shortsword: 1d6-1, 20 sp, 1 kg
- Longsword: 2d6-1, 50 sp, 1.5 kg (cutting or impaling thrust)
- Greatsword: 3d6, 100 sp, 3 kg
- Spear: 1d6+1, 10 sp, 1.5 kg (impaling)
- Shortbow: 1d6+1, 30 sp, 1 kg (50m range)
- Longbow: 2d6, 60 sp, 1.5 kg (100m range)

**Armor** (penalties: Light 0, Medium -2, Heavy -4):
- Leather Cuirass: AR 2, 25 sp, 4 kg (Light)
- Chain Shirt: AR 4, AD 1, 80 sp, 10 kg (Medium, -2 penalty)
- Full Plate Cuirass: AR 10, AD 2, 1500 sp, 15 kg (Heavy, -4 penalty)

**Encumbrance** (see Core Rules for details):
- 0-100% Carry Capacity: No penalties
- 101-150%: Overburdened (-2 Speed, -2 physical, -1 defenses)
- 151-200%: Maximum (half speed, -4 physical, -2 defenses)

**Shields**:
- Small Shield: SD 1, 10 sp
- Medium Shield: SD 2, 25 sp
- Large Shield: SD 3, 50 sp

**Templates provide starting equipment** - don't double-purchase!

---

## COMPLETE CHARACTER CREATION CHECKLIST

- [ ] 1. Determine power level & CP budget
- [ ] 2. Choose race template (if any)
- [ ] 3. Choose profession template (if any)
- [ ] 4. Set attributes (apply racial modifiers)
- [ ] 5. Calculate derived statistics
- [ ] 6. Purchase additional skills (beyond templates)
- [ ] 7. Select perks (beyond templates)
- [ ] 8. Take flaws (optional, max -50 CP)
- [ ] 9. Acquire powers/spells/maneuvers (**use pre-built from library first!**)
- [ ] 10. Note starting equipment (from templates or purchased)
- [ ] 11. Calculate final CP expenditure (must equal or be less than budget)
- [ ] 12. Add background, personality, goals

---

## QUICK NPC CREATION

**For quick NPCs, use templates + minor adjustments:**

**Simple Guard (75 CP Street Level)**:
- Human baseline (0 CP)
- ST 11 (5 CP), EN 11 (5 CP), DX 11 (10 CP)
- Spears 3 (6 CP), Athletics 2 (3 CP), Perception 2 (3 CP)
- Equipment: Spear (1d6+1), leather armor (AR 2), small shield (SD 1)
- Total: 32 CP spent, 43 CP left for Guard template skills/equipment

**Skilled Wizard (150 CP Experienced)**:
- Elf (50 CP) + Wizard (51 CP) = 101 CP
- Remaining 49 CP: IN 11→13 (20 CP), add 5 moderate spells (25 CP)
- Spells: Fire Bolt, Magic Missile, Shield, Invisibility, Detect Magic

**Powerful Warrior (200 CP Heroic)**:
- Dwarf (45 CP) + Warrior (33 CP) = 78 CP
- Remaining 122 CP: ST 11→15 (30 CP), DX 10→13 (30 CP), EN 12→14 (10 CP)
- Weapon Master (10 CP), Extra Vitality (10 CP), Power Attack (8 CP), Shield Bash (1 CP), Disarm (1 CP)
- Final: ST 15 (+2 damage), EN 14, DX 13, Vitality 28+10=38

---

## COMBAT QUICK REFERENCE

**Initiative**: Speed value (highest acts first)

**Actions per Turn**:
- 1 Major: Attack, cast spell, full move
- 1 Minor: Draw weapon, command, quick action
- 1 Reaction: Defense roll (dodge/parry/block)

**Attack Resolution**:
1. Attacker rolls: 3d6 ≤ (DX + Weapon Skill + mods)
2. Calculate margin: Target Number - Roll Result
3. Defender penalty: -1 per 5 margin
4. Defender chooses defense and rolls
5. If defender fails: Roll damage, subtract AR, apply to Vitality

**Defense Options**:
- **Dodge**: DX/2 + AD (works vs all attacks)
- **Parry**: (DX + Weapon Skill)/2 (-4 if attacked this turn)
- **Block**: (DX + Shield Skill)/2 + SD (frontal attacks only)

**Two-Weapon Fighting & Off-Hand**:
- **Off-hand penalty**: -4 to hit with non-dominant hand
- **Two weapons**: Main hand -2, off-hand -6 (both attack as 1 Major Action)
- **Ambidextrous (10 CP)**: Removes all off-hand penalties

**Damage Types**:
- **Bludgeoning**: Normal AR applies
- **Cutting**: AR counts as double, but causes bleeding (1 Vitality/turn)
- **Impaling** (two types):
  - **Dedicated impaling weapons** (arrows, spears, pikes): Damage through AR is doubled
  - **Slashing weapons thrust** (swords, daggers): Subtract 1 per die first, then damage through AR is doubled
- **Energy**: Normal AR applies, may cause special effects

---

## EXAMPLE CHARACTER: ELVEN SCOUT (100 CP STARTING)

**Name**: Lyra Windwhisper
**Race**: Elf (50 CP)
**Profession**: Scout (29 CP)
**Remaining**: 21 CP

**Attributes**:
- DX 13 (12 from racial +1 purchased = 10 CP)
- IN 10, WS 10, CH 10
- ST 9 (racial -1)
- EN 9 (racial -1)
- AW 12 (11 from racial +1 purchased = 5 CP)

**Derived Stats**:
- Vitality: 18, Stamina: 18, Mana: 24
- Speed: 5.5, Perception: 11
- ST Damage Bonus: -1

**Skills** (from Scout template):
- Bow 4 (6 CP + 4 CP upgrade = 10 total)
- Stealth 4 (6 CP + 4 CP upgrade = 10 total)
- Tracking 3, Survival 2, Perception 2

**Perks** (from templates):
- Night Vision, Acute Senses (Hearing & Sight)
- Facilitated Movement (Forest), Graceful

**Combat Maneuvers** (remaining CP):
- Aimed Shot (3 CP): +4 to hit after aiming
- Quick Draw (1 CP): Draw weapon as free action

**Equipment**: Light armor (AR 2), longbow (2d6, 100m), hunting knife (1d6-3), camping gear

**Combat Stats**:
- Bow Attack: DX 13 + Bow 4 = 17 to hit
- Bow Damage: 2d6 -1 (ST penalty) = avg 6 damage
- Dodge: DX 13/2 = 6.5 → 6
- Vitality: 18 HP

**Total CP**: 50 (Elf) + 29 (Scout) + 10 (DX) + 5 (AW) + 4 (Bow upgrade) + 4 (Stealth upgrade) + 3 (Aimed Shot) + 1 (Quick Draw) = **106 CP**
*Note: Exceeded by 6 CP - could reduce by taking -6 CP flaws or adjusting skills*

---

## FINAL REMINDERS FOR AI CHARACTER CREATION

### ALWAYS DO THIS:
1. **Check reference files first** for existing templates, perks, and powers
2. **Start with templates** - they're balanced and save time
3. **Use pre-built powers** from Simverse_Powers_Library.md before creating custom
4. **Verify CP math** - total spent must equal or be less than budget
5. **Apply racial modifiers** to base attributes (all start at 10)
6. **Include equipment** from templates in the character sheet

### NEVER DO THIS:
1. ❌ Create custom perks/flaws without checking existing ones first
2. ❌ Create custom powers without checking the Powers Library first
3. ❌ Forget to calculate derived statistics (Vitality, Stamina, Mana, Speed, Perception)
4. ❌ Exceed CP budget without taking equivalent flaws
5. ❌ Give powers without checking minimum skill requirements
6. ❌ Forget armor penalties (-2 for medium, -4 for heavy)

### BALANCE GUIDELINES:
- Starting characters (100 CP): Primary attribute 12-14, main skill 3-5
- Primary combat roll: ~15-17 (attribute + skill)
- Spellcasters: Invest 30-40 CP in spells (about 8-12 minor/moderate spells)
- Warriors: Invest 20-30 CP in combat maneuvers
- Don't min-max excessively - balanced characters are more fun and versatile

---

**END OF CHARACTER CREATION GUIDE**

For complete rules, see:
- **Simverse_Core_Rules.md** - Complete rulebook
- **Simverse_Powers_Library.md** - 100+ pre-built powers, spells, maneuvers
- **Simverse_Additional_Templates.md** - Extended races and professions
- **Simverse_Equipment_List.md** - Comprehensive weapons, armor, gear
- **Simverse_Skill_List.md** - Complete skill descriptions
- **Simverse_Character_Sheet.md** - Character sheet template
