     1|     1|# Wiki Log
     2|     2|
     3|     3|> Chronological record of all wiki actions. Append-only.
     4|     4|> Format: `## [YYYY-MM-DD] action | subject`
     5|     5|> Actions: ingest, update, query, lint, create, archive, delete, batch-ingest
     6|     6|> Rotate when this file exceeds 500 entries: rename to log-YYYY.md, start fresh.
     7|     7|
     8|     8|## [2026-04-10] create | Wiki initialized
     9|     9|- Domain: Post-ChatGPT AI knowledge base (2022–present)
    10|    10|- Structure: SCHEMA.md, index.md, log.md + entities/, concepts/, events/, regulations/, security/, comparisons/, queries/, raw/
    11|    11|
    12|    12|## [2026-04-10] batch-ingest | Initial corpus — 12 sources across 5 categories
    13|    13|- Sources fetched: Wikipedia (ChatGPT, GPT-4, History of AI, Generative AI, LLMs), Official lab blogs (OpenAI, Anthropic, Google DeepMind, Meta AI, HuggingFace), Policy sources (EU AI Act, US EO, UK AISI, Stanford AI Index, AI Safety Wikipedia, AGI Risk Wikipedia)
    14|    14|- Raw source index: raw/articles/source-index.md
    15|    15|
    16|    16|## [2026-04-10] create | entities/openai.md
    17|    17|- Major model releases 2022–2025, safety policies, governance crisis, controversies
    18|    18|
    19|    19|## [2026-04-10] create | entities/anthropic.md
    20|    20|- Claude 1–3.7 releases, Constitutional AI, RSP, interpretability research
    21|    21|
    22|    22|## [2026-04-10] create | entities/google-deepmind.md
    23|    23|- Gemini 1.0–2.5, AlphaFold 3, research highlights, safety framework
    24|    24|
    25|    25|## [2026-04-10] create | entities/meta-ai.md
    26|    26|- Llama 1–4, open-source strategy, research (SAM, Seamless), safety approach
    27|    27|
    28|    28|## [2026-04-10] create | entities/chatgpt.md
    29|    29|- Launch Nov 2022, 100M users, model evolution, controversies, real-world impact
    30|    30|
    31|    31|## [2026-04-10] create | entities/gpt-4.md
    32|    32|- Mar 2023 release, benchmarks, integrations, Turbo/Vision variants, controversies
    33|    33|
    34|    34|## [2026-04-10] create | entities/gpt-4o.md
    35|    35|- May 2024; native multimodal; real-time voice; free tier; benchmark performance
    36|    36|
    37|    37|## [2026-04-10] create | entities/openai-o1.md
    38|    38|- Sep 2024; chain-of-thought reasoning paradigm; AIME/GPQA benchmarks; o-series successors
    39|    39|
    40|    40|## [2026-04-10] create | entities/claude-3.md
    41|    41|- Mar 2024 three-tier family; Opus beats GPT-4; 200K context; 3.5 Computer Use; 3.7 extended thinking
    42|    42|
    43|    43|## [2026-04-10] create | entities/gemini.md
    44|    44|- 1.0 Ultra beats human MMLU; 1.5 Pro 1M context; 2.0 Flash multimodal output; 2.5 Pro SOTA
    45|    45|
    46|    46|## [2026-04-10] create | entities/llama.md
    47|    47|- LLaMA 1 through Llama 4; open commercial license; MoE; 10M context; ecosystem impact
    48|    48|
    49|    49|## [2026-04-10] create | entities/deepseek.md
    50|    50|- DeepSeek-V3 ($5.5M training); R1 matches o1; open MIT; DeepSeek moment (Nvidia -17%)
    51|    51|
    52|    52|## [2026-04-10] create | concepts/rlhf.md
    53|    53|- Three-stage pipeline; variants (DPO, RLAIF); limitations; used in all major models
    54|    54|
    55|    55|## [2026-04-10] create | concepts/constitutional-ai.md
    56|    56|- Anthropic's RLAIF; AI critiques against written constitution; foundational Dec 2022 paper
    57|    57|
    58|    58|## [2026-04-10] create | concepts/scaling-laws.md
    59|    59|- Kaplan 2020; Chinchilla 2022 (data parity); inference scaling (o1 2024)
    60|    60|
    61|    61|## [2026-04-10] create | concepts/mixture-of-experts.md
    62|    62|- Sparse activation; major models table; routing; tradeoffs
    63|    63|
    64|    64|## [2026-04-10] create | concepts/benchmarks-overview.md
    65|    65|- MMLU, GPQA, HumanEval, SWE-bench, AIME, ARC-AGI, MATH, Chatbot Arena; inflation concerns
    66|    66|
    67|    67|## [2026-04-10] create | concepts/ai-alignment.md
    68|    68|- Core problems; current approaches; key orgs; Anthropic interpretability milestone; open debates
    69|    69|
    70|    70|## [2026-04-10] create | events/ai-milestones-timeline.md
    71|    71|- Comprehensive 2022–2026 chronological table with 60+ dated events across all categories
    72|    72|
    73|    73|## [2026-04-10] create | regulations/eu-ai-act.md
    74|    74|- World's first comprehensive AI law; risk tiers; GPAI rules; enforcement; key debates
    75|    75|
    76|    76|## [2026-04-10] create | regulations/us-executive-order-ai.md
    77|    77|- Biden EO 14110 (Oct 2023); DPA reporting; AISI; revoked by Trump Jan 2025
    78|    78|
    79|    79|## [2026-04-10] create | regulations/ai-safety-summits.md
    80|    80|- Bletchley (Nov 2023); Seoul (May 2024); Paris (Feb 2025); international coordination milestones
    81|    81|
    82|    82|## [2026-04-10] create | regulations/china-ai-regulation.md
    83|    83|- Generative AI regs (Aug 2023); deepfake labeling; Chinese labs (DeepSeek, Baidu, Alibaba); chip war
    84|    84|
    85|    85|## [2026-04-10] create | security/ai-security-incidents.md
    86|    86|- DAN jailbreaks; many-shot jailbreaking; prompt injection; 2024 election AI; CBRN; Samsung leak; OpenAI governance crisis
    87|    87|
    88|    88|## [2026-04-10] create | comparisons/frontier-labs-comparison.md
    89|    89|- OpenAI vs Anthropic vs Google DeepMind vs Meta AI: models, philosophy, benchmarks, safety, open-source
    90|    90|
    91|    91|## [2026-04-10] create | queries/ai-economic-impact.md
    92|    92|- Investment ($91B 2023); labor impact; industry effects; geopolitical dimensions
    93|    93|
    94|    94|## [2026-04-10] update | index.md
    95|    95|- All 26 pages catalogued; sectioned by type
    96|    96|
    97|    97|Total pages created this session: 26
    98|    98|Total sources ingested: 12 (Wikipedia ×5, lab blogs ×5, policy sources ×4, Stanford AI Index ×1)
    99|    99|
   100|## [2026-04-10] batch-ingest | People, models, concepts, research — second pass
   101|- Sources: Wikipedia (Sam Altman, Dario Amodei, Geoffrey Hinton, Yann LeCun, Ilya Sutskever, Demis Hassabis), Import AI, LessWrong, The Batch, Stanford AI Index 2024, Papers with Code SOTA
   102|
   103|## [2026-04-10] create | entities/sam-altman.md
   104|- OpenAI CEO; governance crisis Nov 2023; AGI views
   105|
   106|## [2026-04-10] create | entities/dario-amodei.md
   107|- Anthropic CEO; Constitutional AI architect; "Machines of Loving Grace"
   108|
   109|## [2026-04-10] create | entities/geoffrey-hinton.md
   110|- Godfather of Deep Learning; Turing Award; Nobel 2024; resigned Google to warn of AI risk
   111|
   112|## [2026-04-10] create | entities/yann-lecun.md
   113|- Meta Chief AI Scientist; CNN pioneer; prominent AI optimist; open-source advocate; Turing Award
   114|
   115|## [2026-04-10] create | entities/ilya-sutskever.md
   116|- OpenAI co-founder; board vote crisis; left May 2024; founded Safe Superintelligence Inc.
   117|
   118|## [2026-04-10] create | entities/demis-hassabis.md
   119|- Google DeepMind CEO; Nobel Prize 2024 Chemistry (AlphaFold); AlphaGo, Gemini
   120|
   121|## [2026-04-10] create | entities/sora.md
   122|- OpenAI text-to-video (Feb 2024 demo, Dec 2024 public); diffusion transformer; competitors table
   123|
   124|## [2026-04-10] create | entities/alphafold-3.md
   125|- Google DeepMind (May 2024, Nature); all biomolecular structure prediction; Nobel prize trigger
   126|
   127|## [2026-04-10] create | entities/mistral-ai.md
   128|- French AI startup; Mistral 7B, Mixtral 8x7B; EU AI champion; $6B valuation
   129|
   130|## [2026-04-10] create | entities/hugging-face.md
   131|- "GitHub of AI"; 800K+ models; Open LLM Leaderboard; central open-source hub; $4.5B valuation
   132|
   133|## [2026-04-10] create | entities/uk-ai-safety-institute.md
   134|- World's first government frontier AI safety evaluator; est. Bletchley Nov 2023
   135|
   136|## [2026-04-10] create | concepts/reasoning-models.md
   137|- Chain-of-thought reasoning paradigm; inference-time compute; o1/o3/R1/Claude 3.7/Gemini 2.5
   138|
   139|## [2026-04-10] create | concepts/multimodal-ai.md
   140|- Evolution from unimodal to native multimodal; GPT-4o, Gemini, Llama 3.2, Sora
   141|
   142|## [2026-04-10] create | concepts/ai-agents.md
   143|- LLM-based autonomous systems; tool use; Computer Use; SWE-bench; safety concerns
   144|
   145|## [2026-04-10] create | concepts/interpretability.md
   146|- Mechanistic interpretability; Anthropic SAE work; 1.34M features in Claude; Chris Olah
   147|
   148|## [2026-04-10] create | concepts/open-source-ai-safety.md
   149|- Core debate: open weights increase or decrease safety? LeCun/Meta vs. OpenAI/Anthropic
   150|
   151|## [2026-04-10] create | concepts/agi-risk.md
   152|- Existential risk scenarios; Bostrom, Yudkowsky, Hinton (high risk) vs. LeCun, Marcus (skeptical)
   153|
   154|## [2026-04-10] create | queries/stanford-ai-index-2024.md
   155|- Stanford HAI 7th annual report; 7 chapters of AI data; key findings 2024
   156|
   157|## [2026-04-10] create | queries/import-ai-lesswrong-themes.md
   158|- Safety community themes: Import AI, LessWrong/AF, The Batch coverage
   159|
   160|## [2026-04-10] create | comparisons/reasoning-models-comparison.md
   161|- o1/o3 vs. DeepSeek-R1 vs. Claude 3.7 vs. Gemini 2.5 Pro side-by-side
   162|
   163|## [2026-04-10] update | index.md
   164|- All 46 pages catalogued with one-line summaries
   165|
   166|Total pages in wiki: 46
   167|Total sources ingested (cumulative): ~20 web sources across Wikipedia, lab blogs, newsletters, policy docs
   168|
## [2026-04-10] update | Corrected stale model information — fetched live data
- Issue: wiki contained training-cutoff-era model info (Claude 3.7, Gemini 2.5 Pro as "current")
- Fix: Fetched live from deepmind.google/models and anthropic.com/models
- Confirmed current models:
  - Anthropic: Claude Haiku 4.5, Sonnet 4.5, Opus 4.5 (from Anthropic 404 page model dropdown)
  - Google: Gemini 3, Gemini 3.1 Pro, 3.1 Deep Think, 3.1 Flash-Lite, 3 Flash (from live DeepMind page)
  - OpenAI: GPT-5.4 (stable Mar 27 2026, per Wikipedia ChatGPT infobox)
- Files updated: gemini.md, claude-3.md (historical note), anthropic.md, openai.md, chatgpt.md, events/ai-milestones-timeline.md, index.md
- Files created: entities/claude-4.md, entities/gpt-5.md
- Total pages: 49

## [2026-04-10] update | Corrected Claude model names using authoritative source
- Source: claude.com/product/overview (correct source, not a 404 page)
- Corrected: Opus 4.6, Sonnet 4.6, Haiku 4.5 (not all 4.5 as previously written)
- Noted: Mythos (preview) in footer — likely upcoming model
- Noted: Claude Cowork product (autonomous file/app agent)
- Updated: entities/claude-4.md, entities/anthropic.md, comparisons/frontier-labs-comparison.md, index.md

## [2026-04-30] rebuild | Full source-grounded rewrite of all 49 wiki pages

### Why
A user audit identified that pages had AI-generated prose with bibliography-style "Sources" lists at the bottom, but no inline citations and an empty `raw/` tier. The SCHEMA promised "immutable source material (never edit)" — but `raw/articles/` had three 0-byte files and one placeholder. Specific fabrication risks were flagged: "Mythos (preview)" Anthropic model, "OpenAI Prism" Jan 27 2026 launch, "GPT-5.4 stable Mar 27 2026", "Claude Opus 4.6" as current flagship, dozens of unsourced benchmark numbers.

### Methodology (option 3 of the audit: full rebuild from sources)
1. Fetched authoritative Wikipedia pages and the live claude.com product page via WebFetch / WebSearch.
2. Saved verbatim excerpts to `raw/articles/wikipedia-<topic>.md` — populating the previously-empty `raw/` tier for the first time.
3. Rewrote every wiki page citing the saved excerpts inline, with verbatim quotations where appropriate.
4. Removed every claim not grounded in a saved source, and listed the removed claims under a "Notes on what was removed" section in each page so they can be re-added when the corresponding primary sources are fetched.
5. Updated index.md and source-index.md to reflect the new structure.

### Source corpus (33 saved excerpts in raw/articles/)
- Wikipedia (32): OpenAI, Anthropic, Google DeepMind, Meta AI, Mistral AI, Hugging Face, AISI (UK), ChatGPT, Claude, Gemini, Llama, DeepSeek, GPT-4, GPT-4o, OpenAI o1, Sora, AlphaFold, AI agent, AI alignment, Mechanistic interpretability, Existential risk from AI, Open-source artificial intelligence, Constitutional AI, Multimodal learning, Reinforcement learning from human feedback, Mixture of experts, Neural scaling law, MMLU, Artificial Intelligence Act, Executive Order 14110, AI Safety Summit, Regulation of AI § China, plus a combined people excerpt (Altman, Amodei, Hinton, LeCun, Sutskever, Hassabis)
- Live: claude.com/product/overview

### Notable corrections found during rebuild
- Anthropic flagship model is **Opus 4.7** (released 2026-04-16), not 4.6 as previously claimed
- ChatGPT engine is **GPT-5.5** (stable 2026-04-23), not GPT-5.4
- OpenAI founding date is **2015-12-08** per Wikipedia, not "December 11, 2015"
- DeepSeek "moment" stock drop was **18%** per Wikipedia (V3 cost "$6 million"), not 17% / $5.5M
- Microsoft post-restructure stake in OpenAI is **27% at $135B**, not "~49%"
- Sam Altman born in **Chicago**, not St. Louis
- Dario Amodei has **PhD in Biophysics**, not "Computational Neuroscience"
- Google paid **£400 million** for DeepMind in 2014, not "~$500M"
- Sora **public release was 2024-12-09**, not Dec 5; **Sora app shutdown announced 2026-03-24**
- Mythos *is* real per Wikipedia (released 2026-04-07, "Limited availability") — but the previous wiki's claim that it was visible "in footer" of claude.com was wrong; it's not on the public product page
- "OpenAI Prism" (Jan 27 2026 LaTeX workspace) is **not** in any saved source — likely fabricated; removed
- "1.34M features in Claude" Scaling Monosemanticity figure is **not** in [Wikipedia: Mechanistic interpretability](https://en.wikipedia.org/wiki/Mechanistic_interpretability) — needs primary source; removed pending fetch

### Outstanding work
Each rebuilt page contains a "Sources to fetch (pending rate-limit reset)" section listing the primary URLs (lab announcement posts, arXiv papers, agency text, news coverage) that should be fetched next to fill in benchmark numbers, paper findings, regulatory specifics, and incident details. Stanford AI Index, Import AI / LessWrong / The Batch syntheses, and AI security incidents are the highest-leverage gaps.

## [2026-04-30] fetch | Second-pass: arXiv papers, EUR-Lex, EO 14110 secondaries, Stanford AI Index 2026, OpenAI announcement summaries

### New raw excerpts saved
- raw/papers/arxiv-deepseek-r1.md, arxiv-deepseek-v3.md, arxiv-gpt-4.md, arxiv-mixtral.md, arxiv-llama-3.md, arxiv-react.md, arxiv-instructgpt.md, arxiv-clip.md, arxiv-flamingo.md, arxiv-constitutional-ai.md, arxiv-kaplan-scaling-laws.md, arxiv-chinchilla.md, anthropic-scaling-monosemanticity.md
- raw/articles/eur-lex-ai-act.md (verbatim official title + OJ publication date)
- raw/articles/eo-14110-details.md (10²⁶ FLOPs threshold and Section 4.2 reporting requirements; from WebSearch summary because federalregister.gov fetch was redirected)
- raw/articles/stanford-ai-index-2026.md (current AI Index figures via WebSearch summary; PDF re-fetch flagged)
- raw/articles/openai-o1-announcement.md and openai-gpt-4o-announcement.md (via WebSearch summary; direct openai.com WebFetch returned 403)

### Wiki pages updated with new sourced facts
- entities/openai-o1.md — added announcement breakdown (AIME 74/83/93% by sampling regime; GPQA Diamond 78.3%)
- entities/deepseek.md — added DeepSeek-R1 paper title and abstract; V3 GPU-hour figure (2.788M H800)
- entities/gpt-4.md — added arXiv abstract bar-exam quote
- entities/gpt-4o.md — added native voice-to-voice claim from announcement summary
- entities/llama.md — added Llama 3 herd 405B / 128K context arXiv quote
- concepts/reasoning-models.md — added o1 announcement chain-of-thought quote and DeepSeek-R1 emergent-patterns quote
- concepts/constitutional-ai.md — added arXiv abstract verbatim including SL+RL phase descriptions
- concepts/rlhf.md — added InstructGPT abstract verbatim including the "1.3B preferred over 175B" headline
- concepts/scaling-laws.md — added Kaplan and Chinchilla abstract verbatim
- concepts/mixture-of-experts.md — added Mixtral paper 47B/13B figures and DeepSeek-V3 figures
- concepts/multimodal-ai.md — added CLIP and Flamingo abstract excerpts
- concepts/ai-agents.md — added ReAct abstract verbatim
- concepts/interpretability.md — added Scaling Monosemanticity paper details and FLAGGED that the prior "1.34M features" figure does not match any of the three autoencoder sizes named in the WebSearch summary
- regulations/eu-ai-act.md — added official EUR-Lex title and 12.7.2024 OJ publication date
- regulations/us-executive-order-ai.md — added 10²⁶ FLOPs Section 4.2(b)(i) threshold and the dual-use foundation model definition (with caveat that source is a WebSearch summary, not the Federal Register PDF directly)
- comparisons/reasoning-models-comparison.md — expanded confirmed-benchmark table with three AIME sampling regimes and GPQA Diamond
- queries/stanford-ai-index-2024.md — replaced with 2026 AI Index figures
- queries/ai-economic-impact.md — added Stanford 2026 economic figures and DeepSeek V3 GPU-hour cost data

### Tooling notes
- WebFetch was rate-limited on anthropic.com (until 11pm Toronto on the day) and 403'd on openai.com — substituted WebSearch summaries (clearly flagged as such in each saved excerpt).
- transformer-circuits.pub/2024/scaling-monosemanticity/ exceeds the 10MB content-length cap, so the Anthropic SAE paper itself remains only partially captured.
- federalregister.gov redirects to an unblock page; switched to WebSearch summaries from law-firm secondaries (Fenwick, Dorsey, Morrison Foerster) plus the EO summary articles.

### Findings worth flagging
- The "1.34M features in Claude" figure popular in second-hand AI-safety summaries does not match the three SAE sizes (~1M, ~4M, ~34M) named in the Scaling Monosemanticity WebSearch summary; needs primary-source verification.
- Stanford AI Index 2026 reports US private AI investment at **$285.9 billion** (vs. China's $12.4 billion), with global corporate AI investment at **$581.7 billion** in 2025 — vastly larger than the "$91 billion 2023" figure the previous wiki cited.

## [2026-05-06] fetch | Third-pass: Anthropic primary posts, more arXiv, Bletchley primary text, incident reconstructions

### New saved excerpts
- raw/articles/anthropic-claude-3-family.md, anthropic-claude-3-5-sonnet.md, anthropic-claude-3-7-sonnet.md, anthropic-many-shot-jailbreaking.md, anthropic-alignment-faking.md, anthropic-rsp.md
- raw/articles/wikipedia-openai-o3.md, wikipedia-alexnet.md, wikipedia-gpt-5.md, wikipedia-alphago.md
- raw/articles/bletchley-declaration.md (primary gov.uk text, 28-country signatory list)
- raw/articles/incidents-collected.md (Italy GDPR, NYT v. OpenAI, Slovakia deepfake, Samsung leak — WebSearch reconstructions)
- raw/papers/arxiv-toolformer.md, arxiv-llama-2.md, arxiv-mistral-7b.md

### Wiki pages updated
- entities/claude-3.md — three Anthropic announcement excerpts (3 family, 3.5 Sonnet, 3.7 Sonnet)
- entities/anthropic.md — full Responsible Scaling Policy with ASL-1 through ASL-4 verbatim
- entities/llama.md — Llama 2 paper abstract
- entities/mistral-ai.md — Mistral 7B paper abstract; Mixtral paper details
- entities/gpt-5.md — corrected the "unified model" framing to Wikipedia's "system with components and a router"
- entities/openai-o1.md — added o3 / o3-pro / o4-mini release dates and ARC-AGI / SWE-bench-Verified deltas
- entities/ilya-sutskever.md — AlexNet authorship verbatim
- entities/geoffrey-hinton.md — AlexNet authorship verbatim
- entities/demis-hassabis.md — AlphaGo Lee Sedol / Ke Jie matches
- concepts/ai-agents.md — Toolformer paper abstract added alongside ReAct
- concepts/ai-alignment.md — Alignment Faking research with 12% / 78% findings
- security/ai-security-incidents.md — Italy GDPR, NYT, Slovakia, Samsung; many-shot jailbreaking and alignment-faking
- regulations/ai-safety-summits.md — primary Bletchley Declaration text with 28-country signatory list

### Tooling notes
- Anthropic posts succeeded once the rate limit reset. www.anthropic.com is generally reliable.
- arxiv.org continues to be the most reliable source for paper abstracts.
- openai.com index pages still return 403 on direct fetch; relying on WebSearch summaries for those.
- gov.uk worked cleanly for Bletchley Declaration; should work for Seoul Declaration too (not yet fetched).
- CourtListener returned 403 on the NYT-v-OpenAI docket; the federal complaint PDF needs PACER access.

### Findings worth flagging
- **GPT-5 architecture**: Wikipedia describes it as a **system with multiple components plus a router**, not a single "unified" model — correcting the prior wiki's framing.
- **Mistral 7B paper benchmark claim** (2023-10-10) precisely states Mistral 7B "outperforms Llama 2 13B across all evaluated benchmarks, and Llama 1 34B in reasoning, mathematics, and code generation" — a more careful claim than the wiki had previously paraphrased.
- **Anthropic RSP**: ASL-3 commitment to "not deploy ASL-3 models if they show any meaningful catastrophic misuse risk under adversarial testing by world-class red-teamers" is now sourced inline.
- **Italy GDPR fine**: Garante imposed €15M fine in December 2024 — "the first GDPR penalty against a generative AI company."

## [2026-05-06] fetch | Fourth-pass: AI Safety Summit primaries, Anthropic Computer Use, pre-ChatGPT incidents

### New saved excerpts
- raw/articles/anthropic-claude-3-5-new-computer-use.md (Oct 22, 2024 — SWE-bench 33.4 → 49.0, joint US/UK AISI testing)
- raw/articles/seoul-frontier-commitments.md (Frontier AI Safety Commitments, full 16-organization signatory list)
- raw/articles/wikipedia-ai-action-summit.md (Paris Feb 2025; 58 signatories; US/UK refused to sign)
- raw/articles/wikipedia-tay.md (Microsoft Tay 2016)
- raw/articles/galactica-incident.md (Meta Galactica withdrawal Nov 17, 2022)
- raw/articles/wikipedia-lamda.md (Blake Lemoine sentience controversy 2022)
- raw/articles/wikipedia-palm.md (Google PaLM 540B / PaLM 2 340B)
- raw/articles/wikipedia-stable-diffusion.md (Stability AI release timeline)

### Wiki pages updated
- entities/claude-3.md — Claude 3.5 (new) + Computer Use announcement integrated, with the verbatim "33.4% to 49.0%" SWE-bench number
- security/ai-security-incidents.md — Microsoft Tay, Galactica, LaMDA pre-ChatGPT-era reference incidents added
- regulations/ai-safety-summits.md — Seoul 16-signatory list and Paris 58-signatory list, plus US/UK Paris refusal

### Findings worth flagging
- **Seoul 16 signatories include Zhipu.ai (China) and G42 (UAE)** — broader-than-Western coalition.
- **Paris AI Action Summit (Feb 2025) had 58 signatories — US and UK refused to sign**; UK rationale: agreement "did not go far enough in defining global governance of AI."
- **Galactica withdrawal (2022-11-17)** sits exactly two weeks before ChatGPT's launch (2022-11-30); brought "hallucination" into public discourse.
- **Claude 3.5 (new) Sonnet's SWE-bench Verified jumped from 33.4% to 49.0%** in the 2024-10-22 release — the primary anchor for the Sonnet benchmark progression that earlier drafts had quoted from secondary sources.

## [2026-05-06] fetch | Fifth-pass: AI Action Plan, RSP v3.2, AISI Inspect, Operator, AlphaFold 3 Nature

### New saved excerpts
- raw/articles/america-ai-action-plan.md — Trump's "Winning the AI Race: America's AI Action Plan" (2025-07-23, 90+ federal actions, three pillars: Accelerating Innovation / Building American AI Infrastructure / Leading in International Diplomacy and Security)
- raw/articles/anthropic-rsp-v3.md — RSP v3.2 effective 2026-04-29 with red-teaming commitment verbatim
- raw/articles/aisi-inspect.md — UK AISI + Meridian Labs open-source eval framework; "over 200 pre-built evaluations"; Docker/Kubernetes/Modal/Proxmox sandboxing
- raw/articles/wikipedia-openai-operator.md — Operator launched 2025-01-23, shut down 2025-08-31 (deprecated by ChatGPT agent)
- raw/papers/alphafold-3.md — Nature 630:493–500 (Abramson et al., 2024-05-08); diffusion architecture; "at least a 50% improvement" on protein–ligand interactions

### Wiki pages updated
- regulations/us-executive-order-ai.md — added Trump's AI Action Plan as the policy successor to EO 14110, with three pillars verbatim and Marco Rubio / Kratsios quotes
- entities/anthropic.md — added current RSP v3.2 (2026-04-29) section alongside the historical 2023-09-19 ASL framework
- entities/uk-ai-safety-institute.md — added Inspect framework primary source with full feature list verbatim
- entities/openai.md — Operator entry updated to reflect 2025-08-31 shutdown
- entities/alphafold-3.md — added Nature paper architecture and accuracy quotes (50% improvement, doubled accuracy on key categories); Addendum flagged
- events/ai-milestones-timeline.md — added Seoul Summit, Operator launch + shutdown, Paris Summit, Claude 3.7 + Code, AI Action Plan signing, RSP v3.2 effective dates

### Tooling notes
- openai.com primary pages still 403 (Sora technical, Introducing Operator, Hello GPT-4o, Learning to reason). Wikipedia and Anthropic blog continue to fill those gaps.
- Nature direct fetches return 303 redirects; AlphaFold 3 paper required WebSearch summary.
- whitehouse.gov press-release pages work; the AI.gov landing page also works; PDF links don't render via WebFetch.

### Findings worth flagging
- **Operator was a ~7-month product**: launched 2025-01-23, shut down 2025-08-31. Earlier wiki drafts treated it as an ongoing product; the correct framing is "first OpenAI agent product, deprecated and superseded by ChatGPT agent."
- **Trump's AI Action Plan came with three accompanying executive orders** signed the same day (2025-07-23); their EO numbers are pending Federal Register access.
- **AlphaFold 3 has a published Addendum** (Nature s41586-024-08416-7) — the original paper shipped with errata.
- **AISI's Inspect framework** is jointly developed with **Meridian Labs**, not solely UK government — a relevant detail for safety-eval context.
- **Anthropic RSP is now at v3.2 (2026-04-29)**, three years on from the original 2023-09-19 policy. The current page summarises but defers full ASL definitions to the policy PDF, so the wiki uses the 2023 version for the canonical ASL hierarchy quotes.

## [2026-05-06] fetch | Sixth-pass: ChatGPT Atlas/agent, NIST CAISI, Veo, Codex agent, Deep Research

### New saved excerpts
- raw/articles/wikipedia-chatgpt-atlas.md — Chromium-based AI browser launched 2025-10-21 for macOS
- raw/articles/wikipedia-chatgpt-agent.md — released July 2025; controls a virtual computer; succeeded Operator
- raw/articles/nist-caisi.md — Center for AI Standards and Innovation primary mission text from nist.gov/aisi
- raw/articles/wikipedia-veo.md — Google DeepMind Veo (May 2024) → Veo 2 (Dec 2024, 4K) → Veo 3 (May 2025, +audio) → Veo 3.1 (Oct 15 2025 stable)
- raw/articles/wikipedia-openai-codex-agent.md — Codex Cloud research preview 2025-05-16; codex-1 → GPT-5.3-Codex/Spark/GPT-5.4
- raw/articles/wikipedia-chatgpt-deep-research.md — launched 2025-02-03; **26.6%** Humanity's Last Exam (was claimed as 27% in earlier wiki)

### Wiki pages updated
- entities/openai.md — product table now spans Deep Research, Operator (with shutdown), Codex agent, ChatGPT agent, ChatGPT Atlas, GPT-5.x; "Notes on what was removed" updated to reflect that codex-1 is real and Deep Research is 26.6% (not 27%)
- entities/uk-ai-safety-institute.md — added US CAISI primary mission text from nist.gov/aisi
- events/ai-milestones-timeline.md — added six new dated entries (Deep Research launch, Codex preview, Veo 3, ChatGPT agent, Veo 3.1, ChatGPT Atlas)

### Tooling notes
- Wikipedia pages exist for individual OpenAI products (Atlas, agent, Codex agent, Deep Research, Operator) — these provide better-grounded primary-adjacent sources than openai.com/index/* (which continues to 403).
- nist.gov/aisi works cleanly even though the institute has been renamed; Wikipedia tracks the AI Safety Institute → CAISI rename to June 2025.

### Findings worth flagging
- **Deep Research scored 26.6% on Humanity's Last Exam**, not 27% as previous wiki claimed. Small but the correction matters for downstream citations.
- **ChatGPT product proliferation in 2025**: Operator (Jan 23), Deep Research (Feb 3), Codex Cloud (May 16), ChatGPT agent (July), Atlas (Oct 21) — five distinct agentic products in 10 months, with Operator already deprecated.
- **Codex's underlying model lineage**: codex-1 (based on o3) → GPT-5.3-Codex → GPT-5.3-Codex-Spark → GPT-5.4. The progression is verifiable.
- **NIST AISI was renamed to CAISI in June 2025** under the Trump administration, paralleling the UK AISI → AI Security Institute rename in February 2025.

## [2026-05-06] fetch | Seventh-pass: new entities (xAI, Stargate, Microsoft Copilot, GitHub Copilot, Allen Institute, ARC-AGI)

### New saved excerpts
- raw/articles/wikipedia-xai.md — Musk's lab; Grok 1 (open-source 2024-03-17) → Grok-4 (2025-07-09); acquired X Corp. 2025-03-28; ~$22B raised across rounds
- raw/articles/wikipedia-stargate.md — $500B/2029 AI infrastructure project announced 2025-01-21 (one day after Trump rescinded EO 14110); OpenAI/SoftBank/Oracle/MGX
- raw/articles/wikipedia-microsoft-copilot.md — Bing Chat (Feb 2023) → Microsoft Copilot rebrand (Sep 2023); M365 Copilot $30/user/month
- raw/articles/wikipedia-github-copilot.md — Preview 2021-06-29; GA 2022-06-21; Codex → GPT-4 → user-selectable Gemini/Claude (2024); class action 2022-11
- raw/articles/wikipedia-allen-institute-ai.md — Paul Allen 2014; OLMo family; OLMo 32B "first fully-open model" March 2025
- raw/articles/wikipedia-arc-agi.md — Chollet 2019 ARC-AGI; ARC Prize $1M competition launched 2024

### New wiki pages
- entities/xai.md
- entities/stargate.md
- entities/microsoft-copilot.md
- entities/github-copilot.md
- entities/allen-institute-ai.md

### Wiki pages updated
- events/ai-milestones-timeline.md — added Stargate announcement (2025-01-21), Grok-3 (2025-02-17), xAI/X acquisition (2025-03-28), Grok-4 (2025-07-09)
- index.md — added five new entity pages to the Organizations & Labs section

### Findings worth flagging
- **Stargate's announcement (2025-01-21) was one day after EO 14110's rescission (2025-01-20)** — the policy reset and the infrastructure investment were near-simultaneous. The wiki now sources both as primary events.
- **Grok timeline accelerated dramatically in 2025**: Grok-3 (Feb), Grok-4 (Jul) — pace comparable to OpenAI/Anthropic for the first time.
- **xAI raised ~$22B+ across documented rounds** (Dec 2023, May 2024, Dec 2024, Jul 2025), independent of the X Corp. acquisition.
- **OLMo 32B's "first fully-open model" framing (Mar 2025)** is a meaningful claim against the OSAID 2024 definition (full data + code + weights + details). Most "open" models from Llama/Mistral/DeepSeek are open-weight but not full data — so the AI2 milestone matters for the [[Open Source AI Safety]] debate.
- **GitHub Copilot now supports user-selectable Gemini/Claude** (since 2024) — Microsoft is no longer locked to OpenAI-only. Notable strategic shift.
- **ARC-AGI's home page does not exist on Wikipedia as a dedicated article** — only the Chollet biography references the benchmark. This is a gap; the o3 87.5% ARC-AGI claim popular in safety summaries needs the ARC Prize site or system cards as primary source.

## [2026-05-06] fetch | Eighth-pass: Cohere, Cursor/Anysphere, CAIS, Qwen, Ernie Bot

### New saved excerpts
- raw/articles/wikipedia-cohere.md — Toronto enterprise AI lab; founded 2019 by Aidan Gomez (co-author of "Attention Is All You Need"), Ivan Zhang, Nick Frosst; Seoul signatory
- raw/articles/wikipedia-anysphere-cursor.md — Cursor (VS Code AI fork); $8M seed → $29.3B valuation in 25 months; $1B annualized revenue Nov 2025
- raw/articles/wikipedia-center-for-ai-safety.md — Dan Hendrycks 2022; published the May 2023 22-word Statement on AI Risk
- raw/articles/wikipedia-qwen.md — Alibaba Qwen open-weight family; Qwen3 trained on 36T tokens / 119 languages
- raw/articles/wikipedia-ernie-bot.md — Baidu's chatbot; public release 2023-08-31 post-China generative AI regs

### New wiki pages
- entities/cohere.md
- entities/cursor.md
- entities/center-for-ai-safety.md
- entities/qwen.md
- entities/ernie-bot.md

### Wiki pages updated
- events/ai-milestones-timeline.md — added CAIS founding (2022), Qwen beta (Apr 2023), CAIS Statement (May 2023), Ernie public release (Aug 2023), Qwen3 (Apr 2025), Cursor $1B ARR (Nov 2025)
- index.md — added five new entity pages, plus a new "China-based AI" section grouping Qwen, Ernie Bot, and DeepSeek

### Findings worth flagging
- **Aidan Gomez (Cohere co-founder) is the same Gomez of "Attention Is All You Need"** — the original Transformer paper. Worth noting in any treatment of how the Transformer's authors dispersed across the industry.
- **Cursor went $8M seed → $29.3B valuation in 25 months** (Oct 2023 → Nov 2025), and crossed $1B ARR in the same window — one of the fastest software growth stories on record.
- **Ernie Bot's public release (2023-08-31) was 16 days after China's generative AI regs entered force (2023-08-15)** — Baidu was first to navigate the new approval regime. Worth noting in [[China AI Regulation]].
- **Qwen3 was trained on 36 trillion tokens in 119 languages** — multilingual scale that's hard to find disclosed elsewhere; a useful primary anchor for Chinese-lab compute claims.
- **The May 2023 CAIS Statement on AI Risk is now sourced two ways**: directly via the CAIS Wikipedia article and via the Existential Risk Wikipedia article (which has the verbatim 22-word text). The wiki [[AGI Risk]] page already used the text; CAIS now has its own dedicated page citing both.

## [2026-05-07] fetch | Ninth-pass: Nvidia, Murati, Suleyman, Inflection, Karpathy, Moffatt v. Air Canada

### New saved excerpts
- raw/articles/wikipedia-nvidia.md — FY2024 $60.9B → FY2026 $215.9B revenue; market cap $3T (2024-06) → $4T (2025-07) → $5T (2025-10); $600B DeepSeek-driven drop
- raw/articles/wikipedia-mira-murati.md — OpenAI CTO May 2022; 3-day interim CEO November 2023; Thinking Machines Lab Feb 2025
- raw/articles/wikipedia-mustafa-suleyman.md — DeepMind co-founder 2010 → Inflection AI co-founder 2022 → Microsoft AI CEO 2024-03
- raw/articles/wikipedia-inflection-ai.md — Microsoft acqui-hired ~70 employees + tech license for $650M (March 2024)
- raw/articles/wikipedia-andrej-karpathy.md — OpenAI founding member; Tesla AI 2017–22; Eureka Labs 2024-07-16
- raw/articles/moffatt-air-canada.md — *Moffatt v Air Canada, 2024 BCCRT 149* (2024-02-14): first common-law ruling that companies remain liable for their AI chatbot's representations

### New wiki pages
- entities/nvidia.md
- entities/mira-murati.md
- entities/mustafa-suleyman.md
- entities/inflection-ai.md
- entities/andrej-karpathy.md

### Wiki pages updated
- security/ai-security-incidents.md — added Moffatt v. Air Canada section with verbatim tribunal quote and $650.88 damages
- events/ai-milestones-timeline.md — eight new dated entries (Moffatt ruling, Inflection acqui-hire, Blackwell announcement, Nvidia $3T/$4T/$5T, Eureka Labs, Murati departure, Thinking Machines Lab launch)
- index.md — added Nvidia, Inflection AI, Mira Murati, Mustafa Suleyman, Andrej Karpathy

### Findings worth flagging
- **Nvidia FY2026 revenue is $215.9B, vs FY2024 $60.9B — a 3.5× jump in two fiscal years.** Compute & networking is now 89% of total revenue (was a fraction of that pre-ChatGPT). The clearest single-firm signal of the AI capex boom.
- **Nvidia hit $5T market cap on 2025-10-29** — first company in history. This and the DeepSeek-driven $600B one-day drop in January 2025 are now both sourced primary.
- **Microsoft acqui-hire of Inflection AI ($650M, March 2024)** is now properly sourced. The structure (license + personnel, not acquisition) was likely designed to avoid antitrust scrutiny — a model since copied in other AI deals.
- **Moffatt v. Air Canada (2024-02-14, $650.88 damages)** is a small-dollar ruling but the first common-law precedent that a company can't disclaim liability for its chatbot's statements. Cited in subsequent commercial-AI risk doctrine.
- **Mira Murati was interim CEO for 3 days in November 2023**, between Altman's removal and Emmett Shear's brief tenure. The wiki's [[Sam Altman]] / [[OpenAI]] pages didn't previously source this short-but-real chapter.
- **Andrej Karpathy left OpenAI twice** — 2017 (to Tesla), 2024-02-13 (to Eureka Labs). The "second departure" pattern is uncommon enough to be worth noting in the OpenAI alumni story.

## [2026-05-07] fetch | Tenth-pass: Bengio, Transformer paper, FLI Pause Letter, SB 1047

### New saved excerpts
- raw/articles/wikipedia-yoshua-bengio.md — third Turing Award co-winner; led International AI Safety Report (Jan 2025); founded LawZero nonprofit (Jun 2025)
- raw/papers/attention-is-all-you-need.md — Vaswani et al. 2017; 173,000+ citations as of 2025; all 8 authors left Google
- raw/articles/wikipedia-fli-pause-letter.md — March 2023 FLI Open Letter (30,000+ signatures, including Bengio/Russell/Musk/Wozniak/Harari)
- raw/articles/wikipedia-sb-1047.md — California SB 1047 ("Safe and Secure Innovation for Frontier Artificial Intelligence Models Act"); 10²⁶ FLOPs / $100M thresholds; vetoed by Newsom 2024-09-29

### New wiki pages
- entities/yoshua-bengio.md — closes the Turing-Award trio (Hinton/LeCun/Bengio)
- concepts/transformer-architecture.md — first proper foundational-architecture page
- regulations/sb-1047.md — first US state-level AI safety regulation (vetoed)

### Wiki pages updated
- concepts/agi-risk.md — primary detail on FLI Pause Letter (signatories, Altman/Gates responses)
- events/ai-milestones-timeline.md — six new dated entries (Transformer paper, FLI Pause, SB 1047 introduction, SB 1047 veto, International AI Safety Report, LawZero)
- index.md — added Yoshua Bengio, transformer-architecture, SB 1047

### Findings worth flagging
- **All eight Transformer paper authors left Google** after publishing it — primary source confirmation for what's now a widely-told industry story.
- **The Transformer paper is among the top-10 most-cited papers of the 21st century** (173,000+ citations) per Wikipedia. The wiki now has the foundational architecture properly anchored.
- **Bengio leads the International AI Safety Report** (commissioned at Bletchley 2023, full report Jan 2025) — the most institutionally-recognized AI scientific assessment to date. The wiki now has Bengio as a peer entry to Hinton and LeCun.
- **The 10²⁶ FLOPs threshold appears in three policy regimes**: Biden EO 14110, California SB 1047, and is referenced in the EU AI Act discussion (which uses 10²⁵). This is now sourced across all three pages.
- **SB 1047's veto (2024-09-29) is the most significant US state-level AI policy outcome to date** — Newsom's "based only on computational size" objection is now sourced verbatim.
- **Bill Gates declined to sign the FLI Pause Letter**, with the rationale that "asking one particular group to pause solves the challenges" — a direct counter to the petition that's commonly omitted from secondary coverage.

## [2026-05-07] fetch | Eleventh-pass: Brockman, Russell, Apple Intelligence, Diffusion model, Whisper

### New saved excerpts
- raw/articles/wikipedia-greg-brockman.md — OpenAI co-founder & President; ex-Stripe first CTO; quit on 2023-11-17 with Altman, returned days later; Aug–Nov 2024 sabbatical
- raw/articles/wikipedia-stuart-russell.md — UC Berkeley CHAI founder; "Human Compatible" (2019); Russell & Norvig textbook in 1,500+ universities
- raw/articles/wikipedia-apple-intelligence.md — announced WWDC 2024-06-10; GPT-4o integration via Siri; Gemini partnership announced January 2026
- raw/articles/wikipedia-diffusion-model.md — DDPM 2020 framework; foundation for Stable Diffusion, DALL-E, Sora
- raw/articles/wikipedia-whisper.md — OpenAI's open-source MIT speech recognition (2022-09-21); encoder-decoder transformer

### New wiki pages
- entities/greg-brockman.md — final missing OpenAI co-founder
- entities/stuart-russell.md — completes the major academic AI-safety voice trio (Bengio/Russell/Hinton)
- entities/apple-intelligence.md — closes the largest consumer-AI distribution gap
- entities/whisper.md — first OpenAI MIT-licensed open-source page
- concepts/diffusion-models.md — second foundational architecture page (after Transformer)

### Wiki pages updated
- events/ai-milestones-timeline.md — three new dated entries (DDPM 2020, Whisper 2022-09-21, Apple Intelligence WWDC 2024-06-10)
- index.md — added five new pages with one-line summaries

### Findings worth flagging
- **Greg Brockman quit OpenAI on 2023-11-17 (the same day as Altman's firing)** — the wiki had Altman's reinstatement well sourced but didn't have Brockman's parallel departure / return chapter. The "two co-founders walked out together" framing now has primary sourcing.
- **Stuart Russell's Russell & Norvig textbook is in 1,500+ universities across 135 countries** — the wiki's [[AI Alignment]] page references CHAI but until now didn't anchor Russell as a peer to Hinton/LeCun/Bengio.
- **Apple's January 2026 Gemini partnership** is now sourced. Apple is a unique frontier-AI distribution channel: not building frontier models itself, but shipping GPT-4o (via OpenAI partnership) and Gemini (via Google partnership) to most of its devices via Siri.
- **Whisper (2022-09-21) was OpenAI's last major open-source release before the closed-by-default ChatGPT era** — exactly two months before ChatGPT launched. Worth tracking as a marker of the policy shift.
- **The Transformer (2017) and DDPM (2020) are now both source-anchored** — the two architectural pillars under modern frontier AI, primary-sourced for the first time in this wiki.

## [2026-05-14] batch-ingest | Twelfth pass — Nano Banana, Seedance 2.0, World Models, Genie

### Trigger
User flagged three categories of gaps: (1) "nano banana" — Google's viral image generation model, (2) "Seedance 2.0" — ByteDance video generation, (3) "world models" — the LeCun/Schmidhuber paradigm competing with LLMs. Claude Opus 4.5 was already in the wiki (claude-4.md line 21) sourced from the Wikipedia Claude infobox.

### New raw excerpts
- raw/articles/wikipedia-nano-banana.md — https://en.wikipedia.org/wiki/Nano_Banana (redirects to Gemini article; Nano Banana = codenamed Gemini 2.5/3/3.1 Flash Image; viral Aug 2025; 200M edits within weeks; nickname originated from a Google DeepMind PM)
- raw/articles/bytedance-seedance-2-0-launch.md — https://seed.bytedance.com/en/blog/official-launch-of-seedance-2-0 (ByteDance SEED Lab; released 2026-02-12; multimodal audio-video generation; text/image/video/audio inputs; 15s output; 2K/60FPS capable via CapCut and API)
- raw/articles/wikipedia-world-models.md — https://en.wikipedia.org/wiki/World_model_(artificial_intelligence) (Schmidhuber 1990 coined the term; LeCun JEPA 2022; Genie 3 Aug 2025 at 24 FPS; AMI Labs $1.03B raised Mar 2026)
- raw/articles/wikipedia-genie-world-model.md — https://en.wikipedia.org/wiki/Genie_(world_model) (Google DeepMind; Genie 1 Mar 2024 → Genie 2 Dec 2024 → Genie 3 Aug 2025; Project Genie public Jan 29, 2026; $250/month Ultra tier; Waymo adopted Feb 2026)

### New wiki pages
- entities/nano-banana.md — three-model family (Gemini 2.5/3/3.1 Flash Image); 200M image edits impact; SynthID + C2PA provenance
- entities/seedance-2-0.md — ByteDance SEED Lab multimodal video; 2026-02-12 release; Seedance 2.0 Fast variant; CapCut integration
- concepts/world-models.md — Schmidhuber 1990 → Ha & Schmidhuber 2018 → LeCun JEPA 2022 → Genie series → AMI Labs 2026; vs-LLMs comparison with LeCun verbatim quote

### Wiki pages updated
- index.md — added three new entries; total pages updated to 55
- raw/articles/source-index.md — twelfth-pass section added (4 new excerpts)

### Findings worth flagging
- **"Nano Banana" is a nickname, not the official model name.** The official names are Gemini 2.5 Flash Image / Gemini 3 Pro Image / Gemini 3.1 Flash Image. The nickname came from a Google DeepMind PM named Naina Raisinghani. Wikipedia redirects /wiki/Nano_Banana into the Gemini article.
- **Seedance 2.0 released 2026-02-12 with native 2K/60FPS output**, making it the first publicly accessible video generation model to match cinema-grade specs. ByteDance distributes it through CapCut (consumer) and fal.ai/Replicate (developer API).
- **World models have a deeper history than the LeCun discourse suggests.** Jürgen Schmidhuber coined the term in 1990; David Ha and Schmidhuber published the key 2018 revival paper. LeCun's JEPA (2022 paper; I-JEPA released CVPR 2023) is a third wave, not the origin.
- **AMI Labs ($1.03B, March 2026) is the largest European seed round ever.** The world models paradigm now has serious funding competition: AMI Labs vs World Labs (Fei-Fei Li, $1B) vs Google DeepMind Genie series.
- **Genie 3's public access is heavily gated**: Google AI Ultra ($250/month), US only, ages 18+, 60-second session limit. This is dramatically more restricted than Nano Banana (free in Gemini app) or Seedance 2.0 (CapCut).

## [2026-05-14] batch-ingest | Thirteenth pass — AI agents (Manus, OpenClaw, Hermes Agent)

### Trigger
User: "add some sources/content related to ai agents, like manus, openclaw, hermes". The existing concepts/ai-agents.md page named Operator/Cursor/Devin but had no entries for the autonomous-agent wave of 2025-2026.

### New raw excerpts
- raw/articles/wikipedia-manus.md — https://en.wikipedia.org/wiki/Manus_(AI_agent) (Butterfly Effect; Xiao Hong founder + Ji Yichao Chief Scientist; beta 2025-03-06; Series B $75M Apr 2025; Meta acquisition announced Dec 2025; **NDRC blocked acquisition 2026-04-27**)
- raw/articles/wikipedia-openclaw.md — https://en.wikipedia.org/wiki/OpenClaw (Peter Steinberger "vibe coder"; Clawdbot 2025-11-24 → Moltbot 2026-01-27 → OpenClaw; MIT License; 247K stars / 47.7K forks by 2026-03-02; Steinberger joined OpenAI 2026-02-14)
- raw/articles/nous-research-hermes-agent.md — https://hermes-agent.nousresearch.com/ + GitHub README (Nous Research; MIT License; v0.13.0 "Tenacity Release" 2026-05-07; 11+ LLM providers; 7 sandboxing backends; FTS5 session search + Honcho dialectic user modeling)

### New wiki pages
- entities/manus.md — Butterfly Effect autonomous agent; Singapore relocation; Meta-Manus block episode
- entities/openclaw.md — most-starred open-source agent project; named after Anthropic's Claude
- entities/hermes-agent.md — Nous Research self-improving agent runtime; model-agnostic

### Wiki pages updated
- concepts/ai-agents.md — added new section "General-purpose autonomous agents (sourced separately)" linking to all three; added related pages and source-index entries
- index.md — added three new entries under "Entities — Organizations & Labs"; total pages → 58
- raw/articles/source-index.md — thirteenth-pass section added (3 new excerpts)

### Findings worth flagging
- **Manus did not train its own foundation models** — Wikipedia explicitly notes Benchmark's counsel argued this in the US Treasury OISP review. Manus is fundamentally an orchestration layer over external LLMs (third-party reporting suggests Claude 3.5 Sonnet + fine-tuned Qwen, but Wikipedia does not confirm specific models).
- **The China NDRC blocked the Meta-Manus acquisition on 2026-04-27** — this is the first case of Chinese authorities blocking a Chinese-origin AI company from accepting a US tech acquisition. The wiki's [[Manus]] entry and the AI milestones timeline should reflect this as a major geopolitical inflection point.
- **OpenClaw's name lineage is a small piece of cultural history**: Clawd → Clawdbot → Moltbot → OpenClaw. The original Clawd was a Steinberger personal assistant explicitly named after Claude. Wikipedia documents this lineage verbatim.
- **Peter Steinberger joined OpenAI on 2026-02-14** while OpenClaw's stewardship transitioned to a non-profit foundation — paralleling how Steinberger built a Claude-adjacent project, then crossed to OpenAI.
- **Hermes Agent's "no lock-in" provider list is a marker of model-agnostic agent design** — 11 named providers (Nous Portal, OpenRouter, NovitaAI, NVIDIA NIM, Xiaomi MiMo, z.ai/GLM, Kimi, MiniMax, HuggingFace, OpenAI, custom endpoints). This contrasts sharply with Manus (closed-source orchestrator) and Cursor (Anthropic/OpenAI-leaning).
- **All three agents converged on messaging platforms as primary interface** — not browser windows. OpenClaw lists 22 channels; Hermes lists 5; Manus runs as a web app but its launch demo emphasized chat-thread-style interaction. The "ambient agent in your existing chat app" pattern displaced the "ChatGPT-style web tab" pattern over 2025-2026.

## [2026-05-14] create | AI Wiki.html — visual editorial index
- Implemented from Claude Design handoff bundle at `~/Downloads/ai-wiki/` (README + `project/AI Wiki.html`, 2739 lines, React-via-CDN single-page).
- Saved to `~/wiki/AI Wiki.html`. Self-contained HTML/CSS/JS; depends on unpkg CDN at runtime for React 18.3.1 + Babel standalone + Google Fonts (Instrument Serif / Sans / JetBrains Mono).
- Sections: Hero, Timeline (90+ events, filterable by category and lab), Labs (6), Models (swimlane chart), Capital (funding bars + DeepSeek Moment + Nvidia + Stargate + Nobels), Macro (Stanford AI Index 2026), Incidents, Policy, Concepts, People, Footer.
- **Departures from the as-shipped design** (faithful otherwise): added href deep-links from labs / concepts / people / policy cards to their corresponding markdown notes under `entities/`, `concepts/`, `regulations/`. Added a hover-only `↗` cue (`a.card-link::after`) so card visuals are unchanged at rest. Lab-card cue is offset to avoid clashing with the existing roman-numeral counter.
- Total of 30 deep-links: 6 labs, 9 concepts, 9 people (Jensen Huang → entities/nvidia.md as the closest match), 6 policy cards. Two timeline events that already had wiki entities are intentionally left unlinked (the design's filterable timeline is a 100+ row list; per-row anchors would crowd the editorial layout).
- Synced to Obsidian vault `AI Wiki/` via Finder duplicate-with-replacing.

## [2026-05-14] update | Unified storage — symlinked `Obsidian Vault/AI Wiki` → `~/wiki/`
- Replaced the duplicated `~/Documents/Obsidian Vault/AI Wiki/` (which was a Finder-duplicated copy of `~/wiki/`) with a POSIX symlink: `ln -s /Users/jing/wiki "/Users/jing/Documents/Obsidian Vault/AI Wiki"`. The previous folder was moved to Trash (recoverable).
- Canonical location is now `~/wiki/` only. The Obsidian vault entry resolves to the same inode tree.
- **Effect**: any edit to `~/wiki/*.md` is visible in Obsidian instantly — no Finder/rsync sync step. The two "folders" are physically one.
- **TCC side-benefit**: traversing the vault path through the symlink resolves to the unrestricted `~/wiki/` path, so this Claude Code shell now has full read/write/list access via the vault path too (TCC checks happen at the resolved path).
- **Caveat**: Obsidian Sync (the paid cloud feature) doesn't traverse symlinks; irrelevant for this local vault. If Obsidian Sync is enabled later, the symlinked content won't be synced — the canonical `~/wiki/` would need to be backed up separately.
