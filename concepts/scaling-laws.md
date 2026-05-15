---
title: Scaling Laws
created: 2026-04-10
updated: 2026-04-30
type: concept
tags: [scaling, training, architecture]
sources: [raw/articles/wikipedia-scaling-laws.md]
---

# Scaling Laws

## Source
[Wikipedia: Neural scaling law](https://en.wikipedia.org/wiki/Neural_scaling_law) → raw excerpt at [wikipedia-scaling-laws.md](../raw/articles/wikipedia-scaling-laws.md).

## Definition (verbatim)
> "A neural scaling law is an empirical scaling law that describes how neural network performance changes as key factors are scaled up or down."

## Kaplan et al. 2020 (OpenAI)
[arXiv:2001.08361](https://arxiv.org/abs/2001.08361)

Critical relationship cited in Wikipedia: "optimal model parameter count is consistently around N_opt(C) = (C / 5×10⁻¹² petaFLOP-day)^0.7"

Suggested N should scale **more aggressively than dataset size D** with compute budget C.

## Chinchilla — Hoffmann et al. 2022 (DeepMind)
[arXiv:2203.15556](https://arxiv.org/abs/2203.15556)

Verbatim: "For a given training compute budget (C), to achieve the minimal pretraining loss for that budget, the number of model parameters (N) and the number of training tokens (D) should be scaled in equal proportions."

Specifically: N_opt(C) ∝ C^0.5, D_opt(C) ∝ C^0.5.

This contradicted Kaplan et al., finding more balanced scaling.

## Chinchilla loss model (verbatim)
> L = A/Nᵅ + B/Dᵝ + L₀
> (α = 0.34, β = 0.28, A = 406.4, B = 410.7, L₀ = 1.69)

## Inference-time compute (verbatim)
> "The OpenAI o1 report documented that o1's performance consistently improved with both increased train-time compute and test-time compute."

## Kaplan paper abstract (verbatim, [arXiv:2001.08361](https://arxiv.org/abs/2001.08361))
Raw: [arxiv-kaplan-scaling-laws.md](../raw/papers/arxiv-kaplan-scaling-laws.md). Submitted **2020-01-23**. Authors: Kaplan, McCandlish, Henighan, Brown, Chess, Child, Gray, Radford, Wu, Amodei.

> "We study empirical scaling laws for language model performance on the cross-entropy loss. The loss scales as a power-law with model size, dataset size, and the amount of compute used for training, with some trends spanning more than seven orders of magnitude."

> "Larger models are significantly more sample-efficient, such that optimally compute-efficient training involves training very large models on a relatively modest amount of data and stopping significantly before convergence."

## Chinchilla paper abstract (verbatim, [arXiv:2203.15556](https://arxiv.org/abs/2203.15556))
Raw: [arxiv-chinchilla.md](../raw/papers/arxiv-chinchilla.md). Submitted **2022-03-29**. 22 authors led by Jordan Hoffmann.

> "We investigate the optimal model size and number of tokens for training a transformer language model under a given compute budget. We find that current large language models are significantly undertrained, a consequence of the recent focus on scaling language models whilst keeping the amount of training data constant."

> "By training over 400 language models ranging from 70 million to over 16 billion parameters on 5 to 500 billion tokens, we find that for compute-optimal training, the model size and the number of training tokens should be scaled equally: for every doubling of model size the number of training tokens should also be doubled."

## Notes on what was removed
The previous version of this page contained:

- "GPT-3 (175B) was significantly under-trained" — implicit in Chinchilla but not directly quoted in saved excerpt
- "Chinchilla (70B) outperformed Gopher (280B) using same compute" — not in saved excerpt
- "Justified hundreds of billions in GPU investment" framing — not in saved excerpt
- "Emergent capabilities appear suddenly at scale thresholds" — not in saved excerpt

These will be re-added with citations after fetching:
- https://arxiv.org/abs/2001.08361 (Kaplan paper)
- https://arxiv.org/abs/2203.15556 (Chinchilla paper)
- https://openai.com/research/ai-and-compute

## Related Pages
[[GPT-4]] | [[Llama]] | [[OpenAI o1]] | [[Reasoning Models]]

## Sources (saved excerpts in raw/)
- [Wikipedia: Neural scaling law](https://en.wikipedia.org/wiki/Neural_scaling_law) → [raw/articles/wikipedia-scaling-laws.md](../raw/articles/wikipedia-scaling-laws.md)
