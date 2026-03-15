# KWeaver

[中文](README.zh.md) | English

[License](LICENSE.txt)

KWeaver is an open-source ecosystem for building, deploying, and running decision intelligence AI applications. This ecosystem adopts business knowledge network (Business Knowledge Network) as its core methodology, aiming to provide elastic, agile, and reliable enterprise-grade decision intelligence to further unleash everyone's productivity.

The KWeaver project includes KWeaver Core and KWeaver DIP.

## Platform Architecture

```text
┌─────────────────────────────────────────────┐
│                 KWeaver                     │
│  ┌───────────────────────────────────────┐  │
│  │           KWeaver DIP                 │  │
│  ├───────────────────────────────────────┤  │
│  │           KWeaver Core                │  │
│  └───────────────────────────────────────┘  │
└─────────────────────────────────────────────┘
```

### Core Subsystems


| Sub-project      | Description                                                                                                                                                   | Repository                                                                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **KWeaver DIP**  | Include AI application and component marketplace, DIP Studio - Visual development and management interface                                                    | [AI Store](https://github.com/kweaver-ai/ai-store) [DIP Studio](https://github.com/kweaver-ai/studio)                                                                                               |
| **KWeaver Core** | AI-native platform foundation — Decision Agent, AI Data Platform (BKN Engine, VEGA Engine, Context Loader, Execution Factory), Info Security Fabric, Trace AI | [ADP](https://github.com/kweaver-ai/adp) [Decision Agent](https://github.com/kweaver-ai/decision-agent) [ISF](https://github.com/kweaver-ai/isf) [Trace AI](https://github.com/kweaver-ai/trace-ai) |


---

More components will be open-sourced in the future. Stay tuned!