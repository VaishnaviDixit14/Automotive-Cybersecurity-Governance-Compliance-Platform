# Automotive-Cybersecurity-Governance-Compliance-Platform

An enterprise-inspired cybersecurity governance platform for modern automotive software ecosystems.

Meridian is a full-stack project that demonstrates how OEMs can manage cybersecurity compliance, supplier risk, firmware provenance, software updates, and vulnerability traceability throughout a vehicle's lifecycle. The platform is designed around industry standards such as **ISO/SAE 21434**, **UN R155**, and **UN R156**, providing a centralized view of cybersecurity evidence and compliance readiness.

> **Status:** Prototype with production-oriented architecture. Current release showcases an interactive governance dashboard while the backend services are being implemented.

---

## Overview

Modern vehicles contain hundreds of Electronic Control Units (ECUs), thousands of software components, and a complex supplier ecosystem. Tracking firmware versions, cybersecurity risks, and regulatory compliance across this landscape is difficult when information is scattered across spreadsheets and disconnected tools.

Meridian aims to provide a unified platform that enables cybersecurity engineers, compliance teams, and suppliers to:

* Monitor fleet-wide cybersecurity posture
* Track firmware provenance and software integrity
* Manage supplier cybersecurity risks
* Visualize end-to-end traceability
* Assess compliance against automotive cybersecurity standards
* Organize audit evidence
* Review technical documentation using AI-assisted compliance analysis

---

## Key Features

### Fleet & ECU Inventory

* Vehicle inventory management
* ECU tracking
* Firmware version management
* Deployment status monitoring

### Supplier Governance

* Supplier risk scoring
* Certification management
* Audit history
* Incident response SLA tracking

### Firmware Provenance

* Firmware version history
* Cryptographic hash verification
* Digital signature validation
* Deployment records

### End-to-End Traceability

Visualize relationships between:

```
Supplier
    ↓
Component
    ↓
Firmware
    ↓
SBOM
    ↓
Vulnerability
    ↓
Software Update
    ↓
Vehicle
```

### Vulnerability Management

* CVE tracking
* Severity classification
* Investigation workflow
* Remediation status
* SLA monitoring

### Compliance Dashboard

Coverage for:

* ISO/SAE 21434
* UN R155
* UN R156

including compliance readiness and evidence mapping.

### Audit Evidence Repository

Manage:

* Threat assessments
* Penetration testing reports
* SBOMs
* Incident reports
* Compliance documentation

### AI Compliance Assistant

An AI-powered document review module designed to analyze uploaded technical documentation and identify missing compliance evidence against automotive cybersecurity standards.

---

## Technology Stack

### Current Prototype

* HTML5
* CSS3
* Vanilla JavaScript

---

### Planned Production Stack

Frontend

* React
* TypeScript

Backend

* FastAPI
* Python

Database

* PostgreSQL

Graph Database

* Neo4j

AI

* LangChain
* Large Language Model integration

Infrastructure

* Docker
* Docker Compose

Authentication

* JWT
* OAuth2

Deployment

* Vercel
* Railway / Render

---

## Architecture

```
                   User
                     │
                     ▼
            React Frontend
                     │
          REST / WebSocket API
                     │
         ┌───────────┴───────────┐
         │                       │
         ▼                       ▼
    FastAPI Backend         AI Assistant
         │                       │
         ▼                       ▼
 PostgreSQL               LLM Pipeline
         │
         ▼
      Neo4j Graph
```

---

## Screens

* Dashboard Overview
* Fleet & ECU Inventory
* Supplier Management
* Firmware Provenance
* Traceability Graph
* Vulnerability Management
* Compliance Dashboard
* Audit Evidence Repository
* Knowledge Graph
* AI Compliance Assistant
* Quantum Anomaly Detection (Research Prototype)

---

## Project Structure

```
Meridian/
│
├── index.html
├── README.md
├── assets/
├── backend/                 (planned)
│
├── api/                     (planned)
│
├── database/                (planned)
│
└── docs/
```

---


## Roadmap

### Phase 1

* FastAPI backend
* PostgreSQL integration
* CRUD APIs
* Authentication

### Phase 2

* Neo4j knowledge graph
* Dynamic traceability
* REST APIs

### Phase 3

* AI compliance assistant
* Document upload
* Automated compliance analysis

### Phase 4

* Role-based access control
* Audit logging
* Docker deployment
* CI/CD pipeline

### Phase 5

* Quantum anomaly detection integration
* Real telemetry analysis
* Advanced analytics

---

## Future Improvements

* Live OTA telemetry
* Multi-tenant architecture
* Real-time notifications
* Supplier portal
* Interactive dashboards
* SIEM integration
* Digital twin visualization
* Security analytics
* API documentation
* Automated testing
* Kubernetes deployment

---

## Learning Outcomes

This project explores practical concepts used in enterprise automotive cybersecurity systems, including:

* Secure software lifecycle management
* Firmware provenance
* Supply chain cybersecurity
* Vulnerability management
* Compliance engineering
* Graph databases
* AI-assisted document analysis
* Secure backend architecture
* Modern full-stack application design

---

## Disclaimer

Meridian is an educational and portfolio project created to demonstrate software engineering concepts in automotive cybersecurity governance.

The current release contains a fully interactive frontend prototype with representative datasets. Backend services, AI workflows, and graph database integrations are being implemented as part of the project's planned evolution.

---

## Author

**Vaishnavi Dixit**

Computer Science Engineering Student

Interested in:

* Cybersecurity
* Automotive Security
* Artificial Intelligence
* Distributed Systems
* Quantum Machine Learning

---

## License

This project is released under the University of Manchester License.
