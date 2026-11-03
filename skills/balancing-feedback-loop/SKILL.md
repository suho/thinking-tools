---
name: balancing-feedback-loop
description: Balancing feedback loop - analyze a self-correcting mechanism that pushes back against change toward a goal (thermostat, homeostasis, plateaus, resistance to change) by finding its goal, actual level, gap, and corrective action. Use when the user sees a plateau, a metric that snaps back, resistance to a change, or wants to design a control or stabilizing mechanism.
---

# Balancing Feedback Loop

Turn the user's situation into an explicit balancing loop: its goal, actual level, gap, corrective action, delays, and how to work with or change it.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct loop (one round, max 3 questions). The minimum input is the thing that stays stable, plateaus, or resists change.

## Steps

1. **Goal.** Identify the desired level the loop seeks. This is the key step: the goal is often implicit (a norm, a budget, an unwritten standard, a physical equilibrium). Say if it is designed or natural. Done when you can name the goal and the evidence for it.
2. **Actual level.** Identify the measured or perceived current state.
3. **Gap.** Describe how the loop detects the difference between goal and actual.
4. **Corrective action.** Describe what closes the gap and who or what performs it.
5. **Delays.** Name delays between gap, action, and effect. Long delays cause overshoot and oscillation.
6. **Use it.** If the user wants change but the loop resists, change the goal itself rather than pushing against the corrective action. If the user wants stability, strengthen detection and shorten delays.

## Output

```markdown
## Loop
- Goal: <desired level> (<designed / natural>, evidence: <...>)
- Actual level: <...>
- Gap detection: <...>
- Corrective action: <...>
- Delays: <...>

goal vs actual -> gap -> corrective action -> actual level moves toward goal

## Behavior
<what the loop causes: plateau, snap-back, oscillation, resistance>

## Recommendation
<change the goal / strengthen detection / shorten delays / ...>
```

## Related

- `reinforcing-feedback-loop` for the growth the loop limits.
- `connection-circles` to find the loop in a larger system.

Source: https://untools.co/balancing-feedback-loop/
