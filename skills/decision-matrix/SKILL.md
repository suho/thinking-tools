---
name: decision-matrix
description: Decision matrix (weighted scoring) - choose the best of several options by scoring each against weighted factors and totaling the scores. Use when the user must pick between 2+ concrete options (tools, vendors, offers, candidates, designs, approaches) based on multiple criteria, or asks "which option is best?", "compare these", "weighted scoring".
---

# Decision Matrix

Turn the user's options and priorities into a weighted score table and a recommendation.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct matrix (one round, max 3 questions). Typical gaps: the options, what matters most. If the user names no factors, propose them from the context and mark them as proposed.

## Steps

1. **Decision.** Write the decision in one sentence.
2. **Options.** List the options. Add "do nothing" or an obvious missing option if it is a realistic choice.
3. **Factors.** List 3-7 factors that matter. Make them independent (no double counting) and phrase each so a higher score is better.
4. **Weights.** Weight each factor 1-5 by importance to this user. Explain each weight in a few words.
5. **Scores.** Score each option per factor 1-5. Base each score on facts from the input or verifiable data; write the reason. Mark scores that are guesses.
6. **Totals.** Multiply score by weight and sum per option. Show the arithmetic.
7. **Sensitivity.** Check if the winner changes when you change the most uncertain weight or score by 1. Say whether the result is robust or close.
8. **Recommend.** Name the winner, the margin, and any reason the numbers miss.

## Output

```markdown
## Decision
<...>

## Matrix
| Option | <Factor 1> (w=5) | <Factor 2> (w=3) | ... | Total |
|---|---|---|---|---|
| A | 4 x 5 = 20 | 2 x 3 = 6 | | 26 |

## Score reasons
- A / <factor>: <reason> (guess?)

## Sensitivity
<robust / close: what flips it>

## Recommendation
<winner and why>
```

## Related

- `hard-choice-model` to check if the decision deserves this effort.
- `second-order-thinking` to check the winner's long-term effects.

Source: https://untools.co/decision-matrix/
