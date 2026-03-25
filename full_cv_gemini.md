# MIGUEL DE SOUSA
Olinda VIC 3788 | 0497 646 933 | miguel.desousa@protonmail.com

---

### Summary

Highly accomplished Senior Software/DevOps Engineer and Cloud & Security Specialist with over 15 years of comprehensive experience spanning enterprise (NetApp, ANZ Bank), government (Telstra SNE), and critical healthcare (Alfred Hospital ICU) sectors. Proven expertise in architecting, developing, securing, and managing complex, high-availability (24/7/365), and mission-critical systems. Adept at leading CI/CD pipeline implementation for large-scale microservice architectures (100+ services), significantly reducing security risks (achieving zero compliance violations in LEA projects, 95% reduction in billing errors), optimizing cloud expenditure (30% cost reduction), and boosting system performance (40% reduction in edge processing time). Recent work includes architecting AI RAG agents (DeepDivee), refactoring high-performance FastAPI ERP platforms (>100% speedup), and building cloud-native geospatial AI platforms on AWS EKS. Deep proficiency in Kubernetes, multi-cloud environments (AWS, GCP, Azure), security hardening (PII, ISO 27001, Log Masking), infrastructure-as-code (Terraform, CloudFormation, CDK), and data engineering practices. Seeking to leverage extensive technical leadership and hands-on skills in a challenging DevOps, SRE, or Cloud Architect role.

### Technical Skills

*   **DevOps/Cloud Platforms:** OpenShift, Kubernetes (K8s, EKS), ArgoCD, Helm, AWS (EC2, Lambda, API Gateway, DynamoDB, RDS, ECS, S3, Redshift, Athena, Glue, CloudWatch, CloudTrail, CloudFront, Cognito), GCP (GKE, PubSub, BigTable, CloudRun, CloudFunctions), Azure (Cloud Services, Azure SQL, Blob Storage, WAF, SDN), Docker, Serverless Architectures
*   **CI/CD & Automation:** Jenkins, GitLab CI, Bamboo, GitHub Workflows, Ansible, Terraform, CloudFormation, AWS CDK, Puppet, Python scripting, Bash scripting
*   **Programming Languages:** Python (FastAPI, Django, Pydantic V2), Golang (Go), Java (SE 7/8/9/11/17+), Scala, SQL, C++, JavaScript (Node.js, AngularJS)
*   **AI/ML Infrastructure:** RAG Agents (LangChain, HuggingFace), pgvector, sentence-transformers, LLM data pretraining pipelines (BPE tokenization, PII removal, deduplication), S3 Data Lakes for ML
*   **Security:** WSO2 API Management (APIM), APISIX API Gateway, Token Authentication, Log Masking, PII Compliance (ISO 27001), HashiCorp Vault, Network Security (Firewalls, WAF, Security Groups, DMZs, VPNs, SDN), IAM
*   **Data Engineering & MLOps:** Apache Spark, Apache Kafka, Airflow, RabbitMQ, MongoDB, Nifi, Talend, Databricks, Elasticsearch, Logstash, Kibana (ELK), Grafana, Loki, Prometheus, Datadog, HDFS, Zookeeper, PostgreSQL (PostGIS, CloudNativePG), MySQL, Redis
*   **Operating Systems & Networking:** Linux (RHEL, CentOS), Windows Server, Nginx, Squid Proxy, Networking concepts (TCP/IP, UDP, DNS, Load Balancing)
*   **Frameworks & Libraries:** FastAPI, Django, Spring (Java), Chalice (Python), Boto3, Qt/C++, JPA, Cayenne

### GitHub

[https://github.com/miguel-tronix](https://github.com/miguel-tronix)

### Professional Experience

**Senior Software Engineer** | Quantaco | Melbourne, VIC
*October 2025 – March 2026*

*   Refactored a large ERP Microservices FastAPI platform to use Pydantic V2 modelling, consistent exception handling, pagination, unit tests, smoke tests and significant performance speedup of over 100% for large dataset calls - utilizing AsyncIO, Redis and FastAPI best practices.
*   Implemented **Terraform** for GitOps-driven continuous deployment, ensuring automated, reliable application updates across development, staging, and production environments on GCP.
*   Engineered a robust **Redis**-based caching layer and session management system, significantly reducing database load and improving API response times by over 60%.
*   Configured **Google Cloud Platform** services (CloudBuild, CloudRun, CloudFunctions) to support blue/green deployment strategies.
*   Developed and maintained CI/CD pipelines using **GitHub Workflows**, automating testing, security scanning, and deployment processes.

**Architect and CTO** | Azez | Melbourne, VIC
*April 2025 – September 2025*

*   Architected and implemented a AI/ML RAG Agent (DeepDivee) using FastAPI, LangChain, HuggingFace libraries, and other AI tools to provide contra-indication information for drugs/medical interventions based on PubMed article summaries and LLM reasoning.
*   Deployed the DeepDivee Agent in a Kubernetes ecosystem comprising Gitea, ArgoCD, PostgreSQL with pgvector for Vector Search, MinIO, HashiCorp Vault, APISIX API Gateway, and FastAPI microservices.

**DevOps Engineer / Site Reliability Engineer** | Telstra Special Networks Engineering (SNE) | Melbourne, VIC
*October 2022 – April 2025*

*   Built, secured, and maintained robust CI/CD pipelines (Jenkins, GitLab, Bamboo) for over 100 critical Law Enforcement Agency (LEA) microservices (Java, Python, Scala, Go), deploying seamlessly to OpenShift Kubernetes and achieving zero compliance violations.
*   Engineered pipelines incorporating automated testing, security scanning (SAST/DAST), artifact management, and deployment strategies with autoscaling, monitored via Prometheus/Grafana.
*   Significantly enhanced security posture by implementing granular log masking and token-based authentication for WSO2 API Gateway across multiple tenants, ensuring stringent PII protection and LEA compliance.
*   Served as the primary SRE contact for the mission-critical WSO2 APIM platform, managing vendor relations, patching cycles, incident response, and maintaining 99.99% uptime SLA.
*   Optimized national security data processing by deploying low-latency Spark jobs to edge nodes, reducing processing time by 40% compared to centralized cloud clusters.

**Senior Software Engineer** | NetApp | Melbourne, VIC
*January 2020 – May 2022*
*NetApp is a global leader in cloud data services and data management.*

*   Led development on the Keystone NetApp Service Engine, a global cloud/data center storage provisioning and monitoring platform supporting major clients like Mercedes, Aston Martin Racing, Thomson Reuters, and Cisco.
*   Engineered and delivered the Keystone Billing engine (Python, Golang, MongoDB, RabbitMQ), accurately tracking $2M+ annual storage usage and integrating with Zuora, reducing invoice errors by a remarkable 95%.
*   Developed and optimized the Keystone on-demand provisioning system (Python, Ansible, RabbitMQ on Kubernetes), resolving critical concurrency issues for automated ONTAP resource allocation.
*   Implemented the Cisco Athena API ETL project (Golang on Kubernetes), brokering complex billing/financial data between Cisco, NetApp, Zuora, and downstream clients.
*   Strengthened platform security by integrating HashiCorp Vault for secrets management within Kubernetes deployments using Python and Golang service stubs.
*   Technologies: Kubernetes, Ansible, Python, Golang, RabbitMQ, MongoDB, Grafana/Loki, GCP, Azure, AWS, Zuora.

**Data Engineer** | Sportsbet | Melbourne, VIC
*September 2019 – November 2019*
*Sportsbet is a major Australian online wagering provider.*

*   Managed large-scale data lake resources (10TB+ daily processing) on AWS using Nifi, Talend, AWS Glue, Databricks, Redshift, and Athena.
*   Designed and implemented Talend workflows for automated PII sanitization of Zendesk chat logs before Kafka ingestion, ensuring data privacy compliance.
*   Managed cloud infrastructure provisioning and updates using Terraform/CloudFormation scripts.
*   Developed and deployed CI/CD pipelines using Python and Jenkins for data engineering workflows.
*   Configured comprehensive monitoring and alerting using CloudWatch, SumoLogic, PagerDuty, SNS, and ELK.

**DevOps Engineer (Contract via Transpire)** | ANZ Bank | Melbourne, VIC
*May 2019 – August 2019*
*ANZ is one of Australia's largest banking institutions.*

*   Designed and developed the AWS Serverless backend (API Gateway, Lambda, DynamoDB) for ANZ's next-generation EFTPOS payment systems (Ingenico terminals), supporting an initial pilot of 1000+ merchants.
*   Utilized Python with the Chalice framework and Boto3 library for efficient Lambda function development.
*   Managed infrastructure deployment via CloudFormation templates generated using AWS CDK (Python).
*   Implemented robust monitoring and security controls using CloudWatch, CloudTrail, CloudFront, and Cognito.

**DevOps Engineer** | Azez | Melbourne, VIC
*January 2019 – May 2019*

*   Executed a complex lift-and-shift migration of a large on-premise J2EE Spring application (VMWare) to a secure AWS serverless and containerized (ECS) architecture within private/public VPCs.
*   Refactored legacy SOAP-based SOA components into modern RESTful microservices (Java 8+) for the Nutrition module, improving maintainability and performance.
*   Managed AWS infrastructure (Lambda, API Gateway, DynamoDB, RDS, ECS, Route53, EC2) using Terraform and CloudFormation.
*   Configured and hardened Linux environments (RHEL7), Nginx, Tomcat, and Squid proxy servers.

**Big Data DevOps Engineer** | Telstra (CTO/Big Data Analytics) | Melbourne, VIC
*October 2017 – December 2018*
*Telstra is Australia's leading telecommunications company.*

*   Supported data scientists by optimizing Spark cluster job execution (Scala, Python, Java), developing automation scripts (Bash/Python), and scheduling complex DAGs using Airflow.
*   Automated CI/CD pipelines triggering Docker containers for scheduled runs, capturing crucial metadata in Elasticsearch/Kibana for traceability and monitoring.
*   Monitored large-scale cluster performance and capacity using Datadog and Ambari.
*   Stabilized and automated the ingestion of massive LBS data (500Gb+ daily) using Java, NiFi, Kafka, HDFS, and Datadog, eliminating previous data loss issues and ensuring data integrity.
*   Delivered computationally intensive Population-Volume and Origin-Destination models for the Sydney Metro project using Spark, Hadoop (Yarn, HDFS), Kafka, and Zookeeper.
*   Created a Proof-of-Concept (PoC) cluster in GCP (Kubernetes Engine, PubSub, Big Table) evaluating alternatives to the on-prem Hortonworks platform.
*   Technologies: Spark, Hadoop, Yarn, Scala, Python, Java, NiFi, Airflow, Kafka, HDFS, Zookeeper, Docker, Kubernetes, Mesos, AWS Redshift, GCP, Centos, Nginx, Jenkins, GitLab, Ansible, Terraform.

**DevOps Engineer** | Telstra Health | Melbourne, VIC
*February 2016 – September 2017*
*Telstra Health provides eHealth solutions across Australia.*

*   Developed integrated healthcare components using Adobe Experience Manager (AEM), Java RESTful servlets, and Angular UIs, deployed within a secure Azure cloud environment utilizing Software Defined Networks (SDNs) for DMZ implementation.
*   Leveraged Azure cloud services (MongoDB, Azure SQL, Blob storage, WAF, SDN) to deliver a high-availability medical imaging archive solution.
*   Designed and delivered a Security Vulnerability assessment tool integrating the Atlassian stack (Jira, Bamboo) with Splunk for automated ticketing, patch management (via Docker builds), and deployment validation across DEV/UAT environments.
*   Technologies: AEM, Java, Angular, Azure, MongoDB, Azure SQL, Puppet, WAF, SDN, Jira, Bamboo, Splunk, Docker, Linux (RHEL, Centos), Windows, Nginx, Squid, httpd, Tomcat, Jersey.

**Senior Software Engineer** | Genix Ventures | Melbourne, VIC
*November 2015 – February 2016*
*Genix Ventures provides software solutions, including Learning Management Systems.*

*   Developed features for a complex Learning Management System (LMS) targeting professional associations requiring online accreditation modules.
*   Collaborated closely with BA & QA teams, documented detailed test/deployment plans.

**Software Architect/Engineer** | The Alfred Hospital, ICU | Melbourne, VIC
*May 2009 – July 2015*
*The Alfred is one of Australia's busiest and most advanced hospitals and trauma centers.*

*   Led the full lifecycle (design, architecture, development, testing, maintenance) of a mission-critical (24/7/365) Clinical Information System (CIS) for one of Australia's largest Intensive Care Units (ICUs), rivaling commercial offerings like Cerner Millennium.
*   Architected and built a Java SOA-based, secure, high-availability system integrating diverse hospital infrastructure (Patient Admission System, Philips Patient Monitors, Pathology feeds, Billing systems) via HL7 messaging using a custom Mirth (Java HL7 broker) installation and web services (Glassfish, JPA).
*   Created the pioneering "NutritionWeb" application (Java 7, Glassfish 4, JPA, Cayenne, AngularJS, MySQL, PDFBox), the world's first electronic management system for clinical dieticians. This system was instrumental in The Alfred dietician team winning "World Best Nutritional Practices for Critically-Ill Patients" in 2012.
*   Integrated directly with Philips bedside patient monitors (a first in Australia for Philips) to provide real-time and time-lapsed physiological data (Java, Mirth, PostgreSQL, AngularJS, RabbitMQ).
*   Designed and developed the innovative ICU Bed Side Dashboard using Qt/C++ and RabbitMQ, running on thin clients and delivering role-specific information based on smart card authentication (connecting securely to Java backend services).
*   Maintained and planned the redesign of the core ICUActive application for tracking patient procedures and outcomes.
*   Technologies: Java (7), Glassfish (3.2/4), JPA, Cayenne, SQLServer 2008, MySQL, PostgreSQL, RabbitMQ (Java/C++/JS), HL7, Mirth, AngularJS, PDFBox, Qt/C++, Linux (Centos), Windows Server.

**Software Engineer** | ASG Group (Consultant at Royal Perth Hospital) | Perth, WA
*December 2007 – March 2009*
*ASG Group is an IT services provider; Royal Perth Hospital is a major tertiary hospital.*

*   Sole developer for the Burns Management System (BMS) commissioned by Dr. Fiona Wood, gathering requirements, designing, developing (ASP.NET 2.0, C#, SQL Server 2005, Web Services, Ajax/jQuery, XML/XSLT, SOAP), and managing the project using Agile principles and Earned Value Analysis. Implemented performance optimizations using caching and Enterprise Library.
*   Developed key Ethics and Online Import modules for the state-wide Research Management System (RMS), integrating with the PUBMED web service for significant efficiency gains.
*   Resolved a 7-month project stall by developing the critical ActionScript component for an E-Learning FLASH module, successfully delivering online health certification software used by 300-1000+ users daily. Practiced TDD using Nunit/RhinoMocks where feasible.

**Software Engineer** | ITVision | Perth, WA
*August 2007 – December 2007*
*ITVision specializes in software for local government, particularly rural/remote councils.*

*   Developed components for the Nexus SmartClient application using Composite UI Application Block (CAB), Enterprise Library 4, and Spring.NET for dependency injection, focusing on distributed object management via serialization/reflection.
*   Maintained and enhanced an online helpdesk system (ASP, JavaScript).

**Software Developer** | SmartTrack | Perth, WA
*April 2006 – August 2007*
*SmartTrack provides web-based vehicle tracking solutions for large fleets.*

*   Developed an inter-company communication system (SMBSL) using web services to process Biztalk messages between SmartTrack, Bluescope Steel, and Duren Transport regarding logistics status.
*   Dramatically improved website performance by migrating a high-resource ASP sidebar to an efficient Ajax/Web Service solution, reducing data consumption from ~10Mb/hour/client to ~10Mb/day/client and significantly cutting database load via caching.
*   Progressively migrated legacy ASP codebase to ASP.NET C#.

**Micro Electronics Engineering Assistant** | Motium | Perth, WA
*August 2005 – April 2006*
*Motium designs and manufactures rugged computing solutions.*

*   Performed PCB Design using Protel.
*   Developed an internal intranet process management system (PHP/MySQL).
*   Created technical documentation, specifications, and procedure documents. Liaised with international suppliers.

**(Earlier roles as Web Developer/System Administrator available upon request)**

### Education

**Bachelor of Engineering (B.Eng.), Software Engineering**
University of Western Australia | Perth, WA
*Graduated 2004*

**Bachelor of Engineering (B.Eng.), Mechanical Engineering (incomplete)**
University of Western Australia | Perth, WA
*1993 – 1996*

---