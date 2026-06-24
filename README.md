# Sandeep Kumar

**Software Engineer — Backend & Distributed Systems · Full-Stack (MERN / FastAPI)**

📍 Chennai, India &nbsp;·&nbsp; 🌐 [Portfolio](https://sandeep-portfolio-xi-ashen.vercel.app/) &nbsp;·&nbsp; 💼 [LinkedIn](https://linkedin.com/in/sandeep-kumar-b7a8012bb) &nbsp;·&nbsp; 📧 snxd2047@gmail.com

---

## About

Computer Science Engineering student building scalable backend systems and full-stack AI applications. I'm drawn to the parts of software that are hard to fake — request scheduling, concurrency, backpressure, fault tolerance, and clean system design — and I build projects that exercise them end to end. Currently going deep on distributed systems and high-performance backends while sharpening DSA for software engineering interviews.

**Focus:** Distributed systems · Backend architecture · Full-stack (MERN / FastAPI) · AI-integrated applications · System design

---

## Tech Stack

**Languages:** Python · Java · C++ · C · JavaScript · SQL
**Backend & Systems:** FastAPI · Node.js · Express.js · REST APIs · async I/O · Server-Sent Events · Redis · Docker · Celery · Prometheus
**Frontend:** React.js · Vite · HTML5 · CSS3
**Databases:** MongoDB · PostgreSQL · SQLite · SQLAlchemy
**Core CS:** Data Structures & Algorithms · OOP · DBMS · Operating Systems · Computer Networks · System Design
**Practices:** Git · Agile · Requirement analysis · Testing

---

## Featured Projects

### ⚙️ [MiniServe — High-Throughput LLM Inference Server](https://github.com/Sandeep-X47/miniserve-llm-inference-server)
A miniature of production serving systems (vLLM-style): a request queue, a dynamic-batching scheduler with **continuous (iteration-level) batching**, token streaming over SSE, backpressure, priority tiers, and a live React ops console.

- Continuous-batching scheduler that admits queued requests and evicts finished sequences every decode step — the engine never idles
- Async FastAPI + Server-Sent Events pipeline streaming tokens individually, fronted by a bounded priority queue (HTTP 429 on overflow)
- Pluggable engine interface: scheduler simulator **and** a real HuggingFace causal LM with a KV cache
- Prometheus metrics + live telemetry console surfacing batch occupancy, queue depth, and tokens/sec

`Python · FastAPI · React · Docker · Prometheus`

### 🤖 [AI Communication Copilot — Full-Stack AI Assistant](https://github.com/Sandeep-X47/ai-communication-copilot)
A full-stack communication assistant with five generation modules, authentication, caching, and a graceful-degradation layer that runs with zero external services.

- Stateless JWT auth, bcrypt password hashing, and strict per-user data scoping (server-side isolation)
- Redis-backed caching, per-user rate limiting, and analytics that fall back to in-memory equivalents with **zero code changes** when Redis is absent
- Provider-agnostic, OpenAI-compatible LLM client with an offline deterministic mock — the whole product is demoable without an API key
- Hardened API: Pydantic validation, security response headers, CORS origin restriction

`FastAPI · React · JWT · Redis · PostgreSQL · SQLAlchemy`

### 👥 [DevHub — Collaborative Development Workspace](https://github.com/dhirajsrinivas/workos-backend) &nbsp;*(team project)*
A MERN platform for real-time developer collaboration: integrated code editor, team messaging, role-based authentication, and project/task management.

- Built RESTful APIs and optimized database queries, reducing API response time by ~35%
- Real-time collaboration workflows with role-based access control

`MongoDB · Express · React · Node.js`

### 💈 [AI Hair & Facial Analysis Platform](https://github.com/Praveen-Mariappasamy/Hairstyle-Predictor) &nbsp;*(team project)*
A computer-vision grooming recommendation system: multi-angle facial analysis, hairstyle and beard recommendation, and AI barber-instruction generation.

`Python · Computer Vision · AI/ML`

---

## Engineering Experience — Virtual Job Simulations (Forage)

- **JPMorgan Chase — Software Engineering:** Kafka-driven transaction-processing service in Java 17 / Spring Boot with Spring Data JPA and an embedded-Kafka integration test harness
- **Citi — Technology Software Development:** Fault-tolerant Java market-data poller (JDK HTTP client) feeding a Python (pandas/matplotlib) visualization pipeline

---

## Achievements

- 🥇 **Smart India Hackathon 2025** — College Final Round qualifier
- 🧠 **600+ DSA problems** solved across LeetCode and other platforms
- 🔥 **LeetCode 50-Day Coding Badge**

---

## Education

**B.Tech, Computer Science Engineering** — SRM Institute of Science and Technology, Chennai
Expected May 2028 · CGPA 8.95 / 10.0

---

> Build systems that solve real problems. Optimize for learning, execution, and long-term engineering mastery.
