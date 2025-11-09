# SIMVERSE RPG - AI Agent Guides

This directory contains specialized guides designed to help AI agents run Simverse RPG games effectively.

---

## 📚 Available Guides

### 🎭 [roleplaying.md](roleplaying.md) - **MAIN GM AGENT** (38 KB)
**The primary game master agent** that runs adventures and manages narrative.

**Use this for:**
- Running game sessions (15-30 min story arcs)
- Narrating scenes and describing the world
- Calling for skill checks and setting difficulty
- Creating NPCs, items, and custom content on-the-fly
- Managing exploration, social encounters, and investigation
- Awarding CP rewards (1-5 per session)
- Delegating to specialized agents when needed

**Key features:**
- When to call for visible vs hidden rolls
- Session structure templates (hook → investigation → challenge → resolution → cliffhanger)
- Custom content creation (spells, powers, items, perks, flaws)
- All non-combat skills and their uses
- Environmental hazards and survival rules
- Narrative techniques and pacing
- Example complete session walkthrough
- Balancing challenges and rewards

---

### ⚔️ [combat.md](combat.md) - Combat Specialist Agent (30 KB)
**Handles all combat encounters in detail.**

**Use this for:**
- Running detailed tactical combat (3+ rounds)
- Resolving attacks, defense, and damage
- Tracking initiative, status effects, and ongoing conditions
- Managing complex fights with multiple combatants
- Teaching combat system to new players

**Key features:**
- Complete 7-step attack resolution
- All damage types (bludgeoning, cutting, impaling, energy)
- Defense options (Dodge/Parry/Block) with tactical guidance
- Called shots, two-weapon fighting, ranged combat
- Pain/shock penalties and status conditions
- Armor, shields, and equipment degradation
- Full combat round example
- Common mistakes and quick reference tables

**When to delegate:**
- Boss fights
- Complex tactical battles
- Teaching combat to players
- Tracking many combatants

---

### 👤 [character_creation.md](character_creation.md) - Character Builder Agent (19 KB)
**Assists with creating characters and detailed NPCs.**

**Use this for:**
- Helping players build PCs
- Creating detailed recurring NPCs
- Building boss enemies and antagonists
- Explaining character options and templates
- Verifying CP math and balance

**Key features:**
- Complete character creation steps
- Power level tables (100 CP = starting adventurer)
- All templates (Elf, Dwarf, Warrior, Wizard, Rogue, Scout, etc.)
- Attribute/skill cost tables
- Power construction system
- Equipment and starting gear
- Example characters with full builds
- Balance guidelines and CP verification

**When to delegate:**
- Player wants help building character
- Important recurring villain needs full statblock
- Creating party of detailed opponents

---

## 🎯 Agent Workflow

### Typical Session Flow

```
┌─────────────────────────────────────┐
│   ROLEPLAYING AGENT (Main GM)      │
│   - Narrates scene                  │
│   - Calls for skill checks          │
│   - Makes hidden rolls              │
│   - Manages story pacing            │
└───────────┬─────────────────────────┘
            │
            ├──→ Combat needed?
            │   ┌──────────────────────┐
            │   │  COMBAT AGENT        │
            │   │  Runs tactical fight │
            │   └──────────────────────┘
            │
            ├──→ Create NPC/enemy?
            │   ┌──────────────────────┐
            │   │  CHARACTER CREATION  │
            │   │  Builds detailed NPC │
            │   └──────────────────────┘
            │
            └──→ Quick resolution
                (Handle in-house)
```

### When to Use Which Agent

| Situation | Use This Agent | Keep In-House |
|-----------|----------------|---------------|
| **Character Creation** | Detailed PCs, important NPCs, bosses | Quick encounter enemies, shopkeepers |
| **Combat** | Boss fights, complex battles (3+ rounds) | Single attacks, abstract fights |
| **Narrative** | Always use roleplaying agent | N/A |

---

## 💡 Quick Start for AI Agents

### If you're running a game session:
1. **Start with** [roleplaying.md](roleplaying.md)
2. Reference combat.md when fights happen
3. Reference character_creation.md for detailed NPCs

### If you're helping create a character:
1. **Use** [character_creation.md](character_creation.md)
2. Reference roleplaying.md for context on power levels
3. Reference combat.md for combat mechanics questions

### If you're running a combat encounter:
1. **Use** [combat.md](combat.md)
2. Reference roleplaying.md for pacing/narrative
3. Reference character_creation.md if enemies need building

---

## 📖 Additional Resources

These guides reference the full rulebooks:
- **Simverse_Core_Rules.md** - Complete game system
- **Simverse_Powers_Library.md** - 100+ pre-built powers, spells, maneuvers
- **Simverse_Additional_Templates.md** - Extended races and professions
- **Simverse_Equipment_List.md** - Complete weapons, armor, gear, prices
- **Simverse_Advanced_Combat.md** - Deep dive into damage types and special rules

---

## 🎲 Design Philosophy

These guides follow the **Simverse** core philosophy:

**System:** Roll 3d6 ≤ (Attribute + Skill + modifiers) = Success

**Goals:**
- Make AI agents effective game masters
- Balance rules knowledge with narrative flexibility
- Enable dynamic, improvised content creation
- Support 15-30 minute sessions with meaningful progression
- Reward creativity and player agency
- Keep combat tactical but not bogged down
- Make failures interesting, not dead ends

**When in doubt:**
1. **Keep it moving** - Don't let mechanics slow the story
2. **Make it dramatic** - Favor exciting outcomes
3. **Let players be heroes** - Give them chances to shine
4. **Have fun** - Rules serve the story, not vice versa

---

## 📝 Version History

**v1.0** (2024-11-09)
- Initial release
- Three specialized agent guides
- Complete combat system
- Character creation guide
- Roleplaying/GM master guide

---

**Created for Simverse RPG**
*A flexible, tactical, point-buy RPG system*
*Roll-under 3d6 mechanics, scalable from street-level to cosmic campaigns*

© 2024 Julio Holon - CC BY-NC-SA 4.0
