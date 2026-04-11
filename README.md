# Azhan Khan — Data Engineer & AI Systems Builder

**Building data pipelines and agentic AI systems at scale.**

Most recently: ML training data infrastructure for **NVIDIA's autonomous driving program** at Zensar Technologies — 100K+ multi-modal records daily, 35% reduction in training data defect rates.

Gen AI APAC Hackathon: Built **PatchPilot** — a 7-agent autonomous incident response system with real MCP protocol, Gemini function-calling, FAISS memory, and WebSocket streaming. Deployed on GCP Cloud Run.

Currently open to **remote data engineering roles** and **freelance Azure / agentic AI projects**.

---

## What I Build

```
Data Engineering:
Raw Data → Ingestion (ADF) → Bronze → Silver → Gold → BI / ML

Agentic AI:
Alert → Planner → Memory → Tools[×8 parallel] → Diagnosis → Debate → Controller
```

End-to-end Azure data platforms · Scalable ETL in Python & PySpark · Medallion Architecture  
Multi-agent AI systems · LangChain · LangGraph · Gemini · MCP Protocol · GCP

---

## Tech Stack

**Data Engineering**
```
Python · PySpark · SQL · Azure Data Factory · Azure Databricks · Delta Lake
ADLS Gen2 · Unity Catalog · Azure Synapse · DuckDB · Alembic · Pandas · Power BI
```

**Agentic AI & LLMs**
```
Gemini (Vertex AI) · LangChain · LangGraph · FAISS · MCP Protocol (JSON-RPC 2.0)
sentence-transformers · Gemini function-calling · Multi-agent orchestration
```

**Cloud & DevOps**
```
Microsoft Azure · GCP (Cloud Run · Firestore · Pub/Sub · Cloud Monitoring · Cloud Logging)
AWS (EC2 · S3) · Docker · GitHub Actions · CI/CD · Cloud Build · Secret Manager
```

**Backend**
```
FastAPI · Django · REST APIs · WebSockets · asyncio
```

---

## Featured Projects

### [PatchPilot — Multi-Agent Autonomous Incident Response](https://github.com/azhannnnn/patchpilot)
`Gemini` `LangGraph` `MCP` `FAISS` `Firestore` `Cloud Run` `FastAPI` `WebSocket` `Pub/Sub`

> Built for the Gen AI APAC Hackathon

7-agent autonomous system that detects infrastructure incidents, diagnoses root causes with Gemini AI, debates fix strategies adversarially with dual Gemini instances, and resolves incidents — with or without human approval.

```
Alert → PlannerAgent (Gemini fn-calling)
      → MemoryAgent (FAISS + Firestore fingerprint)
      → ToolAgent [8 tools, asyncio.gather PARALLEL]
      → DiagnosticAgent (Gemini RCA synthesis)
      → DebateAgent (dual Gemini, adversarial)
      → TaskAgent (Firestore task scheduling)
      → ControllerAgent (human approval OR auto-fix)
```

- Real MCP protocol — JSON-RPC 2.0 `/mcp` endpoint
- Real GCP APIs — Cloud Monitoring · Cloud Logging · Cloud Run Admin
- FAISS memory — repeat incidents auto-resolve in <2s (no human needed)
- WebSocket real-time agent trace streaming (no polling)
- Deployed on GCP Cloud Run with Docker + nginx

---

### [Scalable Car Sales Analytics Platform](https://github.com/azhannnnn/carSalesProject)
`Azure` `ADF` `Databricks` `PySpark` `Delta Lake` `Unity Catalog` `Power BI`

End-to-end Azure analytics platform on Medallion Architecture (Bronze → Silver → Gold).
5M+ records · Star Schema + SCD Type 2 · Power BI dashboards · Unity Catalog governance.

---

### [Healthcare RCM Data Platform](https://github.com/azhannnnn/RCMdataPlatform)
`Azure` `ADF` `Databricks` `Delta Lake` `PySpark` `GitHub Actions` `Key Vault`

Production data platform for Healthcare Revenue Cycle Management.
2M+ patient records · Metadata-driven ADF pipelines · ICD/CPT code standardization · Full CI/CD.

---

### [Hiring Platform](http://azhanfolio.pythonanywhere.com/)
`Django` `REST API` `AWS`

Job portal handling 1000+ users, 500+ listings, and 2000+ daily requests.

---

## Experience

**Data & AI Operations Engineer** — Zensar Technologies · Client: NVIDIA *(Sep 2025 – Apr 2026)*
→ ML training data pipelines for NVIDIA autonomous driving · 100K+ records/day · 35% defect reduction

**Data Engineer Intern** — Netlink Software Group America *(Feb 2025 – May 2025)*
→ Production ETL pipelines · Python · DuckDB · Alembic migrations

**Software Engineer Intern** — Wyreflow Technology *(May 2024 – Sep 2024)*
→ Django REST APIs · AWS EC2 · 20% response time improvement · 30% bug reduction

---

## Competitive Programming

- LeetCode Rating: **1750+** · Solved: **500+ problems**
- **World Rank 321** among 22,000+ participants — LeetCode Weekly Contest 430 *(Top 8.5% globally)*

![LeetCode Stats](https://leetcard.jacoblin.cool/azhan-born-to-win?theme=dark&font=Source%20Code%20Pro&ext=contest)

---

## Certifications

- Databricks Fundamentals Accreditation
- Oracle Multicloud Architect Professional
- Get Started with Databricks for Data Engineering
- HackerRank Certified — Python & SQL
- Deloitte Australia Data Analytics Job Simulation

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/azhankhan22)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black)](https://leetcode.com/u/azhan-born-to-win/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:work.azhankhan@gmail.com)

`work.azhankhan@gmail.com` · Bhopal, India · Open to Remote & Freelance
