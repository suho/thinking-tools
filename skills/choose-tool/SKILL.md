---
name: choose-tool
description: Thinking-tool chooser - pick the right untools.co thinking tool (or a short chain of tools) for the user's problem, decision, system, or message, then apply it. Use when the user wants to think something through, asks which framework or mental model fits, or shares a situation without naming a tool.
---

# Choose a Thinking Tool

Match the user's situation to the thinking tool that fits it best, explain the match in one line, then run that tool on the user's context.

## Steps

1. **Read the situation.** Use the user's message, conversation, and files. Identify what they need to produce. Done when you can state the need in one sentence.
2. **Pick the need category:**
   - **Solve a problem:** something is wrong, unclear, or needs a solution.
   - **Make a decision:** choose between options, prioritize, or respond.
   - **Understand a system:** see how parts interact or why something recurs.
   - **Communicate:** write or say something so others understand or act.
   If two categories fit, pick the one that matches the output the user asked for. If nothing in the context points to a category, ask one question: "Is your goal to fix something, choose something, understand how something works, or get a message across?"
3. **Pick the tool.** In that category, find the prompt question that best matches the situation in the table below. Choose one primary tool. Add a second tool only when the chain table shows the first tool's output feeds it directly.
4. **Announce.** Write one line: the tool, and why it fits this situation. Add up to two alternatives in one line, only if they are close fits.
5. **Run.** Invoke the chosen skill with the Skill tool (`thinking-tools:<skill-name>`) and apply it to the user's context. If the user asked only for a recommendation, stop after step 4.

## Tool map

### Solve a problem

| Prompt question | Skill |
|---|---|
| Is this the right problem, or only a symptom or a narrow framing of it? | `abstraction-laddering` |
| Can I break this big problem into smaller parts? | `issue-trees` |
| What are the root causes of this problem? | `ishikawa-diagram` |
| Does this need a new solution that ignores how it is usually done? | `first-principles` |
| What could make this fail? | `inversion` |
| How do I find a creative solution and a plan for a defined problem? | `productive-thinking-model` |
| How do I generate many solution concepts for a multi-dimensional problem? | `zwicky-box` |
| How do we resolve a conflict where neither side's proposal works? | `conflict-resolution-diagram` |

### Make a decision

| Prompt question | Skill |
|---|---|
| What kind of decision is this, and how much effort does it deserve? | `hard-choice-model` |
| Which of these options is best? | `decision-matrix` |
| What happens later if we choose this? | `second-order-thinking` |
| Is this judgment based on facts or on assumptions? | `ladder-of-inference` |
| Have I looked at this from every angle? | `six-thinking-hats` |
| Should we follow a known practice, analyze, experiment, or act now? | `cynefin-framework` |
| How do I decide fast with incomplete data in a changing situation? | `ooda-loop` |
| Which tasks need attention first, by urgency and importance? | `eisenhower-matrix` |
| Which items give the best return on effort? | `impact-effort-matrix` |
| Should we build this fast or build it right? | `confidence-determines-speed-vs-quality` |

### Understand a system

| Prompt question | Skill |
|---|---|
| What causes what in this system? | `connection-circles` |
| Why does this keep happening? | `iceberg-model` |
| How do the parts of this concept or domain relate? | `concept-map` |
| Why does this grow or decline faster and faster? | `reinforcing-feedback-loop` |
| Why does this plateau, snap back, or resist change? | `balancing-feedback-loop` |

### Communicate

| Prompt question | Skill |
|---|---|
| How do I get my point across quickly and clearly? | `minto-pyramid` |
| How do I give feedback without judgment? | `situation-behavior-impact` |

## Chains

Use a chain only when the user's need spans both steps.

| First | Then | When |
|---|---|---|
| `hard-choice-model` | `decision-matrix` | A big or hard choice between comparable factors |
| `abstraction-laddering` | `issue-trees` or `first-principles` | Reframe first, then break down or rebuild |
| `issue-trees` | `ishikawa-diagram` | A priority branch needs root-cause analysis |
| `connection-circles` | `reinforcing-feedback-loop` / `balancing-feedback-loop` | A loop found on the map needs deeper analysis |
| `iceberg-model` | `connection-circles` | Structures need mapping |
| `zwicky-box` or `productive-thinking-model` | `decision-matrix` | Many concepts need a final pick |
| `decision-matrix` | `second-order-thinking` | The winner needs a long-term check |
| `ladder-of-inference` | `situation-behavior-impact` | Check the judgment, then give the feedback |
| any tool | `minto-pyramid` | The result must be shared with others |

Source: https://untools.co/thinking-tools-guide/
