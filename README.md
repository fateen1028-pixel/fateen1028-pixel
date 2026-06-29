# Mohamed Fateen — Backend Engineering

First-year Computer Science engineering student building **stateful backend systems, real-time applications, and AI-assisted workflows** using Java, Spring Boot, FastAPI, React, and TypeScript.

My current work focuses on:

* domain modeling and guarded state transitions
* authentication and authorization
* real-time communication using WebSockets
* inter-service communication
* structured validation of AI-generated output
* failure handling, recovery, and persistence consistency

---

## 🚩 Flagship Projects

### [DeployForge](https://github.com/fateen1028-pixel/DeployForge) — Deployment Diagnosis Platform

A full-stack system that analyzes deployment logs and configuration files to identify likely failure causes and generate structured remediation guidance.

DeployForge models the following hierarchy:

```text
User
└── Project
    └── Deployment Service
        └── Diagnosis
```

**Engineering highlights**

* Spring Boot application backend
* Separate FastAPI AI diagnosis service
* Spring Boot-to-FastAPI communication using `RestClient`
* Multipart log and configuration-file ingestion
* Structured AI responses validated with Pydantic
* JWT authentication and project ownership enforcement
* Persistent diagnosis history
* Secret sanitization before AI processing
* Deployment failure classification

**Tech:** Java 21, Spring Boot, Spring Security, PostgreSQL, FastAPI, LangGraph, React, TypeScript

---

### [Chatty](https://github.com/fateen1028-pixel/Chatty) — Multi-Device Encrypted Chat System

A real-time chat application built with Spring Boot, React, WebSockets, and the Web Crypto API.

Chatty implements client-side message encryption, device-specific key access, trusted-device approval, recovery flows, and device-aware authentication.

**Engineering highlights**

* AES-GCM message encryption
* RSA-OAEP key wrapping
* Device-specific encrypted message keys
* Client-side private-key storage using IndexedDB
* Trusted-device approval flow
* Recovery phrase-based encrypted key backup
* JWT access tokens with HttpOnly refresh-token cookies
* Device-aware refresh-token revocation
* STOMP over WebSockets
* Online presence, typing indicators, and delivery/read receipts

**Tech:** Java 21, Spring Boot, Spring Security, PostgreSQL, React, WebSockets, Web Crypto API

---

### [SkillForgeAI](https://github.com/fateen1028-pixel/SkillForgeAI) — Adaptive Learning State Engine

A full-stack learning system that models learner progress through roadmap, phase, slot, task, submission, and evaluation lifecycles.

The backend acts as the source of truth and rejects invalid state transitions before persistence.

**Engineering highlights**

* Roadmap and phase state engine
* Guarded slot and task lifecycle transitions
* Structured AI evaluation pipeline
* Bounded skill-vector updates
* Remediation and retry workflows
* Domain-level validation
* Optimistic locking for roadmap updates
* Repository and domain-layer separation

**Tech:** FastAPI, Pydantic, MongoDB, LangChain, Next.js, React

---

### [ArchitectAI](https://github.com/fateen1028-pixel/ArchitectAI-) — System Design Learning Platform

An interactive platform for studying system-design concepts, attempting architecture challenges, and receiving structured AI-assisted feedback.

**Engineering highlights**

* Topic and lesson APIs
* System-design challenge workflows
* Persistent architecture attempts
* Flyway-managed database migrations
* Spring Boot and React integration
* AI-assisted architecture evaluation

**Tech:** Java 21, Spring Boot, PostgreSQL, Flyway, React, TypeScript

---

## Engineering Focus

* Backend architecture
* Domain modeling and state machines
* Spring Boot and FastAPI
* REST API design
* Authentication and authorization
* Inter-service communication
* WebSocket-based real-time systems
* Structured AI-output validation
* Failure handling and recovery
* Database consistency and optimistic locking

---

## Tech Stack

### Backend

`Java 21` · `Spring Boot` · `Spring Security` · `FastAPI` · `REST APIs` · `WebSockets` · `STOMP`

### Data

`PostgreSQL` · `MongoDB` · `Supabase` · `Flyway`

### AI Engineering

`LangChain` · `LangGraph` · `Structured LLM Outputs` · `Pydantic Validation`

### Frontend

`React` · `TypeScript` · `Next.js` · `Vite` · `Tailwind CSS` · `Web Crypto API` · `IndexedDB`

### Tools

`Git` · `GitHub` · `Docker` · `Maven` · `Postman` · `Render` · `Cloudflare Pages`

---

## Currently Improving

* Adding evidence references and stronger validation to DeployForge diagnoses
* Expanding automated and adversarial tests for Chatty
* Strengthening SkillForgeAI invariant and concurrency test coverage
* Improving deployment, documentation, and observability across projects

---

## Contact

* **LinkedIn:** [linkedin.com/in/mohamed-fateen](https://www.linkedin.com/in/mohamed-fateen)
* **Email:** [fateen.build@gmail.com](mailto:fateen.build@gmail.com)
