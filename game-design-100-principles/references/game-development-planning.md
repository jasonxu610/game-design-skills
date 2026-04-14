---
name: Game Development Planning
description: Define game pillars, problem statements, and resource allocation for game projects. Use when starting a new game project, prioritizing development resources, defining project scope, or making strategic trade-offs between speed, cost, and quality.
---

# Game Development Planning

## When to Use

- Starting a new game project or pitching to publishers
- Prioritizing development resources and features
- Defining design goals and project scope
- Making strategic project management decisions
- Communicating project direction to team or stakeholders

## Planning Workflow

### Step 1: Define Game Pillars

Game pillars are high-level, action-focused concepts that guide all development decisions.

**Requirements:**
- Define **3 pillars** (6 is too many)
- Each pillar MUST relate to player ACTIONS, not just art/theme
- Combine into ONE SENTENCE for communication

**Brainstorming Questions:**
- What if we combine best elements from two genres?
- What if we modify a failed mechanic from another game?
- What if we extend current gameplay to allow new behaviors?
- What if we replicate experiences from other media?

**Example - "Fluid Movement" as a Pillar:**
- Camera: Third-person (highlights movement advantages)
- Character Design: Tall/thin fits better than short/stout
- Combat: Must extend fluid movement to combat
- World Design: Architecture must communicate climbability
- Animation: Requires many transitions (plan workload)

### Step 2: Create Problem Statement

The problem statement is the FIRST and MOST IMPACTFUL step in the creative process.

**Three Required Components:**

1. **Specific Focus** - Determine scope: entire game? a system? a specific mechanism?
2. **Quantifiable Result** - Must yield actionable data
3. **Clear Communication** - Test by explaining to another designer

**Scope Calibration:**

| Level | Example | Issue |
|-------|---------|-------|
| Too Broad | "How do I design a turn-based strategy game?" | Wastes time, insufficient detail |
| Appropriate | "How do I create a fighting game with light RPG elements and weapon forging?" | Clear boundaries, measurable goal |
| Too Narrow | "How do I build an advanced enemy patrol AI?" | May exclude unconventional solutions |

**Validation Method:** Explain to a collaborating designer familiar with the problem and methodology.

### Step 3: Apply 80/20 Rule for Resource Allocation

Players spend ~80% of time using only ~20% of game features.

**Strategic Actions:**
- Identify the 20% core features (basic actions: jumping, fighting, leveling)
- Focus development effort on perfecting these core features
- Avoid over-optimizing flashy but rarely-used features

**Application Examples:**
- **Zelda**: Players spend 80% of time moving/attacking - prioritize smooth core mechanics
- **WoW Movement**: Map traversal is frequent - optimize movement speed to prevent frustration
- **WoW Endgame**: Players spend 80% of endgame effort on raids (20% of content)
- **Game Start**: Beginning is replayed more than ending - invest accordingly

### Step 4: Manage Project Constraints

Use the Fast-Cheap-Good triangle to make explicit trade-offs.

**The Constraint Triangle:**

```
        Fast
        /\
       /  \
      /    \
     /      \
   Good ----- Cheap
```

**You can only pick TWO:**

| Choice | Result | Strategy |
|--------|--------|----------|
| Fast + Cheap | Not Good | Prototyping, feasibility checks |
| Fast + Good | Not Cheap | Hire more staff/experts |
| Cheap + Good | Not Fast | Independent development, long timeline |

**Scope Management:** Reduce scope (fewer features) to maintain quality without disproportionate time/cost increases.

**Warning:** It IS possible to have Slow, Expensive, AND Bad - avoid this outcome.

## Integration Checklist

- [ ] 3 action-focused pillars defined and communicated
- [ ] Problem statement has specific focus, quantifiable result, clear communication
- [ ] Core 20% features identified for priority development
- [ ] Two constraints prioritized, third explicitly managed
- [ ] Scope adjusted to match available resources