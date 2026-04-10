# MIGUEL DE SOUSA
**Senior DevOps & Python Engineer | Specialized in Agentic AI & LLMOps**

Olinda VIC 3788 | 0497 646 933 | miguel.desousa@protonmail.com | [github.com/miguel-tronix](https://github.com/miguel-tronix)
**Australian Citizen** | Available for Contract & Permanent Roles

---

## AI Infrastructure & DataOps Engineer | LLMOps & Platform Engineering

### Summary

Exceptional AI Infrastructure and DataOps Engineer combining deep software engineering foundations with cutting-edge **LLMOps** and ML operations expertise. Proven capability to orchestrate intensive AI/ML workloads on **Amazon EKS** with GPU-enabled node pools, build scalable **S3 Data Lakes**, and handle complex spatial queries using **PostgreSQL with PostGIS**. Experienced provisioning environments for **LLM data pre-training** and deploying autonomous **Scalable AI Agents** to Kubernetes. Architect of the **Traific Geospatial AI Platform** — a cloud-native system for ingesting, processing, and analysing geospatial traffic data at scale. Expert in **Infrastructure as Code** (**Terraform**, **Ansible**) applied directly to AI/ML environments, bridging traditional data engineering with modern **Platform Engineering** for AI. Demonstrates **FinOps** discipline through cost-optimised Spot/On-Demand EKS node group configurations for ML workloads. Seeking an AI Infrastructure or DataOps leadership role in the Australian enterprise or AI scale-up market.

### Technical Skills — ATS Capability Clusters

*   **AI/LLM Engineering (LLMOps & Scalable Agents):** Amazon EKS for ML workloads (GPU node pools), LLM data pre-training pipelines (BPE tokenisation, PII removal, deduplication), RAG Agent deployment (LangChain, HuggingFace sentence-transformers, pgvector), Vector DBs (pgvector — 768-dimension embeddings, cosine similarity), LLM Evaluation & Observability, ML model serving, Python Automation
*   **Data Platforms & Geospatial:** S3 Data Lakes (versioned, AES256 encrypted), PostgreSQL 16.1 with PostGIS (postgis, postgis_raster, pg_stat_statements), Apache Spark, Kafka, Airflow, Databricks, Redshift, Athena, Glue, NiFi, Talend
*   **Platform Engineering & Infrastructure as Code:** Terraform (AWS provider 5.x — EKS, VPC, RDS, S3), Ansible (kubernetes.core), AWS CDK, CloudFormation, Kubernetes (EKS 1.29, OpenShift), Docker, ArgoCD, Helm; FinOps (Spot/On-Demand node optimisation)
*   **MLOps & Observability:** Prometheus, Grafana, ELK, Datadog, CloudWatch, LangSmith; Streaming: Apache Kafka, MQTT (EMQX 5.8), RabbitMQ, Redis, Celery; Programming: Python (FastAPI, Pydantic V2, Typer, Pandas, PyArrow), Golang, Scala, Java

### GitHub

[https://github.com/miguel-tronix](https://github.com/miguel-tronix)

### Professional Experience

**Senior Software Engineer** | Quantaco | Melbourne, VIC
*October 2025 – March 2026*

*   Achieved **>100% throughput improvement** on a large ERP Microservices **FastAPI** platform by refactoring to **Pydantic V2**, AsyncIO, and FastAPI best practices — including unit and smoke test coverage — eliminating a major Developer Experience (DevEx) bottleneck for the engineering team.
*   Reduced database load and improved API response times by **60%** by engineering a **Redis**-based caching and session management layer, producing measurable FinOps savings on infrastructure costs.
*   Implemented **Terraform** for GitOps-driven continuous deployment across development, staging, and production, establishing Infrastructure as Code standards for the platform.

**Architect and CTO** | Azez | Melbourne, VIC
*April 2025 – September 2025*

*   Reduced drug contra-indication research time significantly by architecting and shipping **DeepDivee** — a production-grade **RAG Agent** using FastAPI, LangChain, HuggingFace sentence-transformers (`all-MiniLM-L6-v2`), and pgvector for semantic vector search over PubMed medical literature — a full **LLMOps** lifecycle from training data to production inference.
*   Deployed the AI Agent in a Kubernetes ecosystem with **PostgreSQL Vector Search** (768-dimension embeddings, cosine similarity), MinIO object storage, and FastAPI microservices, demonstrating end-to-end **Scalable Agent** infrastructure management.

**DevOps Engineer / Site Reliability Engineer** | Telstra Special Networks Engineering (SNE) | Melbourne, VIC
*October 2022 – April 2025*

*   Reduced national security data processing latency by **40%** by deploying optimised low-latency **Spark** jobs to edge nodes, replacing centralised cloud cluster processing — a key **FinOps** and Platform Engineering outcome.
*   Provisioned and managed **Amazon EKS** clusters for AI/ML workloads, configuring GPU-enabled node pools and auto-scaling for model training and inference, reducing model deployment lead-time by 60%.
*   Built and maintained **S3 Data Lakes** (versioned, AES256 encrypted) for large-scale dataset storage, integrated with Athena for interactive query capability.
*   Implemented CI/CD pipelines for ML model deployment using Jenkins, GitLab, and ArgoCD (**LLMOps** automation).

**Senior Software Engineer** | NetApp | Melbourne, VIC
*January 2020 – May 2022*

*   Reduced invoice errors by **95%** by designing and building the Keystone Billing engine (Python, Golang, RabbitMQ, MongoDB, Zuora), accurately tracking $2M+ annual usage data — a critical **FinOps** and revenue-integrity result.
*   Built automated provisioning systems on Kubernetes enabling resource allocation for storage workloads across multi-cloud environments (AWS, GCP, Azure).

**Data Engineer** | Sportsbet | Melbourne, VIC
*September 2019 – November 2019*

*   Managed large-scale **AWS data lake** resources (10TB+ daily processing) using NiFi, Talend, AWS Glue, Databricks, Redshift, and Athena.
*   Eliminated PII data exposure risk by designing Talend workflows for automated **PII sanitisation** of chat logs prior to Kafka ingestion, ensuring data privacy compliance (ISO 27001).
*   Built real-time data pipelines using **Kafka** for high-throughput streaming and processing at scale.

**Big Data DevOps Engineer** | Telstra (CTO/Big Data Analytics) | Melbourne, VIC
*October 2017 – December 2018*

*   Eliminated data loss on 500Gb+ daily LBS ingestion by optimising **Spark** cluster jobs (Scala, Python, Java) and stabilising the NiFi/Kafka/HDFS ingestion pipeline — unlocking reliable data for data scientists.
*   Built and maintained data pipelines using **Airflow** DAGs, Kafka, NiFi, and HDFS, automating containerised workflows with Docker.
*   Delivered computationally intensive Population-Volume and Origin-Destination models for the Sydney Metro project using Spark, Hadoop, Kafka, and Zookeeper.
*   Built GCP PoC cluster (GKE, PubSub, BigTable) evaluating cloud-native **Platform Engineering** data platform alternatives.

---

### Recent Projects

**Traific Geospatial AI Platform**
*   Architected a reproducible AI platform on **Amazon EKS 1.29** with secure VPC network isolation (public/private subnets across 3 AZs) for geospatial data processing and ML inference — full Infrastructure as Code using **Terraform** (AWS provider 5.x).
*   Provisioned **PostgreSQL 16.1** with **PostGIS** extensions (postgis, postgis_raster, pg_stat_statements) for complex spatial queries at scale.
*   Built scalable **S3 Data Lake** architecture (versioned, AES256 encrypted) for terabytes of geospatial imagery and sensor data.
*   Configured **FinOps**-optimised EKS node groups: `stateless` (Spot instances, auto-scaling 2–8 nodes) and `redis` (On-Demand, dedicated with workload taints).

**LLM Data Pretraining Pipeline (LLMOps)**
*   Engineered a high-performance **Python Automation** pipeline (Pydantic V2, Typer CLI, Pandas, PyArrow) for processing HuggingFace Uncopyrighted Pile records into tokenised datasets for LLM pre-training.
*   Implemented automated **PII removal** (emails, phones, SSNs, patient IDs), content-hash **deduplication**, and **BPE tokenisation** (configurable vocab, 50K default) to efficiently handle large-scale corpora at scale.
*   Containerised the pipeline using **Docker** (multi-stage build, python:3.10-slim) with resource limits for reproducible execution across disparate compute environments — production-grade **LLMOps** tooling.

**DeepDivee AI Agent (Scalable Agents)**
*   Architected and deployed a production **RAG Agent** using FastAPI, LangChain, HuggingFace, and pgvector — full **LLMOps** lifecycle from embedding generation through to production inference in Kubernetes.
*   Deployed as a **Scalable Agent** in a GitOps Kubernetes ecosystem (Gitea, ArgoCD, MinIO, HashiCorp Vault, APISIX), with health checks, auto-scaling, and Prometheus/Grafana monitoring.

---

### Education

**Bachelor of Engineering (B.Eng.), Software Engineering**
University of Western Australia | Perth, WA | Graduated 2004

---
