---
title: RLHF — Reinforcement Learning from Human Feedback
created: 2026-04-10
updated: 2026-04-30
type: concept
tags: [training, alignment]
sources: [raw/articles/wikipedia-rlhf.md]
---

# RLHF — Reinforcement Learning from Human Feedback

## Source
[Wikipedia: Reinforcement learning from human feedback](https://en.wikipedia.org/wiki/Reinforcement_learning_from_human_feedback) → raw excerpt at [wikipedia-rlhf.md](../raw/articles/wikipedia-rlhf.md).

## Definition (verbatim)
> "A technique to align an intelligent agent with human preferences. It involves training a reward model to represent preferences, which can then be used to train other models through reinforcement learning."

## Three-stage pipeline (verbatim, [Wikipedia: RLHF](https://en.wikipedia.org/wiki/Reinforcement_learning_from_human_feedback))
1. **Supervised Fine-Tuning (SFT)** — pre-trained model trains on prompt-response pairs from human annotators for one epoch.
2. **Reward Model** — learns to "predict if a response to a given prompt is good (high reward) or bad (low reward) based on ranking data."
3. **Policy optimization** — "This model then serves as a reward function to improve an agent's policy through an optimization algorithm like proximal policy optimization."

## Foundational papers (cited in Wikipedia article)
- Stiennon et al., "Learning to summarize with human feedback" (2020) — [arXiv:2009.01325](https://arxiv.org/abs/2009.01325)
- Ouyang et al., InstructGPT (2022) — [arXiv:2203.02155](https://arxiv.org/abs/2203.02155)

### InstructGPT (verbatim, [arXiv:2203.02155](https://arxiv.org/abs/2203.02155))
Raw: [arxiv-instructgpt.md](../raw/papers/arxiv-instructgpt.md). 20 authors led by Long Ouyang. Submitted **2022-03-04**.

> "Starting with a set of labeler-written prompts and prompts submitted through the OpenAI API, we collect a dataset of labeler demonstrations of the desired model behavior, which we use to fine-tune GPT-3 using supervised learning. We then collect a dataset of rankings of model outputs, which we use to further fine-tune this supervised model using reinforcement learning from human feedback. We call the resulting models InstructGPT."

> "outputs from the 1.3B parameter InstructGPT model are preferred to outputs from the 175B GPT-3, despite having 100x fewer parameters."

## Variants (verbatim)
- **DPO** (Direct Preference Optimization) — "directly adjusting the main model according to people's preferences" without training a separate reward model.
- **RLAIF** (RL from AI Feedback) — "the feedback is automatically generated"; notably used in "Anthropic's constitutional AI." See [[Constitutional AI]].

## Limitations (verbatim)
- **Reward hacking** — models learn to "manipulate the feedback process."
- **Sycophancy** — models generating "confident-sounding yet incorrect text" because "humans are not skilled at identifying mistakes in LLM outputs."
- Human feedback collection is expensive and prone to algorithmic bias.

## Notes on what was removed
The previous version of this page contained:

- Specific statement that RLHF is "Used In: ChatGPT/GPT-4, Claude 3, Llama chat" — partly true but not in Wikipedia excerpt at this level of detail
- "GRPO used in DeepSeek-R1" — not in saved RLHF excerpt
- "Goodhart's Law" framing — not in saved excerpt

These will be re-added with citations after fetching:
- https://huggingface.co/blog/rlhf
- The DeepSeek-R1 paper for GRPO

## Related Pages
[[Constitutional AI]] | [[Claude 3]] | [[GPT-4]] | [[AI Alignment]] | [[Reasoning Models]]

## Sources (saved excerpts in raw/)
- [Wikipedia: Reinforcement learning from human feedback](https://en.wikipedia.org/wiki/Reinforcement_learning_from_human_feedback) → [raw/articles/wikipedia-rlhf.md](../raw/articles/wikipedia-rlhf.md)
