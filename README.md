# Ansh Kakadia

CS and Mathematics undergrad at Northeastern University (Khoury College), May 2028. I work on AI agent systems — orchestration, retrieval grounding, and the tooling that makes agent behavior observable and correctable.

Currently an AI Product Development Intern at Synoptek, continuing part-time through Fall 2026 to take the system to production.

**Open to a Spring 2027 co-op (January – July 2027).**

---

## Current work

**Synthia** — an AI desktop agent that resolves end-user IT tickets autonomously: plain-language intake, on-device diagnostics and remediation, full action logging. *(Closed source)*

- Designed the orchestration layer over a five-agent fleet — intent classification, agent sequencing, guardrails, and resolve-vs-escalate decisioning
- Grounded responses with Azure AI Search retrieval over IT knowledgebases, pairing LLM reasoning with deterministic runbooks
- Built Mission Control, a technician console with fleet-wide observability over live agent sessions: in-flight suggestions, course correction, and full session takeover mid-resolution
- Validated against 70,040 quarterly support tickets across 42 of the top 50 issue patterns

---

## Selected projects

| Project | Summary | Stack |
|---|---|---|
| [Album Cover Poster Creator](https://github.com/Ansh-Kakadia/Album_Poster_Creator) | Agentic pipeline that generates custom posters from a Spotify link, orchestrating metadata retrieval, image generation, and code compositing through tool calling. Generation and evaluation are separated — a distinct vision model critiques each draft on composition and readability rather than asking one model to self-assess. | Python, OpenAI API, Spotify API |
| [Fashion Outfit Optimizer](https://github.com/Ansh-Kakadia/CS4100_Final_Project) | Builds a complete outfit from a single anchor item. Encodes a 44K+ item catalog and 1,500 outfit templates as 67-dimensional embeddings over a K=20 cosine-similarity KNN graph, then uses simulated annealing to escape local optima in a non-convex scoring space where any single swap degrades the score before improving it. | Python, PyTorch, scikit-learn, Streamlit |
| [HuskyLeague](https://github.com/Ansh-Kakadia/26S-Project-DataGrippers) | Full-stack intramural sports league platform with four role-based personas (player, captain, admin, analyst). 16-table MySQL schema with ENUM-constrained statuses and named foreign-key constraints; live game statistics computed via multi-join SQL with conditional aggregation. | Python, Flask, Streamlit, MySQL, Docker |

---

## Tech

**Languages** Python · Java · SQL · JavaScript · OCaml · Dart

**AI/ML** Azure AI Foundry · Azure AI Search · LLM APIs (OpenAI, Anthropic) · PyTorch · scikit-learn · RAG

**Frameworks** React · Node.js · Flask · Streamlit · Firebase · Tailwind CSS · Flutter

**Tools** Git · Docker · Azure Service Bus · MySQL

---

## Elsewhere

[LinkedIn](https://linkedin.com/in/ansh-kakadia) · kakadia.an@northeastern.edu
