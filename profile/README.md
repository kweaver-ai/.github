<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./logo/dark.png" />
  <source media="(prefers-color-scheme: light)" srcset="./logo/light.png" />
  <img alt="KWeaver" src="./logo/light.png" width="320" />
</picture>
</div>

[中文](README.zh.md) | English

[License](LICENSE.txt)

[![GitHub stars](https://img.shields.io/github/stars/kweaver-ai/kweaver?style=social)](https://github.com/kweaver-ai/kweaver)

> ⭐ **If you like KWeaver, please [star us](https://github.com/kweaver-ai/kweaver)!** Your support helps us grow and improve.

KWeaver is an open-source ecosystem for building, deploying, and running decision intelligence AI applications. This ecosystem adopts business knowledge network (Business Knowledge Network) as its core methodology, aiming to provide elastic, agile, and reliable enterprise-grade decision intelligence to further unleash everyone's productivity.

The KWeaver project includes KWeaver Core, KWeaver DIP and KWeaver SDK.

## Platform Architecture

```text
┌─────────────────────────────────────────────┐
│                 KWeaver                     │
│  ┌───────────────────────────────────────┐  │
│  │           KWeaver SDK                 │  │
│  ├───────────────────────────────────────┤  │
│  │           KWeaver DIP                 │  │
│  ├───────────────────────────────────────┤  │
│  │           KWeaver Core                │  │
│  └───────────────────────────────────────┘  │
└─────────────────────────────────────────────┘
```

### Core Subsystems

| Sub-project | Description | Repository |
| --- | --- | --- |
| **KWeaver SDK** | CLI and SDK (TypeScript/Python) for AI agents and developers to access KWeaver knowledge networks and Decision Agents programmatically | [kweaver-sdk](https://github.com/kweaver-ai/kweaver-sdk) |
| **KWeaver DIP** | Include AI application and component marketplace, DIP Studio - Visual development and management interface | [AI Store](https://github.com/kweaver-ai/ai-store)<br>[DIP Studio](https://github.com/kweaver-ai/studio) |
| **KWeaver Core** | AI-native platform foundation — Decision Agent, AI Data Platform (BKN Engine, VEGA Engine, Context Loader, Execution Factory), Info Security Fabric, Trace AI | [ADP](https://github.com/kweaver-ai/adp)<br>[Decision Agent](https://github.com/kweaver-ai/decision-agent)<br>[ISF](https://github.com/kweaver-ai/isf)<br>[Trace AI](https://github.com/kweaver-ai/trace-ai) |


---

More components will be open-sourced in the future. Stay tuned!