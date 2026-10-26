<div align="center">

**English** · [简体中文](https://github.com/kaiishityou126/kaiishityou126/blob/main/README.zh-CN.md)

![zhang jieshi — Java Backend & AI Applications](./assets/profile-banner.svg)

### Java Backend Engineer · AI Application Developer

Building business systems with Java. Bringing AI into real workflows.

[![GitHub](https://img.shields.io/badge/GitHub-kaiishityou126-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kaiishityou126)
[![MCP](https://img.shields.io/badge/Focus-MCP_%26_Enterprise_AI-0e7490?style=flat-square)](https://github.com/kaiishityou126/enterprise-connector-mcp)
[![Speech AI](https://img.shields.io/badge/Building-SeaStar_Voice_Translator-0f766e?style=flat-square)](https://github.com/kaiishityou126/voice_translator)

[AI Projects](#ai-projects) · [Enterprise Experience](#enterprise-experience) · [Tech Stack](#tech-stack)

</div>

## 👋 About Me

I'm **zhang jieshi**, focused on **Java backend development, AI applications, and enterprise systems integration**.

My work spans manufacturing platforms and e-commerce order systems. I'm currently working with **AI agents, MCP, and RAG** to connect language models with enterprise data and shop-floor workflows.

<a id="ai-projects"></a>

## 🤖 Featured AI Projects

### Factory Smart Mirror Agent Platform
<sub>Enterprise project · Technical Lead</sub>

**A single interface for employees to access daily tasks, work instructions, and business information.**

- **Identity to tasks:** Face / NFC identification → employee master data → work qualification checks → daily production tasks and electronic SOPs.
- **Business Q&A:** MCP tools query MES tasks, WMS / SAP order and shipment status, and inventory; RAG retrieves work instructions.
- **Controlled access:** Responsible for architecture and core development, using SQL templates, allowlist validation, read-only database accounts, and audit logs to constrain data access.

`Spring Boot` `Spring AI MCP` `pgvector` `Redis` `Vue`

---

### [Enterprise Connector MCP](https://github.com/kaiishityou126/enterprise-connector-mcp)
<sub>Personal open source · Proof of concept</sub>

**Isolated, controlled access to enterprise data for AI agents.**

- Exposes databases and HTTP APIs as MCP tools, with tenant-level isolation for data sources, permissions, tool definitions, and caches.
- Explores enterprise AI integration through controlled SQL queries, two-level caching, runtime configuration updates, and call auditing.

[Backend source ↗](https://github.com/kaiishityou126/enterprise-connector-mcp) · [Admin console ↗](https://github.com/kaiishityou126/enterprise-connector-admin-ui)  
<sub>The admin console is under active development.</sub>

---

### [SeaStar Voice Translator · 海星同传](https://github.com/kaiishityou126/voice_translator)
<sub>Personal open source · Desktop application</sub>

**Live bilingual subtitles for meetings, videos, and streams.**

- Local speech recognition with system-audio / microphone input, a subtitle overlay, and multiple translation engines, including local Ollama.
- Supports two-way voice relay, speaker voiceprint gating, session summaries, and history.

[Source & user guide ↗](https://github.com/kaiishityou126/voice_translator)  
<sub>Primarily for Windows; macOS support awaits hardware testing.</sub>

<a id="enterprise-experience"></a>

## 🏭 Enterprise Experience

**Manufacturing Operations Platform · Enterprise project**  
Spans WMS / MES / QMS / MDM with **SAP / ASPROVA** integration. Responsible for the overall technical design; contributed to core workflows, deployment, and post-launch troubleshooting.

**E-commerce Order Integration & Processing · Enterprise project · Technical Lead**  
Connects external platforms to an internal order system. Contributed to **RabbitMQ messaging, delayed exchanges, and dead-letter queues**; implemented writes to legacy core and new order databases with different failure-handling policies.

<a id="tech-stack"></a>

## 🛠️ Tech Stack

**Backend & Data**

<img src="https://skillicons.dev/icons?i=java,spring,postgres,redis,rabbitmq&theme=dark" alt="Java, Spring, PostgreSQL, Redis, RabbitMQ" />

| Area | Technologies & Practice |
| :--- | :--- |
| Backend services | Java 17 / 21, Spring Boot, Spring Cloud, REST APIs, WebClient |
| Persistence | PostgreSQL, Oracle, MariaDB, Spring Data JPA, MyBatis-Flex; legacy / new-system dual writes |
| Caching & messaging | Redis + Caffeine two-level caching, cache invalidation, RabbitMQ asynchronous processing, delayed exchanges, DLQs |
| Enterprise integration | SAP / ASPROVA interfaces, MES / WMS workflows, multi-tenant data-source routing |
| Access & observability | Tenant isolation, SQL templates and allowlist validation, rate limiting, audit logs, Micrometer / Prometheus |
| Engineering & delivery | Maven / Gradle, Checkstyle, unit and integration testing, deployment and post-launch troubleshooting |

**AI & Application Development**

<img src="https://skillicons.dev/icons?i=vue,ts,react,rust,tauri&theme=dark" alt="Vue, TypeScript, React, Rust, Tauri" />

`Spring AI` · `Agent / MCP / RAG` · `pgvector` · `Ollama` · `sherpa-onnx`

---

<div align="center">

Let's connect over AI applications, Java backend development, and enterprise integration.  
[Explore my repositories →](https://github.com/kaiishityou126?tab=repositories)

</div>
