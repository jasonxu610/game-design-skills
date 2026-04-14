---
name: player-psychology-decisions
description: Use when designing game mechanics, challenges, puzzles, or decision systems that involve player choice, problem-solving, or risk assessment. Applies when you need to account for cognitive biases, prevent player frustration, or structure risk-reward scenarios.
---

# Player Psychology in Decision Making

Design game systems that account for cognitive biases, problem-solving obstacles, and risk-reward decision patterns.

## When to Apply

- Designing puzzles or challenges
- Creating combat or strategic systems
- Implementing risk-reward mechanics
- Structuring player choices
- Analyzing player behavior and feedback

## Cognitive Biases Affecting Player Perception

Players interpret game events through psychological filters, not objective reality.

### Confirmation Bias
- **Pattern**: Players notice and believe information matching pre-existing beliefs; ignore contradictory evidence
- **Impact**: Players may reject game facts that don't fit their mental model
- **Design Consideration**: Provide overwhelming evidence when challenging player assumptions

### Availability Heuristic

**Negativity Bias:**
- Negative/emotional experiences are easier to remember than neutral ones
- Example: Players remember bad Scrabble hands more than good ones

**Recency Bias:**
- Recent events are weighted more heavily than historical data
- Can create false perceptions of trends from random events

### Anchoring
- **Pattern**: Players relate all new information to an initial "anchor" (e.g., sale price vs. original price)
- **Application**: First impressions strongly shape subsequent interpretations

### Framing/Kuleshov Effect
- **Pattern**: How information is packaged (wording, UI, context) changes interpretation
- **Kuleshov Effect**: Players derive context from surrounding information to fill in ambiguous signals
- **Example**: Random AI bark may be interpreted as intelligent based on surrounding cues

## Problem-Solving Obstacles

Design challenges while recognizing why players get stuck:

### Common Cognitive Blocks

**Functional Fixedness:**
- Player knows a function (break brown box) but can't apply it to variation (blue box)
- **Mitigation**: Provide visual/audio cues linking similar interactions

**Irrelevant Information:**
- Too much detail obscures the solution
- Example: Picking up knife when holding guns
- **Mitigation**: Focus player attention on relevant elements

**Assumptions:**
- Player assumes impossibility without trying (e.g., jump distance)
- **Mitigation**: Visual/audio cues, generous save points, low-risk testing areas

**Mental Set:**
- Stuck in previous habits
- Example: Contra controls changing in 3D section
- **Mitigation**: Gradual transition, clear tutorial for new patterns

## Risk Assessment and Decision Making

### Cost-Benefit Analysis

Players weigh failure risk against reward value:

**Triangularity:**
- Offer choices between:
  - Low Risk / Low Reward paths
  - High Risk / High Reward paths
- Engages strategic decision-making

**Hoarding Behavior:**
- Players save powerful items (bombs) "just in case"
- Perceived risk of not having them later > current benefit
- **Design Response**: Make items feel necessary or abundant enough to use

### Design Goals

- Force frequent decisions to maximize engagement
- Balance challenge to avoid frustration
- Provide clear feedback on decision outcomes

## Variables

- **obstacle_type**: Category (Fixedness, Irrelevant Info, Assumption, Mental Set)
- **risk_level**: Probability and cost of failure
- **reward_value**: Benefit of success
- **bias_type**: Cognitive bias affecting perception

## Constraints

- Biases operate subconsciously—players may not be aware of them
- Different individuals may vary, but general patterns apply
- Poorly designed obstacles cause frustration

## Result Template

Player engages in strategic decision-making or overcomes a cognitive block through thoughtful design.