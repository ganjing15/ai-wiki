---
title: OpenAI o1
created: 2026-04-10
updated: 2026-04-30
type: entity
tags: [model, reasoning]
sources: [raw/articles/wikipedia-openai-o1.md]
---

# OpenAI o1

## Infobox (per [Wikipedia: OpenAI o1](https://en.wikipedia.org/wiki/OpenAI_o1))
Raw excerpt: [wikipedia-openai-o1.md](../raw/articles/wikipedia-openai-o1.md)

| Field | Value |
|-------|-------|
| Developer | OpenAI |
| Preview release | 2024-09-12 |
| Full release | 2024-12-05 |
| Predecessor | GPT-4o |
| Successor | OpenAI o3 |

> "The name o2 was skipped to avoid trademark conflict."

## Behaviour (verbatim, [Wikipedia: OpenAI o1](https://en.wikipedia.org/wiki/OpenAI_o1))
> "o1 spends time 'thinking' before it answers, making it better at complex reasoning tasks, science and programming than GPT-4o."

> The model generates "long 'chains of thought' before returning a final answer," representing a distinct paradigm where "improving model outputs by spending more computing power when generating the answer" differs from traditional scaling approaches.

## Benchmarks (verbatim, mixed sources)
From [Wikipedia: OpenAI o1](https://en.wikipedia.org/wiki/OpenAI_o1):
- AIME: "solved 83% (12.5/15) of the problems, compared to 13% (1.8/15) for GPT-4o"
- Codeforces: "ranked in the 89th percentile in coding competitions"
- "PhD-level performance" on physics, chemistry, and biology benchmarks

From the OpenAI announcement [Learning to reason with LLMs](https://openai.com/index/learning-to-reason-with-llms/) (raw: [openai-o1-announcement.md](../raw/articles/openai-o1-announcement.md)):
> "On the 2024 AIME exams, GPT-4o only solved on average 12% (1.8/15) of problems."
> "o1 averaged 74% (11.1/15) with a single sample per problem, 83% (12.5/15) with consensus among 64 samples, and 93% (13.9/15) when re-ranking 1000 samples with a learned scoring function."
> "GPQA Diamond=78.3 percent accuracy."

(Note: the Wikipedia "83%" figure refers to consensus@64; the announcement breaks down three sampling regimes.)

## Successors mentioned in source
o3, o3-mini, o4-mini.

### Successor releases (verbatim, [Wikipedia: OpenAI o3](https://en.wikipedia.org/wiki/OpenAI_o3))
Raw: [wikipedia-openai-o3.md](../raw/articles/wikipedia-openai-o3.md).
- **o3-mini**: 2025-01-31 (released to all ChatGPT users)
- **o3**: 2025-04-16
- **o3-pro**: 2025-06-10
- **o4-mini**: alongside o3 on 2025-04-16

Benchmark deltas (verbatim):
> "o3 attained three times the accuracy of o1" on ARC-AGI
> SWE-bench Verified: "o3 scored 71.7%, compared to 48.9% for o1"

## Notes on what was removed
The previous version of this page contained:

- Codename "Strawberry" — not in saved excerpt
- "GPQA Diamond 78.3%, HumanEval ~95%" — not in saved excerpt; Wikipedia gives only AIME and Codeforces
- "o1 Pro Mode via ChatGPT Pro $200/mo" — not in saved excerpt
- "o3 (Mar 2025): 87.5% ARC-AGI" — not in saved excerpt
- "o4-mini: thinking with tools" — not in saved excerpt
- "System 2" framing — not in saved excerpt

These will be re-added with citations after fetching:
- https://openai.com/index/learning-to-reason-with-llms/
- https://openai.com/index/openai-o1-system-card/
- The o3 announcement post

## Related Pages
[[OpenAI]] | [[GPT-4o]] | [[Reasoning Models]]

## Sources (saved excerpts in raw/)
- [Wikipedia: OpenAI o1](https://en.wikipedia.org/wiki/OpenAI_o1) → [raw/articles/wikipedia-openai-o1.md](../raw/articles/wikipedia-openai-o1.md)
