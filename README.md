<div align="center">

# Raj Firke

**Software Engineer (AI) at Red Hat** · Researcher (LLM evaluation & CoT process monitoring) · 2x EMNLP Main · Open Source

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raj-firke/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rajfirke23@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rajfirke)

<img src="https://komarev.com/ghpvc/?username=rajfirke&label=Profile%20views&color=0e75b6&style=flat-square" alt="Profile views"/>

</div>

---

## About

I am a Software Engineer (AI) at Red Hat. I own multiple customer facing projects and work on agentic systems: MCP servers, diagnostics agents, and support automation.

I also do research in AI Safety with key focus on LLM evaluation and chain-of-thought monitoring. I care about when a score or a trace stops being a trustworthy signal. I look at whether two models can share the same accuracy and still fail in different ways, and whether a chain that still looks clean is already getting riskier with depth.

I belong in the overlap of shipping agents and measuring them. I maintain [Provena](https://github.com/rajfirke/provena). Which is a Context governance for agentic AI. I am an active contributor in PyTorch and vLLM. Additionally, I also do mentor students who are starting the same kind of work.

Please reachout if you wanna collab on research.

---

## Research & Patents

**Patents**

- **System and Method for Utilizing Digital Footprints of a User to Generate Conversational AI Thereof**
  `202421048008` · Filed Jun 2024 · Granted (20-year term)

- **Recommendation and Intent Reconciliation in a Virtual Leader Framework**
  `202521025963` · Filed Apr 2025 · Under review

**Publications**

- **[When Does Reasoning Age? Survival Analysis of Step-Level Error Hazard in LLM Chains](https://github.com/rajfirke/survival-llm-reasoning)**
  · EMNLP 2026 Main · first author · CoT process monitoring

- **[The Correlation Mirage: Benchmark Dependence Collapses for Top-Performing LLMs](https://github.com/rajfirke/correlation-mirage-benchmarks)**
  · EMNLP 2026 Main · first author · science of evaluations

- **[GreenBench: Benchmarking Energy Efficiency and Carbon Footprint of Open-Source LLM Inference on Apple Silicon](https://arxiv.org/abs/2608.28667)**
  · ICCUBEA 2026 (IEEE Xplore) · energy as an eval axis

- **A Survey on Advanced Recommendation Systems: Content-Based Filtering, Collaborative Filtering, Hybrid and Opinion Mining Approaches**
  · ICTIS 2025 / Springer LNNS · 2025

- **[Proposed Model of Hindi Book Review Sentiment Analysis](https://www.ijert.org/proposed-model-of-hindi-book-review-sentiment-analysis)**
  · IJERT 2023 · earlier NLP

---

## Open Source Contributions

### [PyTorch](https://github.com/pytorch/pytorch) — Deep Learning Framework

Active contributor working on core framework improvements:

- **Input validation & safety** — Adding proper bounds checking to prevent silent failures in `max_pool3d`, `channel_shuffle`, `RNN cells`, and convolution ops
- **Optimizer improvements** — `maximize` parameter for LBFGS, integer step tensor support in foreach optimizers
- **Numerical stability** — Fixing NaN propagation in `lp_pool`, `hardtanh` backward pass corrections
- **API enhancements** — `keepdim` for `cosine_similarity`, `NanDetectMode` for forward-pass diagnostics, `dtype` context manager

### [vLLM](https://github.com/vllm-project/vllm) — LLM Inference Engine

Contributing to the high-throughput LLM serving engine:

- **Responses API** — Namespace tools support for harmony/GPT-OSS models

---

## Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [**survival-llm-reasoning**](https://github.com/rajfirke/survival-llm-reasoning) | Code for *When Does Reasoning Age?* — CoT error hazard, 18,969 chains | Python, survival analysis |
| [**correlation-mirage-benchmarks**](https://github.com/rajfirke/correlation-mirage-benchmarks) | Code for *The Correlation Mirage* — copula tail dependence of LLM benches | Python, copulas |
| [**provena**](https://github.com/rajfirke/provena) | Context governance for agentic AI — tamper-evident audit trails, provenance validation, EU AI Act compliance | Python, PostgreSQL, MCP, Policy Engine |
| [**sumo-logic-mcp**](https://github.com/rajfirke/sumo-logic-mcp) | MCP server for Sumo Logic with 48 tools — log search, monitors, alerts, dashboards, metrics | Python, MCP Protocol |
| [**repo-time-machine**](https://github.com/rajfirke/repo-time-machine) | Agentic RAG for codebases — ask questions answered by code, git history, issues & PRs | Python, FAISS, Ollama |

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FF6F00?style=flat-square&logo=data:image/svg+xml;base64,&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Infrastructure & DevOps**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Databases & Tools**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## GitHub Stats

<div align="center">

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=rajfirke&theme=tokyonight" alt="GitHub Stats" />
<img width="49%" src="https://streak-stats.demolab.com/?user=rajfirke&theme=tokyonight&hide_border=true" alt="Streak Stats" />

</div>

---

## Random Dev Quote

<div align="center">

![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

</div>

---

<div align="center">

*Currently measuring when LLM evals and CoT traces stop being trustworthy — and shipping agents at Red Hat.*

</div>
