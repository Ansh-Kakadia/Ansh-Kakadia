# Ansh Kakadia

**Email:** kakadia.an@northeastern.edu
**Phone:** (215) 833-7067
**Location:** Boston, MA
**LinkedIn:** [linkedin.com/in/ansh-kakadia](https://linkedin.com/in/ansh-kakadia)
**GitHub:** [github.com/Ansh-Kakadia](https://github.com/Ansh-Kakadia)

---

## Education

**Northeastern University, Khoury College of Computer Science** | Boston, MA
*BS in Computer Science and Mathematics* | Expected May 2028

- **GPA:** 3.94/4.0
- **Awards and Activities:** Dean's List, Oasis Project Series
- **Relevant Coursework:** Artificial Intelligence, Machine Learning, Algorithms and Data, Object-Oriented Design, Logic and Computation, Linear Algebra, Statistics

---

## Technical Skills

**Languages:** Python, Java, SQL, JavaScript, OCaml, Dart

**AI/ML:** Azure AI Foundry, Azure AI Search, LLM APIs (OpenAI, Anthropic), PyTorch, scikit-learn, RAG

**Frameworks/Libraries:** React, Node.js, Flask, Streamlit, Firebase, Tailwind CSS, Flutter, JUnit

**Developer Tools:** Git, Docker, Azure Service Bus, MySQL, WSL

---

## Professional Experience

### AI Product Development Intern | Synoptek | Boston, MA
*April 2026 – Present*

- Built Synthia, an AI desktop agent that resolves end-user IT tickets autonomously: plain-language intake, on-device diagnostics and remediation, and full action logging
- Validated against 70,040 quarterly support tickets: compressed 45–150 minute routine resolutions to under 5 minutes across 42 of the top 50 issue patterns, with 14.7% resolvable end to end autonomously and 33.3% with human-in-the-loop approval
- Designed the orchestration layer over a five-agent fleet: intent classification, agent sequencing, guardrails, and resolve-vs-escalate decisioning, grounding responses with Azure AI Search retrieval over IT knowledgebases, pairing LLM reasoning with deterministic runbooks
- Shipped Mission Control, a technician console providing fleet-wide observability over live agent sessions, with in-flight suggestions, course correction, and full session takeover mid-resolution
- Returning part-time in Fall 2026 to deploy the system to production, hardening orchestration and connectors and adding ServiceNow write with tenant separation

### Teaching Assistant | Northeastern University | Boston, MA
*January 2025 – December 2025*

- Assisted two courses, Logic & Computation and Calculus 3 for Engineers, grading weekly quizzes and exams for 100+ students
- Held biweekly office hours, working through problem sets and exam preparation with students
- Collaborated with instructors on point distribution across assessment problems to more accurately measure student understanding

---

## Project Experience

### [HuskyLeague](https://github.com/Ansh-Kakadia/26S-Project-DataGrippers)
*Python, Streamlit, Flask, MySQL, Docker, REST API* | March 2026 – April 2026

- Developed a full-stack intramural sports league platform, containerized with Docker Compose, supporting four role-based personas: player, team captain, league admin, and analyst
- Modeled a 16-table MySQL schema with ENUM-constrained statuses and named foreign-key constraints, computing live game statistics via multi-join SQL with conditional aggregation

### [Fashion Outfit Optimizer](https://github.com/Ansh-Kakadia/CS4100_Final_Project)
*Python, PyTorch, scikit-learn, Streamlit* | January 2026 – April 2026

- Built a machine-learning outfit optimizer that generates and refines a complete outfit from a single anchor item, encoding a 44K+ item catalog and 1,500 outfit templates as 67-dimensional embeddings over a K=20 cosine-similarity KNN graph
- Chose simulated annealing over greedy selection to escape local optima in a non-convex outfit space, where swapping any single item degrades the multi-objective score — color harmony, formality coherence, seasonal fit — before improving it

### [Album Cover Poster Creator](https://github.com/Ansh-Kakadia/Album_Poster_Creator)
*Python, OpenAI API, Spotify API* | February 2026

- Architected an agentic AI system that generates custom album posters from a Spotify link, orchestrating metadata retrieval, image generation, and code compositing through tool calling
- Separated generation from evaluation rather than asking one model to produce and self-assess in a single pass, adding a distinct vision-model critique that scores each draft on composition and readability

---

## Earlier Projects

- **Sanguine (Queen's Blood)** — *Java* — Playable implementation of a card minigame variant, with rule enforcement and turn resolution
- **Maze-Solver** — *Java*, April 2025 — Graph-based maze generation via Kruskal's Algorithm, guaranteeing solvability at any size, with an interactive BFS/DFS solver and a 30+ test suite
- **Seam-Carver** — *Java*, April 2025 — Content-aware image resizing using a dual-gradient energy function and dynamic programming, with a pixel-neighbor graph to avoid recomputing seams
- **TravelNU** — *JavaScript, React, Tailwind*, Sept–Oct 2024 — Team-of-four platform for browsing and rating study-abroad experiences, with Northeastern email authentication (Oasis Project Series)
- **Jordan Center Sign-In** — *JavaScript, React, Supabase*, June–Aug 2024 — Check-in system deployed at a high school, replacing paper logs with a PostgreSQL-backed schema supporting self-registration and role-based access
