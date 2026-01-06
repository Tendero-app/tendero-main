# Tendero: Open Source Procurement Intelligence

![Tendero](https://img.shields.io/badge/Tendero-Open%20Source-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-AGPLv3-green?style=for-the-badge)
![Build Status](https://img.shields.io/badge/Build-Passing-success?style=for-the-badge)

**Democratizing access to European public procurement.**

Welcome to the open-source home of Tendero. This project represents our commitment to lowering the barrier of entry for businesses interacting with government contracts. By opening our codebase, we are giving everyone the opportunity to own, deploy, and configure a powerful tender management software locally.

> **Live Platform:** You can see the hosted version of this software at [**tendero.eu**](https://tendero.eu).There we maintain a **freely accessible market intelligence portal** where you can analyze historical data from above-threshold EU public procurement at no cost.

---

## 🟢 The "Why"

Public procurement is often gated by complexity, expensive proprietary tools, and opaque data. We built Tendero to change that.

Our goal has always been simple: use technology to make public spending transparent and accessible. We realized that to truly lower the barrier to entry, the tools themselves need to be accessible. We are open-sourcing our platform so that developers, SMEs, and researchers can:
* Deploy their own procurement intelligence systems.
* Audit and improve how public data is collected and analyzed.
* Build custom workflows on top of our existing infrastructure.

---

## 👥 Builders & Contributors

This platform was built by a dedicated team of founders and engineers passionate about transparency and software architecture.

* **Ivan Stanisavljevic** - *CEO & Founder*
* **Victor-Catalin Bodiu** - *COO, CTO & Founder*
* **Demids Kaidalovs** - *Founding Engineer & Solutions Architect*
* **Marius Frija** - *AI Engineer*
---

## 📂 Repository Structure

This project is divided into three main components, each serving a specific role in the pipeline. **Detailed instructions for installation and usage are located inside the README of each specific component.**

### 1. `tendero-monorepo`
The core of the application. This repository contains:
* **The Web Platform:** The full-stack application (UI and API) that users interact with.
* **The Scrapers:** Our collection of data ingestion tools designed to fetch notices from Tenders Electronic Daily (TED) and national portals.

### 2. `tendero-ai`
The brain of the operation. This module hosts the Machine Learning and NLP models responsible for:
* Semantic search capabilities.
* Automated tender summarization.
* Compliance criteria extraction (parsing "must-have" requirements from unstructured documents).

### 3. `tendero-market-intel`
The data processing powerhouse. This component handles the cleaning, normalization, and analytical processing of historical data. It is split into specific pipelines for:
* **EU-wide Intelligence:** Large-scale analysis of above-threshold tenders.
* **Austria (AT) Intelligence:** Specialized processing for Austrian national data standards.

---

## 🛠️ What it Does

Tendero is more than just a search engine. It is a complete suite for procurement management:

* **Deep Search:** Find opportunities based on context and service descriptions, not just keywords.
* **Automated Compliance:** The AI reads the tender documents for you, extracting critical requirements (Certifications, Turnover, Staffing) so you know if you qualify in seconds.
* **Market Intelligence:** Visualize buyer spending patterns and competitor behavior using our pre-built data pipelines.
* **Standardization:** We map disparate data formats from different countries into a single, unified structure.

---

## 🏗️ Deployment & Support

We designed this software to be locally deployable and highly configurable. Whether you are an agency wanting to host your own internal tool or a developer looking to contribute, you can get this running on your own infrastructure.

### Need help deploying?
Deploying a microservices architecture with AI components can be complex.
**If you need assistance deploying Tendero locally or on your own servers, please reach out to us.** We are happy to guide you through the architecture and configuration.

---

## 📄 License

This project is licensed under the **AGPLv3 License**. This ensures that the software remains free and open for everyone, forever.

<p align="center">
  <b>Tendero</b><br>
  <a href="https://tendero.eu">tendero.eu</a> | <a href="https://tendero.at">tendero.at</a>
</p>
