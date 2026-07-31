<h1 align="center">Kazi Md. Tawsif Rahman</h1>

<p align="center">
  <strong>Backend Software Engineer · Java & Spring Boot · Applied Security & Privacy Research</strong>
</p>

<p align="center">
  I build reliable workflow-heavy backend systems and conduct reproducible research on privacy leakage in machine-learning-based network intrusion detection.
</p>

<p align="center">
  <a href="https://research.tawsifrahman.flaro-tech.com">Academic Portfolio</a> ·
  <a href="https://github.com/tawsif113/Portfolio-v1">Professional Portfolio</a> ·
  <a href="mailto:tawsifcse113@gmail.com">Email</a>
</p>

---

## About

I am a backend software engineer based in Bangladesh, working primarily with Java, Spring Boot, PostgreSQL, Redis, RabbitMQ, and MongoDB. My engineering interests center on dependable business workflows, event-driven systems, data correctness, and maintainable service boundaries.

Alongside software engineering, I am developing a reproducible privacy–utility audit for ML-based network intrusion detection. The study evaluates membership-inference risk and formally accounted DP-SGD while treating Recall and False Negative Rate as first-class IDS outcomes.

## Current focus

- Designing modular backend services with explicit validation, idempotency, audit trails, and failure handling
- Deepening distributed-systems, system-design, and application-security knowledge
- Completing the formal DP-SGD privacy-budget sweep and per-model membership-inference audit
- Preparing for research-oriented graduate study in privacy, security, and trustworthy machine learning

## Selected work

| Project | What it demonstrates | Stack / methods |
|---|---|---|
| [Privacy–Utility Auditing of DP-SGD for IDS](https://github.com/tawsif113/privacy-utility-dp-ids) | Locked experimental protocol, shadow-calibrated MIA, explicit privacy accounting, reproducible evidence | Python, PyTorch, Opacus, scikit-learn |
| [Spring Saga Orchestrator](https://github.com/tawsif113/spring-saga-orchestrator) | Distributed workflow coordination and compensating actions | Java, Spring Boot, event-driven architecture |
| [NotifyFlow](https://github.com/tawsif113/NotifyFlow-Notification-Latency-Simulator) | Notification delivery, asynchronous processing, and latency-oriented experimentation | Spring Boot, RabbitMQ, Web Push |
| [Academic Portfolio](https://github.com/tawsif113/Academic-Portfolio) | Research, publications, CV, and evidence-aligned academic narrative | TypeScript, Vite |
| [Professional Portfolio](https://github.com/tawsif113/Portfolio-v1) | Backend case studies and professional experience | HTML, CSS |

## Research snapshot

My current project asks:

> How does formally accounted DP-SGD affect IDS utility—particularly Recall and FNR—and measurable membership leakage under score-only and label-aware attacks?

Verified milestones:

- Locked NSL-KDD target-train, target-validation, and shadow-pool protocol
- Five-shadow baseline membership-inference audit completed
- Strongest evaluated baseline attack near chance at approximately 0.5029 ROC-AUC
- Opacus DP-SGD feasibility established at epsilon 7.9986 and delta 1.134 × 10^-5
- Full privacy-budget sweep and DP-model MIA evaluation currently in progress

The feasibility result is not presented as a final privacy–utility conclusion or as evidence that DP-SGD has reduced leakage.

## Publications

1. **An Automated System for Detecting Property Insurance Fraud Using Machine Learning.** International Journal of Mathematical Sciences and Computing, 2024. [Publisher and DOI](https://www.mecs-press.org/ijmsc/ijmsc-v10-n3/v10n3-2.html)

2. **Whistle Blower: An Insurance Awareness Mobile Application with Insurance Policy Selection, Fraud Detection, Critical Help, Complaint Features.** IEEE CSITSS, 2024. [IEEE record](https://ieeexplore.ieee.org/document/10817002/)

## Core technologies

**Backend:** Java, Spring Boot, Spring Security, Spring Data JPA, Hibernate, REST APIs  
**Data and messaging:** PostgreSQL, Redis, MongoDB, RabbitMQ, Flyway  
**Architecture:** DDD, CQRS, event-driven services, modular monoliths, microservices  
**Research:** Python, PyTorch, Opacus, scikit-learn, XGBoost  
**Engineering:** Docker, Git, Linux, JUnit, Mockito

## Engineering principles

- Prefer explicit behavior over hidden magic
- Design for correctness before scale
- Treat business workflows and failure paths as first-class concerns
- Keep research claims proportional to committed evidence
- Build systems and experiments that another person can inspect and reproduce

---

<p align="center">
  <i>Building dependable software and defensible empirical evidence.</i>
</p>
