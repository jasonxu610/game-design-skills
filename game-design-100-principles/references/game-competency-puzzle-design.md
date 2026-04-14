---
name: game-competency-puzzle-design
description: Classifies game challenges as Memory-based or Skill-based to prevent player boredom or frustration, and provides specific rules for designing deterministic, fair puzzles. Use this when designing levels, mechanics, or puzzle systems.
---

# Game Competency and Puzzle Design

Use this skill when designing game challenges, level mechanics, or puzzles. It guides the classification of challenges to address player psychology (boredom vs. frustration) and establishes rules for creating valid puzzles.

## Procedure

### 1. Classify the Game Challenge Type

Determine if the challenge relies primarily on **Memory** or **Skill**. Note that many games contain elements of both.

*   **Memory Games**: Rely on trial-and-error, memorization, pattern recognition, and mastery of the game state.
*   **Skill Games**: Require physical or mental prowess/attributes.

### 2. Address Negative Player States

Based on the classification, apply specific mitigation strategies to maintain player engagement.

#### If Memory-Based (Combat Boredom)
*   **Problem**: Players get bored repeating the same actions in the same areas.
*   **Solution**: Introduce randomness to create variation while keeping core mechanics and story consistent.
*   **Implementation**: Vary enemy locations, add moving platforms, or implement randomized loot drops.

#### If Skill-Based (Combat Frustration)
*   **Problem**: Players get frustrated if they lack the required skill to proceed.
*   **Solution**: Implement assist mechanics to bridge the gap without compromising the core design.
*   **Implementation**:
    *   Hints (e.g., NPC appearing to offer help).
    *   Tutorials or help videos (e.g., warping back to a tutorial area).
    *   Visual guides (e.g., flashing the correct path).
    *   Environmental assistance (e.g., using enemies as stepping stones).

### 3. Design Puzzles by Key Principles

When designing specific puzzle mechanics, ensure they meet the following criteria:

*   **Difficulty**: Maintain "Flow" (neither too easy nor too hard). Use "Breadcrumbs" (progressive hints) to guide the player through the solution.
*   **Solution Quality**: Solutions must require a smart or intellectual approach, not brute force.
*   **Determinism**: Puzzles must be deterministic once generated. The same inputs must produce the same outputs (unlike dynamic games like Tennis).
*   **Clarity**: Goals and rules must be explicit and fair. Avoid "guess the rule" puzzles where the logic is obscured.