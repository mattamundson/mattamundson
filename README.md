### Hi, I'm Matt.

I build production systems where the orchestration *is* the product — multi-agent LLM pipelines, domain-expert Claude Code plugins, and autonomous trading infrastructure. Most of my recent work has been turning tribal knowledge into inspectable, eval-scored, agent-addressable assets.

**Current focus** — autonomous futures trading system (paper-validated on MCL, MNQ, MES) with a 7-layer regime classifier, Kelly-sized position management, and a full Sonnet-executor / Opus-grader evaluation harness.

### Featured public work

| Repo | What it is | Live |
|---|---|---|
| [**ralph-orchestrator**](https://github.com/mattamundson/ralph-orchestrator) | Reusable primitives for multi-agent LLM systems — circuit breakers, token tracking, session memory, health metrics, and a drop-in FastAPI router. Extracted from a working production deployment. 50/50 tests, CI green on Python 3.10/3.11/3.12. | [pages](https://mattamundson.github.io/ralph-orchestrator/) |
| [**gms-intelligence-plugin**](https://github.com/mattamundson/gms-intelligence-plugin) | A Claude Code plugin that encodes a metal-roofing manufacturer's domain knowledge as 7 eval-scored skills (pricing, SKUs, material estimation, colors, production, suppliers, inventory). 30/36 pricing-engine assertions pass (83%). Template for domain-expert plugins in any vertical. | [eval reports](https://mattamundson.github.io/gms-intelligence-plugin/) |

### What I care about

- **Eval-driven development** — every skill, every model call, every strategy has a failing test first.
- **Progressive disclosure** — skills load only when relevant; references load only when deep-linked. Context is the scarcest resource in an agent system.
- **Safety rails inside the artifact, not around it** — if a skill can move money or data, its first section says so. Preview, diff, confirm.
- **Extraction over invention** — the best libraries are the ones carved out of working code, not designed in the abstract.

### How to reach me

GitHub issues on any of my repos; LinkedIn; [mattamundson@greenfieldmetalsales.com](mailto:mattamundson@greenfieldmetalsales.com).
