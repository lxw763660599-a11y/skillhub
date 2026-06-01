---
name: 前端组件库 AI 版
description: AI 驱动的 UI 组件生成器。描述需求，自动生成 React/Vue 组件代码。
category: 开发
tags: [UI, 组件, React, 前端, shadcn]
version: 1.0.0
author: ui-blocks
---

# 前端组件库 AI 版

自然语言描述 UI 需求，AI 直接生成即用组件代码。

## 核心功能

- **需求到组件** — "一个带搜索和分页的数据表格" → React 组件
- **多框架** — React / Vue / Svelte / Solid 四框架支持
- **设计系统适配** — shadcn/ui / Ant Design / MUI 风格
- **响应式** — 自动处理移动端适配
- **无障碍** — ARIA 属性自动添加
- **Storybook 生成** — 组件文档自动输出

## 使用方式

```bash
# 生成组件
ui-gen create "用户信息卡片，包含头像、姓名、邮箱、操作按钮"
--framework react
--design shadcn

# 批量生成
ui-gen batch components.txt --output ./src/components/

# 预览
ui-gen preview UserCard
```

```
# components.txt
✅ 数据表格（排序、筛选、分页）
✅ 搜索栏（联想搜索、历史记录）
✅ 步骤引导（4 步）
✅ 通知中心（分类、已读未读）
```

## 适用场景

- 后台管理系统快速搭建
- 设计稿到代码的快速实现
- 组件库批量生成
- 原型到 MVP 加速
