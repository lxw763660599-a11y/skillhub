---
name: Excel 智能分析引擎
description: 用自然语言操作 Excel。说句话就能自动生成图表、透视表和洞察报告。
category: 数据
tags: [Excel, 数据分析, 自然语言, 可视化]
version: 1.0.0
author: data-wizard
---

# Excel 智能分析引擎

用自然语言提问，AI 自动分析数据、生成图表和报告，无需写公式。

## 核心功能

- **自然语言操控** — "帮我分析销售趋势" 即出结果
- **自动透视表** — 按维度自动汇总数据
- **智能图表** — 根据数据特征推荐最佳图表类型
- **异常检测** — 自动标出异常值和趋势突变
- **一键报告** — 生成图文并茂的数据分析报告
- **多源导入** — CSV / JSON / SQL / API

## 使用方式

```bash
# 命令行分析
excel-ai analyze sales.xlsx "各区域季度增长情况"

# Python API
from excel_ai import Analyst
analyst = Analyst("sales.xlsx")
analyst.ask("哪些产品利润率最高？")
analyst.chart("利润分布", type="bar")
analyst.report("季度销售分析报告")
```

## 适用场景

- 销售/运营数据日常分析
- 财务数据快速透视
- 库存和供应链监控
- 营销活动效果评估
