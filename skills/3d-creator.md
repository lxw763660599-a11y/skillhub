---
name: 3D 场景快速生成
description: 文字描述生成 3D 模型和场景，支持多格式导出，适用于游戏和 AR/VR。
category: 设计
tags: [3D, 建模, 游戏, AR/VR]
version: 1.0.0
author: 3d-creator
---

# 3D 场景快速生成

自然语言描述生成高质量 3D 模型，直接导入游戏引擎。

## 核心功能

- **文字生 3D** — "一张圆形的木质桌子" → 3D 模型
- **PBR 材质** — 自动生成金属、木材、布料等真实材质
- **多格式导出** — glTF / OBJ / FBX / USD
- **面数优化** — 自动 LOD，适配移动端到桌面端
- **引擎插件** — Blender / Unity / Unreal 原生插件
- **场景拼接** — 多个模型智能组合为完整场景

## 使用方式

```bash
# 生成单个模型
3d-gen model "现代风格沙发，灰色布艺" --format gltf

# 生成完整场景
3d-gen scene "赛博朋克街道，霓虹灯，潮湿路面" --unity

# 批量生成道具
3d-gen batch props.txt --output ./assets/
```

## 适用场景

- 游戏道具/场景快速原型
- AR/VR 内容创作
- 电商 3D 商品展示
- 建筑可视化
