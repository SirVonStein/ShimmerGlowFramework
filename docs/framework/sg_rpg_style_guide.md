# SG_RPG_Style_Guide.md

---

**Document Version:** 1.0  
**Last Updated:** 2025-06-06  
**Author:** ShimmerGlow AI, Inc.  
**Document Type:** Language & Terminology Framework  
**Status:** Active

---

## Table of Contents

1. [Overview](#overview)
2. [Implementation](#implementation)
   - [Core Terminology Database](#core-terminology-database)
   - [Language Pattern Rules](#language-pattern-rules)
   - [Anti-Pattern Dictionary](#anti-pattern-dictionary)
   - [UI/UX Text Templates](#uiux-text-templates)
3. [Special Emphasis](#special-emphasis)
   - [How It Surpasses Wellness App Language](#how-it-surpasses-wellness-app-language)
   - [Agency Through Language](#agency-through-language)
   - [Recursive Language Evolution](#recursive-language-evolution)
4. [UI/UX Recommendations](#uiux-recommendations)
   - [Visual Language Hierarchy](#visual-language-hierarchy)
   - [Onboarding Language Journey](#onboarding-language-journey)
   - [Error Messages as RPG Events](#error-messages-as-rpg-events)
5. [Cross-References](#cross-references)
6. [Implementation Notes](#implementation-notes)
7. [Summary](#summary)

---

## Overview

The comprehensive terminology guide and language framework that transforms ShimmerGlow from a wellness app into a sacred Fulfillment RPG. This module standardizes all terminology, metaphors, and narrative patterns to ensure consistent implementation of the "player as protagonist" paradigm across every interface, interaction, and communication. Rooted in FRSM/AQI principles, it establishes the linguistic architecture that makes users feel like heroes in their own mythic adventure rather than patients in digital therapy.

---

## Implementation

### Core Terminology Database

**Player Identity Terms** - Transforming users into heroes:
```python
PLAYER_TERMINOLOGY = {
    # Identity References
    "user": ["Player", "Protagonist", "Author", "Hero", "Weaver"],
    "profile": ["Author Sheet", "Player Card", "Hero's Codex"],
    "account": ["Adventurer License", "Player Ledger"],
    "settings": ["Character Preferences", "Play Style Config"],
    
    # Character Development
    "personality_type": ["Character Class", "Archetype", "Player Build"],
    "traits": ["Attributes", "Character Stats", "Core Powers"],
    "preferences": ["Play Style", "Adventure Settings"],
    "history": ["Quest Log", "Adventure Chronicle", "Epic Timeline"]
}
```

**Adventure & Progression Terms** - Gamifying growth:
```python
ADVENTURE_TERMINOLOGY = {
    # Experience & Growth
    "points": "Ux (Units of Experience)",
    "level": "Journey Phase",
    "progress": "Adventure Advancement",
    "achievement": "Quest Completion",
    "milestone": "Legendary Deed",
    
    # Journey Phases
    "phases": [
        "🌱 ThreadBorn - Beginning the adventure",
        "🛡️ EchoBorn - Discovering your path", 
        "🔮 Weaver - Creating connections",
        "✨ StarGuide - Contributing wisdom",
        "🌟 ThreadWeaver - Mastering your realm",
        "🌌 Living Glyph - Living legend"
    ]
}
```

**Challenge & Transformation Terms** - Reframing difficulties as adventures:
```python
CHALLENGE_TERMINOLOGY = {
    # Difficulties & Growth
    "problems": ["Quests", "Adventures", "Challenges"],
    "crisis": ["Boss Fight", "Epic Encounter", "Trial by Fire"],
    "setback": ["Plot Twist", "Character Test", "XP Opportunity"],
    "trauma": ["Ancient Boss", "Shadow Dragon", "Core Quest"],
    
    # Emotional States
    "depression": ["The Void Dungeon", "Shadow Realm Journey"],
    "anxiety": ["Storm Debuff", "Chaos Winds Navigation"],
    "exhaustion": ["Mana Depletion", "Energy Quest"],
    "breakdown": ["System Reboot", "Phoenix Moment"],
    "recovery": ["Respawn Sequence", "Hero's Return"]
}
```

### Language Pattern Rules

**Active Voice Requirements** - Empowering player agency:
```python
ACTIVE_VOICE_TRANSFORMATIONS = {
    "You have earned": "You gain",
    "Points were added": "XP flows to you",
    "Progress has been made": "You advance",
    "It is recommended": "Consider this quest",
    "You should": "You might",
    "You need to": "Ready to",
    "You can": "You may",
    "Try to": "Quest to"
}
```

**Mythic Vocabulary Elevations** - Sacred language patterns:
```python
MYTHIC_VOCABULARY = {
    # Sacred Actions
    "use": ["invoke", "channel", "wield", "summon"],
    "start": ["embark", "initiate", "begin quest"],
    "complete": ["conquer", "master", "achieve victory"],
    "create": ["forge", "manifest", "conjure"],
    "change": ["transmute", "evolve", "transform"],
    "practice": ["ritual", "ceremony", "sacred work"],
    
    # Sacred Objects
    "tool": ["artifact", "relic", "power"],
    "feature": ["ability", "spell", "enchantment"],
    "button": ["portal", "gateway", "activation rune"],
    "screen": ["realm", "chamber", "sanctum"],
    "app": ["digital realm", "sacred technology"]
}
```

**Narrative Voice Guidelines** - Consistent heroic perspective:
- **Second-Person Heroic**: Always address as "you" (the hero)
- **Present Tense Active**: Creates immediate engagement and ongoing adventure
- **Choice-Centered Language**: Frame actions as opportunities, not obligations
- **Mythic but Accessible**: Balance sacred language with clarity and fun

### Anti-Pattern Dictionary

**Forbidden Clinical Terms** - Never pathologize the player:
```python
FORBIDDEN_CLINICAL = {
    "patient": "NEVER USE - Say 'Player' or 'Hero'",
    "treatment": "NEVER USE - Say 'Quest' or 'Adventure'",
    "therapy": "NEVER USE - Say 'Practice' or 'Ritual'",
    "symptom": "NEVER USE - Say 'Signal' or 'Quest Marker'",
    "disorder": "NEVER USE - Say 'Pattern' or 'Challenge'",
    "diagnosis": "NEVER USE - Say 'Character Analysis'",
    "recovery": "USE CAREFULLY - Prefer 'Hero's Return'"
}
```

**Victim Language Transformations** - Empowering alternatives:
```python
VICTIM_TO_HERO_LANGUAGE = {
    "suffer from": "Navigate", "Face", "Quest through",
    "cope with": "Master", "Transform", "Transmute",
    "deal with": "Engage", "Conquer", "Channel",
    "struggle with": "Adventure through", "Train against",
    "get through": "Conquer", "Complete quest",
    "manage": "Command", "Wield", "Direct"
}
```

**Wellness App Clichés to Avoid** - Overused therapeutic language:
```python
WELLNESS_CLICHE_REPLACEMENTS = {
    "self-care": "Power Restoration", "Energy Renewal",
    "mindfulness": "Presence Magic", "Awareness Spell",
    "gratitude practice": "Appreciation Ritual", "Blessing Count",
    "mood tracking": "Emotional Compass Reading", "Inner Weather Check",
    "mental health": "Consciousness Vitality", "Inner Realm Health",
    "work on yourself": "Level up your Character", "Forge your Legend",
    "healing journey": "Epic Quest", "Transformation Adventure"
}
```

### UI/UX Text Templates

**Button Label Library** - Consistent interactive language:
```python
BUTTON_LABELS = {
    # Primary Actions
    "start": "Begin Quest",
    "continue": "Resume Adventure", 
    "submit": "Cast Spell",
    "save": "Chronicle Entry",
    "cancel": "Portal Back",
    "delete": "Banish to Void",
    
    # Navigation
    "home": "Hero's Sanctum",
    "profile": "Character Sheet", 
    "settings": "Forge Settings",
    "help": "Sage Wisdom",
    "logout": "Rest at Inn",
    "back": "Return Portal"
}
```

**Notification Templates** - Celebration and guidance:
```python
NOTIFICATION_TEMPLATES = {
    "achievement": "⚔️ Quest Complete! {achievement_name} conquered!",
    "level_up": "🎯 Journey Phase Unlocked: {phase_name}!",
    "new_ability": "✨ New Spell Learned: {ability_name}",
    "companion": "🐲 Your {echomon_name} seeks adventure!",
    "rest": "🌙 Rest complete. +{stars} Stars gained!",
    "collapse": "🔥 Boss fight detected. Engaging support systems...",
    "recovery": "🌅 Phoenix moment! Your resilience grows stronger."
}
```

**Loading and Status Messages** - Maintaining immersion:
```python
STATUS_MESSAGES = {
    "loading": [
        "Weaving threads of possibility...",
        "Consulting the digital oracle...", 
        "Charging magical energies...",
        "Opening portal to your realm..."
    ],
    "saving": [
        "Chronicling your epic deeds...",
        "Crystallizing wisdom into memory...",
        "Preserving your legend..."
    ],
    "error": [
        "Spell misfired! Attempting recast...",
        "Portal disrupted! Seeking alternate route...",
        "Magic feedback detected. Stabilizing..."
    ]
}
```

---

## Special Emphasis

### How It Surpasses Wellness App Language

1. **Hero vs Patient** - Users are protagonists with agency, not people needing fixing
2. **Quest vs Treatment** - Challenges are adventures to embrace, not problems to solve
3. **XP vs Progress** - Growth is gamified achievement, not clinical improvement
4. **Spells vs Tools** - Practices are magical abilities, not coping mechanisms
5. **Epic vs Journey** - Life is mythic adventure, not therapeutic process

### Agency Through Language

**Sovereignty Reinforcement** - Every phrase empowers player choice:
- Choices presented as opportunities: "Ready to explore?" vs "You should try"
- Failures reframed as learning: "Plot twist unlocked!" vs "Error occurred"
- Rest positioned as strategic: "Tactical recovery" vs "Taking a break"
- Boundaries celebrated as power: "Sovereignty spell activated!" vs "Setting limits"

**Choice Architecture in Language** - Words that invite rather than demand:
- "Consider this quest" instead of "You should do this"
- "Your adventure awaits" instead of "Complete this task"
- "Power available when ready" instead of "Feature unlocked"
- "Portal open if desired" instead of "Click here to continue"

### Recursive Language Evolution

**Progressive Mythic Depth** - Language grows with player mastery:
- **ThreadBorn**: Simple, clear RPG language
- **EchoBorn**: Introduction of mystical terminology
- **Weaver**: Complex magical concepts and rituals
- **StarGuide**: Sacred geometry and consciousness language
- **ThreadWeaver**: Master-level mythic communication
- **Living Glyph**: Transcendent, poetic expression

**Community Language Creation** - Players contribute to the lexicon:
- Seasonal terminology contests
- Player-submitted spell names
- Community-created achievement titles
- Regional mythic language variations

---

## UI/UX Recommendations

### Visual Language Hierarchy

**Primary Terms** - Always visible core language:
- Player name displayed as "Hero [Name]" or "[Name] the [Archetype]"
- Ux counter shown as "Life Force" with energy bar visualization
- Stars currency with glowing, floating visual effects
- Journey Phase displayed as title/badge with appropriate iconography

**Contextual Terms** - Situation-specific language:
- "Boss Fight Mode" during emotional challenges
- "Sanctuary" in rest and recovery spaces
- "Spell Crafting" in ritual creation interfaces
- "Party Forming" in social and community features

**Easter Egg Terms** - Delight and surprise moments:
- "Critical Hit!" for major breakthroughs and insights
- "Legendary!" for rare achievements and milestones
- "Epic Loot!" for valuable rewards and discoveries
- "Secret Unlocked!" for hidden features and abilities

### Onboarding Language Journey

**Progressive Introduction** - Building the mythic world:
1. **First Contact**: "Welcome, Hero. Your adventure begins..."
2. **Character Creation**: "Choose your starting thread and archetype..."
3. **First Quest**: "Your inaugural quest awaits in the StarLog..."
4. **Tutorial Completion**: "Tutorial conquered! Your real adventure begins..."
5. **First Return**: "Welcome back, Hero! Your realm has missed you..."

**Language Teaching Moments** - Explaining RPG terms naturally:
- Hover tooltips: "Ux = Experience Points for living authentically"
- First-time explanations: "Boss Fights are what we call life's big challenges"
- Progressive revelation: Introduce one new term per session maximum

### Error Messages as RPG Events

**Technical Issues as In-World Events** - Maintaining immersion during problems:
- **Connection Lost**: "Portal disrupted! Seeking alternate dimensional route..."
- **Invalid Input**: "Spell components incompatible! Try different incantation..."
- **Feature Locked**: "This realm requires Journey Phase: [Weaver] to access"
- **Maintenance Mode**: "The digital gods are upgrading the realm. Return soon!"
- **Server Error**: "Temporal anomaly detected. Reality stabilizing..."

---

## Cross-References

### Core Philosophy Documents
- [`SG_Gem_Extract.md`](./SG_Gem_Extract.md) - Foundational RPG transformation philosophy
- [`SG_Fulfillment_Philosophy.md`](./SG_Fulfillment_Philosophy.md) - Player-as-protagonist paradigm
- [`SG_Sacred_Technology.md`](./SG_Sacred_Technology.md) - Sacred language integration
- [`SG_User_Sovereignty_Framework.md`](./SG_User_Sovereignty_Framework.md) - Agency-centered language

### System Integration
- [`SG_Fulfillment_XP_System.md`](./SG_Fulfillment_XP_System.md) - Ux terminology and progression language
- [`SG_Visual_Language_Achievement_System.md`](./SG_Visual_Language_Achievement_System.md) - Visual RPG elements
- [`SG_Master_Glossary.md`](./SG_Master_Glossary.md) - Complete terminology database
- [`SG_Economy_Progression_System.md`](./SG_Economy_Progression_System.md) - Currency and progression terms

### Feature Implementation
- [`SG_EchoMon_Naming_Creation_System.md`](./SG_EchoMon_Naming_Creation_System.md) - Companion terminology
- [`SG_Ritual_Recovery_System.md`](./SG_Ritual_Recovery_System.md) - Spell and ritual language
- [`SG_Avatar_Evolution_System.md`](./SG_Avatar_Evolution_System.md) - Character visualization language
- [`SG_Social_Systems_Complete.md`](./SG_Social_Systems_Complete.md) - Party and guild terminology

### Writing Guidelines
- [`SG_Creative_Dopamine_Design_Guide.md`](./SG_Creative_Dopamine_Design_Guide.md) - Language constraints
- [`SG_Resonance_Onboarding_Translation.md`](./SG_Resonance_Onboarding_Translation.md) - First contact language
- [`SG_Narrative_Engine.md`](./SG_Narrative_Engine.md) - Story generation language

---

## Implementation Notes

### Critical Constraints

1. **Never Break Character** - Always maintain RPG metaphor consistency
2. **Consistency Above All** - Same term everywhere for same concept
3. **Fun First Priority** - If language isn't enjoyable to read, rewrite it
4. **Clarity Matters** - Mythic language must remain understandable
5. **Player Agency Always** - Language must continuously empower choice

### Localization Considerations

- **Cultural Adaptation**: RPG metaphors must translate appropriately across cultures
- **Regional Mythology**: Incorporate local heroic traditions where appropriate
- **Gaming Terminology**: Respect regional variations in gaming language
- **Sacred Language**: Handle mystical terms with cultural sensitivity
- **Accessibility**: Ensure metaphors work for diverse cognitive styles

### Testing Guidelines

**Language Effectiveness Metrics**:
```python
LANGUAGE_TESTING = {
    "engagement": "Does RPG language increase session enjoyment?",
    "retention": "Do players return more with heroic framing?",
    "agency": "Does mythic language increase sense of control?",
    "comprehension": "Are RPG terms clear to new players?",
    "immersion": "Does language maintain fantasy without breaking"
}
```

### Evolution Pathways

1. **Community Terminology** - Players submit and vote on new sacred terms
2. **Seasonal Language** - Special event vocabulary and limited-time expressions
3. **Mastery Unlocks** - Advanced mythic language available to experienced players
4. **Cultural Variants** - Region-specific mythology and heroic traditions
5. **AI Language Evolution** - EchoMons developing their own unique speech patterns

---

## Summary

The ShimmerGlow RPG Style Guide transforms every word, phrase, and interaction from clinical wellness language into heroic adventure terminology. By consistently positioning users as protagonists in their own mythic journey, celebrating challenges as boss fights, and framing growth as legendary achievement, it creates the linguistic foundation for the world's first true Fulfillment RPG. Every notification becomes a quest completion, every setback a plot twist, and every moment of growth an epic victory. This is language as transformation technology—where words become spells that remind users of their own inherent heroism.

**Core Mantra:** *"In the realm of ShimmerGlow, every word is a spell cast in service of the player's sovereignty—transforming mundane moments into mythic memories."*

---

**Document Status:** Complete  
**Review Cycle:** Quarterly  
**Next Review:** 2025-06-30
