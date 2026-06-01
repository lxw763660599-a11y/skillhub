---
name: 社交媒体内容管家
description: AI 辅助社交媒体运营。根据品牌调性生成内容、优化发布时间、分析数据。
category: 写作
tags: [社交媒体, 内容, 运营, 分析]
version: 1.0.0
author: social-ai
---

# 社交媒体内容管家

AI 驱动社交媒体运营，从内容创作到数据分析全覆盖。

## 核心功能

- **品牌调性生成** — 设定品牌人格，内容风格一致
- **智能排期** — 分析粉丝活跃时间推荐最佳发布点
- **多平台发布** — 小红书/公众号/微博/抖音/Twitter
- **互动分析** — 粉丝增长、互动率、传播路径
- **竞品洞察** — 竞品内容策略分析
- **热点追踪** — 自动提醒相关热点话题

## 使用方式

```bash
# 生成一周内容规划
social-ai plan --brand "科技创业" --platforms wechat,xiaohongshu

# 生成帖子草稿
social-ai create "AI 产品上线" --tone professional --platform wechat

# 分析数据
social-ai analytics --platform xiaohongshu --period last-30-days
```

## 品牌调性配置

```yaml
brand:
  name: 科技先锋
  tone: 专业且有温度
  keywords: [AI, 效率工具, 产品思考]
  emoji_style: moderate
```

## 适用场景

- 个人 IP / 自媒体运营
- 品牌社媒矩阵管理
- KOL 内容策略
