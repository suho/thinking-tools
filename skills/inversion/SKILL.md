---
name: inversion
description: Inversion and pre-mortem - look at a problem, plan, or decision from the opposite side - what would make it fail or be the worst solution - then derive a better plan that avoids those failure modes. Use when the user only considers ideal scenarios, works on a high-stakes plan, or asks "what could go wrong?", "pre-mortem", "invert".
---

# Inversion

Turn the user's goal, plan, or decision into a list of failure modes and a revised plan that avoids them.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct analysis (one round, max 3 questions). The minimum input is a goal, plan, or decision.

## Steps

1. **State the goal** in one sentence: what success looks like.
2. **Invert.** Ask "what would guarantee failure?" or "what is the worst solution here?" List 8-15 concrete ways to fail. Cover people, process, timing, resources, assumptions, and external factors. Be specific to the user's situation, not generic.
3. **Pre-mortem.** Imagine it is some months later and the effort has failed. Write the 3 most plausible stories of why. Done when each story names a cause the plan does not yet address.
4. **Explain.** For each failure mode, write why it causes failure. Rate likelihood and severity (high/medium/low).
5. **Reverse.** For each high-likelihood or high-severity failure, write the safeguard: the action, rule, or design choice that prevents it, or the early signal that shows it is happening.
6. **Revise.** Rewrite the plan or decision with the safeguards in it.

## Output

```markdown
## Goal
<...>

## Ways to fail
| # | Failure mode | Why it fails | Likelihood | Severity | Safeguard / early signal |
|---|---|---|---|---|---|

## Pre-mortem
1. <failure story>

## Revised plan
<plan with safeguards>
```

## Related

- `second-order-thinking` for long-term consequences of a decision.
- `six-thinking-hats` (black hat) for a broader review.

Source: https://untools.co/inversion/
