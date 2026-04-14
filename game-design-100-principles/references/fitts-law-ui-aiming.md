---
name: fitts-law-ui-aiming
description: Balance speed and precision in UI design and aiming mechanics by applying Fitts' Law principles about movement time, distance, and target size. Use when designing interactive elements that require physical input or aiming.
---

# Fitts' Law for UI and Aiming Mechanics

## When to Use
- Designing user interfaces with clickable/tappable elements
- Creating aiming mechanics for combat or interaction
- Optimizing controller or mouse input systems
- Balancing difficulty in precision-based gameplay
- Reducing user fatigue and frustration

## Core Concept
Movement time depends on the distance to the target and the target's size. As speed increases, precision decreases—this is a fundamental trade-off.

**Key Parameters:**
- D = Distance from start point to target center
- W = Width of target along the axis of motion
- H = Height of target (critical for usability)

## Execution Steps

### 1. Analyze the Movement Task
- Identify where the user starts (cursor position, character location)
- Identify the target (button, enemy, interactive element)
- Measure distance (D) and target size (W, H)

### 2. Apply UI Design Principles

**Group Related Elements**
- Place similar functional elements together
- Reduces travel distance between related actions
- Creates logical interaction patterns

**Optimize Element Placement**
- Place frequently used elements near common starting positions
- Example: Place primary actions near where cursor typically rests
- Consider screen edges and corners (effectively infinite targets)

**Size Elements Appropriately**
- Make frequently used elements larger
- Increase width (W) to reduce required precision
- Ensure adequate height (H)—thin targets are hard to click

**Reduce Distance**
- Bring UI elements closer to interaction points
- Minimize unnecessary cursor travel
- Consider radial menus for faster access

### 3. Apply to Combat/Aiming Mechanics

**Set Difficulty Parameters**
- Adjust target size (W) based on desired difficulty
- Adjust distance (D) to challenge player precision
- Balance both to create intended experience

**Test Against Skilled Players**
- Fastest/most skilled players set the difficulty ceiling
- If experts can't hit it, it's too hard
- If novices can't hit it, consider difficulty scaling

**Consider Movement Constraints**
- Player movement speed affects effective distance
- Weapon characteristics affect precision
- Environmental factors (cover, obstacles) modify D and W

### 4. Validate Through Testing
- Measure actual movement times
- Observe user frustration and fatigue
- Test with different input devices (mouse, controller, touch)
- Iterate based on real user performance

## Common Applications
- **Button Placement:** Size and position based on usage frequency
- **Menus:** Reduce distance between sequential selections
- **Combat Targets:** Enemy hitboxes and engagement ranges
- **Quick-Time Events:** Balance timing windows with target areas
- **Drag-and-Drop:** Optimize drop zones and travel paths

## Key Considerations
- Human physical limits apply
- Extremely small or distant targets can be impossible
- Different input devices have different precision characteristics
- Fatigue increases over time—account for extended sessions
- Accessibility: Some users have reduced motor control
- Visual feedback can help compensate for small targets

## Difficulty Balancing
- **Easy:** Large targets, short distances
- **Medium:** Moderate targets and distances
- **Hard:** Small targets, long distances
- **Expert:** Very small targets, very long distances, or moving targets