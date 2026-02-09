# KWeaver

[中文](README.zh.md) | English

[![GitHub stars](https://img.shields.io/github/stars/kweaver-ai/kweaver?style=social)](https://github.com/kweaver-ai/kweaver)

> ⭐ **If you like KWeaver, please [star us](https://github.com/kweaver-ai/kweaver)!** Your support helps us grow and improve.

KWeaver is an open-source ecosystem for building, deploying, and running decision intelligence AI applications. This ecosystem adopts ontology as the core methodology for business knowledge networks, with DIP as the core platform, aiming to provide elastic, agile, and reliable enterprise-grade decision intelligence to further unleash everyone's productivity.

The DIP platform includes key subsystems such as ADP, Decision Agent, DIP Studio, and AI Store.

## 🏗️ Architecture

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

### 🧩 Subsystems

Core Subsystems:

| Sub-project | Description | Repository |
| --- | --- | --- |
| **KWeaver** | Overall project architecture, documentation, tools and scripts | [kweaver-ai/kweaver](https://github.com/kweaver-ai/kweaver) |
| **AI Store** | AI application and component marketplace | [kweaver-ai/ai-store](https://github.com/kweaver-ai/ai-store) |
| **DIP Studio** | DIP Studio - Visual development and management interface | [kweaver-ai/studio](https://github.com/kweaver-ai/studio) |
| **Decision Agent** | Intelligent decision agent | [kweaver-ai/decision-agent](https://github.com/kweaver-ai/decision-agent) |
| **ADP** | AI Data Platform - Core development framework, including Ontology Engine, Execution Factory, ContextLoader, and VEGA data virtualization engine | [kweaver-ai/adp](https://github.com/kweaver-ai/adp) |

Key Infrastructures:

| Sub-project | Description | Repository |
| --- | --- | --- |
| **Sandbox** | Sandbox runtime environment | [kweaver-ai/sandbox](https://github.com/kweaver-ai/sandbox) |

---

More components will be open-sourced in the future. Stay tuned!
