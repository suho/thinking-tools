---
name: ooda-loop
description: OODA loop (John Boyd) - make fast decisions with incomplete data in a changing or competitive situation by cycling observe, orient, decide, act, and feeding results into the next loop. Use when the user must respond quickly to a competitor move, incident, market shift, or fast-moving situation and cannot wait for full information.
---

# OODA Loop

Turn the user's fast-moving situation into one complete loop (observe, orient, decide, act) with a testable decision and the signals that start the next loop.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct loop (one round, max 3 questions); speed matters more than completeness here.

## Steps

1. **Observe.** List what is known now: the situation, wider context, outside information, and feedback from previous actions. Mark how fresh each piece is; stale data is a risk. List the 1-3 unknowns that matter most.
2. **Orient.** Make sense of the observations: what do they mean, what are the options, what does experience suggest, what would others (customers, competitors, the team) see? Challenge the current assumptions and status quo. Done when you have 2-4 options and the assumption each one rests on.
3. **Decide.** Pick one option and write it as a hypothesis: "If we <action>, we expect <result> by <time>." Balance speed with enough thought; prefer reversible moves.
4. **Act.** Write the concrete actions, owners, and the first thing to do in the next 24-48 hours.
5. **Loop.** Define the signals to observe after acting and when to run the next loop. Done when the next loop has a trigger and a date.

## Output

```markdown
## Observe
- <fact> (as of <when>)
- Key unknowns: <...>

## Orient
- Meaning: <...>
- Options:
  1. <option> - rests on <assumption>

## Decide
If we <action>, we expect <result> by <time>.

## Act
| Action | Owner | When |
|---|---|---|

## Next loop
- Signals to watch: <...>
- Re-run: <trigger / date>
```

## Related

- `cynefin-framework` to check if the situation is complex or chaotic.
- `confidence-determines-speed-vs-quality` to set how fast to move.

Source: https://untools.co/ooda-loop/
