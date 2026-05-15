---
title: AI Agents
created: 2026-04-10
updated: 2026-04-30
type: concept
tags: [agent, architecture]
sources: [raw/articles/wikipedia-ai-agent.md, raw/articles/wikipedia-claude.md]
---

# AI Agents

## Source
[Wikipedia: AI agent](https://en.wikipedia.org/wiki/AI_agent) → raw excerpt at [wikipedia-ai-agent.md](../raw/articles/wikipedia-ai-agent.md).

## Definition (verbatim)
> "AI agents (also referred to as compound AI systems or agentic AI) are a class of intelligent agents distinguished by their ability to operate autonomously in complex environments."

> "Agentic AI tools prioritize decision-making over content creation and do not require continuous oversight."

## Attributes (verbatim)
> "AI agents possess several key attributes, including complex goal structures, natural language interfaces, the capacity to act independently of user supervision, and the integration of software tools or planning systems."

## Examples cited (verbatim from Wikipedia AI agent)
- **OpenAI Operator** (web browser agent)
- **Perplexity Comet** (agentic browser)
- **ChatGPT agent**
- **Cursor** (coding agent)
- **Devin AI** (software development agent)

## General-purpose autonomous agents (sourced separately)
- **[[Manus]]** — Butterfly Effect (Singapore/China origin); launched 2025-03-06; Meta acquisition (Dec 2025) blocked by China NDRC 2026-04-27. See [Wikipedia: Manus](https://en.wikipedia.org/wiki/Manus_(AI_agent)).
- **[[OpenClaw]]** — Peter Steinberger, MIT License; originally Clawdbot (Nov 2025); 247K GitHub stars by Mar 2026; named in reference to Anthropic's Claude. See [Wikipedia: OpenClaw](https://en.wikipedia.org/wiki/OpenClaw).
- **[[Hermes Agent]]** — Nous Research, MIT License; "self-improving" with persistent memory and 11+ LLM providers; v0.13.0 released 2026-05-07. See [hermes-agent.nousresearch.com](https://hermes-agent.nousresearch.com/).

## Capabilities (verbatim)
> "Memory systems for remembering previous user-agent interactions and orchestration software for organizing agent components."

Patterns named: "prompt chaining," "routing," "parallelization."

## Computer Use (verbatim, [Wikipedia: Claude](https://en.wikipedia.org/wiki/Claude_(language_model)))
> "In October 2024, Anthropic released the 'computer use' feature, allowing Claude to attempt to navigate computers by interpreting screen content."

## ReAct paper (verbatim, [arXiv:2210.03629](https://arxiv.org/abs/2210.03629))
Raw: [arxiv-react.md](../raw/papers/arxiv-react.md). Submitted **2022-10-06** by Yao, Zhao, Yu, Du, Shafran, Narasimhan, Cao.

> "We explore the use of LLMs to generate both reasoning traces and task-specific actions in an interleaved manner, allowing for greater synergy between the two: reasoning traces help the model induce, track, and update action plans as well as handle exceptions, while actions allow it to interface with external sources, such as knowledge bases or environments, to gather additional information."

## Toolformer paper (verbatim, [arXiv:2302.04761](https://arxiv.org/abs/2302.04761))
Raw: [arxiv-toolformer.md](../raw/papers/arxiv-toolformer.md). Submitted **2023-02-09**.

> "We introduce Toolformer, a model trained to decide which APIs to call, when to call them, what arguments to pass, and how to best incorporate the results into future token prediction. This is done in a self-supervised way, requiring nothing more than a handful of demonstrations for each API."

## Notes on what was removed
The previous version of this page contained:

- A diagrammatic agent architecture (LLM brain + memory + tools + environment loop)
- Specific frameworks (ReAct, Chain-of-Thought, Tree of Thoughts) — not in saved excerpts
- Frameworks named (LangChain, CrewAI, AutoGPT) — only some confirmed in Wikipedia AI agent (which doesn't name AutoGPT)
- "Project Mariner" / "Jules" (Google) — not in saved excerpts
- SWE-bench progress numbers (49% → 70.3% claim) — not in saved excerpts
- "Human baseline ~13%" for SWE-bench — not in saved excerpts
- Specific safety concern list (prompt injection, irreversible actions, autonomy escalation) — not in saved excerpts (true topics, but should be sourced separately)

These will be re-added with citations after fetching:
- https://arxiv.org/abs/2210.03629 (ReAct paper)
- https://www.swebench.com
- https://www.anthropic.com/news/3-5-models-and-computer-use
- https://arxiv.org/abs/2302.04761 (Toolformer)

## Related Pages
[[Claude 3]] | [[Claude 4]] | [[OpenAI o1]] | [[Reasoning Models]] | [[Manus]] | [[OpenClaw]] | [[Hermes Agent]] | [[Cursor]]

## Sources (saved excerpts in raw/)
- [Wikipedia: AI agent](https://en.wikipedia.org/wiki/AI_agent) → [raw/articles/wikipedia-ai-agent.md](../raw/articles/wikipedia-ai-agent.md)
- [Wikipedia: Claude (language model)](https://en.wikipedia.org/wiki/Claude_(language_model)) → [raw/articles/wikipedia-claude.md](../raw/articles/wikipedia-claude.md)
- [Wikipedia: Manus](https://en.wikipedia.org/wiki/Manus_(AI_agent)) → [raw/articles/wikipedia-manus.md](../raw/articles/wikipedia-manus.md)
- [Wikipedia: OpenClaw](https://en.wikipedia.org/wiki/OpenClaw) → [raw/articles/wikipedia-openclaw.md](../raw/articles/wikipedia-openclaw.md)
- [Hermes Agent (Nous Research)](https://hermes-agent.nousresearch.com/) → [raw/articles/nous-research-hermes-agent.md](../raw/articles/nous-research-hermes-agent.md)
