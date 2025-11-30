[![GitHub followers](https://img.shields.io/github/followers/rolloerro?label=followers&style=flat-square)](https://github.com/rolloerro)
[![License](https://img.shields.io/github/license/rolloerro?style=flat-square)]


# 👨‍⚕️ Vladimir Kopylov
**Medical Full‑Stack Developer · AI/ML Engineer · Emergency Medicine Engineering**


Founder of **Digital WM Core** — clinical AI tools, emergency medicine algorithms, and cloud-native microservices for medical applications.


---


## Mission


Bring clinical algorithms and emergency protocols into reliable, auditable digital tools that help clinicians and patients in time‑critical situations.


---


## Digital WM Core — System Overview


**FDT (Photodynamic Therapy Tools)** · Clinical calculators, session planning, simulation modules.


**EMS (Emergency & Disaster Medicine)** · Rapid decision support, protocol quick-reference, triage helpers.


**PANIC (Mental Health & Panic Aid)** · Offline-capable assistants and mobile apps for panic stabilization techniques and guided self-help.


---


## Key Projects (selected)


- **Panic Helper (iOS, SwiftUI)** — Clinical-grade self-help app for panic stabilization and guidance.
- **EMS Stepspeed** — Decision flow for emergency responders: anaphylaxis, seizures, hypoglycemia, trauma.
- **FDT Clinical Assistant** — Dose/time calculators and session planners for photodynamic therapy.
- **Universal REST Template** — Production-ready microservice templates (Rust / Kotlin / Node).
- **MedKey Auth Service** — Centralized authentication & API key management for the platform.


---


## Architecture (high level)


- API Gateway → Auth Service → Microservices (FDT, EMS, PANIC) → Worker / Task Queue → Storage / Metrics
- ML/AI modules run as isolated services, serve predictions via secure APIs.

- 🏷 Бейджи Cloud Native
<p align="left"> <img src="https://img.shields.io/badge/Kubernetes-Ready-blue?style=for-the-badge&logo=kubernetes" /> <img src="https://img.shields.io/badge/Prometheus-Metrics-orange?style=for-the-badge&logo=prometheus" /> <img src="https://img.shields.io/badge/Docker-Compose-blue?style=for-the-badge&logo=docker" /> <img src="https://img.shields.io/badge/Rust-Workers-orange?style=for-the-badge&logo=rust" /> <img src="https://img.shields.io/badge/CI/CD-GitHub_Actions-black?style=for-the-badge&logo=githubactions" /> </p>


(See `architecture_diagram.png` for a visual overview.)


---


## Tech Stack


**Backend:** Node.js, Rust, Kotlin, PostgreSQL, Redis, MinIO


**Mobile / Frontend:** SwiftUI, TypeScript, React, Next.js


**Infra:** Docker, Kubernetes, Prometheus, Grafana, CI/CD


**AI:** OpenAI API, LangChain, custom ML utilities


---


## How I work


- Production‑mindset: observability, CI/CD, secure defaults
- Clinical safety first: reproducible results, audit logs, versioned clinical rules
- Small, testable services: each microservice is self‑contained and deployable


---


## Contact


- GitHub: https://github.com/rolloerro
- Telegram: @MSL72Rph


---


*If you landed here and want to collaborate — open an issue or ping me on Telegram.*
