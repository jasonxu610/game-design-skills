---
name: experience-pacing-structure
description: Use when designing game flow, level structure, loading screens, cutscenes, or any content introduction. Applies when introducing new concepts, transitioning between scenes, managing player attention spans, or structuring sandbox vs. linear experiences.
---

# Experience Pacing and Structure

Structure and pace game experiences to match player cognitive limits while introducing new content effectively.

## When to Apply

- Introducing new game mechanics or content
- Designing loading screens or transitions
- Planning level progression or game loops
- Structuring sandbox vs. linear experiences
- Implementing attention management systems
- Creating selection menus or map systems

## Advance Organizers

Advance organizers are introductory materials with higher abstraction that precede actual learning tasks, helping players:

- Connect new concepts with prior knowledge
- Place new information into context
- Prepare for upcoming information or transitions

### Implementation Types

**Pre-publicity:**
- **Use**: Ads, demos, trailers, industry conferences
- **Goal**: Raise awareness of upcoming releases
- **Technique**: Alternate between reality and game content
- **Outcome**: Set expectations regarding genre or series

**Loading Screens:**
- **Content**: Introduce at least one game character or establish visual tone
- **Indicators**: Include time prompts (spinning ball, timer) to show background work
- **Outcome**: Signal that something new and exciting is imminent

**Cutscenes:**
- **Use**: Non-playable story sequences at start or during transitions
- **Content**: Provide backstory and context
- **Outcome**: Set expectations, suspense, and signal content/scene changes

**Selection Menus:**
- **Design**: Use visual structures (maps, not lists) to prepare players mentally
- **Avoid**: Simple lists which disorient

### Critical Constraints

- **Use ONLY when introducing new content**
- **Do not force long loading screens** if no new content follows
- **Warning**: If this occurs, it indicates a technical content loading/storage issue requiring developer resolution
- **Consistency**: Ensure the organizer matches the game's artistic style

## Game Experience Structures

### Sandbox Experience Design

**Definition**: Provide freedom to explore/change things without specific goals.

**Mechanism**:
- Allow creative combination of simple, independent mechanics
- Create chain reactions from player actions

**Developer Tasks**:
- Prioritize obvious combinations
- Predict edge cases
- Trust system for unpredicted results

**Structure**: Can be a small part of a game or full open world (which hides physical boundaries)

**Requirement**: Simple, combinable mechanics

### On Rails Experience Design

**Definition**: Require linear completion of experience.

**Benefit**: Focuses player attention on specific tasks and key moments.

**Pacing Models**:

**Train:**
- Consistent experience over time
- No twists
- Predictable rhythm

**Rollercoaster:**
- Sudden direction changes
- Visual stimulation
- Strategic expectation management for surprise

**Requirement**: Careful pacing to maintain engagement

## Attention Span Management

### Biological Limits

- **Human Attention Span**: 7-10 minutes before focus naturally shifts
- **Implication**: Break experiences into 7-10 minute chunks

### Social Game Specifics

- **Core loops**: Should last 1-2 minutes
- **Task completion**: Must be completable in under 10 minutes

### Retention Strategies

**Passive:**
- Show new elements/rewards every ~7 minutes
- Maintain variety to prevent boredom

**Active:**
- Use timers to detect inactivity (1-2 mins)
- Display help/tasks to regain attention

## Variables

- **content_type**: Type of advance organizer (publicity, loading, cutscene, menu)
- **art_style**: Visual theme of the game
- **new_content_available**: Whether actual new content follows the organizer
- **attention_span**: The approximate duration (7-10 mins) a human can maintain focus
- **experience_type**: Sandbox or On Rails

## Design Goals

- Maintain player engagement within cognitive limits
- Smoothly introduce new content without frustration
- Match structure to intended player freedom
- Respect player attention spans

## Result Template

A game experience structured to match player cognitive limits and desired freedom levels.