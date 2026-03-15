# KWeaver

中文 | [English](README.md)

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE.txt)

KWeaver 是一个构建、发布、运行决策智能型 AI 应用的开源生态。此生态以业务知识网络（Business Knowledge Network）为核心方法论，旨在提供弹性、敏捷、可靠的企业级决策智能，进一步释放每一员的生产力。

KWeaver 项目包含 KWeaver Core 和 KWeaver DIP。

## 平台架构

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

### 核心子系统

| 子项目 | 描述 | 仓库地址 |
| --- | --- | --- |
| **KWeaver DIP** | 包含 AI 应用与组件市场、DIP Studio 可视化开发与管理界面 | [AI Store](https://github.com/kweaver-ai/ai-store)<br>[DIP Studio](https://github.com/kweaver-ai/studio) |
| **KWeaver Core** | AI 原生平台基础 —— Decision Agent、AI 数据平台（BKN Engine、VEGA Engine、Context Loader、Execution Factory）、信息安全织物（ISF）、Trace AI | [ADP](https://github.com/kweaver-ai/adp)<br>[Decision Agent](https://github.com/kweaver-ai/decision-agent)<br>[ISF](https://github.com/kweaver-ai/isf)<br>[Trace AI](https://github.com/kweaver-ai/trace-ai) |

---

后续更多组件开源，敬请期待！
