# KWeaver

[中文](README.zh.md) | English

[![GitHub stars](https://img.shields.io/github/stars/kweaver-ai/kweaver?style=social)](https://github.com/kweaver-ai/kweaver)

> ⭐ **If you find KWeaver helpful, please give us a star!** Your support helps us grow and improve.

KWeaver is an open-source ecosystem for building, deploying, and running decision intelligence AI applications. This ecosystem adopts ontology as the core methodology for business knowledge networks, with DIP as the core platform, aiming to provide elastic, agile, and reliable enterprise-grade decision intelligence to further unleash everyone's productivity.

The DIP platform includes key subsystems such as ADP, Decision Agent, DIP Studio, and AI Store.

## 🏗️ Platform Architecture

    ┌────────────────────────────────────┐
    │          DIP Platform              │
    │ ┌────────────────────────────────┐ │
    │ │          AI Store              │ │
    │ ├────────────────────────────────┤ │
    │ │         DIP Studio             │ │
    │ ├────────────────────────────────┤ │
    │ │       Decision Agent           │ │
    │ ├────────────────────────────────┤ │
    │ │            ADP                 │ │
    │ └────────────────────────────────┘ │
    └────────────────────────────────────┘

### 🧩 Core Subsystems

| Sub-project | Description | Repository |
| --- | --- | --- |
| **KWeaver** | Overall project architecture, documentation, tools and scripts | [kweaver-ai/kweaver](https://github.com/kweaver-ai/kweaver) |
| **DIP** | Decision Intelligence Platform (DIP) | [kweaver-ai/dip](https://github.com/kweaver-ai/dip) |
| **AI Store** | AI application and component marketplace | *Coming soon* |
| **Studio** | DIP Studio - Visual development and management interface | [kweaver-ai/studio](https://github.com/kweaver-ai/studio) |
| **Decision Agent** | Intelligent decision agent | [kweaver-ai/data-agent](https://github.com/kweaver-ai/data-agent) |
| **ADP** | AI Data Platform - Core development framework, including Ontology Engine, ContextLoader, and VEGA data virtualization engine | [kweaver-ai/adp](https://github.com/kweaver-ai/adp) |
| **Operator Hub** | Operator management and orchestration platform | [kweaver-ai/operator-hub](https://github.com/kweaver-ai/operator-hub) |
| **Sandbox** | Sandbox runtime environment | [kweaver-ai/sandbox](https://github.com/kweaver-ai/sandbox) |

---

More components will be open-sourced in the future. Stay tuned!
