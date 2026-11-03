---
name: ladder-of-inference
description: Ladder of inference (Chris Argyris) - check a conclusion, belief, or planned action for jumps in reasoning by walking down the ladder (action, belief, conclusion, assumption, interpretation, selected data, available data) and back up on the facts. Use when the user may be jumping to conclusions about a person, situation, or data, or before acting on a judgment.
---

# Ladder of Inference

Turn the user's conclusion or planned action into an explicit reasoning chain, expose the leaps, and rebuild a conclusion grounded in the available data.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct analysis (one round, max 3 questions). The minimum input is the conclusion or action and what led to it.

## The ladder (bottom to top)

1. **Available data:** everything observable.
2. **Selected data:** what was noticed.
3. **Interpretations:** the meaning given to it.
4. **Assumptions:** what was taken as true from that meaning.
5. **Conclusions:** what was decided is the case.
6. **Beliefs:** what is now held about the world or person.
7. **Actions:** what is about to be done.

## Steps

1. **Locate.** Identify the rung the user is on now (usually actions or conclusions).
2. **Walk down.** For each rung from there to the bottom, answer its question from the user's context:
   - Actions: why is this the right action? What are alternatives?
   - Beliefs: what beliefs drive this? What conclusions support them?
   - Conclusions: why this conclusion? What assumptions does it rest on?
   - Assumptions: are they valid? Why assume them?
   - Interpretations: what else could the data mean? Give 2-3 alternative readings.
   - Selected data: what was ignored? What other sources exist? Who has not been asked?
   Done when every rung has an answer and each leap (a step that does not follow from the rung below) is marked.
3. **Gather.** List the missing data and the cheapest way to get it (often: ask the person).
4. **Walk up.** Rebuild the reasoning from the full data, rung by rung, and state the revised conclusion and action. If data is missing, the action is to get it first.

## Output

```markdown
## Original chain
data -> <selected> -> <interpretation> -> <assumption> -> <conclusion> -> <belief> -> <action>

## Walk down
| Rung | Question | Answer | Leap? |
|---|---|---|---|

## Alternative interpretations
- <...>

## Missing data
- <data> - <how to get it>

## Rebuilt reasoning
<revised conclusion and action>
```

## Related

- `situation-behavior-impact` to give feedback based on facts.
- `six-thinking-hats` (white hat) to separate data from opinion.

Source: https://untools.co/ladder-of-inference/
