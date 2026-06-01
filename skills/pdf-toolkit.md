---
name: PDF 全能工具箱
description: 合并、拆分、压缩、转换 PDF 的全能工具。支持 OCR 文字识别和批量处理。
category: 效率
tags: [PDF, 文档, 转换, OCR]
version: 1.0.0
author: pdf-toolkit
---

# PDF 全能工具箱

合并、拆分、压缩、转换 PDF，一站式解决所有 PDF 需求。

## 核心功能

- **合并 PDF** — 将多个 PDF 文件按顺序合并为一个
- **拆分 PDF** — 按页数或书签拆分 PDF
- **PDF 转 Word/Excel/PPT** — 高质量格式转换，保留排版
- **OCR 文字识别** — 扫描件也能提取文字
- **压缩 PDF** — 批量压缩，保持画质
- **完全本地处理** — 文件不上传，保护隐私

## 使用方式

```bash
# 合并 PDF
pdf-tool merge file1.pdf file2.pdf -o merged.pdf

# 拆分 PDF（每 5 页一组）
pdf-tool split document.pdf --every 5

# PDF 转 Word
pdf-tool convert report.pdf --format docx

# OCR 识别
pdf-tool ocr scanned.pdf -o readable.pdf

# 压缩 PDF
pdf-tool compress large.pdf --quality 80
```

## 适用场景

- 合同/报告合并归档
- 扫描件转可编辑文档
- 批量压缩减少文件体积
- 提取 PDF 中的图片和文字
