---
name: 日程智能规划器
description: AI 自动规划日程，输入待办自动生成最优时间安排，支持日历同步。
category: 效率
tags: [日程, 规划, 日历, 时间管理]
version: 1.0.0
author: time-master
---

# 日程智能规划器

AI 理解你的任务优先级和习惯，自动优化每日时间安排。

## 核心功能

- **AI 自动排程** — 输入任务列表，AI 生成最优时间表
- **优先级感知** — 自动调整：紧急 > 重要 > 普通
- **日历同步** — Google / Apple / Outlook 日历双向同步
- **冲突检测** — 时间冲突自动提示和重排
- **习惯学习** — 根据你的工作时间偏好优化
- **周报自动生成** — 总结本周完成情况

## 使用方式

```bash
# 交互式规划
schedule-ai plan

# 从任务列表生成安排
schedule-ai optimize tasks.md --calendar google

# 生成周报
schedule-ai report --week 2026-W22
```

```yaml
# tasks.yaml
- 审查产品需求文档  4h  重要  截止周三
- 周会             1h  固定  周一10:00
- 代码审查          1h  日常
- 写技术方案         3h  重要  截止周五
```

## 适用场景

- 个人日常时间管理
- 团队项目排期
- 会议时间协调
