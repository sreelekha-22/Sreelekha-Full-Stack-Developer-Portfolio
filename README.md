# Sreelekha Guda — Full-Stack Developer

> Building scalable full-stack applications with **React**, **TypeScript**, **Java**, **Spring Boot**, and **Python**. I love turning complex problems into clean, production-ready solutions.

[![GitHub](https://img.shields.io/badge/GitHub-sreelekha--22-blue?logo=github)](https://github.com/sreelekha-22)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sreelekha%20Guda-blue?logo=linkedin)](https://www.linkedin.com/in/sreelekha-guda-051473243)
[![Email](https://img.shields.io/badge/Email-sreelekha2.guda%40gmail.com-red?logo=gmail)](mailto:sreelekha2.guda@gmail.com)

## About Me

I'm a full-stack engineer with experience across frontend, backend, and AI/ML. I enjoy building resilient systems — from distributed microservices (Kafka + Spring Boot) to intelligent applications (LLMs, deep learning). Based in **Hyderabad, Telangana, India**.

## Featured Projects

### [Vykronis — Autonomous Incident Response Platform](https://github.com/sreelekha-22/Vykronis)
**Java · Spring Boot 4 · Apache Kafka · PostgreSQL · Redis**

A closed-loop, human-gated autonomous incident response platform. Detects anomalies, investigates via a tool-constrained AI agent (with deterministic rule-based fallback), enforces a fail-closed policy gate, and only remediates after human approval. 9 Spring Boot microservices, 6 Kafka topics, 298 tests across 70 classes.

- **Architecture**: Event-driven microservices on Kafka with versioned event contracts
- **Safety-first**: Fail-closed policy engine — service-to-service automation denied for production; human approval required
- **Resilient**: Rule-based fallback ensures pipeline never hard-fails when AI infra is degraded
- **Battle-tested**: Full end-to-end demo runs in < 1 min on a 7.9 GB laptop
- [View on GitHub →](https://github.com/sreelekha-22/Vykronis)

---

### [lessongen — Self-Evaluating Lesson Generator](https://github.com/sreelekha-22/lessongen)
**Python · LangGraph · LiteLLM · Pydantic**

Agentic `generate → evaluate → regenerate` system that writes lessons and judges them against a hard pass/fail rubric. Regenerates until every checkpoint passes, producing both the verified lesson and a full rejection log audit trail.

- **Self-evaluating**: 13 deterministic + LLM-judge checkpoints with no partial credit
- **Auditable**: Append-only event log, run records with token usage and provenance
- **Offline-first**: Deterministic stub provider works with zero API keys
- **Model-agnostic**: Works with OpenAI, Anthropic, Ollama, vLLM via LiteLLM
- [View on GitHub →](https://github.com/sreelekha-22/lessongen)

---

### [Language Profiling App](https://github.com/sreelekha-22/LanguageProfilingApp_1)
**React · FastAPI · Python · Whisper · MediaPipe**

Full-stack app that records video, transcribes speech with OpenAI Whisper, and analyzes fluency, vocabulary, grammar, fillers, and facial expressions/confidence to generate a comprehensive language profile.

- **Multimodal analysis**: Combines audio (Whisper) + video frames (MediaPipe) for richer insights
- **Structured assessment**: Two-round speaking evaluation with CEFR-style complexity analysis
- **Local-first**: Runs fully offline with local models — no external API keys required
- [View on GitHub →](https://github.com/sreelekha-22/LanguageProfilingApp_1)

---

### [Fake News Detection](https://github.com/sreelekha-22/ML_projects/tree/main/Fake_News_DetectionHK)
**React · Flask · Python · TensorFlow · Keras · LSTM**

AI-powered web app that classifies news articles as real/fake in real-time. Trained on Kaggle data using an LSTM model (~94% accuracy), served via Flask API with a clean React frontend.

- **Deep Learning**: Bidirectional LSTM for sequence classification
- **End-to-end**: Full stack ML app with React UI + Flask backend
- **Practical**: Returns predictions with confidence scores
- [View on GitHub →](https://github.com/sreelekha-22/ML_projects/tree/main/Fake_News_DetectionHK)

---

### [Absentra — Leave Management System](https://github.com/sreelekha-22/Absentra)
**React · TypeScript · Redux Toolkit · RTK Query · JSON Server**

Role-based leave management system for Employees, Managers, and HR. Features leave applications, approval workflows, employee management, and persistent leave balances.

- **RBAC**: Granular permissions by role (Employee/Manager/HR)
- **Modern state**: RTK + RTK Query for efficient data fetching/caching
- **Clean UX**: Responsive dashboard with status tracking and approval flows
- [View on GitHub →](https://github.com/sreelekha-22/Absentra)

---

### [Appointments Made Easy](https://github.com/sreelekha-22/Appointments-Made-Easy)
**Node.js · Express · EJS · MongoDB**

Scheduling platform that streamlines booking with automated email notifications and intuitive slot management.

- **Full-stack**: Node/Express backend with EJS templating
- **Automated comms**: Email alerts for bookings and updates
- **Production-ready**: Modular, RESTful structure
- [View on GitHub →](https://github.com/sreelekha-22/Appointments-Made-Easy)

---

### [Watch Hub](https://github.com/sreelekha-22/WatchHub)
**React · Express · MongoDB · JWT**

Full-stack video content platform with authentication, filtering, search, and admin CRUD operations.

- **Secure auth**: JWT-based authentication and protected routes
- **Admin panel**: Full content management capabilities
- **Responsive UI**: Dynamic, mobile-friendly interface
- [View on GitHub →](https://github.com/sreelekha-22/WatchHub)

---

### [UrlShorty](https://github.com/sreelekha-22/UrlShorty)
**Java · Spring Boot · MongoDB**

URL shortening service with clean DTO-layered architecture, URL hashing, and fast redirection.

- **RESTful API**: Clean, testable Spring Boot design
- **Scalable storage**: MongoDB for flexible persistence
- **Simple & reliable**: Production-ready structure
- [View on GitHub →](https://github.com/sreelekha-22/UrlShorty)

---

### [ML Projects Collection](https://github.com/sreelekha-22/ML_projects)
**Python · TensorFlow · Keras · OpenCV · Jupyter**

Collection of applied ML projects: Fake News Detection (LSTM), Medicinal Plant Identification, and Poultry Disease Detection.

- **Applied DL/CV**: Real-world datasets and practical use cases
- **End-to-end demos**: Includes full-stack integrations where applicable
- [Browse all →](https://github.com/sreelekha-22/ML_projects)

## Tech Stack

| Domain | Technologies |
|---|---|
| **Frontend** | React, TypeScript, Vite, Redux Toolkit, RTK Query, EJS |
| **Backend** | Java, Spring Boot, Spring Cloud, Node.js, Express, FastAPI, Flask |
| **Data & Messaging** | PostgreSQL, MongoDB, Redis, Apache Kafka, Kafka Streams, Flyway |
| **AI/ML** | Python, TensorFlow, Keras, LSTM, OpenAI Whisper, MediaPipe, LangGraph, LiteLLM |
| **DevOps & Infra** | Docker, Docker Compose, Helm, kind, GitHub Actions |
| **Observability** | OpenTelemetry, Prometheus, Grafana |
| **Architecture** | Microservices, Event-Driven, REST APIs, MVC |

## Get In Touch

- **GitHub**: [github.com/sreelekha-22](https://github.com/sreelekha-22)
- **LinkedIn**: [linkedin.com/in/sreelekha-guda-051473243](https://www.linkedin.com/in/sreelekha-guda-051473243)
- **Email**: [sreelekha2.guda@gmail.com](mailto:sreelekha2.guda@gmail.com)
- **Location**: Hyderabad, Telangana, India

---

*Built with clean, production-ready code. Always open to impactful engineering opportunities.*