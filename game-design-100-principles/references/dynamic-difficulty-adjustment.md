---
name: dynamic-difficulty-adjustment
description: Use when implementing systems to adjust game difficulty based on player performance, frustration, or failure patterns. Applies when designing boss battles, skill-based challenges, or any task where players may repeatedly fail and become frustrated.
---

# Dynamic Difficulty Adjustment (Buster Principle)

Subtly adjust game difficulty based on player performance to maintain engagement without the player's awareness.

## When to Apply

- Players attempt a task multiple times without success
- Designing boss battles or difficult challenges
- Implementing skill-based obstacles
- Balancing player frustration vs. satisfaction
- Designing adaptive game systems

## The Buster Principle

### Core Concept

Named after Buster Keaton (a cockatoo) who lowered game difficulty when the owner got frustrated to prolong play.

### Mechanism

1. Monitor player behavior to detect frustration or excessive failure at a specific task
2. When a player obviously tries many times without success, intervene
3. Adjust the task to be slightly easier
4. Perform adjustments subtly in the background
5. Shift player emotion from frustration (throwing controller) to satisfaction (pumping fist)

## Implementation Guidelines

### Monitoring Player State

**Metrics to Track:**
- **attempt_count**: Number of times player tries a task
- **success_rate**: Player's performance metrics (accuracy, time, deaths)
- **time_spent**: Duration of attempts
- **rage_quit_indicators**: Sudden stops, button mashing, retries

### Adjustment Strategies

**Subtle Adjustments:**
- Lower enemy health or damage by small percentages (5-10%)
- Widen timing windows for actions
- Reduce number of enemies or obstacles
- Provide additional resources (ammo, health)
- Slow down enemy attack patterns

**Maintain Challenge:**
- Do not make the game too easy
- Keep the task still requiring effort
- Ensure player still feels achievement

### Detection Thresholds

**Signs of Frustration:**
- 3-5 consecutive failures on the same task
- Increasing time between attempts (hesitation)
- Rage indicators (rapid retries without improvement)
- Abandoning task and returning later

## Variables

- **attempt_count**: Number of times player tries a task (integer)
- **success_rate**: Player's performance metrics (float)
- **frustration_level**: Derived metric from behavior patterns
- **adjustment_factor**: How much to reduce difficulty (0-1 scale)

## Constraints

- **Do not make the game too easy**—this removes satisfaction
- **Not applicable** if goal is purely competitive fairness (e-sports)
- **Keep adjustments secret**—don't notify players of difficulty changes
- **Apply gradually**—small increments are less noticeable

## Execution Workflow

1. **Define baseline difficulty** for each task or challenge
2. **Set monitoring parameters** (what counts as "trying many times")
3. **Implement detection logic** for frustration patterns
4. **Create adjustment rules** (what changes, by how much)
5. **Test thoroughly**—ensure adjustments feel natural, not noticeable
6. **Monitor playtesting** for unexpected behaviors

## Benefits

- Maintains player engagement through difficult sections
- Prevents rage quitting
- Provides sense of achievement
- Accommodates varying player skill levels
- Creates personalized experience

## Result Template

Task difficulty is reduced incrementally to allow player progression and satisfaction, maintaining the illusion of fixed challenge.