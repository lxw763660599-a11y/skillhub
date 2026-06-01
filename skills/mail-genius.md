---
name: AI 邮件助手
description: 智能邮件撰写、分类、摘要。根据上下文自动回复，自动整理收件箱。
category: 写作
tags: [邮件, Gmail, 自动化, AI]
version: 1.0.0
author: mail-genius
---

# AI 邮件助手

AI 理解邮件上下文，自动生成回复、整理收件箱。

## 核心功能

- **上下文感知回复** — 读完整封邮件，理解语境后生成回复
- **自动分类** — 重要/通知/垃圾/社交，智能分区
- **邮件摘要** — 长邮件一键生成要点
- **定时发送** — 设置最佳发送时间
- **跟进提醒** — 未回复邮件自动提醒
- **模板推荐** — 根据场景推荐回复模板

## 使用方式

```bash
# 连接邮箱
mail-ai connect gmail

# 生成回复
mail-ai reply --to "offer@company.com" --tone professional

# 摘要
mail-ai summarize --from "boss@company.com" --since yesterday

# 整理收件箱
mail-ai organize --archive old --unsubscribe spammy

# 定时发送
mail-ai send draft.md --at "tomorrow 9:00"
```

## 适用场景

- 日常邮件处理和回复
- 客户沟通邮件草拟
- 订阅邮件管理
- 招聘/商务邮件
