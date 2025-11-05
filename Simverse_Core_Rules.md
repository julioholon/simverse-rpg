# SIMVERSE
## Core Rulebook v1.1

---

## Table of Contents
1. [Core Mechanics](#core-mechanics)
2. [Attributes](#attributes)
3. [Derived Statistics](#derived-statistics)
4. [Character Creation](#character-creation)
5. [Skills](#skills)
6. [Perks & Flaws](#perks--flaws)
7. [Templates](#templates)
8. [Powers, Spells & Maneuvers](#powers-spells--maneuvers)
9. [Combat System](#combat-system)
10. [Character Advancement](#character-advancement)

---

## Core Mechanics

### The 3d6 Roll-Under System

Simverse uses a roll-under mechanic for all task resolution. When attempting an action:

1. **Roll 3d6** (three six-sided dice)
2. **Compare to your target number** (usually an Attribute or Attribute + Skill)
3. **Success**: If your roll is equal to or less than the target number
4. **Failure**: If your roll is greater than the target number

**Average human attribute is 10**, making most tasks reasonably achievable.

### Critical Results

- **Critical Success**: Rolling three 1s (1-1-1)
  - Automatic success with exceptional results
  - Counts as +10 margin of success
  - Best possible outcome plus a bonus effect

- **Critical Failure**: Rolling three 6s (6-6-6)
  - Automatic failure with complications
  - Counts as -10 margin (failure even with high skills)
  - Worst possible outcome plus extra problem (drop item, fall prone, etc.)

### Margin of Success

**Margin = Target Number - Roll Result**

- Higher margins indicate better performance
- Used in opposed contests
- Affects defender's roll in combat (each 5 margin = -1 to defender)
- Provides better information or results in skill checks

**Example:** Rolling 9 against a target of 14 = margin of 5 (good success)

### Difficulty Modifiers

The GM applies modifiers to make tasks easier or harder:

| Difficulty | Modifier | Example |
|------------|----------|---------|
| Very Easy | +4 | Climbing a ladder |
| Easy | +2 | Picking a simple lock |
| Average | +0 | Normal task |
| Moderate | -4 | Hitting an arm in combat |
| Hard | -6 | Hitting a head in combat |
| Very Hard | -8 | Performing surgery |
| Nearly Impossible | -10 | Defusing unknown alien tech |

**Modifiers apply to the target number, not the roll.**

### Taking Your Time

When there's **no time pressure or risk of failure**, you can assume a default roll of **10** instead of rolling dice. This represents careful, methodical work.

### Opposed Rolls

When two characters compete, there are three types of contests:

#### 1. Simple Contest
Both characters roll against their own target numbers and compare margins of success:
- Higher margin wins
- If both fail, nothing happens (stalemate)
- Used for: arm wrestling, races, debate contests

**Example:** Two characters arm wrestling both roll against ST. One gets margin 7, other gets margin 3. First character wins.

#### 2. Defense Rolls
One character attempts something, the other resists:
- Attacker rolls and calculates margin
- Each 5 points of attacker's margin = -1 to defender's target number
- Defender rolls to resist
- Used for: combat attacks, mental domination, intimidation

**Example:** Mind control spell hits with margin 12. Defender must resist at -2 to their Wisdom roll.

#### 3. Complex Contest
A race to accumulate successes:
- Set a target number of successes needed (e.g., 20)
- Set maximum number of rolls allowed (e.g., 10)
- Each roll adds margin of success to total
- First to reach target wins, or whoever has most after max rolls
- Used for: hacking battles, extended chases, research competitions

---

## Attributes

Characters have **7 primary attributes** that define their capabilities:

| Attribute | Abbreviation | Governs |
|-----------|--------------|---------|
| **Dexterity** | DX | Agility, reflexes, coordination, ranged combat |
| **Intellect** | IN | Reasoning, memory, learning, technical skills |
| **Wisdom** | WS | Willpower, mental defense, intuition, sixth sense |
| **Charisma** | CH | Social influence, leadership, attractiveness |
| **Endurance** | EN | Stamina, health, resisting fatigue/poison |
| **Awareness** | AW | Perception, initiative, luck, magical intuition |
| **Strength** | ST | Physical power, melee damage bonus, carrying capacity |

### Attribute Scale

- **Range**: 5 to 20 (can go higher with supernatural templates)
- **Human Average**: 10
- **Starting Value**: All attributes begin at 10

### Attribute Costs

Attributes cost Character Points (CP) to raise or lower from baseline (10):

#### Major Attributes (DX, IN, WS, CH)
These govern most skills and are more expensive:

| Level Range | Cost per Level |
|-------------|----------------|
| 5-10 | 10 CP (going down gives +10 CP) |
| 10-15 | 10 CP |
| 15-20 | 20 CP |
| 20-25 | 40 CP |
| 25-30 | 80 CP |
| And so on (doubling) | |

**Example:** Raising DX from 10 to 15 costs: 10+10+10+20+20 = 70 CP

#### Minor Attributes (ST, AW, EN)
These are less central to most builds:

| Level Range | Cost per Level |
|-------------|----------------|
| Any | 5 CP (flat) |

**Example:** Raising ST from 10 to 15 costs: 5×5 = 25 CP

---

## Derived Statistics

Several important values are calculated from your attributes:

### Vitality (HP)
**Vitality = EN × 2**

- Represents physical health and injury tolerance
- Damage from combat reduces Vitality
- At 0 Vitality: unconscious
- At -EN Vitality: death (unless you have Hard to Kill perk)
- Recovers AW/2 per long rest (8 hours sleep)
- Can purchase Extra Vitality / Low Vitality to increase/decrease individually

### Stamina
**Stamina = ST × 2**

- Represents physical exhaustion
- Spent on: running, climbing, heavy lifting, physical combat maneuvers
- At 0 Stamina: exhausted (-4 to all physical actions)
- Recovers ST/2 per short rest (1 hour break)
- Can purchase Extra Stamina / Low Stamina to increase/decrease individually

### Mana
**Mana = AW × 2**

- Represents mental/magical energy
- Spent on: spells, psychic powers, supernatural effects
- At 0 Mana: mentally depleted (-4 to all mental actions)
- Reduced by: mental strain, trauma, shock, extended study
- Recovers AW/2 per short rest (1 hour break)
- Can purchase Extra Mana / Low Mana to increase/decrease individually

### Speed
**Speed = (DX + EN) / 4** (don't round)

- Determines initiative order in combat
- Determines movement rate
- Average human: Speed 5
- Used for dodging
- Used for surprise rolls (roll vs Speed × 2)

### Perception
**Perception = (IN + AW) / 2**

- Used for noticing things, spotting hidden enemies
- Can be modified by Acute Senses or penalties like One Eye

### Strength Damage Bonus
**Damage Bonus = (ST - 10) / 2** (round down)

- Adds to melee and thrown weapon damage
- ST 10-11: +0 damage
- ST 12-13: +1 damage
- ST 14-15: +2 damage
- ST 16-17: +3 damage
- ST 18-19: +4 damage
- ST 20-21: +5 damage
- ST 8-9: -1 damage
- ST 6-7: -2 damage

**Dice Conversion:** When damage modifier reaches +7 or higher, convert to additional damage dice instead:
- 1d6+7 becomes 3d6
- 1d6+8 becomes 3d6+1
- 2d6+7 becomes 4d6
- Each additional +6 adds another 1d6

**Example:** Character with ST 18 (+4 damage) using longsword (2d6-1):
- Base: 2d6-1
- With ST bonus: 2d6-1+4 = 2d6+3 damage

---

## Character Creation

### Character Point Budget

Characters are built by spending Character Points (CP) based on campaign power level:

| Power Level | CP Budget | Description |
|-------------|-----------|-------------|
| Street Level | 200 CP | Normal humans, investigators, criminals |
| Heroic | 250 CP | Adventurers, soldiers, starting heroes |
| Superheroic | 400 CP | Legendary warriors, powerful mages |
| Cosmic | 500+ CP | Demigods, apocalyptic threats |

**Standard starting game: 250 CP**

### Flaw Limit

- Characters can take Flaws (disadvantages) to gain extra CP
- **Maximum**: -50 CP worth of Flaws
- Taking more Flaws later grants 0 CP (narrative only)
- Can buy off Flaws with CP + roleplay justification

### Creation Steps

1. **Choose Templates** (optional but recommended)
   - Pick a Race template
   - Pick a Profession template
   - Pay total CP cost

2. **Set Attributes**
   - All start at 10
   - Raise or lower using CP costs
   - Apply template modifiers

3. **Calculate Derived Stats**
   - Vitality, Stamina, Mana, Speed, Perception

4. **Purchase Perks**
   - Choose advantages that fit your concept
   - Some Perks required for certain abilities (e.g., Mage Gift for spells)

5. **Take Flaws** (optional, max -50 CP)
   - Add complications and disadvantages
   - Gain extra CP to spend

6. **Buy Skills**
   - Purchase skill levels using Fibonacci costs
   - Templates may include starting skills

7. **Acquire Powers/Spells/Maneuvers**
   - Build custom abilities or choose pre-made ones
   - Costs vary widely based on power

8. **Gear & Equipment**
   - Starting equipment from templates or purchased with starting funds

9. **Final Touches**
   - Name, background, personality
   - Calculate final values

---

## Skills

Skills represent trained abilities and specialized knowledge. They are always rolled by adding the skill level to a governing attribute.

**Roll: Attribute + Skill Level**

### Skill Types

#### Regular Skills
- Have a **default value** = Attribute - 2
- Can attempt untrained (at default value)
- Examples: Most combat skills, athletics, tracking

#### Hard Skills
- **No default** - must have at least 1 level to attempt
- Represent specialized training or knowledge
- More expensive to learn
- Examples: Surgery, engineering, lockpicking, occult knowledge

### Skill Costs (Fibonacci Progression)

Skills use Fibonacci costs to represent diminishing returns:

| Skill Level | Regular Skill Cost | Hard Skill Cost | Cumulative (Regular) | Cumulative (Hard) |
|-------------|-------------------|-----------------|----------------------|-------------------|
| 1 | 1 CP | 5 CP | 1 CP | 5 CP |
| 2 | 2 CP | 8 CP | 3 CP | 13 CP |
| 3 | 3 CP | 13 CP | 6 CP | 26 CP |
| 4 | 5 CP | 21 CP | 11 CP | 47 CP |
| 5 | 8 CP | 34 CP | 19 CP | 81 CP |
| 6 | 13 CP | 55 CP | 32 CP | 136 CP |
| 7 | 21 CP | 89 CP | 53 CP | 225 CP |
| 8 | 34 CP | 144 CP | 87 CP | 369 CP |
| 9 | 55 CP | 233 CP | 142 CP | 602 CP |
| 10 | 89 CP | 377 CP | 231 CP | 979 CP |

**Hard skills cost structure:** Each level costs (Fibonacci Progression, but starting at 5)

**Note:** Skills can exceed level 10, but costs continue following Fibonacci sequence. Level 10 represents a grandmaster who's trained for a decade.

### Skill Specializations

At **skill level 5 or higher**, you can specialize:
- **Benefit**: +2 to rolls with that specific specialization
- **Example**: Swords 5 (Longswords)  → +2 with longswords only

### Training Time

Learning skills requires time investment:

**1 CP worth of training per week (base)**

Modifiers:
- **Good teacher**: 1.5 CP per week (+50%)
- **Good books/resources**: 1.5 CP per week (+50%)
- **Both teacher AND resources**: 2 CP per week (maximum)
- **Hard skills**: Require at least a teacher OR quality resources

**Advancement Exception**: Skills used actively in recent sessions (last 3 sessions) require no training time when improving with earned CP.

**Learning New Skills**: Takes half the normal training time when learning something completely new, if also spending CP.

### Common Skills

#### Combat Skills (DX-based)
- Swords, Axes, Spears, Bows, Crossbows, Throwing, Brawling, Shield

#### Physical Skills (DX-based)
- Athletics (DX), Running (DX/EN), Climbing (DX/ST), Swimming (DX/EN), Stealth (DX), Acrobatics* (DX)

#### Social Skills (CH-based unless noted)
- Persuasion, Intimidation (CH/ST), Deception, Leadership, Performance

#### Knowledge Skills (IN-based)
- History, Nature, Tactics, Research

#### Technical Skills (IN-based)
- Engineering*, Medicine*, Surgery*, Alchemy*, Lockpicking* (IN/DX)

#### Perception Skills (Regular)
- Perception (AW+IN)/2, Tracking (WS/AW), Survival (IN/AW)

#### Magic Skills (varies)
- Spellcasting (IN), Psionics (WS), Occult Knowledge* (IN)

\* for HARD skills

---

## Perks & Flaws

Perks represent advantages, talents, and special abilities. Flaws represent disadvantages and complications that make interesting characters.

### Perks

#### Combat Perks

**Combat Reflexes** (15 CP)
- +2 to Speed for initiative purposes
- Never surprised in combat

**Weapon Master** (10 CP)
- Choose one weapon type
- +2 to attack and parry with that weapon

**Martial Arts Training** (20 CP)
- Unarmed attacks deal +2 damage
- Can make unarmed attack as Minor Action
- +2 to all defense rolls when unarmored
- Can parry ranged attacks at -4 (requires hand free)

**Ambidextrous** (5 CP)
- No penalty for using off-hand
- Can wield two weapons effectively

**Tough** (10 CP)
- +5 Vitality

**Hard to Kill** (15 CP)
- Don't fall unconscious until -2× Vitality
- Survive injuries that would kill others

**Relentless** (10 CP)
- When reduced to 0 Vitality, can take one more action before falling unconscious
- Adrenaline surge keeps you fighting for crucial moments

**Armor Familiarity** (5 CP)
- Reduce armor penalties by 2
- Medium armor: -0 penalty (instead of -2)
- Heavy armor: -2 penalty (instead of -4)

**Heavy Armor Familiarity** (10 CP)
- Reduce armor penalties by 4
- Medium armor: -0 penalty (instead of -2)
- Heavy armor: -0 penalty (instead of -4)

#### Physical Perks

**Athletic** (10 CP)
- +2 to all outdoor physical skills
- Running, climbing, swimming, etc.

**Fast Healer** (10 CP)
- Recover double Vitality per long rest
- Wounds heal in half the time

**Night Vision** (10 CP)
- No penalties in darkness or low light
- Can see clearly in moonlight/starlight

**Acute Senses** (5 CP per sense)
- +2 to Perception rolls with chosen sense
- Options: Sight, Hearing, Smell, Touch, Taste

**High Pain Threshold** (10 CP)
- Ignore first -2 from injury penalties
- Can function better when wounded

**Natural Armor** (10 CP)
- +2 AR from thick skin, scales, or chitin
- Stacks with worn armor

**Damage Resistance** (15 CP per type)
- Take half damage from chosen damage type
- Options: Fire, Cold, Lightning, Acid, Poison
- Can be taken multiple times for different types

**Resilient** (10 CP)
- +2 to resist poison and disease
- Hardy constitution and strong immune system

**Sneaky** (5 CP)
- +2 to Stealth checks
- Natural talent for moving quietly and unseen

**Extra Speed** (10 CP / level)
- +1 to Speed 

**Extra Vitality** (10 CP / level)
- +5 to Vitality 

**Extra Stamina** (10 CP / level)
- +5 to Stamina

#### Mental Perks

**Eidetic Memory** (15 CP)
- Perfect recall of anything seen/heard
- +4 to all memory-based knowledge rolls

**Strong Willed** (10 CP)
- +2 to resist mental effects
- Mind control, fear, intimidation

**Quick Learner** (15 CP)
- Learn all skills 50% faster
- Reduces training time significantly

**Natural Talent** (5 CP)
- Choose one skill
- Learn that skill at half CP cost (round up)

**Curious** (5 CP)
- +2 to Investigation and Research
- Natural inquisitiveness and desire to learn

**Tinker** (15 CP)
- Can create magical gadgets and devices
- Spend 1 week and materials worth spell's CP × 10 sp to create single-use item that casts a spell you know
- Can have IN/2 active items at once
- Requires Mage Gift perk

**Animal Companion** (15 CP)
- Loyal animal companion follows and aids you
- GM determines stats (typically ~50 CP creature)
- Can be replaced if killed (requires time and training)

**Familiar** (30 CP)
- Permanent bond with summoned magical creature (up to ~100 CP worth)
- Mental contact allows communication and seeing through its eyes
- Can possess familiar to control it directly
- Can resummon if killed (costs 10 Mana, 1 hour ritual)
- Requires Mage Gift perk
- Common choices: imp, pseudodragon, sprite, cat, owl, raven

#### Social Perks

**Charismatic Leader** (10 CP)
- Allies within 10m get +1 to morale rolls
- Inspiring presence in battle

**Wealthy** (5/10/15 CP)
- Start with 5× / 10× / 20× normal resources
- Easier access to equipment and services

**Connected** (5-15 CP, varies)
- Have contacts in organizations
- Cost depends on power/influence of contacts

**Attractive** (5 CP)
- +2 to social rolls based on appearance
- First impressions and charm

**Intimidating** (5 CP)
- +2 to Intimidation rolls
- Imposing presence and commanding demeanor

#### Supernatural Perks

**Mage Gift** (20 CP)
- Required to learn and cast spells
- Opens access to magical abilities

**Psychic** (20 CP)
- Can learn and use psychic powers
- Mental abilities beyond normal

**Magic Resistance** (15 CP)
- +4 to resist all spells and magical effects
- Natural immunity to magic

**Second Sight** (10 CP)
- Can see invisible creatures and magical auras
- Perceive supernatural phenomena

**Lucky** (10 CP)
- Once per session, reroll any one failed roll
- Must use second result even if worse

**Extra Mana** (10 CP / level)
- +10 to Mana pool

### Flaws

#### Combat Flaws

**Slow Reflexes** (-10 CP / level)
- -1 to Speed
- React slower than others

**Poor Vision** (-5 CP / level)
- -1 to all ranged attack rolls
- Difficulty seeing at distance

**Pacifist** (-15 CP)
- Will not kill or seriously harm except in extreme self-defense
- Must justify violent actions

#### Physical Flaws

**Low Vitality** (-10 CP)
- -10 Vitality

**Low Stamina** (-10 CP)
- -10 Stamina

**One Eye** (-15 CP)
- -3 to ranged attacks
- -2 to Perception rolls

**Lame** (-5 CP / level)
- Movement speed reduced by 1, dodge not affected
- Permanent injury or condition

**Chronic Pain** (-10 CP)
- -1 to all physical actions
- Constant discomfort

**Fragile** (-15 CP)
- Injuries take double time to heal
- Slower recovery from wounds

**Undead** (-30 CP)
- Character is undead (resurrected as zombie, vampire, lich, etc.)
- **Advantages:**
  - No need to breathe, sleep, eat, or drink
  - Immune to poison, disease, and suffocation
  - Resistant to impaling and cutting damage (takes half damage from these types, as they don't bleed or have vital organs)
- **Disadvantages:**
  - Unable to heal naturally (must use magic or necromancy to restore Vitality)
  - Vulnerable to holy damage (takes double damage from holy/divine sources)
  - Vulnerable to fire damage (takes double damage from fire)
  - Social stigma in most civilizations (-4 to social interactions with living)
  - May be turned or destroyed by clerics/paladins
  - Cannot benefit from normal healing magic (Cure spells, etc.)

#### Mental Flaws

**Phobia** (-5 to -15 CP, severity varies)
- Must roll WS vs 12 when encountering phobia
- Failure: freeze, flee, or panic
- Cost depends on commonality of trigger

**Addiction** (-10 to -20 CP)
- Need substance regularly
- Penalties without it, compulsion to obtain

**Overconfident** (-10 CP)
- Underestimate dangers and opponents
- Must roll WS to retreat from fights

**Low Mana** (-10 CP)
- -10 to Mana pool
- Less magical/mental endurance

**Partial Amnesia** (-15 CP)
- Character doesn't remember recent events or portions of their past
- May recover memories over time by rolling WS vs 12 (GM determines frequency and what is recovered)
- -2 to Knowledge skills relating to forgotten period
- Often acquired through resurrection or traumatic brain injury

#### Social Flaws

**Hideous Appearance** (-10 CP)
- -2 to reaction rolls with common folk
- Demonic, monstrous, or disfigured features

**Social Stigma** (-10 CP)
- -2 to social interactions with certain groups
- Prejudice, criminal record, or pariah status

**Enemy** (-5 to -20 CP)
- Someone actively opposes you
- Cost varies by enemy's power and determination

**Debt** (-10 CP)
- Owe significant money or favors
- Obligations that complicate adventures

**Code of Honor** (-10 CP)
- Must follow strict personal rules
- Cannot break code without severe guilt/consequences


#### Character Size Modifiers

Characters of different sizes experience significant changes to their physical capabilities and survivability. Size affects Strength, Dexterity, Vitality, and movement speed. Smaller creatures are more agile but fragile, while larger creatures are stronger and tougher but less nimble. Since ST affects damage output, size directly impacts combat effectiveness - smaller creatures deal less damage while larger creatures hit harder.

**Size Categories and Modifiers:**

| Size Category | Cost (CP) | Height | ST Mod | DX Mod | Vitality/Movement/AR × | Examples |
|---------------|--------|--------|--------|--------|------------|----------|
| **Tiny** | -80 | 1-5cm | -8 | +8 | ×0.1 | Ant, bee, mouse |
| **Miniature** |-40 | 10-20cm | -6 | +6 | ×0.25 | Fairy, pixie, rat |
| **Small** | -20 | 50cm-1m | -4 | +4 | ×0.5 | Small child, cat, small dog |
| **Child/Dwarf** | -10 | 1m-1.3m | -2 | +2 | ×0.75 | Dwarf, human child, goblin |
| **Human** | 0 | 1.5-2m | 0 | 0 | ×1 | Human, elf, orc |
| **Large** | 10 | 2.5-3m | +2 | -2 | ×1.5 | Ogre, large troll, horse |
| **Huge** | 20 | 4-5m | +4 | -4 | ×2.0 | Giant, elephant |
| **Gigantic** | 40 | 8-10m | +6 | -6 | ×2.5 | Large dragon, titan |
| **Colossal** | 80 | 16m+ | +8 | -8 | ×3.0 | Ancient dragon, kaiju |

**Special Size Rules:**
- **Armor and Equipment**: Armor AR values are proportional, but cost and weight scale with size (×2 cost per size category up, ×0.5 per category down)


---

## Templates

Templates are pre-built packages of attributes, perks, skills, and equipment that speed up character creation. They cost exactly what their components are worth.

### Race Templates

**Note:** Human is the baseline (0 CP). Other races modify from this baseline.

#### Elf (55 CP)
**Attribute Modifiers:**
- DX +2 (20 CP)
- AW +1 (5 CP)
- EN -1 (-5 CP)
- ST -1 (-5 CP)

**Included Perks:**
- Night Vision (10 CP)
- Acute Senses - Hearing (5 CP)
- **Forest Movement** (5 CP): No terrain penalty in woodlands
- **Graceful** (10 CP): +1 to Stealth and Acrobatics skills
- **Extended Lifespan** (5 CP): ~300 years

---

#### Dwarf (45 CP)
**Size Modifier:**
- **Child/Dwarf Size** (-10 CP): ST -2, DX +2, Vitality ×0.75, Movement ×0.75

**Additional Attribute Modifiers:**
- ST +3 (15 CP) - Net +1 after size modifier
- EN +2 (10 CP)
- DX -3 (-15 CP) - Net -1 after size modifier
- CH -1 (-10 CP)

**Included Perks:**
- Tough (10 CP)
- Magic Resistance (15 CP)
- **Night vision** (10 CP): See perfectly in darkness up to 30m
- **Stubborn** (5 CP): +2 to resist intimidation/persuasion
- **Mountain Movement** (5 CP): No penalty on rocky/underground terrain
- **Extended Lifespan** (5 CP): ~200 years

---

### Profession Templates

#### Warrior (33 CP)

**Starting Skills:**
- Choose one weapon skill 3 (6 CP)
- Shield 2 (3 CP)
- Tactics 2 (3 CP)
- Athletics 1 (1 CP)

**Included Perks:**
- Armor Familiarity (5 CP)
- Combat Reflexes (15 CP)

**Starting Equipment:**
- Medium armor (AR 3, AD 1)
- One martial weapon of choice
- Medium shield (SD 2)
- Basic adventuring gear

**Note:** Most warriors invest 20-30 CP in combat maneuvers (Shield Bash, Power Attack, Disarm, etc.). See [Simverse_Powers_Library.md](Simverse_Powers_Library.md) for available maneuvers

---

#### Scout/Ranger (29 CP)

**Starting Skills:**
- Bow 3 (6 CP)
- Stealth 3 (6 CP)
- Tracking 3 (6 CP)
- Survival 2 (3 CP)
- Perception 2 (3 CP)

**Included Perks:**
- Acute Senses - choose one (5 CP)

**Starting Equipment:**
- Light armor (AR 2, AD 0)
- Bow with 30 arrows (2d6 damage, 100m range)
- Hunting knife (1d6-2)
- Camping and survival gear

**Note:** Most scouts invest 20-30 CP in combat maneuvers (Precision Strike, Aimed Shot, etc.). See [Simverse_Powers_Library.md](Simverse_Powers_Library.md) for available maneuvers

---

#### Wizard (65 CP)

**Starting Skills:**
- Spellcasting 3 (6 CP)
- Occult Knowledge 3 - Hard (26 CP: 5+8+13)
- Research 2 (3 CP)

**Included Perks:**
- Mage Gift (20 CP) [required for spells]
- Extra Mana (10 CP)

**Starting Equipment:**
- Wizard robes (AR 0)
- Staff (1d6-1 damage, spellcasting focus)
- Spellbook
- Component pouch

**Note:** Most wizards invest ~45-50 CP in spells (10-15 Minor/Moderate spells)

---

#### Rogue (48 CP)

**Starting Skills:**
- Stealth 4 (11 CP: 1+2+3+5)
- Lockpicking 3 - Hard (26 CP: 5+8+13)
- Sleight of Hand 2 (3 CP)
- Perception 2 (3 CP)

**Included Perks:**
- Ambidextrous (5 CP)

**Starting Equipment:**
- Light armor (AR 1, AD 0)
- Two daggers (1d6-2 each)
- Thieves' tools
- Grappling hook and rope

**Note:** Most rogues invest 15-25 CP in combat maneuvers (Sneak Attack, Feint, Precision Strike, etc.). See [Simverse_Powers_Library.md](Simverse_Powers_Library.md) for available maneuvers

---

### Mixing Templates

Templates can be combined freely. Simply add their costs together:

**Example: Elf Scout**
- Elf (55 CP) + Scout (29 CP) = **84 CP total**
- Remaining budget (250 CP start): **166 CP**
- Gets all benefits from both templates
- Attribute modifiers stack: Base 10 DX → +2 from Elf = 12 DX
- Has Night Vision, Acute Hearing, Forest Movement, Graceful, AND Scout skills/equipment
- Typically invests 20-30 CP in combat maneuvers and attributes

**Example: Dwarf Warrior**
- Dwarf (45 CP) + Warrior (33 CP) = **78 CP total**
- Remaining budget: **172 CP**
- Tough, Magic Resistant, Night vision, Stubborn
- Typically invests 20-30 CP in combat maneuvers and attributes
- Natural dungeon delver with combat prowess

---

## Powers, Spells & Maneuvers

This unified system allows you to create supernatural powers, magical spells, and combat maneuvers using the same construction rules.

### Base Effect Types

All abilities start with a base effect tier that determines CP cost and resource cost:

| Tier | Min Skill Level | CP Base | Resource Cost (Stamina/Mana) | Examples |
|------|-----------------|---------|------------------------------|----------|
| **Minor** | 2 | 1 CP | 1 | Shield Bash, Trip, Disarm, Quick Draw, Feint |
| **Moderate** | 3 | 5 CP | 2 Mana | 1d6 damage bolt, minor healing, charm person, detect magic |
| **Major** | 5 | 15 CP | 6 Mana | 3d6 damage, serious healing, flight, invisibility, lightning bolt |
| **Epic** | 8 | 30 CP | 12 Mana | 6d6+ damage, teleportation, open portal, time stop, raise dead |
| **Legendary** | 13 | 50 CP | Varies | World-altering effects, deity-level powers |

**Skill Level Requirement**: To purchase a power of a given tier, you must have the minimum skill level in the relevant skill (Spellcasting for spells, weapon skill for combat maneuvers, etc.). This represents the mastery needed to learn and perform that tier of ability.

**Design Goal:** Starting wizard (~50 CP for spells) should have 10-15 Minor/Moderate spells. Starting warrior/thief (~25 CP for maneuvers) should have ~10 Minor/Moderate maneuvers.

**Resource Types:**
- **Physical Maneuvers**: Usually cost Stamina
- **Spells/Powers**: Usually cost Mana
- **Extreme Effects**: Some may cost Vitality (blood magic, self-sacrifice)

**Alternative Energy Sources**: Wizards can use power stones, ritual circles, ley lines, or blood sacrifice to provide Mana for spells beyond their personal pool.

### Enhancements (Percentage-Based)

These modify the cost by a percentage:

| Enhancement | Cost Modifier | Description |
|-------------|---------------|-------------|
| **Increased Effect** | +50% per +1d6 | More damage, healing, or bonus |
| **Increased Damage** | +50% per +1d6, +100% for +2d6 | Specifically for damage powers (same as Increased Effect) |
| **Extra Range** | +20% (2× range), +40% (4× range) | 10m → 20m (+20%), 10m → 40m (+40%), etc. |
| **Expansive Range** | +100% (100× range) | For very long range effects. 10m → 1km (+100%). Each point skill roll succeeds by doubles maximum range. |
| **Extra Duration** | +10% (2×), +20% (6×), +30% (12×), +40% (72×), +50% (288×), then +10% per doubling | Default 5 min: +10% (10 min), +20% (30 min), +30% (1 hour), +40% (6 hours), +50% (1 day), +60% (2 days), etc. |
| **Area Effect** | +50% (3m radius), +100% (6m) | Affects multiple targets in area |
| **Multiple Targets** | +50% (2 targets), +75% (3), +125% (5) | Add specific targets (not area) |
| **Reduced Resource Cost** | +25% (half cost), +50% (quarter) | Costs less Mana/Stamina to use, if below 1, round to 0 |
| **Weakened Resistance** | +10% per -2 penalty | Target gets -2 to resist (stackable) |
| **Instant Action** | +25% | Can interrupt or use mid-action |
| **Persistent** | +20% | Effect continues without concentration |
| **Reliable Activation** | +100% | No skill roll needed, automatically activates (costs resources but always works) |
| **Armor Piercing** | +50% | Ignores 2 points of armor |
| **Homing** | +50% | Auto-hit, no attack roll needed (e.g., Magic Missile) |
| **Knockback** | +30% | Push target 2m on successful hit |
| **Silent Casting** | +80% | No visible or audible manifestation |
| **Fast Cast** | +100% | Reduce casting/activation time by 50% |

**Note on Skill Rolls:** By default, activating a power/spell/maneuver requires a successful skill roll (Spellcasting for spells, weapon skill for maneuvers, etc.). The "Reliable Activation" enhancement below removes this requirement.


### Limitations (Percentage-Based)

These reduce the cost by a percentage:

| Limitation | Cost Modifier | Description |
|------------|---------------|-------------|
| **Only in [Condition]** | -5% to -40% | Only works in specific conditions. **Frequency determines discount**: -5% common (day/night/sunlight), -10% uncommon (rain/dark/touching earth), -20% rare (solar eclipse/vs undead/target ≤20 Vitality), -40% nearly impossible (lunar eclipse at midnight/target willing to die) |
| **Requires [Item]** | -10% | Need specific tool/weapon/holy symbol/visible object/willing target that must be present |
| **Usage Limit** | -15% (3/day), -30% (1/day), -40% (1/week) | Limited uses per time period |
| **Preparation Time** | -10% (1 min), -20% (10 min), -30% (1 hour) | Must prepare/ritual before use |
| **Obvious/Loud** | -10% | Clearly visible flash/sound, alerts everyone nearby, obvious if resisted |
| **Concentration** | -20% | Can't take other actions while using, broken if interrupted |
| **Backfire Risk** | -30% | On critical failure, lose resources, suffer effect, or summon attacks you |
| **Increased Resource Cost** | -25% (double cost), -50% (triple) | Costs more to use, cheaper to buy |
| **Fragile** | -25% | Broken by any damage to user, or by specific trigger (attack, strong emotions) |
| **Situational Trigger** | -20% | Only works after specific event (successful Parry, being attacked, ally knocked out, etc.) |
| **Gesture Required** | -10% | Need free hand to use (can't use while grappled/bound) |
| **Verbal Component** | -10% | Must speak/chant to activate (can't use while silenced) |
| **Melee Range Only** | -15% | Must be adjacent to target (touch range) |
| **Self Only** | -25% | Cannot target others, only yourself |
| **Exhausting** | -25% | Take 1 Vitality damage when used |
| **Strenuous** | -25% | After use, suffer -2 to all actions for 10 minutes |
| **Cannot Cast** | -25% | Cannot use spellcasting or other powers while this power is active (only for powers with duration) |

**Note:** By default, most powers require a skill roll to activate. This is not a limitation - it's the baseline.

### Construction Rules

1. **Choose Base Effect**: Select tier (Minor 1 CP / Moderate 5 CP / Major 15 CP / Epic 30 CP / Legendary 50+ CP)
2. **Add Enhancements**: Apply percentage-based enhancements from the tables above
3. **Add Limitations**: Apply percentage-based limitations from the tables above
4. **Calculate Total Cost**:
   - **Formula**: Base × (1 + Sum of Enhancements - Sum of Limitations)
   - **Example**: 5 CP × (1 + 0.50 - 0.10 - 0.15) = 5 × 1.25 = 6.25 → 6 CP
   - **Round down**, minimum 1 CP
5. **Maximum Reduction**: Total limitations cannot exceed -75% (net modifier cannot go below 0.25 = 25% of base cost)

### Example Powers

#### Shield Bash (Physical Maneuver)
- **Base**: Minor Effect (1 CP, 1 Stamina)
- **Effect**: Stun opponent, they roll vs EN or lose next action
- **Enhancement**: None
- **Limitation**: Requires [Item] -10%, Melee Range Only -15%
- **Calculation**: 1 × (1 + 0 - 0.10 - 0.15) = 1 × 0.75 = 0.75, round down minimum 1 CP
- **Final Cost**: 1 CP
- **Usage**: Roll Shield skill to activate, costs 1 Stamina, opponent resists vs EN

#### Fire Bolt (Moderate Spell)
- **Base**: Moderate Effect (5 CP, 2 Mana)
- **Effect**: 1d6 fire damage, ranged attack
- **Enhancement**: Extra Range +20%, Increased Damage +100% (2d6 total)
- **Limitation**: Verbal Component -10%
- **Calculation**: 5 × (1 + 0.20 + 1.00 - 0.10) = 5 × 2.10 = 10.5, round down to 10 CP
- **Final Cost**: 10 CP
- **Usage**: Costs 2 Mana, roll Spellcasting vs target's Dodge

#### Power Attack (Combat Maneuver)
- **Base**: Moderate Effect (5 CP, 2 Stamina)
- **Effect**: Next attack deals +2d6 damage
- **Enhancement**: Increased Damage +100%
- **Limitation**: Obvious/Loud -10%, Melee Range Only -15%
- **Calculation**: 5 × (1 + 1.00 - 0.10 - 0.15) = 5 × 1.75 = 8.75, round down to 8 CP
- **Final Cost**: 8 CP
- **Usage**: Costs 2 Stamina, attack at -2 to hit, if hit deal weapon damage +2d6

#### Teleport (Major Spell)
- **Base**: Major Effect (15 CP, 6 Mana)
- **Effect**: Teleport up to 50m to visible location
- **Enhancement**: Extra Range +40%
- **Limitation**: Concentration -20%, Obvious/Loud -10%, Verbal Component -10%
- **Calculation**: 15 × (1 + 0.40 - 0.20 - 0.10 - 0.10) = 15 × 1.00 = 15 CP
- **Final Cost**: 15 CP
- **Usage**: Costs 6 Mana, must see destination, flash of light and sound

---

## Combat System

### Initiative

**Speed** determines who acts first:
- Everyone compares their Speed value
- Highest Speed acts first, then descending order
- Ties: Higher AW acts first, then simultaneous

**Surprise Encounters:**
- Surprised party members roll vs Speed × 2
- Each 5 margin of success/failure = +1 / -1 to Speed this round
- Example: Speed 5 character rolls 8 vs target 10 → margin 2 → no bonus

### Action Economy

Each character gets per turn:
- **1 Major Action**: Attack, cast spell, full movement, activate power
- **1 Minor Action**: Draw weapon, shout command, quick look around
- **1 Reaction**: Defense roll (dodge/parry/block) when attacked
- **Free Actions**: Drop item, speak briefly (GM discretion)

**Full Defense**: Use Major Action to take up to 3 defense reactions this turn instead of 1

### Movement

Based on your Speed value:
- **Half Move**: Speed in meters (can do with other Major Action)
- **Full Move**: Speed × 2 meters (takes your Major Action)
- **Sprint**: Speed × 4 meters (Major Action + 1 Stamina per turn)

**Difficult Terrain**: Costs double movement (half speed)

### Attack Resolution

1. **Attacker Rolls**: Roll weapon skill (DX + Skill Level + modifiers)
2. **Calculate Margin**: Target number - roll result
3. **Defender Chooses Defense**: Dodge, Parry, or Block
4. **Apply Attacker's Margin**: Each 5 margin = -1 to defender's roll
5. **Defender Rolls**: Roll chosen defense
6. **Compare**: If defender succeeds, attack misses. If fails, attack hits.
7. **Roll Damage**: Roll weapon damage dice
8. **Apply Armor**: Subtract Armor Resistance (AR) of the targeted location
9. **Apply to Vitality**: Remaining damage reduces Vitality

### Defense Options

You get **1 Reaction per turn** (3 if using Full Defense):

#### Dodge
**Target Number: DX/2 + Armor Deflection (AD)**
- Use agility to avoid attack entirely
- Works against any attack type
- Not penalized by acting this turn
- Armor's AD helps (padding gives you room to move)

#### Parry
**Target Number: (DX + Weapon Skill)/2**
- Use your weapon to deflect attack
- **Penalty**: -4 if you attacked with that weapon this turn
- Only works against melee attacks
- Weapon damage rules apply if you fail badly

#### Block
**Target Number: (DX + Shield Skill)/2 + AD + Shield Deflection (SD)**
- Use shield to block attack
- Best defense values when specialized
- Only works against frontal attacks
- Shield damage rules apply if you fail with damage taken

### Damage

**Damage = Weapon Damage Roll + ST Bonus - Armor Resistance (AR)**

**Minimum Damage Rule:** If final damage after all modifiers is 0 or negative, before reducing AR, the attack still deals **1 Vitality damage** . Ex.: 1d-3 -1 for ST damage rolls for 2, the damage would be 2-3-1 = -2, but it will still be 1. But then, an AR of 1 will bring it down to zero.

Weapons have damage dice notation:
- Knife: 1d6-3
- Sword: 2d6-1
- Greatsword: 3d6+2
- Bow: 2d6
- Crossbow: 2d6+2

**Add ST Damage Bonus** to all melee and thrown weapon damage (see Derived Statistics).

**Margin does not affect damage** - only hit/miss and defender's penalty

**Knockback** - each 10 points of sheer damage that is received (not blocked, parried or dodged), even if absorbed by armor will cause 1m knockback.

---

### Damage Types

Different damage types interact with armor differently:

#### Bludgeoning Damage (Most Common)
- **Sources:** Clubs, maces, hammers, fists, falls, most magic
- **Effect:** AR applies normally, remaining damage to Vitality
- **Examples:** Warhammer (2d6 bludgeoning), punch (1d6-3 bludgeoning)

#### Cutting Damage
- **Sources:** Swords, axes, slashing weapons
- **Effect:** AR applies **double** (AR 4 counts as 8 vs cutting), but damage that gets through causes **bleeding**
- **Bleeding:** Victim loses 1 Vitality per turn until treated (First Aid roll as Minor Action)
- **Examples:** Longsword (2d6-1 cutting), battleaxe (2d6 cutting)

#### Impaling Damage
- **Sources:** Spears, arrows, piercing weapons, stabs
- **Effect:** Subtract 1 damage per die rolled (before AR), but damage that penetrates AR is **doubled**
- **Examples:** Spear thrust (1d6+1 impaling), arrow (1d6+2 impaling), dagger thrust (1d6-3 impaling)
- **Calculation:** Roll damage + ST bonus, subtract AR, then double remaining damage
- **Dual damage type weapons:** Swords and similar weapons that can be used for swinging or thrusting have the default listed damage for swingind, if you use the same weapon for thrusting, you just reduce 1 damage per dice. E

**Example 1 - Arrow (1 die):**
- Arrow (1d6+2 impaling) + ST 12 (+1): rolls 5 on die
- 5 + 2 + 1 = 8 damage
- vs AR 2: 7 - 2 = 5 gets through
- Impaling doubles: 5 × 2 = **10 Vitality damage**

**Example 2 - Heavy Spear (2 dice):**
- Spear (2d6 impaling) + ST 14 (+2): rolls 9 on dice
- 9 + 2 = 11 damage
- vs AR 3: 11 - 3 = 8 gets through
- Impaling doubles: 8 × 2 = **16 Vitality damage**

**Example 2 - Longsword thrusting:**
- Attacker with ST 14 (+2) uses longsword (2d6-1 cutting) thrusting target with AR 4.
- Roll: 7 on 2d6-1 -2 (-1 per dice) = 4 damage + 2 ST = 6 damage total
- vs AR 4: 6 - 4 = 2 (x2 because of impaling damage) = 4 damage to Vitality

**Example 3 - Longsword swinging:**
Attacker with ST 14 (+2) uses longsword (2d6-1 cutting) for swinging against target with AR 4.
- Roll: 7 on 2d6-1 = 6 damage + 2 ST = 8 damage total
- AR 4 counts as 8 vs cutting damage
- 8 damage - 8 AR = 0 damage (armor absorbed it all)
- If roll had been 10: 9 damage + 2 ST = 11 damage total
- 11 - 8 AR = 3 damage to Vitality + bleeding starts

#### Energy/Magical Damage
- **Sources:** Fire, cold, lightning, acid, magical force
- **Effect:** Functions like bludgeoning (AR applies normally), but can cause additional effects
- **Additional Effects:**
  - **Fire:** May ignite flammable objects and cause ongoing burn damage
  - **Cold:** May slow or freeze targets
  - **Lightning:** May stun or cause muscle spasms
  - **Acid:** May damage equipment and cause ongoing damage
  - **Force:** Pure magical energy, enhanced knockback

**Example - Impaling Damage:**
Archer with ST 12 (+1) shoots arrow (1d6+2 impaling) against target with AR 3.
- Roll: 4 on 1d6+2 = 6 damage + 1 ST = 7 damage total
- 7 - 3 AR = 4 damage gets through
- Impaling doubles: 4 × 2 = **8 Vitality damage**

---

### Unarmed Combat

Characters can fight without weapons:

**Basic Unarmed Attacks:**
- **Punch:** 1d6-3 + ST bonus (bludgeoning)
- **Kick:** 1d6 + ST bonus (bludgeoning)
- Use Brawling skill (DX-based)

**Martial Arts:** Characters with Martial Arts perks or special training may have enhanced unarmed damage and additional techniques (see Monk profession or martial arts expansion).

---

### Heavy Weapon Requirements

Some weapons require minimum Strength to wield effectively:

**Heavy Weapons:**
- **Heavy Two-Handed Swords:** ST 12+ (Greatsword, Zweihander)
- **Heavy Axes:** ST 12+ (Greataxe, Heavy Battleaxe)
- **Heavy Maces/Hammers:** ST 12+ (Maul, Heavy Warhammer)
- **Heavy Polearms:** ST 11+ (Halberd, Pike)
- **Longbow:** ST 10+ (cannot use with less than ST 10)

**Inadequate Strength Penalty:**
If attempting to use a heavy weapon without meeting the ST requirement:
- **-4 to all attack rolls** with that weapon
- **Half damage** (after all other calculations)
- May not be able to use weapon's special maneuvers (GM discretion)

**Example:** Character with ST 10 tries to use Greatsword (requires ST 12):
- Normal attack would be DX 13 + Swords 3 = 16
- With penalty: 16 - 4 = 12 to hit
- Greatsword normally deals 3d6+2 cutting
- With inadequate ST: Rolls 12 damage, halved to 6 damage total

**Note:** These requirements represent the strength needed to use the weapon effectively in combat, not just to lift it.

---

### Pain and Shock

Taking significant damage in a single turn causes shock and pain:

**Pain Penalty Rule:**
- For every **5 Vitality damage taken in one turn**, suffer **-1 to all rolls on the next turn**
- **Exception:** If already in active combat when damaged, adrenaline negates this penalty
- Multiple hits in same turn: add all damage together to calculate penalty

**Examples:**
- Take 7 damage in one hit outside combat: -1 to all rolls next turn
- Take 12 damage in one hit outside combat: -2 to all rolls next turn
- Take 15 damage while already fighting: No penalty (combat adrenaline)
- Take 4 damage, then 6 damage in same turn (10 total) while ambushed: -2 next turn

**Active Combat Definition:** Character has acted in combat in the last 2 rounds, or is aware of immediate danger and prepared to fight.

---

### Damage

### Armor

Armor pieces can be the difference between life and death in combat. Each armor piece offers different protection to each body part. Armor offers **deflection** (AD) that helps dodge blows, and also offer **resistance**(AR) that helps redurce damage directly and avoid bleeding.


| Type | AD (Deflection) | AR (Resistance) |
|------|-----------------|-----------------|
| **Light Torso** | 0 | 1-2 |
| **Medium Torso** | 1 | 3-5 |
| **Heavy Torso** | 2 | 6-10 |

| **Light Legging** | 0 | 1-2 |
| **Medium Legging** | 1 | 3-4 |
| **Heavy Legging** | 2 | 5-6 |

| **Light Gloves/Boots** | 0 | 0-1 |
| **Medium Gloves/Boots** | 1 | 2-3 |
| **Heavy Gloves/Boots** | 2 | 4-5 |

| **Light Helmet** | 0 | 0-1 |
| **Medium Helmet** | 1 | 2-3 |
| **Heavy Helmet** | 2 | 4-6 |


**Armor Skill Penalties**: -2 for Medium, -4 for Heavy. If wearing a single medium or heavy part, the penality for that group is used. Apply the penality to all physical actions involving body movement (climbing, stealth, acrobatics, etc.) and also casting skills, if gestures are required, pure mental skills are not affected.

**Armor/Heavy Armor Familiarity Perk**: Reduces penalties by 2 or by 4.

### Shields

| Type | SD (Shield Deflection) |
|------|----------------------|
| **Light / Buckler** | 1 |
| **Medium Shield** | 2 |
| **Heavy / Tower Shield** | 3-4 |

Shields add SD to Block defense rolls only

### Equipment Degradation

*Optional rule for added realism - can skip for simpler gameplay*

#### Armor Damage
- When you take damage > (AR + AD), armor is breached
- Reduce AR by 1 permanently
- When AR reaches 0, armor is ruined (AD no longer applies)
- Repair: Visit blacksmith/technician, costs money and time

#### Shield Damage
- When you fail Block roll and take 10+ damage
- Shield loses 1 SD permanently
- When SD reaches 0, shield is broken

#### Weapon Breakage
- When you fail Parry and take 10+ damage to yourself
- Roll vs Luck (AW/2) to avoid weapon breaking
- Masterwork or oversized weapons may have higher threshold (15+ damage)
- Broken weapons are useless until repaired

### Combat Modifiers

**Situational:**
- **High Ground**: +2 to attacks
- **Flanking**: +2 when ally is opposite side of enemy
- **Cover**: Light +2 defense, Heavy +4 defense
- **Darkness**: -4 to attacks (unless Night Vision)
- **Prone**: -4 to attacks, attackers get +4 in melee / -4 at range
- **Range** (bows/guns): Penalties at long range per weapon

**Ranged Combat Modifiers:**
- **Range Penalty:** -1 to hit per 5 meters beyond half of maximum range
- **Range Damage Penalty:** after weapon max range, the damage is halved
- **Aiming Bonus:** Spend Major Action aiming, next shot gets +3 to hit (lost if you move or are hit)
- **Point-Blank Range:** Shooting within 2 meters with ranged weapon = -2 to hit (weapon too long/awkward at close range)

**Example Range Penalties:**
- Shortbow (max 50m, penalties start after 25m): Shooting at 30m = -1, at 40m = -3, at 50m = -5, at 55m -6 and deal half damage
- Longbow (max 100m, optimal 50m): Shooting at 60m = -2, at 80m = -6, at 105m = -11 and deal half damage onwards
- Crossbow (max 80m, optimal 40m): Shooting at 60m = -4, at 85m -9 and deal half damage onwards

**Example Aiming:**
- Round 1: Use Major Action to aim at target
- Round 2: Attack with +3 to hit (must shoot same target)
- If hit or moved: lose aiming bonus

**Called Shots:**
- **Arm/Leg**: -4 to hit, may cause specific effects (drop item, slow movement)
- **Head**: -6 to hit, **damage is doubled** after armor
- **Eye/Vitals**: -8 to hit, **damage is doubled** after armor
- **Doubling stacks with impaling:** Head shot with impaling weapon = ×4 total damage (×2 impaling, ×2 called shot)
- On success: GM may apply additional effects (disarm, stun, knockout, etc.)

**Example - Head Shot with Impaling:**
Arrow (1d6+2 impaling) hits head (-6 to hit) against AR 2:
- Roll 5: 7 damage + ST bonus, -2 AR = 5 gets through
- Impaling: 5 × 2 = 10 damage
- Head shot: 10 × 2 = **20 Vitality damage total**

### Status Conditions

**Stunned**: -4 to all actions, lose Reaction, lasts 1 round

**Prone**: -4 to attacks, +4 to be hit in melee, -4 to be hit by ranged, costs half move to stand

**Disarmed**: Must spend Minor Action to retrieve weapon (3m away typically)

**Grappled**: Can't move, both grappler and target at -4 to all actions except grapple-related

**Bleeding**: Lose 1 Vitality per round until bandaged (First Aid roll, Minor Action)

**Dazed**: -2 to all actions, lose Minor Action, lasts 1 round

**Exhausted** (0 Stamina): -4 to all physical actions until rest

**Depleted** (0 Mana): -4 to all mental actions until rest

**Dying** (0 or less Vitality): uncounscious and losing 1 Vitality per turn, roll every turn vs EN/2 after - 1 x Vitality to attempt to stabilize

**Dead** (-2 x Vitality): instant death

---

### Morale and Panic Checks

Characters must make **Morale Checks** (roll vs WS) when facing terrifying or overwhelming situations:

**Common Triggers:**
- First time seeing horrific violence or gore
- Facing supernatural creatures (demons, undead, eldritch horrors)
- Witnessing ally's death
- Outnumbered 3-to-1 or more
- Taking massive damage (half Vitality or more in one hit)
- Supernatural fear effects (spells, dragon presence, etc.)

**Difficulty Modifiers:**
- Familiar with this threat: +2
- Veteran combatant/Strong Willed perk: +2
- Inexperienced or first adventure: -2
- Panicked ally nearby: -2
- Clear escape route visible: +2
- No escape route/surrounded: -4

**Roll Results:**
- **Success by 5+:** Steeled, gain +2 to resist panic for rest of encounter
- **Success:** Hold steady, continue fighting normally
- **Failure:** Shaken, -2 to all actions for 1d6 rounds
- **Failure by 5+:** Panic! Must flee or cower for 1d6 rounds, can't attack
- **Critical Failure (666):** Total panic, flee screaming, drop weapons/items

**Example - Encountering Undead Horde:**
Party sees zombie horde for first time. All roll vs WS:
- **Thorin** (WS 12, veteran +2): Target 14, rolls 10 = success
- **Marcus** (WS 11): Rolls 13 = failure, shaken for 4 rounds (-2 all actions)
- **Lyralei** (WS 14, inexperienced -2): Target 12, rolls 18 = failure by 6, panics and flees!

**GM Note:** Use sparingly for dramatic effect. Veteran adventurers shouldn't panic at normal combat.

---

## Character Advancement

Characters improve through experience gained from adventures.

### Earning Character Points

**The GM awards CP directly** after major story arcs:
- **5 CP**: Minor arc completed (2-3 sessions)
- **10 CP**: Major arc completed (5-8 sessions)
- **Bonus +1-3 CP**: Exceptional roleplay, creative solutions, character growth moments

No XP tracking - just direct CP awards

### Spending CP for Improvement

#### Skills
**Recently Used** (last 3 sessions):
- No training time required
- Just spend CP following Fibonacci costs
- Represents learning from experience

**Learning New Skills**:
- Requires half the normal training time
- 1 CP worth per week (base)
- Good teacher: 1.5 CP/week
- Excellent resources: 1.5 CP/week  
- Both: 2 CP/week (maximum)
- Hard skills require at least teacher OR resources

#### Attributes
Follow the same CP costs as creation:
- Major Attributes (DX, IN, WS, CH): Expensive, scaling costs
- Minor Attributes (ST, AW, EN): Flat 5 CP per level
- Takes time and dedication (GM discretion)
- Usually requires downtime between adventures

#### Perks
**Requirements**:
- Pay CP cost
- Roleplay justification (why did you gain this ability?)
- Often requires mentor, training, or narrative reason
- Cannot buy during active adventure

#### Buying Off Flaws
**Requirements**:
- Pay original CP value of the Flaw
- Roleplay justification (therapy, magical healing, character growth)
- GM approval
- Example: Buying off Phobia (-10 CP) costs 10 CP + story justification

**Note**: Taking on NEW Flaws after creation grants 0 CP, but adds interesting story complications

### Restrictions
- Cannot improve during combat or immediate stress
- Skills capped only by time and dedication (no hard maximum)
- Attributes normally capped at 18 (supernatural templates may exceed)
- Some Perks have prerequisites (level requirements, other Perks, etc.)

---

## Appendix: Quick Reference

### Roll Resolution
1. Roll 3d6
2. Try to get ≤ target number (Attribute + Skill + modifiers)
3. Three 1s = crit success (+10 margin)
4. Three 6s = crit failure (-10 margin, always fails)

### Difficulty Modifiers
| Easy +2 | Average +0 | Moderate -4 | Hard -6 | Very Hard -8 |

### Derived Stats at a Glance
- **Vitality**: EN × 2 (recover AW/2 per long rest)
- **Stamina**: EN × 2 (recover EN/2 per short rest)
- **Mana**: AW × 2 (recover AW/2 per short rest)
- **Speed**: (DX + EN) / 4
- **Perception**: (AW + IN) / 2

### Combat Quick Reference
**Initiative**: Highest Speed first
**Actions**: 1 Major, 1 Minor, 1 Reaction, Free actions
**Defense**: Dodge (DX/2+AD), Parry ((DX+Skill)/2, -4 if acted), Block ((DX+Skill)/2+AD+SD)
**Damage**: Weapon roll - AR = Vitality loss

### Starting Character (250 CP Budget)
1. Buy templates: ~50-110 CP
2. Adjust attributes: ~40-80 CP
3. Buy perks: ~20-60 CP
4. Buy skills: ~30-60 CP
5. Buy powers: ~20-60 CP
6. Take flaws: Optional, up to -50 CP

---

## Designer Notes

**Simverse** is designed to be:
- **Flexible**: Build any character concept from realistic to fantastic
- **Tactical**: Meaningful choices in combat and character building
- **Scalable**: Works from street-level to cosmic campaigns
- **Customizable**: Build powers from components or use pre-made
- **Roll-under simplicity**: Easy math, fast resolution

The 3d6 roll-under system creates a bell curve of results that makes mid-range success common while keeping dramatic failures and triumphs rare and exciting.

---

*Simverse Core Rules v1.0*
*Character Point RPG System*
*Roll-under 3d6 mechanics*

---

## License

**Simverse Core Rules** © 2024 by Julio Holon is licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0).

**You are free to:**
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material

**Under the following terms:**
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.
- **NonCommercial** — You may not use the material for commercial purposes.
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

To view a copy of this license, visit: https://creativecommons.org/licenses/by-nc-sa/4.0/

---

**End of Document**