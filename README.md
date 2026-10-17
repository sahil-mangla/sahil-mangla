<div align="center">

<img width="100%" src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=24&duration=3000&pause=900&color=2F81F7&background=0D1117&center=true&vCenter=true&width=1000&height=80&lines=Computer+Engineering+Student%3BAI+Systems+%26+Developer+Infrastructure%3BOpen+Source+%E2%80%A2+Applied+ML+%E2%80%A2+MCP%3BBuilding+Reliable+Intelligent+Systems" alt="Animated typing introduction" />

### Sahil Mangla · AI Systems · Developer Infrastructure · MLOps

I build AI systems that go beyond demos — from code intelligence and engineering workflows to resilient machine-learning systems.

<p>
  <a href="https://github.com/sahil-mangla">
    <img src="https://img.shields.io/badge/GitHub-sahil--mangla-181717?style=flat-square&logo=github" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/sahil-manglaa">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://leetcode.com/u/sahil-mangla/">
    <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
  <a href="mailto:sahilmangla.official@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

</div>

---

## Engineering Focus

I work across AI engineering, developer infrastructure, applied machine learning, and systems that connect software to the real world. My focus is on understanding how these systems work, building them carefully, and evaluating them under realistic conditions.

- **AI systems & model foundations:** MiniGPT for understanding transformer internals; a custom RAG engine for retrieval, grounding, and evaluation; and ORBIT for modular agent experiments, benchmarks, and reproducible comparisons.
- **Agentic engineering & workflows:** ATLAS-style systems with structured research, planning, traceability, provider integrations, and human approval gates.
- **Code intelligence & developer tooling:** AST-based analysis, call-graph resolution, static analysis, and tools that help engineers navigate complex codebases.
- **Applied ML & resilience:** TraffiTwin AI and trend-discovery experiments focused on measurable model performance, robust data pipelines, and behavior under failure.
- **Systems, cloud & embedded work:** database health monitoring, cloud-backed applications, interactive digital twins, and embedded hardware/firmware prototypes.

My approach is **understand → implement → experiment → evaluate → refine** — connecting fundamentals with practical engineering and measurable outcomes.



## Open Source Contributions

### [PyTorch — PR #190481](https://github.com/pytorch/pytorch/pull/190481) · **Merged**

Fixed a correctness issue where `torch.nextafter` could return the input unchanged for `bfloat16` on Apple's MPS backend. The contribution addressed floating-point stepping behavior in a GPU backend.

### [codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) · **Contributions under review / iteration**

Working on call-graph resolution and relationship precision in a large code-intelligence engine:

- [PR #984](https://github.com/DeusData/codebase-memory-mcp/pull/984) — Java enum-method extraction.
- [PR #893](https://github.com/DeusData/codebase-memory-mcp/pull/893) — receiver-aware same-module resolution.
- [PR #1128](https://github.com/DeusData/codebase-memory-mcp/pull/1128) — tighter receiver-qualified resolution.

I enjoy the engineering work behind subtle correctness bugs: understanding why a system makes the wrong connection, reproducing it, and improving the tests that prevent regressions.

## Featured Work

### 🧭 [ATLAS — AI-Native Engineering Operating System](https://github.com/sahil-mangla/atlas)

A structured engineering workflow that turns project ideas into traceable research, plans, architecture decisions, and evaluation artifacts.

- Built dedicated research, planning, and workflow subsystems with explicit human approval gates.
- Designed a versioned contract and adapter layer for a shared core across AI providers and client surfaces.
- Completed 17 development phases and a full-repository audit that fixed 27 issues across seven dependency-ordered batches.

**Stack:** Python · Pydantic · AI provider adapters · Workflow design · Observability

### 🚦 [TraffiTwin AI — Self-Healing Traffic Digital Twin](https://github.com/sahil-mangla/TraffiTwin-AI) · [Live demo](https://traffitwin-ai.web.app)

A traffic digital twin designed to preserve network observability when sensors fail or telemetry goes missing.

- Built a multi-agent pipeline for health monitoring, data reconstruction, and digital-twin updates.
- Evaluated a spatio-temporal LightGBM model on METR-LA: **2.48 mph MAE** and **6.06% MAPE**.
- Reported **97% observability under 40% simulated sensor failures** in the project's evaluation.

**Stack:** Python · TypeScript · LightGBM · Spatio-temporal ML · Multi-agent systems

### 📈 [Trend Discovery Engine](https://github.com/sahil-mangla/trend-discovery-engine)

An NLP-based technology intelligence platform that identifies and forecasts emerging topics from Hacker News discussions.

- Clustered 2,000+ discussions into 85 semantic topics using embeddings and density-based clustering.
- Built forecasting experiments with Linear Regression, XGBoost, and LSTM, tracked with MLflow.
- Added Gemini-powered summaries to make discovered trends easier to explore.

**Stack:** Python · PyTorch · Sentence Transformers · UMAP · HDBSCAN · XGBoost · MLflow

### 🌕 [DustShield — Electrodynamic Dust Shield Digital Twin](https://github.com/sahil-mangla/Dust-Shield) · [Live demo](https://dust-shield.vercel.app)

An interactive 3D simulation and operations dashboard for a lunar electrostatic dust-clearing concept, paired with embedded hardware work.

- Simulated traveling-wave dust-clearing behavior across angled solar-panel surfaces.
- Modeled dust coverage and solar transmission to estimate power recovery.
- Designed two PCBs and developed ESP32-C3 firmware for the electrode-sequencing system.

**Stack:** Three.js · JavaScript · C++/Arduino · ESP32-C3 · PCB design

### 🗄️ Database Health Dashboard

A SQL Server monitoring framework developed around practical database-administration scenarios.

- Uses DMVs and Extended Events to inspect index fragmentation, storage, transaction-log health, and deadlock telemetry.
- Includes reusable T-SQL monitoring components and a validation lab for controlled database failure scenarios.

**Stack:** SQL Server · T-SQL · DMVs · Extended Events · Database administration

## Technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,c,cpp,java,js,ts,postgres,docker,fastapi,nextjs,pytorch,git,github,linux,gcp,firebase,vercel" alt="Technology icons" />
</p>

| Area | Tools & concepts |
|---|---|
| **Languages** | Python, C/C++, Java, JavaScript, TypeScript, SQL |
| **AI & ML** | PyTorch, scikit-learn, LightGBM, XGBoost, Sentence Transformers, HDBSCAN, UMAP |
| **AI systems** | MCP, provider adapters, agent workflows, evaluation, human-in-the-loop design |
| **Code intelligence** | ASTs, tree-sitter, call graphs, static analysis, test-driven debugging |
| **Backend & data** | FastAPI, Next.js, PostgreSQL, SQL Server, Oracle, T-SQL, PL/pgSQL |
| **Cloud, MLOps & tooling** | Google Cloud (GCP), Firebase, MLflow, Docker, GitHub Actions, Hugging Face, Vercel |
| **Embedded & simulation** | Three.js, ESP32-C3, C++/Arduino, PCB prototyping |

## Recognition

- 🥇 **1st Place** — International AI for Sustainability Challenge, 2026
- 🥈 **2nd Runner-Up** — Bharatiya Antariksh Hackathon (ISRO), 2026
- 🌟 **Top 100** — Google AI Agent Builder, 2026

## GitHub Activity

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=sahil-mangla&show_icons=true&hide_border=true&rank_icon=github&theme=transparent" alt="GitHub statistics" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sahil-mangla&layout=compact&hide_border=true&theme=transparent&langs_count=6" alt="Most used languages" />
</div>

---

<div align="center">

**One Contribution at a time, Grind.**

[GitHub](https://github.com/sahil-mangla) · [LinkedIn](https://linkedin.com/in/sahil-manglaa) · [LeetCode](https://leetcode.com/u/sahil-mangla/)

</div>
