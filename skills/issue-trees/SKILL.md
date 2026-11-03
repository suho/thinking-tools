---
name: issue-trees
description: Issue trees - break a big problem into a MECE tree of smaller parts - a problem tree ("why?") to find causes, then a solution tree ("how?") for the parts that matter most. Use when the user wants to decompose, structure, or "divide and conquer" a complex problem, find where to start, or says "issue tree", "MECE", "logic tree".
---

# Issue Trees

Turn the user's problem into a MECE problem tree, a priority branch, and a solution tree for that branch.

## Input

Work from the user's context. Infer what you can and state assumptions. Ask only for gaps that block a correct tree (one round, max 3 questions). The minimum input is one problem. Data about the problem helps you prioritize.

## Steps

1. **Root.** Write the problem as one specific statement at the root.
2. **Problem tree.** Ask "why could this happen?" and split the root into 2-4 branches. Split each branch again, 2-4 levels deep. Keep each level MECE:
   - **Mutually exclusive:** no two branches overlap.
   - **Collectively exhaustive:** together they cover every possible cause.
   Prefer clean logical splits (e.g. "don't know about it" vs "know but don't use it"). Stay at category level; do not drop into narrow hypotheses. Done when every level passes the MECE check.
3. **Prioritize.** Apply 80/20: mark the 1-3 branches most likely to drive most of the problem. Base this on data in the input; where you have none, say what data would decide it.
4. **Solution tree.** For each priority branch, ask "how might we fix this?" Split into solution categories, then 2-4 concrete ideas per category.
5. **Next step.** Name the first branch to investigate or solution to try, and how to confirm it.

## Output

```markdown
## Problem tree
- <root problem>
  - <branch A>
    - <sub-branch>
  - <branch B>
    - ...

MECE check: <one line per level>

## Priority
- <branch> - <reason / data needed>

## Solution tree: <priority branch>
- How might we <...>?
  - <category>
    - <idea>

## Next step
<...>
```

## Related

- `ishikawa-diagram` for root causes by category.
- `minto-pyramid` to communicate the result.

Source: https://untools.co/issue-trees/
