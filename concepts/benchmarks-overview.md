---
title: Benchmarks Overview
created: 2026-04-10
updated: 2026-04-30
type: concept
tags: [benchmark, evaluation]
sources: [raw/articles/wikipedia-mmlu.md]
---

# AI Benchmarks Overview

## What is sourced
Only one benchmark — MMLU — has had its full Wikipedia source fetched and saved. Other benchmark claims in the prior page (GPQA, HumanEval, SWE-bench, AIME, ARC-AGI, MATH, Chatbot Arena) need their primary sources fetched and saved before being re-stated as fact.

---

## MMLU — Measuring Massive Multitask Language Understanding
Source: [Wikipedia: MMLU](https://en.wikipedia.org/wiki/MMLU) → raw excerpt at [wikipedia-mmlu.md](../raw/articles/wikipedia-mmlu.md).

### Definition (verbatim)
> "Measuring Massive Multitask Language Understanding (MMLU) is a popular benchmark for evaluating the capabilities of large language models."

Released by Dan Hendrycks and a team of researchers on **2020-09-07**.

### Scope (verbatim)
> "15,908 multiple-choice questions" spanning "57 subjects, from highly complex STEM fields and international law, to nutrition and religion."

### Human expert baseline (verbatim)
> "The creators of the MMLU estimated that human domain-experts achieve around 89.8% accuracy."

### Model scores (verbatim)
> At launch: "most existing language models scored near the level of random chance (25%). The best performing model, GPT-3 175B, achieved 43.9% accuracy."
> By mid-2024: "the majority of powerful language models such as Claude 3.5 Sonnet, GPT-4o and Llama 3.1 405B consistently achieved 88%."

For [[GPT-4o]]'s MMLU score (88.7), see [[GPT-4o]] (sourced to its own Wikipedia page).

---

## Other benchmarks — pending source fetch

The previous version of this page made specific claims about:

- **GPQA** — "PhD-level Google-proof Q&A; ~69% human expert baseline; o1 78.3%; Gemini 2.5 Pro ~84%"
- **HumanEval** — "164 Python programming problems"
- **SWE-bench Verified** — "Claude 3.5 Sonnet: 49%; Claude 3.7 Sonnet: 70.3%"
- **AIME** — "o1: 83.3%; DeepSeek-R1: 79.8%"
- **ARC-AGI** — "human baseline ~85%; o3 87.5%"
- **MATH** — "DeepSeek-R1: 97.3%; o1: 96.4%"
- **Chatbot Arena / Lmarena** — Gemini 2.5 Pro top of leaderboard

None of these specific numbers have been verified against fetched primary sources in this rebuild. They are removed pending fetch of:

- https://arxiv.org/abs/2009.03300 (MMLU paper, Hendrycks et al.)
- https://arxiv.org/abs/2311.12022 (GPQA paper, Rein et al.)
- https://arxiv.org/abs/2107.03374 (HumanEval paper, Chen et al.)
- https://arxiv.org/abs/2310.06770 (SWE-bench paper, Jimenez et al.)
- https://arcprize.org (ARC-AGI)
- https://lmarena.ai (Chatbot Arena)

The o1 / DeepSeek-R1 benchmark numbers should also flow from the dedicated [[OpenAI o1]] and [[DeepSeek]] pages once their primary papers are fetched.

## Benchmark inflation concerns
This is a meta-claim that needs grounding (e.g., the Frontier Math paper, NYT/IEEE coverage). Pending fetch.

## Related Pages
[[OpenAI o1]] | [[DeepSeek]] | [[GPT-4o]] | [[Reasoning Models]]

## Sources (saved excerpts in raw/)
- [Wikipedia: MMLU](https://en.wikipedia.org/wiki/MMLU) → [raw/articles/wikipedia-mmlu.md](../raw/articles/wikipedia-mmlu.md)
