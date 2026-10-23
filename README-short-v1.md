# Sridhar Samineni

**Software Engineer | Systems Architecture | Security | Cloud-Native Infrastructure | Applied AI**  
**Location:** [To add] · **Email:** [To add] · **Phone:** [To add]  
**LinkedIn:** [To add] · **GitHub:** [To add] · **AgentNebula:** https://agentnebula.ai

## Professional Summary

Software engineer with **25+ years of experience** designing and implementing systems software, network security, enterprise applications, distributed data platforms, performance-engineering tools, and cloud-native infrastructure. Experience spans Linux kernel and networking, IPsec/IKE, PKI, Java and Python applications, large-scale SLA analytics, Kubernetes, and applied AI. Strong background in **end-to-end technical product ownership**—requirements, architecture, implementation, deployment, operational support, and continuous enhancement. Recent independent work focuses on AI-agent interoperability, security, natural-language-to-SQL, and machine-learning-based anomaly detection.

## Core Technical Skills

- **Architecture and development:** Python, Java, C/C++, SQL, Bash, REST/JSON, Spring, modular systems, extensible frameworks, API integration.
- **Security and networking:** OAuth 2.0, JWT/JOSE, PKI, X.509, TLS/mTLS, IPsec/IKE, PKCS#11, smart cards, Linux networking, authentication and authorization.
- **Cloud and infrastructure:** Kubernetes, Helm, CloudNativePG, OpenStack, Terraform, Ansible, Docker, Linux, AWS services, deployment automation.
- **Data engineering and databases:** PostgreSQL, MySQL, Oracle, Cassandra, Hadoop/HDFS, Hive/UDFs, Sqoop, Flume, ETL, OpenStack Swift, Grafana.
- **AI/ML and agents:** A2A, A2UI, OPA/Rego, AuthZEN, Hugging Face Transformers, FLAN-T5, PEFT/LoRA, PyTorch, XGBoost, Isolation Forest, MLflow, FastAPI, Streamlit.
- **Performance engineering:** EPP registry SLA analytics, production traffic analysis, workload modeling, distributed load generation, performance/scalability testing, latency histograms, release regression analysis.

## Independent Engineering and Applied AI Projects

### AgentNebula — Enterprise AI Agent Hub and Security Platform
**Website:** https://agentnebula.ai · **Documentation:** https://docs.agentnebula.ai

Independently architected and developed a modular platform for **AI-agent registration, discovery, lifecycle management, identity, OAuth security, PKI, and policy-based authorization**. Integrated the **official A2A Python SDK**, built reusable developer-facing Python packages, and implemented centralized authorization using **AuthZEN, Open Policy Agent (OPA), and Rego**. Developed an **A2UI Rich Catalog** package and agent integration examples. Emphasis on standards-based interoperability, modularity, and reuse of established open-source components. **MCP-related policy integration remains an investigation area.**

**Published components:** `agent-nebula-sdk`, `agent-nebula-platform`, `agent-nebula-secureagent`, `agent-nebula-secureagent-examples` (PyPI/GitHub), and `@agent-nebula-npm/a2ui-rich` (npm).

### EPP SLA — Natural Language to SQL Model Training

Built a schema-aware Text-to-SQL pipeline with synthetic question/SQL generation, data augmentation, **FLAN-T5 fine-tuning using Hugging Face Transformers and PEFT/LoRA**, and model inference testing. Included optional S3 artifact synchronization and SageMaker deployment definitions.

### EPP SLA — AI Business Intelligence Agent

Developed a **Streamlit** analytics application that converts natural-language questions about EPP SLA data into SQL using configurable model backends, executes queries, and presents tables and interactive visualizations.

### EPP SLA — Machine Learning Anomaly Detection

Developed hourly SLA anomaly-detection approaches using **XGBoost regression residuals** and **Isolation Forest**, with feature engineering, threshold calibration, **MLflow** experiment tracking, **FastAPI** inference, and Streamlit visualization. Included AWS deployment configurations.

## Professional Experience

### Verisign, Inc. — Engineer IV
**Reston, Virginia | November 2011 – October 2025**

Held end-to-end technical responsibility for registry **production SLA analytics, performance-testing reporting, and load-generation products**, including requirements analysis, architecture, implementation, data engineering, deployment automation, maintenance, enhancements, and documentation. Analyzed EPP traffic and abnormal registrar behavior; correlated **gateway, application, database, and network** measurements to investigate SLA degradation. Designed production-informed workloads for testing registry services across TLDs including **.com, .net, .cc, and .tv**.

**Selected products and contributions**

- **Sirius — Production SLA reporting:** Developed and maintained reporting and dashboards covering approximately **15 years of registry SLA history**, with analysis by registrar, TLD, IP version, gateway type, EPP command, and release. Automated daily SLA processing and hourly database-metrics ingestion to support deviation analysis and troubleshooting.
- **PSTools — Performance-testing analytics portal:** Built consolidated Grafana reporting for test SLA and load metrics, database performance, EPP command latency histograms, release comparisons, bottlenecks, and system breaking points. Reused the production reporting framework with test-specific analytics.
- **Shared reporting architecture:** Designed an extensible **Hive reporting framework** in which new report categories are added through independent query directories. Automated processing in Hadoop, distribution through **OpenStack Swift**, report detection/validation, and loading into **PostgreSQL**. Designed standardized table conventions with **product-specific PostgreSQL schemas**.
- **PSUTF — Unified Testing Framework:** Designed and implemented a configurable, extensible **Java/Spring** load-generation framework for registry performance and scalability testing. Built REST/JSON configuration services, a GWT monitoring interface, reusable test scenarios, and operational automation.
- **Infrastructure modernization:** Supported migrations from **virtual machines → OpenStack → Verisign Kubernetes Services**, implementing **Terraform, Ansible, Kubernetes manifests, and Helm charts**. Migrated an approximately **800 GB MySQL database to PostgreSQL**, then transitioned deployment to **CloudNativePG**. Initially administered a dedicated Hadoop reporting cluster before moving computation to the shared **VSCC** environment.
- **Domain-history analytics:** Supported **Oracle-to-Cassandra** migration using Sqoop and Hive-based reporting structures.

**Technologies:** Java, Python, Linux, SQL, Hadoop, Hive/UDFs, PostgreSQL, MySQL, CloudNativePG, Cassandra, OpenStack Swift, Grafana, Kubernetes, Helm, Terraform, Ansible, Spring, GWT, REST/JSON, EPP.

### Smith Micro Software, Inc. — Senior Software Engineer
**Herndon, Virginia | July 2006 – September 2011**

Designed and developed secure mobile-device services, scalable server components, PKI integrations, and mobile VPN gateway capabilities.

- **SODA:** Implemented certificate-authority integration using **EJBCA**, X.509 issuance workflows, PKCS#8/#10/#12 handling, TLS mutual authentication, and GWT-based device-management interfaces.
- **Mercury:** Developed Cassandra/memcachedb data-access components, RBAC and host-security integrations; conducted load testing and JVM/Linux tuning.
- **Cygnus:** Implemented JNI bindings for encryption/compression libraries and Cassandra-based data access; tested Linux Virtual Server infrastructure at **up to 4 Gbps across eight nodes**.
- **QuickLink Mobile VPN Gateway:** Developed Linux VPN client and kernel traffic logging, MobileIP/IPsec integrations, accounting and reporting, appliance software, authentication integration, and a simulator supporting **up to 5,000 clients**.

**Technologies:** C/C++, Java, Linux, JNI, GWT, Cassandra, PostgreSQL, MySQL, EJBCA, OpenSSL, PKI, IPsec/IKE, MobileIP, Netfilter, REST, JMeter, Grinder.

### Verizon Data Services Technology Centre — Software Analyst
**Tampa, Florida | October 2004 – July 2006**

Developed and enhanced **RequestNet** enterprise telecommunications service-request software, including reporting modules, critical-date calculations, and QueryNet functionality. **Technologies:** C++, Java, Oracle, SQL/PLSQL, JSP, JavaScript, Perl.

### ActivCard Software Private Limited — Senior Software Engineer
**Hyderabad, India | January 2003 – June 2004**

Developed cross-platform smart-card security middleware and applications for Linux, Solaris, and Mac OS X. Implemented **ISO 7816 APDU**, **PKCS#11**, X.509 certificate operations, and authentication integration with **PAM, Kerberos, and Active Directory**.

### Ericsson India Private Limited — Senior Software Engineer
**Hyderabad, India | August 2000 – January 2003**

Enhanced **Tigris multiservice routers**, integrating an IKE stack, contributing to **IPsec hardware acceleration**, security-association management, and L2TP-over-IPsec support (**RFC 3193**).

### Bharat Electronics Limited — Member (Research Staff), Crypto Group
**Bangalore, India | June 1999 – August 2000**

Developed Linux cryptographic-driver components for a Frame Relay encryptor/decryptor and a GPS receiver interface for vehicle tracking.

## Education

**Master of Technology (M.Tech.), Computer Science & Engineering** — Regional Engineering College, Warangal  
**Master's Thesis:** Public Key Encryption Systems, Advanced Numerical Research and Analysis Group (ANURAG), Hyderabad
