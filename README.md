# Laureano Martin Arcanio

**Senior AI Systems & Full-stack Engineer**
Córdoba, Argentina
[GitHub](https://github.com/laureano-arcanio) · [Toptal Profile](https://www.toptal.com/resume/laureano-martin-arcanio)

AI systems engineer with 20+ years of experience building scalable software across frontend, backend, and ML infrastructure. I specialize in large language model (LLM) integration, evaluation pipelines, tool-calling systems, and production-grade AI architectures.

I’ve worked across US and European teams delivering high-performance systems that bridge product, engineering, and design.

Currently available for full-time or long-term engagements.

---

## Core Expertise

* **AI Systems Engineering** – Fine-Tuning, Large-scale LLM dataset creation & curation, PII filtering, synthetic augmentation, evaluation harness design, and production ML pipelines.
* **Backend Architecture** – Python, FastAPI, Node.js, PostgreSQL, SQLAlchemy
* **Frontend Systems** – React, Next.js, TypeScript, Ember.js
* **Infrastructure** – AWS, Terraform, CI/CD, high-performance LLM serving (vLLM, llama.cpp)
* **System Design** – API architecture, data modeling, scalable workflows

---

## Featured AI Work

### AIMO3 Math Corpus & Dataset Pipeline

Public dataset engineering project for the Kaggle **AI Mathematical Olympiad Progress Prize 3 (AIMO3)** competition.

I built a reproducible pipeline for collecting, filtering, profiling, splitting, and analyzing olympiad-style math problems for LLM training and evaluation. The project focuses on dataset quality, integer-answer validation, domain balancing, difficulty profiling, level prediction, and transparent corpus construction.

**Links:**

* [Kaggle writeup](https://www.kaggle.com/competitions/ai-mathematical-olympiad-progress-prize-3/discussion/672685)
* [GitHub repository](https://github.com/laureano-arcanio/aimo3-dataset-pipeline)
* [Dataset exploratory analysis notebook](https://www.kaggle.com/code/laureanoarcanio/multi-axis-dataset-exploratory-analysis)
* [Filtering and split notebook](https://www.kaggle.com/code/laureanoarcanio/filtering-and-split-notebook/)
* [Level prediction notebook](https://www.kaggle.com/code/laureanoarcanio/multi-axis-level-prediction)

---

## 2026 Project Portfolio — Agentic Systems

Across 2026 I configured two recurring agentic patterns on top of Claude Code: **development-process agents** (role-specialized subagents — product owner, tech lead, implementer, reviewer, QA/security — orchestrated via `AGENTS.md`/`CLAUDE.md` conventions and gated by complexity/risk scoring, so large codebases stay consistent without one person reviewing everything) and **production AI agents** (multi-model reasoning pipelines, RAG systems, voice agents, and MCP tool-calling, typically served on self-hosted GPU infrastructure).

### Competitions

**ARC (Kaggle ARC Prize 2026)** — *Apr 2026 – Oct 2026 · 101 commits*
Multi-model reasoning pipeline (deterministic grid analyzer + Nemotron, Qwen and Muse models served locally via vLLM on dual RTX 3090) that generates and self-repairs executable `transform(grid)` programs for abstract-reasoning tasks, with sandboxed execution and controlled ensemble experiments.

**ARC-AGI Annotation Platform** — *Jun 2026 – Aug 2026*
Full-stack platform (FastAPI + Next.js, PostgreSQL/pgvector) where human solvers document step-by-step reasoning on ARC tasks, captured as an auditable event graph. Designed and ran a 3-phase annotator recruitment pipeline; **1,009 of 1,120 tasks solved and documented (90%)**.

**ARC-AGI-2-HyTE** — *Jul 2026 – Sep 2026 · 21 commits*
CLI toolkit with a role-based agent pipeline (coordinator → planner → specifier → implementer → reviewer → evaluator) that procedurally generates new ARC-style task families from human solving traces. Expanded the original 944 families with **337 newly generated families**, keeping 1,263 canonical test cases passing through a 5-phase refactor.

### Voice Assistants

**Atentina — Voice-as-a-Service Platform** — *Sep 2026 – Oct 2026 · 109 commits*
Multi-tenant telephony voice-agent platform with a fully self-hosted inference stack (STT/LLM/TTS on local GPUs, no external AI vendors) over a LiveKit + Asterisk/SIP pipeline, with a structured conversational engine driven by versioned JSON workflows. Benchmarked STT/TTS models for latency and accuracy, sustained **~32 concurrent calls at p95 ≤ 3s**, and shipped WhatsApp and payment integrations to production.

**Atentina Client Apps (SUGYM)** — *Oct 2026*
MCP-based backend exposing 19 typed tools so Atentina's voice/WhatsApp agent can manage a gym's students, attendance, fees, and payments — hardened containerization, no-code business logic.

### Client Engagements

**Siegfried — ExOne RAG Support Platform (OneCast)** — *Feb 2026 – Oct 2026 · 802 commits*
Enterprise RAG support system for 3D sand-printer technical documentation, with hybrid retrieval (pgvector + full-text, RRF-fused) and reranking, DOM-aware chunking, and automatic Salesforce-case triage. Built under a role-based multi-agent dev workflow (PO, tech lead, backend/frontend/AI specialists, QA, security reviewer) gated by complexity/risk scoring.

**OneCast Marketplace** — *May 2026 – Oct 2026 · 427 commits*
Manufacturing marketplace spanning customer, vendor, and ops portals across the full RFQ-to-payout lifecycle, with instant cost estimation and vendor matching. Delivered under a structured multi-agent pipeline (product-owner → tech-lead → plan reviewer → code reviewers → QA); triaged and shipped **42 tasks (~145 person-days) across 6 implementation waves** from a client feedback round.

**RUBS — Utility Billing System** — *Jul 2026 – Aug 2026 · 49 commits*
Automated utility-billing pipeline for a 171-unit student-housing property: ingests ~175 monthly invoices by email, extracts and validates charges, prorates costs by occupancy with exact-cent allocation, and posts to the Entrata PMS — with mandatory human approval and idempotent, offline-testable infrastructure.

---

## Selected Experience

### Senior AI Systems Engineer — Liberate Innovations (2025–2026)

* Designed large-scale conversational datasets with PII masking and synthetic augmentation
* Fine-tuned Gemma, LLaMA, and GPT-OSS models using SFT pipelines
* Built deterministic evaluation frameworks for tool-calling correctness
* Designed multi-agent orchestration systems (LangChain, LangGraph, LiveKit)
* Optimized LLM serving infrastructure (vLLM, SGLang, llama.cpp)

### Full-stack Developer — Tempus Insights (2025)

* Built sourcing platform managing 1,000+ expert profiles
* Developed forecasting algorithms and real-time dashboards
* Redesigned core database schemas for research workflows

### Frontend & Full-stack Roles (2014–2024)

Worked with companies including:

* AB InBev
* Rooms To Go
* CloneOps.AI
* Multiple Toptal clients
* Intel Corporation (2011–2014)

Delivered 200+ production features across e-commerce, fintech, AI, and SaaS platforms.

---

## Technical Stack

**Languages:** Python, TypeScript, JavaScript
**Backend:** FastAPI, Node.js, SQLAlchemy, PostgreSQL
**Frontend:** React, Next.js, Ember.js, Tailwind, MUI
**AI/ML:** PyTorch, Transformers, LLM fine-tuning, evaluation pipelines
**Infra:** AWS, Terraform, GitHub Actions, Docker

---

## Industries

Finance · Healthcare · Retail · Logistics · Fintech · SaaS · AI Platforms · Education
