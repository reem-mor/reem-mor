<h1 align="center">Hi, I'm Re'em Mor 👋</h1>

<h3 align="center">AI Engineer × SRE - Production Operations @ 888 Holdings (Evoke)</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/reemmor/">LinkedIn</a> ·
  <a href="mailto:reem.mor3@gmail.com">Email</a> ·
  <a href="https://github.com/reem-mor">GitHub</a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2F81F7&center=true&vCenter=true&width=640&lines=Production+reliability+meets+AI;Agentic+AiOps+on+AWS+Bedrock;Guardrails%2C+observability%2C+lower+MTTR;Reliability+is+a+feature.+AI+is+the+multiplier." alt="Typing banner" />
</p>

---

## 🚀 About Me

I'm a **Production Operations Analyst at 888 Holdings (Evoke)** and a **B.Sc. Computer Science** student at The Open University of Israel (GPA 91). working right where production reliability meets AI.

By day, I keep regulated, multi-jurisdiction gaming infrastructure healthy: incidents, observability, and reliability workflows across **500+ nodes** with Kubernetes and Terraform, and I've **cut MTTR by ~40%** through smarter dashboards and automated triage.

Increasingly, I build the next layer: **agentic AiOps** , AWS Bedrock agents, RAG over operational runbooks, and n8n automation that takes the manual toil out of incident response.

- 🔭 Production systems, monitoring, incidents, reliability workflows
- ⚙️ DevOps & SRE - CI/CD, Docker, AWS, Kubernetes, Terraform
- 🤖 Agentic AI - Bedrock agents, RAG, MCP, LangChain, n8n orchestration
- 🛡️ Guardrails by default - deterministic safety floors, scope guards, idempotent syncs, dead-letter recovery
- 🎓 B.Sc. CS @ The Open University (GPA 91) · AI-Augmented Software Engineering @ Amdocs / Lab17 *(through Aug 2026)*
- 📫 reem.mor3@gmail.com

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,kubernetes,terraform,docker,linux,nginx,python,fastapi,flask,react,ts,bash,postgres,pytorch,grafana,prometheus" alt="Tech stack" />
</p>

**Observability & Ops** - Monitoring · Incident Management · Grafana · Prometheus · ELK <br>
**AI Engineering & AiOps** - AWS Bedrock · RAG · Agentic AI · LangChain / LangGraph · MCP · n8n · pgvector / FAISS · Embeddings · OpenAI · Gemini

---

## 📂 Featured Projects

| Project | What it does | Stack |
| --- | --- | --- |
| 🧠 **[PITER AiOps](https://github.com/reem-mor/piter-aiops)** | Agentic incident-response platform for NOC/SRE: Bedrock Agent + RAG over runbooks, 4 Lambda action groups, deterministic guardrails, safe escalation previews. **325+ pytest tests.** | AWS Bedrock · RAG · Lambda · Flask · React · Docker |
| 🔎 **[HINDSIGHT](https://github.com/reem-mor/hindsight)** | Incident-log / document intelligence pipeline: ingests ops documents, LLM extraction + deterministic enrichment, semantic search over operational history. | n8n · FastAPI · Gemini · Supabase / pgvector |
| 🎯 **[HaMadrich](https://github.com/LielMaoz/HaMadrich)** | Full-stack training management platform: role-based access, JWT auth, professional content library, admin drill management, Google Drive integration. | Next.js · TypeScript · PostgreSQL · JWT · Tailwind · shadcn/ui |
| 🤖 **[course-assistant-bot](https://github.com/reem-mor/course-assistant-bot)** | Bilingual (HE/EN) Telegram course-ops bot: schedule, recordings, homework submission, RAG recommendations, admin flows. Deterministic routing; LLM classifies, code enforces rules. **224 tests.** | Python · uv · SQLAlchemy/Alembic · LangGraph · Docker |
| 📚 **[ai-engineering-portfolio](https://github.com/reem-mor/ai-engineering-portfolio)** | AI-Augmented Software Engineering learning archive — Python → RAG → agents/MCP; capstone projects and homework evidence (where PITER and the bot began). | Python · FastAPI · React · AWS · pytest · CI |

*Also: [n8n Automation Suite](https://github.com/reem-mor/ai-engineering-portfolio/tree/main/homework/hw06/n8n-customer-support-agent) (Slack ↔ escalation bridge, guardrails, dead-letter handling) · [System Health Checker](https://github.com/reem-mor/system-health-checker) · [DevOps Journey](https://github.com/reem-mor/devops-journey)*

---

## 🆕 Latest Work — PITER AiOps

> **PITER** (Priority · Investigation · Triage · Escalation · Resolution) — an AWS Bedrock–powered agentic platform that automates the incident lifecycle for NOC, DevOps, and SRE teams.

It grew from **IncidentIQ**, an early RAG assistant, into a full agentic system. A Bedrock Agent reasons over a RAG knowledge base of runbooks, service docs, and historical incidents, then calls Lambda action groups to correlate signals — linking a recent deploy → a replication-lag alert → a similar past incident  to accelerate triage.

**What it demonstrates**
- 🤖 Bedrock Agent orchestration over a RAG knowledge base (S3 Vectors)
- 🔧 Four Lambda action groups: deployments, service context, similar incidents, escalation
- 🛡️ Guardrails first - deterministic safety floors that override LLM-stated values, scope guards on every action, Slack escalation for human-in-the-loop
- 🧪 325+ passing pytest tests; reproducible synthetic data (fixed seed)
- 🐳 Dockerized on EC2; Flask backend + React frontend
- 🔌 n8n + MCP for ingestion and notification layers

➡️ Explore: **[piter-aiops](https://github.com/reem-mor/piter-aiops)**

---

## 🎓 AI Engineering Curriculum

Tracked coursework from the **AI-Augmented Software Engineering** program (Amdocs / Lab17), mapped to the tools I build with:

**🐍 Foundations** - Advanced Python (typing, testing, concurrency, OOP) · Web APIs with **Flask** & **FastAPI** · AWS core services (EC2, S3, IAM, RDS, Lambda, CloudWatch, VPC)

**🧠 AI & LLM Engineering** - AWS AI services (**Bedrock**, Textract, Comprehend, Rekognition, Transcribe, Polly) · **RAG** (embeddings, vector databases, semantic search) · **MCP** (Model Context Protocol)

**🕸️ Agents & Orchestration** - **LangChain** (chains, tools, memory, agents) · **LangGraph** (stateful, multi-agent graphs) · **n8n** automation (triggers, webhooks, AI nodes, integrations)

**📊 ML & Models** - ML classifiers (features, training, evaluation metrics) · **PyTorch** & Transformers (tokenization, inference) · Local models with **Ollama** & **Hugging Face**

**🧰 Tooling & Interfaces** - **Open WebUI** for local/remote model serving · AI-assisted development with **Cursor** & **OpenClaw**

<details>
<summary>📖 Full topic breakdown</summary>

<br>

| Topic | Focus |
| --- | --- |
| **Python: Basic & Advanced** | Syntax, data structures, functions, OOP, file handling, modules, error handling, typing, testing, concurrency, scripting |
| **Web Development with Python** | Flask & FastAPI — routes, REST APIs, forms, databases, auth basics, deployment concepts |
| **AWS Core Services** | EC2, S3, IAM, RDS, Lambda, CloudWatch, VPC basics; deploying and managing cloud apps |
| **AWS AI Services** | Bedrock, Transcribe, Polly, Textract, Rekognition, Comprehend — integrated into real applications |
| **RAG & Practical Implementation** | Embeddings, vector databases, document indexing, semantic search, grounding LLM responses |
| **MCP & Practical Implementation** | Connecting AI agents to external tools, files, APIs, and services in a structured way |
| **n8n Workflows** | Triggers, webhooks, API calls, AI agent nodes, Gmail/Sheets integrations, multi-step automations |
| **LangChain** | Chains, prompts, tools, memory, retrievers, agents — building LLM-powered applications |
| **LangGraph** | Graph-based AI workflows — nodes, edges, state management, routing, multi-agent logic |
| **ML Classifier Models** | Datasets, features, labels, training/testing, evaluation metrics, common classifiers |
| **PyTorch & Transformers** | Building neural networks in PyTorch; transformer models — tokenization, inference, usage |
| **Local Models — Ollama & Hugging Face** | Downloading, serving, testing, and comparing local model performance |
| **Open WebUI** | Web interface connecting users to local/remote models, tools, functions, and workflows |
| **AI Assistance — Cursor & OpenClaw** | AI coding and productivity tools for development, automation, and task execution |

</details>

---

## 💻 Languages I Work In

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>

---

<p align="center"><em>"Reliability is a feature. Automation is a discipline. AI is the multiplier."</em></p>

<p align="center">
  <img src="https://raw.githubusercontent.com/reem-mor/reem-mor/main/mario.gif" width="500" alt="Mario coding animation" />
</p>
