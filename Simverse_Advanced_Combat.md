# SIMVERSE: Advanced Combat Rules
## Complete Combat System Update

---

## TABLE OF CONTENTS
1. [Strength Damage Bonus](#strength-damage-bonus)
2. [Damage Types](#damage-types)
3. [Unarmed Combat](#unarmed-combat)
4. [Heavy Weapon Requirements](#heavy-weapon-requirements)
5. [Pain and Shock](#pain-and-shock)
6. [Called Shots](#called-shots)
7. [Updated Weapon Table](#updated-weapon-table)

---

## STRENGTH DAMAGE BONUS

Strength directly affects melee and thrown weapon damage:

### Calculation
**Damage Bonus = (ST - 10) / 2** (round down)

| Strength | Damage Modifier |
|----------|----------------|
| 6-7 | -2 |
| 8-9 | -1 |
| 10-11 | +0 |
| 12-13 | +1 |
| 14-15 | +2 |
| 16-17 | +3 |
| 18-19 | +4 |
| 20-21 | +5 |

### Dice Conversion Rule
When damage modifier reaches **+7 or higher**, convert to extra damage dice:
- **1d6+7 → 3d6**
- **1d6+8 → 3d6+1**
- **2d6+7 → 4d6**
- Each +6 adds another 1d6

### Examples
- ST 12 character with dagger (1d6-3): **1d6-3+1 = 1d6-2** damage
- ST 18 character with longsword (2d6-1): **2d6-1+4 = 2d6+3** damage
- ST 24 character with club (1d6-2): 1d6-2+7 = 1d6+5 → converts to **3d6-2** damage

---

## DAMAGE TYPES

### Overview
Four main damage types affect armor and cause different effects:

| Type | AR Effect | Special |
|------|-----------|---------|
| **Bludgeoning** | Normal | Standard damage |
| **Cutting** | Double AR | Each penetrating hit adds 1 to bleeding_count |
| **Impaling** | Normal | Damage through armor doubled |
| **Energy** | Normal | Additional effects |

---

### BLUDGEONING DAMAGE
**Most common damage type**

**Sources:** Clubs, maces, hammers, fists, kicks, falls, most magical force

**Mechanics:**
- AR subtracts normally from damage
- Remaining damage goes to Vitality
- No special effects

**Example:**
- Warhammer (2d6 bludgeoning) + ST 14 (+2) = rolls 9
- 9 + 2 = 11 damage total
- vs AR 4: 11 - 4 = **7 Vitality damage**

---

### CUTTING DAMAGE
**Deadly against light armor, causes bleeding**

**Sources:** Swords, axes, slashing weapons

**Mechanics:**
1. **AR counts double** for cutting damage
2. Each time damage penetrates, **bleeding_count increases by 1**
3. **Bleeding Mechanics:**
   - Each turn: Lose bleeding_count Vitality
   - Each turn: Roll vs EN (penalty -2 × bleeding_count) to reduce bleeding_count by 1
   - When bleeding_count reaches 0: Bleeding stops
   - Treatment: First Aid as Major Action stops all bleeding immediately (bleeding_count = 0)

**Example:**
- Longsword (2d6-1 cutting) + ST 16 (+3) = rolls 8
- 8 - 1 + 3 = 10 damage total
- vs AR 3: AR counts as 6 vs cutting
- 10 - 6 = 4 damage to Vitality
- **Victim's bleeding_count increases by 1 (will lose 1 Vitality/turn, EN roll each turn to recover)**

**Tactical Note:** Cutting weapons are excellent vs unarmored or lightly armored foes, but struggle against heavy armor.

---

### IMPALING DAMAGE
**High penetration, deadly on hits**

**Sources:** Spears, arrows, daggers (thrust), piercing weapons

**Mechanics:**
1. Usually **smaller base damage**
2. AR subtracts normally
3. **Damage that penetrates AR is DOUBLED**

**Examples:**

**Example 1 - Arrow:**
- Arrow (1d6+2 impaling) + ST 12 (+1) = rolls 5
- 5 + 2 + 1 = 8 damage total
- vs AR 2: 8 - 2 = 6 gets through
- Impaling doubles: 6 × 2 = **12 Vitality damage**

**Example 2 - Spear Thrust:**
- Spear (1d6+1 impaling) + ST 14 (+2) = rolls 4
- 4 + 1 + 2 = 7 damage total
- vs AR 4: 7 - 4 = 3 gets through
- Impaling doubles: 3 × 2 = **6 Vitality damage**

**Tactical Note:** Impaling weapons excel at punching through armor with precision strikes.

---

### ENERGY/MAGICAL DAMAGE
**Varied effects beyond simple damage**

**Sources:** Fire spells, lightning bolts, acid, cold magic, force magic

**Mechanics:**
- Functions like **bludgeoning** (AR applies normally)
- Additional effects based on energy type

**Types:**
- **Fire:** May ignite flammable objects, ongoing burn (GM discretion: 1d6/turn for 1d6 turns)
- **Cold:** May slow target (-2 Speed for 1d6 turns, Dodge at -2)
- **Lightning:** May cause muscle spasms (roll vs ST or drop held items)
- **Acid:** May damage equipment, ongoing damage (1d6-2/turn for 1d6 turns)
- **Force:** Pure magical energy, no special effects

**Example:**
- Fireball (3d6 fire) vs AR 3: rolls 12
- 12 - 3 = 9 Vitality damage
- **Additional:** Target's clothing catches fire, 1d6 fire damage per turn until extinguished (Major Action to put out, or roll on ground)

---

## KNOCKBACK

Heavy impacts can push targets backward, even if armor absorbs the damage.

**Rule:** Every 10 points of damage received (not blocked, parried, or dodged), even if absorbed by armor, causes **1m knockback**.

**Examples:**
- Character takes 15 damage hit: 1m knockback (even if AR reduces it to 5 actual Vitality damage)
- Giant deals 32 damage with club: 3m knockback (victim may hit wall or fall)
- Force magic deals 18 damage: 1m knockback (Force energy has enhanced knockback - GM may increase)

**Tactical Implications:**
- Knockback can push enemies off ledges, into hazards, or away from allies
- Large creatures are harder to knock back (GM may increase threshold for huge/gigantic creatures)
- Can interrupt movement or force enemies out of melee range

---

## UNARMED COMBAT

### Basic Unarmed Attacks
Characters can fight without weapons using the Brawling skill:

| Attack | Damage | Type | Notes |
|--------|--------|------|-------|
| **Punch** | 1d6-3 + ST | Bludgeoning | Quick, can be used as Minor Action with perks |
| **Kick** | 1d6 + ST | Bludgeoning | More powerful, requires balance |

**Skill:** Both use Brawling (DX-based, Regular skill)

### Examples
- ST 10 character punches: 1d6-3+0, rolls 4 = **1 damage**
- ST 14 character punches: 1d6-3+2, rolls 5 = **4 damage**
- ST 18 character kicks: 1d6+4, rolls 4 = **8 damage**

### Martial Arts
Characters with Martial Arts perks or Monk training have enhanced unarmed damage and special techniques (see profession templates or future martial arts expansion).

**Example - Monk with Martial Arts perk:**
- Unarmed damage becomes 1d6+2 + ST bonus
- Can make unarmed attack as Minor Action
- +2 to defenses when unarmored

---

## HEAVY WEAPON REQUIREMENTS

Some weapons require minimum Strength to wield effectively:

### Weapon Requirements

| Weapon Type | Minimum ST | Examples |
|-------------|------------|----------|
| **Heavy Two-Handed Swords** | 12 | Greatsword, Zweihander |
| **Heavy Axes** | 12 | Greataxe, Heavy Battleaxe |
| **Heavy Hammers** | 12 | Maul, Heavy Warhammer |
| **Heavy Polearms** | 11 | Halberd, Pike, Poleaxe |
| **Longbow** | 10 | Longbow, Warbow |

### Inadequate Strength Penalty
Using weapon without meeting ST requirement:
- **-4 to all attack rolls**
- **Half damage** (after all calculations)
- May not use special maneuvers (GM discretion)

### Example
Character with ST 10 uses Greatsword (requires ST 12):
- Normal attack: DX 14 + Swords 4 = 18
- With penalty: 18 - 4 = **14 to hit**
- Greatsword damage: 3d6 cutting = rolls 12
- With inadequate ST: 12 ÷ 2 = **6 damage** (before AR)

**Note:** This represents combat effectiveness, not just ability to lift the weapon.

---

## PAIN AND SHOCK

Taking major damage causes shock that impairs performance:

### Pain Penalty Rule
**For every 5 Vitality damage taken in one turn:**
- Suffer **-1 to all rolls on next turn**
- Applies to all actions: attacks, skills, spells

**Exception:** If already in active combat, adrenaline negates penalty

### Active Combat Definition
Character is in "active combat" if:
- They have acted in combat in last 2 rounds, OR
- They are aware of immediate danger and prepared to fight

### Examples

**Example 1 - Ambushed:**
- Marcus takes 7 damage from surprise arrow (not in combat)
- 7 ÷ 5 = **-1 to all rolls next turn**

**Example 2 - Heavy Hit:**
- Thorin takes 13 damage from ogre club (already fighting)
- No penalty - combat adrenaline active

**Example 3 - Multiple Hits:**
- Lyralei takes 4 damage from arrow, then 6 from sword (10 total, not yet in active combat)
- 10 ÷ 5 = **-2 to all rolls next turn**

**Example 4 - Massive Damage:**
- Character takes 23 damage in one turn while exploring
- 23 ÷ 5 = **-4 to all rolls next turn**

### Tactical Implications
- First strike advantage is significant
- Ambushes are devastating
- Once combat starts, characters can take punishment without panic
- Encourages avoiding surprise

---

## CALLED SHOTS

Targeting specific body parts for extra effect:

### Called Shot Penalties & Effects

| Target | Penalty | Effect |
|--------|---------|--------|
| **Arm/Leg** | -4 to hit | May cause drop item, slow movement |
| **Hand/Foot** | -6 to hit | Disable limb function |
| **Head** | -6 to hit | **Damage doubled** after armor |
| **Eye/Vitals** | -8 to hit | **Damage doubled** after armor |

### Damage Doubling
- Applied **after** armor reduction
- **Stacks with impaling** for ×4 total damage
- GM may add additional effects (knockout, stunning, etc.)

### Examples

**Example 1 - Head Shot (Bludgeoning):**
- Mace (2d6 bludgeoning) + ST 14 (+2) = rolls 8
- 8 + 2 = 10 damage - AR 4 = 6 gets through
- Head shot doubles: 6 × 2 = **12 Vitality damage**

**Example 2 - Head Shot (Impaling):**
- Arrow (1d6+2 impaling) + ST 12 (+1) = rolls 5
- 5 + 2 + 1 = 8 - AR 2 = 6 gets through
- Impaling doubles: 6 × 2 = 12
- Head shot doubles: 12 × 2 = **24 Vitality damage**
- Likely instant death for most characters!

**Example 3 - Arm Shot:**
- Sword (2d6-1 cutting) hits arm at -4
- Damage: 9 total - AR 6 (double for cutting) = 3 damage + bleeding
- **Effect:** Target must roll vs ST or drop held item

### Tactical Use
- High-risk, high-reward option
- Best used by skilled attackers against vulnerable targets
- Snipers and assassins favor called shots
- Devastating when combined with impaling weapons

---

## UPDATED WEAPON REFERENCE TABLE

### Melee Weapons - Light (One-Handed)
| Weapon | Damage | Type | ST | Cost | Notes |
|--------|--------|------|----|----|-------|
| Dagger | 1d6-3 | Cut/Imp (-1 thrust) | - | 5 sp | Conceal, throw 10m |
| Shortsword | 1d6-1 | Cut/Imp (-1 thrust) | - | 20 sp | Versatile |
| Hand Axe | 1d6 | Cutting | - | 15 sp | Throw 8m |
| Mace | 1d6 | Bludgeoning | - | 15 sp | Good vs armor |
| Rapier | 1d6 | Impaling | - | 30 sp | +1 parry |
| Club | 1d6-2 | Bludgeoning | - | 2 sp | Improvised |

### Melee Weapons - Medium (One/Two-Handed)
| Weapon | Damage | Type | ST | Cost | Notes |
|--------|--------|------|----|----|-------|
| Longsword | 2d6-1 | Cut/Imp (-2 thrust) | - | 50 sp | Versatile |
| Battleaxe | 2d6 | Cutting | - | 40 sp | High damage |
| Warhammer | 2d6 | Bludgeoning | - | 45 sp | +2 vs AR 4+ |
| Spear | 1d6+1 | Impaling | - | 10 sp | Throw 15m, 2m reach |

### Melee Weapons - Heavy (Two-Handed)
| Weapon | Damage | Type | ST | Cost | Notes |
|--------|--------|------|----|----|-------|
| Greatsword | 3d6 | Cut/Imp (-3 thrust) | 12 | 100 sp | Massive damage |
| Greataxe | 3d6+1 | Cutting | 12 | 90 sp | Highest damage |
| Maul | 3d6 | Bludgeoning | 12 | 80 sp | +3 vs armor |
| Halberd | 2d6+2 | Cut/Imp (-2 thrust) | 11 | 65 sp | 3m reach |
| Pike | 2d6 | Impaling | 11 | 50 sp | 4m reach |

### Ranged Weapons
| Weapon | Damage | Type | ST | Max Range | Cost | Notes |
|--------|--------|------|----|----|------|-------|
| Shortbow | 1d6+1 | Impaling | - | 50m | 30 sp | Quick draw, penalties after 25m |
| Longbow | 2d6 | Impaling | 10 | 100m | 60 sp | Powerful, penalties after 50m |
| Lt Crossbow | 2d6 | Impaling | - | 80m | 50 sp | No ST req, penalties after 40m |
| Hv Crossbow | 2d6+2 | Impaling | - | 120m | 100 sp | Armor piercing, penalties after 60m |
| Javelin | 1d6+1 | Impaling | - | 20m | 8 sp | Cheap, penalties after 10m |
| Throwing Axe | 1d6 | Cutting | - | 8m | 15 sp | Good damage, penalties after 4m |

**Remember:**
- Add ST damage bonus to all melee and thrown weapons!
- Dual-mode weapons (swords, daggers): subtract 1 damage per die when thrusting
- Pure impaling weapons (spears, arrows, rapiers): no penalty
- Range penalties: -1 per 5m beyond half max range; half damage beyond max range

---

## DAMAGE CALCULATION FLOWCHART

```
1. Roll weapon base damage
2. Add ST damage bonus (if melee/thrown)
3. Subtract Armor Resistance:
   - Bludgeoning: AR applies normally
   - Cutting: AR × 2
   - Impaling: AR applies normally, then double penetrating damage
   - Energy: AR applies normally + special effects
4. Apply called shot multiplier (if applicable):
   - Head/Vitals: × 2
   - Stacks with impaling for × 4 total
5. Final damage to Vitality
6. Apply special effects:
   - Cutting: Bleeding (adds 1 to bleeding_count, -bleeding_count Vitality/turn)
   - Energy: Type-specific effects
7. Check pain penalty (if not in active combat):
   - Every 5 damage = -1 next turn
```

---

## TACTICAL IMPLICATIONS

### Weapon Selection
- **vs Unarmored:** Cutting weapons (cause bleeding)
- **vs Light Armor:** Cutting or impaling (both effective)
- **vs Heavy Armor:** Bludgeoning (bypass doubled AR) or impaling (penetration bonus)
- **vs Mixed Groups:** Versatile weapons or carry multiple types

### Combat Tactics
- **High ST characters:** Favor heavy weapons for maximum damage
- **Low ST characters:** Favor finesse weapons or bows (no ST requirement)
- **Assassins:** Impaling weapons + called shots = lethal
- **Tank characters:** Bludgeoning weapons + high armor
- **Ambush tactics:** Exploit pain penalty, target unaware enemies

### Defense Strategies
- **Heavy armor:** Excellent vs cutting, vulnerable to bludgeoning
- **Light armor + dodge:** Avoid hits entirely, don't rely on AR vs impaling
- **First strike:** Prevent pain penalties by staying in active combat
- **Bleeding management:** Keep First Aid skill trained, carry bandages

---

## QUICK REFERENCE

### ST Damage Bonus Quick Table
| ST | Bonus | ST | Bonus | ST | Bonus |
|----|-------|----|-------|----|-------|
| 6-7 | -2 | 12-13 | +1 | 18-19 | +4 |
| 8-9 | -1 | 14-15 | +2 | 20-21 | +5 |
| 10-11 | +0 | 16-17 | +3 | 22-23 | +6 |

### Damage Type Summary
- **Bludgeoning:** Normal AR, no special
- **Cutting:** AR × 2, each penetrating hit adds 1 to bleeding_count
- **Impaling:** Penetrating damage × 2
- **Energy:** Normal AR, special effects

### Pain Penalty
- 5+ damage (not in combat) = -1 next turn
- 10+ damage (not in combat) = -2 next turn
- 15+ damage (not in combat) = -3 next turn

### Called Shots
- Arm/Leg: -4 to hit
- Head/Vitals: -6/-8 to hit, **damage × 2**

---

**End of Advanced Combat Rules**