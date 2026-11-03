---
name: cynefin-framework
description: Cynefin framework (Dave Snowden) - classify a situation as clear, complicated, complex, chaotic, or disorder, then choose the matching response (sense-categorize-respond, sense-analyze-respond, probe-sense-respond, act-sense-respond). Use when the user asks how to respond to a situation, incident, or problem, whether to plan, analyze, experiment, or act now.
---

# Cynefin Framework

Turn the user's situation into a Cynefin domain, the response pattern for that domain, and concrete next actions.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct classification (one round, max 3 questions). The minimum input is a description of the situation.

## Domains

| Domain | Cause and effect | Knowledge | Response | Practice |
|---|---|---|---|---|
| Clear | Obvious to all | Known knowns | Sense - categorize - respond | Best practice |
| Complicated | Discoverable by analysis or experts | Known unknowns | Sense - analyze - respond | Good practice, experts |
| Complex | Visible only in hindsight | Unknown unknowns | Probe - sense - respond | Safe-to-fail experiments, emergent practice |
| Chaotic | None perceivable | Out of control | Act - sense - respond | Stabilize first, novel practice |
| Disorder | Unknown which domain | - | Break it into parts and classify each | - |

## Steps

1. **Diagnose.** Answer from the context:
   - Are the causes known?
   - Is anyone in control of it right now?
   - How much do we already know?
   - Is specialist expertise required?
2. **Classify.** Pick the domain and give the evidence for it. If parts of the situation sit in different domains, split it and classify each part. Done when each part has one domain and a reason.
3. **Respond.** For each part, write concrete actions in the domain's pattern:
   - Clear: the best practice to apply.
   - Complicated: the analysis to run and who the experts are.
   - Complex: 2-4 small, safe-to-fail experiments with signals to watch, aiming to learn enough to move it to complicated.
   - Chaotic: the immediate action to stabilize, then how to assess and move it to complex.
4. **Watch for drift.** Name the signs that the situation is moving to another domain (for example, complacency pushing clear toward chaotic).

## Output

```markdown
## Situation
<...>

## Diagnosis
- Causes known: <...>
- Under control: <...>
- Knowledge: <...>
- Expertise needed: <...>

## Domain
**<domain>** - <evidence>  (or a table per part)

## Response: <pattern>
1. <action>

## Drift signals
- <...>
```

## Related

- `ooda-loop` for fast cycles in complex or chaotic situations.
- `issue-trees` to split a disorder situation into parts.

Source: https://untools.co/cynefin-framework/
