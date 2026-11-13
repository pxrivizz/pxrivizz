<div align="center">

![banner](https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=220&section=header&text=Halil%20%C3%87ift%C3%A7i&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20Systems%20%26%20Software%20Engineer&descSize=20&descAlignY=62&descAlign=50)

[![Typing](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=19&pause=1000&color=00D4FF&center=true&vCenter=true&width=750&lines=Information+Systems+Engineering+%40+MSKU;Production-Grade+AI+%26+Distributed+Backends;Full-Stack+Architectures+%7C+Next.js%2C+FastAPI%2C+PostgreSQL;66-Week+AI+Systems+Engineer+Roadmap+in+Execution)](https://git.io/typing-svg)

<br/>

<p align="center">
  <a href="https://dersdevam.com.tr"><img src="https://img.shields.io/badge/Live_System-DersDevam.com.tr-00d4ff?style=flat-square&logo=googlechrome&logoColor=white" alt="Live System"></a>
  <a href="https://github.com/pxrivizz"><img src="https://img.shields.io/badge/GitHub-pxrivizz-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="mailto:halilciftci39@gmail.com"><img src="https://img.shields.io/badge/Email-halilciftci39%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

</div>

---

### 👨‍💻 About Me

Hi, I'm Halil. I study **Information Systems Engineering** at Muğla Sıtkı Koçman University.

I design and build software meant to survive real-world production constraints. Instead of populating my profile with disposable code snippets or toy clones, my focus is on **shipping reliable, end-to-end systems** — from zero-leak attendance platforms deployed in higher education to applied retrieval systems (RAG), high-throughput backend APIs, and hardware robotics.

**Engineering Philosophy:**
- **Production-first architecture:** Zero-trust security boundaries, database indexing, edge-case failure modes, and deployment reality take precedence over quick hacks.
- **AI as an engineering multiplier:** I utilize AI coding agents to accelerate test coverage, eliminate boilerplate, and catch code bloat — but system architecture, data contracts, security perimeters, and line-by-line verification remain strictly human-driven.
- **Full-lifecycle depth:** Comfortable moving from low-level Linux environments and hardware kinematics up to modern cloud backends and responsive user interfaces.

---

### 🚀 Production Systems & Featured Projects

| System | Role & Scope | Architecture & Stack | Links |
| :--- | :--- | :--- | :---: |
| **DersDevam** <br>*(Live University Attendance System)* | **Lead & Solo Developer**<br>Replaced paper signatures and vulnerable static QR codes with a zero-leak verification system. Implements **30-second cryptographic rotating tokens**, GPS geofencing, campus IP/subnet validation, automated Excel roster imports, and role-based instructor portals under strict privacy rules. | `Next.js` `TypeScript` `Prisma` `PostgreSQL` `Auth.js` `Tailwind CSS` `Docker` | [🌐 Live Platform](https://dersdevam.com.tr) • [💻 Repo](https://github.com/pxrivizz/qr_yoklama) |
| **Guest Account Registration** <br>*(Moodle 4.5+ Plugin)* | **Backend / LMS Plugin Developer**<br>Custom institutional LMS extension enabling staff to provision temporary guest accounts under a Least-Privilege RBAC model. Features automated account suspension via scheduled cron tasks, background email delivery queues, and CLI preflight checks without touching Moodle core files. | `PHP` `Moodle APIs` `MySQL/PostgreSQL` `PHPUnit` `Mustache` | [💻 Repo](https://github.com/pxrivizz/guestregister) |
| **Smart Food & Nutrition Assistant** <br>*(TÜBİTAK 2209-A Research Project)* | **AI & System Architecture**<br>Domain-specific multimodal assistant combining computer vision with a hybrid RAG pipeline. Blends dense semantic vector retrieval with deterministic rule verification for personalized dietary evaluation. | `Python` `FastAPI` `LangChain / LlamaIndex` `ChromaDB` `HuggingFace` | 🔒 *Academic R&D* |
| **Interactive Hexapod Platform** <br>*(Embedded Systems & Robotics)* | **Embedded Systems Developer**<br>Custom 6-legged robot powered by a Raspberry Pi. Implements real-time inverse kinematics for dynamic gait generation, voice interaction, and hardware sensor telemetry. | `Python` `Raspberry Pi` `Inverse Kinematics` `Speech API` `IoT` | 🛠️ *Hardware Lab* |

---

### 🏛️ Engineering Principles & System Design

```
        ┌─────────────────────────────────────────────────────────────┐
        │                 PRODUCTION SYSTEM BACKBONE                  │
        └──────────────────────────────┬──────────────────────────────┘
                                       │
            ┌──────────────────────────┼──────────────────────────┐
            ▼                          ▼                          ▼
   [ Zero-Trust Security ]    [ Rigorous Evaluations ]   [ High-Throughput APIs ]
   • Ephemeral QR tokens      • Faithfulness & Recall    • Async Python (asyncio)
   • Least-privilege RBAC     • Golden dataset testing   • Schema-driven validation
   • KVKK/PII compliance      • Langfuse observability   • Containerized CI/CD
```

- **Zero-Trust Security & Privacy:** In systems like *DersDevam* and *Moodle GuestRegister*, access is strictly scoped. Tokens rotate on 30-second cryptographic intervals to eliminate screenshot sharing, and background cron jobs enforce automated account suspension.
- **Deterministic Evals over Vibes:** When working with LLM and RAG pipelines, responses must be measurable. Systems are evaluated against synthetic/golden benchmarks using automated metrics (faithfulness, answer relevance, context recall) before production deployment.
- **Predictable Performance:** Backend services are architected around asynchronous event loops (`asyncio`, `FastAPI`), strongly-typed data validation (`Pydantic v2`), and optimized database query plans (`PostgreSQL`, `EXPLAIN ANALYZE`).

---

### 🎯 Continuous Focus: 66-Week AI Systems Roadmap

My technical routine is grounded in a rigorous, 66-week professional specialization roadmap designed to bridge the gap between applied machine learning theory and large-scale production engineering:

```
[Phase 0: Engineering Foundation] ──► [Phase 1: Math & ML from Scratch] ──► [Phase 2: Classical ML & Tabular]
                                                                                        │
[Phase 5: Transformer Internals]  ◄── [Phase 4: Deep Learning & CV]    ◄── [Phase 3: Production RAG v0]
         │
         └──► [Phase 6: Advanced Hybrid RAG] ──► [Phase 7: Serving & vLLM] ──► [Phase 8: Autonomous Agents]
```

- **Core Foundations:** Deriving algorithms from first principles (linear algebra, multivariate calculus, optimization) and implementing them in pure `NumPy` before touching frameworks.
- **Modern Information Retrieval:** Moving beyond naive RAG into hybrid search (Dense + BM25 / RRF), cross-encoder rerankers (`BGE`), chunking strategies, and `pgvector` indexing.
- **Inference & Agentic Orchestration:** Optimizing model serving (quantization, continuous batching, vLLM) and building human-in-the-loop decision-support agents with state machines and tool calling.

---

<div align="center">
  <p><i>"Talk is cheap. Show me the code and the production metrics."</i></p>
  <sub>Muğla Sıtkı Koçman University • Information Systems Engineering</sub>
</div>
