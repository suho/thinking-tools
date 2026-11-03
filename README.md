# thinking-tools

Claude Code plugin. It turns the thinking tools from [untools.co](https://untools.co/) into skills. Each skill applies one tool to your idea, topic, or context and gives the tool's output (a pyramid, a matrix, a tree, a map, a plan).

## Install

```bash
claude plugin marketplace add suho/thinking-tools
```

```bash
claude plugin install thinking-tools@thinking-tools
```

Or in a Claude Code session: `/plugin marketplace add suho/thinking-tools`, then `/plugin install thinking-tools@thinking-tools`.

Local test without install:

```bash
claude --plugin-dir /path/to/thinking-tools
```

## Use

- Let Claude pick: describe your situation, or run `/thinking-tools:choose-tool <situation>`.
- Pick a tool yourself: `/thinking-tools:<skill> <context>`, for example `/thinking-tools:minto-pyramid rewrite this update for my VP: ...`.
- Claude also loads a skill on its own when your request matches it.

## Skills

| Category | Skill | Use it to |
|---|---|---|
| Guide | `choose-tool` | Pick the right tool and apply it |
| Problem solving | `abstraction-laddering` | Reframe the problem |
| | `issue-trees` | Break a problem into a MECE tree |
| | `ishikawa-diagram` | Find root causes by category |
| | `first-principles` | Rebuild a solution from basic truths |
| | `inversion` | Find failure modes, run a pre-mortem |
| | `productive-thinking-model` | Solve creatively, end with an action plan |
| | `zwicky-box` | Generate solution concepts by combination |
| | `conflict-resolution-diagram` | Find a win-win in a conflict |
| Decision making | `hard-choice-model` | Classify a decision and its effort |
| | `decision-matrix` | Pick the best option by weighted factors |
| | `second-order-thinking` | Trace long-term consequences |
| | `ladder-of-inference` | Check for jumps to conclusions |
| | `six-thinking-hats` | Look from six perspectives |
| | `cynefin-framework` | Match the response to the situation type |
| | `ooda-loop` | Decide fast with incomplete data |
| | `eisenhower-matrix` | Prioritize by urgency and importance |
| | `impact-effort-matrix` | Prioritize by return on effort |
| | `confidence-determines-speed-vs-quality` | Choose speed or quality |
| Systems thinking | `connection-circles` | Map causes, effects, and feedback loops |
| | `iceberg-model` | Find why something keeps happening |
| | `concept-map` | Map how a concept or domain fits together |
| | `reinforcing-feedback-loop` | Analyze a vicious or virtuous cycle |
| | `balancing-feedback-loop` | Analyze a plateau or resistance to change |
| Communication | `minto-pyramid` | Lead with the conclusion |
| | `situation-behavior-impact` | Give feedback without judgment |

## Credits

The tools and their selection guide come from [untools.co](https://untools.co/) by Adam Amran. Skill text is a rewrite for Claude, not a copy. Each skill links to its source page. This project is not affiliated with Untools. SBI is a trademark of the Center for Creative Leadership.

## License

[MIT](LICENSE)
