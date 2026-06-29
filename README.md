# Mohamed Fateen — Backend & Systems Engineering

I design and build **invariant-driven backend systems** with a focus on real-time communication, AI-governed workflows, deployment diagnostics, evaluation pipelines, and secure stateful applications.

My work centers on problems most beginner projects avoid:

* enforcing correctness under non-deterministic AI output
* designing strict domain models and validators
* building adaptive state machines instead of simple CRUD applications
* governing progression, failure, recovery, and remediation
* diagnosing deployment failures using logs and configuration evidence
* designing secure multi-device systems with real-time synchronization

---

## 🚩 Flagship Systems

### SkillForgeAI — Invariant-Driven Adaptive Learning System

A full-stack learning control system that models evolving skill states, generates constrained roadmaps, and orchestrates AI-evaluated tasks while preserving roadmap, phase, and skill-vector integrity.

**Core engineering themes**

* Roadmap state engine and lifecycle governance
* Unified AI evaluation pipeline with contract-enforced outputs
* Skill delta engine with bounded updates
* Strict domain validator layer
* Failure-first system design
* AI-governed progression and remediation

👉 Pinned repository: **SkillForgeAI**

---

### DeployForge — AI-Assisted Deployment Diagnosis System

A full-stack deployment debugging system that analyzes failing deployment logs and configuration files to identify root causes and generate evidence-backed remediation steps.

DeployForge models a strict hierarchy of users, projects, deployment services, and diagnosis records. It combines a Spring Boot application backend with a separate FastAPI AI service for structured deployment analysis.

**Core engineering themes**

* Multi-project and deployment-service domain modeling
* Multipart log and configuration-file ingestion
* Spring Boot to FastAPI service communication
* Structured AI diagnosis with validated outputs
* Evidence-backed root-cause analysis
* Multi-file reasoning across logs, configuration, SQL, Docker, and platform files
* Persistent diagnosis history
* Deployment error classification
* Secure JWT-based project ownership
* Failure-oriented debugging workflows

The system can diagnose failures such as:

* database connection and hostname errors
* Flyway migration checksum mismatches
* invalid environment-variable configuration
* Docker and runtime misconfiguration
* framework-specific deployment failures
* platform-specific deployment issues

👉 Pinned repository: **DeployForge**

---

### Chatty — Real-Time End-to-End Encrypted Chat System

A full-stack real-time encrypted chat application built with **Spring Boot**, **React**, **WebSockets**, and the **Web Crypto API**.

Chatty focuses on secure multi-device communication, encrypted message delivery, trusted-device approval, recovery phrase backup, and device-aware authentication.

**Core engineering themes**

* End-to-end encrypted messaging
* AES-GCM message encryption
* RSA-OAEP key wrapping
* Device-specific encrypted message keys
* Multi-device account support
* Trusted-device approval flow
* Recovery phrase-based encrypted key backup
* JWT authentication with HttpOnly refresh tokens
* Device-aware refresh-token revocation
* WebSocket-based real-time messaging
* Online presence, typing indicators, and read/delivery receipts

👉 Pinned repository: **Chatty**

---

## Engineering Focus

* Backend system architecture
* Spring Boot, FastAPI, and API design
* Domain-driven design and invariant enforcement
* Inter-service communication
* Real-time systems using WebSockets
* Authentication, authorization, and device-aware security
* End-to-end encryption architecture
* AI evaluation and diagnosis orchestration
* Structured AI-output validation
* State machines and progression engines
* Deterministic control systems
* Deployment failure analysis
* Failure-first backend design

---

## Currently Building

* **SkillForgeAI** — architecture hardening, diagrams, deployment, and evaluation-pipeline improvements
* **DeployForge** — diagnosis-quality improvements, broader failure classification, deployment history, and evidence-grounded remediation
* **Chatty** — release hardening, deployment polish, message pagination, push notifications, and Redis-backed presence
* **Second system-level project** — distributed or algorithmic engineering pillar

---

## Tech Stack

### Backend

* Java 21
* Spring Boot
* FastAPI
* Spring Security
* WebSockets / STOMP
* REST APIs
* JWT authentication
* PostgreSQL
* MongoDB
* Supabase
* Redis

### AI and Workflow Engineering

* LangChain
* LangGraph
* Structured LLM outputs
* Schema-based response validation
* AI evaluation pipelines
* AI-assisted deployment diagnosis

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* Web Crypto API
* IndexedDB

### Engineering Tools

* Git and GitHub
* Docker
* GitHub Actions
* Maven
* Postman
* Cloudflare Pages
* Render

---

## What I Care About

I am not interested in building only surface-level CRUD applications.

I care about systems where correctness matters:

* Can the backend reject invalid state transitions?
* Can the system recover safely from failure?
* Can AI output be constrained, validated, and audited?
* Can an AI diagnosis point to concrete evidence instead of guessing?
* Can failures be traced across logs, configuration files, and service boundaries?
* Can user data remain protected across multiple devices?
* Can real-time events remain consistent across sessions?

That is the kind of engineering I am working toward.

---

## Contact

* LinkedIn: https://www.linkedin.com/in/mohamed-fateen
* Email: [fateen.build@gmail.com](mailto:fateen.build@gmail.com)
