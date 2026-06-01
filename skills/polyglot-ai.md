---
name: 多语言实时翻译
description: 100+ 语言实时翻译，支持文本、语音、图片、文档，保持原文格式。
category: AI
tags: [翻译, 多语言, 实时, AI]
version: 1.0.0
author: polyglot-ai
---

# 多语言实时翻译

100+ 语言互译，支持文本/语音/图片/文档，翻译质量媲美人工。

## 核心功能

- **100+ 语言互译** — 覆盖大部分国家语言
- **多模态输入** — 文本、语音、图片 OCR、PDF/Word 文档
- **格式保留** — PDF/Word 翻译后排版不变
- **实时语音翻译** — 延迟 <1 秒，同声传译体验
- **专业术语库** — 自定义行业术语映射
- **离线支持** — 常用语言离线翻译包

## 使用方式

```bash
# 文本翻译
translate text "Hello World" --from en --to zh

# 文档翻译
translate doc report.pdf --to ja --output report-ja.pdf

# 实时语音
translate live --from zh --to en

# 批量翻译
translate batch ./docs/ --from zh --to en,ja,ko
```

## 适用场景

- 跨国会议同声传译
- 技术文档多语言本地化
- 海外内容阅读
- 跨境电商商品翻译
