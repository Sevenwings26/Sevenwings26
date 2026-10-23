# Hi there, I'm Iyanu Arowosola 👋

### **Backend & AI Systems Engineer** | Enterprise RAG · LLM Agents · Python (FastAPI, Django)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Iyanu_Arowosola-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/iyanuarowosola)
[![GitHub](https://img.shields.io/badge/GitHub-Sevenwings26-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sevenwings26)
[![Email](https://img.shields.io/badge/Email-iarowosola25%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iarowosola25@gmail.com)
[![Location](https://img.shields.io/badge/Location-Ibadan,_Nigeria_(UTC+1)-2ea44f?style=for-the-badge)](https://github.com/Sevenwings26)

---

### ⚡ About Me

I am a **Backend and AI Engineer** with **4+ years of backend experience** (and **2+ years in AI/ML**), specializing in **Enterprise Retrieval-Augmented Generation (RAG)**, autonomous context engines, and high-concurrency Python backends (**FastAPI, Django**) across enterprise AI, health-tech, and fintech/e-commerce.

> *"AI hasn't come to make software easy; it has come to raise the bar for system architecture."*

- 🔭 **Currently building:** An on-premise, multi-tenant **Enterprise RAG & Autonomous Context Platform** at **TechyZ Limited** designed for 100–1,000+ users across relational databases (PostgreSQL, MSSQL, Oracle) and corporate knowledge silos (SharePoint, Confluence, Google Workspace).
- 🧠 **System Focus:** Replacing stochastic context amnesia and $O(N^2)$ prompt stuffing with **LangGraph state machines**, **Redis JSON blackboards**, **0ms regex fast-paths**, and **AST-validated Text-to-SQL sandboxes**.
- 🛡️ **Security & Scale:** Enforcing zero-leakage multi-tenancy via **Keycloak SSO (OIDC/OAuth2)** JWT role claims mapped to **Qdrant** index-level payload pre-filters and row-level database RBAC.
- 👨‍🏫 **Community & Mentorship:** Trained **100+ developers** in production Python backend engineering, OAuth2/JWT security, database sharding, and AWS deployments.

---

### 🛠️ Technical Stack

#### **Languages & Backend Frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/Django_REST-ff1709?style=flat-square&logo=django&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![AsyncIO](https://img.shields.io/badge/AsyncIO-3776AB?style=flat-square&logo=python&logoColor=white)

#### **AI, RAG & Retrieval Systems**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6F00?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant_Vector_DB-DC244C?style=flat-square)
![Text-to-SQL](https://img.shields.io/badge/Dynamic_Text--to--SQL-00599C?style=flat-square)
![Hybrid Search](https://img.shields.io/badge/Hybrid_Search_%26_RRF-6B46C1?style=flat-square)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![InsightFace](https://img.shields.io/badge/InsightFace_(CV)-FF4B4B?style=flat-square)

#### **Databases, Messaging & Streaming**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MS SQL Server](https://img.shields.io/badge/MS_SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis_(Blackboard_%26_Cache)-DC382D?style=flat-square&logo=redis&logoColor=white)
![SSE](https://img.shields.io/badge/Server--Sent_Events_(SSE)-000000?style=flat-square)

#### **Cloud, DevOps & Security**
![AWS](https://img.shields.io/badge/AWS_(ECS,_RDS,_S3)-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_%26_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak_(OIDC_%2F_OAuth2)-4D4D4D?style=flat-square&logo=keycloak&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_%2F_Bash-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### 🚀 Featured Systems & Architecture

#### 1. 🦅 [Enterprise Multi-Tenant Cognitive RAG & Autonomous Context Engine](https://github.com/Sevenwings26/cognitive-rag-system)
> *Modular Clean Architecture RAG platform uniting heterogeneous SQL databases and corporate knowledge silos under strict RBAC.*
- **Decoupled Strategy Pattern Orchestration:** Routes intents across isolated execution pipelines—Stateless Dynamic Text-to-SQL, ACL-governed Qdrant Vector RAG, Ephemeral Session Document Q&A, and Conversational turns.
- **Universal Blackboard (`Redis` + `LangGraph`):** Maintains out-of-band working memory with a post-execution `StateHarvester` that extracts primary keys and metrics to enable virtualization-free cross-database foreign-key joins (e.g., resolving a customer ID in PostgreSQL on Turn 1 and binding to T-SQL in MSSQL on Turn 4).
- **Zero-Leakage Security:** Keycloak SSO (OIDC/OAuth2) JWT claims bound to Qdrant payload pre-filters + runtime SQLAlchemy schema reflection and AST-validated read-only SQL sandboxes.

#### 2. 🏥 Multi-Tenant Clinical LIMS & Async Diagnostic Engine *(Medvuno)*
- Architected a multi-tenant Laboratory Information Management System on **Django** with strict row-level tenant isolation and department-level RBAC.
- Engineered an asynchronous **Gemini-powered diagnostic reporting pipeline** using **Celery & Redis**, decoupling LLM report synthesis from HTTP cycles and reducing database load by 40%.
- Designed an event-driven clinical alert notification system and automated zero-downtime CI/CD deployments to **AWS ECS/RDS** via GitHub Actions.

#### 3. 📈 Chrysalis Finance — Equities Intelligence & RAG Assistant
- Built a financial intelligence platform for Nigerian equities (**NGX**) featuring real-time market feeds, wallet infrastructure, trading simulation, and a **RAG-powered market assistant** that explains equity movements and financial data.

#### 4. 👤 High-Throughput Face Extraction & Identity Resolution Pipeline
- Developed a computer vision pipeline using **InsightFace** and **ONNX Runtime** to isolate specific individuals in complex group photos using **512-dimensional face embeddings** and pre-normalized cosine similarity matching for low-CPU batch runs.

#### 5. 💳 MarketPrime — E-Commerce Marketplace & Payment Infrastructure
- Led backend & third-party integrations on a ~15-person team using **Django REST Framework**, integrating **Paystack** for customer checkout, automated split vendor disbursements, webhook reconciliation, and automated vendor KYC.

---

### 💼 Experience Snapshot

| Role | Organization | Period | Core Focus |
| :--- | :--- | :--- | :--- |
| **Backend / RAG Engineer** | **TechyZ Limited** *(Remote)* | Jun 2026 – Present | Enterprise RAG, LangGraph/Redis Blackboard, Text-to-SQL, Keycloak RBAC, Qdrant |
| **Lead Backend Developer** | **Medvuno** *(Contract, Remote)* | Oct 2025 – Mar 2026 | Multi-Tenant LIMS, Django, Gemini + Celery/Redis Async Pipelines, AWS ECS/RDS |
| **Python Dev Instructor** | **Soft Quest Inc. (SQI)** *(Ibadan)* | May 2024 – Jun 2026 | Trained 100+ students in API Security (OAuth2/JWT), System Design, Sharding & AWS |
| **Backend & Integration Lead**| **MarketPrime** *(Remote)* | Sep 2024 – Dec 2024 | DRF Marketplace, Paystack Webhooks & Disbursements, Automated KYC, Latency Tuning |
| **Full-Stack Web Developer** | **Arcade Dynasty** *(Contract)* | Apr 2022 – Sep 2024 | RESTful Django APIs, PostgreSQL Query Optimization, JWT/RBAC, React Integration |

---

### 📈 GitHub Stats

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=Sevenwings26&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sevenwings26&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>
</div>

---

### 🤝 Let's Connect

- 💼 **LinkedIn:** [linkedin.com/in/iyanuarowosola](https://linkedin.com/in/iyanuarowosola)
- 📧 **Email:** [iarowosola25@gmail.com](mailto:iarowosola25@gmail.com)
- 🌍 **Location:** Ibadan, Nigeria (WAT, UTC+1) — *Open to Remote & Global Opportunities*
