# جمهور — Jomhoor

[Jomhoor](https://jomhoor.org) is a digital democracy platform enabling secure identity verification and voting for Iranians, powered by NFC document scanning and zero-knowledge proofs.

---

## Live Platforms

### [Jomhoor.org](https://jomhoor.org) — Campaign & Information Hub

[![Jomhoor.org](https://Jomhoor.org/images/thumbnail-fa-a.png)](https://jomhoor.org)

Bilingual (Persian/English) landing page explaining the platform's five structural gaps, the INID SDK, sponsorship model, and ecosystem partners.

---

### [Civic Compass](https://compass.jomhoor.org) — Map Your Political Identity

[![Civic Compass](https://compass.jomhoor.org/opengraph-image?c374982651b8fc0)](https://compass.jomhoor.org)

Eight policy dimensions. One unique shape. Move beyond left-right — discover where you truly stand.

---

### [Taraaz تراز](https://taraaz.jomhoor.org) — Deliberation & Collective Decision-Making

[![Taraaz تراز](https://taraaz.jomhoor.org/og-image.png)](https://taraaz.jomhoor.org)

A space where citizens come together for dialogue and collective decision-making. Built on [Agora](https://github.com/zkorum/agora).

---

## Repositories

| Repository | Description |
|---|---|
| [Jomhoor-citizen-wallet](https://github.com/jomhoor/Jomhoor-citizen-wallet) | The official mobile app (iOS/Android) for [Iranians.Vote](https://iranians.vote). Enables NFC-based passport and national ID card scanning, zero-knowledge proof identity verification (Noir + Circom circuits), and secure on-chain voting on Rarimo L2 — with passport data never leaving the device. |
| [Platform](https://github.com/jomhoor/Platform) | Backend infrastructure for Jomhoor. Contains all backend services, smart contracts (Solidity), deployment configurations, and utility scripts that power the platform. The mobile app communicates with these services to register verified identities and submit votes on the Rarimo L2 blockchain. |
| [Civic-Compass](https://github.com/jomhoor/Civic-Compass) | A Next.js frontend application for the Civic Compass feature — a political compass tool that helps users understand and explore political positions. |
| [Civic-compass-backend](https://github.com/jomhoor/Civic-compass-backend) | NestJS backend service powering the Civic Compass feature, providing APIs for the frontend application. |
| [Jomhoor.org](https://github.com/jomhoor/Jomhoor.org) | Source code for the [jomhoor.org](https://jomhoor.org) website — a multilingual (Persian/English) static site featuring information about the platform, a political compass, and deliberation tools. |