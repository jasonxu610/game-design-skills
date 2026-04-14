---
name: visual-player-guidance
description: Use when designing visual elements that need to guide player interaction, focus attention, or facilitate navigation in UI/HUD, game environments, or puzzles. Applies when players need to intuitively understand how to interact with objects or where to go without explicit instructions.
---

# Visual Player Guidance

Design visual elements that intuitively convey interaction possibilities and guide player attention without requiring tutorials or explicit instructions.

## When to Apply

- Designing interactive UI/HUD elements
- Creating game environments requiring player navigation
- Designing puzzles with physical or virtual objects
- Implementing touch/tablet gesture systems
- Building levels that need wayfinding support

## Core Principles

### Affordance Cues

Affordance cues are visual or physical characteristics that intuitively convey how to interact with an object.

**Key Rule:** Cues must match the designer's intended action. A button meant to be pushed must look pushable, not pullable.

#### Application Areas

**UI/HUD Design:**
- Use bevels, shadows, and shapes (e.g., circles) to imply clickability
- Design elements that appeal to senses (tasty, tactile) to increase interaction urge
- Ensure form follows function—dials should cue circular gestures

**Touch/Tablet Interfaces:**
- Map natural actions (swiping, tapping) to visual cues
- Use visual indicators that guide finger movement (e.g., circular tracing paths)

**Environments and Puzzles:**
- Use clear paths (roads, carpets) to guide player movement
- Design objects with handles or features implying correct behavior
- Start with basic shapes, then add cues (color, shadow) to clarify interaction

### Attention Capture

Use innate psychological triggers to focus player attention on specific elements.

**For Marketing/UI:**
- **Faces**: Humans instinctively recognize and focus on faces
- **Motion**: Flashing, bouncing, or animated elements draw the eye
- **Surprise**: Break patterns in familiar interfaces to create interest
- **Appealing Imagery**: Food, attractive characters trigger basic desires

**For Wayfinding (Level Design):**
- **Landmarks**: Unique objects at decision nodes for orientation
- **Weenies**: Large, distant landmarks that attract players
- **Birth Canals**: Funnel-shaped spaces leading to open areas (tension/release)
- **Structured Paths**: Visual lines (roads, cleared forest) guiding movement
- **Light**: Players instinctively move toward light; warm = comforting, cold = daunting

## Execution Workflow

1. **Identify the intended player action** for each interactive element
2. **Select appropriate visual cues** that match the intended action (push, pull, rotate, etc.)
3. **Test intuitiveness**: Can players understand interaction without instructions?
4. **Apply attention capture** techniques to highlight important elements
5. **Implement wayfinding cues** for navigation in environments
6. **Verify consistency**: Ensure cues match throughout the game

## Variables

- **visual_cue**: Shape, shadow, bevel, or color indicating usage
- **intended_action**: The specific behavior the designer wants the user to perform
- **cue_type**: Category (Face, Motion, Landmark, Light, etc.)
- **goal**: Attention capture or Navigation

## Benefits

- Reduces time spent on tutorials/instructions
- Directs players to correct behaviors intuitively
- Prevents gameplay from becoming a "logical disaster"
- Guides player focus without explicit instructions