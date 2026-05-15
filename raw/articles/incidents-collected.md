# AI Security & Safety Incidents — collected primary excerpts
Sources: WebSearch summaries of news/legal coverage. Where direct primary fetches were possible (gov.uk, anthropic.com), they live in their own files. The items below are from cross-referenced WebSearch summaries.
Fetched: 2026-04-30 / 2026-05-06

---

## Italy ChatGPT ban (March–April 2023)
Sources: TechCrunch (2023-03-31); Garante interim measure 2023-03-30; multiple law-firm summaries.

- **2023-03-30** — Italian Data Protection Authority (Garante) "issued an interim emergency decision ordering OpenAI LLC (OpenAI) to immediately stop the use of ChatGPT to process the personal data of data subjects located in Italy, pending further investigation."
- **GDPR violations alleged** (verbatim from law-firm summary): "failure to provide required transparency information about ChatGPT's processing of personal data," "the absence of a legal basis for processing personal data for the purposes of 'training' the algorithms," "inaccuracy in ChatGPT's processing of personal data," "failure to verify users' age, meaning that users under 13 years of age may obtain answers not appropriate to their degree of development."
- **April 2023** — ChatGPT access reinstated after OpenAI implemented age-verification gates, updated EU privacy policy, and added training-data opt-outs.
- **December 2024** — Garante imposed a **€15 million fine** — described as "the first GDPR penalty against a generative AI company."

---

## NYT v. OpenAI / Microsoft (December 2023–)
Source: court docket "The New York Times Company v. Microsoft Corporation, 1:23-cv-11195" (CourtListener — direct fetch returned 403); WebSearch summaries.

- **2023-12-27** — New York Times filed a federal lawsuit against OpenAI and Microsoft in the United States District Court for the Southern District of New York.
- The complaint alleges OpenAI "unlawfully used millions of NYT articles to train its AI models, including ChatGPT," and seeks damages "in the billions of dollars" for "illegally copying and using the newspaper's archive."
- Case number: 1:23-cv-11195.

---

## Slovakia deepfake audio (September 2023)
Sources: CNN, Bloomberg, IPI, HKS Misinformation Review, Wikipedia: Incident database.

- **2023-09-28** — During the pre-election moratorium, a deepfake audio recording was posted on social media purporting to be a phone call between Michal Šimečka (Progressive Slovakia leader) and journalist Monika Tódová (Denník N) discussing rigging the election.
- The audio surfaced two days before the 2023 Slovak parliamentary election.
- Šimečka told CNN: "It does sound like me."
- Election moratorium "limited the ability of parties and media to respond, maximizing the impact of this disinformation."
- Cited in the misinformation literature as plausibly "the first [election] swung by deepfakes" — though [HKS Misinformation Review](https://misinforeview.hks.harvard.edu/article/beyond-the-deepfake-hype-ai-democracy-and-the-slovak-case/) cautions against overclaiming.

---

## Samsung ChatGPT data leak (April 2023)
Sources: CIO Dive, Cybersecurity Dive, Gizmodo, Dark Reading.

- **April 2023** — Three separate leaks within 20 days at Samsung Electronics. Engineers pasted into ChatGPT:
  1. "faulty source code related to the Samsung Electronics facility measurement database download program"
  2. "program code for identifying defective equipment to get code optimization"
  3. A meeting recording converted to text and submitted "to get meeting minutes"
- Samsung's response: company-wide generative-AI ban (ChatGPT, Bard, Bing Chat); 1024-byte cap on prompts; disciplinary action up to termination for violations.
- Significance: the Samsung incident became the canonical case study cited in enterprise AI-governance literature for shadow-AI / data-exfiltration risk.

---

## Note
All four incidents are **secondary-source** reconstructions from news / legal coverage rather than primary documents. For the NYT case in particular, the actual complaint PDF lives on PACER / CourtListener and would need a direct fetch to verify specific paragraphs.
