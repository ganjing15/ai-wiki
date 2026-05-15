---
title: Claude 3 (Historical)
created: 2026-04-10
updated: 2026-04-30
type: entity
tags: [model, benchmark, alignment]
sources: [raw/articles/wikipedia-claude.md]
---

> ⚠️ **Historical page.** The current Claude generation is [[Claude 4]] (Opus 4.7 / Sonnet 4.6 / Haiku 4.5 active per [Wikipedia](https://en.wikipedia.org/wiki/Claude_(language_model)), 2026-04-30). This page covers the Claude 1–3.7 generations.

# Claude 3 (and earlier)

## Generation timeline (per Wikipedia Claude infobox)
Source: [Wikipedia: Claude (language model)](https://en.wikipedia.org/wiki/Claude_(language_model)) → raw excerpt at [wikipedia-claude.md](../raw/articles/wikipedia-claude.md).

| Model | Release date | Wikipedia status |
|-------|--------------|------------------|
| Claude (1) | 2023-03-14 | Discontinued |
| Claude 2 | 2023-07-11 | Discontinued |
| Claude 2.1 | 2023-11-21 | Discontinued |
| Claude 3 Opus | 2024-03-04 | Retired |
| Claude 3.5 Sonnet | 2024-06-20 | Discontinued |
| Claude 3.7 Sonnet | 2025-02-24 | Discontinued |

## Constitutional AI (verbatim, Wikipedia Claude)
> "The constitution is a document used for training Claude to be harmless and helpful without relying on extensive or expensive human feedback."

## Computer Use (verbatim, Wikipedia Claude)
> "In October 2024, Anthropic released the 'computer use' feature, allowing Claude to attempt to navigate computers by interpreting screen content."

## Anthropic announcement posts — verbatim excerpts

### Claude 3 family (announcement 2024-03-04, [anthropic.com/news/claude-3-family](https://www.anthropic.com/news/claude-3-family))
Raw: [anthropic-claude-3-family.md](../raw/articles/anthropic-claude-3-family.md).
- **Haiku**: "fastest, most compact model for near-instant responsiveness."
- **Sonnet**: "strikes the ideal balance between intelligence and speed—particularly for enterprise workloads."
- **Opus**: "most intelligent model, with best-in-market performance on highly complex tasks."
- Context: "200K context window upon launch. However, all three models are capable of accepting inputs exceeding 1 million tokens."
- Vision: "can process a wide range of visual formats, including photos, charts, graphs and technical diagrams."

### Claude 3.5 Sonnet (announcement 2024-06-21, [anthropic.com/news/claude-3-5-sonnet](https://www.anthropic.com/news/claude-3-5-sonnet))
Raw: [anthropic-claude-3-5-sonnet.md](../raw/articles/anthropic-claude-3-5-sonnet.md).
- "Our first release in the forthcoming Claude 3.5 model family"
- "Outperforming competitor models and Claude 3 Opus on a wide range of evaluations"
- Speed: "Claude 3.5 Sonnet operates at twice the speed of Claude 3 Opus."
- Internal agentic-coding eval: "solved 64% of problems" vs. Claude 3 Opus at 38%.

### Claude 3.5 Sonnet (new) + Claude 3.5 Haiku + Computer Use (announcement 2024-10-22, [anthropic.com/news/3-5-models-and-computer-use](https://www.anthropic.com/news/3-5-models-and-computer-use))
Raw: [anthropic-claude-3-5-new-computer-use.md](../raw/articles/anthropic-claude-3-5-new-computer-use.md).
- New models announced: "upgraded Claude 3.5 Sonnet" and "Claude 3.5 Haiku"
- Computer Use: "developers can direct Claude to use computers the way people do—by looking at a screen, moving a cursor, clicking buttons, and typing text"
- SWE-bench Verified: "improves performance on SWE-bench Verified from 33.4% to 49.0%, scoring higher than all publicly available models"
- Pre-deployment: "joint pre-deployment testing of the new Claude 3.5 Sonnet model was conducted by the US AI Safety Institute (US AISI) and the UK Safety Institute (UK AISI)"
- Caveat: "Claude's current ability to use computers is imperfect"

### Claude 3.7 Sonnet and Claude Code (announcement 2025-02-24, [anthropic.com/news/claude-3-7-sonnet](https://www.anthropic.com/news/claude-3-7-sonnet))
Raw: [anthropic-claude-3-7-sonnet.md](../raw/articles/anthropic-claude-3-7-sonnet.md).
- "Claude 3.7 Sonnet can produce near-instant responses or extended, step-by-step thinking that is made visible to the user"
- "Claude 3.7 Sonnet is both an ordinary LLM and a reasoning model in one"
- Claude Code: "our first agentic coding tool" (limited research preview).
- API thinking budget: "you can tell Claude to think for no more than N tokens, for any value of N up to its output limit of 128K tokens"

## What still needs fetching
- Specific MMLU/GPQA/HumanEval/GSM8K/MATH percentage numbers — none of the announcement posts above include them in their rendered text; they are typically in the model-card PDFs.
- Claude 3.5 Sonnet model card / new (Oct 2024) update post for **Computer Use** specifics.

## Related Pages
[[Anthropic]] | [[Constitutional AI]] | [[Claude 4]] | [[GPT-4]] | [[Gemini]]

## Sources (saved excerpts in raw/)
- [Wikipedia: Claude (language model)](https://en.wikipedia.org/wiki/Claude_(language_model)) → [raw/articles/wikipedia-claude.md](../raw/articles/wikipedia-claude.md)

## Sources to fetch (pending rate-limit reset)
- https://www.anthropic.com/news/claude-3-family
- https://www.anthropic.com/news/claude-3-5-sonnet
- https://www.anthropic.com/news/claude-3-7-sonnet
