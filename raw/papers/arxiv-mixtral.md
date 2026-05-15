# arXiv: Mixtral of Experts
Source: https://arxiv.org/abs/2401.04088
Fetched: 2026-04-30

## Title
"Mixtral of Experts"

## Authors
26 authors including Albert Q. Jiang, Alexandre Sablayrolles, Antoine Roux. Affiliation Mistral AI (per context).

## Submission
2024-01-08

## Architecture (verbatim)
"Each token only sees two experts, the selected experts can be different at each timestep. As a result, each token has access to 47B parameters, but only uses 13B active parameters during inference."

- Total: 47B
- Active per token: 13B
- Experts: 8 feedforward blocks
- Active per token: 2

(Note: The Wikipedia "Mixture of experts" page lists Mixtral 8x7B as "46.7B parameters" — slight rounding difference. Use the paper's figure.)

## Benchmarks (verbatim)
"Mixtral outperforms or matches Llama 2 70B and GPT-3.5 across all evaluated benchmarks. In particular, Mixtral vastly outperforms Llama 2 70B on mathematics, code generation, and multilingual benchmarks."

Instruct variant: "surpasses GPT-3.5 Turbo, Claude-2.1, Gemini Pro, and Llama 2 70B-chat model on human benchmarks."
