---
name: eisenhower-matrix
description: Eisenhower matrix - prioritize tasks by importance and urgency into do, schedule, delegate, and drop quadrants. Use when the user has a to-do list, backlog, or busy week and asks what to work on now, what to cut or delegate, or feels busy without progress on long-term goals.
---

# Eisenhower Matrix

Turn the user's tasks into four quadrants and an ordered plan of what to do, schedule, delegate, and drop.

## Input

Work from the user's context (task lists, calendars, notes, issues). Infer what you can and state assumptions. Ask only for gaps that block a correct sort (one round, max 3 questions). Typical gaps: the user's goals (to judge importance), deadlines (to judge urgency), whether delegation is possible.

## Rules

- **Urgent:** has a near deadline or needs a timely reaction; delay causes harm soon.
- **Important:** moves the user's long-term goals or key projects forward.
- Priority order: Do, then Schedule, then Delegate, then Drop. Important-but-not-urgent comes before urgent-but-not-important.

## Steps

1. **Goals.** State the user's goals for the period, from context or as an assumption. Importance is judged against them.
2. **Sort.** Place each task in one quadrant with a few-word reason. Done when every task is placed.
   - **Do (important, urgent):** do it today.
   - **Schedule (important, not urgent):** put it on the calendar, ideally as protected deep-work time.
   - **Delegate (urgent, not important):** hand it to someone; if no one can take it, schedule it after the Schedule items.
   - **Drop (neither):** do not do it.
3. **Challenge.** Check for false urgency (other people's priorities, notifications) and for important work hidden in no quadrant. Point out if Do is overloaded and the cause.
4. **Plan.** Give the order for today, the time slots to block for Schedule items, delegation targets, and the drop list.

## Output

```markdown
## Goals
<...>

## Matrix
| | Urgent | Not urgent |
|---|---|---|
| **Important** | **Do:** <tasks> | **Schedule:** <tasks> |
| **Not important** | **Delegate:** <tasks> | **Drop:** <tasks> |

## Plan
1. Today: <ordered Do items>
2. Block time for: <Schedule items and when>
3. Delegate: <item -> person>
4. Drop: <items>

## Notes
<false urgency, overload, missing important work>
```

## Related

- `impact-effort-matrix` to order tasks inside a quadrant.
- `hard-choice-model` for single decisions, not lists.

Source: https://untools.co/eisenhower-matrix/
