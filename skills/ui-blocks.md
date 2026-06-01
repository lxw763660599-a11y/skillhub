---
name: UI组件生成器
description: 描述需要的UI组件，自动生成可直接使用的React/Vue组件代码
category: 开发
tags: [UI, 组件, React, Vue, 前端, 组件库]
version: 1.0
---

# UI 组件生成器

用自然语言描述你需要的 UI 组件，自动生成可直接使用的组件代码。

## 功能

- **多框架**：React / Vue / Svelte / 原生 HTML
- **样式方案**：Tailwind CSS / CSS Modules / styled-components
- **完整输出**：组件代码 + 类型定义 + 使用示例 + 单元测试
- **无障碍**：自动添加 ARIA 标签、键盘导航支持
- **响应式**：自动适配手机/平板/桌面

## 使用方法

```
帮我创建一个"标签输入框"组件：

功能：
- 输入文字后按回车添加标签
- 点击x删除标签
- 最多10个标签
- 重复标签自动去重并提示
- 支持从建议列表中选择

技术栈：React + TypeScript + Tailwind
```

## 输出内容

```
TagInput/
  TagInput.tsx     ← 组件主文件
  TagInput.test.tsx ← 单元测试
  README.md       ← Props 文档和使用示例
```

## 常用组件

表格（排序/筛选/分页）、弹窗、下拉多选、文件上传、步骤条、评分组件、日历选择、富文本编辑器、图片轮播、骨架屏

## 技巧

- 描述"像XXX组件一样"加速生成
- 指定组件库（Ant Design/Element Plus/Shadcn）
- 告诉它现有项目的技术栈，生成代码直接兼容
