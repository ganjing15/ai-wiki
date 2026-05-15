---
title: Mistral AI
created: 2026-04-10
updated: 2026-04-30
type: entity
tags: [lab, company, model, open-source]
sources: [raw/articles/wikipedia-mistral-ai.md]
---

# Mistral AI

## Infobox (per [Wikipedia: Mistral AI](https://en.wikipedia.org/wiki/Mistral_AI))
Raw excerpt: [wikipedia-mistral-ai.md](../raw/articles/wikipedia-mistral-ai.md)

| Field | Value |
|-------|-------|
| Founded | 2023-04-28 |
| Founders | Arthur Mensch, Guillaume Lample, Timothée Lacroix |
| Headquarters | Paris, France |

## Models (verbatim)
| Model | Release date | Detail |
|-------|--------------|--------|
| Mistral 7B | 2023-09-27 | "7.3B parameter language model" released via BitTorrent under Apache 2.0 |
| Mixtral 8x7B | 2023-12-09 | "sparse mixture of experts architecture" with 46.7B total parameters |
| Mistral Large | 2024-02-26 | Proprietary; "available on Microsoft Azure" |
| Codestral 22B | 2024-05-29 | Code-focused; "more than 80 programming languages" |
| Mistral Large 2 | 2024-07-24 | Open-weight; "123 billion parameters" |
| Mistral Large 3 | 2025-12-02 | Sparse MoE; "675 billion total parameters" |

## Funding (verbatim, [Wikipedia: Mistral AI](https://en.wikipedia.org/wiki/Mistral_AI))
- June 2023: €105M at €240M valuation
- December 2023: €385M, valued "over €2 billion"
- June 2024: €600M, valuation €5.8B
- September 2025: €2B investment, €12B valuation (~$14B)

## License
"Apache-2.0" plus proprietary offerings.

## Mistral 7B paper (verbatim, [arXiv:2310.06825](https://arxiv.org/abs/2310.06825))
Raw: [arxiv-mistral-7b.md](../raw/papers/arxiv-mistral-7b.md). Submitted **2023-10-10**.

> "We introduce Mistral 7B v0.1, a 7-billion-parameter language model engineered for superior performance and efficiency. Mistral 7B outperforms Llama 2 13B across all evaluated benchmarks, and Llama 1 34B in reasoning, mathematics, and code generation."

> "Our model leverages grouped-query attention (GQA) for faster inference, coupled with sliding window attention (SWA) to effectively handle sequences of arbitrary length with a reduced inference cost."

> "Our models are released under the Apache 2.0 license."

## Mixtral 8x7B paper (verbatim, [arXiv:2401.04088](https://arxiv.org/abs/2401.04088))
Raw: [arxiv-mixtral.md](../raw/papers/arxiv-mixtral.md). Submitted **2024-01-08**.

> "Each token only sees two experts, the selected experts can be different at each timestep. As a result, each token has access to 47B parameters, but only uses 13B active parameters during inference."

> "Mixtral outperforms or matches Llama 2 70B and GPT-3.5 across all evaluated benchmarks."

## Notes on what was removed
The previous version of this page contained:

- "$6B valuation (2024)" — Wikipedia says **€5.8B (June 2024)** and **€12B (Sept 2025)**
- Investor list (a16z, Lightspeed, Salesforce, BNP Paribas) — not in saved excerpt
- Mixtral 8x22B (Apr 2024, 141B), Pixtral 12B (Sep 2024) — not in saved Wikipedia table; will reverify by fetching mistral.ai/news/
- Architectural details (Grouped Query Attention, Sliding Window Attention) — not in saved excerpt
- Products "La Plateforme" and "Le Chat" — not in saved excerpt

These will be re-added with citations after fetching:
- https://mistral.ai/news/
- https://mistral.ai/news/mixtral-of-experts/
- https://mistral.ai/news/announcing-mistral-7b/

## Related Pages
[[Meta AI]] | [[Llama]] | [[Mixture of Experts]] | [[Hugging Face]] | [[EU AI Act]]

## Sources (saved excerpts in raw/)
- [Wikipedia: Mistral AI](https://en.wikipedia.org/wiki/Mistral_AI) → [raw/articles/wikipedia-mistral-ai.md](../raw/articles/wikipedia-mistral-ai.md)
