# Praximity
A Research OS

**Praximity** is an open-source, cross-platform mobile application (Android/iOS) designed to turn research into a social, dynamic, and deeply personal learning experience.  

Built for autodidacts, researchers, and learning cohorts, it fuses AI-assisted semantic search, embedded annotation, timeline generation, and collaborative study—making rigorous learning scalable, elegant, and shareable.

> "Learn as a guild. Think as a swarm. Study like civilization depends on it."

---

## 🔍 Features

### 📚 Semantic Research Engine
- Input a research query (e.g., *"The impact of CRISPR on global bioethics"*)
- Fetches & ranks sources across:
  - Academic databases (arXiv, PubMed, SSRN, etc.)
  - Preprint servers
  - Open-access journals
  - Policy briefs, whitepapers, lectures
- Rank based on:
  - Relevance
  - Citation density
  - Recency
  - Source credibility

### 🧠 Smart Study Plan Generator
- Dynamically creates Gantt-style timelines
- Adapts based on document complexity, estimated reading time, and user pacing
- Weekly adaptive updates if sources change

### 📖 Embedded AI-Powered E-Reader
- Highlight, annotate, and organize text and figures
- Auto-generates *talking notes* (audio summaries in natural language)
- Customize tone (e.g., *podcast-style*, *Socratic*, *bullet-point academic*)

### 🧬 Source Intelligence Layer
- Auto-tags sources by:
  - Theme
  - Methodology
  - Conflicting viewpoints
- Highlight conceptual disagreements and emergent patterns

### 🤝 Cohort-Based Learning (Collaborative Mode)
- Create or join a research group
- Shared source packets, synced timeline
- Live discussions with AI-generated minutes
- Group overlays: see what others highlight, annotate together
- Post-session consensus summaries

---

## 🛠 Tech Stack

- **React Native** for Android/iOS
- **Firebase** (Auth, Firestore, Storage) for user data & group sync
- **Node.js** backend (Express)
- **LangChain** + **OpenAI/Claude/Local LLMs** for summarization & search
- **Scrapy/Puppeteer** for content ingestion (via external microservices)
- **Python** for semantic indexing & source classification
- **PostgreSQL** + **pgvector** for vector search

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- Yarn or npm
- Android Studio / Xcode CLI tools

### Install

```bash
git clone https://github.com/your-org/praximity.git
cd praximity
yarn install

Run on Android

yarn android

Run on iOS

cd ios
pod install
cd ..
yarn ios```


---

📦 Contributing

We welcome pull requests, feature proposals, and critique.

Fork the repo

Create a new branch: feature/my-feature

Make your changes

Submit a PR with a clear description


Refer to CONTRIBUTING.md for more details.


---

🛡 License

GNU General Public License v3.0

Praximity is free software: you can redistribute it and/or modify it under the terms of the GPL as published by the Free Software Foundation. See LICENSE for full details.


---

🧙 Vision

In a collapsing attention economy, Praximity is not just an app—
It’s an epistemic weapon.
A tool for critical thinking guilds, sovereign knowledge flows, and organized intelligence.


---

👤 Maintainer

Frater O — Founder & Builder
[Twitter](https://x.com/ovahly)


---

🌌 Roadmap

[ ] Offline-first mode

[ ] Integration with Zotero/Mendeley

[ ] Plugin system for custom ingest pipelines

[ ] AI "learning companion" personas

[ ] Federated/self-hostable version



---

Praise the proximity of minds. Let research become ritual.

---

Let me know if you want:
- A separate `CONTRIBUTING.md` or `CODE_OF_CONDUCT.md`
- A docs folder with architecture diagrams or deployment instructions
- Licensing alternatives for non-copyleft friendliness (e.g., MIT for optional modules)

We can make this project feel like a movement.