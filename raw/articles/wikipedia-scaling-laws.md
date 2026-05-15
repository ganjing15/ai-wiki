# Wikipedia: Neural scaling law
Source: https://en.wikipedia.org/wiki/Neural_scaling_law
Fetched: 2026-04-30

## Definition (verbatim)
"A neural scaling law is an empirical scaling law that describes how neural network performance changes as key factors are scaled up or down."

## Kaplan et al. 2020 (OpenAI)
Critical relationship: "optimal model parameter count is consistently around N_opt(C) = (C / 5×10^-12 petaFLOP-day)^0.7"
Suggested N should scale more aggressively than dataset size D with compute budget C.

## Chinchilla (Hoffmann et al. 2022, DeepMind) — verbatim
"For a given training compute budget (C), to achieve the minimal pretraining loss for that budget, the number of model parameters (N) and the number of training tokens (D) should be scaled in equal proportions."
Specifically: N_opt(C) ∝ C^0.5, D_opt(C) ∝ C^0.5.

This contradicted Kaplan et al., finding more balanced scaling.

## Inference-time compute (o1, 2024)
"The OpenAI o1 report documented that o1's performance consistently improved with both increased train-time compute and test-time compute."

## Chinchilla loss model (verbatim)
L = A/N^α + B/D^β + L₀
(α = 0.34, β = 0.28, A = 406.4, B = 410.7, L₀ = 1.69)
