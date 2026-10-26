<div align="center">

# Hi, I'm zhang jieshi 👋

### AI Applications · Enterprise Integration · Business Systems

让 AI 连接真实业务，让软件解决具体问题。

[GitHub](https://github.com/kaiishityou126) · [AI 企业数据接入](https://github.com/kaiishityou126/enterprise-connector-mcp) · [海星同传](https://github.com/kaiishityou126/voice_translator)

</div>

---

## 关于我

你好，我是 **zhang jieshi**。

关注 AI 应用与企业业务系统的结合，探索从模型能力、数据接入到实际产品的完整路径。这里优先展示我的 AI 项目，也记录工厂与订单管理方向的实践。

- **AI 应用**：MCP、语音识别、实时翻译与大模型集成。
- **企业数据接入**：多租户隔离、权限控制、数据库与 HTTP API 集成。
- **业务系统**：参与制造业平台与电商订单系统建设，承担技术方案设计、研发推进、系统集成与上线交付。

## 精选 AI 项目

### 01 / Enterprise Connector MCP

**让 AI Agent 通过 MCP 访问企业业务数据。**

面向企业数据库与 HTTP API 的多租户接入层，围绕数据隔离、访问控制和可观测性设计，探索 AI 与企业系统之间的工程化连接方式。

- 按租户隔离数据源、工具定义、缓存和访问权限。
- 通过模板化 SQL、白名单校验和只读数据库账号约束数据访问。
- 提供两级缓存、配置热更新、限流与审计能力。

**技术栈**：Java 21 · Spring Boot · Spring AI MCP · PostgreSQL · Redis · MyBatis-Flex

[查看后端仓库 →](https://github.com/kaiishityou126/enterprise-connector-mcp) · [配套管理控制台 →](https://github.com/kaiishityou126/enterprise-connector-admin-ui)

> 个人作品集 / PoC 项目；配套管理控制台仍在建设中。

### 02 / 海星同传 · SeaStar Voice Translator

**把电脑上的声音变成实时双语字幕。**

面向会议、视频和直播等场景的桌面语音翻译应用，将本地语音识别、翻译与字幕展示连接起来，并提供双向语音回灌能力。

- 支持系统音频与麦克风输入，以及置顶双语字幕悬浮窗。
- 语音识别在本机完成，可接入 OpenAI 兼容翻译接口或本地 Ollama。
- 提供会话摘要、历史回看和说话人声纹门控。

**技术栈**：Tauri · React · Rust · sherpa-onnx · Ollama

[查看项目 →](https://github.com/kaiishityou126/voice_translator)

> 当前主要面向 Windows；macOS 实现待真机验证。

## 企业业务项目经历

### 03 / 工厂制造业综合业务平台

**围绕生产运营，连接仓库、制造、品质与主数据。**

面向工厂制造业，涵盖仓库管理（WMS）、制造执行（MES）、品质管理（QMS）及主数据管理（MDM），并与 SAP、ASPROVA 等外部系统集成，支撑生产运营与业务数据协同。

- **技术方案与研发协作**：负责整体技术方案设计，参与客户需求调研、功能设计与开发计划制定，承担开发任务分配和进度跟踪。
- **核心流程与系统集成**：参与 WMS/MES 核心业务流程设计，处理 SAP、ASPROVA 数据交互、接口联调及业务异常。
- **上线交付与问题闭环**：参与交付和上线部署，负责上线初期问题排查与修复，建立缺陷跟踪和处理机制。

**技术栈与集成环境**：Java · Spring Boot · Redis · PostgreSQL · PDA · SAP · ASPROVA

### 04 / 电商订单接入与处理系统

**打通外部订单通知与内部订单管理系统。**

承接外部平台订单通知，通过订单接入、校验、分配、信息构建及确认入库等流程，完成外部订单与内部业务系统的衔接。

- **技术负责人**：负责任务分配、进度跟踪与技术问题解决，推动 Checkstyle 编码规范检查和单元测试落地。
- **订单链路与异步处理**：推进订单接入、分配、信息构建及确认入库等业务研发，参与 RabbitMQ 异步消息、延迟交换机与死信队列（DLQ）功能开发。
- **新旧系统双库写入**：实现遗留 core 库与新 order 库的双库写入，按业务要求采用差异化异常策略：旧库写入失败容错，新库写入失败抛出业务异常。

**技术栈**：Java 17 · Spring Boot 3.2 · Spring Cloud 2023 · RabbitMQ · WebClient · Spring Data JPA · Oracle / MariaDB · Gradle

## 技术方向

| 方向 | 技术与实践 |
| :--- | :--- |
| AI 与模型集成 | MCP、Spring AI、OpenAI 兼容接口、Ollama |
| 后端与数据 | Java、Spring Boot、Spring Cloud、PostgreSQL、Redis、Oracle / MariaDB、MyBatis-Flex、Spring Data JPA |
| 消息与系统集成 | RabbitMQ、WebClient、SAP / ASPROVA 对接 |
| 前端与桌面 | Vue 3、TypeScript、React、Tauri、Rust |
| 工程关注点 | 多租户隔离、权限、安全、缓存、可观测性、Checkstyle 与单元测试 |

---

<div align="center">

**Building useful AI, connected to real work.**

欢迎围绕 AI 应用、企业数据接入和业务系统交流。  
[浏览我的项目 →](https://github.com/kaiishityou126?tab=repositories)

</div>
