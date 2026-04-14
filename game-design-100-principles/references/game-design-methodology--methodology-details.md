# Detailed Design Methodology Reference

## Brainstorming: Advanced Techniques

### Combining Methods

For complex projects, combine multiple brainstorming methods:

1. **Start with Word Bubbles** for initial concept exploration
2. **Transition to Tree Diagrams** for feature organization
3. **Use Flowcharts** for mechanic flow
4. **Apply Bodystorming** for control scheme validation

### Group Brainstorming

When brainstorming with a team:
- Assign one person to record all ideas
- No criticism during idea generation phase
- Build on others' ideas explicitly
- Set time limits to maintain energy
- Review and categorize afterward

## Core Loop: Depth Analysis

### Loop Duration Considerations

| Duration | Type | Example |
|----------|------|----------|
| 1-5 seconds | Micro-loop | Shooting a gun, jumping |
| 5-30 seconds | Action loop | Combat encounter, puzzle |
| 30 seconds - 5 minutes | Session loop | Level completion, match |
| 5-30 minutes | Play session | Quest completion |
| Hours | Meta loop | Character progression, season |

### Loop Failure Modes

**Mode 1: No Depth**
- Loop is fun once but doesn't evolve
- Players master it quickly and get bored
- Solution: Add complexity layers, combine with other mechanics

**Mode 2: No Feedback**
- Player doesn't understand impact of actions
- Loop feels meaningless
- Solution: Add clear visual/audio feedback, progress indicators

**Mode 3: No Flexibility**
- Loop only works in one context
- Cannot extend to new scenarios
- Solution: Design modular actions that combine in multiple ways

**Mode 4: No Extension**
- Cannot add new actions to the loop
- Game cannot grow
- Solution: Design with hooks for future mechanics

### Small Games Application

Not all games need Halo-level ambition:

- **Bejeweled**: Simple match-3 loop with significant repetition
- Small games can validate core loops for larger experiences
- Use as prototype tools (see Prototyping skill)

## Iteration: Advanced Patterns

### The Iteration Spiral

```
        Version 4
            ↑
    Version 3
        ↑
Version 2
    ↑
Version 1 (Prototype)
```

Each iteration should:
1. Add meaningful content
2. Improve existing mechanics
3. Fix identified issues
4. Move toward final vision

### Iteration Scope Management

**Per Iteration:**
- Focus on 1-3 major additions
- Fix critical bugs from previous iteration
- Gather feedback before next iteration

**Avoid:**
- Adding too many features per iteration
- Changing core mechanics mid-development
- Skipping testing between iterations

### Regression Testing

After each iteration:
- Test all previously working features
- New features can break old ones
- Maintain a test checklist for each iteration

### Iteration in Different Game Types

**Linear Games (Metroid-style):**
- Player abilities iterate (grow)
- Return to previous areas with new abilities
- Each area designed for multiple ability levels

**Arcade Games (Donkey Kong-style):**
- Loop entire game with increased difficulty
- Same content, different parameters
- Enemy speed, spawn rate, AI aggression

**Service Games (MMO, Live Service):**
- Content updates as iteration
- Seasonal changes, new areas, balance patches
- Meta-game evolution over years