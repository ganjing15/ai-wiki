# Wikipedia: Mixture of experts
Source: https://en.wikipedia.org/wiki/Mixture_of_experts
Fetched: 2026-04-30

## Definition (verbatim)
"MoE is a machine learning technique where multiple expert networks (learners) are used to divide a problem space into homogeneous regions."

## Sparse activation (verbatim)
"The output for each query can only involve a few experts' outputs."
Sparsely-gated approach uses "a weighted sum of only the top-k experts, instead of the weighted sum of all of them."

## Gating function (verbatim)
"A weighting function (also known as a gating function) takes input x and produces a vector of outputs."
Modern form: w(x) = softmax(top_k(Wx + noise)) — noise aids load balancing.

## Historical references
Jacobs et al. (1991) "Adaptive Mixtures of Local Experts" — foundational probabilistic approach. Connections to "committee machines" terminology and Hinton's neural-network ensemble work.

## Modern LLMs using MoE (verbatim)
- **Mixtral 8x7B** (Mistral AI, December 2023): "46.7B parameters, 8 experts, and sparsity 2"
- **DBRX** (Databricks, March 2024): "132B parameters, 16 experts, and sparsity 4"
- DeepSeek models use MoE variants with shared and routed experts

GPT-4's architecture remains unconfirmed by OpenAI.
