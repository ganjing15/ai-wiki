---
title: Multimodal AI
created: 2026-04-10
updated: 2026-04-30
type: concept
tags: [multimodal, architecture]
sources: [raw/articles/wikipedia-multimodal.md]
---

# Multimodal AI

## Source
[Wikipedia: Multimodal learning](https://en.wikipedia.org/wiki/Multimodal_learning) → raw excerpt at [wikipedia-multimodal.md](../raw/articles/wikipedia-multimodal.md).

## Definition (verbatim)
> "Multimodal learning is a type of deep learning that integrates and processes multiple types of data, referred to as modalities, such as text, audio, images, or video."

## Distinction from unimodal (verbatim)
> Multimodal approaches "jointly represent the information such that the model can capture the combined information from different modalities."

## Modalities cited
text, images, audio, video, proprioception.

## Notable models cited (verbatim from Wikipedia)
- **CLIP** — "learns joint representations through contrastive objectives"
- **GPT-4o** — "can process and generate text, audio and images" (see [[GPT-4o]])
- **Google Gemini** (see [[Gemini]])
- **Google PaLM** — fine-tuned for multimodal robotic control
- **Flamingo, LLaVA, vision-language LLaMA variants**

## CLIP paper (verbatim, [arXiv:2103.00020](https://arxiv.org/abs/2103.00020))
Raw: [arxiv-clip.md](../raw/papers/arxiv-clip.md). Submitted **2021-02-26** by Radford et al. (OpenAI).

> "Learning directly from raw text about images is a promising alternative which leverages a much broader source of supervision. We demonstrate that the simple pre-training task of predicting which caption goes with which image is an efficient and scalable way to learn SOTA image representations from scratch on a dataset of 400 million (image, text) pairs collected from the internet..."

## Flamingo paper (verbatim, [arXiv:2204.14198](https://arxiv.org/abs/2204.14198))
Raw: [arxiv-flamingo.md](../raw/papers/arxiv-flamingo.md). Submitted **2022-04-29**. Title: "Flamingo: a Visual Language Model for Few-Shot Learning."

> "Flamingo models can be trained on large-scale multimodal web corpora containing arbitrarily interleaved text and images, which is key to endow them with in-context few-shot learning capabilities."

## Notes on what was removed
The previous version of this page contained:

- A three-phase evolution narrative (specialized → vision-language → native multimodal)
- Detailed model timelines (CLIP 2021, Flamingo 2022, GPT-4V Sep 2023, GPT-4o May 2024)
- A "Modality Coverage (April 2026)" capability matrix across text/image/audio/video/code/documents
- Architectural details (ViT, CLIP encoders, end-to-end audio "no separate ASR")
- "Sora: Spatiotemporal video patches in a diffusion transformer"
- Application areas (accessibility, healthcare, robotics RT-2, document AI)

None of those specifics are in the Wikipedia source excerpt. They will be re-added with citations after fetching:

- https://openai.com/index/hello-gpt-4o/
- https://arxiv.org/abs/2312.11805 (Gemini)
- https://arxiv.org/abs/2204.14198 (Flamingo)
- https://arxiv.org/abs/2103.00020 (CLIP)

## Related Pages
[[GPT-4o]] | [[Gemini]] | [[Sora]] | [[Llama]]

## Sources (saved excerpts in raw/)
- [Wikipedia: Multimodal learning](https://en.wikipedia.org/wiki/Multimodal_learning) → [raw/articles/wikipedia-multimodal.md](../raw/articles/wikipedia-multimodal.md)
