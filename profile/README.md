<div align="center">
  <img src="https://avatars.githubusercontent.com/u/224754962?v=4" alt="openkursar logo" width="120" />
  <h1>openkursar</h1>
  <p><b>The Open Infrastructure for 7x24 Autonomous Agents.</b></p>
  
  <p>
    <a href="#english">English</a> | <a href="#中文">中文</a>
  </p>

  <p>
    <a href="https://github.com/openkursar/digital-human-protocol"><img src="https://img.shields.io/badge/Protocol-DHP_v1.0-black?style=flat-square" alt="DHP Protocol" /></a>
    <img src="https://img.shields.io/badge/Architecture-Decentralized-blue?style=flat-square" alt="Decentralized" />
    <img src="https://img.shields.io/badge/Ecosystem-Open_Source-success?style=flat-square" alt="Open Source" />
  </p>
</div>

---

## <a name="english"></a>English

### Vision

**openkursar** is an open-source organization dedicated to building the infrastructure for 24/7 background "Digital Humans" (Autonomous Agents).

We were born from a simple tech philosophy: **Kill Ugly Raw Source, AI Rewrites.** In the past, this meant using AI to refactor bad code. Today, its meaning has evolved—**eliminating primitive, inefficient, and repetitive manual interventions by rewriting how tasks are executed using 24/7 autonomous agents.**

We believe the computing platform of the future should not just offer "Copilot tools." Instead, it should provide a standardized runtime environment that allows agents to persistently and autonomously take over complex workflows.

### Core Infrastructure

To achieve this, we are not building a walled garden. We are defining a fully open protocol and a decentralized ecosystem:

#### 1. DHP (Digital Human Protocol)
The declarative standard for autonomous agents.
We provide a minimalist YAML specification (AppSpec) that allows developers to define a background agent just like writing a `Dockerfile`. It standardizes the agent's identity, triggers (Schedule/Webhook), capabilities (Skills), and its context for interacting with the external world (powered by the Model Context Protocol - MCP).

#### 2. Decentralized Registry
A GitHub and CI/CD-driven agent distribution network.
We discarded the traditional centralized app store model in favor of a pure static index (`index.json`) protocol. Developers simply submit YAML files, and automated workflows handle validation and publishing. Clients can mount multiple registries, catering to both the official ecosystem and private enterprise deployments.

#### 3. Halo Runtime
The "Operating System" for agents.
The Halo client serves not only as the storefront interface but as the local mothership for running agents. It provides secure Space isolation, dependency resolution (automatically fetching and mounting MCPs/Skills), IPC communication, and dynamic configuration rendering.

### Showcases

Powered by the openkursar protocol, we have incubated the first batch of 24/7 agents in our Registry:

* **`jd-price-hunter` (E-commerce):** Mounts the `ai-browser` MCP for automated price tracking and drop alerts.
* **`github-pr-reviewer` (DevTools):** Listens to Webhook events to autonomously perform code reviews.
* **`hn-daily` (Content/News):** Analyzes Hacker News trends daily to generate and push structured briefings.

### Contributing

Whether it is protocol design, core component development, or building creative new agents, we welcome all developers to join the fleet.

* **[Read the DHP Spec](https://github.com/openkursar/digital-human-protocol)**: Learn how to write your first `spec.yaml`.
* **[Explore the Registry](https://github.com/openkursar)**: Discover existing agents or submit your PR.
* **[Join the Community](https://github.com/openkursar)**: Shape the evolution of our architecture.

---

## <a name="中文"></a>中文

### 愿景

**openkursar** 是一个致力于构建全天候"数字人 (Autonomous Agents)"基础设施的开源组织。

我们诞生于一个朴素的技术哲学：**Kill Ugly Raw Source, AI Rewrites.** 过去，这句话意味着用 AI 重构糟糕的代码；今天，它的意义已全面进化——**消除数字世界中原始、低效、重复的人工干预，用 7x24 小时静默运行的数字人重写任务的执行方式。**

我们认为，未来的计算平台不应仅仅是"提供 Copilot 工具"，而是提供一个标准化的运行时环境，让 AI 智能体能够持久化、自主化地接管复杂业务流。

### 核心架构

为了实现这一目标，我们并没有构建一个封闭的黑盒平台，而是定义了一套完整的开放协议与去中心化生态：

#### 1. DHP 协议 (Digital Human Protocol)
数字人的声明式标准。
我们提供了一套极简的 YAML 规范（AppSpec），让开发者可以像编写 Dockerfile 一样定义一个后台运行的数字人。它标准化了 Agent 的身份、触发机制（Schedule/Webhook）、能力（Skills）以及对外部世界的操作上下文（基于 MCP - Model Context Protocol）。

#### 2. 去中心化注册中心 (Decentralized Registry)
基于 GitHub 与 CI/CD 驱动的 Agent 分发网络。
我们摒弃了传统的中心化应用商店，采用纯静态索引 (`index.json`) 协议。开发者只需提交 YAML 文件，工作流会自动完成校验与发布。支持客户端挂载多个 Registry，满足官方生态与企业私有化部署的需求。

#### 3. Halo 运行时 (The Runtime Client)
数字人的"操作系统"。
Halo 客户端不仅是商店的前端界面，更是数字人的本地运行母舰。它提供安全的工作空间（Space）隔离、依赖解析（自动拉取并挂载 MCP/Skill）、IPC 通信以及可视化的配置渲染。

### 示例用例

基于 openkursar 协议，我们已在 Registry 中孵化了首批 7x24 运行的数字人：

* **`jd-price-hunter` (电商监控)**：挂载 `ai-browser` MCP，自动化比价与降价提醒。
* **`github-pr-reviewer` (开发者工具)**：监听 Webhook 事件，自主完成代码审查。
* **`hn-daily` (内容分发)**：定时分析 Hacker News 趋势，生成并推送结构化简报。

### 参与共建

无论是协议设计、基础组件开发，还是构建极具创造力的数字人，我们欢迎所有开发者的加入。

* **[阅读 DHP 协议规范](https://github.com/openkursar/digital-human-protocol)**：了解如何编写你的第一个数字人 `spec.yaml`。
* **[探索 Registry 仓库](https://github.com/openkursar)**：查看现有数字人的实现，或提交你的 PR。
* **[加入社区讨论](https://github.com/openkursar)**：参与架构演进与下一步规划。

<div align="center">
  <br>
  <i>Automating reality, one standard at a time.</i>
</div>
