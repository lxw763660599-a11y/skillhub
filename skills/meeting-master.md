---
name: 智能会议记录官
description: 自动录音、转写、总结会议内容。生成待办事项和会议纪要。
category: AI
tags: [会议, 转录, 总结, 效率]
version: 1.0.0
author: meeting-master
---

# 智能会议记录官

实时语音转文字，AI 自动生成会议摘要和待办事项。

## 核心功能

- **实时语音转文字** — 准确率 >98%，支持中英双语
- **AI 会议摘要** — 自动提取关键讨论点和结论
- **说话人识别** — 自动区分不同发言人
- **待办生成** — 从讨论中提取 Action Items
- **50+ 语言翻译** — 跨国会议无障碍
- **一键导出** — Notion / 飞书 / 钉钉文档

## 使用方式

```bash
# 开始录音转写
meeting-ai record --lang zh,en

# 导入音频文件
meeting-ai transcribe meeting.mp3 --output summary.md

# 生成会议纪要
meeting-ai summarize session-2026.wav
```

## 适用场景

- 日常会议记录与纪要
- 客户访谈转录
- 跨国团队沟通
- 培训课程笔记
