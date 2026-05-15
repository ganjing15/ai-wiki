# Anthropic — Scaling Monosemanticity
Source: https://transformer-circuits.pub/2024/scaling-monosemanticity/
Direct fetch returned content-length error (>10MB); content below from WebSearch summary, 2026-04-30. Flagged for direct fetch via curl/archive once a smaller URL exists.

## Title
"Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet"

## Publication date
2024-05-21

## Subject
Interpretability features extracted from Claude 3 Sonnet (production model, released 2024-03-04).

## Autoencoder sizes (from search summary)
"The research trained autoencoders of different sizes (~1M, ~4M, and ~34M features)."

## Note on "1.34M features" claim
The wiki's previous "1.34 million features" claim appears to **conflate the ~1M autoencoder size** with a more specific figure. The search summary lists three sizes (~1M, ~4M, ~34M) — none of which is exactly "1.34M". This requires direct verification against the paper text. The closest to "1.34M" would presumably be the largest autoencoder evaluated on a Claude variant; needs primary-source confirmation.

## Key qualitative findings (from search summary)
"The researchers found a diversity of highly abstract features that both respond to and behaviorally cause abstract behaviors."
"Systematic correlation between the frequency of a concept in the training data and the probability of locating a corresponding feature, with the likelihood of dedicated features for rare concepts being significantly lower."

## TODO
- Fetch the actual paper at smaller granularity (transformer-circuits.pub returns >10MB).
- Confirm the exact "1.34M" figure in the paper itself.
- Extract the famous "Golden Gate Bridge feature" example if present.
