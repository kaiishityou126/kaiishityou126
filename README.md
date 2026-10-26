<div align="center">

![zhang jieshi — Java Backend & AI Applications](./assets/profile-banner.svg)

### Java Backend Engineer · AI Application Developer

用 Java 构建业务系统，让 AI 走进真实场景。

[![GitHub](https://img.shields.io/badge/GitHub-kaiishityou126-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kaiishityou126)
[![MCP](https://img.shields.io/badge/Focus-MCP_%26_Enterprise_AI-0e7490?style=flat-square)](https://github.com/kaiishityou126/enterprise-connector-mcp)
[![Speech AI](https://img.shields.io/badge/Building-SeaStar_Voice_Translator-0f766e?style=flat-square)](https://github.com/kaiishityou126/voice_translator)

[AI 项目](#-featured-ai-projects) · [业务项目](#-enterprise-experience) · [技术栈](#-tech-stack)

</div>

## 👋 About Me

我是 **zhang jieshi**，从事 Java 后端与企业业务系统开发，目前重点探索 **AI 应用与企业数据的连接**。

- 🤖 **AI 工程实践**：Spring AI / MCP 企业数据接入、本地语音识别与实时翻译。
- 🏭 **业务系统经验**：制造业 WMS / MES / QMS / MDM，以及电商订单处理。
- 🔗 **系统集成**：SAP / ASPROVA 接口对接、RabbitMQ 异步消息、新旧系统数据衔接。
- 🛠️ **研发与交付**：技术方案设计、任务推进、编码规范、单元测试与上线问题闭环。

## 🤖 Featured AI Projects

### [Enterprise Connector MCP](https://github.com/kaiishityou126/enterprise-connector-mcp)
**为 AI Agent 与企业业务数据搭建受控的连接层。**

将数据库与 HTTP API 暴露为 MCP 工具，重点解决多租户场景下的数据隔离、访问控制和可观测性问题。

- **租户隔离**：数据源、工具定义、权限与缓存按租户划分。
- **受控查询**：模板化 SQL、白名单校验与只读数据库账号。
- **运行治理**：两级缓存、配置热更新、限流与审计。

`Java 21` `Spring Boot` `Spring AI MCP` `PostgreSQL` `Redis`

[后端源码 ↗](https://github.com/kaiishityou126/enterprise-connector-mcp) · [Vue 管理控制台 ↗](https://github.com/kaiishityou126/enterprise-connector-admin-ui)  
<sub>个人作品集 / PoC；配套管理控制台持续建设中。</sub>

---

### [海星同传 · SeaStar Voice Translator](https://github.com/kaiishityou126/voice_translator)
**把会议、视频与直播中的声音，变成实时双语字幕。**

结合本地语音识别与可切换的翻译引擎，提供跨应用的桌面翻译体验。

- **实时字幕**：系统音频 / 麦克风输入，双语字幕与置顶悬浮窗。
- **本地识别**：音频在本机识别，可搭配本地 Ollama 翻译。
- **双向沟通**：语音回灌、说话人声纹门控，以及会话摘要与历史回看。

`Tauri` `React` `Rust` `sherpa-onnx` `Ollama`

[项目源码与使用说明 ↗](https://github.com/kaiishityou126/voice_translator)  
<sub>当前主要面向 Windows；macOS 实现待真机验证。</sub>

## 🏭 Enterprise Experience

### 工厂制造业综合业务平台
**WMS · MES · QMS · MDM**

覆盖仓库、制造执行、品质与主数据管理，对接 **SAP / ASPROVA**，支撑生产运营和业务数据协同。

- 负责整体技术方案设计，参与需求调研与功能设计，推进任务分配和开发进度。
- 参与 WMS / MES 核心流程设计，处理外部系统数据交互、联调及业务异常。
- 参与上线部署，负责初期排障与修复，建立缺陷跟踪和问题闭环机制。

`Java` `Spring Boot` `PostgreSQL` `Redis` `PDA` `SAP` `ASPROVA`

### 电商订单接入与处理系统
**订单接入 → 校验 → 分配 → 信息构建 → 确认入库**

承接外部平台订单通知，连接内部订单管理系统，承担项目技术负责人职责。

- 推进业务链路研发、任务分配与技术问题解决，推动 **Checkstyle 与单元测试**落地。
- 参与 **RabbitMQ 异步处理、延迟交换机与死信队列（DLQ）**开发。
- 实现 **core / order 双库写入**：按业务要求，旧库写入失败容错，新库失败抛出业务异常。

`Java 17` `Spring Boot 3.2` `Spring Cloud` `RabbitMQ` `WebClient` `JPA` `Oracle / MariaDB` `Gradle`

## 🛠️ Tech Stack

**Backend & Data**

<img src="https://skillicons.dev/icons?i=java,spring,postgres,redis,rabbitmq,gradle&theme=dark" alt="Java, Spring, PostgreSQL, Redis, RabbitMQ, Gradle" />

`Spring Boot / Cloud` · `MyBatis-Flex` · `Spring Data JPA` · `Oracle / MariaDB`

**AI, Frontend & Desktop**

<img src="https://skillicons.dev/icons?i=vue,ts,react,rust,tauri&theme=dark" alt="Vue, TypeScript, React, Rust, Tauri" />

`Spring AI` · `MCP` · `OpenAI-compatible APIs` · `Ollama` · `sherpa-onnx`

---

<div align="center">

**Connecting AI to real business.**

欢迎交流 AI 应用、Java 后端与企业系统集成。  
[Explore my repositories →](https://github.com/kaiishityou126?tab=repositories)

</div>
