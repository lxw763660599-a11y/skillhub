---
name: 数据可视化仪表盘
description: 拖拽式数据可视化构建器。连接任意数据源，秒级生成专业仪表盘。
category: 数据
tags: [可视化, 仪表盘, 数据, 拖拽]
version: 1.0.0
author: viz-builder
---

# 数据可视化仪表盘

拖拽构建图表，连接任意数据源，实时动态刷新。

## 核心功能

- **拖拽构建** — 拖拽图表组件到画布，所见即所得
- **40+ 图表类型** — 折线/柱状/饼图/热力图/地图/桑基图
- **多数据源** — SQL / REST API / Excel / CSV / 实时流
- **实时刷新** — WebSocket 推送，秒级更新
- **交互联动** — 点击图表联动筛选其他图表
- **一键分享** — 生成分享链接或嵌入 iframe

## 使用方式

```bash
# 启动仪表盘编辑器
viz start --port 3000

# 连接数据源
viz connect mysql://localhost:3306/mydb

# 导出配置
viz export dashboard.json
```

```sql
-- 直接 SQL 查询驱动图表
SELECT date, revenue FROM sales WHERE date > '2026-01-01'
```

## 适用场景

- 业务数据实时监控大屏
- 运营周报数据可视化
- 产品数据看板
- 股市/行情实时展示
