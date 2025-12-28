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

Characters have **7 attributes**, divided in two groups, that define their capabilities:


### Major Attributes

These are attributes are more general and govern most skill rolls

| Attribute | Abbreviation | Governs |
|-----------|--------------|---------|
| **Dexterity** | DX | Agility, reflexes, coordination, ranged combat |
| **Intellect** | IN | Reasoning, memory, learning, technical skills |
| **Wisdom** | WS | Willpower, mental defense, intuition, sixth sense |
| **Charisma** | CH | Social influence, leadership, attractiveness |

### Minor attributes

These atributes are used to calculate other derived characteristics (like Speed, Vitality, Stamina, Mana etc.) and usually don't matter for skill rolls

| Attribute | Abbreviation | Governs |
|-----------|--------------|---------|
| **Endurance** | EN | Stamina, health, resisting fatigue/poison |
| **Awareness** | AW | Perception, initiative, luck, magical intuition |
| **Strength** | ST | Physical power, melee damage bonus, carrying capacity |

### Attribute Scale

- **Range**: 5 to 20 (can go higher with supernatural templates)
- **Human Average**: 10
- **Starting Value**: All attributes begin at 10

### Attribute Costs

Attributes cost Character Points (CP) to raise or lower from baseline (10). Costs scale exponentially to represent diminishing returns and encourage balanced character builds.

#### Major Attributes (DX, IN, WS, CH)
These govern most skills and are more expensive:

| Attribute Range | Cost per Increment | Formula | Example |
|-------------|----------------|---------|---------|
| 3-9 | -10 CP | -10 × level | 10→3 nets -70 CP |
| 10-13 | 10 CP | 10 × 2^0 | 10→13 costs 30 CP |
| 14-16 | 20 CP | 10 × 2^1 | 13→16 costs 60 CP (90 total) |
| 17-19 | 40 CP | 10 × 2^2 | 16→19 costs 120 CP (210 total) |
| 20-22 | 80 CP | 10 × 2^3 | 19→22 costs 240 CP (450 total) |

**Mathematical Formula:** Cost to go from level n-1 to n (for n >=11) => 10 × 2^⌊(n-11)/3⌋ where n is the desired level

**Common Examples:**
- DX 10→12: 10+10 = **20 CP**
- DX 10→14: 10+10+10+20 = **50 CP**
- DX 10→15: 10+10+10+20+20 = **70 CP**
- DX 10→16: 10+10+10+20+20+20 = **90 CP**

#### Minor Attributes (ST, AW, EN)
These are generally not used for skill rolls and cost half as much:

| Attribute Range | Cost per Increment | Formula | Example |
|-------------|----------------|---------|---------|
| 3-9 | -5 CP | -5 × level | 10→3 nets -35 CP |
| 10-13 | 5 CP | 5 × 2^0 | 10→13 costs 15 CP |
| 14-16 | 10 CP | 5 × 2^1 | 13→16 costs 30 CP (45 total) |
| 17-19 | 20 CP | 5 × 2^2 | 16→19 costs 60 CP (105 total) |
| 20-22 | 40 CP | 5 × 2^3 | 19→22 costs 120 CP (225 total) |

**Mathematical Formula:** Cost to go from level n-1 to n = 5 × 2^⌊(n-11)/3⌋ where n is the desired level

**Common Examples:**
- ST 10→12: 5+5 = **10 CP**
- ST 10→14: 5+5+5+10 = **25 CP**
- ST 10→16: 5+5+5+10+10+10 = **45 CP**

**Design Note:** The exponential scaling ensures that skills remain competitive with attributes as characters advance. Raising a major attribute from 16→17 costs 40 CP, making individual skill improvements (which boost only one task) a viable alternative to broad attribute increases (which boost many tasks).

### Attribute Guidelines by Power Level

While there are no hard limits on attributes, the following guidelines help maintain game balance and narrative consistency:

| Power Level | Major Attributes (DX, IN, WS, CH) | Minor Attributes (ST, AW, EN) | Notes |
|-------------|----------------------------------|-------------------------------|-------|
| **Weaklings** (50 CP) | Typical max: 11-12 | Typical max: 12-13 | Children, small animals, weak creatures |
| **Street Level** (75 CP) | Typical max: 12-13 | Typical max: 13-14 | Thugs, militia, typical adult humans |
| **Starting Adventurer** (100 CP) | Typical max: 13-14 | Typical max: 14-15 | Beginning heroes, competent professionals |
| **Experienced** (150 CP) | Typical max: 14-15 | Typical max: 15-16 | Veterans, skilled warriors |
| **Heroic** (200 CP) | Typical max: 15-16 | Typical max: 16-17 | Champions, renowned masters |
| **Elite** (250 CP) | Typical max: 16-17 | Typical max: 17-18 | Legendary heroes, master wizards |
| **Superheroic** (400 CP) | Can reach: 18-19 | Can reach: 19-20 | Demigods, supernatural beings |
| **Cosmic** (500+ CP) | 20+ possible | 20+ possible | Gods, world-shaking entities |

**Important Notes:**
- These are **guidelines, not hard caps** - players can exceed them if they have the CP
- Going beyond these ranges should require **narrative justification** (supernatural bloodline, divine blessing, cybernetic enhancement, years of training, etc.)
- GMs can enforce stricter limits for grounded/realistic campaigns
- Supernatural templates (vampire, dragon, etc.) may inherently exceed these ranges
- At 100 CP starting level, most characters will have their primary attribute at 12-14 and skills at 3-5

---

## Derived Statistics

Several important values are calculated from your attributes:

### Vitality (HP) and Integrity

**Living beings use Vitality = EN × 2**

- Represents physical health and injury tolerance
- Damage from combat reduces Vitality
- At 0 Vitality: unconscious
- At -EN Vitality: death (unless you have Hard to Kill perk)
- At -2×EN Vitality: body destroyed (beyond normal resurrection)
- Recovers AW/2 per long rest (8 hours sleep)
- Can purchase Extra Vitality / Low Vitality to increase/decrease individually

**Constructs/Robots/Unliving beings use Integrity = EN × 2**

- Represents structural integrity and functionality
- Damage from combat reduces Integrity
- At 0 Integrity: glitches and malfunctions, random system failures
- At -EN Integrity: complete shutdown (can be repaired with time)
- At -2×EN Integrity: completely broken/destroyed (beyond normal repair, needs complete reconstruction)
- **Note**: Constructs with Integrity cannot be "unconscious" - they either function (with glitches) or shut down completely
- Physical objects like doors, chests, and walls also have Integrity and may have AR (Armor Rating)
- Constructs typically require Engineering skill for repair rather than healing magic

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

### Carrying Capacity

**Maximum Lift** = ST × 5 kg (one-time lift)
**Carry Capacity** = ST × 2 kg (sustained carrying)

| ST | Max Lift | Carry Capacity |
|----|----------|----------------|
| 8  | 40 kg    | 16 kg          |
| 10 | 50 kg    | 20 kg          |
| 12 | 60 kg    | 24 kg          |
| 14 | 70 kg    | 28 kg          |
| 16 | 80 kg    | 32 kg          |
| 18 | 90 kg    | 36 kg          |
| 20 | 100 kg   | 40 kg          |

### Encumbrance Levels

Based on percentage of Carry Capacity:

| Level | Load | Effects |
|-------|------|---------|
| **Normal** | 0-100% | No penalties |
| **Heavy** | 101-150% | -2 Speed, -2 to physical skills, -1 to defenses, 1 Stamina/10 min |
| **Overburdened** | 151-200% | Speed halved, -4 to physical skills, -2 to defenses, cannot sprint |

**Beyond 200%:** Cannot move without dropping weight.

**Combat Effects:**
- Encumbrance penalties stack with armor penalties
- Overburdened characters cannot use Sprint movement

**Example:** Character with ST 12 (24 kg capacity) carrying 30 kg (125%) is Heavy load: -2 Speed, -2 to Athletics/Stealth/etc., -1 to Dodge/Parry/Block.

---

## Character Creation

### Character Point Budget

Characters are built by spending Character Points (CP) based on campaign power level:

| Power Level | Base CP | +Max Flaws | Total | Best Skill Range | Description |
|-------------|---------|------------|-------|------------------|-------------|
| **Weaklings** | 50 CP | +25 CP | 75 CP | 13-15 | Children, wild animals, animal familiars |
| **Street Level** | 75 CP | +35 CP | 110 CP | 14-16 | Thugs, rookies, militia, untrained fighters |
| **Starting Adventurer** | 100 CP | +50 CP | 150 CP | 15-17 | Beginning heroes, young adventurers, competent professionals |
| **Experienced** | 150 CP | +50 CP | 200 CP | 18-19 | Veterans, sergeants, skilled warriors, journeyman mages |
| **Heroic** | 200 CP | +50 CP | 250 CP | 20-21 | Champions, masters, renowned warriors, expert mages |
| **Elite** | 250 CP | +50 CP | 300 CP | 22-23 | Legendary heroes, elite soldiers, master wizards |
| **Superheroic** | 400 CP | +50 CP | 450 CP | 25-27 | Demigods, archmages, superhuman warriors |
| **Cosmic** | 500+ CP | +50 CP | 550+ CP | 30+ | Gods, apocalyptic threats, world-shaking powers |

**Standard starting game: 100 CP** (up to 150 CP with flaws)

**"Best Skill Range"** indicates the typical highest roll (Attribute + Skill) a specialist character will achieve with their primary skill at this power level.

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
   - Purchase skill levels using sum progression costs
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

### Skill Costs (Sum Progression)

Skills use a sum progression (1+2+3+...+N) to represent diminishing returns while remaining affordable at high levels:

**Formula:** Total cost to reach level N = N × (N+1) / 2
**Cost to improve a skill from level N-1 to level N:** N CP

| Skill Level | Increment | Cumulative (Regular) | Cumulative (Hard) |
|-------------|-----------|----------------------|-------------------|
| 1 | +1 CP | 1 CP | 2 CP |
| 2 | +2 CP | 3 CP | 6 CP |
| 3 | +3 CP | 6 CP | 12 CP |
| 4 | +4 CP | 10 CP | 20 CP |
| 5 | +5 CP | 15 CP | 30 CP |
| 6 | +6 CP | 21 CP | 42 CP |
| 7 | +7 CP | 28 CP | 56 CP |
| 8 | +8 CP | 36 CP | 72 CP |
| 9 | +9 CP | 45 CP | 90 CP |
| 10 | +10 CP | 55 CP | 110 CP |

**Hard Skills:** Cost ×2 the regular skill cost. Hard skills have no default value and require specialized training.

**Common Examples:**
- Regular skill to 4: **10 CP**
- Regular skill to 8: **36 CP**
- Hard skill to 4: **20 CP**
- Hard skill to 8: **72 CP**

**Hard Formula:** Total cost to reach level N = N × (N+1)
**Cost to improve a HARD skill from level N-1 to level N:** 2xN CP

**Design Note:** This progression makes skills competitive with attribute increases. A skill from 6→7 costs 7 CP, while raising a major attribute from 14→15 costs 20 CP. Since attributes boost multiple skills, both remain viable choices at different stages of character development.

**Note:** Skills can exceed level 10, continuing the sum progression. Level 10 represents a grandmaster who's trained for a decade.

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
- Spellcasting (WS), Psionics (IN), Divine Magic (CH), Ritual Magic (IN), Occult Knowledge* (IN)

\* for HARD skills

---

## Perks & Flaws

Perks represent advantages, talents, and special abilities. Flaws represent disadvantages and complications that make interesting characters.

### Perks

#### Combat Perks

**Combat Reflexes** (5 CP)
- +2 to Speed for initiative only
- Will never be surprised in combat or be caught off guard

**Weapon Master** (10 CP)
- Choose one weapon type
- +2 to attack and parry with that weapon
- +2 to weapon damage as well

**Martial Arts Training** (20 CP)
- Unarmed attacks deal +2 damage
- Can make unarmed attack as Minor Action
- +2 to all defense rolls when unarmored
- Can parry ranged attacks at -4 (requires hand free)

**Ambidextrous** (10 CP)
- No penalty for using off-hand
- Can wield two weapons effectively

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

**No Sense of Pain** (5 CP)
- Cannot feel pain
- Immune to pain-based penalties and torture
- **Drawback**: Don't know when injured. -2 to notice injuries or damage to self.
- May fight until destroyed without realizing severity
- GM will keep account of the remaining Vitality, damage rolls not revealed, just eventual GM description of the blow visual effects
- **Justification**: Constructs, certain undead, beings with alien neurology, nerve damage

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
- +10 to Vitality 

**Extra Stamina** (10 CP / level)
- +10 to Stamina

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

**Undead** (+50 CP)
- Character is undead (resurrected as zombie, vampire, lich, skeleton, wight, etc.)
- Count as undead creature for all effects
- **Use Vitality normally** (not Integrity - undead bodies still have "health")
- **Immunities:**
  - Doesn't need food, water, air, or sleep
  - Immune to poison and disease
  - Immune to death magic and life drain (already dead)
  - No bleeding from cutting damage (immune to bleeding effects)
  - Immune to effects targeting "living creatures"
  - Can be healed by negative energy and necromantic magic
- **Vulnerabilities:**
  - Can be affected by anti-undead magic (Turn Undead, Destroy Undead, etc.)
  - Cannot benefit from normal healing magic (Cure Wounds, healing potions, etc.)
  - Cannot heal naturally during rest - must use necromantic healing
  - Severe social stigma - hunted, feared, usually killed on sight by most civilizations


#### Racial Perks

**Facilitated Movement** (5 CP)
- No terrain penalty in a selected type of terrain (woodlands, desert, cities)

**Graceful** (10 CP)
- +1 to Stealth and Acrobatics skills

**Extended Lifespan** (5 CP)
-  Longer than human lifespan (~80 years) up to around 500 years, specify per race

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

**Paraplegic** (-30 CP)
- Cannot walk or use legs
- Requires wheelchair, mount, or assistance to move
- Movement speed is 0 without aid (wheelchair provides Speed 2)
- Cannot dodge, can only parry or block
- -4 to most physical skills involving lower body
- May still fight effectively from mounted position or stationary

**Chronic Pain** (-10 CP)
- -1 to all physical actions
- Constant discomfort

**Fragile** (-15 CP)
- Injuries take double time to heal
- Slower recovery from wounds

#### Sensory Flaws

**Blind** (-20 CP)
- Cannot see
- Automatically fail any action requiring vision
- -6 to attacks and most Perception rolls
- Must rely on other senses (hearing, smell, touch)
- **Often combined with**: Enhanced other senses like Acute Hearing or exotic senses
- **Example combination**: Blind (-20 CP) + Acute Hearing (+5 CP) = Net -15 CP

**Deaf** (-10 CP)
- Cannot hear
- Automatically fail hearing-based Perception
- -4 to Perception rolls overall
- **Immunities**: Sonic attacks, sound-based effects, verbal charms requiring hearing
- Cannot understand spoken language (must read lips or use sign language)
- **Benefit**: +4 to resist sonic/thunder damage
- **Often combined with**: Enhanced vision or other senses

**Mute** (-5 CP)
- Cannot speak or produce speech sounds
- Cannot use verbal spell components without alternate method (GM may allow silent casting at increased cost/difficulty)
- Must communicate via writing, gestures, sign language, or telepathy
- Can still make involuntary sounds (grunt, scream, gasp) at GM discretion
- **Note**: Less limiting than it seems - gestures and writing work in most situations

#### Mental Flaws

**Animal Intelligence** (-20 CP)
- **IN capped at maximum 6**
- Cannot learn complex skills requiring reasoning (Engineering, Medicine, Tactics, Spellcasting)
- Cannot read or write (unless trained like a parrot - mimicry without comprehension)
- Follow simple commands and instincts
- Rely on training, conditioning, and natural behavior
- **Benefit**: +2 to Survival, Tracking (natural instincts)
- **Justification**: Awakened animals, low-intelligence constructs, brain damage, magical regression

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

**Severe Social Stigma** (-20 CP)
- -4 to social interactions with certain groups
- Hunted, death on sight


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

#### Elf (50 CP)
**Attribute Modifiers:**
- DX +2 (20 CP): 10→12
- AW +1 (5 CP): 10→11
- EN -1 (-5 CP): 10→9
- ST -1 (-5 CP): 10→9

**Included Perks:**
- Night Vision (10 CP)
- Acute Senses - Hearing (5 CP)
- Facilitated Movement (Forest) (5 CP): No terrain penalty in woodlands
- Graceful (10 CP): +1 to Stealth and Acrobatics skills
- Extended Lifespan (5 CP): ~300 years

**Total Cost Breakdown:** 20 + 5 - 5 - 5 + 35 (perks) = **50 CP**

---

#### Dwarf (45 CP)
**Size Modifier:**
- **Child/Dwarf Size** (-10 CP): ST -2, DX +2, Vitality ×0.75, Movement ×0.75

**Additional Attribute Modifiers:**
- ST +1 (15 CP): Final ST 11 (base 10 -2 size +3 purchased = 11)
- EN +2 (10 CP): 10→12
- DX +0 (-20 CP): Final DX 10 (base 10 +2 size -2 purchased = 10)
- CH -1 (-10 CP): 10→9

**Included Perks:**
- Extra Vitality (10 CP)
- Magic Resistance (15 CP)
- Night vision (10 CP): See perfectly in darkness up to 30m
- Strong Willed (10 CP): +2 to resist mental effects
- Facilitated Movement (Mountain) (5 CP): No penalty on rocky/underground terrain
- Extended Lifespan (5 CP): ~200 years

**Total Cost Breakdown:** -10 (size) + 15 + 10 - 20 - 10 + 55 (perks) = **40 CP**

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
- Combat Reflexes (5 CP)
- Fast Healer (10 CP)

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

#### Wizard (51 CP)

**Starting Skills:**
- Spellcasting 3 (6 CP)
- Occult Knowledge 3 - Hard (12 CP: 2+4+6)
- Research 2 (3 CP)

**Included Perks:**
- Mage Gift (20 CP) [required for spells]
- Extra Mana (10 CP)

**Starting Equipment:**
- Wizard robes (AR 0)
- Staff (1d6-1 damage, spellcasting focus)
- Spellbook
- Component pouch

**Total Cost Breakdown:** 6 + 12 + 3 + 30 (perks) = **51 CP**

**Note:** Most wizards invest ~30-40 CP in spells (8-12 Minor/Moderate spells)

---

#### Rogue (33 CP)

**Starting Skills:**
- Stealth 4 (10 CP: 1+2+3+4)
- Lockpicking 3 - Hard (12 CP: 2+4+6)
- Sleight of Hand 2 (3 CP)
- Perception 2 (3 CP)

**Included Perks:**
- Ambidextrous (5 CP)

**Starting Equipment:**
- Light armor (AR 1, AD 0)
- Two daggers (1d6-2 each)
- Thieves' tools
- Grappling hook and rope

**Total Cost Breakdown:** 10 + 12 + 3 + 3 + 5 (perk) = **33 CP**

**Note:** Most rogues invest 15-25 CP in combat maneuvers (Sneak Attack, Feint, Precision Strike, etc.). See [Simverse_Powers_Library.md](Simverse_Powers_Library.md) for available maneuvers

---

### Mixing Templates

Templates can be combined freely. Simply add their costs together:

**Example: Elf Scout (Starting Adventurer, 100 CP)**
- Elf (50 CP) + Scout (29 CP) = **79 CP total**
- **Remaining budget (100 CP base): 21 CP**
- Gets all benefits from both templates
- **Final Stats:** DX 12, AW 11, EN 9, ST 9, others 10
- Has Night Vision, Acute Hearing, Facilitated Movement (Forest), Graceful, AND Scout skills/equipment
- **Suggested 21 CP allocation:**
  - DX 12→13 (10 CP): Boost primary stat for better bow attacks
  - Aimed Shot maneuver (3 CP): +4 to hit after aiming
  - Precision Strike maneuver (8 CP): +2d6 damage on precision attacks
- **Final best bow attack:** DX 13 + Bow 3 = **16** (98% success vs unmodified targets)

**Example: Dwarf Warrior (Starting Adventurer, 100 CP)**
- Dwarf (45 CP) + Warrior (33 CP) = **78 CP total**
- **Remaining budget (100 CP base): 22 CP**
- Gets Extra Vitality, Fast Healer, Magic Resistant, Night vision, Strong Willed, AND Warrior training
- **Final Stats:** ST 11, EN 12, DX 10, CH 9, others 10
- **Suggested 22 CP allocation:**
  - ST 11→12 (5 CP): Boost damage
  - Shield Bash (1 CP): Stun enemies
  - Power Attack (8 CP): +2d6 damage
  - Disarm (8 CP): Remove enemy weapon
- **Final best melee attack:** DX 10 + Weapon 3 = **13** (84% success)
- Natural dungeon delver with solid combat prowess and great survivability

For more templates and ideas, see [Simverse_Addittional_Templates.md](Simverse_Addittional_Templates.md)

---

## Powers, Spells & Maneuvers

This unified system allows you to create supernatural powers, magical spells, and combat maneuvers using the same construction rules.

### Base Effect Types

All abilities start with a base effect tier that determines CP cost and resource cost:

| Tier | Min Skill Level | CP Base | Resource Cost (Stamina/Mana) | Examples |
|------|-----------------|---------|------------------------------|----------|
| **Minor** | 2 | 1 CP | 1 | 1 damage, move objecs, cantrips, most easy combat maneuvers |
| **Moderate** | 3 | 5 CP | 2 Mana | harder combat maneuvers, 1d6 damage bolt, 1d6 healing bolt, easy less impactful roleplay spells like charm and detect magic |
| **Major** | 5 | 15 CP | 6 Mana | 3d6 damage, serious healing, stronger more impactful spells like invisibility, flight |
| **Epic** | 8 | 30 CP | 12 Mana | 6d6+ damage, game changing spells like teleportation, open portal, time stop, raise dead |
| **Legendary** | 13 | 50 CP | Varies | world-altering effects, deity-level powers |

**Skill Level Requirement**: To purchase a power of a given tier, you must have the minimum skill level in the relevant skill (Spellcasting for spells, weapon skill for combat maneuvers, etc.). This represents the mastery needed to learn and perform that tier of ability.

**Design Goal:** Starting wizard (~50 CP for spells) should have 10-15 Minor/Moderate spells. Starting warrior/thief (~25 CP for maneuvers) should have ~10 Minor/Moderate maneuvers.

**Resource Types:**
- **Physical Maneuvers**: Usually cost Stamina
- **Spells/Powers**: Usually cost Mana
- **Extreme Effects**: Some may cost Vitality (blood magic, self-sacrifice)

**Alternative Energy Sources**: Wizards can use mana stones, ritual circles, ley lines, or blood sacrifice to provide Mana for spells beyond their personal pool.

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
| **Cone Shaped** | +50% (4m cone) | Affects all targets in a 4m cone emanating from the user |
| **Multiple Targets** | +50% (2 targets), +75% (3), +125% (5) | Add specific targets (not area) |
| **Reduced Cost** | +25% (half cost), +50% (quarter) | Costs less Mana/Stamina to use, if below 1, round to 0 |
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
| **Increased Cost** | -25% (double cost), -50% (triple) | Costs more to use, cheaper to buy |
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
- **Enhancement**: Extra Range +20%, Increased Damage +50% (2d6 total)
- **Limitation**: Verbal Component -10%, Obvious/Loud -10%
- **Calculation**: 5 × (1 + 0.20 + 0.50 - 0.10 - 0.10) = 5 × 1.50 = 7.5, round down to 7 CP
- **Final Cost**: 7 CP
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
**Target Number: (DX + Shield Skill)/2 + Shield Deflection (SD)**
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
- **Bleeding:** Each cutting wound that penetrates armor adds 1 to bleeding count. Each turn:
  - Lose bleeding_count Vitality
  - Roll vs EN with penalty -2 × bleeding_count to naturally heal one wound (reduce bleeding_count by 1)
  - When bleeding_count reaches 0, bleeding stops completely
- **Treatment:** First Aid roll as Major Action stops all bleeding immediately (wraping some bandage or available piece of cloth around the wound to compress it)
- **Examples:** Longsword (2d6-1 cutting), battleaxe (2d6 cutting)

#### Impaling Damage

Impaling attacks deal devastating damage by penetrating vital areas, but there are two types:

**1. Dedicated Impaling Weapons** (arrows, spears, pikes, lances):
- **Effect:** Damage that penetrates AR is **doubled**
- **Sources:** Arrows, javelins, spears, pikes, lances
- **Use weapon damage as listed** - no modifications
- **Examples:** Arrow (1d6+2 impaling), Spear (1d6+1 impaling), Pike (1d6+3 impaling)

**2. Slashing Weapons Used for Thrusting** (swords, daggers, knives):
- **Effect:** **Subtract 1 per die rolled first**, then damage that penetrates AR is **doubled**
- **Sources:** Swords, daggers, knives when thrusting instead of slashing
- **Why the subtraction?** Thrusts with slashing weapons are less effective than proper cuts
- **Examples:** Longsword thrust (2d6-1 cutting becomes 2d6-3 impaling), Dagger thrust (1d6-3 cutting becomes 1d6-4 impaling)

**Example 1 - Dedicated Impaling (Arrow):**
- Archer with ST 12 (+1) shoots arrow (1d6+2 impaling) vs target with AR 3
- Roll: 4 on 1d6+2 = 6 damage + 1 ST = **7 damage total**
- vs AR 3: 7 - 3 = **4 gets through**
- Impaling doubles: 4 × 2 = **8 Vitality damage**

**Example 2 - Dedicated Impaling (Heavy Spear):**
- Warrior with ST 14 (+2) thrusts spear (2d6 impaling) vs target with AR 3
- Roll: 9 on 2d6 = 9 damage + 2 ST = **11 damage total**
- vs AR 3: 11 - 3 = **8 gets through**
- Impaling doubles: 8 × 2 = **16 Vitality damage**

**Example 3 - Slashing Weapon Thrust (Longsword):**
- Warrior with ST 14 (+2) thrusts longsword (2d6-1 cutting) vs target with AR 4
- Roll: 7 on 2d6-1 = 6 damage
- **Subtract 1 per die for thrust:** 6 - 2 = 4 damage + 2 ST = **6 damage total**
- vs AR 4: 6 - 4 = **2 gets through**
- Impaling doubles: 2 × 2 = **4 Vitality damage**

**Example 4 - Same Longsword, Slashing Instead:**
- Warrior with ST 14 (+2) slashes longsword (2d6-1 cutting) vs target with AR 4
- Roll: 7 on 2d6-1 = 6 damage + 2 ST = **8 damage total**
- AR 4 counts as **8 vs cutting** damage
- 8 damage - 8 AR = **0 damage** (armor absorbed it all)
- If roll had been 10: 9 damage + 2 ST = 11 total
- 11 - 8 AR = **3 damage to Vitality + bleeding starts**

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

### Two-Weapon Fighting and Off-Hand Attacks

Characters can attack with two weapons or use their off-hand, but this comes with penalties unless they have the Ambidextrous perk.

**Off-Hand Penalty:**
- Attacking with your non-dominant hand: **-4 to hit**
- Applies to any action using the off-hand (attacking, throwing, catching, etc.)

**Two-Weapon Fighting:**
- Can attack with both weapons in the same turn as a single Major Action
- **Main hand attack**: -2 to hit
- **Off-hand attack**: -6 to hit (off-hand penalty already accounted)
- Both attacks roll separately against the same or different targets
- Defender gets separate defense rolls against each attack

**Ambidextrous Perk (10 CP):**
- **Removes all off-hand penalties**
- Off-hand attacks have no penalty
- Two-weapon fighting: Both attacks at -2 to hit (no additional off-hand penalty)
- Can use off-hand for any task without penalty

**Example - Two-Weapon Fighting:**
- **Without Ambidextrous**: Rogue attacks with two daggers. Main hand at -2 (DX 13 + Skill 4 - 2 = 15), off-hand at -6 (DX 13 + Skill 4 - 6 = 11).
- **With Ambidextrous**: Same rogue attacks with both daggers at -2 each (both at 15 to hit).

**Example - Off-Hand Use:**
- **Without Ambidextrous**: Warrior switches sword to off-hand to open door with main hand. When ambushed, attacks with sword in off-hand at -4.
- **With Ambidextrous**: Warrior can use either hand interchangeably with no penalty.

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

#### Bleeding to death
- When Vitality reaches 0, roll versus EN every turn (6 seconds), modified by how much negative vitality the character has
- Failing this roll sets the character unsconscious, and start bleeding by -1 vitality to death (if not bleeding already)
- Upon reaching -1 x Vitality the character is dead (bleeding stops)

### Combat Modifiers

**Situational:**
- **High Ground**: +2 to attacks
- **Flanking**: +2 when ally is opposite side of enemy
- **Cover**: Light +2 defense, Heavy +4 defense
- **Darkness**: -4 to attacks (unless Night Vision)
- **Prone**: -4 to attacks, attackers get +4 in melee / -4 at range
- **Range** (bows/guns): Penalties at long range per weapon

**Ranged Combat Modifiers:**
- **Range Penalty:** -1 to hit per log2(distance) rounded up. Example: for 10m, log2(10) = 3.3219, rounded up = 4, so -4 penalty
- **Range Damage Penalty:** after weapon max range, the damage is halved
- **Aiming Bonus:** Spend Major Action aiming, next shot gets +3 to hit (lost if you move or are hit)
- **Point-Blank Range:** Shooting within 2 meters with ranged weapon = -2 to hit (weapon too long/awkward at close range)

**Example Range Penalties:**
- Shortbow (max 50m): Shooting at 10m = -4 (log2(10)=3.32→4), at 30m = -5 (log2(30)=4.91→5), at 50m = -6 (log2(50)=5.64→6), at 55m = -6 (log2(55)=5.78→6) and deal half damage
- Longbow (max 100m): Shooting at 20m = -5 (log2(20)=4.32→5), at 60m = -6 (log2(60)=5.91→6), at 100m = -7 (log2(100)=6.64→7), at 105m = -7 (log2(105)=6.71→7) and deal half damage onwards
- Crossbow (max 80m): Shooting at 15m = -4 (log2(15)=3.91→4), at 60m = -6 (log2(60)=5.91→6), at 80m = -7 (log2(80)=6.32→7), at 85m = -7 (log2(85)=6.41→7) and deal half damage onwards

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

**Bleeding**: Lose bleeding_count Vitality per round. Each round, roll vs EN (penalty -2 × bleeding_count) to reduce bleeding by 1. First Aid (Major Action) stops all bleeding

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

## Environmental Hazards & Survival

Characters must manage basic needs and survive harsh environments.

### Nourishment

**Starvation:**
Characters need to eat regularly to maintain health and function.

- **Day 1 without food**: No immediate effect
- **Day 2-3 without food**: -2 to all physical actions, constant hunger
- **Day 4-7 without food**: -4 to all physical actions, -2 to mental actions, lose 1 Vitality per day
- **Day 8+ without food**: -6 to all actions, lose 2 Vitality per day, roll vs EN each day or collapse unconscious
- **After 2 weeks**: Roll vs EN each day or die from starvation

**Dehydration:**
Water is more critical than food for survival.

- **Day 1 without water**: -1 to all actions, constant thirst
- **Day 2 without water**: -4 to all physical actions, -2 to mental actions, lose 2 Vitality per day
- **Day 3 without water**: -6 to all actions, lose 4 Vitality per day, roll vs EN or collapse unconscious
- **Day 4+**: Roll vs EN each day or die from dehydration

**Hot/Desert environments**: Double the penalties and Vitality loss (need more water)

### Breath-Holding and Suffocation

**Breath-Holding:**
Characters can hold their breath for a limited time.

- **Normal breath-holding**: EN × 10 seconds (average human with EN 10 = 100 seconds / ~1.5 minutes)
- **After preparation** (deep breath, calm): EN × 15 seconds
- **Under stress** (combat, panic): EN × 5 seconds

**After breath-holding limit:**
- Start losing 2 Vitality per round (6 seconds)
- Must roll vs EN each round or fall unconscious
- Unconscious characters drown/suffocate in 1d6 rounds unless rescued

**Suffocation/Drowning:**
- Being strangled, buried, or in airless environment without preparation = immediate EN × 5 seconds limit
- Then lose 2 Vitality per round as above

**Vacuum/Space:**
- Exposure to vacuum causes 1d6 damage per round to exposed areas due to extreme cold
- Holding breath in vacuum: EN × 3 seconds only (pressure differential)
- Unconscious in 2-3 rounds, death in 1 minute without rescue

### Sleep Deprivation

Characters need rest to maintain mental and physical performance.

- **1 night without sleep**: -1 to all actions, -2 to Perception
- **2 nights without sleep**: -2 to all actions, -4 to Perception, roll vs WS or microsleep (freeze for 1 round randomly)
- **3 nights without sleep**: -4 to all actions, -6 to Perception, roll vs WS each hour or fall asleep uncontrollably for 1d6 hours
- **4+ nights without sleep**: -6 to all actions, hallucinations, roll vs WS every 30 minutes or collapse unconscious for 8+ hours

**Recovery**: Full 8-hour sleep removes all penalties. Partial sleep (4-6 hours) reduces penalty by half.

### Pain and Injury

Beyond the shock penalties from sudden damage (see [Pain and Shock](#pain-and-shock) in Combat section), ongoing injuries cause persistent effects, post combat:

**Ongoing Pain from Injuries:**
- **Below 50% Vitality**: -1 to all physical actions from accumulated injuries
- **Below 25% Vitality**: -2 to all physical actions, obvious limp/impairment
- **Below 10% Vitality**: -4 to all actions, barely functional, movement at half speed

**No Sense of Pain trait**: Immune to pain penalties, but -2 to notice injuries or damage to self

**High Pain Threshold perk**: Ignore first -2 from injury penalties

**Chronic Pain flaw**: -1 to all physical actions at all times (stacks with injury penalties)

### Disease and Poison

**Poison Types:**
Poisons cause various effects based on type and potency. See [Simverse_Powers_Library.md](Simverse_Powers_Library.md) for detailed poison effects and creation rules.

**Common Poison Effects:**
- **Lethal Poison**: Deals damage over time (1d6 per hour/minute/round depending on potency)
- **Paralyzing Poison**: Causes -4 to all actions, or complete paralysis on failed EN roll
- **Weakening Poison**: Reduces ST or EN by 1d6 for duration
- **Sedative**: Causes drowsiness (-4 to mental actions), sleep on failed EN roll
- **Hallucinogenic**: Causes -6 to Perception, hallucinations, roll vs WS per minute to act normally

**Resisting Poison:**
- Roll vs EN to resist or reduce poison effect
- Critical success: Negate completely (success by 10+)
- Success: Reduce effect by half or negate for weaker poisons
- Failure: Full poison effect applies, range of failure extends duration
- Critical failure: Double poison effect or duration

**Treating Poison:**
- Medicine skill roll can reduce ongoing poison effects
- Antidote (if available) neutralizes specific poison
- Healing magic can cure poison instantly
- Time: Most poisons run their course in hours to days

**Disease:**
Diseases are similar to poisons but spread over longer periods.

**Common Disease Effects:**
- **Mild Disease** (common cold, minor infection): -1 to actions, lasts 3-7 days
- **Moderate Disease** (flu, serious infection): -2 to physical actions, -1 to mental actions, lose 1 Vitality per day, lasts 1-2 weeks
- **Severe Disease** (plague, magical disease): -4 to all actions, lose 2 Vitality per day, lasts 2-4 weeks, may be contagious
- **Fatal Disease**: As severe, but also roll vs EN each day or lose 1 EN permanently. Death at EN 0.

**Resisting Disease:**
- Initial exposure: Roll vs EN to avoid contracting disease
- During disease: Roll vs EN each day to start recovering (reduce duration)
- Resilient perk: +2 to resist poison and disease

**Treating Disease:**
- Medicine skill can improve recovery (reduce penalties or duration)
- Magical dieseases may require Occult Knowledge instead
- Magical healing often cures disease instantly
- Rest and proper care: +2 to resistance rolls

### Travel & Exploration

#### Travel Pace

Characters can travel at different paces affecting distance and fatigue:

| Pace | Distance/Day | Effects |
|------|--------------|---------|
| **Cautious** | Speed × 3 km | +2 to Perception, can use Stealth, no fatigue |
| **Normal** | Speed × 5 km | Standard travel, 1 Stamina per 4 hours |
| **Forced March** | Speed × 7 km | -2 to Perception, 2 Stamina per 4 hours, roll vs EN each 4 hours or gain 1 level Fatigue |

**Standard Day**: 8 hours of travel with breaks. Characters can push to 12 hours at Forced March pace (roll vs EN or -2 to all actions next day).

#### Terrain Modifiers

| Terrain | Distance Modifier | Notes |
|---------|-------------------|-------|
| Road/Trail | ×1 | Standard |
| Open Plains | ×0.9 | Slightly slower |
| Light Forest | ×0.75 | Some obstacles |
| Dense Forest/Jungle | ×0.5 | Navigation check or get lost |
| Hills | ×0.6 | Stamina cost +50% |
| Mountains | ×0.4 | Climbing required, double Stamina |
| Swamp | ×0.3 | Triple Stamina, disease risk |
| Desert | ×0.5 | Double water requirement |

#### Encumbrance During Travel

Add one level of effective encumbrance for travel fatigue calculations:
- Medium encumbrance travels as if Heavy
- Overburdened characters cannot maintain Forced March pace
- Heavy+ encumbrance doubles Stamina costs for travel

#### Fatigue System

Extended exertion causes cumulative fatigue:

| Fatigue Level | Effects |
|---------------|---------|
| **1 - Tired** | -1 to all actions |
| **2 - Weary** | -2 to all actions, half movement |
| **3 - Exhausted** | -4 to all actions, cannot sprint, -2 to defenses |
| **4 - Collapse** | Fall unconscious, must rest 8 hours |

**Gaining Fatigue:**
- Failed EN roll during Forced March
- 8+ hours of travel without rest
- Heavy exertion while Overburdened
- Fighting while already Weary or worse

**Recovering Fatigue:**
- Short rest (1 hour): Reduce 1 fatigue level, recover Stamina = ST/2
- Long rest (8 hours): Remove all fatigue, full Stamina/Vitality recovery (see Recovery in Downtime Activities)

#### Navigation

**Getting Lost:**
When traveling without clear path, roll Survival or Navigation:
- **Success**: Travel correct direction, full distance
- **Failure by 1-4**: Drift off course, lose 25% distance
- **Failure by 5-9**: Wrong direction for half day, lose 50% distance
- **Failure by 10+**: Completely lost, no progress, may enter dangerous area

**Modifiers:**
- Map/directions: +2 to +4
- Guide who knows area: +4
- Poor weather: -2 to -4
- Night travel: -4

#### Mounts and Vehicles

| Mount/Vehicle | Speed Multiplier | Carry Capacity | Notes |
|---------------|------------------|----------------|-------|
| Riding Horse | ×2 | 80 kg rider + 40 kg gear | Can't maintain sprint long |
| War Horse | ×1.8 | 100 kg rider + 60 kg gear | Combat trained |
| Draft Horse | ×1.2 | Pulls 500 kg | Slow but strong |
| Wagon | ×1 | 1000+ kg | Requires roads, draft animal |
| Camel | ×1.5 | 150 kg total | Desert specialist, less water |

Mounted characters use mount's Speed for travel but rider's skills for navigation.

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
- Just spend CP following sum progression costs
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

### Downtime Activities

During periods between adventures, characters can engage in productive activities. Each activity has a time requirement and potential outcomes.

#### Time Allocation

A character can engage in **one primary activity per day** (4-8 hours) plus **one secondary activity** (1-2 hours). Some activities can be combined.

#### Recovery

**Short Rest (1 hour):**
- Recover Stamina = ST/2
- Recover Mana = AW/2
- Reduce 1 Fatigue level

**Long Rest (8 hours sleep):**
- Recover all Stamina and Mana
- Recover Vitality = EN/2 (natural healing)
- Remove all Fatigue
- **With medical care**: Recover Vitality = EN (double healing)
- **With magical healing environment**: As medical care plus cure one disease/poison

**Meditation (1 hour):**
- Roll Meditation skill
- Success: Recover additional Mana = margin of success
- Can be done multiple times per day, but each subsequent attempt is at -2
- Requires quiet, undisturbed environment

**Bed Rest (full day):**
- Recover Vitality = EN (even without medical care)
- **With medical care**: Recover Vitality = EN × 1.5
- Required for serious injuries (broken bones, organ damage)

#### Serious Injuries as Temporary Flaws

Major injuries impose **temporary flaws** on the character until healed. These use existing flaw mechanics but are gained through injury rather than character creation:

| Injury | Temporary Flaw | CP Value | Natural Healing Time |
|--------|----------------|----------|----------------------|
| Broken arm | One Arm (-20) | 20 | 6-8 weeks |
| Broken leg | Lame (-15) | 15 | 6-8 weeks |
| Severe burns | Chronic Pain (-10) | 10 | 2-4 weeks |
| Concussion | Slow (-10) | 10 | 1-2 weeks |
| Damaged eye | One Eye (-10) | 10 | Permanent without magic |
| Paralysis (partial) | Lame (-15) or Paraplegic (-30) | 15-30 | Permanent without magic |
| Internal injury | Fragile (-15) | 15 | 3-4 weeks |

**Removing Injury Flaws:**
- **Medical Treatment**: Proper care (Surgery + ongoing Medicine rolls) allows natural healing over time
- **Magical Healing**: Appropriate healing magic removes injury instantly
- **Spending CP**: Character can spend CP equal to the flaw value to "miraculously" heal faster (represents body's extraordinary recovery, divine intervention, or narrative convenience)

**Example:** A character breaks their leg, gaining the Lame (-15) temporary flaw. They can:
- Wait 6-8 weeks with proper medical care
- Receive healing magic to remove it instantly
- Spend 15 CP to heal dramatically faster (perhaps over a few days)

#### Medical Treatment

**First Aid** (immediate, 1-10 minutes, Major action in combat):
- Roll Medicine/First Aid skill vs wound severity
- Success: Stop all bleeding (set bleeding_count to 0), prevent infection, stabilize patient
- Each 5 margin: +1 Vitality recovered immediately (max EN/2)
- Requires: Basic medical supplies

**Surgery** (1-4 hours):
- Required for: embedded objects, internal injuries, setting broken bones
- Roll Surgery skill (Hard) at appropriate difficulty
- Success: Begin proper healing, injury flaw can start recovering
- Failure: Patient loses 1d6 Vitality, complications (may worsen flaw)
- Requires: Surgery tools, clean environment, assistant helpful (+2)

**Ongoing Care** (daily attention):
- Roll Medicine once per day
- Success: Patient gets +2 to recovery rolls, halves healing time for injury flaws
- Can treat up to IN/2 patients simultaneously

#### Crafting and Recipes

All crafting follows a unified recipe system. Whether forging weapons, brewing potions, or creating magical items, the process uses the same structure.

**Recipe Components:**
Every recipe specifies:
- **Required Skill** (Blacksmithing, Alchemy, Leatherworking, etc.)
- **Difficulty Modifier** (penalty to the skill roll)
- **Time Required** (hours, days, or weeks)
- **Materials/Ingredients** (specific items needed)
- **Tools Required** (workshop, alchemist's kit, forge, etc.)

**Crafting Procedure:**
1. **Verify Requirements**: Must know the recipe, have tools and materials
2. **Spend Time**: Complete the required crafting time
3. **Roll Skill**: Roll relevant craft skill with difficulty modifier
4. **Determine Outcome**: Based on success/failure margin

**Crafting Results:**
| Roll Result | Outcome |
|-------------|---------|
| **Critical Success** | Exceptional quality (+1 tier), extra doses/effects, or half materials used |
| **Success by 5+** | Superior result, possible bonus effect or durability |
| **Success** | Item created as specified |
| **Failure by 1-4** | Flawed item (reduced quality) OR +50% time needed to fix |
| **Failure by 5+** | Materials ruined, must start over |
| **Critical Failure** | Materials ruined, possible damage to tools or crafter (explosion, injury, etc.) |

**Quality/Tool/Material Modifiers:**
| Condition | Modifier |
|-----------|----------|
| Excellent tools | +2 |
| Standard tools | +0 |
| Poor/improvised tools | -2 to -4 |
| Missing essential tool | Cannot attempt or -6 |
| Premium materials | +2 |
| Standard materials | +0 |
| Substandard materials | -2 |
| Substituted ingredients | -2 to -4 |

#### Alchemy (Hard Skill)

Alchemy covers potion brewing, poison creation, and alchemical compounds. It follows the standard recipe system with additional rules for experimentation.

**Potion Brewing:**
- Must know the recipe (learned from teacher, book, or experimentation)
- Requires alchemist's tools (retorts, burners, vials, etc.)
- Requires specific ingredients (herbs, reagents, monster parts, etc.)

**Example Potion Recipes:**

| Potion | Difficulty | Time | Ingredients | Effect |
|--------|------------|------|-------------|--------|
| Healing Potion (Minor) | -2 | 2 hours | Healroot, purified water | Restore 1d6+2 Vitality |
| Healing Potion (Major) | -4 | 4 hours | Healroot ×2, moonpetal, silver dust | Restore 2d6+4 Vitality |
| Antidote | -3 | 2 hours | Neutralizing moss, charcoal, clean water | Cure poison (EN roll +4) |
| Stamina Tonic | -2 | 1 hour | Ginseng root, honey, stimulant herbs | Restore 2d6 Stamina |
| Mana Elixir | -4 | 3 hours | Arcane crystal dust, moonwater, lotus | Restore 2d6 Mana |
| Fire Resistance | -5 | 4 hours | Salamander scale, frost lily, mineral oil | Resist fire (AR +4 vs fire) for 1 hour |
| Invisibility | -8 | 8 hours | Chameleon skin, ghost orchid, quicksilver | Invisibility for 10 minutes |
| Poison (Lethal) | -4 | 2 hours | Deathcap, viper venom, black lotus | 2d6 damage per hour for 4 hours |

**Alchemy Roll Modifiers:**
- Complete laboratory: +2
- Field kit only: -2
- Fresh ingredients: +1
- Aged/degraded ingredients: -1 to -3
- Rare/exotic ingredients: Usually required for powerful effects

**Experimentation:**
Alchemists can attempt to create new recipes or modify existing ones:

1. **Describe Desired Effect**: Tell GM what you want to achieve
2. **GM Sets Difficulty**: Based on similar recipes or effect power (-4 to -10 typical)
3. **Gather Materials**: May need to seek specific rare ingredients
4. **Attempt Roll**: Roll Alchemy vs difficulty
5. **Interpret Results**:
   - **Success**: Discover working recipe, can reproduce it
   - **Failure by 1-4**: Partial success—learn what's missing (specific ingredient or tool needed)
   - **Failure by 5+**: Complete failure, materials wasted, no useful information
   - **Critical Failure**: Dangerous reaction—explosion (2d6 damage in 2m radius), toxic fumes (poison check), or tool destruction

**Experimentation Example:**
An alchemist wants to create a potion granting water breathing. The GM decides this is similar to other transformation potions (difficulty -6). The alchemist rolls Alchemy-6. On failure by 3, the GM tells them the formula needs "essence of a water-breathing creature"—they must obtain fish gills, nixie tears, or similar. On success, they've created the recipe and can brew it again at -6 difficulty.

#### Enchanting (Hard Skill)

Enchanting allows spellcasters to imbue permanent magical effects into items. Any spell the enchanter knows can be placed into a suitable item vessel, though maneuvers cannot be enchanted.

**Requirements:**
- Know the spell to be enchanted (or have access to it via scroll/teacher)
- Suitable prepared item vessel (weapon, ring, amulet, etc.)
- Reagents as specified by GM based on the effect
- Initial roll: Enchanting skill (or Occult Knowledge, or Theology for divine powers)

**Difficulty Modifier:**
- -1 per tier of the spell being enchanted
- -1 per tier of spells already on the item (enchanting additional effects is harder)

**Enchanted Item Activation:**
- Enchanted items always consume the **user's Mana** when activated
- Items have no inherent charges
- To allow alternative power source, a **Mana Stone** must be incorporated into the item
- User can then choose to draw from their own Mana or the item's Mana Stone

**Two Methods of Enchanting:**

##### Regular Enchanting (Time-Intensive)

For each CP of the spell's cost:
- **10 days of work** (2 hours per day)
- Must remain stationary (cannot be traveling)
- Well-equipped laboratory or sacred place: Reduce time by up to 50% (GM discretion)

**Assistants:** Each assistant who also knows the spell reduces time by 5%, up to -50% maximum. This does not stack with lab bonus—maximum time reduction is 50% total.

**At the end of the enchanting period**, roll Enchanting with the difficulty modifier.

| Result | Outcome |
|--------|---------|
| **Critical Success** | Enchantment complete with bonus effect (extra charges, enhanced power, etc.) |
| **Success** | Enchantment complete as intended |
| **Failure** | Must start the process over (time wasted, materials intact) |
| **Critical Failure** | Item destroyed |

After enchanting one spell, you may proceed to enchant another on the same item, but each additional enchantment increases difficulty.

##### Immediate Enchanting (Energy-Intensive)

For each CP of the spell's cost:
- **20 Mana** provided by the enchanter, mana stones, or other sources
- Mana is consumed instantly upon attempt
- **Warning**: If all your Mana is consumed directly, you may faint or worse

Roll Enchanting with the difficulty modifier immediately.

| Result | Outcome |
|--------|---------|
| **Critical Success** | Enchantment complete with bonus effect |
| **Success** | Enchantment complete as intended |
| **Failure** | Item destroyed, Mana lost |
| **Critical Failure** | Item destroyed, enchanter takes damage, may gain temporary injury flaw |

**Assistants with Immediate Enchanting:**
- Assistants need not know the spell, only have Mage Gift and be willing
- Each assistant may contribute up to their full Mana
- For every 2 Mana drained from assistants, only 1 is useful to the enchanter
- Each assistant adds -1 to the Enchanting roll difficulty
- **If the enchantment fails or critically fails, all assistants suffer the bad outcomes too!**

**Example:** Enchanting a 10 CP spell immediately requires 200 Mana. With two assistants contributing 40 Mana each (yielding 20 + 20 = 40 useful Mana), the enchanter needs to provide 160 Mana themselves, and the roll is at -2 additional penalty from the assistants.

#### Mana Stones

Mana Stones are enchanted items that store magical energy for later use. They are created using the standard enchanting rules.

**Creating Mana Stones:**
- Each 1 point of Mana storage capacity is enchanted as a 1 CP **Tier 1 (Minor) spell**
- Must use Regular or Immediate enchanting methods
- Multiple points of storage must be enchanted separately (e.g., a 5 Mana stone requires 5 separate Tier 1 enchantments)

**Mana Stone Recovery:**
- Recover **1 Mana per day** under normal conditions
- **Sacred or deeply magical places**: Faster recovery (GM discretion, typically 2-5 per day)
- **No-mana zones**: No recovery at all

**Availability and Rarity:**

| Capacity | Rarity | Availability | Approximate Cost |
|----------|--------|--------------|------------------|
| 1-5 Mana | Common | Easily purchased in magic shops | Affordable |
| 6-10 Mana | Rare | Expensive, limited availability | Costly |
| 11-20 Mana | Very Rare | Very hard to craft or find | Very expensive |
| 21-50 Mana | Legendary | Almost impossible to purchase | Extremely expensive |

**Natural Mana Stones:**
In deeply magical places—ancient groves, ley line nexuses, sites of great magical events—Mana Stones occasionally form naturally. These are ultra-rare and highly sought after, often the subject of quests or the treasures of powerful creatures.

#### Other Crafting Skills

**Blacksmithing** (weapons, armor, metal tools):
- Requires forge, anvil, hammer, tongs
- Base time: 1 day per 10 gold value
- Quality affects damage/protection and durability

**Leatherworking** (leather armor, bags, straps):
- Requires cutting tools, needles, tanning supplies
- Base time: 4 hours per 5 gold value
- Can incorporate special hides for bonuses

**Woodworking** (bows, shafts, shields, furniture):
- Requires carving tools, lathe (for fine work)
- Base time: 4 hours per 5 gold value
- Wood type affects final properties

**Engineering** (mechanisms, siege equipment, complex devices):
- Hard skill, requires drafting tools and workshop
- Base time: 1 week+ for complex devices
- Often requires multiple rolls for subsystems

#### Repair and Maintenance

**Equipment Repair:**
- Time: 10% of original crafting time per point of damage/degradation
- Skill: Same as crafting the item
- Materials: 10% of item cost per point repaired

**Weapon/Armor Maintenance** (1 hour):
- Prevents degradation from regular use
- Required weekly for metal items, daily in wet/harsh conditions
- No roll needed, just time and basic supplies
- Neglected equipment: -1 to function per week of neglect

#### Research and Study

**Learning New Knowledge:**
- Time: As skill training (1 CP/week base, modified by resources/teacher)
- Activities: Reading, experimenting, practice
- Can combine with other light duties

**Research Specific Information:**
- Time: Varies by obscurity (hours to weeks)
- Roll: Research or appropriate Knowledge skill
- **Success**: Find accurate information
- **Failure**: Find incomplete info or take additional time
- **Critical failure**: Find misleading information

| Information Type | Base Time | Difficulty |
|------------------|-----------|------------|
| Common knowledge | 1 hour | +2 |
| Specialized | 4 hours | 0 |
| Obscure | 1-3 days | -2 |
| Rare/Secret | 1 week+ | -4 to -6 |

**Library/Resource Quality:**
- Poor: +50% time, -2 to rolls
- Average: Normal
- Good: -25% time, +2 to rolls
- Excellent: Half time, +4 to rolls

#### Practice and Training

**Skill Practice** (follows existing training rules):
- 1 CP worth of progress per week (base)
- Requires 4+ hours daily practice
- Can combine with light duties

**Physical Training:**
- Maintain fitness: 1 hour/day
- Improve attributes: 4+ hours/day, 10× CP cost in weeks
- Athletics, combat drills, strength training

**Sparring/Combat Practice:**
- Gain familiarity with specific opponents (+1 vs that fighting style)
- Develop new techniques (work toward maneuver CP cost)
- Requires partner of similar or greater skill

#### Social Activities

**Gather Information** (2-4 hours):
- Roll Streetwise, Persuasion, or Etiquette
- Learn rumors, locate people/places, gauge local mood
- Better results in appropriate venues (taverns, markets, guilds)

**Build Contacts** (days to weeks):
- Repeated positive social interactions
- Eventually gain Contacts advantage (see Perks)
- Requires investment of time and often money

**Work for Income:**
| Work Type | Daily Income | Skill Required |
|-----------|--------------|----------------|
| Unskilled labor | 1-2 silver | None |
| Skilled labor | 5-10 silver | Relevant craft 2+ |
| Professional | 1-5 gold | Relevant skill 4+ |
| Expert | 5-20 gold | Relevant skill 6+, reputation |

#### Writing and Documentation

**Transcription:**
- Copy existing text: 10 pages per day
- Requires: Writing materials, original text

**Composition:**
- Letters, reports: 1-2 hours
- Technical documents: 4-8 hours
- Books/manuals: Weeks to months

**Creating Spell Scrolls/Formulae:**
- Time: Power CP cost in hours (minimum 4 hours)
- Skill: Appropriate magic skill
- Materials: Special inks, paper (10 x power CP cost in silver coins)
- Creates one-use magical item or permanent reference

#### Combined Activities

Some activities can be done together:
- **Travel + Gather Information**: At each stop
- **Recovery + Light Study**: Reading while resting
- **Crafting + Training**: Learn while doing (if master craftsman teaches)
- **Guard Duty + Practice**: Drill and watch (reduced efficiency for both)

Activities that **cannot** be combined:
- Surgery + anything else
- Forced march + anything productive
- Complex crafting + other focused work
- Enchanting (requires full concentration)

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
**Defense**: Dodge (DX/2+AD), Parry ((DX+Skill)/2, -4 if acted), Block ((DX+Skill)/2+SD)
**Damage**: Weapon roll - AR = Vitality loss

### Starting Character (100 CP Budget)
1. Buy templates: ~30-80 CP (race + profession)
2. Adjust attributes: ~10-30 CP (raise 1-2 key attributes)
3. Buy perks: ~5-15 CP (1-3 perks)
4. Buy skills: ~10-20 CP (boost template skills or add new ones)
5. Buy powers/maneuvers: ~10-25 CP (3-8 abilities)
6. Take flaws: Optional, up to -50 CP (enables 150 CP total)

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