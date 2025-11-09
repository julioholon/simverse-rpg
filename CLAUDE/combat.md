# SIMVERSE RPG: AI Combat Guide
**Quick Reference for Running Combat Encounters & Resolving Actions**

---

## AI COMBAT AGENT ROLE

When running combat encounters:
1. **Describe cinematically** - Make every attack vivid and exciting
2. **Track everything** - Status effects, bleeding, pain penalties, ongoing conditions
3. **Be fair but dramatic** - Apply rules consistently, but favor exciting outcomes
4. **Use tactics** - Enemies should act intelligently (cover, flanking, targeting)
5. **Ask for clarification** - "Do you want to Dodge, Parry, or Block?" "Which target?"
6. **Show the math** - Be transparent: "You rolled 12 vs target 17, margin 5, so defender gets -1"
7. **Keep pace moving** - Don't let combat drag; summarize minor details when appropriate
8. **Remind players** - "You're still bleeding (-1/turn)" "You took 12 damage last turn outside combat, so -2 to all actions this turn"

---

## CORE COMBAT PHILOSOPHY

**System**: Roll 3d6 ≤ (Attribute + Skill + modifiers) = Success
**Combat Style**: Tactical, consequence-driven, bell-curve probability
**AI Goal**: Make combat exciting, fair, and narratively interesting

---

## COMBAT FLOW OVERVIEW

### STEP-BY-STEP COMBAT SEQUENCE

1. **Determine Surprise** (if applicable)
2. **Resolve Initiative** (compare Speed values)
3. **For Each Turn** (highest Speed first):
   - Declare Major Action
   - Declare Minor Action
   - Resolve actions
   - Use Reaction if attacked
   - Apply ongoing effects (bleeding, poison, etc.)
4. **Repeat** until combat ends

---

## 1. INITIATIVE & SURPRISE

### Initiative Order
**Speed = (DX + EN) / 4** (don't round)

- Highest Speed acts first
- Ties: Higher AW goes first, then simultaneous
- Record initiative order at start, keeps throughout combat

**Example Initiative:**
```
Lyra (Speed 5.5) → Marcus (Speed 5) → Thorin (Speed 4.5) → Goblin (Speed 4)
```

### Surprise Encounters

When one side is unaware:

1. **Surprised characters roll vs Speed × 2**
2. **Each 5 margin of success/failure = ±1 to Speed this round**
3. **Critical failure (666):** Act last this round, -2 to all actions

**Example:**
- Thorin (Speed 4.5, target 9) rolls 7 → margin 2 → no bonus
- Marcus (Speed 5, target 10) rolls 15 → margin -5 → Speed 4 this round
- Goblin ambusher gets surprise round advantage

**Notes:**
- Combat Reflex perk negates surprise

---

## 2. ACTION ECONOMY

Each character gets **per turn**:

| Action Type | Limit | Examples |
|-------------|-------|----------|
| **Major Action** | 1 | Attack, cast spell, full movement, activate power, aim |
| **Minor Action** | 1 | Draw weapon, command ally, quick perception check, bandage bleeding |
| **Reaction** | 1 (3 if Full Defense) | Dodge/Parry/Block when attacked |
| **Free Actions** | Unlimited (GM discretion) | Drop item, speak briefly, fall prone |

### Common Actions Breakdown

**Major Actions:**
- Attack with weapon or spell
- Full Movement (Speed × 2 meters)
- Sprint (Speed × 4 meters, costs 1 Stamina)
- Cast most spells
- Activate most powers
- Aim (grants +3 to next ranged attack)
- Use complex skill (pick lock, first aid on unconscious ally)

**Minor Actions:**
- Draw/stow weapon (or Quick Draw maneuver as free action)
- Move up to Speed in meters
- Bandage bleeding wound (First Aid roll)
- Shout command/warning
- Quick perception check

**Reactions:**
- Dodge incoming attack
- Parry with weapon
- Block with shield
- Use instant action maneuver os spell, like Riposte

**Special: Full Defense** - Use Major Action to gain **3 Reactions** this turn instead of 1

---

## 3. ATTACK RESOLUTION

### Attack Sequence (7 Steps)

**1. ATTACKER DECLARES TARGET & METHOD**
   - "I attack the goblin with my sword"
   - "I shoot the wizard with my longbow"

**2. ATTACKER ROLLS**
   - Roll: 3d6 ≤ (DX + Weapon Skill + modifiers)
   - Example: DX 13 + Swords 4 + Flanking +2 = 19 target, rolls 12 = SUCCESS

**3. CALCULATE MARGIN OF SUCCESS**
   - Margin = Target Number - Roll Result
   - Example: 19 - 12 = **Margin 7**

**4. APPLY MARGIN PENALTY TO DEFENDER**
   - Each 5 margin = -1 to defender's defense roll
   - Example: Margin 7 = -1 to defender (round down from 1.4)
   - Margin 12 = -2 to defender
   - Margin 18 = -3 to defender

**5. DEFENDER CHOOSES DEFENSE**
   - **Dodge**: DX/2 + AD (Armor Deflection)
   - **Parry**: (DX + Weapon Skill)/2, -4 if attacked this turn
   - **Block**: (DX + Shield Skill)/2 + SD (Shield Deflection), frontal only

**6. DEFENDER ROLLS DEFENSE**
   - Roll 3d6 ≤ (Defense Value - Margin Penalty)
   - Example: Dodge 7 - 1 (margin penalty) = target 6, rolls 8 = FAILURE

**7. IF DEFENSE FAILS, ROLL DAMAGE**
   - Attacker rolls weapon damage dice
   - Add ST bonus (for melee/thrown)
   - Subtract Armor Resistance (AR)
   - Apply damage type effects
   - Reduce Vitality

### Quick Example - Complete Attack

**Setup:** Marcus (DX 14, Swords 5) attacks Goblin (DX 12, AR 2)

1. **Attack Roll:** 3d6 ≤ 19 (DX 14 + Swords 5), rolls **11** → Success
2. **Margin:** 19 - 11 = **8 margin**
3. **Defender Penalty:** 8 ÷ 5 = -1 (round down)
4. **Goblin Dodges:** DX 12/2 = 6, minus 1 = target **5**
5. **Goblin Rolls:** 3d6 ≤ 5, rolls **9** → FAILURE, hit confirmed
6. **Damage Roll:** Longsword 2d6-1 + ST bonus +2 = rolls 8, total **9 damage**
7. **After AR:** 9 - 2 AR = **7 Vitality damage** to goblin

---

## 4. DEFENSE OPTIONS (CRITICAL!)

### Dodge
**Target Number: DX/2 + AD (Armor Deflection)**

**Advantages:**
- Works vs ALL attacks (melee, ranged, spells, area effects)
- No penalty for attacking this turn
- Light/medium armor helps with AD

**Disadvantages:**
- Usually lowest defense value
- Doesn't benefit from weapon skill

**Best For:** Lightly armored characters, avoiding ranged attacks, avoiding area effects

**Example:** DX 14 character in chain shirt (AD 1) = 14/2 + 1 = **8 to dodge**

---

### Parry
**Target Number: (DX + Weapon Skill)/2**

**Advantages:**
- Benefits from weapon skill (potentially high value)
- Can counter-attack with Riposte maneuver

**Disadvantages:**
- **-4 penalty if you attacked with that weapon this turn**
- Only works vs melee attacks
- Can damage weapon on critical failure

**Best For:** Skilled melee fighters who haven't attacked yet, defensive warriors

**Example:**
- DX 14 + Swords 6 = (14 + 6)/2 = **10 to parry** (if didn't attack)
- Same character after attacking = 10 - 4 = **6 to parry**

---

### Block
**Target Number: (DX + Shield Skill)/2 + SD (Shield Deflection)**

**Advantages:**
- Usually highest defense value for shield users
- Benefits from Shield Deflection (SD 1-3)
- No penalty for attacking

**Disadvantages:**
- Only works against **frontal attacks**
- Requires shield equipped
- Shield can break on critical failures (optional rule)

**Best For:** Shield-wielding warriors, defensive tanks

**Example:**
- DX 12 + Shield 4 + Medium Shield (SD 2) = (12 + 4)/2 + 2 = **8 + 2 = 10 to block**

---

### When to Use Which Defense

| Situation | Best Defense | Reason |
|-----------|--------------|--------|
| Archer shooting at you | Dodge | Only option that works vs ranged |
| Melee attack, you have shield | Block | Highest value, no attack penalty |
| Melee attack, high weapon skill, haven't attacked | Parry | High value from skill |
| Melee attack, you already attacked | Dodge or Block | Parry takes -4 penalty |
| Area effect spell | Dodge | Only option |
| Flanked/rear attack | Dodge | Block doesn't work, Parry unreliable |

---

## 5. DAMAGE CALCULATION

### Basic Damage Formula
```
Final Damage = Weapon Dice Roll + ST Bonus - Armor Resistance (AR)
Minimum Damage = 1 (if AR = 0)
```

### Step-by-Step Damage

**1. Roll Weapon Base Damage**
- Dagger: 1d6-3
- Longsword: 2d6-1
- Greatsword: 3d6
- Longbow: 2d6

**2. Add ST Damage Bonus** (melee/thrown only)
- ST 10-11: +0
- ST 12-13: +1
- ST 14-15: +2
- ST 16-17: +3
- ST 18-19: +4

**3. Apply to Armor**
- **Bludgeoning:** AR applies normally
- **Cutting:** AR × 2 (double), but causes bleeding if penetrates
- **Impaling (dedicated weapons):** AR applies normally, then penetrating damage × 2
- **Impaling (slashing weapon thrust):** Subtract 1 per die first, then penetrating damage × 2
- **Energy/Magical:** AR applies normally, plus special effects

**4. Calculate Final Damage**
- Subtract AR from damage
- Apply minimum damage rule (1 if total AR = 0)
- Reduce Vitality by final damage

### Damage Examples

**Example 1 - Bludgeoning:**
- Mace (2d6) + ST 14 (+2) = rolls 9
- 9 + 2 = 11 total damage
- vs AR 4: 11 - 4 = **7 Vitality damage**

**Example 2 - Cutting:**
- Longsword (2d6-1) + ST 16 (+3) = rolls 8
- 8 - 1 + 3 = 10 total damage
- vs AR 3: AR counts as 6 for cutting
- 10 - 6 = **4 Vitality damage + bleeding (-1 Vitality/turn)**

**Example 3 - Dedicated Impaling (Arrow):**
- Arrow (1d6+2) + ST 12 (+1) = rolls 4
- 4 + 2 + 1 = 7 total damage
- vs AR 3: 7 - 3 = 4 penetrates
- Impaling doubles: 4 × 2 = **8 Vitality damage**

**Example 4 - Slashing Weapon Thrust (Longsword):**
- Longsword thrust (2d6-1) + ST 14 (+2) = rolls 7 on 2d6
- 7 - 1 = 6, **subtract 1 per die (2)**: 6 - 2 = 4 + 2 ST = **6 total**
- vs AR 4: 6 - 4 = 2 penetrates
- Impaling doubles: 2 × 2 = **4 Vitality damage**

---

## 6. DAMAGE TYPES (CRUCIAL!)

### Bludgeoning (Most Common)
**Sources:** Clubs, maces, hammers, fists, falls, force magic

**Mechanics:**
- AR subtracts normally
- No special effects
- Good vs heavy armor

**Tactical:** Default damage type, reliable vs all armor types

---

### Cutting (High Risk/Reward)
**Sources:** Swords, axes, slashing weapons

**Mechanics:**
- **AR counts DOUBLE** (AR 3 = 6 vs cutting)
- Damage that penetrates causes **bleeding**
- **Bleeding:** -1 Vitality per turn until bandaged (First Aid as Minor Action)

**Tactical:** Devastating vs unarmored/light armor, poor vs heavy armor

**Example:**
- 10 damage vs AR 3 → AR counts as 6 → 10 - 6 = 4 damage + bleeding
- 10 damage vs AR 5 → AR counts as 10 → 0 damage (fully absorbed)

---

### Impaling (Armor Penetration)
**Sources:** Spears, arrows, pikes, rapiers (dedicated), OR swords/daggers when thrusting

**Two Types:**

**1. Dedicated Impaling Weapons** (spears, arrows, pikes, rapiers):
- AR applies normally
- **Penetrating damage × 2**
- No die penalty

**2. Slashing Weapons Thrust** (swords, daggers thrusting):
- **Subtract 1 per die rolled FIRST**
- Then AR applies normally
- Then **penetrating damage × 2**

**Tactical:** Best for penetrating heavy armor with precision

**Examples:**
- Spear 1d6+1 + ST +2 = 8 total vs AR 4 → 4 penetrates × 2 = **8 damage**
- Longsword thrust (2d6-1, -2 more for thrust) + ST +2 = 9 - 3 = 6 vs AR 4 → 2 penetrates × 2 = **4 damage**

---

### Energy/Magical (Special Effects)
**Sources:** Fire, cold, lightning, acid, force magic

**Mechanics:**
- AR applies normally (like bludgeoning)
- **Additional effects** based on type

**Types:**
- **Fire:** May ignite (1d6/turn for 1d6 turns), ongoing burn
- **Cold:** May slow (-2 Speed, -2 Dodge for 1d6 turns)
- **Lightning:** May cause muscle spasms (roll vs ST or drop items)
- **Acid:** May damage equipment, ongoing damage (1d6-2/turn)
- **Force:** Pure energy, enhanced knockback

**Tactical:** Variable utility beyond raw damage

---

## 7. ARMOR & SHIELDS

### Armor System

Armor provides two benefits:
- **AD (Armor Deflection):** Adds to Dodge defense
- **AR (Armor Resistance):** Subtracts from damage

| Armor Type | AD | AR | Penalty | Examples |
|------------|----|----|---------|----------|
| **Light** | 0 | 1-2 | 0 | Leather, padded cloth |
| **Medium** | 1 | 3-5 | -2 | Chain shirt, scale mail |
| **Heavy** | 2 | 6-10 | -4 | Plate mail, full plate |

**Armor Penalties:**
- Apply to: Physical skills (climbing, stealth, acrobatics), casting with gestures
- Don't apply to: Pure mental skills, attacks (but may affect movement)
- **Armor Familiarity perk (5 CP):** Reduce penalty by 2
- **Heavy Armor Familiarity perk (10 CP):** Reduce penalty by 4

### Shields

Shields add to Block defense only (not Dodge or Parry):

| Shield Type | SD (Shield Deflection) | Cost |
|-------------|----------------------|------|
| **Small/Buckler** | +1 | 10 sp |
| **Medium** | +2 | 25 sp |
| **Large/Tower** | +3 | 50 sp |

**Limitation:** Only works against frontal attacks

---

## 8. COMBAT MODIFIERS

### Situational Modifiers

| Situation | Modifier | Applies To |
|-----------|----------|------------|
| **High Ground** | +2 | Attacks downward |
| **Flanking** | +2 | Attack when ally opposite side |
| **Light Cover** | +2 | Defender's defense rolls |
| **Heavy Cover** | +4 | Defender's defense rolls |
| **Darkness** | -4 | Attacks (unless Night Vision) |
| **Prone Attacker** | -4 | Attacks from prone |
| **Prone Defender** | +4 (melee), -4 (ranged) | To be hit while prone |

### Ranged Combat Modifiers

**Range Penalties:**
- **-1 to hit per 5m beyond half maximum range**
- **Half damage beyond maximum range**

**Examples:**
- Shortbow (max 50m): Penalties after 25m
  - At 30m: -1 to hit
  - At 50m: -5 to hit
  - At 55m: -6 to hit + half damage
- Longbow (max 100m): Penalties after 50m
  - At 60m: -2 to hit
  - At 100m: -10 to hit
  - At 110m: -12 to hit + half damage

**Aiming Bonus:**
- Spend Major Action to aim
- Next shot against same target: **+3 to hit**
- Lost if you move, take damage, or change targets

**Point-Blank Range:**
- Shooting within 2m with ranged weapon: **-2 to hit**
- Weapon too long/awkward at close range

---

## 9. CALLED SHOTS

Targeting specific body parts for extra effect:

| Target | Penalty | Effect |
|--------|---------|--------|
| **Arm/Leg** | -4 | May disarm, slow movement, specific injury |
| **Hand/Foot** | -6 | Disable limb completely |
| **Head** | -6 | **Damage × 2** after armor |
| **Eye/Vitals** | -8 | **Damage × 2** after armor, may blind/kill |

### Damage Doubling
- Applied **AFTER** armor reduction
- **Stacks with impaling:** Head shot with arrow = × 4 total (× 2 impaling, × 2 head)

**Example - Head Shot with Arrow:**
- Arrow (1d6+2) + ST +1 = 8 total
- vs AR 2: 8 - 2 = 6 penetrates
- Impaling: 6 × 2 = 12
- Head shot: 12 × 2 = **24 Vitality damage** (likely instant death!)

**Tactical Use:**
- High-risk, high-reward
- Best for skilled attackers vs vulnerable targets
- Devastating with impaling weapons
- GM may add effects: disarm on arm shot, slow on leg shot, stun on head shot

---

## 10. PAIN, SHOCK & STATUS CONDITIONS

### Pain Penalty Rule

**For every 5 Vitality damage taken in one turn:**
- Suffer **-1 to all rolls on next turn**
- Stacks: 10 damage = -2, 15 damage = -3, etc.

**EXCEPTION:** If already in **active combat**, adrenaline negates penalty

**Active Combat Definition:**
- Character acted in combat in last 2 rounds, OR
- Character aware of immediate danger and prepared to fight

**Examples:**
- Ambushed for 7 damage (not in combat): -1 next turn
- Take 13 damage while fighting: No penalty (adrenaline)
- Take 12 damage exploring dungeon: -2 next turn

### Vitality Thresholds

(IMPORTANT) - penalties here apply only if started combat that way, changes during combat are not applied due to adrenaline effects.

| Vitality Level | Condition | Effects |
|----------------|-----------|---------|
| **Full to 50%** | Healthy | Minor ongoing penalty if below 50% (-1 to physical) |
| **Below 50%** | Wounded | -1 to all physical actions |
| **Below 25%** | Badly Wounded | -2 to all physical actions, visible impairment |
| **Below 10%** | Critical | -4 to all actions, half movement |
| **0 Vitality** | Unconscious | Can't act, dying (-1 Vitality/turn) |
| **-EN Vitality** | Death | Dead (unless Hard to Kill perk) |
| **-2×EN Vitality** | Destroyed | Body destroyed, beyond resurrection |

### Key Status Conditions

| Condition | Effects | Duration | Treatment |
|-----------|---------|----------|-----------|
| **Bleeding** | -1 Vitality/turn | Until bandaged | First Aid (Minor Action) |
| **Stunned** | -4 to all actions, lose Reaction | 1 round | Wait it out |
| **Prone** | -4 to attacks, +4 to be hit (melee), -4 to be hit (ranged) | Until stand | Half move to stand up |
| **Disarmed** | No weapon | Until retrieved | Minor Action (3m away) |
| **Grappled** | Can't move, -4 to all actions | Until escape | Opposed ST roll |
| **Dazed** | -2 to all actions, lose Minor Action | 1 round | Wait it out |
| **Exhausted** (0 Stamina) | -4 to all physical actions | Until rest | 1 hour rest |
| **Depleted** (0 Mana) | -4 to all mental actions | Until rest | 1 hour rest |
| **Dying** (≤0 Vitality) | Unconscious, -1 Vitality/turn | Until stabilized | First Aid or healing |

### Bleeding Management
**Critical for cutting weapons!**

1. **Inflicted:** When cutting damage penetrates armor
2. **Effect:** -1 Vitality per turn (ongoing)
3. **Treatment:** First Aid roll as Minor Action
   - Roll vs (IN + Medicine/First Aid) or default (IN-2)
   - Success: Bleeding stops
   - Failure: Continues for 1d6 more turns, can retry
4. **Multiple Wounds:** Track separately (can bleed from 3 cuts = -3/turn)

---

## 11. TWO-WEAPON FIGHTING & OFF-HAND

### Off-Hand Penalty
**-4 to hit** with non-dominant hand

### Two-Weapon Fighting
Attack with both weapons as **single Major Action:**
- **Main hand:** -2 to hit
- **Off-hand:** -6 to hit (includes off-hand penalty)
- Both roll separately
- Defender gets separate defense vs each

### Ambidextrous Perk (10 CP)
**Removes ALL off-hand penalties:**
- Off-hand attacks: no penalty
- Two-weapon fighting: Both at -2 (no additional off-hand penalty)

**Example:**
- **Without Ambidextrous:** Rogue with DX 13 + Daggers 4
  - Main hand: 13 + 4 - 2 = 15
  - Off-hand: 13 + 4 - 6 = 11
- **With Ambidextrous:**
  - Both hands: 13 + 4 - 2 = 15

---

## 12. MOVEMENT IN COMBAT

Based on Speed value:

| Movement Type | Distance | Cost |
|---------------|----------|------|
| **Half Move** | Speed meters | Can combine with Major Action |
| **Full Move** | Speed × 2 meters | Uses Major Action |
| **Sprint** | Speed × 4 meters | Major Action + 1 Stamina/turn |

**Difficult Terrain:** Costs double movement (half speed)

**Examples:**
- Speed 5 character: 5m half move, 10m full move, 20m sprint
- Speed 6.5 character: 6.5m half, 13m full, 26m sprint

---

## 13. MORALE & PANIC CHECKS

### When to Trigger Morale Checks

Characters roll vs **WS** when facing:
- First time seeing horrific violence/gore
- Facing supernatural creatures (demons, undead, eldritch horrors)
- Witnessing ally's death
- Outnumbered 3-to-1 or more
- Taking massive damage (half Vitality or more in one hit)
- Supernatural fear effects

### Modifiers

| Situation | Modifier |
|-----------|----------|
| Familiar with this threat | +2 |
| Veteran combatant / Strong Willed perk | +2 |
| Inexperienced / first adventure | -2 |
| Panicked ally nearby | -2 |
| Clear escape route | +2 |
| Surrounded / no escape | -4 |

### Results

| Result | Effect |
|--------|--------|
| **Success by 5+** | Steeled, +2 vs panic rest of encounter |
| **Success** | Hold steady, fight normally |
| **Failure** | Shaken, -2 to all actions for 1d6 rounds |
| **Failure by 5+** | Panic! Flee or cower for 1d6 rounds, can't attack |
| **Critical Failure (666)** | Total panic, flee screaming, drop weapons |

**GM Note:** Use sparingly for dramatic effect. Don't overuse on veterans.

---

## 14. COMBAT MANEUVERS

### Common Maneuvers (From Powers Library)

**Minor Maneuvers (1-3 CP, 0-1 Stamina):**
- **Shield Bash (1 CP, 1 Stamina):** Stun enemy (EN save or lose action)
- **Disarm (1 CP, 0 Stamina):** Opposed roll, win by 5+ to disarm
- **Trip (1 CP, 0 Stamina):** Knock prone (DX save)
- **Feint (1 CP, 0 Stamina):** +4 to next attack if win vs Perception
- **Quick Draw (1 CP, 0 Stamina):** Draw weapon as free action
- **Aimed Shot (3 CP, 0 Stamina):** +4 to ranged after aiming action

**Moderate Maneuvers (5-10 CP, 2 Stamina):**
- **Power Attack (8 CP, 2 Stamina):** +2d6 damage, -2 to hit
- **Precision Strike (7 CP, 2 Stamina):** Ignore 2 AR, defender -2
- **Sneak Attack (8 CP, 1 Stamina):** +2d6 vs unaware/flanked (once per target)
- **Rapid Strike (6 CP, 3 Stamina):** Two attacks at -4 each

**See Simverse_Powers_Library.md for complete list!**

---

## 15. SPECIAL SITUATIONS

### Unarmed Combat
- **Punch:** 1d6-3 + ST bonus (bludgeoning)
- **Kick:** 1d6 + ST bonus (bludgeoning)
- **Skill:** Brawling (DX-based)
- **Martial Arts perk:** +2 damage, attack as Minor Action, +2 defense unarmored

### Heavy Weapon Requirements

| Weapon Type | Min ST | Examples |
|-------------|--------|----------|
| Heavy 2H Swords | ST 12 | Greatsword, Zweihander |
| Heavy Axes | ST 12 | Greataxe |
| Heavy Hammers | ST 12 | Maul |
| Heavy Polearms | ST 11 | Halberd, Pike |
| Longbow | ST 10 | Longbow |

**Inadequate ST Penalty:**
- -4 to all attacks
- Half damage
- Can't use special maneuvers

### Grappling
- **Initiate:** Roll Brawling vs target's Brawling or DX
- **Effect:** Both grappler and target -4 to all actions, can't move
- **Escape:** Opposed ST or DX roll on your turn
- **Pin:** After grappling for 1 round, can attempt pin (opponent -6 to escape)

### Mounted Combat
- **Charge:** +2 to attack, +ST damage from mount's speed
- **Mount acts on your initiative**
- **Mounted Archery:** -4 to ranged attacks while moving
- **Unseated:** Roll vs DX or fall prone, take 1d6 damage

---

## 16. KNOCKBACK

**Rule:** Every 10 points of damage dealt (before AR), causes **1m knockback**

**Examples:**
- 15 damage hit: 1m knockback (even if AR reduces to 5 actual damage)
- 32 damage from giant: 3m knockback
- Force spell 18 damage: 1m knockback (GM may increase for force)

**Effects:**
- May push into hazards
- May push off ledges
- May interrupt actions
- May force out of melee range

---

## 17. QUICK REFERENCE TABLES

### Critical Results
- **Three 1s (111):** Critical success, +10 margin, exceptional result + bonus
- **Three 6s (666):** Critical failure, -10 margin, worst outcome + complication

### Attack Resolution Flowchart
```
1. Attacker rolls weapon skill (DX + Skill + mods)
2. Calculate margin (Target - Roll)
3. Each 5 margin = -1 to defender
4. Defender chooses defense (Dodge/Parry/Block)
5. Defender rolls defense - margin penalty
6. If defender fails:
   → Roll weapon damage + ST bonus
   → Apply damage type effects (cutting × AR, impaling × 2 penetration)
   → Subtract AR
   → Apply to Vitality
   → Apply status effects (bleeding, etc.)
```

### ST Damage Bonus Quick Table
| ST | Bonus | ST | Bonus | ST | Bonus |
|----|-------|----|-------|----|-------|
| 6-7 | -2 | 12-13 | +1 | 18-19 | +4 |
| 8-9 | -1 | 14-15 | +2 | 20-21 | +5 |
| 10-11 | +0 | 16-17 | +3 | 22-23 | +6 |

### Weapon Selection vs Armor

| Enemy Armor | Best Weapon Type | Reason |
|-------------|------------------|--------|
| **Unarmored (AR 0-1)** | Cutting | Bleeding effect devastating |
| **Light Armor (AR 2-3)** | Cutting or Impaling | Both effective, cutting causes bleeding |
| **Medium Armor (AR 4-5)** | Impaling or Bludgeoning | Penetration or bypass doubled AR |
| **Heavy Armor (AR 6+)** | Bludgeoning or Impaling | Best AR penetration |

### Defense Selection Guide

| Your Situation | Choose | Why |
|----------------|--------|-----|
| Have shield, frontal attack | Block | Highest value |
| High weapon skill, didn't attack | Parry | High value from skill |
| Already attacked this turn | Dodge or Block | Parry takes -4 |
| Ranged attack | Dodge | Only option |
| Area effect | Dodge | Only option |
| Flanked/rear | Dodge | Block doesn't work |

---

## 18. AI COMBAT TIPS

### Running Exciting Combat

1. **Describe Cinematically:**
   - Not: "The goblin attacks and misses"
   - Better: "The goblin lunges with its rusty shortsword, but you sidestep and the blade clangs off the stone wall"

2. **Use Margin for Narration:**
   - High margin success: Describe masterful execution
   - Narrow success: Describe close call
   - Narrow failure: Describe near miss
   - Critical failure: Describe embarrassing fumble

3. **Track Status Effects:**
   - Bleeding: Remind players each turn
   - Prone: Apply modifiers correctly
   - Stunned: Don't forget they lose reactions
   - Pain penalties: Track who took damage outside combat

4. **Tactical Variety:**
   - Enemies use terrain (cover, high ground)
   - Enemies flank when possible
   - Smart enemies target vulnerable characters (spellcasters)
   - Use morale for dramatic retreats

5. **Pacing:**
   - Minor fights: 2-4 rounds
   - Major fights: 5-10 rounds
   - Boss fights: 10+ rounds with phases
   - Don't let combat drag; push narrative forward

### Common Mistakes to Avoid

❌ **Forgetting margin penalty to defender**
✅ Always calculate margin and apply to defense

❌ **Forgetting parry penalty after attacking**
✅ Track who attacked with what weapon

❌ **Applying cutting damage wrong**
✅ Remember AR × 2 for cutting, then check bleeding

❌ **Forgetting impaling doubling**
✅ Dedicated impaling: penetration × 2. Thrust: subtract dice first, then × 2

❌ **Forgetting pain penalties**
✅ Track damage taken outside active combat

❌ **Not using terrain/tactics**
✅ Make combat dynamic with environment

❌ **Forgetting called shot is × 2 AFTER armor**
✅ Subtract AR first, THEN double

---

## 19. EXAMPLE FULL COMBAT ROUND

**Setup:**
- **Lyra** (Elf Scout): Speed 5.5, DX 13, Bow 4, AR 2, Vitality 18
- **Marcus** (Human Warrior): Speed 5, DX 14, Swords 5, Shield 3, AR 4, SD 2, Vitality 22
- **Two Goblins:** Speed 4, DX 11, Swords 2, AR 2, Vitality 10 each

**Initiative Order:** Lyra (5.5) → Marcus (5) → Goblins (4)

---

**ROUND 1:**

**Lyra's Turn (Speed 5.5):**
- **Major Action:** Shoot Goblin 1 with longbow
- **Attack Roll:** 3d6 ≤ 17 (DX 13 + Bow 4), rolls **10** → Success!
- **Margin:** 17 - 10 = **7**
- **Goblin Defense:** Dodge 11/2 = 5.5 → 5, minus 1 (margin ÷ 5) = **4 target**
- **Goblin Dodge:** 3d6 ≤ 4, rolls **8** → FAILURE
- **Damage:** Longbow 2d6 + ST 9 (-1) = rolls 7, total **6 damage**
- **After AR:** 6 - 2 = 4, but impaling! 4 penetrated × 2 = **8 Vitality damage**
- **Goblin 1:** 10 → 2 Vitality remaining

**Marcus's Turn (Speed 5):**
- **Major Action:** Attack Goblin 2 with longsword
- **Minor Action:** Move 5m to flank
- **Attack Roll:** 3d6 ≤ 21 (DX 14 + Swords 5 + Flanking +2), rolls **13** → Success!
- **Margin:** 21 - 13 = **8**
- **Goblin Defense:** Dodge 5, minus 1 (margin) = **4 target**
- **Goblin Dodge:** 3d6 ≤ 4, rolls **11** → FAILURE
- **Damage:** Longsword 2d6-1 cutting + ST 13 (+1) = rolls 8, total **8 damage**
- **After AR:** AR 2 × 2 (cutting) = 4, so 8 - 4 = **4 Vitality damage + bleeding**
- **Goblin 2:** 10 → 6 Vitality, **bleeding**

**Goblin 1's Turn (Speed 4):**
- **Status:** 2 Vitality, badly wounded
- **Morale Check:** Roll vs WS 10, rolls 14 → FAILURE → Shaken (-2 all actions)
- **Action:** Flees! Full movement away (8m)

**Goblin 2's Turn (Speed 4):**
- **Status:** 6 Vitality, bleeding (-1 next turn)
- **Major Action:** Attack Marcus with shortsword
- **Attack Roll:** 3d6 ≤ 13 (DX 11 + Swords 2), rolls **11** → Success!
- **Margin:** 13 - 11 = **2** (no penalty to Marcus)
- **Marcus Defense:** Block (DX 14 + Shield 3)/2 + SD 2 = 10 + 2 = **12**
- **Marcus Block:** 3d6 ≤ 12, rolls **9** → SUCCESS! Attack blocked!

**End of Round Effects:**
- Goblin 2 takes 1 Vitality from bleeding: 6 → 5 Vitality

---

**ROUND 2:**

**Lyra's Turn:**
- **Major Action:** Shoot fleeing Goblin 1
- **Attack Roll:** 3d6 ≤ 17, rolls **8** → Success! Margin 9
- **Goblin Dodge:** 4 - 1 = 3, rolls **15** → FAILURE
- **Damage:** 2d6 impaling -1 ST = rolls 5, **4 damage**
- Penetrates AR 2 → 2 × 2 = **4 damage**
- **Goblin 1:** 2 → -2 Vitality → **DEAD**

**Marcus's Turn:**
- **Major Action:** Attack Goblin 2 (Power Attack maneuver for +2d6)
- **Cost:** 2 Stamina
- **Attack Roll:** 3d6 ≤ 17 (DX 14 + Swords 5 - 2 from Power Attack), rolls **12** → Success!
- **Margin:** 17 - 12 = **5**
- **Goblin Dodge:** 5 - 1 = 4, rolls **9** → FAILURE
- **Damage:** 2d6-1 + 2d6 (Power Attack) + ST +1 = rolls 16 total!
- **After AR:** 16 - 4 (cutting AR × 2) = **12 Vitality damage** + more bleeding
- **Goblin 2:** 5 → -7 Vitality → **DEAD**

**Combat Ends!**

---

## 20. FINAL REMINDERS FOR AI COMBAT AGENTS

### ALWAYS DO:
1. ✅ Calculate margin and apply penalty to defender
2. ✅ Apply damage type effects correctly (cutting AR × 2, impaling penetration × 2)
3. ✅ Track bleeding and ongoing effects
4. ✅ Apply pain penalties for damage taken outside active combat
5. ✅ Use tactical terrain and enemy intelligence
6. ✅ Describe combat cinematically
7. ✅ Track status conditions (prone, stunned, bleeding, etc.)
8. ✅ Apply parry penalty (-4) if character attacked with that weapon

### NEVER DO:
1. ❌ Forget to subtract AR from damage
2. ❌ Apply impaling or cutting bonuses incorrectly
3. ❌ Forget that Block only works frontally
4. ❌ Forget range penalties for ranged weapons
5. ❌ Let combat become boring slog
6. ❌ Ignore morale for intelligent enemies
7. ❌ Forget minimum damage rule (1 if pre-AR > 0)
8. ❌ Apply called shot multiplier before AR subtraction

---

## REFERENCE FILES

For complete rules, see:
- **Simverse_Core_Rules.md** - Complete rulebook with combat section
- **Simverse_Advanced_Combat.md** - Detailed damage types, heavy weapons, pain rules
- **Simverse_Powers_Library.md** - 100+ combat maneuvers and spells
- **Simverse_Equipment_List.md** - Complete weapons and armor stats
- **Simverse_Combat_Simulations.md** - Example combats and tactics

---

**END OF COMBAT GUIDE**

**Remember:** The goal is exciting, tactical, narratively satisfying combat. When in doubt, favor drama and fun over perfect mechanical accuracy!

*Simverse RPG Combat AI Guide v1.0*
*Roll 3d6, keep it under target, tell amazing stories*