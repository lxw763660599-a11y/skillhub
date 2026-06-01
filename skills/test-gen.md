---
name: 自动化测试生成器
description: 基于代码自动生成单元测试和集成测试，覆盖主流测试框架。
category: 开发
tags: [测试, 自动化, Jest, Pytest]
version: 1.0.0
author: test-gen
---

# 自动化测试生成器

分析代码自动生成高质量测试用例，覆盖率 >90%。

## 核心功能

- **智能测试生成** — 分析函数签名和逻辑自动生成用例
- **多框架支持** — Jest / Pytest / JUnit / Go test / RSpec
- **边界值覆盖** — 自动覆盖空值、极值、异常路径
- **Mock 自动生成** — 自动为依赖创建 Mock
- **CI/CD 集成** — GitHub Actions / GitLab CI 一键配置
- **覆盖率报告** — 自动生成覆盖率和未覆盖行

## 使用方式

```bash
# 为文件生成测试
test-gen generate src/utils.js --framework jest

# 为整个项目生成测试
test-gen generate --project ./myapp --framework pytest

# 只补充未覆盖的部分
test-gen fill-gaps --coverage lcov.info
```

## 适用场景

- 遗留代码补充测试
- 新项目测试脚手架
- 提高测试覆盖率
- CI 流水线质量卡点
