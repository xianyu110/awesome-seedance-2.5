---
name: seedance-25-fight-previz-pipeline
description: "Seedance 2.5 fight pipeline from ni_naai: do not feed hard previz motion blindly — parse previz to text (e.g. Astra), reference only character + background stills, generate 480p then upscale to 1080p. Use for 格斗, previz, fight scene, Higgsfield Seedance 2.5."
license: MIT
metadata:
  author: xianyu110
  version: 1.0.0
  model: Seedance 2.5
  gallery: https://xianyu110.github.io/awesome-seedance-2.5
---

# Seedance 2.5 · Fight Previz → Text → Refs

Community workflow that improves natural motion vs raw motion-transfer.

## Steps (from public author notes)

1. Block the fight in any previz tool
2. Convert previz → textual shot list (author used Astra-style parse)
3. Keep **only** character + background image refs for Seedance 2.5
4. Generate draft at 480p for iteration speed
5. Upscale / re-render hero takes at 1080p

## Why

Feeding previz video directly can "carry hard / robotic motion". Text + still refs let Seedance invent more natural physics.

## Demo

### 90s fight scene: previz to text to refs / 90 秒格斗：预演→文字化→角色/背景参照

- **Author:** [@ni_naai](https://x.com/ni_naai)
- **Post:** https://x.com/ni_naai/status/2099124910887141825
- **Gallery:** [https://xianyu110.github.io/awesome-seedance-2.5/#2099124910887141825](https://xianyu110.github.io/awesome-seedance-2.5/#2099124910887141825)
- **Platform:** Higgsfield
- **Duration:** 90s · likes 33 · views 1667 (snapshot)
- **Category:** Cinematic & Action / 电影感 / 动作

Higgsfield × Seedance 2.5。作者分享工作流：直接喂预演会「带着硬动作」；用 Astra 解析成文后只参照角色与背景，动作更自然；480p 生成再升到 1080p。


## Agent output format

Deliver: (a) beat sheet, (b) identity locks, (c) 480p trial prompt, (d) 1080p final prompt.
