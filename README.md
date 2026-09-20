<div align="center">

# 赵紫璐 | Zilu Zhao

### Java Backend & AI Application Engineer

**Shenzhen, China · Cross-border E-commerce Agent Automation**

用稳定的后端工程连接业务、数据与大模型。  
Building reliable systems that connect business workflows, data, and LLMs.

[![Email](https://img.shields.io/badge/Email-zilu__zhao%40outlook.com-1f6feb?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:zilu_zhao@outlook.com)
![Location](https://img.shields.io/badge/Location-Shenzhen-2ea44f?style=flat-square)

</div>

## About Me

我是一名拥有 Java 微服务与 AI 应用开发经验的工程师，目前在深圳从事**跨境电商 Agent 自动化**相关工作。

早期主要使用 Java 构建高并发业务系统，参与过 O2O 家政服务、智慧公寓 IoT、营销抽奖等项目，积累了订单、支付、缓存、搜索、消息队列和设备数据处理经验。现在更关注如何将这些可靠的业务能力封装为工具，由 Agent 进行理解、编排和调用。

我希望解决的不是“让模型看起来会聊天”，而是让 AI 能够在真实业务中做到：

- 正确理解用户目标，并选择合适的 Agent、知识库或业务工具。
- 对规则和知识提供可追溯回答，对价格、库存、订单等实时数据调用业务接口。
- 对写操作增加用户确认、权限校验、幂等和审计，避免模型越权执行。
- 在模型或下游服务失败时，提供清晰、可恢复的降级路径。

## Current Focus

- 构建跨境电商场景下的 Agent 工作流与业务自动化能力。
- 使用 Tool Calling / MCP 连接订单、商品、运营和知识服务。
- 设计可控的多 Agent 路由、状态管理、异常处理与人工确认机制。
- 建设 RAG 知识服务，包括文档清洗、混合检索、Rerank、引用和评测。
- 将 Java 业务系统的稳定性能力复用到 AI 应用：限流、熔断、幂等、消息可靠性与可观测性。

## Tech Stack

### Backend & Frameworks

![Java](https://img.shields.io/badge/Java-Backend-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-AI_Applications-3776AB?style=flat-square&logo=python&logoColor=white)
![MyBatis Plus](https://img.shields.io/badge/MyBatis--Plus-2f74c0?style=flat-square)

- Java、Python、面向对象、多线程、集合框架与常用设计模式
- Spring Boot、Spring MVC、Spring Cloud Alibaba、MyBatis-Plus
- Nacos、OpenFeign、Gateway、Sentinel、Swagger

### Agent & LLM Applications

![LangChain](https://img.shields.io/badge/LangChain-Agent_&_RAG-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-Workflow-5b5bd6?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Tool_Integration-8a2be2?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Hybrid_Retrieval-d97706?style=flat-square)

- Agent 路由、工具调用、状态工作流、SSE 流式响应
- MCP 工具封装、结构化输出、人工确认与异常兜底
- LangChain、LangGraph、RAG、Prompt Engineering
- Milvus、Embedding、BM25、Reranker、Metadata Filtering

### Data & Infrastructure

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

- MySQL、Redis、Milvus、Elasticsearch
- RabbitMQ、XXL-Job、Quartz
- Docker、Linux、Git、Maven
- 缓存设计、分布式锁、异步削峰、消息可靠性与搜索索引同步

## Engineering Experience

### Cross-border E-commerce Agent Automation · Current

在深圳参与跨境电商 Agent 自动化建设，关注 Agent 如何可靠地连接知识、商品、订单及运营流程。当前工作重点包括意图理解、任务编排、工具调用、上下文管理、业务写操作保护和失败恢复。


### O2O Home Services Platform · Java Microservices

- 参与 C 端门户、订单、支付结果查询、取消订单及优惠券抢购链路的设计与开发。
- 使用 Redis、Spring Cache 与 Canal 优化门户查询，处理缓存穿透、击穿及数据同步问题。
- 使用 Elasticsearch、Canal 与 RabbitMQ 建设服务搜索和异步索引同步链路。
- 使用 Redis + Lua、分布式锁、队列和线程池处理高并发优惠券扣减与异步落库。
- 参与订单分库分表、状态机和订单快照设计，降低订单状态流转的耦合度。

### Smart Apartment & IoT Platform · Java / IoT / LLM

- 接入华为云 IoT，处理智能门锁、烟感、空气净化器及智能水电表的状态上报。
- 使用 RabbitMQ 与线程池完成设备消息削峰、批量写库和异常告警。
- 使用 Quartz 构建设备告警与沉默期控制流程。
- 构建本地知识库与大模型双层响应的智能客服，让高频问题优先由本地知识命中。

### Marketing Lottery Platform · High Concurrency

- 使用策略模式与责任链模式解耦活动校验、奖品路由和状态转换。
- 使用 Redis 缓存热点活动数据，并通过缓存重建保证查询稳定性。
- 使用 RabbitMQ、Direct Exchange 与死信队列异步处理抽奖及中奖通知。
- 对接短信与邮件服务，使用线程池完成异步消息推送。

## AI Application Principles

```text
Document knowledge  -> RAG retrieval with evidence
Exact / live data   -> Database or business API
Read operation      -> Tool call with validation
Write operation     -> Confirmation + permission + idempotency + audit
Insufficient proof  -> Clarify, refuse, or hand off to a human
```

我在 AI 应用中尤其关注以下边界：

1. **不让 LLM 猜实时数据。** 价格、库存、订单状态等必须来自数据库或业务接口。
2. **不把检索相关当成答案正确。** RAG 需要 Metadata 过滤、Rerank、引用和无答案处理。
3. **不让 Agent 直接完成高风险操作。** 支付、退款、发布等操作需要明确确认和业务系统校验。
4. **不忽略传统工程能力。** 限流、超时、熔断、幂等、日志和消息可靠性仍然决定系统是否可用。

## What I Bring

- 能从 Java 业务系统视角理解订单、缓存、搜索、消息和一致性问题。
- 能用 Python 与 LLM 框架构建 Agent、RAG 和自动化工作流。
- 能区分模型应该负责的“理解与编排”和业务系统应该负责的“事实与执行”。
- 关注系统边界、失败路径和线上可维护性，而不仅是 Demo 效果。

## Contact

- **Email:** [zilu_zhao@outlook.com](mailto:zilu_zhao@outlook.com)
- **Location:** Shenzhen, China
- **Education:** B.S. in Computer Science and Technology

---

<div align="center">

**Java foundations. AI-native workflows. Reliable business automation.**

</div>
