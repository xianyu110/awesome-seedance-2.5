---
name: seedance-25-music-mv-longform
description: "Seedance 2.5 long-form MV skill inspired by kraqvoid Flova workflow: agent-driven shot lists, character bibles, rough cut, full-song length (~4 min) assembled from Seedance 2.5 clips. Use for MV, music video, Flova, long-form Seedance."
license: MIT
metadata:
  author: xianyu110
  version: 1.0.0
  model: Seedance 2.5
  gallery: https://xianyu110.github.io/awesome-seedance-2.5
---

# Seedance 2.5 · Music MV Long-form

Treat the agent as a **director's desk**, not a one-prompt lottery.

## Pipeline

1. Lyrics / mood board → act breakdown
2. Character bible + recurring locations
3. Per-shot Seedance 2.5 prompts (10–30s each)
4. Rough cut to music peaks
5. Grade / stitch

## Demo

### MV 'One Light-Year Away' on Flova / MV《一光年、となり》：Flova 全流程长片

- **Author:** [@kraqvoid](https://x.com/kraqvoid)
- **Post:** https://x.com/kraqvoid/status/2104915254430056833
- **Gallery:** [https://xianyu110.github.io/awesome-seedance-2.5/#2104915254430056833](https://xianyu110.github.io/awesome-seedance-2.5/#2104915254430056833)
- **Platform:** Flova
- **Duration:** 241s · likes 22 · views 4217 (snapshot)
- **Category:** Music & Long-form / 音乐 / 长片

约 4 分钟 MV。作者用 Claude 驱动 Flova 代理完成分镜、角色、镜头与粗剪，强调「像在做导演」。全片 Seedance 2.5。


## Per-shot card

```text
SHOT <n> | DUR <s> | ASPECT 16:9
ON MODEL Seedance 2.5
SYNC: lyric line / bar numbers
VISUAL: …
CAMERA: …
AUDIO: music bed provided in edit (generate dry or with scratch score?)
```
