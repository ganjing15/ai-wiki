---
title: Anthropic
created: 2026-04-10
updated: 2026-04-30
type: entity
tags: [lab, company, model, alignment]
sources: [raw/articles/wikipedia-anthropic.md, raw/articles/wikipedia-claude.md, raw/articles/claude-com-product-overview.md]
---

# Anthropic

## Infobox (per [Wikipedia: Anthropic](https://en.wikipedia.org/wiki/Anthropic))
Raw excerpt: [wikipedia-anthropic.md](../raw/articles/wikipedia-anthropic.md)

| Field | Value |
|-------|-------|
| Founded | 2021 |
| Headquarters | 500 Howard Street, San Francisco, California |
| CEO | Dario Amodei |
| President | Daniela Amodei |
| Industry | Artificial Intelligence |
| Employees | 2,500 (2026) |

**Founders (verbatim):** Dario Amodei, Daniela Amodei, Jared Kaplan, Jack Clark, Chris Olah, Ben Mann, Sam McCandlish, Tom Brown.

## Funding rounds (per [Wikipedia: Anthropic](https://en.wikipedia.org/wiki/Anthropic))
| Round | Date | Amount | Valuation |
|-------|------|--------|-----------|
| Series E | March 2025 | $3.5B | $61.5B |
| Series F | September 2025 | $13B | $183B |
| Series G | February 2026 | $30B | $380B |

**Strategic investors:**
- Google: $500M (October 2023) + $1.5B committed + $1B (March 2025)
- Amazon: $1.25B (September 2023) + $2.75B (March 2024) + $4B (November 2024)

## Models
The active Claude lineup as of 2026-04-30, per [Wikipedia: Claude (language model)](https://en.wikipedia.org/wiki/Claude_(language_model)) (raw: [wikipedia-claude.md](../raw/articles/wikipedia-claude.md)):

- Claude Opus 4.7 (2026-04-16)
- Claude Sonnet 4.6 (2026-02-17)
- Claude Haiku 4.5 (2025-10-15)
- Claude Mythos (2026-04-07, "Limited availability")
- Plus several earlier 4.x models still listed Active (Opus 4.6, Opus 4.5, Sonnet 4.5, Opus 4.1)

For full version history see [[Claude 4]] and [[Claude 3]].

## Products (per [Wikipedia: Anthropic](https://en.wikipedia.org/wiki/Anthropic) and [claude.com/product/overview](https://claude.com/product/overview))
- Claude
- **Claude Code** — Wikipedia describes as "a command-line AI agent for coding"
- **Claude Cowork** — Wikipedia describes as "graphical interface version"; claude.com adds: "works with your local files and cloud-based apps to organize folders, build spreadsheets, or prepare reports"
- Claude Design (Wikipedia)
- Claude for Chrome / Slack / Excel / PowerPoint / Word (claude.com)
- Claude Skills (claude.com)
- Acquired Bun (developer tool, per Wikipedia)

## Constitutional AI (verbatim, [Wikipedia: Anthropic](https://en.wikipedia.org/wiki/Anthropic))
> "Constitutional AI represents Anthropic's framework where 'the LLM is trained to adhere to a set of principles' through a defined constitution guiding system behavior."

See [[Constitutional AI]] for details.

## Responsible Scaling Policy (verbatim, [anthropic.com/news](https://www.anthropic.com/news/anthropics-responsible-scaling-policy))
Raw: [anthropic-rsp.md](../raw/articles/anthropic-rsp.md). Published **2023-09-19**.

> "A series of technical and organizational protocols that we're adopting to help us manage the risks of developing increasingly capable AI systems."

**AI Safety Levels (verbatim):**
- ASL-1: "systems which pose no meaningful catastrophic risk, for example a 2018 LLM or an AI system that only plays chess"
- ASL-2: "systems that show early signs of dangerous capabilities – for example ability to give instructions on how to build bioweapons – but where the information is not yet useful due to insufficient reliability"
- ASL-3: "systems that substantially increase the risk of catastrophic misuse compared to non-AI baselines (e.g. search engines or textbooks) OR that show low-level autonomous capabilities"
- ASL-4+: "not yet defined as it is too far from present systems, but will likely involve qualitative escalations in catastrophic misuse potential and autonomy"

ASL-3 commitment (verbatim): "not to deploy ASL-3 models if they show any meaningful catastrophic misuse risk under adversarial testing by world-class red-teamers."

### Current RSP version (verbatim, [anthropic.com/responsible-scaling-policy](https://www.anthropic.com/responsible-scaling-policy))
Raw: [anthropic-rsp-v3.md](../raw/articles/anthropic-rsp-v3.md).

- **RSP v3.2**, effective **2026-04-29**
- The current page references "ASL-3 Security Standard" and "ASL-3 Deployment Standard" thresholds, plus an "AI R&D capability threshold."
- Red-teaming commitment (verbatim): "Partner with a diverse range of external red team and penetration testing experts. Simulate sophisticated attacks, including insider threat and software supply chain compromise scenarios, to identify vulnerabilities."

(Full ASL-1 through ASL-4 definitions in v3.2 are in the policy PDF, not the summary page — the 2023-09-19 version cited above remains the canonical source for the ASL framework definitions in this wiki.)

## Notes on what was removed
The previous version of this page included:

- "Founded by former OpenAI researchers" — not in saved excerpts (true historically, but should cite)
- Specific benchmark numbers (MMLU 86.8%, GPQA 50.4%, 70.3% SWE-bench, "1.34M interpretable features in Claude") — not in saved sources
- "ASL-1 through ASL-4" RSP detail — not in saved sources
- "Many-shot Jailbreaking (Apr 2024)" — not in saved sources
- "Model Welfare commitments (2024)" — not in saved sources
- Older valuation numbers ($18B 2024, $60B+ 2025) — superseded by Series E/F/G data above

These will be re-added with citations after fetching:
- https://www.anthropic.com/news/anthropic-raises-series-c (and follow-on round announcements)
- https://www.anthropic.com/responsible-scaling-policy
- https://www.anthropic.com/research (interpretability + Many-shot Jailbreaking papers)

## Related Pages
[[Claude 3]] | [[Claude 4]] | [[Constitutional AI]] | [[Dario Amodei]] | [[OpenAI]] | [[AI Alignment]] | [[Interpretability]]

## Sources (saved excerpts in raw/)
- [Wikipedia: Anthropic](https://en.wikipedia.org/wiki/Anthropic) → [raw/articles/wikipedia-anthropic.md](../raw/articles/wikipedia-anthropic.md)
- [Wikipedia: Claude (language model)](https://en.wikipedia.org/wiki/Claude_(language_model)) → [raw/articles/wikipedia-claude.md](../raw/articles/wikipedia-claude.md)
- [claude.com/product/overview](https://claude.com/product/overview) → [raw/articles/claude-com-product-overview.md](../raw/articles/claude-com-product-overview.md)
