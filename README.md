<h1 align="center">Hi, I'm Apuroop Yarabarla 👋</h1>

<p align="center">
  <strong>AI/ML Engineer &nbsp;·&nbsp; AI Product Owner &nbsp;·&nbsp; GenAI Builder</strong><br/>
  Building production-grade AI systems with LangGraph, CrewAI, RAG, and Claude
</p>

<p align="center">
  <a href="https://linkedin.com/in/apuroopyarabarla">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin" />
  </a>
  &nbsp;
  <a href="mailto:apuroopyarabarla@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail" />
  </a>
</p>

---

## About Me

I design and build **end-to-end AI products** — from requirements gathering and architecture through deployment and iteration. I work at the intersection of engineering and product ownership: I write the code *and* define what should be built and why.

My focus is **applied GenAI** — not demos, but systems that process real data, reason over it, and deliver decisions users can act on.

- **AI Engineering:** LangGraph agents, RAG pipelines, multi-agent systems (CrewAI), vector search
- **Product Thinking:** Requirements analysis, BRDs, user story mapping, stakeholder alignment
- **AI Tooling at Work:** Notion AI, ClickUp AI — automating PM workflows with AI
- **Certified:** Scrum Alliance CSM · Google Cloud · AI for Product Managers

---

## Featured Projects

### [AccountingGPT](https://github.com/apuroopy1-prog/accountinggpt-poc)
> AI-powered financial platform for small businesses

- **LangGraph ReAct agent** with persistent memory — ask anything about your finances in plain English
- **PDF bank statement parser** — pdfplumber + Claude Sonnet extracts structured transactions from any bank format
- **Facebook Prophet forecasting** — 12-month net cash flow prediction, auto-configured to data availability
- **Anomaly detection** — Claude identifies duplicate charges, spending spikes, suspicious patterns
- **Stack:** FastAPI · React · PostgreSQL · Redis · Docker · Claude Opus 4.6 · LangGraph · Prophet

---

### AI Health Navigator
> Clinical decision support system with RAG and voice interface

- **LangGraph workflow** orchestrating symptom assessment, triage, and care recommendations
- **Google Vertex AI Vector Search** (Matching Engine) — RAG over medical knowledge base with 512-token chunks and 50-token overlap
- **Embeddings:** Google `text-embedding-004` via VertexAI
- **Deployed:** AWS App Runner + EC2, Docker Compose, CI/CD via GitHub Actions
- **Stack:** LangGraph · Vertex AI · Streamlit · FastAPI · Docker · AWS

---

### JurisGPT — Legal AI Platform
> Multi-agent legal research and document analysis system

- **Multi-agent pipeline** — separate agents for investigation, legal research, document drafting, and case analysis
- **Voice I/O:** OpenAI Whisper (STT) + text-to-speech for fully spoken legal consultations
- **Document parsing:** PyMuPDF, PyPDF2, python-docx — ingests contracts, case files, legal briefs
- **Visualization:** NetworkX case relationship graphs, Plotly timelines
- **Stack:** LangChain · Anthropic Claude · OpenAI · Streamlit · ReportLab

---

### AI Vacation Planner — CrewAI Multi-Agent
> 4-agent CrewAI pipeline for personalized travel planning

- **4 specialized agents:** City Expert → Local Tour Guide → Logistics Manager → Report Compiler
- Real-time web search via Serper API (Google Search)
- Generates branded PDF itinerary + sends via email
- **Stack:** CrewAI · OpenAI GPT · Streamlit · SerperDev · FPDF · SMTP

---

### AI Content Generator
> Text-to-image, text-to-video, and text-to-speech in one app

- **Text-to-Image:** SDXL-Turbo (4-step diffusion, runs on Apple MPS / CUDA)
- **Text-to-Video:** ModelScope text-to-video generation
- **Text-to-Speech:** Bark (high quality) + Edge TTS (fast, free)
- Runs on Google Colab (free T4 GPU) or local Mac M1/M2/M3
- **Stack:** Diffusers · PyTorch · Gradio · Hugging Face

---

### BowlGuard
> Claude AI-powered app with rate limiting and vanilla JS frontend

- Direct Anthropic API integration with per-IP rate limiting (no framework)
- Pure Python HTTP server proxying Claude API calls (bypasses CORS)
- **Stack:** Anthropic Claude · Python · Vanilla JS/HTML/CSS

---

## Tech Stack

### AI / GenAI
![LangGraph](https://img.shields.io/badge/LangGraph-ReAct_Agents-FF6B35?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-Chains_&_Tools-1C3C3C?style=flat-square)
![CrewAI](https://img.shields.io/badge/CrewAI-Multi_Agent-FF4B4B?style=flat-square)
![Claude](https://img.shields.io/badge/Anthropic_Claude-Opus_4.6-blueviolet?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT_&_Whisper-412991?style=flat-square)
![Vertex AI](https://img.shields.io/badge/Google_Vertex_AI-Vector_Search-4285F4?style=flat-square)
![Prophet](https://img.shields.io/badge/Facebook_Prophet-Forecasting-3B5998?style=flat-square)
![Diffusers](https://img.shields.io/badge/HuggingFace_Diffusers-SDXL-FFD21E?style=flat-square)

### RAG & Vector Search
![RAG](https://img.shields.io/badge/RAG-Retrieval_Augmented_Generation-green?style=flat-square)
![Vector Embeddings](https://img.shields.io/badge/Vector_Embeddings-text--embedding--004-blue?style=flat-square)
![Vertex Matching Engine](https://img.shields.io/badge/Vertex_Matching_Engine-ANN_Search-4285F4?style=flat-square)

### Backend & Data
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi)
![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis)
![Celery](https://img.shields.io/badge/Celery-Task_Queue-37814A?style=flat-square)

### Frontend & Infra
![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit)
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker)
![AWS](https://img.shields.io/badge/AWS-App_Runner_&_EC2-FF9900?style=flat-square&logo=amazon-aws)

### AI Productivity Tools
![Notion AI](https://img.shields.io/badge/Notion_AI-Workflow_Automation-000000?style=flat-square&logo=notion)
![ClickUp AI](https://img.shields.io/badge/ClickUp_AI-PM_Automation-7B68EE?style=flat-square)

---

## Certifications

- **Certified Scrum Master (CSM)** — Scrum Alliance
- **Generative AI for Project Managers** — AI Product Management
- **Google Cloud** — Vertex AI & GCP fundamentals
- **AI for Product Owners** — Requirements gathering with AI tools

---

## What I Bring

```
Requirements Gathering  ──▶  Architecture Design  ──▶  Build  ──▶  Deploy  ──▶  Iterate
        ↑                                                                           │
        └───────────────────────── Stakeholder Feedback ◀──────────────────────────┘
```

I've worked across the full AI product lifecycle — from writing BRDs and user stories with stakeholders, to building LangGraph agents and deploying them on AWS. I don't need a separate team to hand off to: I own the outcome end to end.

---

<p align="center">
  <em>Open to AI/ML Engineering and AI Product roles. Let's build something.</em><br/><br/>
  <a href="https://linkedin.com/in/apuroopyarabarla">
    <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin" />
  </a>
</p>
