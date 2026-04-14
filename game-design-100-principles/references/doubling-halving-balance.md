---
name: doubling-halving-balance
description: Rapidly identify game balance issues by doubling or halving core game variables (movement, time limits, resources, health/damage) during prototyping and balance tuning. Use when you need to quickly validate design hypotheses or expose balance flaws.
---

# Doubling and Halving Balance Method

## When to Use
- In prototype phase to discover design issues
- During balance tuning to identify problematic variables
- Testing hypotheses about game balance
- Needing to quickly find the right range for a variable
- Internal development testing (not for external playtesters)

## Core Concept
Make extreme adjustments (2x or 0.5x) to core game variables rather than fine-tuning. This quickly reveals whether a variable has meaningful impact and helps find the right balance range.

## Execution Steps

### 1. Identify Target Variable
Select a variable that significantly impacts core game balance:
- Movement options (speed, jump height)
- Time limits (level timers, cooldowns)
- Resource allocation (ammo, mana, currency)
- Health or damage ratios
- Other programmable input values

**Skip:** Variables with minimal impact on game experience

### 2. Choose Adjustment Direction
- **Double (2x):** If current value seems too low or weak
- **Halve (0.5x):** If current value seems too high or strong
- Base direction on your testing hypothesis

### 3. Apply Adjustment and Test
- Modify the variable value
- Playtest to observe impact
- Record whether change produces significant difference

### 4. Iterate Until Impact is Found
- If no significant change: double/halve again
- Continue until you observe meaningful impact on gameplay
- Track iteration count

### 5. Analyze Results
- **Significant change found:** Variable is important; now fine-tune from this point
- **No change even after extreme iterations:** Variable may not matter; consider removing or redesigning
- **Change reveals new issues:** Adjust other related variables

### 6. Determine Next Action
- If balance is close: proceed to fine-tuning
- If fundamental issues exposed: consider redesign
- Document findings for future reference

## Example Workflow
**Problem:** Player starting health is 200; game feels too easy

1. Halve health to 100
2. Playtest
3. If still too easy → halve to 50
4. If now too hard → fine-tune between 50-100
5. Result: Found meaningful range in 2 iterations vs. 20+ micro-adjustments

## Constraints and Warnings
- **Internal tool only:** Do not use with external playtesters
- **Developer knowledge required:** Must understand how systems interact
- **Prepare for discomfort:** Extreme values will create bad experiences
- **Not for A/B testing:** Non-developers find extreme conditions frustrating
- **Not for trivial variables:** Only use for balance-critical values

## Advantages
- Exposes balance flaws quickly
- Saves time compared to incremental tuning
- Reveals which variables actually matter
- Gets you close to target values fast
- Can be used throughout development until final release