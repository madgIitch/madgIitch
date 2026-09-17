# José Ortiz Roldán

**Software Engineer · Fullstack · Data Engineering · AI**

Computer Engineering graduate from the **University of Seville**, currently pursuing a **Master's in Big Data & Data Engineering at Universidad Complutense de Madrid (UCM)**.

Based in **Madrid**, I enjoy building complete systems end to end: architecture, backend, data pipelines, frontend, infrastructure, observability and deployment.

I'm especially interested in **data-intensive applications, distributed systems, AI agents, developer tools and products built around real-world data**.

📫 peorrr2@gmail.com  
📍 Madrid, Spain

---

## What I'm working on

- 🎓 Master's in **Big Data & Data Engineering — Universidad Complutense de Madrid**
- 🏀 Building **Canastio**, a fantasy basketball platform powered by federated competition data
- 🌍 Developing **Mwangaza**, a satellite-powered drought early-warning and decision-support platform
- 🤖 Experimenting with **AI agents, RAG, observability and evaluation systems**
- 🛠️ Building web and mobile products with Python, TypeScript, React, React Native and PostgreSQL

---

## Stack

**Languages**  
TypeScript, JavaScript, Python, SQL, Kotlin

**Frontend & Mobile**  
React, React Native, Expo, Next.js, PWA, Jetpack Compose

**Backend & Data**  
Python, PostgreSQL, Supabase, FastAPI, ASGI, Node.js, Firebase, Google Earth Engine, REST APIs, Realtime systems

**Data & Geospatial**  
SQL, data pipelines, satellite data, NDVI, spatial aggregation, anomaly analysis, Google Earth Engine

**AI & LLM Systems**  
Gemini, Google ADK, RAG, MCP, LLM-as-judge evaluation

**Observability**  
OpenTelemetry, OpenInference, Phoenix / Arize

**Cloud & Infrastructure**  
Docker, Cloud Run, Railway, Vercel, Supabase, GitHub Actions

**Services**  
Stripe, FCM v1, RevenueCat, Plaid

**Tools**  
Git, VS Code, Figma, Android Studio, Expo EAS

---

# Featured Projects

## [Canastio](https://github.com/madgIitch/FABntasy) — Fantasy basketball data platform
*TypeScript · PostgreSQL · Supabase · Python · Railway · Vercel*

Fantasy basketball platform built around real federated competition data.

The project combines data ingestion, backend architecture, fantasy mechanics and product development into a full end-to-end system.

- Data ingestion pipelines for competitions, schedules, games and player statistics.
- PostgreSQL data model designed around competitions, teams, players, games and fantasy entities.
- Automated synchronization workflows between external federation data and the application database.
- Fantasy mechanics including leagues, squads, scoring, transfers and social features.
- Independent Python ingestion service deployed on Railway.
- Supabase backend with PostgreSQL and production migrations.
- CI/CD workflows and automated deployment infrastructure.
- Mobile-first PWA built for real league usage.

---

## [Mwangaza](https://github.com/madgIitch/Mwangaza) — Satellite-powered drought early-warning platform
*Python · Google Earth Engine · React · TypeScript · ASGI · Docker · Cloud Run*

Drought early-warning and decision-support prototype for the IGAD region, transforming satellite and climate data into interpretable risk signals and early-action recommendations.

- Satellite data pipeline processing vegetation, rainfall and land-surface-temperature indicators using Google Earth Engine.
- NDVI, rainfall and LST anomaly workflows with spatial aggregation and data-quality checks.
- Composite drought-risk scoring based on multiple environmental indicators.
- Explicit **live / cache / demo data provenance**, avoiding silent fallback to synthetic data.
- Python ingestion and processing layer exposed through an ASGI API.
- React + TypeScript PWA consuming processed environmental datasets.
- Alerts, early-action recommendations, reports and audit trails.
- End-to-end scenarios for **Somalia and Northern Kenya**, including Turkana, Marsabit and Isiolo.
- Low-bandwidth, multilingual and installable PWA behavior.
- Dockerized architecture and Cloud Run deployment.
- Production refresh pipeline with locking, immutable snapshots and atomic last-good promotion.
- Automated quality checks, testing and CI workflows.

---

## [Phoenix Reflex](https://github.com/madgIitch/Phoenix-Reflex) — Self-improving RAG agent
*Python · FastAPI · Google ADK · Gemini · OpenTelemetry · Phoenix/Arize · React*

Regression-driven PDF RAG system built for an AI observability hackathon.

Weak answers become regression cases, prompt candidates and scored experiments before a human promotes changes.

- Code-owned agent runtime with Google ADK and Gemini.
- FastAPI backend and React demo interface.
- OpenInference / OpenTelemetry instrumentation for GenAI calls.
- Phoenix / Arize observability for tracing and debugging.
- Phoenix MCP runtime introspection so the agent can inspect its own operational traces.
- In-session correction loop for invalid or phantom citation IDs.
- LLM-as-judge evaluation for faithfulness, document relevance and answer quality.
- Regression dataset generation from real failures.
- Candidate prompt experimentation against production behavior.
- Human-controlled staging and prompt promotion workflow.

---

## [HomiMatch](https://github.com/HomiMatch/HomiMatchApp) — Roommate matching platform
*React Native · Expo · TypeScript · Supabase · Stripe · FCM*

Mobile platform for finding rooms and flatmates, built end to end from architecture to backend, mobile client and deployment.

- Recommendation engine with weighted scoring:
  - 40% lifestyle
  - 30% budget
  - 20% location
  - 10% demographics
- Separate recommendation flows for seekers and owners.
- Premium visibility boosting system.
- ~45 Supabase Edge Functions in Deno with Zod validation.
- Authentication, matching, messaging, payments, push notifications and administrative logic.
- Full Stripe subscription lifecycle with checkout, portal and webhook handling.
- Transactional rollback on database failures.
- FCM v1 push notifications implemented without the Firebase SDK.
- Real-time messaging through PostgreSQL change subscriptions.
- Server-side rate limiting and premium feature enforcement.
- Concurrency-safe authentication token refresh.

---

## [What's In My Fridge](https://github.com/madgIitch/What-s-in-my-fridge-) — AI kitchen assistant
*React Native · Expo · TypeScript · Firebase · WatermelonDB · Cloud Run*

Mobile application for inventory management and AI-assisted recipe discovery.

- Receipt scanning and pantry inventory management.
- AI recipe import pipeline from YouTube, Instagram, TikTok and blog URLs.
- Whisper-based audio transcription.
- LLM extraction of ingredients and cooking steps.
- Containerized AI services deployed on Cloud Run.
- Firebase Cloud Functions integration.
- Offline-first architecture using WatermelonDB.
- Bidirectional Firestore synchronization.
- Freemium monetization with RevenueCat.
- Entitlements, purchase restoration and monthly usage limits.

---

## [Tonal Field](https://tonal-field.vercel.app) — Accessible color system generator
*Next.js · TypeScript · TailwindCSS · Supabase · Stripe*

SaaS tool for generating perceptually consistent color systems using the OKLCH color space.

- Interactive 2D field for exploring perceptual color relationships.
- Semantic palette generation.
- WCAG contrast auto-fix.
- Color blindness simulation.
- Authentication and PostgreSQL persistence.
- Supabase Row Level Security.
- Edge Functions.
- Stripe subscription system.

---

## [FinTrack](https://github.com/madgIitch/FinTrack-main2) — Personal finance PWA
*JavaScript · Firebase · Node.js · IndexedDB · Service Workers*

Progressive Web App for income and expense tracking.

- Offline-first architecture using IndexedDB and Service Workers.
- Real-time synchronization.
- Interactive dashboards and financial visualizations.
- Bank account integration through Plaid API.

---

## [SwipeClean](https://github.com/madgIitch/SwipeClean) — Android gallery cleanup
*Kotlin · Jetpack Compose*

Gallery management application based on multidirectional swipe gestures.

- Delete, save, share and Zen Mode interactions.
- MVVM architecture with StateFlow.
- Fluid gesture-driven animations.
- Zen Mode with audio, timer and haptic feedback.

---

## Currently interested in

**Data Engineering · Distributed Systems · Data Platforms · AI Agents · RAG · Observability · Backend Architecture · Developer Tools · Product Engineering**

---

## Contact / Opportunities

I'm always interested in meeting people working on **data, software engineering, AI, product development and technical projects**.

I'm also open to **junior software engineering roles and paid internships**, especially around backend, fullstack, data engineering or AI-enabled products.

📫 peorrr2@gmail.com
