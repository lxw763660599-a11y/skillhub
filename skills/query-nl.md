---
name: SQL 自然语言查询
description: 用中文/英文自然语言查询数据库，自动生成优化 SQL。
category: 数据
tags: [SQL, 自然语言, 数据库, 查询]
version: 1.0.0
author: query-nl
---

# SQL 自然语言查询

用自然语言对话数据库，自动生成并执行优化后的 SQL。

## 核心功能

- **自然语言转 SQL** — "上月销售额 TOP10 产品" → 直接出结果
- **自动优化** — 生成索引建议，高亮慢查询
- **多数据库支持** — MySQL / PostgreSQL / Snowflake / BigQuery
- **结果可视化** — 查询结果自动图表展示
- **学习模式** — 展示 SQL 生成过程，边用边学
- **安全模式** — 只读模式可选，防止误删

## 使用方式

```bash
# 交互式查询
sql-nl connect mysql://localhost/mydb
> 去年每个月的订单总额？

# 单次查询
sql-nl query "近30天活跃用户数" --db production

# 安全只读
sql-nl connect --readonly postgresql://db.example.com/app
```

## 示例

| 自然语言 | 生成的 SQL |
|---------|------------|
| 销售额最高的 5 个城市 | `SELECT city, SUM(amount) FROM orders GROUP BY city ORDER BY 2 DESC LIMIT 5` |
| 上月同比去年增长了多少 | `SELECT (curr - prev) / prev * 100 FROM (SELECT ...) AS t` |

## 适用场景

- 运营/产品人员自助查数据
- 快速数据探索
- SQL 学习和复习
