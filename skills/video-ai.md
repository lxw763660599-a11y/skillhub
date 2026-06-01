---
name: 视频智能剪辑师
description: AI 自动剪辑视频，识别精彩片段，自动加字幕和配乐。
category: AI
tags: [视频, 剪辑, 字幕, AI]
version: 1.0.0
author: video-ai
---

# 视频智能剪辑师

AI 理解视频内容，自动剪辑、加字幕、配乐。

## 核心功能

- **高光识别** — 自动检测精彩片段和关键帧
- **智能字幕** — 语音识别生成时间轴精准字幕
- **踩点配乐** — 根据画面节奏自动匹配 BGM
- **横竖屏适配** — 横屏视频一键转竖屏（智能构图）
- **多平台导出** — 抖音 / B站 / YouTube / 视频号预设
- **批量处理** — 一次处理多个视频素材

## 使用方式

```bash
# 自动剪辑
video-ai clip raw-footage.mp4 --duration 60 --highlight

# 添加字幕
video-ai subtitle video.mp4 --lang zh --style modern

# 横屏转竖屏
video-ai convert landscape.mp4 --aspect 9:16 --smart-crop

# 批处理
video-ai batch ./raw/ --output ./clips/ --platform douyin
```

## 适用场景

- 短视频创作者日常剪辑
- 直播回放精华提取
- 课程视频字幕添加
- 多平台内容分发
