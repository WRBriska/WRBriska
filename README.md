# William Briska — AI Engineer

AI engineer building production agentic and LLM systems. Currently in the FinTech space, where I own AI projects end to end: requirements → architecture → deployment → monitoring.

---

## What I build

- **Multi-agent systems** — LangGraph pipelines with autonomous reasoning and dynamic tool use, deployed at enterprise scale
- **MCP servers** — powering third-party AI agents for sales and customer support workflows
- **RAG pipelines** — structured retrieval to mitigate hallucinations in high-stakes financial contexts
- **Python automation** — replacing manual effort at scale

Stack: Python · LangGraph · Claude · GPT-4 · Gemini · RAG · Vector DBs · AWS · SQL

---

## Projects

### [InvoiceAudit](https://github.com/WRBriska/InvoiceAudit)

LangGraph system that audits LTL freight invoices against contract terms and flags overbilling with exact dollar impact. Central design decision: **the LLM never touches a number.** Extraction and classification go to the model; arithmetic stays deterministic. Ships with a synthetic data generator, a labeled eval set, and an eval harness — every claim is reproducible with `make all`.

### [GTMAgent](https://github.com/WRBriska/GTMAgent)

LangGraph + Claude agent that runs a full go-to-market workflow: researches an account, scores it against an ICP, runs bounded discovery to close information gaps, and produces a prioritized next-best-action with a drafted outreach message. Includes a prompt-injection defense layer — all untrusted CRM data, call transcripts, and enrichment feeds are sanitized and fenced before reaching the model.

### [TempoScroll](https://github.com/WRBriska/TempoScroll)

Beat-synced PDF score reader for musicians — combines a metronome with an autoscroller to display music scores. Built for personal use for the classical guitar. Client-side, no build step. Work in progress.
---

## Background

- **MS Data Science** — University of Colorado Boulder (expected 2026), with coursework in Generative AI, NLP, and Reinforcement Learning
- **BS Mathematics & Economics** — University of Illinois Chicago
- 8 years of experience across automation, data engineering, and analytics

---

## Find me

[LinkedIn](https://www.linkedin.com/in/williamrobertb/) · briska.r.william@gmail.com · Boulder/Denver, CO
