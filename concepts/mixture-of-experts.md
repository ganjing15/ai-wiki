---
title: Mixture of Experts (MoE)
created: 2026-04-10
updated: 2026-04-30
type: concept
tags: [architecture, scaling, training]
sources: [raw/articles/wikipedia-mixture-of-experts.md]
---

# Mixture of Experts (MoE)

## Source
[Wikipedia: Mixture of experts](https://en.wikipedia.org/wiki/Mixture_of_experts) → raw excerpt at [wikipedia-mixture-of-experts.md](../raw/articles/wikipedia-mixture-of-experts.md).

## Definition (verbatim)
> "MoE is a machine learning technique where multiple expert networks (learners) are used to divide a problem space into homogeneous regions."

## Sparse activation (verbatim)
> "The output for each query can only involve a few experts' outputs."

The sparsely-gated approach uses "a weighted sum of only the top-k experts, instead of the weighted sum of all of them."

## Gating function (verbatim)
> "A weighting function (also known as a gating function) takes input x and produces a vector of outputs."

Modern form: w(x) = softmax(top_k(Wx + noise)) — noise aids load balancing.

## Origins
- Jacobs et al. (1991), "Adaptive Mixtures of Local Experts" — the foundational paper.
- Connections to "committee machines" terminology and Hinton's neural-network ensemble work.

## Modern LLMs using MoE (verbatim)
- **Mixtral 8x7B** (Mistral AI, December 2023): per [Wikipedia: MoE](https://en.wikipedia.org/wiki/Mixture_of_experts), "46.7B parameters, 8 experts, and sparsity 2"
- **DBRX** (Databricks, March 2024): "132B parameters, 16 experts, and sparsity 4"
- DeepSeek models use MoE variants with shared and routed experts.

> GPT-4's architecture remains unconfirmed by OpenAI.

### Mixtral paper (verbatim, [arXiv:2401.04088](https://arxiv.org/abs/2401.04088))
Raw: [arxiv-mixtral.md](../raw/papers/arxiv-mixtral.md). Submitted **2024-01-08**.

> "Each token only sees two experts, the selected experts can be different at each timestep. As a result, each token has access to 47B parameters, but only uses 13B active parameters during inference."

> "Mixtral outperforms or matches Llama 2 70B and GPT-3.5 across all evaluated benchmarks. In particular, Mixtral vastly outperforms Llama 2 70B on mathematics, code generation, and multilingual benchmarks."

(Note: Wikipedia's "46.7B" rounds the paper's "47B"; both refer to total parameters.)

### DeepSeek-V3 (verbatim, [arXiv:2412.19437](https://arxiv.org/abs/2412.19437))
Raw: [arxiv-deepseek-v3.md](../raw/papers/arxiv-deepseek-v3.md).

> "671B total parameters with 37B activated for each token"
> "requires only 2.788M H800 GPU hours for its full training"

## Notes on what was removed
The previous version of this page contained:

- Specific Llama 4 Scout (109B / 17B), Llama 4 Maverick (400B / 17B), DeepSeek-V3 (671B / 37B) parameter splits in a comparison table — total parameter counts are confirmed by other saved sources but the dense-equivalent active counts and Llama 4 active-param breakdowns are not in the MoE excerpt; will be re-added with the Llama 4 paper / DeepSeek-V3 paper as citations
- "GPT-4 rumored ~1.8T / ~220B active" — explicitly **unconfirmed**; Wikipedia notes GPT-4's architecture "remains unconfirmed by OpenAI" — speculation removed

These will be re-added with citations after fetching:
- https://arxiv.org/abs/2401.04088 (Mixtral paper)
- https://arxiv.org/abs/2412.19437 (DeepSeek-V3 paper)
- https://arxiv.org/abs/2101.03961 (Switch Transformers)

## Related Pages
[[DeepSeek]] | [[Llama]] | [[Scaling Laws]] | [[Mistral AI]]

## Sources (saved excerpts in raw/)
- [Wikipedia: Mixture of experts](https://en.wikipedia.org/wiki/Mixture_of_experts) → [raw/articles/wikipedia-mixture-of-experts.md](../raw/articles/wikipedia-mixture-of-experts.md)
