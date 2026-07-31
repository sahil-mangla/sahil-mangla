# Sahil Mangla

Computer Engineering student building AI-powered developer tooling — static analysis, code intelligence infrastructure, and MCP-based AI agent orchestration.

I enjoy working inside large, high-bar codebases and building systems that let AI agents reason over and act on real software. My recent work spans code intelligence, agentic AI infrastructure, applied ML, and database engineering — with merged fixes into PyTorch's GPU kernel layer and a 33K-star code-intelligence engine.

---

## Current Focus
- Building AI agent tooling on the Model Context Protocol (MCP)
- Static analysis, AST parsing, and call-graph resolution
- Multi-agent system design for self-healing, resilient infrastructure
- Contributing to production-grade open-source codebases

---

# Selected Projects

## Atlas — AI-Native Engineering Operating System
An MCP-based developer tooling platform that lets AI agents (CLI, IDE, or remote) reason over a codebase and turn a raw problem statement into phased implementation plans and traceable engineering artifacts.
- Built dedicated research, planning, and workflow subsystems with human review gates at every phase transition.
- Designed a versioned contract and adapter layer (request/response envelopes, capability-negotiation manifest) so CLI, MCP, IDE, and REST clients share a single core engine across Gemini, Anthropic, and OpenAI-compatible providers without breaking changes.

**Stack:** Python • Pydantic • MCP • Multi-Provider AI Orchestration
**Links:** [GitHub](https://github.com/sahil-mangla/atlas)

---

## TraffiTwin AI — Self-Healing Traffic Digital Twin
A self-healing traffic digital twin that autonomously detects sensor failures and reconstructs missing spatio-temporal traffic data in real time.
- Designed a multi-agent pipeline (Health Monitoring, Reconstruction, and Digital Twin Layer agents) for continuous, resilient traffic-network observability.
- Benchmarked a spatio-temporal LightGBM model on the real-world METR-LA dataset, achieving 2.48 mph MAE / 6.06% MAPE — a 78.55% improvement over fallback methods — while sustaining 97% observability under 40% simulated sensor failures.

**Stack:** Python • TypeScript • LightGBM • Graph Neural Networks • Multi-Agent Systems
**Links:** [GitHub](https://github.com/sahil-mangla/TraffiTwin-AI) • [Live Demo](https://traffitwin-ai.web.app/)

---

## Trend Discovery Engine
An NLP platform that analyzes Hacker News discussions to identify emerging technology trends.
- Clustered 2,000+ Hacker News discussions into 85 semantic topics using Sentence Transformers, UMAP, and HDBSCAN.
- Built forecasting pipelines using Linear Regression, XGBoost, and LSTM with MLflow experiment tracking, improving forecast reliability by 18%.
- Generated natural-language trend summaries using a Gemini-powered prompt pipeline.

**Stack:** Python • PyTorch • Sentence Transformers • HDBSCAN • UMAP • MLflow • Streamlit
**Links:** [GitHub](https://github.com/sahil-mangla/trend-discovery-engine) • [Live Demo](https://huggingface.co/spaces/sahilmangla/trend-engine)

---

## SQL Server Database Health Dashboard
Production-oriented database monitoring framework developed during my internship at DCM Infotech.
- Built a modular health monitoring engine using SQL Server DMVs and Extended Events to analyze index fragmentation, storage utilization, transaction log health, and deadlock telemetry.
- Designed a configuration-driven architecture with reusable T-SQL views, stored procedures, historical snapshot collection, and executive health reporting.
- Developed a reproducible validation laboratory covering fragmentation, storage, Write-Ahead Logging (WAL), recovery models, deadlock detection, and end-to-end dashboard validation.

**Stack:** SQL Server • T-SQL • DMVs • Extended Events • Database Administration

---

## Database Auditing & Backup Verification System
Database auditing and disaster recovery automation platform built during my internship.
- Automated backup verification and restore validation across production databases.
- Developed trigger-based field-level auditing using PostgreSQL and PL/pgSQL.
- Implemented SHA-256 integrity verification for backup validation and disaster recovery workflows.

**Stack:** PostgreSQL • PL/pgSQL • Python • Docker

---

## Open Source

I enjoy contributing to production-grade open-source software and learning from large engineering codebases.

**[codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** (33K+ Stars) — Diagnosed a false-positive recursion bug in the C-based call-graph resolver, eliminating 2,056 spurious CALLS edges with zero recall loss ([#893](https://github.com/DeusData/codebase-memory-mcp/pull/893), [#984](https://github.com/DeusData/codebase-memory-mcp/pull/984), [#1128](https://github.com/DeusData/codebase-memory-mcp/pull/1128)); co-authored merged fixes for silent-failure and locale issues.

**[PyTorch](https://github.com/pytorch/pytorch)** ([PR #190481 — Merged](https://github.com/pytorch/pytorch/pull/190481)) — Diagnosed and fixed a correctness bug where `torch.nextafter` silently returned its input unchanged for bfloat16 on Apple's MPS backend; implemented a bitwise stepping kernel fix merged into the PyTorch main branch.

---

# Technologies

### Code Intelligence & Static Analysis
AST/tree-sitter • Call Graph Resolution • C • C++

### AI Agent & LLM Engineering
Model Context Protocol (MCP) • Multi-Provider AI Orchestration • Gemini API • Claude API

### Languages
Python • C/C++ • JavaScript • TypeScript • SQL

### Machine Learning
PyTorch • LightGBM • Graph Neural Networks (GNNs) • Scikit-learn • XGBoost • Sentence Transformers • HDBSCAN • UMAP

### Backend & Infra
FastAPI • Next.js • PostgreSQL • PL/pgSQL • Docker • Pandas • NumPy

### Database Engineering
SQL Server • PostgreSQL • Oracle Database • T-SQL • PL/pgSQL • Database Administration • Query Optimization • Backup & Recovery • Performance Monitoring

### MLOps & Tooling
MLflow • Git • GitHub Actions (CI/CD) • Hugging Face • Firebase • Vercel

---

# Achievements
- 🏆 Winner — International AI For Sustainability 2026 (1st Place among 200+ international teams)
- 🏆 Winner — TIET Business Hackathon 2024

---

# Connect
- LinkedIn: https://linkedin.com/in/sahil-manglaa
- Email: sahilmangla.official@gmail.com
