# Wikipedia: Constitutional AI
Source: https://en.wikipedia.org/wiki/Constitutional_AI
Fetched: 2026-04-30

## What it is (verbatim)
"An approach to AI alignment called 'Constitutional AI'" where "The constitution is a document used for training Claude to be harmless and helpful without relying on extensive or expensive human feedback."

## Two-phase process (verbatim)
**Supervised Learning Phase**: "the model generates responses to prompts, self-critiques these responses based on a set of guiding principles (a 'constitution'), and revises the responses. Then the model is fine-tuned on these revised responses."

**Reinforcement Learning Phase**: "responses are generated, and an AI compares their compliance with the constitution. This dataset of AI feedback is used to train a preference model that evaluates responses based on how much they satisfy the constitution."

## Constitution evolution (verbatim)
- Original (2022): "The first constitutions included concepts taken from the 1948 UN Universal Declaration of Human Rights."
- 2023 update: "listed 75 guidelines for Claude to follow."
- 2026 update: "provided more context to the model, explaining the rationale behind guidelines such as refraining from assisting in undermining democracy." Length: "23,000 words, an increase from 2,700 in 2023."

## Foundational paper
"Constitutional AI: Harmlessness from AI Feedback" (Anthropic, December 2022).
