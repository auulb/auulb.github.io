---
{"dg-publish":true,"permalink":"/test/javaplan/","dg-note-properties":{}}
---


# Java 专项路线（W13–W18）

> 配套主计划：test/workplan.md
> 时间：2027-01-03 → 2027-02-13（含 W17 春节缓冲）
> 核心原则：**不从零学 Java，而是用 Java 重写你已经用 Python 写过的东西**

## 为什么排在 W13

- 第 1–12 周 Python 一条线，先把「写代码的手感」和「系统能力」建立起来
- Java 对你是「换工具」不是「学新东西」：你已经知道要做什么，只是换一种表达
- 培训班会重点讲 Java。你提前亲手写过一遍接口、缓存和部署，上课会轻松很多

---

## W13 · Java 速通（对照 Python 学）｜1/3–1/9

目标：能读懂并写出 100 行以内的 Java 类。

- 环境：JDK 21 + IntelliJ IDEA + Maven
- 对照清单：强类型 vs 动态类型 / List·Map / 循环 / 方法 / 类与接口 / 异常 / 字符串

每日任务：

- [ ] 用 Java 打印 Hello World，跑通一次 Maven 构建
- [ ] 用 Java 写一个类，读 JSON 文件并解析（对照 Python 版）
- [ ] 用 Java 调用大模型 HTTP 接口，打印回答
- [ ] 用 Java 重写 Python 版的「JSON → Markdown 表格」
- [ ] 开始整理「Python → Java 语法对照表」笔记

**验收**：Java 版命令行摘要脚本能跑通。

---

## W14 · Java 进阶｜1/10–1/16

- 集合：List / Set / Map 的实现与选择（对照 Python 的 list / dict）
- 泛型、接口与抽象类、简单的面向对象设计
- 异常体系、try-with-resources、IO 与文件
- Maven 依赖管理、多模块概念

每日任务：

- [ ] 用 Java 重写 2 个你已经用 Python 写过的小工具
- [ ] 每天 1 道算法题改用 Java 写（顺便练语法）

**验收**：能用 Java 写出 200 行左右、有类拆分的程序。

---

## W15 · Spring Boot 单个接口｜1/17–1/23

- Spring Boot 项目骨架与分层：Controller – Service – Repository
- 写 `GET /summarize?text=...`，内部调用大模型
- 参数校验、统一返回格式、全局异常处理
- 用 SLF4J 打日志
- 用 Spring AI 或 HTTP Client 接大模型

**验收**：本地 `curl` 能调通接口。

---

## W16 · 接数据库与事务｜1/24–1/30

- JPA / MyBatis 二选一（建议先 JPA 入门）
- 实体与表的映射、Repository、分页查询
- 事务基础：`@Transactional`、隔离级别概念
- 连接池是什么、为什么要它

**验收**：Java 版接口能把数据写进数据库并查出来。

---

## W17 · 春节缓冲｜1/31–2/6

- **减量**：不做新东西，只做复盘
- 每天 30 分钟 Java 小练习（保持手感即可）
- 把 W13–W16 的笔记整理成一份完整的「Python → Java 对照表」

---

## W18 · 重写后端 + 缓存 + 上线｜2/7–2/13

- 把 Phase 2 的 Python 接口用 Java 重写
- 接 PostgreSQL 或 MySQL
- 加 Redis 缓存「已经生成过的摘要」
- Docker 打包部署，替换掉 Python 版

**验收（M3）**：公网服务由 Java 后端提供。

> W19 之后的 RAG / Agent 继续用 Python 做，Java 侧只维护接口层。

---

## Java 长期地图（架构师方向，培训班之后再推进）

- 基础：集合源码、泛型、反射、注解
- 进阶：JMM、synchronized、JUC、线程池
- 运行时：类加载、GC、jstack / jmap / arthas 排障
- 框架：Spring IoC·AOP、自动装配、MyBatis
- 数据：MySQL 索引与执行计划、MVCC、事务隔离
- 中间件：Redis、Kafka / RocketMQ
- 分布式：一致性、分布式锁、限流熔断、链路追踪
- 架构：DDD、微服务边界、容量估算
- 软能力：技术方案文档、ADR
