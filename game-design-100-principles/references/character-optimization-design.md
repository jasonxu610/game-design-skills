---
name: character-optimization-design
description: Use when designing character creation systems, unit attributes, or stat-based progression. Applies when players can allocate points to customize characters/units, or when balancing RPG, wargame, or strategy game systems.
---

# Character Optimization and Mitigation Design

Design character creation and progression systems that balance player optimization strategies with game integrity and role-playing experience.

## When to Apply

- Designing character creation systems
- Creating stat/attribute systems
- Balancing RPG or strategy game units
- Addressing player power optimization behaviors
- Designing progression mechanics

## Min/Maxing Definition

Min/Maxing is a dominant strategy where players:
- Minimize unfavorable traits
- Maximize favorable traits
- Create specialized characters/units optimized for specific tasks

### Characteristics

- **High power** in specific skills or areas
- **Reduced overall flexibility** or versatility
- **Dominant strategies** that outperform balanced builds
- **Common in**: RPGs (combat stats over social/intellectual), Military games (glass cannon units)

## Player Perspectives

### Supporters Argue:
- Rules-compliant behavior
- Contributes to team efficiency (division of labor)
- Fits game spirit of optimization and mastery
- Satisfying to find optimal builds

### Critics Argue:
- Breaks social contract of role-playing
- Ignores character realism and narrative
- Ruins non-combat experiences
- Creates unbalanced multiplayer environments
- Reduces creative expression

## Designer Mitigation Strategies

### Preset Values

**Approach:**
- Set preset, balanced attribute values
- Limit player customization to presets

**Pros:**
- Guaranteed balance
- Easy to design and test

**Cons:**
- Reduces player agency
- Limits creative expression

### Random Generation

**Approach:**
- Randomly generate new attribute values for each new game
- Roguelike-style character creation

**Pros:**
- Encourages adaptability
- Prevents repetitive optimization
- Adds replay variety

**Cons:**
- Players may feel cheated by bad rolls
- May require re-rolling (wastes time)

### Interconnected Attributes

**Approach:**
- Link attributes into complex systems
- Raising one stat lowers another
- Shifts focus to system optimization

**Pros:**
- Maintains depth
- Requires strategic thinking
- Prevents single-stat dominance

**Cons:**
- More complex to understand
- Still vulnerable to system optimization

### Thematic Emphasis

**Approach:**
- Emphasize game theme and narrative
- Encourage role-playing over number-crunching
- Reward narrative choices with mechanical benefits

**Pros:**
- Maintains immersion
- Encourages desired playstyle
- Aligns mechanics with theme

**Cons:**
- May not stop pure optimizers
- Requires strong narrative

## Related Design Traps

**Powergaming:**
- Dominant players bullying others to achieve goals
- Using any means to "win" at social play

**Rule Lawyering:**
- Strict adherence to rules to optimize math
- Ignoring fun and spirit of the game
- Arguing technicalities for advantage

**Twinking:**
- Equipping low-level characters with high-level gear
- Creates absolute advantage over natural progression
- Breaks early-game balance

## Variables

- **trait_values**: The quantitative values of character attributes (strength, intelligence, etc.)
- **optimization_level**: Degree to which player is min/maxing
- **flexibility_factor**: How versatile the character/unit is
- **system_complexity**: How interconnected the stats are

## Constraints

- May violate social contracts in role-playing games
- Reduces character flexibility
- Controversial player behavior—satisfying for some, frustrating for others

## Design Workflow

1. **Define desired balance** between specialization and versatility
2. **Choose mitigation strategy** (or combination)
3. **Implement attribute system** with chosen constraints
4. **Test for dominant strategies** and exploits
5. **Iterate** based on playtesting feedback
6. **Monitor live game** for emerging optimization patterns

## Result Template

A character/unit system that accommodates player optimization while maintaining game balance and supporting the intended playstyle.