---
title: 路线图
order: 3
---

# CnosDB2.0 路线图

## 设计目标

设计和开发一个高性能、高压缩比、高可用性、分布式云原生时序数据库，需要满足以下目标。

> 时间序列数据库

1. 可扩展性，理论上支持无上限的时间序列，彻底解决时间序列膨胀问题，支持水平/垂直扩展。
2. 分离存储和计算，计算节点和存储节点可以独立扩展和缩减。
3. 高性能存储和低成本，使用高性能I/O堆栈，云磁盘和对象存储进行存储分层。
4. 查询引擎支持向量化查询。
5. 支持多种时间协议进行写入和查询，并提供外部组件导入数据。

> 云原生

1. 支持云原生，充分利用云基础设施带来的便利，并集成到云原生生态系统中。
2. 高可用性，支持秒级故障恢复，多云和多区域灾备和预防措施。
3. 原生支持多租户，按需计费。
4. CDC，日志可以被订阅并分发到其他节点。
5. 提供更多可配置的项目，以满足公共云用户在多种场景下的复杂要求。
7. 云边协同，提供与公共云的边缘-端集成能力。
6. 云上汇聚的 OLAP/CloudAI 数据生态系统。

## CnosDB 架构

![整体架构](/_static/img/arch.jpg)

## CnosDB Timeline

| 产品特性                  | 时间节点  |
|-----------------------| ----  |
| 2.0 Stand-alone  Beta | 2022.10 |
| 2.0 Distribution Beta | 2022.12 |
| Cloud Trial on AWS    | 2023.Q1 |
| Enterprise Service    | 2023.Q2 |


