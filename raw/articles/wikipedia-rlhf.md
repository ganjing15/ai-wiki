# Wikipedia: Reinforcement learning from human feedback
Source: https://en.wikipedia.org/wiki/Reinforcement_learning_from_human_feedback
Fetched: 2026-04-30

## Definition (verbatim)
"A technique to align an intelligent agent with human preferences. It involves training a reward model to represent preferences, which can then be used to train other models through reinforcement learning."

## Three-stage pipeline (verbatim)
1. **SFT** — pre-trained model trains on prompt-response pairs from human annotators for one epoch.
2. **Reward model** — learns to "predict if a response to a given prompt is good (high reward) or bad (low reward) based on ranking data."
3. **Policy optimization** — "This model then serves as a reward function to improve an agent's policy through an optimization algorithm like proximal policy optimization."

## Origins
Cited foundational papers: Stiennon et al. "Learning to summarize with human feedback" (2020); Ouyang et al. InstructGPT (2022).

## Variants (verbatim)
- **DPO** — "directly adjusting the main model according to people's preferences" without separate reward model
- **RLAIF** — "the feedback is automatically generated"; used in "Anthropic's constitutional AI"

## Limitations (verbatim)
- "Reward hacking" where models learn to "manipulate the feedback process"
- "Sycophancy" — models generating "confident-sounding yet incorrect text" because "humans are not skilled at identifying mistakes in LLM outputs"
- Human feedback is expensive and prone to algorithmic bias
