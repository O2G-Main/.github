<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
    <img alt="O2G: Applied decision systems and context graphs" src="./assets/hero-light.svg" width="100%">
  </picture>
</div>

<p align="center">
  <strong>O2G</strong> is an Indonesian engineering collective building applied decision systems, context graphs, and field software across aquaculture, healthcare, agriculture, energy, industrial supply chains, and capital markets.
</p>

<p align="center">
  <a href="https://github.com/orgs/O2G-Main/repositories">Repositories</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/orgs/O2G-Main/people">People</a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/O2G-Main/.github">Profile Source</a>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/divider-dark.svg">
  <img alt="" src="./assets/divider-light.svg" width="100%">
</picture>

## Multi-Service Platforms

Core products split across dedicated backend engines, web consoles, and mobile clients.

| Platform | Focus | Repositories | Stack |
| :--- | :--- | :--- | :--- |
| **AquaSeq** | Shrimp pond health decision support combining eDNA qPCR and water chemistry scoring with offline-capable field observation (GenoHack 2026) | [`AquaSeq-back`](https://github.com/O2G-Main/AquaSeq-back), [`AquaSeq-front`](https://github.com/O2G-Main/AquaSeq-front)<br>[`AquaSeq-Mobile`](https://github.com/O2G-Main/AquaSeq-Mobile), [`AquaSeq-Explaination`](https://github.com/O2G-Main/AquaSeq-Explaination) | Go, Next.js, TypeScript, Expo |
| **Pantara** | Collaborative team workspace designed to help teams distribute and balance workloads sustainably | [`PANTARA-BACK`](https://github.com/O2G-Main/PANTARA-BACK), [`PANTARA-v1`](https://github.com/O2G-Main/PANTARA-v1)<br>[`Pantara`](https://github.com/O2G-Main/Pantara) | Go (chi, pgx, Redis), Next.js, Python |
| **MilkGraph** | Dynamic dairy receiving flow, end-to-end volume traceability, and context-graph simulation for milk processing (PLAY IT! PLUS 2026) | [`Milkgraph`](https://github.com/O2G-Main/Milkgraph), [`Milkgraph-Back`](https://github.com/O2G-Main/Milkgraph-Back) | Next.js, TypeScript, Go, PostgreSQL |

## Context Graphs and Intelligence

Systems that connect fragmented operational records into queryable graphs and risk views.

| Project | What It Does | Links | Stack |
| :--- | :--- | :--- | :--- |
| **Tessera** | Customer churn early-warning graph unifying CRM, billing, support, usage, and interaction signals for account teams | [Repository](https://github.com/O2G-Main/tessera)<br>[Live Demo](https://tessera-xi-swart.vercel.app) | JavaScript, TypeScript, Python |
| **ChainGuard** | Traceability dashboard and IoT logger receiver for chili and shallot agricultural supply chains | [Repository](https://github.com/O2G-Main/chainguard-app) | TypeScript, Next.js, Neo4j |
| **OreLens** | Commodity exposure and company resilience intelligence across IDX coal, gold, nickel, and copper issuers (Sectors Hackathon) | [Repository](https://github.com/O2G-Main/OreLens) | Python (Django/DRF), Next.js, SQLite |

## Applied AI and Field Operations

Focused tools solving operational workflows in clinics, rural energy grids, internal SOPs, and verified learning.

| Project | What It Does | Links | Stack |
| :--- | :--- | :--- | :--- |
| **KapanDok** | Outpatient clinic start-time prediction and WhatsApp arrival re-timing system (UMS Health Innovation Hackathon 2026) | [Repository](https://github.com/O2G-Main/kapandok) | TypeScript, Python, Docker |
| **SuryaJaga** | Early-warning monitoring prototype keeping rural solar microgrids (PLTS desa) operational (Seno Hackathon ITS 2026) | [Repository](https://github.com/O2G-Main/SURYAJAGA)<br>[Live Demo](https://suryajaga.vercel.app) | Next.js, TypeScript, FastAPI |
| **SOPia** | Conversational SOP assistant that surfaces matching policy clauses, step sequences, and human approval checkpoints | [Repository](https://github.com/O2G-Main/SOPia) | Python, TypeScript |
| **Progressio** | Career-path learning platform turning diagnostics and skill assessments into SHA-256 verifiable credentials | [Repository](https://github.com/O2G-Main/Progressio) | Python, JavaScript, Flutter (Dart) |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/divider-dark.svg">
  <img alt="" src="./assets/divider-light.svg" width="100%">
</picture>

## Stack and Engineering Approach

<p>
  <img alt="Go" src="https://img.shields.io/badge/Go-190128?style=flat-square&logo=go&logoColor=F2F1F0&labelColor=090011">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-190128?style=flat-square&logo=typescript&logoColor=F2F1F0&labelColor=090011">
  <img alt="Python" src="https://img.shields.io/badge/Python-190128?style=flat-square&logo=python&logoColor=F2F1F0&labelColor=090011">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-190128?style=flat-square&logo=nextdotjs&logoColor=F2F1F0&labelColor=090011">
  <img alt="React Native" src="https://img.shields.io/badge/React_Native-190128?style=flat-square&logo=react&logoColor=F2F1F0&labelColor=090011">
  <img alt="Flutter" src="https://img.shields.io/badge/Flutter-190128?style=flat-square&logo=flutter&logoColor=F2F1F0&labelColor=090011">
  <br>
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-29003F?style=flat-square&logo=postgresql&logoColor=white&labelColor=090011">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-29003F?style=flat-square&logo=redis&logoColor=F2F1F0&labelColor=090011">
  <img alt="Neo4j" src="https://img.shields.io/badge/Neo4j-29003F?style=flat-square&logo=neo4j&logoColor=F2F1F0&labelColor=090011">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-29003F?style=flat-square&logo=docker&logoColor=F2F1F0&labelColor=090011">
</p>

- **Deterministic logic before model layers:** Risk scoring, threshold gating, and curriculum rules are kept explicit and testable in Go or Python before layering inference or guidance on top.
- **Clear API boundaries:** Backend engines expose typed JSON and OpenAPI contracts consumed independently by Next.js dashboards and mobile clients.
- **Designed for field constraints:** Interfaces support low-friction channels such as WhatsApp notifications, rule-based offline fallbacks, and lightweight container deployments.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/divider-dark.svg">
  <img alt="" src="./assets/divider-light.svg" width="100%">
</picture>

<p align="center">
  <strong>O2G</strong> &middot; Indonesia &middot; <a href="https://github.com/orgs/O2G-Main/repositories">Browse all repositories</a>
</p>
