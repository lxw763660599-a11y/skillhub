---
name: 图片背景智能去除
description: AI 驱动背景去除，发丝级精度，支持批量处理和背景替换。
category: 设计
tags: [图片处理, 抠图, 批量, AI]
version: 1.0.0
author: bg-remover
---

# 图片背景智能去除

AI 精准识别主体，发丝级别抠图，本地处理无需上传。

## 核心功能

- **发丝级精度** — 头发、宠物毛发、复杂边缘精准识别
- **批量处理** — 一次处理 100 张图片
- **背景替换** — 透明 / 纯色 / 自定义图片背景
- **格式支持** — PNG / JPG / WebP / AVIF
- **本地处理** — 完全离线，不传服务器
- **API 调用** — 程序化批量处理

## 使用方式

```bash
# 去除单张图片背景
bg-remover remove photo.jpg -o transparent.png

# 批量处理
bg-remover batch ./input/ --output ./output/

# 替换背景
bg-remover replace product.jpg --bg white --output result.png

# API 模式
bg-remover serve --port 8080
```

## 适用场景

- 电商产品图批量处理
- 证件照制作
- 社交媒体内容创作
- 设计素材准备
