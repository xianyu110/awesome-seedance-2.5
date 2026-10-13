---
name: seedance-25-character-lock-i2v
description: "Seedance 2.5 character-lock I2V workflow: freeze hero/extra/boss stills with an image model first (e.g. GPT Image), then drive physics in Seedance 2.5 — pattern from TomaAIbijo Comiket→GTA chase plus transform cases. Use for 图生视频, character consistency, I2V, cosplay to chase."
license: MIT
metadata:
  author: xianyu110
  version: 1.0.0
  model: Seedance 2.5
  gallery: https://xianyu110.github.io/awesome-seedance-2.5
---

# Seedance 2.5 · Character-Lock I2V

**Images hold identity. Seedance owns physics.**

## Pipeline

1. **Still pass:** generate or photograph hero / extras / key locations
2. **Label refs:** `@图片1` hero, `@图片2` extra, `@图片3` location plate
3. **Video pass:** Seedance 2.5 prompt that only restates locked traits + action timeline
4. **Forbid:** wardrobe drift, face morph, extra limbs; allow physics, cloth, impacts

## Demo to study

### Comiket photoshoot turns into a GTA chase / 漫展被拍到破防：GTA 风追战（图生视频）

- **Author:** [@TomaAIbijo](https://x.com/TomaAIbijo)
- **Post:** https://x.com/TomaAIbijo/status/2099714890671984742
- **Gallery:** [https://xianyu110.github.io/awesome-seedance-2.5/#2099714890671984742](https://xianyu110.github.io/awesome-seedance-2.5/#2099714890671984742)
- **Platform:** Pollo AI
- **Duration:** 51s · likes 162 · views 16387 (snapshot)
- **Category:** Character & I2V / 角色一致 / 图生视频

先用 GPT Image 2.5 固化主角/杂鱼/Boss 场景图，再交给 Seedance 2.5 做视频。作者强调「图像参照稳住人设，视频模型负责物理」。


Also see transform one-take: `seedance-25-mech-backpack`.

## Prompt glue

```text
Use @image1 as the only hero identity. Do not redesign face, hair, or outfit.
Seedance 2.5 handles motion, physics, and camera only.
Action: <chase / fight / walk cycle beats>
```
