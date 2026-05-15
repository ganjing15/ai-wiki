---
title: Reasoning Models
created: 2026-04-10
updated: 2026-04-30
type: concept
tags: [reasoning, model, scaling]
sources: [raw/articles/wikipedia-openai-o1.md, raw/articles/wikipedia-scaling-laws.md, raw/articles/wikipedia-deepseek.md]
---

# Reasoning Models

## What is sourced
This page draws from three saved Wikipedia excerpts:
- [Wikipedia: OpenAI o1](https://en.wikipedia.org/wiki/OpenAI_o1) → [wikipedia-openai-o1.md](../raw/articles/wikipedia-openai-o1.md)
- [Wikipedia: Neural scaling law](https://en.wikipedia.org/wiki/Neural_scaling_law) → [wikipedia-scaling-laws.md](../raw/articles/wikipedia-scaling-laws.md)
- [Wikipedia: DeepSeek](https://en.wikipedia.org/wiki/DeepSeek) → [wikipedia-deepseek.md](../raw/articles/wikipedia-deepseek.md)

## Defining behaviour (verbatim, [Wikipedia: OpenAI o1](https://en.wikipedia.org/wiki/OpenAI_o1))
> "o1 spends time 'thinking' before it answers, making it better at complex reasoning tasks, science and programming than GPT-4o."

> Models generate "long 'chains of thought' before returning a final answer," reflecting a paradigm where "improving model outputs by spending more computing power when generating the answer" differs from traditional scaling.

## The new scaling axis (verbatim, [Wikipedia: Neural scaling law](https://en.wikipedia.org/wiki/Neural_scaling_law))
> "The OpenAI o1 report documented that o1's performance consistently improved with both increased train-time compute and test-time compute."

## Confirmed reasoning models in saved sources
| Model | Source | Confirmed details |
|-------|--------|-------------------|
| [[OpenAI o1]] | Wikipedia OpenAI o1; [openai-o1-announcement.md](../raw/articles/openai-o1-announcement.md) | Preview 2024-09-12; full release 2024-12-05; AIME 2024: o1 averaged "74% (11.1/15)" single-sample, "83% (12.5/15)" with consensus@64, "93% (13.9/15)" with re-ranking@1000 vs. GPT-4o's "12% (1.8/15)"; GPQA Diamond "78.3 percent accuracy"; Codeforces "89th percentile" |
| OpenAI o3, o3-mini, o4-mini | Wikipedia OpenAI o1 | Listed as successors |
| [[DeepSeek]]-R1 | [arxiv-deepseek-r1.md](../raw/papers/arxiv-deepseek-r1.md) | "DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning" — submitted 2025-01-22; abstract: "the reasoning abilities of LLMs can be incentivized through pure reinforcement learning (RL), obviating the need for human-labeled reasoning trajectories" |

## o1 announcement — chain-of-thought (verbatim, [Learning to reason with LLMs](https://openai.com/index/learning-to-reason-with-llms/))
> "Similar to how a human may think for a long time before responding to a difficult question, o1 uses a chain of thought when attempting to solve a problem."
> "Through reinforcement learning, o1 learns to hone its chain of thought and refine the strategies it uses."

## DeepSeek-R1 — emergent patterns (verbatim, [arXiv:2501.12948](https://arxiv.org/abs/2501.12948))
> "The proposed RL framework facilitates the emergent development of advanced reasoning patterns, such as self-reflection, verification, and dynamic strategy adaptation."

## Notes on what was removed
The previous version of this page contained:

- "78% GPQA Diamond" for o1 — not in saved excerpt
- "87.5% ARC-AGI" / "25.2% FrontierMath" for o3 — not in saved excerpt
- "70.3% SWE-bench" for Claude 3.7 — not in saved excerpt
- Claude 3.7 Sonnet, Gemini 2.0 Flash Thinking, QwQ-32B as confirmed reasoning models — none of these are in the saved Wikipedia o1/scaling/DeepSeek excerpts; need their own sources
- Process Reward Models (PRMs) training framing — not in saved excerpts
- GRPO vs PPO discussion, "Aha moment" behaviour — these come from the DeepSeek-R1 paper, not yet fetched
- "$6M vs. OpenAI's hundreds of millions" cost claim — Wikipedia DeepSeek says V3 cost "$6M" but doesn't compare R1 cost to OpenAI directly

These will be re-added with citations after fetching:
- https://arxiv.org/abs/2501.12948 (DeepSeek-R1 paper)
- https://www.anthropic.com/news/claude-3-7-sonnet
- https://openai.com/index/learning-to-reason-with-llms/
- https://arcprize.org

## Related Pages
[[OpenAI o1]] | [[DeepSeek]] | [[Claude 3]] | [[Scaling Laws]]

## Sources (saved excerpts in raw/)
- [Wikipedia: OpenAI o1](https://en.wikipedia.org/wiki/OpenAI_o1) → [raw/articles/wikipedia-openai-o1.md](../raw/articles/wikipedia-openai-o1.md)
- [Wikipedia: Neural scaling law](https://en.wikipedia.org/wiki/Neural_scaling_law) → [raw/articles/wikipedia-scaling-laws.md](../raw/articles/wikipedia-scaling-laws.md)
- [Wikipedia: DeepSeek](https://en.wikipedia.org/wiki/DeepSeek) → [raw/articles/wikipedia-deepseek.md](../raw/articles/wikipedia-deepseek.md)
