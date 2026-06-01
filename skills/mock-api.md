---
name: Mock API服务
description: 输入数据结构描述，快速生成可调用的 Mock API 接口
category: 开发
tags: [API, Mock, 后端, 接口, 测试, 开发]
version: 1.0
---

# Mock API 服务

描述你需要的 API 接口，自动生成可调用的 Mock 服务，支持增删改查、分页、筛选。

## 功能

- **快速生成**：描述数据结构和接口行为 → 生成可立即调用的 API
- **完整 CRUD**：GET/POST/PUT/DELETE 全支持
- **高级特性**：分页、排序、筛选、关联查询、延迟模拟
- **数据生成**：自动生成逼真的中文测试数据（人名、地址、手机号等）
- **错误模拟**：自定义错误码和响应，测试异常处理

## 使用方法

```
帮我创建一个博客系统的 Mock API：

文章（posts）：
- id, title, content, author, tags, created_at
- 支持分页、按标签筛选、关键词搜索

评论（comments）：
- id, post_id, author, content, created_at
- 支持按文章ID查询

生成50篇测试文章和200条评论
```

## 接口示例

```
GET  /api/posts?page=1&tag=tech&search=AI
GET  /api/posts/:id
POST /api/posts
GET  /api/posts/:id/comments
POST /api/posts/:id/comments
```

## 适用场景

- 前后端并行开发（后端还没写好）
- 原型演示和 POC
- 自动化测试
- 教学和培训

## 技巧

- 指定中文测试数据：用户用中文名、手机号是138开头
- 需要关联数据时明确外键关系
- 告诉它"需要 token 鉴权"，会自动加上登录接口
