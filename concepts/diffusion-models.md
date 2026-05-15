---
title: Diffusion Models
created: 2026-05-07
updated: 2026-05-07
type: concept
tags: [architecture, multimodal]
sources: [raw/articles/wikipedia-diffusion-model.md, raw/articles/wikipedia-stable-diffusion.md, raw/articles/wikipedia-sora.md]
---

# Diffusion Models

## Source
[Wikipedia: Diffusion model](https://en.wikipedia.org/wiki/Diffusion_model) → raw excerpt at [wikipedia-diffusion-model.md](../raw/articles/wikipedia-diffusion-model.md).

## Definition (verbatim)
> "A diffusion model consists of two major components: the forward diffusion process, and the reverse sampling process."

The model learns "a diffusion process for a given dataset, such that the process can generate new elements that are distributed similarly as the original dataset."

## DDPM (2020, verbatim)
> "The 2020 paper proposed the Denoising Diffusion Probabilistic Model (DDPM), which improves upon the previous method by variational inference."

## Applications (verbatim)
> "Diffusion-based image generators have seen widespread commercial interest, such as Stable Diffusion and DALL-E."

> Models "typically combine diffusion models with other models, such as text-encoders and cross-attention modules to allow text-conditioned generation."

Beyond images: "natural language processing such as text generation and summarization, sound generation, and reinforcement learning."

## Sora as a "diffusion transformer"
Per [Wikipedia: Sora](https://en.wikipedia.org/wiki/Sora_(text-to-video_model)) (raw: [wikipedia-sora.md](../raw/articles/wikipedia-sora.md)):

> "Sora is a diffusion transformer, a denoising latent diffusion model with one transformer as its denoiser."

This makes Sora the first widely-deployed model to combine the [[Transformer Architecture]] with diffusion-based generation in a video setting.

## Stable Diffusion lineage
Per [Wikipedia: Stable Diffusion](https://en.wikipedia.org/wiki/Stable_Diffusion) (raw: [wikipedia-stable-diffusion.md](../raw/articles/wikipedia-stable-diffusion.md)):

- v1.0: 2022-08-22 (Stability AI)
- v1.5: 2022-10-20 (released by RunwayML)
- v2.0: November 2022
- XL 1.0: July 2023
- v3.0: February 2024 (early preview)
- v3.5: 2024-10-22

## Note
The Wikipedia article references "latent diffusion" as a main variant but the fetched excerpt does not include the Rombach et al. 2022 paper detail (the basis for Stable Diffusion). That should be fetched separately when needed.

## Related Pages
[[Sora]] | [[Multimodal AI]] | [[Transformer Architecture]]

## Sources (saved excerpts in raw/)
- [Wikipedia: Diffusion model](https://en.wikipedia.org/wiki/Diffusion_model) → [raw/articles/wikipedia-diffusion-model.md](../raw/articles/wikipedia-diffusion-model.md)
- [Wikipedia: Stable Diffusion](https://en.wikipedia.org/wiki/Stable_Diffusion) → [raw/articles/wikipedia-stable-diffusion.md](../raw/articles/wikipedia-stable-diffusion.md)
- [Wikipedia: Sora](https://en.wikipedia.org/wiki/Sora_(text-to-video_model)) → [raw/articles/wikipedia-sora.md](../raw/articles/wikipedia-sora.md)
