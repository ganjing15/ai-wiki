---
title: World Models (AI)
created: 2026-05-14
updated: 2026-05-14
type: concept
tags: [architecture, world-models, jepa, lecun, embodied-ai]
sources: [raw/articles/wikipedia-world-models.md, raw/articles/wikipedia-genie-world-model.md]
---

# World Models (AI)

## Source
[Wikipedia: World model (artificial intelligence)](https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)) → raw excerpt at [wikipedia-world-models.md](../raw/articles/wikipedia-world-models.md).
[Wikipedia: Genie (world model)](https://en.wikipedia.org/wiki/Genie_(world_model)) → raw excerpt at [wikipedia-genie-world-model.md](../raw/articles/wikipedia-genie-world-model.md).

## Definition (verbatim from Wikipedia)
> "A world model in artificial intelligence is a machine learning system that builds an internal representation of an environment and predicts how that environment changes over time in response to actions."

These systems differ from classification or generation systems by simulating dynamics such as physics, object interactions, and causality.

## History

| Year | Event |
|------|-------|
| 1990 | Jürgen Schmidhuber introduced the term "world model in machine learning," proposing recurrent neural networks that predict future states from observations |
| 2018 | David Ha and Schmidhuber demonstrated agents that "learned to drive virtual cars and play video games inside self-generated simulations" |
| 2022 | Yann LeCun published "A Path Towards Autonomous Machine Intelligence," arguing that "intelligence requires predictive models of the world rather than pure pattern matching" |
| 2024 | Google DeepMind introduced Genie, which "learned interactive environments from unlabeled internet videos" |
| Aug 2025 | Genie 3 launched: "photorealistic, real-time interactive worlds from text prompts...displayed at 24 frames per second" |
| Mar 2026 | LeWorldModel introduced; LeCun founded Advanced Machine Intelligence Labs (AMI Labs) |
| Apr 2026 | Alibaba announced Happy Oyster; World Labs unveiled Spark 2.0 |

## Key architectures

### JEPA (Joint Embedding Predictive Architecture)
Meta AI's approach. Comprises encoder, predictor, critic, and regularizer. Compresses sensory data into embeddings and predicts future states rather than raw pixels.
- **I-JEPA** (June 2023): image variant; first released at CVPR 2023
- **V-JEPA 2**: video variant; "reached state-of-the-art performance on video understanding and physical reasoning"

### Genie Series (Google DeepMind)
- **Genie** (March 2024): 2D environments from unlabeled internet video
- **Genie 2** (December 2024): added 3D capability
- **Genie 3** (August 2025): 720p at 24 FPS, ~1-minute memory; photorealistic real-time worlds
- **Project Genie** (January 29, 2026): public access — Google AI Ultra subscribers ($250/month), US only, ages 18+, 60-second per-session limit

### LeWorldModel (March 2026)
Trains "stably end-to-end from raw pixels" using only two loss terms: a next-embedding prediction loss and a Gaussian regularizer.

## vs. Large Language Models (LeCun verbatim)
> "because LLMs are trained only on text, they have no ability to predict anything beyond text, such as real-world events."

LLMs predict the next token; world models predict physical state changes from sensor inputs (pixels, lidar).

## Key researchers
| Researcher | Contribution |
|------------|-------------|
| Jürgen Schmidhuber | Pioneered world models concept (1990) |
| Yann LeCun | JEPA architecture; AMI Labs (founded March 2026, $1.03B raised) |
| David Ha | 2018 revival paper with Schmidhuber |
| Fei-Fei Li | Co-founded World Labs ($1B raised) |

## Applications
- Robot learning and sim-to-real transfer
- Autonomous vehicle testing (Waymo World Model, Feb 2026)
- Interactive entertainment and game prototyping
- Scientific simulation and digital twins

## Notable organizations (2026)
- **AMI Labs** (Advanced Machine Intelligence Labs): LeCun, Paris, $1.03B raised (March 2026)
- **World Labs**: Fei-Fei Li, $1B raised
- **Waymo World Model**: Autonomous vehicle edge-case simulation

## Related Pages
[[Yann LeCun]] | [[Google DeepMind]] | [[Transformer Architecture]] | [[Reasoning Models]] | [[AI Agents]] | [[Multimodal AI]]

## Sources (saved excerpts in raw/)
- [Wikipedia: World model (artificial intelligence)](https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)) → [raw/articles/wikipedia-world-models.md](../raw/articles/wikipedia-world-models.md)
- [Wikipedia: Genie (world model)](https://en.wikipedia.org/wiki/Genie_(world_model)) → [raw/articles/wikipedia-genie-world-model.md](../raw/articles/wikipedia-genie-world-model.md)
- [Meta AI: I-JEPA](https://ai.meta.com/blog/yann-lecun-ai-model-i-jepa/)
