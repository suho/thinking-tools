---
name: conflict-resolution-diagram
description: Conflict Resolution Diagram (Evaporating Cloud, Theory of Constraints) - map two opposing positions to their underlying needs and shared goal, expose the assumptions behind the clash, and build a win-win solution. Use when the user is stuck in a disagreement with someone (or an internal dilemma) where neither proposal seems acceptable, or says "evaporating cloud".
---

# Conflict Resolution Diagram

Turn a deadlocked disagreement into a map of positions, needs, and a shared goal, then into a solution that meets both needs.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct diagram (one round, max 3 questions). Typical gaps: what each side proposes, why each side wants it. The conflict can be between people or inside one person.

## Steps

Work the diagram from right to left: positions, then needs, then goal.

1. **Positions.** Write what side A wants to do and what side B wants to do. Phrase each as an action. Done when the two positions are clearly mutually exclusive.
2. **Needs.** For each position, ask "what need does this satisfy?" Write the need, not another action. Done when each need is something the other side could accept as legitimate.
3. **Shared goal.** Ask "what do both needs serve?" Write the higher objective both sides want. This is the critical step: confirm that both sides would agree with it. Done when both sides can say "yes, that is what I want too."
4. **Assumptions.** For each arrow (goal -> need, need -> position, and the conflict between positions), list the assumptions that make it true. Mark the weakest ones. The conflict usually rests on one weak assumption.
5. **Win-win options.** Challenge the weak assumptions. Generate 2-4 options that meet both needs and serve the shared goal. Pick the strongest and say why.

## Output

```markdown
## Diagram
| Shared goal | Need | Position |
|---|---|---|
| <goal> | A: <need> | A: <position> |
|        | B: <need> | B: <position> |

## Assumptions
- <arrow>: <assumption> - <weak/strong>

## Win-win options
1. <option> - meets A by <...>, meets B by <...>
...

## Recommendation
<chosen option and first step>
```

## Related

- `ladder-of-inference` to check each side's reasoning.
- `six-thinking-hats` to run the follow-up discussion.

Source: https://untools.co/conflict-resolution-diagram/
