---
name: API 模拟服务器
description: 零配置 REST/GraphQL API Mock 工具。自动生成模拟数据，支持延迟模拟和错误注入。
category: 开发
tags: [API, Mock, 测试, 开发]
version: 1.0.0
author: mock-api
---

# API 模拟服务器

零配置启动 Mock API，支持 REST、GraphQL、WebSocket。

## 核心功能

- **零配置启动** — 定义接口结构，秒级启动 Mock 服务
- **智能数据生成** — 自动生成逼真的模拟数据（中文名、地址、金额等）
- **多协议支持** — REST / GraphQL / WebSocket
- **延迟模拟** — 模拟真实网络延迟
- **错误注入** — 随机返回 4xx/5xx 测试容错
- **自动文档** — Swagger / GraphiQL 文档自动生成

## 使用方式

```json
// mock.config.json
{
  "endpoints": {
    "GET /api/users": {
      "response": "users.json",
      "delay": 200
    },
    "POST /api/login": {
      "response": { "token": "{{uuid}}", "user": "{{user}}" },
      "errorRate": 0.1
    }
  }
}
```

```bash
# 启动 Mock 服务
mock-api start --port 3000

# 生成模拟数据
mock-api gen users --count 100 --locale zh
```

## 适用场景

- 前后端并行开发
- 自动化测试
- 原型演示
