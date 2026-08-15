# Sahil Mangla

Computer Engineering student building AI-powered developer tooling — static analysis, code intelligence infrastructure, and MCP-based AI agent orchestration.

I enjoy working inside large, high-bar codebases and building systems that let AI agents reason over and act on real software. My recent work spans code intelligence, agentic AI infrastructure, applied ML, and database engineering — with a merged fix into PyTorch's GPU kernel layer and active review-cycle contributions to a 33K-star code-intelligence engine.

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
- Designed a versioned contract and adapter layer (request/response envelopes, capability-negotiation manifest) so 6 client surfaces — CLI, IDE, MCP, AI, REST, and Desktop — share a single core engine across Gemini, Anthropic, and OpenAI-compatible providers without breaking changes.
- Shipped 17 sequential development phases (repository init through Release Candidate Stabilization); ran a full-repo audit that surfaced and fixed 27 issues across 7 dependency-ordered batches, including crash-safe atomic writes and AI-provider adapter fixes.

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

## DustShield — Electrodynamic Dust Shield Digital Twin
An interactive, browser-based 3D digital twin and operations control dashboard for a lunar Electrodynamic Dust Shield (EDS) mission concept, simulating orbit navigation, surface landing, and real-time dust-clearing physics on solar panels — paired with production-ready hardware to build the real thing.
- Built a Three.js simulation of AC traveling-wave electrostatic clearing physics, using raycasting and tangential-plane projection so dust particles slide and detach realistically across sloped panel surfaces without artificial bounding boxes.
- Modeled net energy recovery with a Beer-Lambert exponential attenuation model relating dust coverage to solar transmission, driving real-time efficiency and power-recovery telemetry in the dashboard.
- Designed and laid out two physical PCBs (a 12V→1-5kV HV flyback driver and a 3-phase electrode sequencer with 4kV-isolated optoisolation) and wrote ESP32-C3 firmware to drive the traveling-wave electrode sequence end-to-end.

**Stack:** Three.js, JavaScript (ES6+), C++/Arduino (ESP32-C3), EasyEDA
**Links:** [GitHub](https://github.com/sahil-mangla/Dust-Shield) • [Live Demo](https://dust-shield.vercel.app)

---

## SQL Server Database Health Dashboard
Production-oriented database monitoring framework developed during my internship at DCM Infotech.
- Built a modular health monitoring engine using SQL Server DMVs and Extended Events to analyze index fragmentation, storage utilization, transaction log health, and deadlock telemetry.
- Designed a configuration-driven architecture with reusable T-SQL views, stored procedures, historical snapshot collection, and executive health reporting.
- Developed a reproducible validation laboratory covering fragmentation, storage, Write-Ahead Logging (WAL), recovery models, deadlock detection, and end-to-end dashboard validation.

**Stack:** SQL Server • T-SQL • DMVs • Extended Events • Database Administration

---


## Open Source

I enjoy contributing to production-grade open-source software and learning from large engineering codebases.

**[codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** (33K+ Stars) — Submitted three fixes to the C-based call-graph resolution engine: a Java enum-method extraction fix ([#984](https://github.com/DeusData/codebase-memory-mcp/pull/984), maintainer-praised as "genuinely good work," pending final review) and two receiver-qualified CALLS-edge precision fixes targeting false-positive resolution on unrelated method names ([#893](https://github.com/DeusData/codebase-memory-mcp/pull/893), [#1128](https://github.com/DeusData/codebase-memory-mcp/pull/1128)), currently iterating with the maintainer on test coverage.

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
- 🏆 2nd Runner-Up — Bharatiya Antariksh Hackathon (ISRO), NRSC Hyderabad 2026 — Top 30 of 15,000+ registered teams
- 🏆 Winner — International AI For Sustainability 2026 (1st Place among 200+ international teams)
- 🏆 Top 100 — Google AI Agent Builder, Google Office Bengaluru 2026

---

# Connect
- LinkedIn: https://linkedin.com/in/sahil-manglaa
- Email: sahilmangla.official@gmail.com
