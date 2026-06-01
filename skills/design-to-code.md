---
name: 设计稿转代码
description: 上传设计稿截图，自动生成前端代码（HTML/CSS/React/Vue）
category: 开发
tags: [设计稿, 前端, HTML, React, Vue, UI还原]
version: 1.0
---

# 设计稿转代码

上传 UI 设计稿截图或 Figma 链接，自动生成高质量前端代码。

## 功能

- **截图转代码**：上传 PNG/JPG 截图直接生成代码
- **多框架支持**：HTML+CSS / React / Vue / Tailwind
- **组件拆分**：自动识别可复用组件并拆分
- **响应式适配**：自动生成移动端/平板/桌面适配
- **设计系统提取**：自动提取颜色、字体、间距为 CSS 变量

## 使用方法

```
帮我把这个设计稿转成 React + Tailwind 代码：[上传 design.png]

要求：
- 使用 React + TypeScript
- 组件化拆分
- 响应式适配手机和桌面
- 暗色模式支持
```

## 输出结构

```
components/
  Header.tsx
  Hero.tsx
  FeatureGrid.tsx
  Footer.tsx
styles/
  variables.css
  globals.css
App.tsx
```

## 适用场景

- 设计师交付 → 开发还原
- 竞品页面快速复刻
- 落地页快速搭建
- 原型转 MVP

## 技巧

- 提供 Figma 链接比截图还原度更高
- 指定像素级还原还是允许优化调整
- 复杂页面分区域上传，逐块生成
