<div align="center">

```
██████╗  █████╗ ██╗  ██╗███████╗██╗  ██╗██╗████████╗██╗  ██╗
██╔══██╗██╔══██╗██║ ██╔╝██╔════╝██║  ██║██║╚══██╔══╝██║  ██║
██████╔╝███████║█████╔╝ ███████╗███████║██║   ██║   ███████║
██╔══██╗██╔══██║██╔═██╗ ╚════██║██╔══██║██║   ██║   ██╔══██║
██║  ██║██║  ██║██║  ██╗███████║██║  ██║██║   ██║   ██║  ██║
╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝   ╚═╝   ╚═╝  ╚═╝
```

# Rakshith Kumar K.N

**`Senior AI/ML Engineer — Building production AI systems that actually ship`**

[![MCP Contributor](https://img.shields.io/badge/MCP-Foundation_Contributor-7c6ff7?style=flat-square&labelColor=111118)](https://github.com/rakshit176)
[![Impact](https://img.shields.io/badge/Business_Impact-$2.3M%2B-3dd68c?style=flat-square&labelColor=111118)](https://github.com/rakshit176)
[![Cloud](https://img.shields.io/badge/Multi--Cloud-AWS_·_Azure_·_GCP-f7a14e?style=flat-square&labelColor=111118)](https://github.com/rakshit176)
[![Compliance](https://img.shields.io/badge/Compliance-HIPAA_·_SOC_2-f76f7c?style=flat-square&labelColor=111118)](https://github.com/rakshit176)
[![Views](https://komarev.com/ghpvc/?username=rakshit176&style=flat-square&color=7c6ff7&labelColor=111118)](https://github.com/rakshit176)

[📧 Email](mailto:rakshitkumarkn@gmail.com) · [💼 LinkedIn](https://linkedin.com/in/rakshith-kumar-kn-4108b31a3) · [🌐 Portfolio](https://portfolio-v2-nu-three-33.vercel.app/)

</div>

---

## ⚡ Who I am

5+ years shipping **production AI systems** across enterprise security, healthcare, and financial services. I don't just experiment — I build things that process millions of requests, pass regulatory audits, and generate real revenue impact.

- 🏗️ **Built production MCP servers** connecting LLM agents to live enterprise tools (HappyFox, Jira, Confluence) — contributed to the open-source MCP ecosystem
- 🧠 **End-to-end RLHF practitioner** — reward model design → DPO preference optimization on 72B-parameter medical LLMs → LLM-as-judge evaluation frameworks
- ⚡ **Pioneered LLM-supervised Knowledge Distillation** compressing 4+ hour firewall validation to 2–5 seconds (zero LLM calls at inference)
- 🔐 **Zero PII leakage** across 50K+ J.P. Morgan financial documents — SOC 2 certified
- 👥 **Led cross-functional squads** of 4–8 engineers (ML, backend, frontend); mentored 5 junior engineers, 2 promoted in 8 months

---

## 📊 Impact by numbers

| Metric | Result |
|--------|--------|
| 💰 Total business impact | **$2.3M+** across 4 companies |
| ⚡ Cisco ASA validation (Knowledge Distillation) | 4 hrs → **2–5 sec · 98% reduction** |
| 🔐 J.P. Morgan NLP redaction (SOC 2) | **Zero PII leakage** · 99.2% precision |
| 🏥 Healthcare diagnostic AI (August AI) | 67% → **91% accuracy** · 5,000+ sessions |
| ☁️ Azure cloud migration (FinOps) | **$18K/month saved** · 62% cost reduction |
| 🏭 Manufacturing SSE migration (Lincode) | **$2M/year** infrastructure savings |
| 🖼️ Image generation pipeline (Krut AI) | 8s → **1.2s latency** · $32K/month GPU savings |
| 🔍 Enterprise AI Search (GSC) | **10K+ QPD** · p95 <300ms · 99.9% uptime |

---

## 🔥 Featured projects

### 🔐 Cisco ASA Firewall Validator — LLM Knowledge Distillation
> `PyTorch` `BERT` `GPT-4` `LangGraph` `Neo4j` `Qdrant` `AWS Bedrock` `ECS`

GPT-4 Teacher annotates 50K+ ASA configs with soft labels and chain-of-thought reasoning. AI agents orchestrate KL-divergence distillation into 3 student models (conflict classifier, syntax validator, risk scorer). **Zero LLM calls at inference.**

**Result:** `4+ hours → 2–5 seconds` · Fortune 500 scale · 200+ firewalls · 10× faster migration · Led 4 engineers

---

### 🔍 GSC Enterprise AI Search Engine *(public release pending)*
> `Neo4j` `Qdrant` `AWS Bedrock` `ECS` `Lambda` `SQS` `LangSmith` `Prometheus`

Hybrid graph + vector search across 1M+ graph nodes and 50M embeddings with cross-region LLM routing and semantic caching on private VPC.

**Result:** `10K+ queries/day` · `p95 <300ms` · `99.9% uptime`

---

### ⚡ Distributed Inference Service — [`→ View repo`](https://github.com/rakshit176/distributed-inference)
> `Ray Serve` `Redis` `Prometheus` `Docker` `FastAPI` `Terraform`

Multi-region ML serving platform with auto-scaling, full observability, and cross-cloud failover.

**Result:** `5K req/sec` · `99.9% uptime` · AWS + GCP multi-region

---

### 🏥 Healthcare Multi-Agent AI (August AI)
> `LangChain` `GPT-4` `RAGAS` `DSPy` `AWS` `Azure` `FastAPI` `HIPAA`

Multi-agent patient interview + clinical documentation system with full RLHF alignment pipeline on Qwen 2.5 72B. Passed 2 regulatory audits with zero findings.

**Result:** `67% → 91% diagnostic accuracy` · `2,500+ daily interactions` · `3 hospitals` · `$150K annual savings`

---

### 🚚 IDP Supply Chain Agent — Scania *(client work)*
> `AWS Bedrock` `Claude` `Elasticsearch` `MinerU VLM` `FastAPI` `Docker`

5-stage confidence-gated agent harness for shipping document intelligence. Per-field precision thresholds act as automated LLM-as-judge routing; low-confidence extractions go to HITL queue.

**Result:** `p95 <300ms` · `73% HITL reduction` · `Zero critical-field errors`

---

## 🛠️ Technical stack

**GenAI & LLMs**
```
GPT-4 · Claude 3.5 · Gemini Pro · LLaMA 3 · Qwen 2.5 72B
RAG · GraphRAG · Multi-Agent · RLHF · DPO · PPO · LoRA/QLoRA
Knowledge Distillation · LLM-as-Judge · Alignment Engineering
Confidence-Gated Evaluation · Agentic Workflows
```

**Orchestration & Protocols**
```
MCP SDK · LangGraph · LangChain · LlamaIndex · DSPy
NeMo Guardrails · RAGAS · Semantic Kernel · Google ADK
```

**LLM Inference & LLMOps**
```
vLLM · TensorRT-LLM · SGLang · Ollama · Unsloth · LLaMA Factory
LangSmith · MLflow · Prometheus · GitHub Actions · CI/CD
```

**Cloud Platforms**
```
AWS  — SageMaker · ECS · Lambda · Bedrock · SQS · S3 · G5
Azure — Container Apps · Cognitive Services · Key Vault
GCP  — Vertex AI · Cloud Run · Gemini
Modal · RunPod
```

**Vector & Data Stores**
```
Neo4j · Qdrant · Pinecone · Elasticsearch · PostgreSQL · MongoDB · Redis
```

**Languages**
```
Python · TypeScript · Rust · Go · JavaScript
```

---

## 💼 Work experience

```
Senior AI/ML Engineer    Gruve AI          Oct 2024 — Present
AI Engineer              August AI         Aug 2023 — Oct 2024
Machine Learning Eng.    Krut AI (Snive)   Jan 2023 — Aug 2023
Associate Data Scientist Lincode Labs      Mar 2022 — Jan 2023
```

---

## 🏆 Recognition

- 🥇 **Winner** — Gruve AI Internal Hackathon: IT Help Desk Multi-Agent AI
- 🥇 **Winner** — August AI Hackathon: AI Doctor Analyzer (biomarker extraction)
- 📄 **IEEE ACAI 2022** — Co-author: *"Water Quality Prediction using BPNN, SVR, and LSTM"*
- ⚡ **MCP Foundation Contributor** — Open-source Model Context Protocol ecosystem

---

## 📚 Education

| Degree | Institution | Year |
|--------|-------------|------|
| M.Sc. Big Data Analytics | St. Joseph's University, Bengaluru | 2020–2022 |
| B.C.A. Computer Applications | Seshadripuram College, Bengaluru | 2016–2019 |

---

## 📈 GitHub stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=rakshit176&show_icons=true&hide_border=true&count_private=true&theme=dark&bg_color=0a0a0f&title_color=7c6ff7&text_color=8b8a9e&icon_color=3dd68c" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs?username=rakshit176&hide_border=true&layout=compact&theme=dark&bg_color=0a0a0f&title_color=7c6ff7&text_color=8b8a9e" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=rakshit176&hide_border=true&background=0a0a0f&stroke=7c6ff7&ring=7c6ff7&fire=f7a14e&currStreakLabel=3dd68c&sideLabels=8b8a9e&dates=8b8a9e&currStreakNum=f0eff8&sideNums=f0eff8" />
</div>

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=rakshit176&theme=darkhub&no-frame=true&row=1&column=6&margin-w=8" />
</div>

---

<div align="center">

**Open to Senior ML Engineer / Staff AI Engineer roles**

*FAANG-tier · AI-first companies · Bengaluru / Remote*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-7c6ff7?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rakshith-kumar-kn-4108b31a3)
[![Email](https://img.shields.io/badge/Email-Reach_out-3dd68c?style=flat-square&logo=gmail&logoColor=white)](mailto:rakshitkumarkn@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-View_work-f7a14e?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-v2-nu-three-33.vercel.app/)

</div>
