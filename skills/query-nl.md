---
name: SQL自然语言查询
description: 用中文描述查询需求，自动生成SQL语句并执行
category: 数据
tags: [SQL, 数据库, 查询, 数据分析, 自然语言]
version: 1.0
---

# SQL 自然语言查询

用中文描述你想要的查询结果，自动生成并执行 SQL 语句。

## 功能

- **中文转SQL**：自然语言描述 → 标准SQL语句
- **多数据库支持**：MySQL / PostgreSQL / SQLite / SQL Server / ClickHouse
- **查询优化**：分析慢查询，给出索引优化建议
- **结果可视化**：查询结果自动生成图表
- **安全审查**：检测潜在的性能问题和注入风险

## 使用方法

```
查一下过去30天，消费金额最高的10个用户，
显示用户名、总消费金额、订单数，
按消费金额从高到低排序
```

生成SQL：
```sql
SELECT 
  u.username,
  SUM(o.amount) AS total_spent,
  COUNT(o.id) AS order_count
FROM users u
JOIN orders o ON u.id = o.user_id
WHERE o.created_at >= DATE_SUB(NOW(), INTERVAL 30 DAY)
GROUP BY u.id, u.username
ORDER BY total_spent DESC
LIMIT 10;
```

## 适用场景

- 临时数据查询（不用找开发）
- 运营拉数据做分析
- 学习SQL（看它怎么翻译的）
- 慢查询优化

## 技巧

- 提供表结构能大幅提高准确率
- 不确定的表名可以用中文描述，它会猜
- 对结果不放心让它"加注释解释每行SQL的含义"
