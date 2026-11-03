---
name: hard-choice-model
description: Hard choice model - classify a decision by impact (low/high) and comparability of options (easy/hard) as a no-brainer, apples and oranges, big choice, or hard choice, then apply the matching approach and effort. Use when the user is stuck on or overthinking a decision, asks "what kind of decision is this?", or needs to know how much time a choice deserves.
---

# Hard Choice Model

Turn the user's decision into a type, the right approach for that type, and a next step.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct classification (one round, max 3 questions). The minimum input is the decision and its options.

## Steps

1. **Decision.** Write the decision and its options.
2. **Impact.** Rate how much the outcome will affect the user's life, work, or organization: low or high. Give the reason (reversibility, cost, duration, people affected).
3. **Comparability.** Rate how easy it is to compare the options on the same terms: easy (same kind of thing, shared measures) or hard (different in nature, different values). Give the reason.
4. **Classify.**

   | | Easy to compare | Hard to compare |
   |---|---|---|
   | **Low impact** | No-brainer | Apples and oranges |
   | **High impact** | Big choice | Hard choice |

5. **Apply the approach.**
   - **No-brainer:** decide now; optimizing wastes time. Give the pick or a simple rule.
   - **Apples and oranges:** decide by the user's current priorities. Name the priority that decides it.
   - **Big choice:** gather enough data and compare thoroughly. List the data to collect and the comparison to run.
   - **Hard choice:** accept there is no objectively right answer. Lay out the factors (a decision matrix helps), name what the user values, and propose a small, reversible experiment to reduce risk.
6. **Time box.** Suggest how much time and energy the decision deserves.

## Output

```markdown
## Decision
<...> - options: <...>

## Classification
- Impact: <low/high> - <reason>
- Comparability: <easy/hard> - <reason>
- **Type: <type>**

## Approach
<type-specific guidance applied to this decision>

## Time box and next step
<...>
```

## Related

- `decision-matrix` for big and hard choices.
- `second-order-thinking` for high-impact choices.

Source: https://untools.co/hard-choice-model/
