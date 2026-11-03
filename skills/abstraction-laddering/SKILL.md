---
name: abstraction-laddering
description: Abstraction laddering - reframe a problem statement by moving up ("why?") to broader problems and down ("how?") to concrete ones, to find the right problem and new solution directions. Use when the user asks whether they are solving the right problem, has a narrow or solution-shaped problem statement, or wants alternative framings or "how might we" statements.
---

# Abstraction Laddering

Turn the user's problem statement into a ladder of framings, from abstract to concrete, and pick the framing that opens the best solutions.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct ladder (one round, max 3 questions). The minimum input is one problem statement or goal.

## Steps

1. **Anchor.** Rewrite the user's input as one problem statement. Put it in the middle of the ladder.
2. **Climb up.** Ask "why does this matter?" of the anchor. Write the answer as a broader problem statement. Repeat 2-3 times. Stop when the statement becomes a universal goal that gives no direction. Done when each rung is a real reason for the rung below.
3. **Climb down.** Ask "how might we do this?" of the anchor. Write the answer as a more concrete statement. Repeat 2-3 times until you reach an actionable solution.
4. **Branch.** From each upper rung, ask "how else?" to create 1-2 sibling statements that differ from the original path. These alternative framings are the main value of the tool.
5. **Choose.** Pick the 1-2 framings with the best balance of scope (broad enough to allow new solutions, narrow enough to act on). Say why.

## Output

```markdown
## Ladder
- **Why** <most abstract statement>
  - <alternative from this rung: how else?>
- **Why** <broader statement>
  - <alternative>
- **Anchor:** <original problem statement>
- **How** <more concrete statement>
- **How** <concrete solution>

## Reframed problems
1. How might we <...>? - <why this framing is useful>
2. ...

## Recommendation
<framing to pursue and first step>
```

## Related

- `first-principles` to rebuild a solution for the chosen framing.
- `issue-trees` to break the chosen framing down.
- `productive-thinking-model` to solve it creatively.

Source: https://untools.co/abstraction-laddering/
