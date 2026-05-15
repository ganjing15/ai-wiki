---
title: Reasoning Models Comparison
created: 2026-04-10
updated: 2026-04-30
type: comparison
tags: [comparison, reasoning, model]
sources: [raw/articles/wikipedia-openai-o1.md, raw/articles/wikipedia-deepseek.md, raw/articles/wikipedia-gemini.md]
---

# Reasoning Models Comparison

This comparison contains **only** facts directly verifiable against the saved Wikipedia raw excerpts.

## Confirmed reasoning models

| Model | Lab | Released | Confirmed claim | Source |
|-------|-----|----------|-----------------|--------|
| OpenAI o1 (preview) | OpenAI | 2024-09-12 | "spends time 'thinking' before it answers" | [wikipedia-openai-o1.md](../raw/articles/wikipedia-openai-o1.md) |
| OpenAI o1 (full) | OpenAI | 2024-12-05 | AIME "83% (12.5/15)" vs GPT-4o "13% (1.8/15)"; Codeforces "89th percentile" | [wikipedia-openai-o1.md](../raw/articles/wikipedia-openai-o1.md) |
| OpenAI o3 / o3-mini / o4-mini | OpenAI | (listed as successors) | — | [wikipedia-openai-o1.md](../raw/articles/wikipedia-openai-o1.md) |
| DeepSeek-R1-Lite | DeepSeek | 2024-11-20 (preview) | — | [wikipedia-deepseek.md](../raw/articles/wikipedia-deepseek.md) |
| DeepSeek-R1 | DeepSeek | 2025-01-20 | MIT license; full release | [wikipedia-deepseek.md](../raw/articles/wikipedia-deepseek.md) |
| Gemini 3 Deep Think | Google DeepMind | 2026-02-12 | "Deep Think (reasoning mode)" | [wikipedia-gemini.md](../raw/articles/wikipedia-gemini.md) |
| Gemini 2.5 Pro Experimental | Google DeepMind | 2025-03-25 | listed as "Pro (thinking model)" | [wikipedia-gemini.md](../raw/articles/wikipedia-gemini.md) |

## Confirmed benchmark numbers
| Model | Benchmark | Score | Source |
|-------|-----------|-------|--------|
| OpenAI o1 | AIME 2024 (single sample) | 74% (11.1/15) | [openai-o1-announcement.md](../raw/articles/openai-o1-announcement.md) |
| OpenAI o1 | AIME 2024 (consensus@64) | 83% (12.5/15) | [openai-o1-announcement.md](../raw/articles/openai-o1-announcement.md) |
| OpenAI o1 | AIME 2024 (re-rank@1000) | 93% (13.9/15) | [openai-o1-announcement.md](../raw/articles/openai-o1-announcement.md) |
| GPT-4o (comparison) | AIME 2024 | 12% (1.8/15) | [openai-o1-announcement.md](../raw/articles/openai-o1-announcement.md) |
| OpenAI o1 | GPQA Diamond | 78.3% | [openai-o1-announcement.md](../raw/articles/openai-o1-announcement.md) |
| OpenAI o1 | Codeforces | 89th percentile | [wikipedia-openai-o1.md](../raw/articles/wikipedia-openai-o1.md) |
| Gemini 3.1 Pro | ARC-AGI-2 | 77.1% | [wikipedia-gemini.md](../raw/articles/wikipedia-gemini.md) |
| Gemini 3.1 Pro | SWE-Bench Verified | 80.6% | [wikipedia-gemini.md](../raw/articles/wikipedia-gemini.md) |

## Notes on what was removed
The previous version of this page contained:

- A side-by-side table claiming specific GPQA Diamond, MATH, FrontierMath, ARC-AGI scores for o1, o3, R1, Claude 3.7, Gemini 2.5 Pro — **none of those scores are in the saved excerpts**
- Cost comparisons ("o1 $15/$60 per million tokens") — not in saved excerpts
- Open vs. closed weights characterization with specific commentary — partially covered in [[Open Source AI Safety]]
- "Hidden chain of thought (o1) vs visible (Claude/Gemini)" framing — only Gemini "thinking model" tier is in saved excerpts; o1's hidden CoT is implied by Wikipedia OpenAI o1 but not stated in the fetched excerpt
- Claude 3.7 Sonnet listed as a reasoning model with "70.3% SWE-bench" — Wikipedia Claude lists 3.7 Sonnet but doesn't quote the SWE-bench score in our excerpt; needs anthropic.com/news/claude-3-7-sonnet
- "DeepSeek-R1 79.8% AIME / 97.3% MATH" — not in saved excerpts

These will be re-added with citations after fetching:
- https://arxiv.org/abs/2501.12948 (DeepSeek-R1 paper)
- https://www.anthropic.com/news/claude-3-7-sonnet
- https://openai.com/index/learning-to-reason-with-llms/
- The o3 announcement post and its system card

## Related Pages
[[Reasoning Models]] | [[OpenAI o1]] | [[DeepSeek]] | [[Claude 3]] | [[Gemini]]

## Sources (saved excerpts in raw/)
- [Wikipedia: OpenAI o1](https://en.wikipedia.org/wiki/OpenAI_o1) → [raw/articles/wikipedia-openai-o1.md](../raw/articles/wikipedia-openai-o1.md)
- [Wikipedia: DeepSeek](https://en.wikipedia.org/wiki/DeepSeek) → [raw/articles/wikipedia-deepseek.md](../raw/articles/wikipedia-deepseek.md)
- [Wikipedia: Gemini (chatbot)](https://en.wikipedia.org/wiki/Gemini_(chatbot)) → [raw/articles/wikipedia-gemini.md](../raw/articles/wikipedia-gemini.md)
