<div align="center">

# Debjit Dey

### Software Engineer · Full-Stack Products · Applied AI · Real-Time Systems

I build end-to-end software products — web apps, live-data platforms, developer tools,  
and ML-integrated systems that move from idea to deployment.

[![Portfolio](https://img.shields.io/badge/Portfolio-debjit--dey--2026.vercel.app-111827?style=for-the-badge&logo=vercel&logoColor=white)](https://debjit-dey-2026.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Debjit_Dey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/debjit-dey)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:debjitdey450@gmail.com)

</div>

---

## About Me

I am a full-stack developer from Kolkata, India with experience building and shipping products across frontend, backend and cloud environments.

I like projects where the product is visible and the engineering matters: real-time tracking, interactive interfaces, async workflows, ML-assisted features, secure execution environments and production deployment.

Right now, my flagship project is **[SkyWatch Live](https://github.com/debjit450/skywatch-live)** — an airspace intelligence platform that tracks live aircraft, visualizes satellites and surfaces unusual flight behaviour using a three-model anomaly detection pipeline.

---

## Featured Project — [SkyWatch Live](https://github.com/debjit450/skywatch-live)

### Airspace Intelligence Platform · `May 2026 - Present`

[![Repository](https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/debjit450/skywatch-live)
[![Stars](https://img.shields.io/github/stars/debjit450/skywatch-live?style=for-the-badge&logo=github&label=Stars)](https://github.com/debjit450/skywatch-live/stargazers)
[![License](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge)](https://github.com/debjit450/skywatch-live/blob/main/LICENSE)

<a href="https://github.com/debjit450/skywatch-live">
  <img src="https://raw.githubusercontent.com/debjit450/skywatch-live/main/frontend/public/showcase/skywatch.png" alt="SkyWatch Live airspace intelligence dashboard" width="100%" />
</a>

**SkyWatch Live** is a real-time airspace surveillance and anomaly detection platform built with public aviation and orbital data.

At the captured project benchmark, it tracked **11,862 active aircraft** including **10,894 airborne aircraft** on 30-second polling cycles, combining state vectors from **5+ public feeds** with cross-source deduplication.

#### What I built

- Ingested live ADS-B data from multiple public sources, including OpenSky, ADS-B One and FLARM, and displayed unique aircraft on an interactive Leaflet canvas map.
- Implemented a **three-model ML ensemble** — Isolation Forest, Local Outlier Factor and MLP Autoencoder — over a **30-dimensional engineered feature space** for asynchronous trajectory anomaly detection.
- Indexed **85,390 airport facilities across 249 countries** for origin and destination resolution.
- Added SGP4 satellite propagation using CelesTrak TLE data, alongside live FAA TFR and AWC SIGMET airspace overlays.
- Designed the event-driven workflow using Django Channels, Celery and Redis so ingestion and ML scoring run asynchronously while telemetry streams over WebSockets.
- Exposed Prometheus metrics with custom gauges, counters and histograms for a Grafana observability dashboard.

#### Stack

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111827)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-111827?style=flat-square)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

[**View the repository →**](https://github.com/debjit450/skywatch-live) &nbsp;·&nbsp;
[**Read the architecture →**](https://github.com/debjit450/skywatch-live/blob/main/docs/architecture.md) &nbsp;·&nbsp;
[**Read the build story →**](https://medium.com/@debjitdey_59101/tracking-chaos-building-a-real-time-flight-anomaly-engine-with-django-celery-and-machine-3d499ab8824b)

---

## Another Product — [GrindNode](https://grindnode.app)

### Coding Practice Platform · `Oct 2025 - Present`

A full-stack coding practice platform built around safe code execution, structured problem tracks and AI-assisted learning.

- Built a custom judge engine that executes Python and Java submissions inside isolated Docker containers rather than running arbitrary user code on the host.
- Designed validation for exact-match and floating-point outputs across **853 problems** spanning **35+ topic tracks**.
- Added a Monaco-based editor for an IDE-like browser experience.
- Integrated Razorpay payment webhooks with idempotent event handling to avoid duplicate subscription grants.
- Added Gemini-powered hints that help users progress without revealing full solutions.

`React` `Node.js` `PostgreSQL` `Docker` `AWS` `Gemini API`

---

## Experience

### Full-Stack Developer — Valk Technologies & Solutions
`Dec 2024 - Sep 2025` · Kolkata, India

- Served as the sole developer on **Inca**, a live ride-booking platform: built the Node.js backend, React Native Android apps for customers and drivers, and a Next.js admin dashboard; shipped the product to the Play Store where it reached **500+ downloads**.
- Implemented real-time trip tracking and driver matching with Socket.io and MongoDB geospatial queries, keeping customer, driver and admin views synchronized without a polling layer.
- Built product catalogue, cart and order-management workflows for an e-commerce platform using Next.js and MySQL, giving the business a single admin interface for inventory and orders.
- Diagnosed N+1 query patterns and introduced composite indexes across MySQL and MongoDB to improve response times on frequently used endpoints without changing the schema.
- Set up GitHub Actions CI/CD pipelines, environment-based configuration management and graceful shutdown handling to prevent in-flight request drops during deployments.

### Frontend Engineer (Independent Contractor) — Collabtalent LLC
`Mar 2024 - May 2024` · Remote, United States

- Migrated core frontend components from Angular to React using TypeScript strict mode, eliminating a recurring class of runtime type errors in the existing codebase.
- Built asynchronous request handling with retry logic and streaming support for LLM API integrations, keeping the UI responsive during high-latency model responses.
- Brought UI components up to WCAG-AA accessibility standards, improving screen-reader usability and resolving cross-browser responsiveness gaps.

---

## Tech I Work With

| Area | Technologies |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript (ES6+), Python, Lua |
| **Frontend** | React.js, Next.js, React Native |
| **Backend** | Node.js, Express.js, Django, REST APIs, WebSockets, Socket.io, Celery |
| **Databases** | PostgreSQL, MySQL, MongoDB, Redis |
| **ML & Data** | scikit-learn, Keras, Isolation Forest, Local Outlier Factor, MLP Autoencoder, LSTM, feature engineering |
| **Cloud & DevOps** | Docker, AWS EC2, S3, CloudFront, GCP Compute Engine, GitHub Actions, CI/CD |

---

## Education & Certification

**B.Tech, Computer Science Engineering**  
Techno India University, Kolkata · `2020 - 2024` · **CGPA: 8.31 / 10**

**Google Cloud Digital Leader**  
Google Cloud · `Dec 2023`

---

<div align="center">

### I build complete products, not just isolated features.

Open to opportunities in **software engineering**, **full-stack development**,  
**applied AI/ML** and **product-focused engineering**.

[![Portfolio](https://img.shields.io/badge/View_Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white)](https://debjit-dey-2026.vercel.app)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/debjit-dey)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/debjit450)

</div>
