<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./logo/dark.png" />
  <source media="(prefers-color-scheme: light)" srcset="./logo/light.png" />
  <img alt="KWeaver" src="./logo/light.png" width="320" />
</picture>
</div>

中文 | [English](README.md)

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE.txt)

[![GitHub stars](https://img.shields.io/github/stars/kweaver-ai/kweaver?style=social)](https://github.com/kweaver-ai/kweaver)

> ⭐ **如果您喜欢 KWeaver，请给我们点个 Star！** 您的支持是我们前进的动力。

KWeaver 是一个构建、发布、运行决策智能型 AI 应用的开源生态。此生态以业务知识网络（Business Knowledge Network）为核心方法论，旨在提供弹性、敏捷、可靠的企业级决策智能，进一步释放每一员的生产力。

KWeaver 项目包含 KWeaver Core、KWeaver DIP 与 KWeaver SDK。

## 平台架构

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

### 核心子系统

| 子项目 | 描述 | 仓库地址 |
| --- | --- | --- |
| **KWeaver SDK** | 面向 AI Agent 和开发者的 CLI 及 SDK（TypeScript/Python），用于以编程方式访问 KWeaver 知识网络与 Decision Agent | [kweaver-sdk](https://github.com/kweaver-ai/kweaver-sdk) |
| **KWeaver DIP** | 包含 AI 应用与组件市场、DIP Studio 可视化开发与管理界面 | [AI Store](https://github.com/kweaver-ai/ai-store)<br>[DIP Studio](https://github.com/kweaver-ai/studio) |
| **KWeaver Core** | AI 原生平台底座 — Decision Agent、AI Data Platform（BKN Engine、VEGA Engine、Context Loader、Execution Factory）、Info Security Fabric、Trace AI | [ADP](https://github.com/kweaver-ai/adp)<br>[Decision Agent](https://github.com/kweaver-ai/decision-agent)<br>[ISF](https://github.com/kweaver-ai/isf)<br>[Trace AI](https://github.com/kweaver-ai/trace-ai) |

---

后续更多组件开源，敬请期待！
