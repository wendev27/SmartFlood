# 🌊 SmartFlood

### AI-Powered Flood Relief Allocation & Disaster Response Platform

**SmartFlood** is an evolving disaster-response platform developed through
multiple iterations of experimentation, system redesign, AI research,
IoT integration, cloud deployment, and DevSecOps learning.

This repository serves as the **canonical index and engineering history of the
SmartFlood ecosystem**, documenting the evolution of the project and linking
its individual implementations, experiments, and major releases.

> **One project. Multiple generations. Continuous engineering evolution.**

---

# 🧬 SmartFlood Evolution

```text
V1 → V2 → V3 → V4 → V4.1 → V5 → AWS
```

Each generation represents a different stage of SmartFlood's development,
from early experimentation to increasingly structured engineering,
cloud deployment, and future AWS infrastructure.

---

# 📌 Version Overview

| Version | Focus | Deployment | Status |
|---|---|---|---|
| **V1** | Initial prototype & ecosystem | Early deployment experiments | 🗄️ Archived |
| **V2** | Second-generation platform | Vercel / Railway / Render | 🗄️ Archived |
| **V3** | Integrated full-stack platform | Vercel / Heroku | 🗄️ Archived |
| **V4** | Cloud-deployed Capstone 2 system | Google Cloud Run | 🟢 Complete |
| **V4.1** | Complete frontend design evolution | Vercel | 🟢 Complete |
| **V5** | Personal AWS & cloud-engineering challenge | AWS | 🚧 Active |

---

# 🧪 V1 — Initial Prototype

V1 was the beginning of the SmartFlood ecosystem.

This generation focused on exploring the initial frontend architecture,
user workflows, disaster-response concepts, sensor simulation, and early
AI experimentation.

The V1 implementation was distributed across several repositories.

## V1 Repositories

| Repository | Purpose |
|---|---|
| [SmartFlood-V1-Admin](https://github.com/wendev27/SmartFlood-V1-Admin) | Administrative dashboard for monitoring floods, managing relief operations, and overseeing the SmartFlood ecosystem. |
| [SmartFlood-V1-Barangay](https://github.com/wendev27/SmartFlood-V1-Barangay) | Barangay portal for reporting incidents, monitoring local flood conditions, and coordinating emergency response. |
| [SmartFlood-V1-Landing-Page](https://github.com/wendev27/SmartFlood-V1-Landing-Page) | Initial SmartFlood landing page and platform entry point. |
| [SmartFlood-V1-Simulator](https://github.com/wendev27/SmartFlood-V1-Simulator) | Early internal simulator for generating sensor data and testing SmartFlood monitoring functionality. |
| [SmartFlood-V1-Web3DonationTesting](https://github.com/wendev27/SmartFlood-V1-Web3DonationTesting) | Experimental blockchain-based donation module exploring transparent disaster-relief contributions. |
| [SmartFlood-V1-nodeployment](https://github.com/wendev27/SmartFlood-V1-nodeployment) | Early SmartFlood implementation that was not deployed. |
| [SmartFlood-V1-MockSensorData-Simulator](https://github.com/wendev27/SmartFlood-V1-MockSensorData-Simulator) | Mock IoT sensor simulator developed before physical ESP32 sensor integration. |

## V1 Engineering Notes

V1 was primarily an **exploration and prototyping phase**.

The architecture was still being discovered, multiple approaches were tested,
and some implementations were eventually abandoned or replaced.

Some historical V1 repositories may no longer run with modern dependencies or
environments. They are preserved here as part of the project's development
history.

---

# 🔄 V2 — Second Generation

V2 represented a significant step forward from the initial prototype.

The frontend was consolidated into a more structured repository architecture
while the deployment model went through several iterations.

## V2 Repository

| Repository | Purpose |
|---|---|
| [SmartFlood-V2](https://github.com/wendev27/SmartFlood-V2) | Second-generation SmartFlood platform introducing improved monitoring features, application architecture, and disaster-response workflows. |

## Deployment Evolution

```text
Frontend
   ↓
Vercel

Backend / Application
   ↓
Railway
   ↓
Render
```

V2 provided practical experience with application deployment and revealed
architectural limitations that motivated the redesign that followed.

---

# 🚀 V3 — Integrated Full-Stack Platform

V3 became a major turning point in the SmartFlood project.

The platform evolved into a more integrated full-stack system incorporating:

- Near-real-time monitoring
- Disaster-management workflows
- AI-assisted relief allocation
- Sensor data
- Interactive dashboards

## Core Repository

| Repository | Purpose |
|---|---|
| [SmartFlood-V3](https://github.com/wendev27/SmartFlood-V3) | Full-stack SmartFlood platform integrating near-real-time monitoring, AI-assisted relief allocation, interactive dashboards, and disaster-management functionality. |

## Supporting V3 Research & IoT Repositories

| Repository | Purpose |
|---|---|
| [SmartFlood-V3-ArduinoSensorWebSerial](https://github.com/wendev27/SmartFlood-V3-ArduinoSensorWebSerial) | ESP32 flood-sensor integration, Web Serial communication, device configuration, and real-time monitoring. |
| [SmartFlood-V3-Human-In-The-Loop-AI](https://github.com/wendev27/SmartFlood-V3-Human-In-The-Loop-AI) | Human-in-the-loop AI research using AHP and Fuzzy Logic for disaster-relief prioritization and decision support. |

## Deployment

```text
SmartFlood V3
│
├── Frontend / Full-Stack Application
│       ↓
│     Vercel
│
└── AI Service
        ↓
      Heroku
```

## 🛠️ V3 — Engineering Maturity

V3 was also an important turning point in the project's **engineering
workflow**.

Earlier generations were primarily focused on experimentation and rapid
prototyping.

Beginning with V3, development became increasingly structured around:

- More intentional Git commits
- Improved pull request practices
- Code review
- Better branch organization
- More deliberate architecture decisions
- Stronger documentation
- More systematic debugging and validation

The project began moving from:

> **"Can we make this work?"**

toward:

> **"How should we engineer this properly?"**

This improvement in engineering discipline became one of the most important
outcomes of the V3 generation.

---

# ☁️ V4 — Cloud-Deployed Capstone 2

V4 represents the cloud-deployed evolution of SmartFlood and the system
prepared for **Capstone 2**.

The architecture moved beyond the previous deployment model and introduced
independently deployed services.

## V4 Architecture

```text
                     SmartFlood V4
                          │
                   ┌──────┴──────┐
                   │             │
               Frontend       Backend
                   │             │
                Vercel     Google Cloud Run
                                │
                         ┌──────┴──────┐
                         │             │
                      Backend          AI
                      Service        Service
                         │             │
                         └──────┬──────┘
                                │
                           Data Services
```

## V4 Repository

| Repository | Purpose |
|---|---|
| [SmartFlood-V4](https://github.com/wendev27/SmartFlood-V4) | Main V4 SmartFlood implementation and cloud-deployed Capstone 2 system. |

## Deployment

| Component | Platform |
|---|---|
| **Frontend** | Vercel |
| **Backend API** | Google Cloud Run |
| **AI Service** | Google Cloud Run |

The backend and AI services are independently deployed, providing a more
modular cloud architecture.

## Status

**🟢 Complete and ready for Capstone 2 presentation.**

---

# 🎨 V4.1 — Frontend Design Evolution

V4.1 focuses on the **complete frontend design and web experience** of
SmartFlood.

It builds upon the system established in V4 while developing a more complete
and cohesive user-facing interface.

## V4.1 Repository

| Repository | Purpose |
|---|---|
| [SmartFlood-V4.1](https://github.com/wendev27/SmartFlood-V4.1) | Complete SmartFlood frontend design and web experience. |

## Deployment

**Frontend**

→ Vercel

## Status

**🟢 Complete**

---

# ☁️ V5 — AWS Engineering Challenge

V5 represents a new chapter in the SmartFlood project.

Unlike previous generations, V5 is **not part of the academic Capstone
implementation**.

It is a **self-directed personal engineering challenge** created to explore
AWS and deepen practical knowledge of cloud infrastructure, networking,
security, automation, and DevSecOps.

Rather than learning AWS through isolated tutorials, SmartFlood will be used
as a realistic application and engineering laboratory.

## 🎯 Objective

The goal of V5 is not simply to **deploy SmartFlood on AWS**.

The goal is to answer:

> **"Can I design, deploy, secure, automate, observe, and operate a real
> application using AWS infrastructure?"**

SmartFlood provides the application.

AWS provides the engineering environment.

---

## 🧪 V5 as a Personal Cloud Laboratory

V5 will be used to experiment with:

- AWS fundamentals
- IAM
- VPC and networking
- Compute
- Containers
- Managed databases
- Object storage
- Load balancing
- CI/CD
- Infrastructure as Code
- Monitoring and observability
- Secrets management
- Security
- DevSecOps
- Cost management

The architecture may change throughout the experiment as new AWS concepts
are learned and evaluated.

---

## 🏗️ Engineering Approach

V5 will intentionally evolve through multiple infrastructure iterations.

```text
Local Development
       ↓
Containerized Application
       ↓
AWS Compute
       ↓
AWS Networking
       ↓
Managed AWS Services
       ↓
Infrastructure as Code
       ↓
CI/CD Automation
       ↓
Observability
       ↓
Security & DevSecOps
```

The objective is to understand **why** each architectural decision is made,
not simply to reproduce a tutorial.

---

## 📦 V5 Repository

| Repository | Purpose |
|---|---|
| [SmartFlood-V5](https://github.com/wendev27/SmartFlood-V5) | Personal AWS engineering challenge and cloud-infrastructure laboratory built around SmartFlood. |

---

## 🧭 V5 Philosophy

> **V5 is a personal engineering challenge, not another capstone version.**

> SmartFlood is the laboratory. AWS is the environment.  
> The objective is to learn how to engineer, secure, automate, and operate
> cloud infrastructure.

---

## 🚧 Status

**🚧 Active Learning / Personal Engineering Challenge**

---

# 📈 Engineering Journey

The SmartFlood project has evolved in two dimensions.

## System Evolution

```text
Prototype
   ↓
Integrated Platform
   ↓
Cloud Deployment
   ↓
Independent Services
   ↓
AWS Engineering
```

## Engineering Process Evolution

```text
Rapid Experimentation
        ↓
Structured Development
        ↓
Code Review
        ↓
Architecture Decisions
        ↓
Cloud Engineering
        ↓
DevSecOps
```

The project therefore documents not only the evolution of the software,
but also the evolution of the development practices used to build it.

---

# 🧪 Experiments Are Part of the History

Not every SmartFlood experiment became part of the final architecture.

The project explored:

- IoT sensors
- ESP32
- Web Serial
- Sensor simulation
- Human-in-the-loop AI
- AHP
- Fuzzy Logic
- Blockchain donation concepts
- Multiple frontend architectures
- Multiple backend architectures
- Multiple deployment platforms
- Cloud-native services

Some experiments were successful.

Some were replaced.

Some were abandoned.

Some implementations may no longer run in their original environment.

These are intentionally preserved as **historical engineering artifacts**,
because they document the decisions and experiments that shaped later versions
of SmartFlood.

---

# 🧭 Current State

## 🟢 Completed

- V3.3 / Capstone implementation
- V4 cloud deployment
- V4.1 frontend design

## 🚧 Future

- V5 AWS exploration
- Infrastructure as Code
- Cloud security
- Advanced observability
- DevSecOps automation
- Production-oriented AWS architecture

---

# 🎯 Long-Term Direction

SmartFlood began as an academic prototype and has evolved into a
long-running engineering project spanning:

**Frontend → Backend → AI → IoT → Cloud → DevSecOps**

The goal of future iterations is not simply to add more features.

Instead, each iteration is intended to explore deeper engineering questions:

- How should the system be architected?
- How should services communicate?
- How should applications be deployed?
- How should infrastructure be secured?
- How should deployments be automated?
- How should failures be detected?
- How should the system scale?
- How should cloud resources be managed?
- How should infrastructure be reproduced?

SmartFlood will continue evolving as these questions are explored.

---

# 🌊 From Prototype to Cloud

SmartFlood represents an ongoing engineering journey.

It started with experimentation and gradually evolved into an integrated
platform, a cloud-deployed capstone system, and eventually a personal AWS
engineering laboratory.

The goal is not to claim that every iteration was perfect.

The goal is to document how each iteration contributed to the next.

> **V1 — Explore.**
>
> **V2 — Improve.**
>
> **V3 — Integrate.**
>
> **V4 — Deploy.**
>
> **V4.1 — Refine.**
>
> **V5 — Challenge.**

**SmartFlood — continuously evolving.**
