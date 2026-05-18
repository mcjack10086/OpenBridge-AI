# OpenBridge AI

> Reduce paperwork.  
> Let seafarers focus on navigation and engineering.

Offline AI assistant for seafarers and shipboard workflows.  
面向船员的离线 AI 助手。

---

# Introduction

OpenBridge AI is an experimental open-source project designed for seafarers.

The goal is not to replace seafarers, but to help reduce repetitive paperwork and improve shipboard workflow efficiency.

This project focuses on:

- Logbook writing
- Shift handover summaries
- Maintenance records
- PSC preparation
- Maritime English assistance
- Task reminders
- SMS / checklist queries

Designed for real ship environments:

- Limited internet access
- Expensive satellite communication
- High paperwork pressure
- Small onboard local networks

---

# 为什么做这个项目？

现代船舶越来越智能。

但很多船员每天仍然需要花费大量时间处理：

- 航海日志
- 检查表
- PSC 文书
- 英文邮件
- 设备记录
- 交班内容
- SMS 文件查询

尤其在远洋环境下：

- 网络昂贵
- 卫星通信有限
- 文件繁杂
- 值班疲劳严重

因此本项目希望尝试：

> “离线 AI + 船员工作流”

而不是单纯追求“无人化”。

---

# Vision

OpenBridge AI aims to become:

- Local-first
- Offline-capable
- Lightweight
- Easy to deploy onboard
- Usable through ship LAN

Possible deployment devices:

- Mac mini
- Small onboard servers
- Edge AI devices

Access from:

- Tablets
- Bridge computers
- Engine control room terminals

---

# 项目愿景

OpenBridge AI 希望成为：

- 本地优先（Local First）
- 支持离线运行
- 适合船内局域网
- 轻量化部署
- 面向真实船员场景

未来可能部署于：

- Mac mini
- 小型服务器
- 边缘 AI 设备

高级船员可通过：

- 平板
- 驾驶台电脑
- 机舱终端

访问系统。

---

# Planned Features

## Navigation Assistant

- Bridge log generation
- Watchkeeping summaries
- Maritime English polishing
- Voyage notes

## Engine Department Assistant

- Maintenance record drafting
- Fault report generation
- Spare part request drafting

## PSC / SMS Assistant

- Checklist reminders
- Certificate expiry reminders
- SMS knowledge search

## AI Knowledge Base

Local searchable maritime knowledge:

- SOLAS
- MARPOL
- COLREGS
- PSC cases
- Company SMS
- Shipboard manuals

---

# 计划中的功能

## 驾驶台辅助

- 航海日志生成
- 值班摘要
- 航海英语润色
- 航次记录整理

## 轮机部辅助

- 维修记录生成
- 故障报告辅助
- 备件申请生成

## PSC / SMS 辅助

- 检查项目提醒
- 证书到期提醒
- SMS 文件搜索

## AI 知识库

本地海事知识查询：

- SOLAS
- MARPOL
- COLREGS
- PSC 案例
- 公司 SMS
- 船舶手册

---

# Example

Input:

```text
2300值班，右前方渔船群，左改向15度避让。
```

Output:

```text
2300:
Altered course 15 degrees to port to avoid fishing vessels on starboard bow.
Situation under control.
```

---

# Technical Direction

Planned stack:

- Python
- FastAPI
- Ollama
- DeepSeek / Qwen
- SQLite
- Local Web UI

---

# 技术方向（规划中）

- Python
- FastAPI
- Ollama
- DeepSeek / Qwen
- SQLite
- 本地 Web UI

---

# Project Status

Early concept stage.

Currently researching:

- Maritime workflow
- Shipboard documentation
- Offline AI deployment
- Maritime terminology datasets

---

# 项目状态

当前仍处于早期概念阶段。

目前主要研究：

- 船员工作流
- 船舶文书结构
- 离线 AI 部署
- 海事专业术语数据

---

# Open Source

This project will remain open-source.

Contributions, ideas, and maritime experience sharing are welcome.

Especially welcome:

- Seafarers
- Maritime students
- Marine engineers
- AI developers
- Maritime English learners

---

# 开源说明

本项目将保持开源。

欢迎：

- 船员
- 航海学生
- 轮机员
- AI 开发者
- 海事英语学习者

一起参与改进。

---

# Disclaimer

This project is experimental and is NOT intended to replace professional judgment, navigational responsibility, or official shipboard procedures.

Always follow:

- Company SMS
- International regulations
- Master's orders
- Official bridge procedures

---

# 免责声明

本项目仅作为实验性辅助工具。

不能替代：

- 船长决策
- 航行值班责任
- 公司 SMS
- 国际海事规则
- 正式船舶程序

请始终遵守：

- 国际规则
- 公司体系
- 驾驶台规范
- 船长指令

---

# Author

Maritime student from China.  
Learning AI while learning navigation.

中国航海学生。  
一边学习航海，一边学习 AI。