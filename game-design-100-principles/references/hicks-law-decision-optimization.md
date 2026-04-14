---
name: hicks-law-decision-optimization
description: Optimize user interfaces, game menus, and navigation systems by applying Hick's Law to estimate decision time based on number of choices. Use when designing choice interfaces to reduce cognitive load and prevent decision paralysis.
---

# Hick's Law Decision Optimization

## When to Use
- Designing user interfaces with multiple options
- Creating game menus or navigation systems
- Presenting lists of similar, ordered choices
- Users must make a selection from available options
- Wanting to reduce decision time and cognitive load

## Core Concept
Decision time increases logarithmically as the number of choices increases. Too many options can cause decision paralysis and abandonment.

**Formula:** T = a + b × log₂(n)
- T = Reaction time
- n = Number of choices
- a = Base time for non-choice cognitive processes
- b = Time per bit of information processing

## Execution Steps

### 1. Count Your Choices
- Identify all options available to the user
- Determine if choices are similar/ordered or unrelated

### 2. Estimate Decision Impact
- More choices = logarithmically longer decision time
- Too many choices = higher probability of abandonment
- Unrelated/unordered choices = linear (worse) time growth

### 3. Apply Design Strategies

**Limit Options (Primary Strategy)**
- Aim for 3-6 items for optimal decision speed
- Remove unnecessary options
- Consolidate similar choices

**Group Similar Options**
- For complex lists (e.g., large inventories), create categories
- Each category reduces effective 'n' for that decision
- Example: Amazon groups products by type, brand, price range

**Structure Menus Hierarchically**
- Fewer main options with more sub-options
- Avoid many main options with few sub-options
- Use progressive disclosure

### 4. Handle Exceptions

**Customization Scenarios**
- If user has specific pre-existing preferences (e.g., character appearance)
- Provide more options but organize into categorized sub-menus
- Allow filtering and sorting

**Expert Users**
- Power users may prefer more options visible
- Consider providing both simple and advanced modes

### 5. Validate Through Testing
- Prioritize playtesting over strict mathematical calculation
- Human cognitive limits may override theoretical predictions
- Example: 4 million options is not just "30x harder" than 4—it's overwhelming
- Measure actual decision time and abandonment rates

## Common Applications
- **Main Menus:** Keep options minimal and clear
- **Settings Menus:** Group related settings together
- **Inventory Systems:** Use categories, filters, and search
- **Dialog Trees:** Limit branch complexity at each node
- **Skill Trees:** Organize into logical groups

## Key Considerations
- The law applies best to similar, ordered choices
- Context matters—expert users handle more complexity
- Visual design can mitigate cognitive load (icons, grouping)
- Always test with real users
- Balance between choice and decision paralysis