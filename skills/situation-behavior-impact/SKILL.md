---
name: situation-behavior-impact
description: Situation-Behavior-Impact (SBI) - turn a reaction to someone's behavior into clear, non-judgmental feedback - the situation, the observed behavior, its impact, and a question about intent. Use when the user wants to give or prepare feedback (negative or positive) to a colleague, report, manager, or peer, or says "SBI".
---

# Situation-Behavior-Impact

Turn the user's account of what happened into feedback that describes facts instead of judgments, so the recipient can reflect instead of defend.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block correct feedback (one round, max 3 questions). Typical gaps: the specific occasion, what the person actually said or did, who was affected.

## Steps

1. **Situation.** Name the specific time and place where the behavior occurred ("In Tuesday's sprint review, ..."). Done when the recipient can recall the exact moment.
2. **Behavior.** Describe only what the person did or said, as a camera would record it. Remove every interpretation, label, motive, or adjective about character ("rude", "lazy", "careless"). Done when each word describes an observable action.
3. **Impact.** State the effect of the behavior: what the user thought or felt and why, and any effect on others, the team, or the work. Use "I" statements for personal impact. Done when the link from behavior to impact is explicit.
4. **Intent question.** Write one open question that invites the person's reason ("What was your thinking there?"). The goal is to expose the gap between intent and impact.
5. **Reflection prompt.** Write one line that invites the person to think about what to do differently next time.
6. **Judgment check.** Reread the draft. List each judgment you removed from the user's original wording and what replaced it.

## Output

```markdown
## Feedback
**Situation:** <...>
**Behavior:** <...>
**Impact:** <...>
**Intent:** <open question>
**Next time:** <reflection prompt>

## Script
<the feedback as natural spoken or written words, 3-6 sentences>

## Judgments removed
- "<original wording>" -> "<observable fact>"
```

## Related

- `ladder-of-inference` if the user may be jumping to conclusions about the person.
- `minto-pyramid` for written messages that are not feedback.

Source: https://untools.co/situation-behavior-impact/ (SBI is a trademark of the Center for Creative Leadership)
