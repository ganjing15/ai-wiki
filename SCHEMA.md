# Wiki Schema

## Domain
Post-ChatGPT AI knowledge base (2022–present). Covers:
- Major model releases and capabilities (LLMs, multimodal, vision, audio, code, agents)
- Research publications and technical advances (transformers, RLHF, MoE, scaling laws, etc.)
- AI labs and organizations (OpenAI, Anthropic, Google DeepMind, Meta AI, etc.)
- Benchmarks and evaluations (MMLU, HumanEval, GPQA, HELM, etc.)
- AI safety, alignment, and security incidents
- Regulatory developments (EU AI Act, US EO, China regulations, etc.)
- Societal and economic impacts (jobs, creative industries, education, etc.)
- Business and investment landscape (funding rounds, acquisitions, valuations)

## Directory Structure
```
wiki/
├── SCHEMA.md           # This file
├── index.md            # Content catalog (update every ingest)
├── log.md              # Append-only action log
├── raw/                # Immutable source material (never edit)
│   ├── articles/       # Web articles, blog posts, clippings
│   ├── papers/         # arXiv papers, reports
│   ├── transcripts/    # Interviews, talks
│   └── assets/         # Images, charts
├── entities/           # People, orgs, models, products
├── concepts/           # Technical concepts, techniques, paradigms
├── comparisons/        # Side-by-side analyses
├── queries/            # Filed query results worth keeping
├── events/             # Dated AI events, milestones, releases
├── regulations/        # Policy, law, governance documents
└── security/           # Safety incidents, vulnerabilities, red-teaming
```

## Conventions
- File names: lowercase, hyphens, no spaces (e.g., `gpt-4.md`, `eu-ai-act.md`)
- Every wiki page starts with YAML frontmatter (see below)
- Use `[[wikilinks]]` to link between pages — minimum 3 outbound links per page
- When updating a page, always bump the `updated` date
- Every new page must be added to `index.md` under the correct section
- Every session's actions must be appended to `log.md`
- Dates always in ISO format: YYYY-MM-DD

## Frontmatter Template
```yaml
---
title: Page Title
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: entity | concept | comparison | query | event | regulation | security
tags: [from taxonomy below]
sources: [raw/articles/source-name.md]
---
```

## Tag Taxonomy
All tags used on any page MUST appear here. Add new tags to this list before using them.

### Model / Architecture
- `model` — a specific AI model release
- `architecture` — neural network design (transformer, diffusion, SSM, MoE, etc.)
- `multimodal` — vision, audio, video + language
- `agent` — autonomous agent systems, tool use, agentic AI
- `code-model` — models focused on coding tasks
- `reasoning` — chain-of-thought, o1-style reasoning models

### Training / Research
- `training` — training methods, RLHF, DPO, fine-tuning, data
- `scaling` — scaling laws, compute, infrastructure
- `benchmark` — evaluation suites, leaderboards, SOTA results
- `alignment` — AI alignment, safety, value learning
- `interpretability` — mechanistic interpretability, explainability

### Organizations
- `lab` — AI research lab or company (OpenAI, Anthropic, etc.)
- `company` — tech company with significant AI involvement
- `person` — researcher, executive, policymaker
- `open-source` — open-source models, frameworks, communities

### Events / Impact
- `event` — dated milestone, announcement, release, incident
- `regulation` — policy, law, executive order, international treaty
- `security` — jailbreaks, adversarial attacks, data poisoning, misuse
- `safety-incident` — real-world AI harms, near-misses
- `economic-impact` — jobs, markets, industries affected by AI
- `geopolitics` — US/China competition, export controls, sovereignty

### Meta
- `timeline` — chronological overview of a topic's evolution
- `comparison` — contrasting models, approaches, orgs
- `controversy` — debates, disputes, contradictory claims
- `prediction` — forecasts and their outcomes

## Page Thresholds
- **Create a page** when an entity/concept appears in 2+ sources OR is central to one source
- **Add to existing page** when a source mentions something already covered
- **DON'T create** for passing mentions or minor details
- **Split a page** when it exceeds ~200 lines
- **Archive** when content is fully superseded → move to `_archive/`

## Update Policy
When new information conflicts with existing content:
1. Check dates — newer sources generally supersede
2. If genuinely contradictory, note both with dates and sources
3. Mark: `contradictions: [page-name]` in frontmatter
4. Flag for user review in lint reports

## Source Priority (highest to lowest)
1. Official lab/org announcements (OpenAI blog, Anthropic blog, etc.)
2. Peer-reviewed papers (arXiv, NeurIPS, ICML, ICLR, ACL)
3. Stanford AI Index Report (annual, authoritative statistics)
4. Curated newsletters (The Batch, Import AI)
5. Major journalism (FT, NYT, Bloomberg, Politico)
6. Wikipedia (good for timelines, well-sourced summaries)
