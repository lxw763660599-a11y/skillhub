---
name: 浏览器自动化工作流
description: 可视化浏览器自动化。录制操作步骤自动回放，无需代码。
category: 效率
tags: [自动化, 浏览器, RPA, 无代码]
version: 1.0.0
author: browser-bot
---

# 浏览器自动化工作流

可视化录制浏览器操作，自动回放执行，无需编写代码。

## 核心功能

- **可视化录制** — 点击录制按钮，操作浏览器，自动生成工作流
- **条件判断** — 等待元素出现、判断页面内容
- **循环执行** — 批量处理多页数据
- **定时任务** — 每日/每周自动执行
- **智能重试** — 页面加载失败自动重试
- **数据抓取** — 提取页面结构化数据导出 Excel/JSON

## 使用方式

```bash
# 启动录制模式
browser-bot record

# 回放工作流
browser-bot replay daily-check.workflow

# 定时执行
browser-bot schedule daily-check.workflow --at "09:00" --weekday

# 数据抓取
browser-bot scrape "https://example.com/list" --pagination --output data.json
```

## 工作流示例

```yaml
name: 每日签到
steps:
  - navigate: https://example.com
  - click: "登录按钮"
  - type: { selector: "#email", value: "user@example.com" }
  - type: { selector: "#password", value: "{{ENV_PASSWORD}}" }
  - click: "提交"
  - wait: 2000
  - click: "签到"
  - screenshot: success.png
```

## 适用场景

- 每日签到/打卡
- 数据采集和监控
- 表单批量填写
- 跨系统流程自动化
