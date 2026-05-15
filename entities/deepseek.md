---
title: DeepSeek
created: 2026-04-10
updated: 2026-04-30
type: entity
tags: [model, open-source, reasoning]
sources: [raw/articles/wikipedia-deepseek.md]
---

# DeepSeek

## Infobox (per [Wikipedia: DeepSeek](https://en.wikipedia.org/wiki/DeepSeek))
Raw excerpt: [wikipedia-deepseek.md](../raw/articles/wikipedia-deepseek.md)

| Field | Value |
|-------|-------|
| Founded | 2023-07-17 |
| Founder | Liang Wenfeng |
| Headquarters | Hangzhou, Zhejiang, China |

## Model timeline (verbatim)
| Model | Release date | Parameters |
|-------|--------------|------------|
| DeepSeek Coder | 2023-11-02 | 1.3B–33B |
| DeepSeek-LLM | 2023-11-29 | 7B, 67B |
| DeepSeek-MoE | 2024-01-09 | 16B (2.7B active) |
| DeepSeek-Math | April 2024 | 7B |
| DeepSeek-V2 | May 2024 | 15.7B–236B |
| DeepSeek-V3 | December 2024 | 671B (37B active) |
| DeepSeek-R1-Lite | 2024-11-20 | Preview only |
| DeepSeek-R1 | 2025-01-20 | Full release |
| DeepSeek-V3.1 | 2025-08-21 | 671B+ |
| DeepSeek-V4 | 2026-04-24 | 1.6T (Pro), 284B (Flash) |

## "DeepSeek moment" (verbatim, [Wikipedia: DeepSeek](https://en.wikipedia.org/wiki/DeepSeek))
> "By 27 January, DeepSeek surpassed ChatGPT as the most downloaded freeware app on the iOS App Store in the United States, triggering an 18% drop in Nvidia's share price."

> "Nvidia's share price dropped sharply, losing US$600 billion in market value, the largest single-company decline in U.S. stock market history."

(Note: the prior version of this page said "~17%". Wikipedia says **18%**.)

## Open-source claim (verbatim)
> "Since the January 2025 debut of DeepSeek-R1, the company has made its new models available under free and open-source software licenses, primarily the MIT License."

> "DeepSeek's models are described as 'open-weight', meaning the exact parameters are openly shared, but the training data is not openly licensed."

## Training cost (verbatim)
> "The company claims that it trained its V3 model for US$6 million—far less than the US$100 million cost for OpenAI's GPT-4 in 2023."

(Note: the prior version said **"$5.5 million"**. Wikipedia says **"US$6 million"**, with detailed breakdown totalling US$5.576 million.)

The DeepSeek-V3 paper itself ([arXiv:2412.19437](https://arxiv.org/abs/2412.19437), raw: [arxiv-deepseek-v3.md](../raw/papers/arxiv-deepseek-v3.md)) states:
> "671B total parameters with 37B activated for each token"
> "requires only 2.788M H800 GPU hours for its full training"
> "DeepSeek-V3 outperforms other open-source models and achieves performance comparable to leading closed-source models"

## DeepSeek-R1 — paper abstract (verbatim, [arXiv:2501.12948](https://arxiv.org/abs/2501.12948))
> "Here we show that the reasoning abilities of LLMs can be incentivized through pure reinforcement learning (RL), obviating the need for human-labeled reasoning trajectories."
> "The proposed RL framework facilitates the emergent development of advanced reasoning patterns, such as self-reflection, verification, and dynamic strategy adaptation."

Raw excerpt: [arxiv-deepseek-r1.md](../raw/papers/arxiv-deepseek-r1.md).

## Notes on what was removed
The previous version of this page contained:

- "Parent company: High-Flyer (Chinese hedge fund)" — not in saved excerpt
- "Used Nvidia H800 chips (export-controlled, lower than H100s)" — not in saved excerpt
- "Multi-head latent attention, FP8 mixed precision" — not in saved excerpt
- DeepSeek-R1 vs. o1 benchmark numbers ("79.8% AIME", "97.3% MATH") — not in saved excerpt
- "Distilled versions from 1.5B to 70B parameters" — not in saved excerpt
- "Quickly adopted on Hugging Face" claim — not in saved excerpt

These will be re-added with citations after fetching:
- https://arxiv.org/abs/2501.12948 (DeepSeek-R1 paper)
- https://arxiv.org/abs/2412.19437 (DeepSeek-V3 paper)
- https://huggingface.co/deepseek-ai

## Related Pages
[[OpenAI o1]] | [[Reasoning Models]] | [[Llama]] | [[China AI Regulation]] | [[Mixture of Experts]]

## Sources (saved excerpts in raw/)
- [Wikipedia: DeepSeek](https://en.wikipedia.org/wiki/DeepSeek) → [raw/articles/wikipedia-deepseek.md](../raw/articles/wikipedia-deepseek.md)
