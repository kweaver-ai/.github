# KWeaver

中文 | [English](README.md)

[![GitHub stars](https://img.shields.io/github/stars/kweaver-ai/kweaver?style=social)](https://github.com/kweaver-ai/kweaver)

> ⭐ **如果您喜欢 KWeaver，请给我们点个 Star！** 您的支持是我们前进的动力。

KWeaver 是一个构建、发布、运行决策智能型 AI 应用的开源生态。此生态采用本体作为业务知识网络的核心方法，以 DIP 为核心平台，旨在提供弹性、敏捷、可靠的企业级决策智能，进一步释放每一员的生产力。

DIP 平台包括 ADP、Decision Agent、DIP Studio、AI Store 等关键子系统。

## 🏗️ 架构

    ┌────────────────────────────────────┐
    │            DIP 平台                │
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

### 🧩 子系统

核心子系统：

| 子项目 | 描述 | 仓库地址 |
| --- | --- | --- |
| **KWeaver** | 总体项目架构，包含文档、工具和脚本 | [kweaver-ai/kweaver](https://github.com/kweaver-ai/kweaver) |
| **AI Store** | AI 应用与组件市场 |  [kweaver-ai/ai-store](https://github.com/kweaver-ai/ai-store) |
| **DIP Studio** | DIP Studio - 可视化开发与管理界面 | [kweaver-ai/studio](https://github.com/kweaver-ai/studio) |
| **Decision Agent** | 决策智能体 | [kweaver-ai/decision-agent](https://github.com/kweaver-ai/decision-agent) |
| **ADP** | 智能数据平台 - 核心开发框架，包含本体引擎、ContextLoader 和 VEGA 数据虚拟化引擎 | [kweaver-ai/adp](https://github.com/kweaver-ai/adp) |

关键基础设施：

| 子项目 | 描述 | 仓库地址 |
| --- | --- | --- |
| **Operator Hub** | 算子平台，负责算子管理与编排 | [kweaver-ai/operator-hub](https://github.com/kweaver-ai/operator-hub) |
| **Sandbox** | 沙箱运行环境 | [kweaver-ai/sandbox](https://github.com/kweaver-ai/sandbox) |

---

后续更多组件开源，敬请期待！
