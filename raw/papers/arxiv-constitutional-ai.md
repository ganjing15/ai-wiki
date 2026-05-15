# arXiv: Constitutional AI — Harmlessness from AI Feedback
Source: https://arxiv.org/abs/2212.08073
Fetched: 2026-04-30

## Title
"Constitutional AI: Harmlessness from AI Feedback"

## Authors
51 authors including Yuntao Bai, Saurav Kadavath, Sandipan Kundu, Amanda Askell. Anthropic affiliation per context.

## Submission
2022-12-15

## Abstract (verbatim)
"As AI systems become more capable, we would like to enlist their help to supervise other AIs. We experiment with methods for training a harmless AI assistant through self-improvement, without any human labels identifying harmful outputs. The only human oversight is provided through a list of rules or principles, and so we refer to the method as 'Constitutional AI'. The process involves both a supervised learning and a reinforcement learning phase. In the supervised phase we sample from an initial model, then generate self-critiques and revisions, and then finetune the original model on revised responses. In the RL phase, we sample from the finetuned model, use a model to evaluate which of the two samples is better, and then train a preference model from this dataset of AI preferences. We then train with RL using the preference model as the reward signal, i.e. we use 'RL from AI Feedback' (RLAIF)."

## SL+RL phases (verbatim)
**SL phase**: "sample from an initial model, then generate self-critiques and revisions, and then finetune the original model on revised responses."

**RL phase**: "sample from the finetuned model, use a model to evaluate which of the two samples is better, and then train a preference model from this dataset of AI preferences."
