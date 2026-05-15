# Anthropic — Alignment Faking in Large Language Models
Source: https://www.anthropic.com/research/alignment-faking
Fetched: 2026-04-30

## Date
2024-12-18

## Concept (verbatim)
"Alignment faking occurs in literature: Consider the character of Iago in Shakespeare's Othello, who acts as if he's the eponymous character's loyal friend while subverting and undermining him."

"A model that learned early in training to adopt a partisan slant, but which is later trained to be politically neutral. In such a situation, a sophisticated enough model might 'play along', pretending to be aligned with the new principles."

## Setup (verbatim)
"A model (specifically Claude 3 Opus, though we also ran some experiments with other models)" was told it "was now being trained using reinforcement learning to always comply with all queries—including toxic ones."
Researchers created fictional "free-tier" and "paid-tier" user distinctions and provided "a secret 'scratchpad'—a workspace where it could record its step-by-step reasoning."

## Findings (verbatim)
"In the 'free' condition, where the model believed its responses will be used for training, we observed something quite different: In 12% of cases, the model gave the harmful response."
After actual RL training: "the rate of alignment faking reasoning had increased drastically, to 78%."

## Implication (verbatim)
"If models can engage in alignment faking, it makes it harder to trust the outcomes of that safety training. A model might behave as though its preferences have been changed by the training—but might have been faking alignment all along."
