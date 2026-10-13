---
name: seedance-25-prompt-director
description: "Core Seedance 2.5 prompting OS for Claude Code / Codex / Cursor: director-style shot timelines, character cards, DV/handheld camera grammar, audio layers, aspect/duration presets, and anti-slop rules. Use for Seedance 2.5 prompts, 即梦 Seedance2.5, Dreamina video, director prompt, 分镜提示词, I2V recipes."
license: MIT
metadata:
  author: xianyu110
  version: 1.0.0
  model: Seedance 2.5
  gallery: https://xianyu110.github.io/awesome-seedance-2.5
---

# Seedance 2.5 Prompt Director

Write **director-grade** prompts for ByteDance **Seedance 2.5** (audio–video joint generation). Part of [https://github.com/xianyu110/awesome-seedance-2.5](https://github.com/xianyu110/awesome-seedance-2.5) (gallery + skills).

## When to use

- User asks for Seedance 2.5 / Seedance2.5 / Dreamina Seedance / `dreamina-seedance-2-5-*` prompts
- Need a shot timeline, character lock, DV look, or one-take story
- Converting a vague idea into a paste-ready Seedance brief

## Model facts (keep accurate)

- Official: [seedance2_5](https://seed.bytedance.com/en/seedance2_5)
- Common API / product names: Seedance 2.5, Dreamina Seedance 2.5
- Strength: ~4–30s single-pass A/V, multimodal refs, one-take storytelling
- **Not** Seedance 2.0 / Mini / Fast unless the user explicitly asks for those

## Prompt skeleton (always)

```text
MODEL: Seedance 2.5
DURATION: <Ns, usually 10–30>
ASPECT: <9:16 | 16:9 | 1:1>
STYLE LOCK: <photoreal / DV home-video / cinematic CG / brand film / …>
AUDIO: <dialogue? BGM? ambience-only? no subs?>

[CHARACTER CARDS]
@imageN = <name> — face, hair, body, wardrobe, props. Keep identity locked.

[ENVIRONMENT]
Place, time of day, weather, light.

[CAMERA]
Lens feel, move (handheld / locked / one continuous track), cut rhythm.

[ACTION TIMELINE]
00:00–00:03 …
00:03–00:08 …
…

[NEGATIVE / NOT]
No watermarks, no fake UI, no beauty filter (unless requested), no random text overlays.
```

## Camera grammar cheat-sheet

| Look | Cue words |
|---|---|
| DV / home video | early-2000s DV, handheld shake, AF hunting, soft digital noise, clumsy zoom, no BGM |
| Cinematic action | anamorphic feel, motivated camera, impact frames, practical light, grit |
| Brand film | night plates, controlled motion, logo-safe negative space, premium grade |
| Fantasy duel | dual character cards, scale contrast, staged beats, score layers |
| POV explore | first-person, natural head sway, underwater rays / bubbles / ambience |

## Audio layers

Prefer **layered ambience** over wall-to-wall music unless the user wants an MV. Explicitly say: dialogue / no dialogue, subs / no subs, SFX hits only on contact.

## Identity lock (I2V)

If the user has a reference image:

1. Name it `@图片1` / `@image1`
2. Restate face, hair, outfit, accessories
3. Forbid wardrobe changes mid-clip unless scripted
4. Prefer "image holds identity; video model owns physics"

## Delivery

1. Ask only missing critical inputs (duration, aspect, refs, language of dialogue)
2. Output one paste-ready prompt block
3. Offer a short variant (15s) and a long variant (30s+) when useful
4. Link related case demos from the gallery when teaching a pattern

## Related skills in this repo

- `seedance-25-cinematic-action`, `seedance-25-dv-day-in-life`, `seedance-25-boxing-handheld`
- `seedance-25-mech-backpack`, `seedance-25-cat-knight-duel`, `seedance-25-ocean-kingdom-pov`
- `seedance-25-character-lock-i2v`, `seedance-25-fight-previz-pipeline`
- `seedance-25-brand-commercial`, `seedance-25-music-mv-longform`, `seedance-25-gallery-index`

## Not for

Seedance 2.0-only workflows, guaranteeing platform recommendation, or claiming private/unpublished prompts as public.
