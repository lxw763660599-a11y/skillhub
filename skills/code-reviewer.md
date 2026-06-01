---
name: AI 代码审查助手
description: 基于 AI 的智能代码审查工具。自动检测 bug、安全漏洞、性能问题，并提供修复建议。
category: 开发
tags: [代码审查, GitHub, 安全, 自动化]
version: 1.0.0
author: code-reviewer
---

# AI 代码审查助手

自动 PR Review，检测安全漏洞和代码异味，秒级反馈修复建议。

## 核心功能

- **自动 PR Review** — 提交 PR 后自动审查，秒级反馈
- **安全漏洞检测** — 识别 SQL 注入、XSS、敏感信息泄露等
- **代码异味分析** — 检测重复代码、过长函数、复杂度过高
- **一键修复** — 提供可直接应用的修复建议
- **多平台支持** — GitHub / GitLab / Gitee 全平台兼容
- **自定义规则** — 团队自定义审查规则

## 使用方式

```bash
# 审查单个文件
ai-review check src/app.py

# 审查整个 PR
ai-review pr https://github.com/user/repo/pull/123

# 生成审查报告
ai-review report --format markdown > review.md
```

## 集成配置

```yaml
# .ai-review.yml
rules:
  - security
  - performance
  - style
severity:
  security: error
  style: warning
ignore:
  - "**/vendor/**"
  - "**/test/**"
```

## 适用场景

- 日常 PR Review 加速
- 新成员代码规范检查
- CI/CD 流水线集成
