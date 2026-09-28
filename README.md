<div align="center">

# Jasman
### AI Engineer · LLMs, RAG & Multi-Agent Systems

*Turning research prototypes into reliable, production AI systems — with a rare foundation in hardware R&D and manufacturing automation.*

[![Portfolio](https://img.shields.io/badge/Portfolio-1E3BDE?style=for-the-badge&logo=googlechrome&logoColor=white)](https://jasman123.github.io/jasman-portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jasman-jasman-74ab21186)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jasman0603@gmail.com)

</div>

---

## About

AI Engineer with hands-on experience across the full ML lifecycle — LLM applications, retrieval-augmented generation, multi-agent systems, and the FastAPI/Postgres backends that ship them. Before AI, I spent years in hardware R&D and manufacturing process engineering, which shows up now as a bias for measurable, production-ready systems over demos.

**Currently:** AI Engineer at Opus Solutions Limited (Hong Kong), building an air-gapped, on-premise RAG platform for document intelligence — LangGraph + Qdrant hybrid retrieval (dense + BM25 + RRF), async FastAPI/PostgreSQL/Celery, and LLM inference (vLLM, llama.cpp) sized for constrained, sovereign deployments.

---

## Tech Stack

**LLM & Agents**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-8A2BE2?style=flat-square)
![vLLM](https://img.shields.io/badge/vLLM-FF6F00?style=flat-square)
![llama.cpp](https://img.shields.io/badge/llama.cpp-00897B?style=flat-square)

**Retrieval & Data**
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square)
![Hybrid Search](https://img.shields.io/badge/Hybrid_(BM25%2BRRF)-333333?style=flat-square)

**Backend & Infra**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**ML & Data Science**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

---

## Featured Projects

### [multi-doc-rag](https://github.com/Jasman123/multi-doc-rag)
Multi-document RAG API — upload PDFs, ask questions across them, get answers grounded in cited source chunks.
- **Architecture:** FastAPI on a ports & adapters (hexagonal) core — swapping LLM/embedding providers means writing an adapter, not touching business logic
- **Retrieval:** ChromaDB (vector) + BM25 (keyword) hybrid search fused with RRF, orchestrated as a corrective RAG pipeline in LangGraph (grades results, rewrites the query, and retries before falling back)
- **Auth:** JWT access/refresh tokens, Postgres-backed user store

### [Fastapi-repo-project](https://github.com/Jasman123/Fastapi-repo-project)
A monorepo of LangGraph agent projects:
- **Autonomous Research Agent** — plans, searches the web, and writes structured research reports end to end
- **[Support Agent with RAG](https://github.com/Jasman123/Fastapi-repo-project/tree/feat/support-agent)** — customer-support assistant grounded in a knowledge base, hybrid retrieval, streaming responses
- **Lead-Generation Agent** — headless-browser lead/job discovery synced to Google Sheets

### [Portfolio & case studies](https://jasman123.github.io/jasman-portfolio/)
Full write-ups of client and freelance work — including a 60+ country AI-agent sourcing pipeline for Startup World Cup, and a churn model built for a segmented SaaS customer base.

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Jasman123&show_icons=true&theme=github_dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Jasman123&layout=compact&theme=github_dark&hide_border=true)

</div>

---

## Let's Connect

Open to AI/ML engineering roles and freelance collaboration — RAG systems, LLM applications, and production backends.

- 🌐 **Portfolio:** [jasman123.github.io/jasman-portfolio](https://jasman123.github.io/jasman-portfolio/)
- 💼 **LinkedIn:** [linkedin.com/in/jasman-jasman-74ab21186](https://www.linkedin.com/in/jasman-jasman-74ab21186)
- 📧 **Email:** jasman0603@gmail.com
