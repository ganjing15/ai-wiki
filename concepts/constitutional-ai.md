---
title: Constitutional AI
created: 2026-04-10
updated: 2026-04-30
type: concept
tags: [alignment, training]
sources: [raw/articles/wikipedia-constitutional-ai.md, raw/articles/wikipedia-claude.md]
---

# Constitutional AI (CAI)

## Source
[Wikipedia: Constitutional AI](https://en.wikipedia.org/wiki/Constitutional_AI) → raw excerpt at [wikipedia-constitutional-ai.md](../raw/articles/wikipedia-constitutional-ai.md).

## Definition (verbatim, [Wikipedia: Claude](https://en.wikipedia.org/wiki/Claude_(language_model)))
> "The constitution is a document used for training Claude to be harmless and helpful without relying on extensive or expensive human feedback."

## How it works (verbatim)
**Supervised Learning Phase**:
> "the model generates responses to prompts, self-critiques these responses based on a set of guiding principles (a 'constitution'), and revises the responses. Then the model is fine-tuned on these revised responses."

**Reinforcement Learning Phase**:
> "responses are generated, and an AI compares their compliance with the constitution. This dataset of AI feedback is used to train a preference model that evaluates responses based on how much they satisfy the constitution."

## Constitution evolution (verbatim)
- **Original (2022)** — "The first constitutions included concepts taken from the 1948 UN Universal Declaration of Human Rights."
- **2023 update** — "listed 75 guidelines for Claude to follow."
- **2026 update** — "provided more context to the model, explaining the rationale behind guidelines such as refraining from assisting in undermining democracy." Length: **23,000 words**, up from **2,700 in 2023**.

## Foundational paper (verbatim, [arXiv:2212.08073](https://arxiv.org/abs/2212.08073))
Raw: [arxiv-constitutional-ai.md](../raw/papers/arxiv-constitutional-ai.md). Submitted **2022-12-15** by Yuntao Bai et al. (51 authors).

Abstract:
> "As AI systems become more capable, we would like to enlist their help to supervise other AIs. We experiment with methods for training a harmless AI assistant through self-improvement, without any human labels identifying harmful outputs. The only human oversight is provided through a list of rules or principles, and so we refer to the method as 'Constitutional AI'. The process involves both a supervised learning and a reinforcement learning phase. In the supervised phase we sample from an initial model, then generate self-critiques and revisions, and then finetune the original model on revised responses. In the RL phase, we sample from the finetuned model, use a model to evaluate which of the two samples is better, and then train a preference model from this dataset of AI preferences. We then train with RL using the preference model as the reward signal, i.e. we use 'RL from AI Feedback' (RLAIF)."

## Notes on what was removed
The previous version of this page contained:

- "Apple ToS, various ethical frameworks" listed as constitution sources — Wikipedia mentions UN Universal Declaration of Human Rights but **not** Apple ToS
- "Reduces sycophancy (model less likely to flatter vs. correct)" — not in saved excerpt (general RLHF/RLAIF claim, not specific to Constitutional AI in the source)

These will be re-added with citations after fetching:
- https://arxiv.org/abs/2212.08073 (Anthropic Constitutional AI paper)
- https://www.anthropic.com/news/claudes-constitution (if such a post exists)

## Related Pages
[[Anthropic]] | [[Claude 3]] | [[Claude 4]] | [[RLHF]] | [[AI Alignment]]

## Sources (saved excerpts in raw/)
- [Wikipedia: Constitutional AI](https://en.wikipedia.org/wiki/Constitutional_AI) → [raw/articles/wikipedia-constitutional-ai.md](../raw/articles/wikipedia-constitutional-ai.md)
- [Wikipedia: Claude (language model)](https://en.wikipedia.org/wiki/Claude_(language_model)) → [raw/articles/wikipedia-claude.md](../raw/articles/wikipedia-claude.md)
