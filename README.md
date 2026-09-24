<h1 align="center">Kazi Md. Tawsif Rahman</h1>

<p align="center">
  <strong>Backend Software Engineer · Java / Spring Boot · Distributed Systems · Security & Privacy Research</strong>
</p>

<p align="center">
  I build production-minded backend systems and reproducible empirical studies where correctness, failure handling, and evidence matter.
</p>

<p align="center">
  <a href="https://research.tawsifrahman.flaro-tech.com">Academic Portfolio</a> ·
  <a href="https://github.com/tawsif113">GitHub</a> ·
  <a href="mailto:tawsifcse113@gmail.com">Email</a>
</p>

---

## About me

I am a backend software engineer based in Bangladesh. My primary engineering stack is **Java 25, Spring Boot 4, Spring Security, PostgreSQL, Redis, RabbitMQ, MongoDB, Docker, and Gradle**.

I am most interested in backend problems that go beyond CRUD: **transaction boundaries, idempotency, concurrency, authorization, messaging reliability, observability, DDD/CQRS, and distributed workflows**.

Alongside software engineering, I work on reproducible research in **privacy-preserving machine learning, network security, and software-testing reliability**.

## Featured engineering work

| Project | What it demonstrates | Main stack |
|---|---|---|
| [Spring Boot Rescue Lab](https://github.com/tawsif113/spring-boot-rescue-lab) | Five production-style incidents repaired with measurable evidence: N+1 queries, duplicate retries, inventory races, broken object authorization, and lost events | Java 25, Spring Boot 4.1.1, PostgreSQL, RabbitMQ, Redis, Testcontainers, Prometheus |
| [Spring Saga Orchestrator](https://github.com/tawsif113/spring-saga-orchestrator) | Event-driven Saga coordination across order, inventory, and payment services with idempotency and compensation | Java 25, Spring Boot 4, RabbitMQ, MongoDB, Docker |
| [Academic Portfolio](https://github.com/tawsif113/Academic-Portfolio) | Research-first portfolio containing publications, CV, reproducible evidence, and systems work | TypeScript, Vite |
| [Loan Proposal Command Service](https://github.com/tanvir70/bits-loan-proposal-commnad) | Pinned collaborative codebase for a DDD-oriented loan-proposal command service | Java 25, Spring Boot 4, Gradle, bits-ddd |

### Spring Boot Rescue Lab — current flagship backend project

Instead of another greenfield CRUD application, the lab begins with a deliberately fragile order API and fixes failures that resemble real production incidents.

- **SQL performance:** pagination-safe fetching removes the N+1 pattern
- **Idempotency:** concurrent retries resolve to one business outcome
- **Concurrency:** atomic stock updates prevent overselling
- **Authorization:** ownership is enforced below the controller layer
- **Reliable messaging:** transactional outbox, confirms, retries, DLQ, and consumer deduplication
- **Operability:** correlation IDs, ECS JSON logs, Actuator health probes, Prometheus metrics, Grafana, CI, and Testcontainers

The repository preserves both the fragile baseline and the remediated implementation so the engineering decisions can be inspected rather than merely described.

## Research work

| Project | Research focus |
|---|---|
| [Privacy–Utility Auditing of DP-SGD for IDS](https://github.com/tawsif113/privacy-utility-dp-ids) | Formally accounted DP-SGD, intrusion-detection utility, and membership-inference auditing |
| [Persistent Cross-Execution State and Order-Dependent Tests](https://github.com/tawsif113/persistent-state-od-study) | How persistent process-external state changes iDFlakies detection and RankF polluter/state-setter ranking |

### Privacy–utility study

The DP-SGD study now contains the completed experimental roadmap for the core work:

- Five-seed **NSL-KDD** comparison of non-private, **ε≈4**, and **ε≈2** conditions
- Formal privacy accounting with **Opacus**
- IDS-specific evaluation including Recall, FNR, F1, FPR, and average precision
- Shadow-model membership-inference attacks with score-only and label-aware threat models
- Accepted final NSL-KDD analysis
- Supplementary single-seed **UNSW-NB15** external validation
- Venue-neutral paper draft frozen for author review and target-venue selection

The current evidence does **not** support claiming that DP-SGD reduced overall measured membership leakage or that ε≈4 is universally optimal. Formal differential privacy guarantees and empirical membership-inference measurements are reported separately.

### Order-dependent-test study

The persistent-state study examines how filesystem and other process-external state surviving between executions can change:

- brittle/order-dependent test outcomes,
- iDFlakies candidate generation and verification,
- final detector reporting, and
- RankF state-setter/polluter rankings.

The repository includes controlled experiments, manually validated real IDoFT cases, fixed test orders, provenance manifests, raw evidence, and deterministic analysis artifacts.

## Publications

1. **An Automated System for Detecting Property Insurance Fraud Using Machine Learning.**  
   *International Journal of Mathematical Sciences and Computing*, 2024.  
   [Publisher / DOI](https://www.mecs-press.org/ijmsc/ijmsc-v10-n3/v10n3-2.html)

2. **Whistle Blower: An Insurance Awareness Mobile Application with Insurance Policy Selection, Fraud Detection, Critical Help, Complaint Features.**  
   *IEEE CSITSS*, 2024.  
   [IEEE record](https://ieeexplore.ieee.org/document/10817002/)

## Technical toolbox

**Backend:** Java, Spring Boot, Spring Security, Spring Data JPA, Hibernate, REST APIs  
**Architecture:** DDD, CQRS, Saga, modular monoliths, microservices, event-driven systems, transactional outbox  
**Data:** PostgreSQL, MongoDB, Redis, Flyway  
**Messaging:** RabbitMQ, Kafka  
**Testing & reliability:** JUnit, Mockito, Testcontainers, idempotency, concurrency control, failure-path testing  
**Observability:** Spring Boot Actuator, Micrometer, Prometheus, Grafana, structured logging  
**Research:** Python, PyTorch, Opacus, scikit-learn, XGBoost  
**Engineering:** Docker, Docker Compose, GitHub Actions, Gradle, Linux

## How I approach engineering

- Make failure modes explicit rather than hiding them behind happy-path demos.
- Prefer measurable evidence over speculative optimization.
- Treat idempotency, authorization, concurrency, and transactions as design concerns.
- Use asynchronous messaging with explicit delivery semantics instead of pretending distributed systems provide exactly-once behavior for free.
- Keep research claims proportional to the evidence actually produced.
- Build systems and experiments another engineer or researcher can inspect and reproduce.

---

<p align="center">
  <strong>Backend systems that survive failure. Research claims that survive scrutiny.</strong>
</p>
