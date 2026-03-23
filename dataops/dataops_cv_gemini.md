**MIGUEL DE SOUSA**
Olinda VIC 3788 | 0497 646 933 | miguel.desousa@protonmail.com

---

## AI Infrastructure & DataOps Engineer

### Summary

Exceptional AI Infrastructure and DataOps Engineer combining deep software engineering foundations with cutting-edge ML operations expertise. Proven capability to orchestrate intensive AI/ML workloads on **Amazon EKS** with GPU-enabled node pools, build scalable **S3 Data Lakes**, and handle complex spatial queries using **PostgreSQL with PostGIS**. Experienced provisioning environments for **LLM data pre-training** and deploying autonomous **DeepDivee AI Agents** to Kubernetes. Architect of the **Traific Geospatial AI Platform** — a cloud-native system for ingesting, processing, and analyzing geospatial traffic data at scale. Expert in Infrastructure-as-Code (**Terraform**, **Ansible**) applied directly to AI/ML environments, bridging traditional data engineering with modern AI infrastructure. Seeking an AI Infrastructure or DataOps leadership role.

### Technical Skills

*   **AI/ML Infrastructure:** Amazon EKS (Kubernetes for ML workloads), GPU node pools, LLM data pre-training environments (BPE tokenization, PII removal, deduplication), RAG Agent deployment (LangChain, HuggingFace, pgvector), ML model serving
*   **Data Platforms & Geospatial:** S3 Data Lakes (versioned, encrypted), PostgreSQL 16.1 with PostGIS (postgis, postgis_raster, pg_stat_statements), Apache Spark, Kafka, Airflow, Databricks, Redshift, Athena, Glue, Nifi, Talend
*   **Infrastructure as Code:** Terraform (AWS provider 5.x — EKS, VPC, RDS, S3 modules), Ansible (kubernetes.core), AWS CDK, CloudFormation
*   **Containerization & GitOps:** Kubernetes (EKS 1.29, OpenShift), Docker, ArgoCD, Helm
*   **MLOps & Observability:** Prometheus, Grafana, ELK, Datadog, CloudWatch, MLflow
*   **Programming:** Python (FastAPI, Pydantic V2, Typer, Pandas, PyArrow), Golang, Scala, Java
*   **Streaming & Messaging:** Apache Kafka, MQTT (EMQX 5.8), RabbitMQ, Redis, Celery

### Professional Experience

**Senior Software Engineer** | Quantaco | Melbourne, VIC
*October 2025 – March 2026*

*   Refactored a large ERP Microservices FastAPI platform to use Pydantic V2 modelling, consistent exception handling, pagination, unit tests, smoke tests and significant performance speedup of over 100% for large dataset calls - utilizing AsyncIO, Redis and FastAPI best practices.
*   Implemented **Terraform** for GitOps-driven continuous deployment, ensuring automated, reliable application updates across development, staging, and production environments.
*   Engineered a robust **Redis**-based caching layer and session management system, significantly reducing database load and improving API response times by over 60%.

**Architect and CTO** | Azez | Melbourne, VIC
*April 2025 – September 2025*

*   Architected and implemented a **RAG Agent** (DeepDivee) using FastAPI, LangChain, HuggingFace sentence-transformers (all-MiniLM-L6-v2), and pgvector for semantic vector search over medical literature.
*   Deployed the AI Agent in a Kubernetes ecosystem with **PostgreSQL Vector Search** (768-dimension embeddings, cosine similarity), MinIO object storage, and FastAPI microservices, demonstrating full AI infrastructure lifecycle management.

**DevOps Engineer / Site Reliability Engineer** | Telstra Special Networks Engineering (SNE) | Melbourne, VIC
*October 2022 – April 2025*

*   Provisioned and managed **Amazon EKS** clusters for hosting intensive AI/ML workloads, configuring GPU-enabled node pools and auto-scaling for model training and inference.
*   Orchestrated deployment of autonomous **DeepDivee AI Agents** to Kubernetes, implementing auto-scaling, self-healing, and Prometheus/Grafana monitoring for model performance metrics and resource utilization.
*   Built and maintained **S3 Data Lakes** (versioned, AES256 encrypted) for storing and processing large-scale datasets, integrating with Athena for interactive querying.
*   Implemented CI/CD pipelines for ML model deployment using Jenkins, GitLab, and ArgoCD, reducing deployment time by 60%.
*   Optimized national security data processing by deploying low-latency **Spark** jobs to edge nodes, reducing processing time by 40% compared to centralized cloud clusters.

**Senior Software Engineer** | NetApp | Melbourne, VIC
*January 2020 – May 2022*

*   Designed and built data pipelines handling $2M+ annual usage data using Python, Golang, RabbitMQ, and MongoDB for the Keystone Billing engine.
*   Built automated provisioning systems on Kubernetes enabling resource allocation for storage workloads across multi-cloud environments (AWS, GCP, Azure).
*   Integrated with multiple cloud providers demonstrating multi-cloud data platform expertise for a global storage-as-a-service platform.

**Data Engineer** | Sportsbet | Melbourne, VIC
*September 2019 – November 2019*

*   Managed large-scale **AWS data lake** resources (10TB+ daily processing) using Nifi, Talend, AWS Glue, Databricks, Redshift, and Athena.
*   Designed Talend workflows for automated **PII sanitization** of chat logs prior to Kafka ingestion, ensuring data privacy compliance.
*   Built data pipelines using **Kafka** for real-time data streaming and processing at scale.

**Big Data DevOps Engineer** | Telstra (CTO/Big Data Analytics) | Melbourne, VIC
*October 2017 – December 2018*

*   Optimized **Spark** cluster job execution (Scala, Python, Java) for data scientists, processing 500Gb+ daily LBS data with zero data loss.
*   Built and maintained data pipelines using **Airflow** DAGs, **Kafka**, **NiFi**, and **HDFS**, automating containerized workflows with Docker.
*   Delivered computationally intensive Population-Volume and Origin-Destination models for the Sydney Metro project using Spark, Hadoop, Kafka, and Zookeeper.
*   Built GCP PoC cluster (GKE, PubSub, BigTable) evaluating cloud-native data platform alternatives.

### Recent Projects

**Traific Geospatial AI Platform**
*   Architected a reproducible AI platform on **Amazon EKS 1.29** with secure VPC network isolation (public/private subnets across 3 AZs) for geospatial data processing and ML inference.
*   Provisioned infrastructure using **Terraform** (AWS provider 5.x) managing **PostgreSQL 16.1** with **PostGIS** extensions (postgis, postgis_raster, pg_stat_statements) for complex spatial queries.
*   Built scalable **S3 Data Lake** architecture (versioned, AES256 encrypted) for storing terabytes of geospatial imagery and sensor data.
*   Configured EKS with dual node groups: `stateless` (Spot instances, auto-scaling 2-8 nodes) and `redis` (On-Demand, dedicated with workload taints) for cost-optimized AI workloads.

**LLM Data Pretraining Pipeline**
*   Engineered a high-performance **Python pipeline** (Pydantic V2, Typer CLI, Pandas, PyArrow) for processing HuggingFace Uncopyrighted Pile records into tokenized datasets for LLM pre-training.
*   Implemented automated **PII removal** (emails, phones, SSN, patient IDs), content-hash **deduplication**, and **BPE tokenization** (configurable vocab size, 50K default) to efficiently handle large-scale corpora.
*   Containerized the entire pipeline using **Docker** (multi-stage build, python:3.10-slim) with resource limits for reproducible execution across disparate compute environments.

### Education

**Bachelor of Engineering (B.Eng.), Software Engineering**
University of Western Australia | Perth, WA | Graduated 2004

---
