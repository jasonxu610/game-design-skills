---
name: Player Error Handling
description: Classify and design responses for player errors in games. Use when analyzing player behavior issues, designing error-tolerant systems, improving user experience, or creating helpful feedback for player mistakes.
---

# Player Error Handling

## When to Use

- Analyzing player behavior during playtesting
- Designing error-tolerant game systems
- Creating feedback for player mistakes
- Improving user experience and accessibility
- Debugging player flow issues

## Error Classification System

### Level 1: Primary Categories

```
┌─────────────────────────────────────┐
│        Player Errors                │
└─────────────┬───────────────────────┘
              │
    ┌─────────┴─────────┐
    ▼                   ▼
Motor Control       Behavioral
Errors               Errors
```

### Motor Control Errors

**Definition:** Errors stemming from player coordination, mastery, or application of input devices.

**Examples:**
- Simple: Accidentally pressing wrong button
- Complex: Failing to time a boss fight action correctly
- Physical: Accidentally knocking over chess pieces

**Design Responses:**
- Understand target audience capabilities
- Conduct playtesting to predict and control these errors
- Consider player age or physical condition limitations
- Example: Board games for children shouldn't use tiny pieces
- Console games must consider controller familiarity

### Level 2: Behavioral Error Subtypes

```
┌─────────────────────────────────────┐
│        Behavioral Errors            │
└─────────────┬───────────────────────┘
              │
   ┌──────────┼──────────┐
   ▼          ▼          ▼
Procedure  Omission   Wrong
Errors     Errors     Action
```

#### Procedure Errors

**Definition:** Adding extra, unwanted steps to a procedure.

**Example:** Player thinks they need to return to main menu to find map, when current screen has access.

**Causes:**
- Confusing interface design
- Inattentional blindness

**Design Response:** Improve UI clarity, reduce unnecessary navigation paths

#### Omission Errors

**Definition:** Failing to complete one step in an action sequence, missing something important.

**Design Responses:**
- Keep action sequences short and direct
- Ensure step information is obvious, logical, or intuitive
- Balance learning curve appropriately

#### Wrong Action Errors

**Definition:** Executing wrong action in a situation - should do one thing but did another.

**Design Response:** Apply "Unpunished Errors" principle

**Provide:**
- Entertaining failure states
- Witty, clever hint messages
- Opportunities to recover without major penalty

## Design Response Framework

### General Principles

1. **Predict** possible error types for your game
2. **Prepare** countermeasures in advance
3. **Provide** helpful hint text
4. **Guide** players back to correct direction
5. **Make** occasional mistakes amusing, not frustrating

### Error Severity Response Matrix

| Severity | Response |
|----------|----------|
| Minor | Subtle visual/audio cue |
| Moderate | Clear feedback, easy recovery |
| Major | Explicit guidance, minimal penalty |
| Critical | Auto-save, checkpoint, or undo option |

### Target Audience Considerations

| Audience | Motor Control Focus | Behavioral Focus |
|----------|---------------------|------------------|
| Children | Large UI elements, simple inputs | Short sequences, obvious steps |
| Casual | Forgiving timing, clear prompts | Guided tutorials, hints |
| Hardcore | Precise challenges accepted | Complex sequences allowed |
| Accessibility | Alternative input methods | Extended time limits |

## Quick Reference

| Error Type | Key Characteristic | Primary Design Response |
|------------|-------------------|------------------------|
| Motor Control | Input coordination | Know audience, playtest |
| Procedure | Extra unwanted steps | Clear UI, reduce paths |
| Omission | Missing step | Short sequences, obvious info |
| Wrong Action | Incorrect choice | Entertaining failure, recovery |

## Integration with Related Principles

- **Principle 63 (Attention and Perception)**: Understand why players miss information
- **Principle 64 (Balance and Debugging)**: Error handling as part of balance
- **Principle 69 (Unpunished Errors)**: Design philosophy for forgiving gameplay