---
name: zwicky-box
description: Zwicky box (morphological analysis) - generate many whole solutions to a multi-dimensional problem by splitting it into independent attributes, listing options per attribute, and combining one option from each. Use when the user wants systematic idea generation, product or feature concepts, design variations, or "out of the box" options beyond normal brainstorming, or says "morphological box".
---

# Zwicky Box

Turn the user's problem into a table of independent attributes and options, then into distinct whole-solution combinations.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct box (one round, max 3 questions). The minimum input is the problem or thing to design.

## Steps

1. **Define the problem** in one sentence.
2. **Attributes.** Choose 4-7 attributes (parts, functions, properties) that define any solution. They must be logically independent, so any option of one can combine with any option of another. Tip: list the parts of a known example and derive attributes from them. Done when no attribute depends on another.
3. **Options.** For each attribute, list 4-6 options. Include unusual ones; do not filter for feasibility yet.
4. **Combine.** Build 5-8 combinations by picking one option per attribute. Mix strategies: one conventional, several deliberately odd, one random. Describe each as a short concept, not just a list of picks.
5. **Evaluate.** Mark the 2-3 most promising concepts, say why, and name what to refine or test.

## Output

```markdown
## Problem
<...>

## Zwicky box
| <Attribute 1> | <Attribute 2> | <Attribute 3> | ... |
|---|---|---|---|
| <option> | <option> | <option> | |
| ... | | | |

## Combinations
1. **<name>:** <A1 option> + <A2 option> + ... - <one-line concept>
...

## Most promising
- <combination> - <why> - <next step to test>
```

## Related

- `decision-matrix` to pick among the concepts.
- `first-principles` to question the attributes themselves.

Source: https://untools.co/zwicky-box/
