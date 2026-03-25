# MIGUEL DE SOUSA
Olinda VIC 3788 | 0497 646 933 | miguel.desousa@protonmail.com

---

## Senior Cloud Native & GitOps Engineer

### Summary

Elite Cloud Native and GitOps Engineer with 15+ years designing, provisioning, and automating highly available cloud architectures. Proven expertise in building enterprise-grade AWS infrastructure using **Terraform** (EKS, RDS, S3 Data Lakes, VPC network isolation), orchestrating complex multi-service deployments via **Ansible** and **ArgoCD** GitOps workflows to Kubernetes clusters. Track record of deploying stateful workloads including high-availability PostgreSQL clusters using the **CloudNativePG** operator with automatic failover, configuring **Redis** clusters for high-performance caching, and managing **APISIX** API Gateways with token-based authentication. Demonstrated ability to handle cross-cloud secrets management, dynamically injecting GCP credentials into Kubernetes Secrets via HashiCorp Vault. Extensive experience maintaining 99.99% uptime SLA for mission-critical Law Enforcement systems. Seeking a senior Cloud Native/GitOps role to drive infrastructure excellence.

### Technical Skills

*   **Infrastructure as Code:** Terraform (AWS provider 5.x, modules: EKS, VPC, RDS, S3), AWS CDK, CloudFormation, Ansible (kubernetes.core collection), Puppet
*   **GitOps & Orchestration:** ArgoCD (Helm chart 7.7.0, automated sync with prune/selfHeal), Kubernetes (EKS 1.29, OpenShift), Docker, Helm
*   **Cloud Platforms:** AWS (EKS, RDS PostgreSQL 16.1, S3 Data Lakes, Lambda, API Gateway, VPC with public/private subnets), GCP (GKE, CloudRun, CloudFunctions, CloudBuild), Azure
*   **Stateful Workloads:** CloudNativePG operator (PostgreSQL HA clusters), Redis 7 (StatefulSet with LRU eviction, PVC storage), MongoDB
*   **API Management:** APISIX API Gateway (Helm chart 2.10.0), WSO2 APIM, NGINX Ingress Controller, token-based authentication
*   **CI/CD & Automation:** Jenkins, GitLab CI, Bamboo, GitHub Workflows, ArgoCD, Bash/Python scripting
*   **Security & Observability:** HashiCorp Vault (cross-cloud secrets injection), PII/ISO 27001 compliance, Prometheus, Grafana, ELK, Datadog

### GitHub

[https://github.com/miguel-tronix](https://github.com/miguel-tronix)

### Professional Experience

**Senior Software Engineer** | Quantaco | Melbourne, VIC
*October 2025 – March 2026*

*   Implemented **Terraform** for GitOps-driven continuous deployment, provisioning and managing GCP infrastructure (CloudBuild, CloudRun, CloudFunctions) ensuring automated, reliable application updates across dev, staging, and production environments.
*   Engineered **Ansible** playbooks for declarative Kubernetes resource management, deploying FastAPI microservices with PVC-backed storage, GCP credential secrets, and NGINX Ingress configuration.
*   Configured **Redis** StatefulSets with LRU eviction policies and persistent volume claims for high-performance session caching, reducing API response times by over 60%.
*   Developed and maintained CI/CD pipelines using **GitHub Workflows**, automating testing, security scanning, and deployment to Kubernetes clusters.

**Architect and CTO** | Azez | Melbourne, VIC
*April 2025 – September 2025*

*   Architected and deployed a RAG Agent (DeepDivee) into a full **Kubernetes GitOps ecosystem** comprising Gitea, **ArgoCD** (automated sync with prune and self-heal), PostgreSQL with pgvector, MinIO, **HashiCorp Vault**, and **APISIX API Gateway**.
*   Managed **cross-cloud secrets** by dynamically injecting GCP credentials into Kubernetes Secrets, enabling secure multi-cloud service integration.

**DevOps Engineer / Site Reliability Engineer** | Telstra Special Networks Engineering (SNE) | Melbourne, VIC
*October 2022 – April 2025*

*   Provisioned highly-available AWS infrastructure using **Terraform**, including EKS clusters, RDS PostgreSQL instances with automated backups and multi-AZ failover, S3 Data Lakes with versioning and AES256 encryption, and VPC network isolation with private subnets and security groups.
*   Orchestrated automated deployments of 100+ microservices (Java, Python, Scala, Go) to **OpenShift Kubernetes** using **Ansible** playbooks and **ArgoCD** GitOps workflows, achieving zero compliance violations.
*   Deployed stateful workloads using **CloudNativePG** operator for high-availability PostgreSQL clusters (2+ instances, 15Gi storage), ensuring zero data loss and automatic failover.
*   Configured and managed **Redis** clusters (Redis 7-alpine, StatefulSet with PVC) for session caching and high-throughput data processing, optimizing application performance.
*   Implemented granular security controls including cross-cloud secrets management, dynamically injecting GCP credentials into Kubernetes Secrets via **HashiCorp Vault**.
*   Configured **APISIX** and **WSO2 API Gateways** with token-based authentication and log masking for multi-tenant LEA systems, achieving zero compliance violations.
*   Deployed **ArgoCD** via Helm (chart 7.7.0) with NGINX Ingress, automated sync policies, and server-side apply for declarative GitOps management.
*   Maintained 99.99% uptime SLA for mission-critical API platforms through proactive monitoring (Prometheus/Grafana) and rapid incident response.

**Staff Engineer** | NetApp | Melbourne, VIC
*January 2020 – May 2022*

*   Designed and provisioned multi-cloud infrastructure using **Terraform** and **Ansible** for the Keystone Service Engine, supporting global storage provisioning across AWS, GCP, and Azure.
*   Built automated resource allocation system on Kubernetes resolving critical concurrency issues for ONTAP storage allocation using Python and RabbitMQ.
*   Integrated **HashiCorp Vault** for secrets management across Kubernetes deployments, implementing dynamic secret injection for service-to-service authentication.
*   Engineered the Keystone Billing engine processing $2M+ annual usage with 95% invoice error reduction.

**Big Data DevOps Engineer** | Telstra (CTO/Big Data Analytics) | Melbourne, VIC
*October 2017 – December 2018*

*   Provisioned and managed Spark clusters using **Terraform** and **Ansible**, enabling data scientists to process 500Gb+ daily LBS data across on-prem and cloud environments.
*   Automated CI/CD pipelines triggering Docker containers for scheduled data processing runs, capturing metadata in Elasticsearch/Kibana for observability.
*   Built GCP PoC environment (GKE, PubSub, BigTable) evaluating cloud-native data platform alternatives to on-prem Hortonworks.

**DevOps Engineer** | Telstra Health | Melbourne, VIC
*February 2016 – September 2017*

*   Deployed integrated healthcare components within a secure **Azure** cloud environment, utilizing Software Defined Networks (SDNs) for DMZ implementation.
*   Automated infrastructure and configuration management using **Puppet**, ensuring consistent and repeatable deployments across Azure environments.
*   Designed and delivered a Security Vulnerability assessment tool integrating Atlassian (Jira, Bamboo) with Splunk for automated ticketing and patch management via Docker builds.

### Recent Infrastructure Projects

**Traific Geospatial AI Platform** (AWS)
*   Architected reproducible AWS environment using **Terraform** (VPC, EKS 1.29, RDS PostgreSQL 16.1 with PostGIS, S3 Data Lake) with secure public/private subnet isolation across 3 AZs.
*   Configured EKS with two managed node groups: `stateless` (Spot instances, 2-8 nodes auto-scaling) and `redis` (On-Demand, dedicated with taints for workload isolation).
*   Provisioned RDS with gp3 storage, multi-AZ failover, Performance Insights, and automated PostGIS extension enablement.

**Kubernetes GitOps Stack** (On-prem/Cloud)
*   Deployed complete GitOps platform via **Ansible** and **ArgoCD**: CloudNativePG PostgreSQL clusters, Redis StatefulSets, APISIX API Gateway, Gitea, Kubernetes Dashboard — all with automated sync and self-healing.
*   Managed cross-cloud secrets by dynamically injecting GCP application default credentials into Kubernetes Secrets for secure multi-cloud microservice operation.

### Education

**Bachelor of Engineering (B.Eng.), Software Engineering**
University of Western Australia | Perth, WA | Graduated 2004

---
