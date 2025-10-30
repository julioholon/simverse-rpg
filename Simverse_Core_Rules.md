# SIMVERSE
## Core Rulebook v1.0

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
| **Strength** | ST | Physical power, melee damage, carrying capacity |

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

### Stamina
**Stamina = ST × 2**

- Represents physical exhaustion
- Spent on: running, climbing, heavy lifting, physical combat maneuvers
- At 0 Stamina: exhausted (-4 to all physical actions)
- Recovers ST/2 per short rest (1 hour break)

### Mana
**Mana = AW × 2**

- Represents mental/magical energy
- Spent on: spells, psychic powers, supernatural effects
- At 0 Mana: mentally depleted (-4 to all mental actions)
- Reduced by: mental strain, trauma, shock, extended study
- Recovers AW/2 per short rest (1 hour break)

### Speed
**Speed = (DX + EN) / 4** (don't round)

- Determines initiative order in combat
- Determines movement rate
- Average human: Speed 5
- Used for surprise rolls (roll vs Speed × 2)

### Perception
**Perception = (IN + AW) / 2**

- Used for noticing things, spotting hidden enemies
- Can be modified by Acute Senses or penalties like One Eye

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

**Ambidextrous** (5 CP)
- No penalty for using off-hand
- Can wield two weapons effectively

**Rapid Strike** (20 CP)
- Make 2 attacks in one action at -4 each
- Costs 2 Stamina per use

**Tough** (10 CP)
- +5 Vitality

**Hard to Kill** (15 CP)
- Don't fall unconscious until -1× Vitality
- Survive injuries that would kill others

**Armor Familiarity** (5 CP)
- Reduce armor penalties by 2
- Medium armor: -0 penalty (instead of -2)
- Heavy armor: -2 penalty (instead of -4)

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

**Mana Reserve** (10 CP)
- +10 to Mana pool
- More magical/mental endurance

**Natural Talent** (5 CP)
- Choose one skill
- Learn that skill at half CP cost (round up)

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

### Flaws

#### Combat Flaws

**Slow Reflexes** (-15 CP)
- -2 to Speed
- React slower than others

**Poor Vision** (-10 CP)
- -2 to all ranged attack rolls
- Difficulty seeing at distance

**Weak** (-10 CP)
- -5 Vitality
- Less resilient to injury

**Pacifist** (-15 CP)
- Will not kill or seriously harm except in extreme self-defense
- Must justify violent actions

#### Physical Flaws

**One Eye** (-15 CP)
- -3 to ranged attacks
- -2 to Perception rolls

**Lame** (-10 to -20 CP)
- Speed reduced by 1 (-10 CP) or 2 (-20 CP)
- Permanent injury or condition

**Chronic Pain** (-10 CP)
- -1 to all physical actions
- Constant discomfort

**Fragile** (-15 CP)
- Injuries take double time to heal
- Slower recovery from wounds

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

#### Social Flaws

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

---

## Templates

Templates are pre-built packages of attributes, perks, skills, and equipment that speed up character creation. They cost exactly what their components are worth.

### Race Templates

#### Human (0 CP)
**Attribute Modifiers:** None (baseline)

**Racial Traits:**
- **Adaptable**: +1 CP per session (learn faster)
- **Versatile**: Can take any profession
- **Lifespan**: ~80 years

---

#### Elf (30 CP)
**Attribute Modifiers:**
- DX +2 (20 CP)
- AW +1 (5 CP)
- EN -1 (-5 CP)
- ST -1 (-5 CP)

**Included Perks:**
- Night Vision (10 CP)
- Acute Senses - Hearing (5 CP)

**Racial Traits:**
- **Forest Movement**: No terrain penalty in woodlands
- **Graceful**: +1 to Stealth and Acrobatics
- **Lifespan**: ~300 years

**Starting Equipment:** None (from profession)

---

#### Dwarf (20 CP)
**Attribute Modifiers:**
- ST +1 (5 CP)
- EN +2 (10 CP)
- DX -1 (-10 CP)
- CH -1 (-10 CP)

**Included Perks:**
- Tough (10 CP)
- Magic Resistance (15 CP)

**Racial Traits:**
- **Darkvision**: See perfectly in darkness up to 30m
- **Stubborn**: +2 to resist intimidation/persuasion
- **Mountain Movement**: No penalty on rocky/underground terrain
- **Lifespan**: ~200 years
- **Speed**: 4 (instead of 5)

**Starting Equipment:** None (from profession)

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

---

#### Wizard (110 CP)

**Starting Skills:**
- Spellcasting 3 (6 CP)
- Occult Knowledge 3 - Hard (26 CP: 5+8+13)
- Research 2 (3 CP)

**Included Perks:**
- Mage Gift (20 CP) [required for spells]
- Mana Reserve (10 CP)

**Starting Spells:**
- Choose 3 spells worth up to 15 CP each (45 CP total)

**Starting Equipment:**
- Wizard robes (AR 0)
- Staff (1d6-1 damage, spellcasting focus)
- Spellbook
- Component pouch

---

#### Rogue (38 CP)

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

---

### Mixing Templates

Templates can be combined freely. Simply add their costs together:

**Example: Elf Scout**
- Elf (30 CP) + Scout (29 CP) = **59 CP total**
- Remaining budget (250 CP start): **191 CP**
- Gets all benefits from both templates
- Attribute modifiers stack: Base 10 DX → +2 from Elf = 12 DX
- Has Night Vision, Acute Hearing, AND Scout skills/equipment

**Example: Dwarf Warrior**
- Dwarf (20 CP) + Warrior (33 CP) = **53 CP total**
- Remaining budget: **197 CP**
- Tough, Magic Resistant, Armored fighter
- Natural dungeon delver with combat prowess

---

## Powers, Spells & Maneuvers

This unified system allows you to create supernatural powers, magical spells, and combat maneuvers using the same construction rules.

### Base Effect Types

All abilities start with a base effect tier that determines CP cost and resource cost:

| Tier | CP Base | Resource Cost | Examples |
|------|---------|---------------|----------|
| **Minor** | 5 CP | 0 (or 1 Stamina) | Shield Bash, Trip, Disarm, Quick Draw, Feint |
| **Moderate** | 10 CP | 2 Mana | 1d6 damage bolt, minor healing, charm person, detect magic |
| **Major** | 20 CP | 6 Mana | 3d6 damage, serious healing, flight, invisibility, lightning bolt |
| **Epic** | 40 CP | 16 Mana | 6d6+ damage, teleportation, open portal, raise dead, time stop |

**Resource Types:**
- **Physical Maneuvers**: Usually cost Stamina or nothing
- **Spells/Powers**: Cost Mana
- **Extreme Effects**: Some may cost Vitality (blood magic, self-sacrifice)

**Alternative Energy Sources**: Wizards can use power stones, ritual circles, ley lines, or blood sacrifice to provide Mana for spells beyond their personal pool.

### Enhancements (Percentage-Based)

These modify the cost by a percentage:

| Enhancement | Cost Modifier | Description |
|-------------|---------------|-------------|
| **Increased Effect** | +50% per +1d6 | More damage, healing, or bonus |
| **Extra Range** | +10% per doubling | 10m → 20m → 40m → 80m |
| **Extra Duration** | +10% per doubling | 1 min → 2 min → 4 min → 8 min |
| **Area Effect** | +50% (3m radius), +100% (6m) | Affects multiple targets in area |
| **Multiple Targets** | +25% per target | Add specific targets |
| **Reduced Resource Cost** | +25% (half cost), +50% (quarter) | Costs less Mana/Stamina to use |
| **Increased Resource Cost** | -25% (double cost), -50% (triple) | Costs more to use, cheaper to buy |
| **Weakened Resistance** | +10% per -2 penalty | Target gets -2 to resist (stackable) |
| **Instant Action** | +25% | Can interrupt or use mid-action |
| **Persistent** | +20% | Effect continues without concentration |

### Enhancements (Fixed Cost)

| Enhancement | Cost | Description |
|-------------|------|-------------|
| **Armor Piercing** | +5 CP | Ignores 2 points of armor |
| **Homing** | +5 CP | Reroll one missed attack with this power |
| **Knockback** | +3 CP | Push target 2m on successful hit |
| **Lingering Pain** | +5 CP | Target at -1 for 1 round after effect |
| **Silent Casting** | +8 CP | No visible or audible manifestation |
| **Fast Cast** | +10 CP | Reduce casting/activation time by 50% |

### Limitations (Percentage-Based)

These reduce the cost by a percentage:

| Limitation | Cost Modifier | Description |
|------------|---------------|-------------|
| **Requires Skill Roll** | -20% | Must succeed on skill check to activate |
| **Only in [Condition]** | -60% | Only works in rain/night/touching earth/etc. |
| **Requires [Item]** | -20% | Need specific tool/weapon/holy symbol |
| **Usage Limit** | -30% (3/day), -60% (1/day), -80% (1/week) | Limited uses |
| **Preparation Time** | -20% (1 min), -40% (10 min), -60% (1 hour) | Must prepare before use |
| **Obvious/Loud** | -10% | Clearly visible, alerts everyone nearby |
| **Concentration** | -20% | Can't take other actions while using |
| **Backfire Risk** | -30% | On crit fail, lose resources or suffer effect |
| **Increased Resource** | -20% (double), -30% (triple) | Costs more Mana/Stamina to use |
| **Fragile** | -25% | Broken by any damage to user |

### Limitations (Fixed Cost)

| Limitation | Cost | Description |
|------------|------|------------|
| **Gesture Required** | -2 CP | Need free hand to use |
| **Verbal Component** | -2 CP | Must speak/chant to activate |
| **Melee Range Only** | -3 CP | Must be adjacent to target |
| **Self Only** | -5 CP | Cannot target others, only yourself |
| **Exhausting** | -5 CP | Take 1 Vitality damage when used |
| **Obvious Tell** | -3 CP | Target sees it coming, +2 to their defense |

### Construction Rules

1. **Choose Base Effect**: Select tier (Minor/Moderate/Major/Epic) and effect type
2. **Add Enhancements**: Apply percentage and fixed enhancements
3. **Add Limitations**: Apply percentage and fixed limitations
4. **Calculate Total Cost**: 
   - Start with Base CP
   - Multiply by (1 + sum of enhancement %) × (1 + sum of limitation %)
   - Add/subtract fixed costs
   - Round to nearest whole number
5. **Minimum Cost**: No power can cost less than 1 CP
6. **Maximum Reduction**: Limitations can't reduce cost below 10% of base (max -90%)

### Example Powers

#### Shield Bash (Physical Maneuver)
- **Base**: Minor Effect (5 CP, 1 Stamina)
- **Effect**: Stun opponent, they roll vs EN or lose next action
- **Enhancement**: None
- **Limitation**: Requires Shield (-3 CP), Requires Skill Roll - Shield skill (-20%)
- **Final Cost**: (5 × 0.8) - 3 = 1 CP
- **Usage**: Roll Shield skill to activate, costs 1 Stamina, opponent resists vs EN

#### Fire Bolt (Moderate Spell)
- **Base**: Moderate Effect (10 CP, 2 Mana)
- **Effect**: 1d6 fire damage, ranged attack
- **Enhancement**: Extra Range +10% (20m), Increased Damage +50% (2d6 total)
- **Limitation**: Verbal Component (-2 CP)
- **Final Cost**: (10 × 1.6) - 2 = 14 CP
- **Usage**: Costs 2 Mana, roll Spellcasting vs target's Dodge

#### Power Attack (Combat Maneuver)
- **Base**: Minor Effect (5 CP, 2 Stamina)
- **Effect**: Next attack deals +2d6 damage
- **Enhancement**: Increased Damage +100%
- **Limitation**: Requires Skill Roll (-20%), Obvious Tell (-3 CP)
- **Final Cost**: (5 × 2.0 × 0.8) - 3 = 5 CP
- **Usage**: Costs 2 Stamina, roll weapon skill at -2, if hit deal weapon damage +2d6

#### Teleport (Major Spell)
- **Base**: Major Effect (20 CP, 6 Mana)
- **Effect**: Teleport up to 50m to visible location
- **Enhancement**: Extra Range +20% (4× base)
- **Limitation**: Concentration (-20%), Obvious/Loud (-10%)
- **Final Cost**: 20 × 1.2 × 0.7 = 17 CP
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
8. **Apply Armor**: Subtract Armor Resistance (AR)
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

**Damage = Weapon Damage Roll - Armor Resistance (AR)**

Weapons have damage dice notation:
- Knife: 1d6-3
- Sword: 2d6-1
- Greatsword: 3d6+2
- Bow: 2d6
- Crossbow: 2d6+2

**Margin does not affect damage** - only hit/miss and defender's penalty

### Armor

| Type | AD (Deflection) | AR (Resistance) | Penalty to Skills |
|------|-----------------|-----------------|-------------------|
| **Light** | 0 | 1-2 | 0 |
| **Medium** | 1 | 3-4 | -2 |
| **Heavy** | 2 | 5-10 | -4 |

**Armor Penalties**: Apply to all physical actions involving body movement (climbing, stealth, acrobatics, etc.) and also casting skills, if gestures are required, pure mental skills are not affected

**Armor Familiarity Perk**: Reduces penalties by 2

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

**Called Shots:**
- **Arm/Leg**: -4 to hit
- **Head**: -6 to hit
- **Eye/Vitals**: -8 to hit
- On success: GM may apply additional effects (disarm, stun, extra damage, etc.)

---

### Surprise Attacks (General Rule)

When attacking a **completely unaware** target, the attacker gains a significant advantage:

**Completely Unaware Targets include:**
- Sleeping characters
- Paralyzed or unconscious targets
- Characters who have absolutely no knowledge of the attacker's presence
- Targets of successful assassination attempts (GM discretion)

**Effect:**
- **Double all damage dealt** from that attack
- This applies to the first attack only
- Subsequent attacks against the same target use normal damage
- If the target survives and becomes aware, they are no longer unaware

**Available to All:** This is a general combat rule available to all characters as a tactical reward for good planning and stealth.

**Does NOT Apply To:**
- Flanked enemies (they're aware, just poorly positioned - use flanking bonus instead)
- Enemies in active combat (even if not looking at you)
- Surprised enemies who rolled poorly on surprise rolls (they get initiative penalties but aren't completely unaware)

---

## Examples

**Example 1 - Assassinating a Guard:**
Marcus sneaks up on a sleeping guard (Stealth vs the guard's Perception while asleep at -8). Success! Marcus attacks with his dagger. He rolls 1d6-3 and gets 2 total. This is doubled to 4 damage. Additionally, he uses his Sneak Attack maneuver (1 Stamina) for +2d6, rolling 7. Total damage: 4 (doubled base) + 14 (sneak attack, also doubled) = 18 damage to the sleeping guard.

**Example 2 - Surprise Attack from Ambush:**
Thorin hides behind a door (Stealth vs guards' Perception). When a guard walks through, Thorin attacks from complete surprise. His battleaxe deals 2d6, rolling 8. This is doubled to 16 damage on the first hit! The guard is badly wounded but now aware - subsequent attacks use normal damage.

**Example 3 - Not a Surprise Attack:**
Marcus flanks an enemy who's fighting Thorin. The enemy sees both combatants and is in active combat, just poorly positioned. Marcus gets the +2 flanking bonus to his attack roll, but does NOT double damage. However, he can still use his Sneak Attack maneuver against the flanked enemy for +2d6 bonus damage.

---

## Interaction with Maneuvers

**Sneak Attack Maneuver (8 CP):**
Some rogues train in a special Sneak Attack maneuver that allows them to deal extra damage (+2d6) against **flanked OR unaware** enemies. This is more versatile than the general surprise attack rule:

- Works against flanked enemies (not just unaware)
- Adds +2d6 damage (not doubling base)
- Costs 1 Stamina and can only be used once per target per combat
- Can stack with surprise attack doubling

**Combined Effect Example:**
Marcus attacks a completely unaware guard:
1. Base dagger damage: 1d6-3 = 2 damage
2. Doubled for surprise: 2 × 2 = 4 damage
3. Sneak Attack maneuver: +2d6 = +14 damage
4. Total: 18 damage

---

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
2. Try to get <= target number (Attribute + Skill + modifiers)
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