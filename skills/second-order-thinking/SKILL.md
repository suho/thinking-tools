---
name: second-order-thinking
description: Second-order thinking - trace the consequences of a decision beyond the immediate effects by repeatedly asking "and then what?" and checking the 10 minutes / 10 months / 10 years horizons. Use when the user weighs a decision, policy, or change and wants its long-term or knock-on effects, hidden costs, or unintended consequences.
---

# Second-Order Thinking

Turn the user's decision into consequence chains across orders and time horizons, and a verdict on whether the long-term picture still supports it.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct analysis (one round, max 3 questions). The minimum input is one decision or option. For several options, analyze each.

## Steps

1. **Decision.** State the decision and the main reason for it (the first-order win).
2. **First order.** List 3-6 immediate effects. Include costs, not only benefits.
3. **And then what?** For each first-order effect, ask "and then what?" 2-3 times. Write each chain as `effect -> consequence -> consequence`. Cover effects on the user, other people, incentives, and the system around them. Done when every chain reaches a consequence that the first-order view missed or confirms there is none.
4. **Time horizons.** Summarize the consequences at 10 minutes, 10 months, and 10 years (or the scale that fits: days / quarters / years).
5. **Weigh.** Mark which chains flip a first-order win into a loss or a cost into a gain.
6. **Verdict.** Say if the decision holds, and what to change or watch to keep the long-term effects acceptable.

## Output

```markdown
## Decision
<...> - first-order win: <...>

## Consequence chains
- <first-order effect> -> <second order> -> <third order> (+/-)

## Time horizons
| 10 minutes | 10 months | 10 years |
|---|---|---|

## Flips
- <chain that changes the picture>

## Verdict
<hold / change / reject> - <mitigations and signals to watch>
```

## Related

- `inversion` for failure modes.
- `connection-circles` when consequences loop back into causes.

Source: https://untools.co/second-order-thinking/
