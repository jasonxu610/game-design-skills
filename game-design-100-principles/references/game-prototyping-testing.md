---
name: Game Prototyping and Testing
description: Validate game designs and identify issues through prototyping and testing methodologies. Use when validating game concepts, finding bugs, testing player experience, or ensuring game quality before full development.
---

# Game Prototyping and Testing

## When to Use

- Validating a game concept before full development
- Finding bugs and usability issues
- Testing player experience and fun factor
- Ensuring game communicates clearly
- Verifying server stability for online games

## Prototyping Methods

### Paper Prototyping

**Best for:** UI design, card games, board games, early concept validation

**Materials:** Paper, scissors, pens

**Advantages:**
- Fastest and cheapest method
- Immediate iteration
- Easy to modify

**Techniques:**
- Use color/texture to distinguish elements
- Create multiple versions quickly
- Test with actual players immediately

### Digital Prototyping

**Best for:** Video game mechanics, control schemes, timing-sensitive gameplay

**Tools:** Touch screens, middleware, game engines

**Advantages:**
- Faster iteration after initial setup
- Easy sharing with remote team
- More accurate representation of final experience

### General Prototyping Principles

**Purpose:** Create representative models to test:
- Feasibility (can we build this?)
- Usability (can players understand this?)
- Market demand (will people want this?)

**Warning:** Never skip prototyping to save time in early stages.

## Testing Methods

### Kleenex Test

**Definition:** One-time use per test subject.

**Purpose:** Validates first impressions and initial learning curve.

**Process:**
1. Bring in fresh player who has never seen the game
2. Observe their first interaction
3. Record where they struggle or get confused
4. Do NOT reuse the same player for this test type

**Best for:** Tutorial design, first-time user experience, onboarding

### Black Box Testing

**Definition:** Subject knows nothing about the design.

**Purpose:** Reveals natural player behavior vs. designer intent.

**Process:**
1. Give player the game with no instructions beyond basic controls
2. Observe how they naturally approach the game
3. Note where their assumptions differ from design intent
4. Identify UI/UX issues that mislead players

**Best for:** Discovering unintended gameplay, finding confusing elements

### White Box Testing

**Definition:** Subject follows a script or specific path.

**Purpose:** Finds specific bugs and logic errors.

**Process:**
1. Create test script covering specific features
2. Guide player through predetermined actions
3. Document any bugs or unexpected behavior
4. After fixes, perform Regression Testing

**Regression Testing:** Re-test all previously working features after bug fixes.

**Best for:** QA, bug hunting, feature verification

### Load Testing

**Definition:** Simulate thousands of players simultaneously.

**Purpose:** Check server stability and performance.

**Application:** MMOs, online multiplayer games, live service games

**Process:**
1. Simulate expected player load
2. Monitor server performance
3. Identify bottlenecks and failure points
4. Test beyond expected load for safety margin

**Best for:** Online games before launch, major updates

## Testing Goals

Ensure the game is:

| Goal | Validation Method |
|------|------------------|
| Fun | Kleenex test, observe emotional reactions |
| Clear | Black box test, track confusion points |
| Functional | White box test, bug reports |
| Stable | Load test, performance metrics |

## Testing Cycle

```
┌─────────────────────────────────────┐
│                                     │
│    1. Prototype                     │
│           ↓                         │
│    2. Test                          │
│           ↓                         │
│    3. Analyze Results               │
│           ↓                         │
│    4. Iterate                       │
│           ↓                         │
│    Return to Step 2                 │
│                                     │
└─────────────────────────────────────┘
```

## Quick Reference

| Method | When to Use | What It Reveals |
|--------|-------------|-----------------|
| Paper Prototype | Early concept, UI/board games | Core mechanics viability |
| Digital Prototype | Video game mechanics | Feel, timing, controls |
| Kleenex Test | First-time experience | Onboarding, tutorials |
| Black Box Test | Natural behavior | UX issues, assumptions |
| White Box Test | Bug hunting | Technical issues |
| Load Test | Online games | Server stability |