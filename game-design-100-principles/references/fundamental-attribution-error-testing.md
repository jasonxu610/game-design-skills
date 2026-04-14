---
name: fundamental-attribution-error-testing
description: Identify and correct Fundamental Attribution Error bias when analyzing game testing feedback or user testing results. Use when interpreting test failures, feedback sessions, or user complaints to distinguish between actual design flaws and situational factors.
---

# Fundamental Attribution Error in Testing

Detect and correct cognitive bias when analyzing test feedback to accurately identify design flaws vs. user-specific issues.

## When to Use

- Analyzing game testing feedback
- Interpreting user test failures
- Reviewing feedback from test sessions
- Investigating why users struggle with a design

## Identify the Bias Pattern

**Self-Attribution** (when you experience failure):
- Attribute failures to external/situational factors
- Examples: "I was late", "System lag", "Bad controller", "Interrupted"

**Other-Attribution** (when others experience failure):
- Attribute failures to internal/personal traits
- Examples: "They are stupid", "Incompetent tester", "Lazy user", "Not paying attention"

## Apply to Testing Scenarios

### For Testers
- Testers experiencing issues will blame the game ("It's broken", "Bad design")
- They rarely attribute failures to their own state (tired, hungry, distracted)

### For Designers
- Designers watching failures will blame the testers ("They are incompetent")
- Or blame the test setup ("Unfinished build", "Wrong configuration")
- They often ignore the game's potential faults

## Corrective Actions

When analyzing feedback:

1. **Assume the product might be at fault**
   - Was the tutorial icon actually visible?
   - Was the button large enough to tap easily?
   - Was the instruction clear and understandable?

2. **Check situational factors first**
   - Consider the testing environment
   - Evaluate the tester's physical/mental state
   - Review the build quality and stability

3. **Do not dismiss feedback**
   - Never label issues as "user error" without verification
   - Investigate whether design contributed to the failure
   - Look for patterns across multiple testers

## Constraints

- Bias is subconscious and difficult to eliminate completely
- Being aware of the bias doesn't prevent it
- Requires deliberate effort to counteract natural tendencies