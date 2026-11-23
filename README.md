<div align="center">

# B Sai Sannidh

**Software Engineer · I build production LLM apps (RAG, agents) · Python · FastAPI · PostgreSQL · Bangalore**

[![Portfolio](https://img.shields.io/badge/kravlone.xyz-ask_my_AI_résumé-111F35?style=for-the-badge&labelColor=F63049)](https://kravlone.xyz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111F35?style=for-the-badge&logo=linkedin&logoColor=F63049)](https://www.linkedin.com/in/b-sai-sannidh/)
[![Email](https://img.shields.io/badge/Email-111F35?style=for-the-badge&logo=gmail&logoColor=F63049)](mailto:b.sai.sannidh@gmail.com)

</div>

## What I'm building at work

Software Engineer at **Arpa Global Infotech** (promoted Aug 2026). The code is private, so here's what it does:

- **ERP Copilot:** managers and purchasing teams ask questions about their ERP data in plain English and get answers from SQL that the copilot writes for them. I designed, built and shipped it; **60+ users at 2 enterprise clients** use it.
- **Schema retrieval:** the ERP has 1,000+ tables and 30K+ columns, about 150K tokens. Hybrid retrieval (embeddings + BM25 over per-table chunks with foreign-key links) picks only the tables a question needs, so prompts are **~2K tokens**.
- **Tests and guardrails:** before every release I run a test set of **100+ real questions with known-correct SQL**. Guardrails stop destructive SQL and block reads of tables a user isn't allowed to see.
- **Code knowledge base for a legacy ERP:** modeled the .NET / VB.NET code, SQL Server stored procedures and DB schema as a **Neo4j knowledge graph (1M+ nodes/edges, 10K+ procedures, screens and functions indexed)**. An MCP server gives a Claude Agent SDK agent tools to search that graph. **15 people** use it, and it has cut support-ticket resolution from days to hours and onboarding from weeks to days.
- **Deployments:** CI/CD with Jenkins, GitHub Actions, Docker and Nginx on AWS EC2 for 3 clients, so a deploy is one click.

## Projects

| Project | What it is | Stack |
|---|---|---|
| [**portfolio**](https://github.com/KraVLonE/portfolio) · [live](https://kravlone.xyz) | Portfolio with an AI assistant that answers questions about my work, plus an admin panel to manage the content | React, TypeScript, FastAPI, PostgreSQL, Docker |
| [**SIH_Ganga**](https://github.com/KraVLonE/SIH_Ganga) · [live](https://ganga.kravlone.xyz) | Daily estimates and 5-day forecasts of Ganga water quality over 1,369 km, with uncertainty ranges. Smart India Hackathon 2024 finalist | Python, PostgreSQL, TimescaleDB, PostGIS |
| [**Traffic-Control-Optimization**](https://github.com/KraVLonE/Traffic-Control-Optimization) · [live](https://traffic-ai.kravlone.xyz) | Q-learning agent that controls traffic lights at a 4-way junction, compared against fixed-cycle and actuated controllers on the same traffic | Python, React, Recharts |
| [**Ambulance-Management-System**](https://github.com/KraVLonE/Ambulance-Management-System) · [live](https://ambulance-management.kravlone.xyz) | Real-time ambulance dispatch: sends the fastest unit by road (OSRM), queues calls by severity, public tracking link | JavaScript, PostgreSQL, Docker |
| [**GeoGuide**](https://github.com/KraVLonE/GeoGuide) · [demo](https://www.youtube.com/watch?v=jPzFFzKt_RI) | Robot that spots disaster events from an overhead camera and drives to them in priority order. Top 30 of 4,000+ teams in e-Yantra (IIT Bombay) | Python, PyTorch, OpenCV, C++ |
| [**ClipIn**](https://github.com/KraVLonE/ClipIn) · [Firefox add-on](https://addons.mozilla.org/en-US/firefox/addon/clipin) | Browser extension that saves a LinkedIn profile to a Notion database in one click | JavaScript, Notion API |

## Stack

**AI**
![LangChain](https://img.shields.io/badge/LangChain-111F35?style=flat-square&logo=langchain&logoColor=F63049)
![LangGraph](https://img.shields.io/badge/LangGraph-111F35?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-111F35?style=flat-square)
![RAG](https://img.shields.io/badge/RAG_·_Hybrid_Search-111F35?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-111F35?style=flat-square&logo=pytorch&logoColor=F63049)
![OpenCV](https://img.shields.io/badge/OpenCV-111F35?style=flat-square&logo=opencv&logoColor=F63049)

**Backend**
![Python](https://img.shields.io/badge/Python-111F35?style=flat-square&logo=python&logoColor=F63049)
![FastAPI](https://img.shields.io/badge/FastAPI-111F35?style=flat-square&logo=fastapi&logoColor=F63049)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111F35?style=flat-square&logo=postgresql&logoColor=F63049)
![Neo4j](https://img.shields.io/badge/Neo4j-111F35?style=flat-square&logo=neo4j&logoColor=F63049)
![Redis](https://img.shields.io/badge/Redis-111F35?style=flat-square&logo=redis&logoColor=F63049)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-111F35?style=flat-square&logo=rabbitmq&logoColor=F63049)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-111F35?style=flat-square&logo=sqlalchemy&logoColor=F63049)

**Frontend**
![React](https://img.shields.io/badge/React-111F35?style=flat-square&logo=react&logoColor=F63049)
![TypeScript](https://img.shields.io/badge/TypeScript-111F35?style=flat-square&logo=typescript&logoColor=F63049)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-111F35?style=flat-square&logo=tailwindcss&logoColor=F63049)

**DevOps**
![Docker](https://img.shields.io/badge/Docker-111F35?style=flat-square&logo=docker&logoColor=F63049)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-111F35?style=flat-square&logo=githubactions&logoColor=F63049)
![Jenkins](https://img.shields.io/badge/Jenkins-111F35?style=flat-square&logo=jenkins&logoColor=F63049)
![Nginx](https://img.shields.io/badge/Nginx-111F35?style=flat-square&logo=nginx&logoColor=F63049)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-111F35?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-111F35?style=flat-square&logo=linux&logoColor=F63049)

---

<div align="center">

TCS CodeVita global rank 1844 / 537K+ · Smart India Hackathon 2024 finalist · Off the keyboard: chess

*"I can make it work on your machine."*

</div>
