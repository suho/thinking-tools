---
name: confidence-determines-speed-vs-quality
description: Confidence determines speed vs. quality - decide whether to optimize a product, feature, or project for speed or quality from data-based confidence in the problem's importance and the solution's correctness. Use when the user debates shipping fast (MVP, prototype, hack) versus building it right (polish, scale, rigor).
---

# Confidence Determines Speed vs. Quality

Turn the user's product or feature situation into confidence ratings and a speed-versus-quality call with concrete build implications.

## Input

Work from the user's context (research, metrics, customer feedback, specs). Infer what you can and state assumptions. Ask only for gaps that block a correct call (one round, max 3 questions). Typical gap: what evidence exists for the problem and the solution.

## Steps

1. **Problem confidence.** Rate confidence that the problem is important (low / medium / high). List the evidence. Count data (usage, research, revenue, support volume) and discount opinions. Done when each rating cites its evidence or says there is none.
2. **Solution confidence.** Rate confidence that the proposed solution is correct, with evidence, the same way.
3. **Call.**
   - Low problem confidence: **focus on speed.** Build the cheapest thing that tests whether the problem matters.
   - High problem, low solution confidence: **balance speed and quality.** Iterate on solutions quickly, keep the core solid enough to learn from.
   - High problem and high solution confidence: **focus on quality.** Build it right: robust, scalable, polished.
   Confidence is a scale, so place the call on a spectrum and say where.
4. **Implications.** Translate the call into concrete choices: scope, testing, architecture, design polish, rollout, and what is deliberately skipped.
5. **Raise confidence.** Name the cheapest evidence that would move each rating up and change the call.

## Output

```markdown
## Confidence
| | Rating | Evidence |
|---|---|---|
| Problem importance | <low/med/high> | <...> |
| Solution correctness | <low/med/high> | <...> |

## Call
**<speed / balance / quality>** - <position on the spectrum and why>

## Build implications
- Scope: <...>
- Quality bar: <...>
- Skipped on purpose: <...>

## To raise confidence
- <evidence> - <how to get it>
```

## Related

- `impact-effort-matrix` to pick which items to build.
- `ooda-loop` for fast iteration cycles.

Source: https://untools.co/confidence-determines-speed-vs-quality/
