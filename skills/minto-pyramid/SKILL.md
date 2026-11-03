---
name: minto-pyramid
description: Minto Pyramid (BLUF) - restructure a message, email, update, report, proposal, or pitch top-down - conclusion first, then key arguments, then supporting evidence. Use when the user wants to write or rewrite communication so busy readers get the point fast, or says "Minto", "pyramid principle", "BLUF", "bottom line up front".
---

# Minto Pyramid

Turn the user's idea, draft, or notes into a top-down message: one conclusion, the key arguments that justify it, and the evidence that makes each argument credible.

## Input

Work from the user's context (draft, notes, data, conversation, files). Infer what you can and state assumptions. Ask only for gaps that block a correct message (one round, max 3 questions). Typical gaps: the audience, the action you want from them, the channel (email, Slack, doc, slide).

## Steps

1. **Find the conclusion.** Write the single takeaway, recommendation, or ask in one sentence. If the input holds no clear conclusion, derive the strongest one the material supports and flag it. Done when one sentence answers "what must the reader know or do?"
2. **Group the key arguments.** Collect every reason in the input. Merge overlaps and group them into 2-5 arguments. Each argument answers "why?" for the conclusion. Order them by weight for this audience. Done when no argument overlaps another and together they fully justify the conclusion.
3. **Attach evidence.** Under each argument, put the facts, numbers, results, or examples that support it. Mark any argument that has no evidence as a gap. Done when every argument has evidence or a marked gap.
4. **Fit to the audience.** Drop the evidence layer if the arguments alone convince this audience. Keep it when the conclusion needs proof before people act.
5. **Write the message.** Use the channel's form. The first line carries the conclusion. Do not build up to it.

## Output

```markdown
## Pyramid
- **Conclusion:** <one sentence>
  - **Argument 1:** <summary>
    - <evidence>
  - **Argument 2:** <summary>
    - <evidence>
  - ...

## Message
<the final message, ready to send, conclusion in the first line>

## Gaps
- <missing evidence or assumptions to verify, if any>
```

## Related

- `situation-behavior-impact` for feedback messages.
- `issue-trees` to build a MECE argument set for a complex case.

Source: https://untools.co/minto-pyramid/
