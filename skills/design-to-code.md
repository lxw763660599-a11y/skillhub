---
name: 设计稿转代码
description: 一键将 Figma/Sketch 设计稿转换为高质量前端代码。支持 React、Vue、HTML。
category: 设计
tags: [Figma, 前端, React, Vue, 自动布局]
version: 1.0.0
author: design-to-code
---

# 设计稿转代码

将 Figma/Sketch 设计稿直接转为生产级前端组件代码。

## 核心功能

- **Figma/Sketch 一键导出** — 选中设计稿即生成代码
- **多框架支持** — React / Vue / Angular / Svelte
- **响应式自动适配** — 处理断点和弹性布局
- **Design Token 保留** — 颜色、字号等设计变量原样输出
- **CSS 方案灵活** — Tailwind / CSS Modules / styled-components

## 使用方式

```bash
# 从 Figma URL 生成 React 组件
d2c generate https://figma.com/file/xxx --framework react

# 导出整个页面
d2c export page --platform figma --output ./src/pages/

# 生成响应式组件
d2c generate button.fig --responsive --tailwind
```

## 适用场景

- 设计稿快速还原
- 组件库批量生成
- 多端适配代码输出
