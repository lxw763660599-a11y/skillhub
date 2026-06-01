---
name: 个人知识库构建器
description: 自动整理笔记、书签、阅读记录，构建 AI 可搜索的第二大脑。
category: 效率
tags: [知识管理, 笔记, AI, 图谱]
version: 1.0.0
author: second-brain
---

# 个人知识库构建器

打造你的第二大脑 — 自动整理所有信息，AI 智能检索和关联。

## 核心功能

- **自动抓取** — 网页/文档/书签/聊天记录一键导入
- **AI 自动分类** — 智能标签和文件夹自动整理
- **双向链接** — 关联笔记自动发现和建立
- **知识图谱** — 可视化你的知识网络
- **自然语言搜索** — "上次看到的关于微服务的文章"
- **每日回顾** — 随机推送旧笔记，强化记忆

## 使用方式

```bash
# 启动知识库
kb start

# 导入内容
kb import https://example.com/article
kb import ~/Documents/notes/
kb import --notion

# 搜索
kb search "react 性能优化"
kb ask "我们上次讨论的数据库方案是什么？"

# 每日回顾
kb review today
```

## 适用场景

- 学习笔记管理
- 研究资料整理
- 个人阅读记录
- 团队知识沉淀
