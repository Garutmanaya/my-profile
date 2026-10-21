# Professional Engineering Profile
**AI & Agentic AI Engineering · Forward Deployed Engineering · Enterprise Architecture**

> **Name, contact information, professional links, and current title:** To be updated before publication.

## Professional Summary
Hands-on engineer and architect with more than 25 years of experience spanning applied AI and machine learning, enterprise security, distributed systems, data platforms, cloud-native infrastructure, and low-level systems engineering. Recent projects include AgentNebula, an independent enterprise agent infrastructure and security platform, and EPP SLA analytics using natural-language-to-SQL, XGBoost anomaly detection, and automated reporting.

Experienced in moving across unfamiliar technical domains: from cryptographic hardware interfaces, Linux kernel modules, network protocols, and embedded appliances to enterprise Java services, large-scale analytics, Kubernetes operations, and modern agentic AI. Strong emphasis on evaluating existing standards and open-source technologies, rapid prototyping, designing practical architectures, and implementing working systems end to end.

**Target roles:** Forward Deployed Engineer (AI) · Principal AI Engineer · Agentic AI Platform Engineer · Enterprise / Solutions Architect

## Technical Expertise
**Agentic AI and agent interoperability:** Agent-to-Agent (A2A) protocol, Agent Cards, agent discovery and registration, multi-agent orchestration, agent security, A2UI, authorization policy integration, and Model Context Protocol (MCP) concepts. AgentNebula implementation details are documented in the project section.

**Applied AI and data science:** Neural networks, transformers, PyTorch, Keras, TensorFlow, XGBoost, anomaly detection, natural-language-to-SQL, data analysis, and model evaluation. Hands-on project evidence currently includes EPP SLA Text-to-SQL and XGBoost anomaly detection; other frameworks include studied and practiced technologies whose project-level usage will be refined.

**MLOps and cloud native:** MLflow, Kubeflow, Kubernetes administration and deployments, CloudNativePG, PostgreSQL, Linux system administration, and deployment automation. Production scope and project-specific responsibilities to be confirmed.

**Enterprise security and identity:** OAuth 2.0, JWT, DPoP, AuthZEN, OPA/Rego, public-key infrastructure, certificate authorities, X.509, TLS/mTLS, PKCS standards, IPsec/IKE, smart-card middleware, and PKCS#11.

**Software engineering and data platforms:** Python, Java, C/C++, SQL, shell scripting, REST services, Linux internals, multithreading, networking, distributed systems, Apache Hadoop, Hive, MapReduce, Sqoop, Flume, Cassandra, MySQL, PostgreSQL, GWT, and enterprise application servers.

## Featured Project — AgentNebula
**Independent engineering project · Latest project · Dates to be confirmed**

AgentNebula is an enterprise agent infrastructure and security platform designed around interoperable agent protocols, discoverability, identity, authorization, trust, and developer tooling. The project demonstrates integration of established security standards with emerging agent architectures rather than replacing mature protocol implementations.

- Designed a modular Registry & Security control plane with publisher/provider/agent ownership, registration, discovery, lifecycle, credentials and trust.
- Developed standalone OAuth and AuthZEN policy services with OPA/Rego integration; composed OAuth, JWT, DPoP, PKI and authorization boundaries.
- Integrated the official A2A Python SDK into reusable Platform and SecureAgent developer layers, including skill dispatch and A2UI presentation.
- Built capability exploration, orchestration, playground tooling and multi-agent inventory-replenishment reference workflows.
- Separated responsibilities across core control-plane services, plugins, OAuth authorization server, AuthZEN policy server, developer SDK, A2A platform integration, SecureAgent interface, explorer, playground, and reference solutions.
- Designed around official A2A SDK integration; MCP transport support is a future direction and is not presented as implemented.

**Technical focus:** Python · A2A · A2UI · OAuth 2.0 · AuthZEN · OPA/Rego · PKI · agent lifecycle · agent discovery · secure invocation

**Detailed architecture and component documentation:** [AgentNebula documentation](https://docs.agentnebula.ai) (publication status to be confirmed).

## Recent AI and Infrastructure Work — Verisign
**Current employer · Project dates, current designation, and production details to be confirmed**

### EPP SLA Text-to-SQL
Natural-language interface for querying EPP SLA data using model-assisted SQL generation.
- Developed a model-based natural-language-to-SQL workflow for SLA analytics.
- Implementation architecture, evaluation methodology, guardrails, data sources and measured outcomes to be confirmed.

### EPP SLA Anomaly Detection
XGBoost-based anomaly detection for EPP SLA metrics.
- Developed an XGBoost-based model to identify anomalies in SLA-related data.
- Feature engineering, labels, model metrics, monitoring and deployment details to be confirmed.

### EPP SLA Reporter
Automated EPP SLA reporting and analysis.
- Developed reporting capabilities for EPP SLA analysis.
- Report workflow, automation details, consumers and impact to be confirmed.

### Kubernetes & CloudNativePG
Kubernetes administration, application deployments and CloudNativePG on Kubernetes.
- Hands-on Kubernetes administration and application deployment.
- Worked with CloudNativePG to operate PostgreSQL on Kubernetes.
- Specific production topology, HA strategy, backup/recovery and operational outcomes to be confirmed.

## Professional Experience
### Verisign
**Engineer III (historical title; current title to confirm) · Nov 2011 – Present (continuity to confirm)**
Registry engineering, performance/scalability testing, analytics, automation, and recent AI/ML initiatives.

#### EPP SLA Text-to-SQL, Anomaly Detection & Reporter
- Developed natural-language-to-SQL capabilities for EPP SLA analytics.
- Developed an XGBoost-based anomaly detection model for SLA metrics.
- Developed an EPP SLA reporting solution. Detailed implementation and results to be added.

#### Domain History Migration
- Automated migration of historical domain transaction data from Oracle toward Cassandra-backed reporting.
- Used Sqoop and partitioned/bucketed Hive schemas to support reporting views.

#### P&S Hadoop Cluster
- Installed and managed a five-node Hadoop test cluster with 60 mapper and 60 reducer capacity, as documented in the original resume.
- Built ingestion workflows with Flume and scripts, Java MapReduce jobs, Hive queries/UDFs, and Sqoop export to MySQL.
- Evaluated business-intelligence tools and built Pentaho reporting views for registry and performance trends.

**Additional implementation detail:** Built a five-node Hadoop environment to study production logs and load-test behavior. Automated real-time ingestion with Flume and offline ingestion with scripts; generated response-time, registrar, domain-name and TLD trend reports using MapReduce, Hive, and custom UDFs. Used Sqoop for export to MySQL and Pentaho BI for report presentation.

#### P&S Unified Testing Framework (PSUTF)
- Designed and implemented a pluggable load-generation framework for registry products.
- Used Spring/Spring Expression Language, JSON and REST for dynamic command/data configuration.
- Built a GWT web console, service packaging, RPM build tooling, and Rundeck-based workflow automation.

### Smith Micro Software
**Senior Software Engineer · Jul 2006 – Sep 2011**
CTO-team technology evaluation, secure device infrastructure, highly available services and mobile VPN systems.

**Additional implementation detail:** Created a central configuration manager and extensible command/data models using Spring and Spring Expression Language. Supported load testing of registry products through manager, agent and console services. Built a GWT monitoring console, Ant build scripts, RPM packaging, and Rundeck workflows for installation, configuration and maintenance.

#### SODA — Secure On-Device API / SODA-CA
- Built a GWT/mvp4g management dashboard and TLS mutual-authentication integration.
- Designed certificate issuance flows using PKCS#8, PKCS#10, PKCS#12 and X.509v3; integrated EJBCA and evaluated Entrust/OpenCA.
- Implemented secure access to device certificate material stored in Cassandra.

**Additional implementation detail:** Evaluated Entrust Security Manager and Java Security Toolkit APIs; investigated OpenCA and EJBCA; adapted EJBCA to support private certificate extensions. Certificate issuance work included key generation, PKCS#8 private-key storage, PKCS#10 requests, X.509v3 issuance, and PKCS#12 packaging. The device-management web layer used REST, GWT and mvp4g.

#### Mercury — Shared Server Platform
- Contributed to layered multi-application server architecture and Cassandra/memcachedb data access.
- Implemented role-based access control and Linux hardening with iptables and SELinux roles.
- Performed load testing, JVM/application profiling and performance tuning.

**Additional implementation detail:** Evaluated a multi-application layered server architecture; built database access for Cassandra and memcachedb, GWT interfaces, role-based authorization, and security policies using iptables and SELinux. Established load-testing environments with JMeter and Grinder; profiled bottlenecks with JProfiler and tuned Linux, JVM, and application-server parameters.

#### Cygnus — Cloud File Delivery
- Implemented JNI integration for proprietary compression/encryption routines and Cassandra data access.
- Evaluated load-balancing/proxy solutions and configured Linux Virtual Server; original resume records testing up to 4 Gbps across eight nodes.
- Worked on REST-based file-upload interfaces.

**Additional implementation detail:** Worked on secure delivery of large files through REST APIs and encrypted storage paths. Evaluated Linux Virtual Server, Squid, Varnish, and other load-balancing/proxy technologies; configured VLANs, network bonding, and jumbo frames in a multi-node load test environment.

#### QuickLink VPN Gateway
- Developed accounting/reporting using MySQL, Netfilter/iptables traffic collection and a PHP administration UI.
- Implemented PostgreSQL replication for mobility-manager state and improved failover behavior.
- Built Linux VPN clients, custom Linux appliance images and a VPN client simulator supporting up to 5,000 clients.
- Worked on MobileIP, IKEv2, TLS, RADIUS, LDAP, Active Directory and platform ports.

### Verizon Data Services
**Software Analyst · Oct 2004 – Jul 2006**
Enterprise telecom provisioning and reporting applications.

**Additional implementation detail:** Developed VPN gateway accounting for session duration, bandwidth, and access type; Linux kernel traffic instrumentation using Netfilter hooks; PostgreSQL replication of mobility-manager information; customized Linux boot images and administrative UI for appliances. Worked on client and gateway capabilities spanning MobileIP, IPsec/IKE, TLS, Active Directory, OpenLDAP, RADIUS, RSA SecurID, and platform ports to Windows Mobile, Windows XP, and Nokia IPSO.

#### RequestNet
- Maintained and enhanced reporting, critical-date calculation and QueryNet modules for high-capacity service pre-provisioning.
- Worked with C++, Java, SQL/PLSQL, Oracle and enterprise web technologies.

### ActivCard
**Senior Software Engineer · Jan 2003 – Jun 2004**
Cross-platform smart-card middleware and authentication.

#### Smart Card Application Suite
- Implemented ISO-7816 APDU middleware interfaces and PKCS#11 cryptographic operations.
- Integrated smart-card login into Linux PAM with PKI, Kerberos and Active Directory.
- Developed Oracle-backed card-lifecycle APIs and PKCS#11/MS-CSP test tools; investigated EMV authentication.

### Ericsson
**Senior Software Engineer · Aug 2000 – Jan 2003**
Carrier-grade router software and network security.

**Additional implementation detail:** Developed middleware for Linux, Solaris, and macOS with ISO-7816 APDU handling and PKCS#11 cryptographic services for signing, encrypted email, secure browsing, and certificate import/download. Integrated PAM authentication using local PKI credentials, Kerberos, and Active Directory. Supported smart-card issuance lifecycle through Oracle-backed services.

#### Tigris Multi-Service Access Platform
- Integrated an IKE stack into Ericsson router products.
- Contributed to IPsec hardware acceleration using ADSP-2141, including driver interfaces and security-association management.
- Implemented dynamic IPsec/IKE policies for L2TP protection under RFC 3193; investigated SCEP/OCSP.

### Bharat Electronics (BEL), Central Research Laboratory
**Member, Research Staff — Crypto Group · Jun 1999 – Aug 2000**
Applied cryptography, Linux drivers and embedded interfaces.

**Additional implementation detail:** Contributed to IKE stack integration and IPsec offload work on ADSP-2141 hardware, including driver-facing interfaces and security-association database handling. Implemented IPsec/IKE policy support for L2TP protection with floating LNS addresses and ports, and researched SCEP and OCSP.

#### Frame Relay Encryptor / Decryptor (FRED)
- Contributed to Linux cryptographic driver development for MOXA C101 hardware.

#### GPS Vehicle Tracking
- Implemented GPS receiver frame parsing and validation for vehicle location tracking.

#### Public-Key Encryption Research
- Completed a thesis on secure network communication using public-key encryption and implemented RSA/Twofish-based research software.

## Education
**Master of Technology (M.Tech.), Computer Science & Engineering** — Regional Engineering College, Warangal, India.

## Certifications and Professional Development
- Cloudera Certified Developer for Apache Hadoop (historical certification listed in the original resume; current validity not verified).
- Continued study and hands-on exploration of data science, neural networks, transformers, PyTorch, TensorFlow, Keras, MLflow, Kubeflow, and modern agent frameworks.

---

*Content note: Historical employment and project details are adapted from an older five-page resume. Recent project descriptions are based on the information provided during this review. Current title, dates, impact metrics, deployment scope, and public-disclosure approval should be verified before publishing.*
