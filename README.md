<div align="center">

  <!-- Dynamic Typing Header Banner -->
  <a href="https://github.com/Sxmxxrth">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=00FFCC&background=05050500&center=true&vCenter=true&width=780&lines=Hey%2C+I'm+Samarth+Sugandhi+%E2%9A%A1;AI%2FML+Engineer+%E2%80%A2+GenAI+%26+LLMOps;Fine-Tuning+Mistral-7B+(QLoRA+%2B+Unsloth);Production+RAG+Architect+(0.81+RAGAS+Precision);Production+ML+Drift+Monitoring+(PSI+%2B+SHAP);Building+Autonomous+Agentic+Systems" alt="Typing SVG Banner" />
  </a>

  <p align="center">
    <strong>Architecting Production Agentic Systems • Edge LLM Deployment • Stealth Automation • High-Throughput MLOps</strong>
  </p>

  <!-- Connect & Identity Badges -->
  <p align="center">
    <a href="https://linkedin.com/in/samarthz"><img src="https://img.shields.io/badge/LinkedIn-samarthz-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:samarthsugandhi5@gmail.com"><img src="https://img.shields.io/badge/Email-samarthsugandhi5%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://github.com/Sxmxxrth"><img src="https://img.shields.io/badge/GitHub-Sxmxxrth-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
    <img src="https://img.shields.io/badge/B.Tech%20CSE-AI%20%26%20ML%20(2024)-6C5CE7?style=for-the-badge&logo=academia&logoColor=white" alt="Degree" />
    <img src="https://img.shields.io/badge/Location-Bengaluru%20%2F%20Indore%2C%20India-00ffcc?style=for-the-badge&logo=googlemaps&logoColor=black" alt="Location" />
    <img src="https://img.shields.io/badge/Status-Immediate%20Joiner-brightgreen?style=for-the-badge" alt="Status" />
  </p>

</div>

---

### 👨‍💻 Executive Summary

I am an **AI/ML Engineer** focused on transitioning generative AI and foundation models from experimental notebooks into high-throughput, fault-tolerant production infrastructure. My engineering ethos centers on:
- **Parameter-Efficient LLM Fine-Tuning**: Domain adaptation using **QLoRA & Unsloth** for low-latency edge & private enterprise deployments.
- **Enterprise RAG Architecture**: Building scalable vector retrieval pipelines with **0.81 Context Precision** validated through systematic **RAGAS** evals.
- **Real-Time ML Observability**: Instrumenting statistical feature drift detection (**PSI**) and explainability (**SHAP**) to prevent silent degradation in production.
- **Autonomous Multi-Agent Automation**: Engineering resilient headless crawlers, intelligent routing engines, and rate-limited outreach daemons.

---

### 🚀 Flagship Architectural Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🧠 1. Fine-Tuned Mistral-7B (Financial Reasoning)
*Domain-adapted 7B foundation model optimized for structured financial insights.*

- **Core Technologies**: `PyTorch` • `Hugging Face` • `Unsloth` • `QLoRA` • `PEFT` • `TRL`
- **Architecture**:
  - Implemented 4-bit NormalFloat (NF4) quantization with double quantization.
  - Targeted low-rank adapter injection into all linear attention projections (`q_proj`, `k_proj`, `v_proj`, `o_proj`).
  - Achieved **75% VRAM footprint reduction**, enabling 16-bit performance on consumer GPUs with **2.2x faster training throughput**.
- **Outcomes**: Generated high-fidelity financial summaries with 0 hallucination on structured balance-sheet schemas.

```
Base Mistral-7B ──► [NF4 Quantization] ──► [QLoRA Adapters] ──► Loss: Cross-Entropy
                           │                      │
                  [Unsloth Kernels]      [Gradient Checkpointing]
```

</td>
<td width="50%" valign="top">

#### 🔍 2. Production Mutual Fund RAG Assistant
*High-precision multi-document semantic retrieval engine with quantitative evaluation.*

- **Core Technologies**: `LangChain` • `ChromaDB` • `FastAPI` • `FAISS` • `RAGAS` • `Docker`
- **Architecture**:
  - Recursive character chunking with dynamic overlap for regulatory financial filings.
  - Hybrid retrieval combining dense vector similarity with metadata-filtered schemas.
  - End-to-end evaluation harness tracking Context Precision, Faithfulness, and Answer Relevance.
- **Metrics**: Achieved **0.81 Context Precision** and **0.84 Answer Relevance** on benchmark QA pairs; sub-180ms p95 latency.

```
Document Corpus ──► [Chunking] ──► [Embedding Model] ──► ChromaDB Vector Store
                                                               │
User Query ─────► [Semantic Search] ────► [Context Rerank] ────┴─► LLM Synthesis
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📈 3. Production ML Pipeline & Drift Monitor
*Continuous model performance observability stack preventing silent covariate shift.*

- **Core Technologies**: `Python` • `Scikit-Learn` • `SHAP` • `FastAPI` • `PostgreSQL` • `Docker`
- **Architecture**:
  - Real-time calculation of **Population Stability Index (PSI)** across incoming inference payloads.
  - Feature attribution tracking via TreeSHAP and KernelSHAP for automated anomaly detection.
  - Automated circuit breaker and fallback triggers when distribution drift exceeds threshold ($\text{PSI} > 0.25$).
- **Impact**: Successfully diagnosed silent model degradation where ROC-AUC collapsed from 0.84 to 0.61 during unseen covariate shifts.

```
Live Inference Payload ──► [Feature Store] ──► Model Scoring
                                 │
                   [PSI Drift Calculator (PSI > 0.25)]
                                 │
                   [TreeSHAP Feature Attribution] ──► Alert / Rollback
```

</td>
<td width="50%" valign="top">

#### 🤖 4. Autonomous Outreach & Deliverability Engine
*Distributed, zero-bounce outbound pipeline with multi-account rotation and browser automation.*

- **Core Technologies**: `Python` • `Playwright` • `Selenium` • `DNS MX Resolver` • `POSIX fcntl`
- **Architecture**:
  - Transactional multi-worker lease manager (`LeadRouter`) with company-level diversity caps.
  - Real-time pre-flight authoritative DNS MX resolution with loopback rejection.
  - Headless Chrome SPA automation with live DOM verification of PDF resume attachment chips before dispatch.
- **Scale**: Dispatched **1,745+ verified emails** with **0 bounces** and atomic thread-safe deduplication across 27,200+ contacts.

```
Lead Ingestion ──► [DNS MX Pre-Flight] ──► [Exclusion Filter] ──► [LeadRouter]
                                                                        │
[DOM Resume Attached] ◄─── [Headless Chrome / SMTP Rotation] ◄──────────┘
```

</td>
</tr>
</table>

---

### 🛠️ Technical Skill Taxonomy

<div align="center">

| Domain | Technologies & Frameworks |
|---|---|
| **Core Languages** | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> |
| **Deep Learning & Core ML** | <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/> |
| **GenAI, LLMs & LLMOps** | <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/LlamaIndex-6A1B9A?style=flat-square&logo=databricks&logoColor=white"/> <img src="https://img.shields.io/badge/vLLM-00E5FF?style=flat-square&logo=openai&logoColor=black"/> <img src="https://img.shields.io/badge/Unsloth-FF4500?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/PEFT%20%2F%20LoRA-7928CA?style=flat-square"/> |
| **Vector DBs & Data Stores** | <img src="https://img.shields.io/badge/ChromaDB-FF6600?style=flat-square"/> <img src="https://img.shields.io/badge/FAISS-0052CC?style=flat-square&logo=meta&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/> |
| **Backend & Cloud Infrastructure** | <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/> |

</div>

---

### 📊 GitHub Activity & System Diagnostics

<div align="center">

  <table border="0">
    <tr>
      <td width="50%" align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=Sxmxxrth&show_icons=true&theme=radical&hide_border=true&bg_color=050505&title_color=00ffcc&text_color=eaeaea&icon_color=00ffcc" width="100%" alt="Samarth's GitHub Stats" />
      </td>
      <td width="50%" align="center">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sxmxxrth&layout=compact&theme=radical&hide_border=true&bg_color=050505&title_color=00ffcc&text_color=eaeaea" width="100%" alt="Top Languages" />
      </td>
    </tr>
    <tr>
      <td colspan="2" align="center">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sxmxxrth&theme=radical&hide_border=true&background=050505&ring=00ffcc&fire=00ffcc&currStreakLabel=00ffcc" width="95%" alt="GitHub Streak" />
      </td>
    </tr>
  </table>

  <!-- GitHub Contribution Grid Snake -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sxmxxrth/Sxmxxrth/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sxmxxrth/Sxmxxrth/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Grid Snake" src="https://raw.githubusercontent.com/Sxmxxrth/Sxmxxrth/output/github-contribution-grid-snake.svg" width="95%" />
  </picture>

</div>

---

### 🤝 Connect & Collaborate

I am actively open to full-time **AI/ML Engineer**, **GenAI / LLM Engineer**, and **Backend/MLOps** roles in India (Bengaluru, Hyderabad, Pune, Delhi NCR, Remote) and globally.

- 💼 **LinkedIn**: [linkedin.com/in/samarthz](https://linkedin.com/in/samarthz)
- 🐙 **GitHub**: [github.com/Sxmxxrth](https://github.com/Sxmxxrth)
- 📧 **Direct Email**: [samarthsugandhi5@gmail.com](mailto:samarthsugandhi5@gmail.com)
- 📍 **Location**: Bengaluru / Indore, India (Immediate Joiner • Open to Relocate)

<div align="center">
  <sub>Built with precision by <strong>Samarth Sugandhi</strong> • Updated automatically via GitHub Actions</sub>
</div>
