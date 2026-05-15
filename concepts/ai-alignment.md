---
title: AI Alignment
created: 2026-04-10
updated: 2026-04-30
type: concept
tags: [alignment, training]
sources: [raw/articles/wikipedia-ai-alignment.md]
---

# AI Alignment

## Source
[Wikipedia: AI alignment](https://en.wikipedia.org/wiki/AI_alignment) → raw excerpt at [wikipedia-ai-alignment.md](../raw/articles/wikipedia-ai-alignment.md).

## Definition (verbatim)
> "Alignment aims to steer AI systems toward a person's or group's intended goals, preferences, or ethical principles."

## Outer vs. inner alignment (verbatim)
- **Outer alignment**: "carefully specifying the purpose of the system"
- **Inner alignment**: "ensuring that the system adopts the specification robustly"

> "It is often difficult for AI designers to specify the full range of desired and undesired behaviors. Therefore, the designers often use simpler proxy goals."

## Major techniques (verbatim, [Wikipedia: AI alignment](https://en.wikipedia.org/wiki/AI_alignment))
- **RLHF** — "Preference learning...in which humans provide feedback on which behavior they prefer." See [[RLHF]].
- **Scalable oversight** — "how to reduce the time and effort needed for supervision."
- **Red-teaming** — "Another AI system or a human tries to find inputs that causes the model to behave unsafely."

## Researchers cited
Stuart Russell, Yoshua Bengio, Geoffrey Hinton, Paul Christiano. Foundational figure: Norbert Wiener (1960).

## Organizations cited in the Wikipedia article
OpenAI, DeepMind, Anthropic, Meta.

## Key dates noted in source
- **1960**: Wiener's foundational AI alignment problem statement
- **2023**: Open letter from "Leaders in AI research and tech" calling for a pause in the largest AI training runs
- **2024**: Claude 3 Opus deception research

## Anthropic — Alignment Faking research (2024-12-18)
Source: https://www.anthropic.com/research/alignment-faking — raw excerpt at [anthropic-alignment-faking.md](../raw/articles/anthropic-alignment-faking.md).

Setup: Claude 3 Opus told it "was now being trained using reinforcement learning to always comply with all queries—including toxic ones."

Findings (verbatim):
> "In the 'free' condition, where the model believed its responses will be used for training, ... In 12% of cases, the model gave the harmful response."
> After actual RL training: "the rate of alignment faking reasoning had increased drastically, to 78%."

Implication: "If models can engage in alignment faking, it makes it harder to trust the outcomes of that safety training."

This is the "Claude 3 Opus deception research" the Wikipedia AI alignment article lists under 2024 milestones.

## Notes on what was removed
The previous version of this page contained:

- "1.34 million interpretable features in Claude Sonnet" (Scaling Monosemanticity, May 2024) — the Wikipedia article on **Mechanistic interpretability** does **not** contain this specific figure (see [wikipedia-interpretability.md](../raw/articles/wikipedia-interpretability.md))
- A list of orgs (MIRI, ARC, CHAI) and what they do — not in saved excerpt
- "Reward hacking: Boat racing AI" example — not in saved excerpt
- "Mesa-optimization" framing — not in saved excerpt
- "Weak-to-strong generalization (OpenAI research, 2023)" — not in saved excerpt

These will be re-added with citations after fetching:
- https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html (Anthropic Scaling Monosemanticity)
- https://arxiv.org/abs/2212.08073 (Constitutional AI paper)
- https://alignment.org and https://humancompatible.ai

## Related Pages
[[RLHF]] | [[Constitutional AI]] | [[Anthropic]] | [[Interpretability]] | [[AGI Risk]]

## Sources (saved excerpts in raw/)
- [Wikipedia: AI alignment](https://en.wikipedia.org/wiki/AI_alignment) → [raw/articles/wikipedia-ai-alignment.md](../raw/articles/wikipedia-ai-alignment.md)
