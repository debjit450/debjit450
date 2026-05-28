<div align="center">

# Debjit Dey

### Backend & Full-Stack Engineer · Distributed Systems · Real-Time Data Platforms

I build production-oriented software across **distributed backends**, **real-time intelligence systems**,  
**high-performance APIs**, and **applied machine learning**.

[![Portfolio](https://img.shields.io/badge/Portfolio-debjit--dey--2026.vercel.app-0EA5E9?style=for-the-badge&logo=vercel&logoColor=white)](https://debjit-dey-2026.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Debjit_Dey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/debjit-dey)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:debjitdey450@gmail.com)

![Backend Engineering](https://img.shields.io/badge/Backend_Engineering-111827?style=flat-square)
![Distributed Systems](https://img.shields.io/badge/Distributed_Systems-111827?style=flat-square)
![Real--Time Systems](https://img.shields.io/badge/Real--Time_Systems-111827?style=flat-square)
![Applied ML](https://img.shields.io/badge/Applied_ML-111827?style=flat-square)
![Developer Tooling](https://img.shields.io/badge/Developer_Tooling-111827?style=flat-square)

</div>

---

## About

I am a full-stack engineer with a backend-first approach to building reliable software. My work focuses on systems that ingest, process, and expose data under real operational constraints: asynchronous workloads, event-driven updates, API reliability, database performance, observability, and failure handling.

- **Engineering focus:** Distributed systems, backend architecture, real-time applications, REST/WebSocket APIs, data-intensive products, and developer tooling.
- **Currently building:** [SkyWatch Live](https://github.com/debjit450/skywatch-live), a real-time airspace surveillance and anomaly detection platform over live public aviation data.
- **Core technologies:** Python, TypeScript, Django, Node.js, React, PostgreSQL, Redis, Celery, Docker, AWS, CI/CD, and applied ML.
- **Based in:** Kolkata, India.

---

## Featured Project

# [SkyWatch Live](https://github.com/debjit450/skywatch-live)
### Real-Time Airspace Surveillance, Orbital Tracking & Anomaly Detection Platform

[![Repository](https://img.shields.io/badge/Repository-View_Source-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/debjit450/skywatch-live)
[![MIT License](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge)](https://github.com/debjit450/skywatch-live/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/debjit450/skywatch-live?style=for-the-badge&logo=github&label=Stars)](https://github.com/debjit450/skywatch-live/stargazers)

<p align="center">
  <a href="https://github.com/debjit450/skywatch-live">
    <img src="https://raw.githubusercontent.com/debjit450/skywatch-live/main/frontend/public/showcase/skywatch.png" alt="SkyWatch Live airspace surveillance dashboard" width="100%" />
  </a>
</p>

**SkyWatch Live** is a full-stack aviation intelligence system for live aircraft tracking, satellite situational awareness, airspace overlays, and anomaly detection. It combines a React/TanStack Start interface with a Django, Channels, Celery, PostgreSQL, and Redis backend designed around ingestion, persistence, scoring, and real-time broadcast workflows.

```text
Public Aviation Feeds → Celery Ingestion & Scoring → PostgreSQL / Redis → REST + WebSockets → MapLibre Dashboard
```

**Engineering highlights**

- Designed a **multi-source ingestion pipeline** that combines OpenSky with supplemental public ADS-B and aviation data sources, normalizes live states, persists flight history, and broadcasts committed snapshots.
- Implemented **real-time system architecture** using Django REST Framework, Django Channels, Redis channel layers, Celery workers, Celery Beat scheduling, and PostgreSQL persistence.
- Built **anomaly detection and intelligence workflows** covering rule-based alerts, ML-assisted scoring, custom alert rules, explainability payloads, route prediction, and historical track playback.
- Integrated **satellite visualization using CelesTrak and SGP4 propagation**, alongside METAR weather cards and AWC/FAA airspace restriction overlays.
- Added **production observability foundations** through Prometheus metrics, Grafana provisioning, Jaeger tracing, structured JSON logging, health checks, and deployment documentation.

**Technology surface**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111827)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-111827?style=flat-square)
![MapLibre](https://img.shields.io/badge/MapLibre-396CB2?style=flat-square)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[**Explore the repository →**](https://github.com/debjit450/skywatch-live) &nbsp;·&nbsp;
[**Read the architecture →**](https://github.com/debjit450/skywatch-live/blob/main/docs/architecture.md) &nbsp;·&nbsp;
[**Read the technical write-up →**](https://medium.com/@debjitdey_59101/tracking-chaos-building-a-real-time-flight-anomaly-engine-with-django-celery-and-machine-3d499ab8824b)

---

## Selected Projects

<table>
<tr>
<td width="50%" valign="top">

### [ARCE](https://github.com/debjit450/arce)
**Distributed Adaptive Traffic Control System**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)

Adaptive rate limiting and abuse detection built around Redis-backed Lua scripts for atomic enforcement. Supports token bucket, sliding window, leaky bucket, dynamic traffic policies, middleware integration, and live metrics.

</td>
<td width="50%" valign="top">

### [GrindNode](https://grindnode.app)
**AI-Powered Coding Interview Platform**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111827)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Interview preparation product with Docker-based sandboxed execution, a custom judge engine, context-aware AI hints, and idempotent Razorpay webhook processing.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [StableJSON](https://stablejson.vercel.app)
**Privacy-First Browser JSON Toolkit**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111827)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Client-side utility for validating, formatting, diffing, querying, and generating schemas from JSON without transmitting user data to a backend.

</td>
<td width="50%" valign="top">

### [gitwit](https://github.com/debjit450/gitwit)
**AI Commit Message CLI**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)

Focused CLI developer tool that generates Conventional Commit messages from `git diff`, reducing repetitive workflow overhead while preserving readable commit history.

</td>
</tr>
</table>

---

## Professional Experience

### Valk Technologies & Solutions — Full-Stack Developer
`Dec 2024 – Sep 2025` · Kolkata, India

- Improved time-to-interactive by **~35–40%** across three client-facing Next.js applications using server-side rendering and route-level code splitting, verified through Lighthouse comparisons.
- Reduced average database response time from **~400 ms to ~160 ms** by identifying slow queries, eliminating N+1 patterns, and applying composite indexes across high-traffic MySQL and MongoDB collections.
- Investigated and resolved production incidents through structured log tracing and introduced graceful shutdown handling to reduce restart-related data loss risk.
- Established GitHub Actions CI workflows for automated builds and Jest test execution on pull requests, strengthening release confidence and regression detection.

### Collabtalent LLC — Frontend Engineer, Contract
`Apr 2024 – Nov 2024` · Remote, United States

- Contributed to an Angular-to-React migration that reduced new-developer onboarding time from approximately three weeks to five days.
- Integrated streaming LLM APIs with exponential backoff and retry handling, reducing timeout failures by **~70%**.
- Delivered accessible, responsive user interfaces aligned with WCAG-AA requirements across major browsers.

---

## Technical Competencies

| Area | Technologies & Practices |
| :--- | :--- |
| **Backend Engineering** | Python, Django, Django REST Framework, Node.js, Express, REST APIs, WebSockets, asynchronous processing |
| **Distributed & Real-Time Systems** | Celery, Redis, Channels, scheduled ingestion, event-driven updates, caching, rate limiting, anomaly pipelines |
| **Databases & Data** | PostgreSQL, MongoDB, MySQL, indexing, query optimization, persistence design, time-series flight state workflows |
| **Frontend Engineering** | React, TypeScript, Next.js, TanStack Start, Tailwind CSS, MapLibre, deck.gl, responsive UI |
| **Cloud & Delivery** | Docker, AWS EC2, GitHub Actions, CI/CD, Linux, deployment configuration, production readiness |
| **Observability & Reliability** | Prometheus, Grafana, Jaeger, structured logging, health checks, graceful shutdowns, retry and failure handling |
| **Applied AI / ML** | Gemini API integrations, ML-assisted anomaly scoring, explainability workflows, prediction interfaces |

---

## Education

**B.Tech in Computer Science Engineering**  
Techno India University, Kolkata · CGPA: **8.31**

---

<div align="center">

### Let’s build reliable software that solves difficult problems.

I am open to opportunities in **backend engineering**, **full-stack development**,  
**distributed systems**, **real-time platforms**, and **applied AI/ML**.

[![Portfolio](https://img.shields.io/badge/View_Portfolio-0EA5E9?style=for-the-badge&logo=vercel&logoColor=white)](https://debjit-dey-2026.vercel.app)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/debjit-dey)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/debjit450)

</div>
