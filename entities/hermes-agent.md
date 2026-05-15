---
title: Hermes Agent (Nous Research)
created: 2026-05-14
updated: 2026-05-14
type: entity
tags: [agent, open-source, mit-license, nous-research]
sources: [raw/articles/nous-research-hermes-agent.md]
---

# Hermes Agent (Nous Research)

## Source
[hermes-agent.nousresearch.com](https://hermes-agent.nousresearch.com/) + [GitHub README](https://github.com/nousresearch/hermes-agent) → raw excerpt at [nous-research-hermes-agent.md](../raw/articles/nous-research-hermes-agent.md).

## Developer
**Nous Research**

## License
**MIT License** — fully open source.

## Tagline (verbatim)
> "The Agent That Grows With You"

## Description (verbatim from project site)
> "An autonomous agent that lives on your server, remembers what it learns, and gets more capable the longer it runs."

## Pitch (verbatim from GitHub README)
> "The self-improving AI agent built by Nous Research."
> "the only agent with a built-in learning loop — it creates skills from experience, improves them during use"

## Version
**v0.13.0** ("The Tenacity Release") — released **2026-05-07** (most recent visible).

## LLM provider compatibility
Hermes Agent is model-agnostic. Supported providers:
- Nous Portal
- OpenRouter (200+ models)
- NovitaAI
- NVIDIA NIM (Nemotron)
- Xiaomi MiMo
- z.ai/GLM
- Kimi/Moonshot
- MiniMax
- Hugging Face
- OpenAI
- Custom endpoints

> "Switch with `hermes model` — no code changes, no lock-in."

## Memory system
- Persistent cross-session memory and user profiles
- "FTS5 session search with LLM summarization for cross-session recall"
- "Honcho dialectic user modeling"

## Skills system
Procedural memory, Skills Hub, autonomous skill creation after complex tasks.

## Platform integrations (verbatim)
> "Telegram, Discord, Slack, WhatsApp, Signal, and CLI — all from a single gateway process."

## Sandboxing / execution backends (verbatim)
> "Seven terminal backends — local, Docker, SSH, Singularity, Modal, Daytona, and Vercel Sandbox."

## Automation
Built-in cron scheduler with delivery to any platform.

## Interface (verbatim)
> "Full TUI with multiline editing, slash-command autocomplete, conversation history, interrupt-and-redirect."

## Significance
- One of the leading **MIT-licensed** agent runtimes alongside [[OpenClaw]]
- Distinguishes itself with a "self-improving" pitch — persistent memory plus autonomous skill creation
- Wide LLM-provider compatibility (11 named providers) makes it one of the most model-agnostic agent runtimes
- Built by Nous Research, the same organization known for the Hermes series of fine-tuned models — note that Hermes Agent (the runtime) is a separate product from the Hermes models on Hugging Face

## Related Pages
[[AI Agents]] | [[OpenClaw]] | [[Manus]] | [[Open Source AI Safety]] | [[OpenAI]]

## Sources (saved excerpts in raw/)
- [Hermes Agent (Nous Research)](https://hermes-agent.nousresearch.com/) → [raw/articles/nous-research-hermes-agent.md](../raw/articles/nous-research-hermes-agent.md)
- [github.com/nousresearch/hermes-agent](https://github.com/nousresearch/hermes-agent)
