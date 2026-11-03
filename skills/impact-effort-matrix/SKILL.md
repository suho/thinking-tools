---
name: impact-effort-matrix
description: Impact-effort matrix - prioritize tasks, features, or projects by impact versus effort into quick wins, major projects, fill-ins, and thankless tasks. Use when the user has a backlog, roadmap, idea list, or improvement list and wants the best return on effort, or asks "what should we do first?", "quick wins", "value vs effort".
---

# Impact-Effort Matrix

Turn the user's list of items into four quadrants and an execution order based on return on effort.

## Input

Work from the user's context (backlogs, roadmaps, notes). Infer what you can and state assumptions. Ask only for gaps that block a correct sort (one round, max 3 questions). Typical gaps: the goal that defines impact, team size or capacity that defines effort.

## Steps

1. **Define impact.** State the goal that impact is measured against (revenue, user value, risk reduction, learning).
2. **Rate.** For each item, rate impact and effort as high or low (or 1-5) with a short reason. Be realistic: do not overstate impact or understate effort. Mark ratings that are guesses and who could give a better estimate. Done when every item has both ratings.
3. **Place.**
   - **Quick wins (high impact, low effort):** do first.
   - **Major projects (high impact, high effort):** plan and resource after quick wins.
   - **Fill-ins (low impact, low effort):** do when there is spare capacity.
   - **Thankless tasks (low impact, high effort):** avoid, simplify, or cut.
4. **Order.** Give the sequence: quick wins by impact, then major projects with a first milestone each.
5. **Review point.** Say when to re-rate (e.g. after the quick wins ship or each sprint).

## Output

```markdown
## Impact measured by
<goal>

## Ratings
| Item | Impact | Effort | Reason | Guess? |
|---|---|---|---|---|

## Matrix
| | Low effort | High effort |
|---|---|---|
| **High impact** | **Quick wins:** <...> | **Major projects:** <...> |
| **Low impact** | **Fill-ins:** <...> | **Thankless:** <...> |

## Order
1. <...>

## Review
<when and what to re-rate>
```

## Related

- `eisenhower-matrix` to add urgency.
- `decision-matrix` when more than two factors matter.

Source: https://untools.co/impact-effort-matrix/
