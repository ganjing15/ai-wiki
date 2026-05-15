---
title: Interpretability
created: 2026-04-10
updated: 2026-04-30
type: concept
tags: [interpretability, alignment]
sources: [raw/articles/wikipedia-interpretability.md]
---

# Interpretability (Mechanistic Interpretability)

## Source
[Wikipedia: Mechanistic interpretability](https://en.wikipedia.org/wiki/Mechanistic_interpretability) → raw excerpt at [wikipedia-interpretability.md](../raw/articles/wikipedia-interpretability.md).

## Definition (verbatim)
> "Mechanistic interpretability...aims to understand the internal workings of neural networks by analyzing the mechanisms present in their computations."

## Sparse autoencoders (verbatim)
> "A sparse autoencoder...is a model trained to disentangle neural network activations into sparse representations."

## Circuits (verbatim)
> "A circuit in a neural network is composed of causal chains of feature activations."

## Term origin (verbatim)
> "The term mechanistic interpretability was coined by Chris Olah as a description of his work in circuit analysis."

## Recent applications
> "Sparse autoencoders applied to large language model interpretability by Anthropic."

(Wikipedia article references 2024–2026 publications but does not detail specific milestone achievements.)

## Anthropic — Scaling Monosemanticity (May 2024)
Source: https://transformer-circuits.pub/2024/scaling-monosemanticity/ — direct fetch returned content-length error; raw excerpt at [anthropic-scaling-monosemanticity.md](../raw/papers/anthropic-scaling-monosemanticity.md) (from WebSearch summary).

- Title: "Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet"
- Published: 2024-05-21
- Subject: Anthropic interpretability team applied sparse autoencoders to Claude 3 Sonnet (production model, released 2024-03-04).
- Autoencoder sizes (per WebSearch summary): "~1M, ~4M, and ~34M features"

> ⚠️ The wiki's previous "1.34 million features in Claude" claim does not match any of the three autoencoder sizes named in the WebSearch summary. The exact figure needs direct verification against the paper text (the page itself exceeds 10MB and was not fully fetched).

## Notes on what was removed
The previous version of this page contained:

- "1.34 million interpretable features" in Claude Sonnet (Scaling Monosemanticity, May 2024) — **not in the Wikipedia mechanistic interpretability page**; needs verification against the Anthropic primary source
- "Zoom In: An Introduction to Circuits (2020)" specific paper claim — not in saved excerpt
- "Superposition Hypothesis" — not in saved excerpt
- "On the Biology of a Large Language Model (2025)" — not in saved excerpt
- "Claude has emotion-like internal features (frustration, calm, curiosity)" — not in saved excerpt
- DeepMind activation patching / Eleuther logit lens / Neel Nanda — not in saved excerpt

These will be re-added with citations after fetching:
- https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html
- https://distill.pub/2020/circuits/zoom-in/
- https://transformer-circuits.pub/2025/attribution-graphs/biology.html
- https://transformer-circuits.pub

## Related Pages
[[AI Alignment]] | [[Anthropic]] | [[Constitutional AI]]

## Sources (saved excerpts in raw/)
- [Wikipedia: Mechanistic interpretability](https://en.wikipedia.org/wiki/Mechanistic_interpretability) → [raw/articles/wikipedia-interpretability.md](../raw/articles/wikipedia-interpretability.md)
