# David Emmanuel Munyaka

**Backend Software Engineer | Python & Distributed Systems - Nairobi, Kenya**

I build resilient backend services, scalable REST APIs, and database architectures using Python, FastAPI, PostgreSQL, and Docker Compose. I focus on clean architecture, containerized deployments, and robust security patterns like JWT authentication and RBAC.

`Backend Engineering` `Microservices` `Database Architecture` `Docker` `API Design`

---

**About**

I am a Backend Software Engineer focused on building reliable distributed systems with Python, FastAPI and PostgreSQL.

I enjoy designing APIs, optimizing databases, automating infrastructure, and building production-ready backend services.

Currently exploring distributed systems, event-driven architecture, and scalable backend design.

---

**Current Focus**

* **Building:** Asynchronous distributed task queues with Redis brokers, worker concurrency, exponential backoff retries, and Dead-Letter Queue (DLQ) state persistence.
* **Learning:** Advanced Message Brokers (RabbitMQ/Kafka) and Event-Driven Architectural Patterns.
* **Maintaining:** Containerized PostgreSQL and FastAPI production templates.

---

**Projects**

**TaskPulse – Distributed Task Queue & Execution Engine**
* **Problem:** Synchronous API execution of long-running operations leads to latency spikes, timeout failures, and poor user experience.
* **Solution:** Engineered an asynchronous Producer-Broker-Worker task queue that offloads execution to Redis, processes jobs with background Python workers, and persists execution states in PostgreSQL.
* **Impact:** Eliminates API latency (<50ms response times), ensures system resilience via exponential backoff retries, and isolates unprocessable jobs via Dead-Letter Queue (DLQ) routing.
* **Stack:** Python · FastAPI · Redis · PostgreSQL · SQLAlchemy · Docker Compose · GitHub Actions
* **[Repository Link](https://github.com/demmanuel58-spec/taskpulse)**


**SysGuard: Enterprise Server Health & Incident Alerting Engine**
* **Problem:** Unmonitored server resource exhaustion (CPU spikes, memory leaks, and disk space limits) leads to sudden production crashes and silent service outages.
* **Solution:** Built a zero-dependency, modular POSIX monitoring sidecar that continuously inspects host metrics, captures diagnostic snapshots of offending process trees, and dispatches real-time webhook alerts.
* **Impact:** Prevents unexpected server downtime with kernel-level concurrency locking (`flock`), defensive error handling (`set -euo pipefail`), and native `systemd` background automation.
* **Stack:** Linux / POSIX Shell - Bash - Systemd - Curl - Webhooks (Slack/Discord)
* [Repository Link](https://github.com/demmanuel58-spec/sysguard)


**Campaign Management API**
* **Problem:** Marketing workflows require secure multi-role access control, soft deletion, and verifiable action tracking across complex campaigns.
* **Solution:** Developed a modular FastAPI backend utilizing SQLAlchemy, Alembic database migrations, and JWT authentication with fine-grained RBAC.
* **Impact:** Delivered 100% test-backed API coverage, sub-50ms query responses, and containerized zero-downtime deployments via Docker Compose.
* **Stack:** Python · FastAPI · PostgreSQL · SQLAlchemy · Alembic · Docker Compose · JWT
* [Repository Link](https://github.com/demmanuel58-spec/campaign-management-api) 


**High-Throughput PDF Manipulation Engine**
* **Problem:** Legacy PDF layout tools break vector graphics, custom borders, and embedded fonts during programmatic text modifications.
* **Solution:** Built an in-memory PDF manipulation pipeline leveraging PyMuPDF and ReportLab for precise coordinate targeting and vector layout preservation.
* **Impact:** Reduced batch layout rendering errors by 90% while maintaining target font styling.
* **Stack:** Python · PyMuPDF · ReportLab

---

**Architecture & Systems Experience**

* **Role-Based Access Control (RBAC):** Admin, Manager, and Developer role differentiation with route-level security guards.
* **Authentication:** JWT, OAuth2, and session-based auth integration.
* **Database Design:** Relational schema design, database indexing, and migration pipelines using PostgreSQL and Alembic.
* **Containerization & CI/CD:** Docker, Docker Compose multi-container orchestrations, and GitHub Actions automation.

---

**Technical Skills**

* **Languages & Frameworks:** Python, FastAPI, PostgreSQL, SQLAlchemy, Alembic
* **Tools & Infrastructure:** Docker, Docker Compose, Git, Linux/Unix Shell, Git CLI
* **Architectural Patterns:** Microservices, Event-Driven Architecture, MVC, Message Broker, Pipe-Filter

---

**Learning**

* Designing Data-Intensive Applications — Martin Kleppmann *(Active Reading)*
* Advanced Event-Driven Microservices & Message Queues

---

**Open Source & Collaboration**

I am open to contributing to:
* Open-source backend systems and API tooling
* Python web frameworks and async libraries
* Outreachy software engineering initiatives

---

**Connect**

* **GitHub:** [demmanuel58-spec](https://github.com/demmanuel58-spec)
* **LinkedIn:** [David Emmanuel Munyaka](https://linkedin.com/in/your-linkedin-handle)
* **X (Twitter):** [@David_E_Munyaka](https://x.com/David_E_Munyaka)

Open to remote backend roles, contract work, and engineering collaborations.


