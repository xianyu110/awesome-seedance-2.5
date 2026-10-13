---
name: seedance-25-dv-day-in-life
description: "Seedance 2.5 DV / home-video day-in-the-life skill with the public fuji_ai_ Seoul walk prompt: early-2000s handheld shake, AF hunting, ambience-only audio, character-ref lock. Use for DV camera, 家用DV, lifestyle vlog, day in the life, Seedance 2.5 prompt."
license: MIT
metadata:
  author: xianyu110
  version: 1.0.0
  model: Seedance 2.5
  gallery: https://xianyu110.github.io/awesome-seedance-2.5
---

# Seedance 2.5 · DV Day-in-the-Life

Reproduce the **early-2000s home DV** lifestyle look on Seedance 2.5 — shaky, imperfect, ambience-only.

## Inputs

1. Character reference image (face lock)
2. City / neighborhood vibe
3. 3–6 mundane beats (leave home → greet neighbors → park → snack → bye)
4. Duration (default 30s) and aspect (often 9:16 or 16:9)

## Workflow

1. Split prompt into: setup+character · first half beats · second half beats · DV look+audio
2. Forbid BGM, narration, subs, beauty filter, CG, commercial polish
3. Keep one continuous "friend filming" POV energy

## Public recipe (attribution)

### A realistic day-in-the-life with DV camera shake / DV 手持感：首尔女孩的一天（全文提示词）

- **Author:** [@fuji_ai_](https://x.com/fuji_ai_)
- **Post:** https://x.com/fuji_ai_/status/2107048284191916446
- **Gallery:** [https://xianyu110.github.io/awesome-seedance-2.5/#2107048284191916446](https://xianyu110.github.io/awesome-seedance-2.5/#2107048284191916446)
- **Duration:** 30s · likes 136 · views 19946 (snapshot)
- **Category:** Lifestyle & Vlog / 生活流 / Vlog

手持晃动、对焦犹豫、环境音全靠提示词约束。作者在帖子线程里公开了四段提示词（设定/前半/后半/画质与音）。

#### Original public prompt (from author)

```text
プロンプト①　設定と人物

2000年代初期の家庭用DVカメラで撮った、超リアルなホームビデオを作成。

ソウルの古い住宅街で、若い韓国人女性が何気ない1日を過ごす。

添付画像をキャラクター参照にして、顔と見た目を一貫させる。

ピンクのクロップトップに白のショートパンツ、シンプルなサンダルと小さなブレスレット。

手には透明な水のボトル。

プロンプト②　前半の流れ

家を出てドアを閉め、ボトルを手に静かな住宅街を歩く。

途中、近所の人たちに自然な笑顔で小さく手を振ってあいさつ。

公園に着いてベンチに座り、サッカーをする子どもたちをなんとなく眺める。

そこへボールが転がってくる。

拾って笑い、そっと蹴り返して「Enjoy」と言う。

子どもたちは笑って遊びを続ける。

プロンプト③　後半の流れ

公園を出て、ボトルを持ったまま通りを歩く。

とうもろこしの屋台で1本買い、歩きながらうれしそうに最初のひと口。

食べている途中、ボトルが手から滑って歩道に落ちる。

立ち止まって小さく笑い、拾ってもうひと口かじり、家へ歩き出す。

ラストは片手にボトル、片手にとうもろこしで住宅街をゆっくり歩く。

カメラの方を見て自然に笑い、「Bye bye」と言って去っていく。

プロンプト④　画質と音

映像は2000年代初期の家庭用DVカメラの生素材。

・手持ちの揺れ
・ずれた構図
・オートフォーカスの迷い
・わずかな露出の揺れ
・柔らかいデジタル感と軽いノイズ
・自然なモーションブラー
・ときどき入る不器用なズーム

本物のホームビデオの空気感、リアルな肌、自然な表情と動き。

音は住宅街の環境音だけ。

足音、鳥の声、遠くの車、子どもたちのサッカー、近所の話し声、自転車、屋台のざわめき、ボトルの音、そよ風。

音楽・ナレーション・字幕・美肌フィルター・CG・CM風の映像・滑らかなカメラワークはすべてなし。
```

> Prompt © original author [@fuji_ai_](https://x.com/fuji_ai_). Included only because it was posted publicly. Remix with credit.


## Remixed English skeleton (adapt, do not claim as original author text)

```text
MODEL: Seedance 2.5 | early-2000s consumer DV home video
Character ref @image1 locked (face, hair, outfit).
Mundane day in <city old residential street>.
Beats: leave home → greet neighbors → park bench → kick ball back to kids → buy street snack → drop bottle → laugh → walk home → say bye to camera.
CAMERA: handheld shake, off-center framing, AF hunting, soft digital noise, clumsy zooms, natural motion blur.
AUDIO: street ambience only (footsteps, birds, distant cars, kids, bikes, stall chatter). No music, no narration, no subs.
```

## QA

- Skin and motion look real, not influencer-smooth
- No accidental score
- Character matches ref across the clip
