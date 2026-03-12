# جمهور — Jomhoor

[Jomhoor](https://jomhoor.org) is a digital democracy platform enabling secure identity verification and voting for Iranians, powered by NFC document scanning and zero-knowledge proofs.

## Repositories

| Repository | Description |
|---|---|
| [Jomhoor-citizen-wallet](https://github.com/jomhoor/Jomhoor-citizen-wallet) | The official mobile app (iOS/Android) for [Iranians.Vote](https://iranians.vote). Enables NFC-based passport and national ID card scanning, zero-knowledge proof identity verification (Noir + Circom circuits), and secure on-chain voting on Rarimo L2 — with passport data never leaving the device. |
| [Platform](https://github.com/jomhoor/Platform) | Backend infrastructure for Jomhoor. Contains all backend services, smart contracts (Solidity), deployment configurations, and utility scripts that power the platform. The mobile app communicates with these services to register verified identities and submit votes on the Rarimo L2 blockchain. |
| [Civic-Compass](https://github.com/jomhoor/Civic-Compass) | A Next.js frontend application for the Civic Compass feature — a political compass tool that helps users understand and explore political positions. |
| [Civic-compass-backend](https://github.com/jomhoor/Civic-compass-backend) | NestJS backend service powering the Civic Compass feature, providing APIs for the frontend application. |
| [Jomhoor.org](https://github.com/jomhoor/Jomhoor.org) | Source code for the [jomhoor.org](https://jomhoor.org) website — a multilingual (Persian/English) static site featuring information about the platform, a political compass, and deliberation tools. |