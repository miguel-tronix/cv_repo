# Miguel de Sousa — CV & Project Showcase

> **Senior DevOps & Python Engineer | Specialized in Agentic AI & LLMOps**
> Australian Citizen | Melbourne, VIC | Available for Contract & Permanent Roles
> 📧 miguel.desousa@protonmail.com | 📞 0497 646 933 | 🐙 [github.com/miguel-tronix](https://github.com/miguel-tronix)

---

## About

This repository contains targeted CV variants, each tailored for a specific market segment of the Australian senior engineering contract and permanent market (2026). The CVs are maintained as Markdown and compiled to `.docx` using Pandoc with a reference template.

Miguel is a hands-on architect and engineer with 15+ years spanning enterprise, government, fintech, and healthcare. His edge is the rare combination of deep **Python automation** and **Platform Engineering** — applied directly to cutting-edge **AI/LLM infrastructure** (LLMOps, Agentic AI, RAG pipelines).

---

## CV Variants

| Role Focus | File | Target Market |
|---|---|---|
| **Master / Full CV** | [`full_cv_gemini.md`](./full_cv_gemini.md) | All-round senior engineering roles |
| **Cloud Native & GitOps / Platform Engineering** | [`devops/devops_cv.md`](./devops/devops_cv.md) | DevOps, SRE, Platform Eng, Infrastructure Architect |
| **AI Infrastructure & DataOps / LLMOps** | [`dataops/dataops_cv_gemini.md`](./dataops/dataops_cv_gemini.md) | AI Infra, DataOps, MLOps, Data Platform Engineering |
| **Senior Python Microservices Architect** | [`dev/dev_cv_gemini_summary.md`](./dev/dev_cv_gemini_summary.md) | Python Backend, Microservices Architect, API Engineer |

### Plain-Text Recruiter Versions (Direct-to-Recruiter Email)
| Role | File |
|---|---|
| DevOps / Platform Engineering | [`plain_text/miguel_devops_plain.txt`](./plain_text/miguel_devops_plain.txt) |
| AI Infrastructure / DataOps / LLMOps | [`plain_text/miguel_dataops_plain.txt`](./plain_text/miguel_dataops_plain.txt) |
| Python Microservices Architect | [`plain_text/miguel_dev_plain.txt`](./plain_text/miguel_dev_plain.txt) |

---

## Key Technical Strengths

```
Platform Engineering     LLMOps                  Python Automation
DevSecOps                Scalable Agents          Infrastructure as Code
FinOps & Cost Reduction  Agentic AI / RAG         Developer Experience (DevEx)
```

---

## Highlighted Projects

### 🤖 DeepDivee AI Agent (Production RAG / Scalable Agent)
> *Azez | April 2025 – September 2025*

A production-grade **Agentic AI** system providing drug contra-indication insights via Retrieval-Augmented Generation (RAG) over PubMed medical literature.

**Stack:** FastAPI · LangChain · HuggingFace (`all-MiniLM-L6-v2`) · pgvector (768-dim, cosine similarity) · PostgreSQL · MinIO · HashiCorp Vault · APISIX API Gateway · ArgoCD · Kubernetes (GitOps)

**Highlights:**
- Full **LLMOps** lifecycle: embedding pipeline → vector store → inference API → Kubernetes deployment
- **Scalable Agent** with ArgoCD automated sync, self-healing, and Prometheus/Grafana observability
- Cross-cloud secrets management: GCP credentials dynamically injected into Kubernetes Secrets via Vault (**DevSecOps**)

---

### 🌍 Traific Geospatial AI Platform (AWS / Platform Engineering)
> *2024 – 2025*

Cloud-native AI platform for ingesting, processing, and analysing geospatial traffic data at scale on AWS EKS.

**Stack:** Terraform (AWS provider 5.x) · EKS 1.29 · RDS PostgreSQL 16.1 + PostGIS · S3 Data Lake (AES256) · VPC (3-AZ, public/private) · Ansible · ArgoCD · Redis · Prometheus/Grafana

**Highlights:**
- Fully reproducible **Infrastructure as Code** — VPC, EKS, RDS, S3 provisioned via Terraform modules
- **FinOps** optimised: Spot instances (stateless, 2–8 auto-scaling) + On-Demand (Redis, dedicated node taint)
- PostGIS extensions (postgis, postgis_raster, pg_stat_statements) for complex spatial ML queries

---

### 🧠 LLM Data Pretraining Pipeline (LLMOps / Python Automation)
> *2024 – 2025*

High-performance Python data pipeline for preparing large-scale corpora for LLM pre-training.

**Stack:** Python (Pydantic V2 · Typer CLI · Pandas · PyArrow) · Docker (multi-stage, python:3.10-slim) · HuggingFace Uncopyrighted Pile · BPE Tokenisation · Kubernetes Job

**Highlights:**
- Automated **PII removal** (emails, phones, SSNs, patient IDs) + content-hash **deduplication**
- Configurable **BPE tokenisation** (50K default vocab) for LLM pre-training datasets
- Production containerised as a **Kubernetes Job** — reproducible across disparate compute environments

---

### 🏢 Keystone NetApp Service Engine (Enterprise / FinOps)
> *NetApp | January 2020 – May 2022*

Global cloud/data centre storage provisioning and monitoring platform supporting Mercedes, Aston Martin Racing, Thomson Reuters, and Cisco.

**Stack:** Python · Golang · RabbitMQ · MongoDB · Ansible · Kubernetes · HashiCorp Vault · AWS · GCP · Azure · Zuora

**Highlights:**
- **95% reduction in invoice errors** — Billing engine accurately tracked $2M+ annual storage usage (**FinOps**)
- Resolved critical concurrency issues in automated ONTAP provisioning via Python Automation
- **DevSecOps**: HashiCorp Vault for dynamic secrets across Kubernetes multi-cloud deployments

---

### 🏥 NutritionWeb — World-First Clinical Dietician System
> *The Alfred Hospital, ICU | 2012*

The world's first electronic management system for clinical dieticians, purpose-built for Australia's largest and most advanced ICU.

**Award:** The Alfred dietician team won **"World Best Nutritional Practices for Critically-Ill Patients" (2012)** — directly enabled by this system.

**Stack:** Java 7 · Glassfish 4 · JPA · Cayenne · AngularJS · MySQL · PDFBox

---

## Agent Instructions

This repository also contains agent prompts in [`Agent.md`](./Agent.md) for generating role-targeted CVs from the master document, and improvement strategies in [`Resume_Improvement.md`](./Resume_Improvement.md).

---

## Compile to Word (Pandoc)

```bash
# Full CV
pandoc full_cv_gemini.md -o full_cv_gemini.docx --reference-doc=reference-template.docx

# Targeted CVs
pandoc devops/devops_cv.md -o devops/devops_cv_gemini.docx --reference-doc=reference-template.docx
pandoc dataops/dataops_cv_gemini.md -o dataops/dataops_cv_gemini.docx --reference-doc=reference-template.docx
pandoc dev/dev_cv_gemini_summary.md -o dev/dev_cv_gemini_summary.docx --reference-doc=reference-template.docx
```

---

*Last updated: April 2026*
