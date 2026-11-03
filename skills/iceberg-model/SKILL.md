---
name: iceberg-model
description: Iceberg model - find why something keeps happening by digging below the visible event to patterns over time, the system structures that drive them, and the mental models behind those structures, then pick high-leverage fixes. Use when the user asks "why does X keep happening?", faces a recurring problem, or wants systemic root causes rather than a quick fix.
---

# Iceberg Model

Turn the user's event or problem into four levels (events, patterns, structures, mental models) and interventions ranked by leverage.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct model (one round, max 3 questions). Typical gaps: how often it happens, what has been tried.

## Steps

1. **Events: what is happening now?** Describe the visible event in concrete terms.
2. **Patterns: what trends or repeats over time?** Describe the trend or recurrence. If the input has no history, say what history to check.
3. **Structures: what drives these patterns?** Identify the rules, incentives, processes, deadlines, org design, tools, information flows, and feedback loops that produce the pattern. Name how patterns connect.
4. **Mental models: what beliefs hold the structure in place?** Identify the values, assumptions, and beliefs of the people involved ("shipping on time matters more than quality", "it's not my place to push back"). Mark which are inferred and how to verify them (interviews, retros, surveys).
   Done when each level explains the level above it.
5. **Interventions.** For each level, propose one action. Leverage rises with depth: event fixes react, pattern fixes anticipate, structure fixes redesign, mental-model fixes transform. Recommend the deepest action that is feasible now, plus a quick event fix if the event needs one.

## Output

```markdown
## Iceberg
| Level | What we see | Evidence / to verify |
|---|---|---|
| Events | <...> | |
| Patterns | <...> | |
| Structures | <...> | |
| Mental models | <...> | |

## Interventions
| Level | Action | Leverage |
|---|---|---|
| Events | <react> | low |
| Patterns | <anticipate> | |
| Structures | <redesign> | |
| Mental models | <transform> | high |

## Recommendation
<...>
```

## Related

- `connection-circles` to map the structures and their feedback loops.
- `ishikawa-diagram` for a single problem's causes.

Source: https://untools.co/iceberg-model/
