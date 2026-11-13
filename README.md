# Markus Kühnle

**AI Engineer** · Document Intelligence, Agents & Production AI · Germany · [LinkedIn](https://linkedin.com/in/markuskuehnle) (~16k)

AI Engineer with 4+ years building production AI at the domain boundary: document intelligence (schema-gated extraction, span-level provenance), agents, RAG, and systems across manufacturing, pharma, health tech, banking, retail, automotive, and technical consulting.

Critical care nursing background (incl. infant ward), then tech from 2021. M.Sc. Information Systems @ University of Ulm (expected March 2027), part-time in parallel. Based in Germany. English C1.

---

## Selected work

### AI Engineer | Wieland AG · Ulm · Part-time
**Oct 2025 – Present** · Copper / foundry production planning

- **Requirements & Architecture:** Worked on-site with production and materials to define scope, data model, and system design for scrap-melting planning.
- **Optimization:** Built a MILP solver (Python, OR-Tools) under ~40 chemical constraints; co-designed the material pipeline with the same domain experts.
- **Data Quality:** Found and fixed material-data integrity issues during design so the optimizer was not fed bad inputs.
- **Analytics & Agents:** Reporting and agent UI for plant users on a skill suite with guardrails, MCP, semantic layer, and agent orchestration (Ollama / Claude / other self-hosted models). Also Streamlit apps for other internal tools.
- **Impact:** Pilot ~4% raw-material cost reduction; business case in the 7-figure €/year range (rollout ongoing).

Stack: Python, OR-Tools, FastAPI, Pydantic, Streamlit, MCP, semantic layer, agent orchestration, guardrails, Ollama, Claude, self-hosted LLMs, Linux.

Architecture: [`cases/production_ai_fde_solution_architecture.png`](cases/production_ai_fde_solution_architecture.png)

### AI Systems Engineer | PsyLogic · Ulm · University pre-founding venture
**Aug 2025 – Aug 2026** · Ended after MVP / clinician pilot

High-stakes document intelligence for a clinical copilot (own IP).

- **Knowledge Extraction:** Several thousand pages of regulated PDFs → layout/OCR with page/BBox anchors → hierarchical ToC → dual-pass extract + ground.
- **Schema Gate:** Pydantic circuit breaker blocks ungated writes; self-heal ≤2; 99.4% extraction quality on a validated sample.
- **Dual-Path Agent:** Deterministic rules path (measured <800ms p95) + guideline/protocol RAG; synthesis only with span-level provenance.
- **Delivery & Pilot:** AI lead in a 3-person team (AI, web, clinician); MVP + clinician pilot at University Hospital Ulm; MDR Class IIa architecture review; venture not continued.

Architecture: [`cases/medextract_solution_architecture.png`](cases/medextract_solution_architecture.png)

### Data Scientist | Alta Sigma GmbH · Ulm · Part-time / consulting
**Jan 2025 – Sep 2025**

Modular data/ML platform (reusable enterprise modules).

- **RAG Module Ownership:** Multi-format corpora, quality/latency evaluation, product API.
- **Document AI / OCR:** Multiple OCR approaches with fallback + rules; >90% faster vs. manual; VQA contribution.
- **Enterprise Delivery:** Delivery owner for enterprise AI chatbots; technical discovery with stakeholders (no client names).

### Data Scientist (Technical / Data Science Consulting) | elanyo GmbH · Stuttgart · Full-time
**Nov 2023 – Dec 2024**

Technical consulting: led development and deployment of ML projects for industrial, retail, and e-commerce clients, covering models, data pipelines, and the APIs/UIs to put them into production.

- **Computer Vision:** Defect detection + manufacturing API; scrap −25% in project context.
- **Retail Pricing / Recommenders:** Competitor-price scraping + dynamic pricing; store-layout and path simulation (large retail client).
- **Segmentation:** Automotive OEM (Europe); group-wide rollout; campaign ROI +15%.

### Data Analyst | Teva Pharmaceuticals · Internship / Bachelor thesis · Teva US
**Sep 2022 – Sep 2023**

- **Campaign Analytics:** US smart-inhaler forecast (+30% accuracy vs. baseline) + HCP targeting for marketing/sample allocation.
- **NLP / Conversational AI:** Built chatbot interfaces and conversational flows with Kore.ai for internal / US-facing use cases.
- **Process Automation:** SQL/Python automation for US sales reporting (>100 h/month saved).

---

## Community

- LinkedIn (~16k): applied AI engineering from real projects (document intelligence, grounded agents, production AI)
- Mentoring (FPDS): production ML/RAG reviews; workshops (tooling, semantic layer)
- Research support, IBA Ulm (2025–2026): interactive XAI platform and hierarchical time-series baselines
- Open source: credit-document OCR system (~275 stars, ~85 forks)

---

## Stack

Document AI · schema gates (Pydantic) · span provenance · dual-path agents (rules + RAG) · MCP · semantic layer · agent orchestration · guardrails · FastAPI · Streamlit · OR-Tools · Ollama / Claude / self-hosted LLMs · Python/SQL · PostgreSQL/pgvector · Azure/GCP (project-dependent)

---

Open to forward-deployed / field-style AI engineering and platform / module ownership: technical ownership between complex systems, domain experts, and shipping.
