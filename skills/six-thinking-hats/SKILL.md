---
name: six-thinking-hats
description: Six Thinking Hats (Edward de Bono) - examine a decision, idea, or problem through six perspectives - white (facts), red (feelings), black (risks), yellow (benefits), green (ideas), blue (process) - and synthesize a balanced next step. Use when the user wants to look at something from all angles, run a balanced team discussion or meeting, or avoid blind spots.
---

# Six Thinking Hats

Turn the user's decision or idea into a structured view from six perspectives and a synthesized next step.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct analysis (one round, max 3 questions). The minimum input is the decision, idea, or problem.

## Hats

- **Blue (process):** frames the question, sets the order, and summarizes.
- **White (facts):** data, trends, what is known and unknown. No opinions.
- **Red (feelings):** gut reactions and intuition, of the user and of the people affected. No justification needed.
- **Black (caution):** risks, weaknesses, worst cases, what might not work.
- **Yellow (optimism):** benefits, opportunities, best realistic case.
- **Green (creativity):** new options, alternatives, ways to fix black-hat problems.

## Steps

1. **Blue - frame.** State the question being decided and the order of hats. Default order: white, yellow, black, green, red, then blue. Adapt the order to the situation and say why.
2. **Each hat.** Write 3-6 specific points per hat, about this situation only. Keep each hat pure: no risks under yellow, no opinions under white. Under white, separate known facts from data still needed. Under green, answer the main black-hat risks. Done when every hat has its points and no point is in the wrong hat.
3. **Blue - synthesize.** Summarize where the hats agree and conflict, and state a next step: decide, test, gather data, or postpone with a reason.
4. **Meeting use (if the user is preparing a group session).** Add a short agenda with time per hat and hat assignments or a whole-group order.

## Output

```markdown
## Question
<...>

## White - facts
- Known: <...>
- Needed: <...>
## Yellow - benefits
## Black - risks
## Green - ideas
## Red - feelings
## Blue - synthesis
<agreements, tensions, next step>
```

## Related

- `inversion` to deepen the black hat.
- `productive-thinking-model` or `first-principles` to deepen the green hat.
- `decision-matrix` to make the final call.

Source: https://untools.co/six-thinking-hats/
