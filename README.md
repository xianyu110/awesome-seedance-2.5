# Awesome Seedance 2.5（字节 Seedance 2.5 音视频提示词合集）

[English](README.en.md) | 简体中文

这里收集了创作者明确用 **Seedance 2.5** 做出、并**公开了提示词**的电影感短片、生活流 Vlog、角色一致图生视频、奇幻世界、品牌片等。当前共 **467 个「视频 + 公开提示词」案例**（LearnPrompt 142 · BeatAPI 318 · 其他原帖 7），分 8 类。每条都署名并链接到原帖，可一键复制提示词。

**这是 Seedance 2.5 版本专项、且只收有公开提示词的画廊**。仅有视频、无提示词的帖子不收录。跨版本大合集请看 [LearnPrompt/awesome-seedance](https://github.com/LearnPrompt/awesome-seedance)；结构对齐 [awesome-nano-banana-2.1](https://github.com/xianyu110/awesome-nano-banana-2.1)。

**[🌐 打开在线画廊：按分类筛选、搜索、一键复制提示词 →](https://xianyu110.github.io/awesome-seedance-2.5/)**

<table>
  <tr>
    <td width="25%" align="center"><a href="https://x.com/techhalla/status/2083389002552664385"><img src="https://media.goodcase.ai/media/poster/seedance-25-diner-frozen-time-rewind.jpg" width="200" alt="复古餐厅时间冻结与倒放"></a><br><sub>复古餐厅时间冻结与倒放 · @techhalla</sub></td><td width="25%" align="center"><a href="https://x.com/AIwithkhan/status/2092971211169100048"><img src="https://media.goodcase.ai/media/poster/vlog-c8171f712492.jpg" width="200" alt="首尔夏夜 Vlog"></a><br><sub>首尔夏夜 Vlog · @AIwithkhan</sub></td><td width="25%" align="center"><a href="https://x.com/abxxai/status/2095179656802844727"><img src="https://media.goodcase.ai/cases/c28b3bfa6a04.jpg" width="200" alt="护肤品自拍口播 UGC 广告"></a><br><sub>护肤品自拍口播 UGC 广告 · @abxxai</sub></td><td width="25%" align="center"><a href="https://x.com/Strength04_X/status/2083094742682787939"><img src="https://media.goodcase.ai/media/poster/seedance-25-minidv-coffee-asmr-vlog.jpg" width="200" alt="mini DV 咖啡 ASMR vlog"></a><br><sub>mini DV 咖啡 ASMR vlog · @Strength04_X</sub></td>
  </tr>
  <tr>
    <td width="25%" align="center"><a href="https://x.com/Just_sharon7/status/2083422886686031982"><img src="https://media.goodcase.ai/media/poster/seedance-25-kpop-mv-dual-idol.jpg" width="200" alt="双人 K-pop MV 逐镜分镜"></a><br><sub>双人 K-pop MV 逐镜分镜 · @Just_sharon7</sub></td><td width="25%" align="center"><a href="https://x.com/AIwithSynthia/status/2108760866422415701"><img src="https://media.goodcase.ai/cases/e7a04f6d6d46.jpg" width="200" alt="首尔地铁反击：女子将挑衅者扔进垃圾桶"></a><br><sub>首尔地铁反击：女子将挑衅者扔进垃圾桶 · @AIwithSynthia</sub></td><td width="25%" align="center"><a href="https://x.com/cnyzgkc/status/2099029556434985065"><img src="https://media.goodcase.ai/cases/f16c9f956a8d.jpg" width="200" alt="Seedance 2.5 超真实 AI 动态桌面壁纸：换装互动女主一镜到底"></a><br><sub>Seedance 2.5 超真实 AI 动态桌面壁纸：换装互动女主一镜到底 · @cnyzgkc</sub></td><td width="25%" align="center"><a href="https://x.com/Zarnab_with_Ai/status/2104764823091490851"><img src="https://media.goodcase.ai/cases/88ca30c0568f.jpg" width="200" alt="幼儿开门学字母与单词"></a><br><sub>幼儿开门学字母与单词 · @Zarnab_with_Ai</sub></td>
  </tr>
</table>

[🎬 电影感 / 动作](#cinematic) · [🎒 生活流 / Vlog](#lifestyle) · [🧑‍🎨 角色一致 / 图生视频](#character) · [🐉 奇幻 / 世界观](#fantasy) · [📣 品牌 / 广告](#commercial) · [🎵 音乐 / 长片](#music) · [⚖️ 对比评测](#compare) · [🧩 其他（趣味 / 平台试水）](#other) · [收录标准](#收录标准) · [Seedance 2.5 是什么](#seedance-25-是什么) · [来源仓库](#来源仓库) · [数据](#数据)

## 收录标准

- 只收**创作者本人发布的原帖**；搬运、纯转发不收。
- 作者在帖子里**明确写了是 Seedance 2.5**（含 Seedance2.5 / #Seedance2.5）。**不收录**仅写 Seedance / 2.0 / Mini / Fast 而未标明 2.5 的作品。
- **必须有公开提示词**（≥80 字）与预览封面；原帖正文、作者回复，或公开 GitHub 仓库中完整收录并可追溯到原帖。
- 按 URL / 提示词哈希去重；README 每类展示代表作，完整列表见在线画廊。
- 互动数为整理时快照（2026-10-13 21:11 (UTC+8)）。导入条目在 `cases.json` 的 `source_attribution` 字段署名。

## Seedance 2.5 是什么

ByteDance Seed 团队在 Seedance 2.0 音视频联合架构上的下一代模型，强调：

- 单次生成约 **4–30 秒**音视频，并支持续写扩展
- 更强的多模态参照（多图 / 多视频 / 多音频）
- 面向「一口气讲完一段故事」的创作，而非只出 5 秒碎片

官方页面：[seed.bytedance.com/en/seedance2_5](https://seed.bytedance.com/en/seedance2_5) · 发布博文：[Introducing Seedance 2.5](https://seed.bytedance.com/en/blog/one-take-creation-flexible-referencing-introducing-seedance-2-5)

常见体验入口：即梦 / Dreamina、Jimeng、Doubao，以及 Higgsfield、Flova、OpenArt、CapCut AI Lab 等第三方。

<a id="cinematic"></a>
## 🎬 电影感 / 动作

196 个作品 · [在线画廊查看本类](https://xianyu110.github.io/awesome-seedance-2.5/?cat=cinematic)

| 预览 | 作品 | 模型 | 创作者 | 时长 | 提示词 |
|---|---|---|---|---|---|
| <a href="https://x.com/cnyzgkc/status/2099029556434985065"><img src="https://media.goodcase.ai/cases/f16c9f956a8d.jpg" width="160" alt="Seedance 2.5 超真实 AI 动态桌面壁纸：换装互动女主一镜到底"></a> | [Seedance 2.5 超真实 AI 动态桌面壁纸：换装互动女主一镜到底](https://x.com/cnyzgkc/status/2099029556434985065) | Seedance 2.5 | [@cnyzgkc](https://x.com/cnyzgkc) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2099029556434985065) |
| <a href="https://x.com/Zarnab_with_Ai/status/2104764823091490851"><img src="https://media.goodcase.ai/cases/88ca30c0568f.jpg" width="160" alt="幼儿开门学字母与单词"></a> | [幼儿开门学字母与单词](https://x.com/Zarnab_with_Ai/status/2104764823091490851) | Seedance 2.5 | [@Zarnab_with_Ai](https://x.com/Zarnab_with_Ai) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2104764823091490851) |
| <a href="https://x.com/Zarnab_with_Ai/status/2106560621932384657"><img src="https://media.goodcase.ai/cases/e7b938f20d48.jpg" width="160" alt="萌娃学爸爸剃须，泡沫胡子逗笑父母"></a> | [萌娃学爸爸剃须，泡沫胡子逗笑父母](https://x.com/Zarnab_with_Ai/status/2106560621932384657) | Seedance 2.5 | [@Zarnab_with_Ai](https://x.com/Zarnab_with_Ai) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2106560621932384657) |
| <a href="https://x.com/RishuaVR/status/2089204108175741157"><img src="https://media.goodcase.ai/media/poster/rishuavr-seedance-ai-ad4e6de3949d.jpg" width="160" alt="Seedance 2.5 印尼女生日常写实短片"></a> | [Seedance 2.5 印尼女生日常写实短片](https://x.com/RishuaVR/status/2089204108175741157) | Seedance 2.5 | [@RishuaVR](https://x.com/RishuaVR) | 0:20 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2089204108175741157) |
| <a href="https://x.com/AIwithSynthia/status/2106955772395659431"><img src="https://media.goodcase.ai/cases/17336ecf1069.jpg" width="160" alt="大学实验室感染失控，学生变成丧尸"></a> | [大学实验室感染失控，学生变成丧尸](https://x.com/AIwithSynthia/status/2106955772395659431) | Seedance 2.5 | [@AIwithSynthia](https://x.com/AIwithSynthia) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2106955772395659431) |
| <a href="https://x.com/AIwithkhan/status/2106397932304191969"><img src="https://media.goodcase.ai/cases/3b9300fbc51d.jpg" width="160" alt="微缩女子的便利店跑酷冒险"></a> | [微缩女子的便利店跑酷冒险](https://x.com/AIwithkhan/status/2106397932304191969) | Seedance 2.5 | [@AIwithkhan](https://x.com/AIwithkhan) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2106397932304191969) |
| <a href="https://x.com/johnAGI168/status/2095025524586193105"><img src="https://media.goodcase.ai/media/poster/seedance-269d1fc95820.jpg" width="160" alt="Seedance：不会有人认为这是真的吧？😄"></a> | [Seedance：不会有人认为这是真的吧？😄](https://x.com/johnAGI168/status/2095025524586193105) | Seedance 2.5 | [@johnAGI168](https://x.com/johnAGI168) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2095025524586193105) |
| <a href="https://x.com/Aqsahere_/status/2087386090315616601"><img src="https://media.goodcase.ai/cases/5ee3737281f4.jpg" width="160" alt="Cyberpunk Holographic Dance Performance"></a> | [Cyberpunk Holographic Dance Performance](https://x.com/Aqsahere_/status/2087386090315616601) | Seedance 2.5 | [@Aqsahere_](https://x.com/Aqsahere_) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087386090315616601) |
| <a href="https://x.com/Just_sharon7/status/2103032789910401038"><img src="https://media.goodcase.ai/cases/d6bbdc164e90.jpg" width="160" alt="地铁疾驰中的夏夜时尚女孩"></a> | [地铁疾驰中的夏夜时尚女孩](https://x.com/Just_sharon7/status/2103032789910401038) | Seedance 2.5 | [@Just_sharon7](https://x.com/Just_sharon7) | 0:09 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2103032789910401038) |
| <a href="https://x.com/itsSaira_1/status/2108765927194198397"><img src="https://media.goodcase.ai/cases/605e835bd0b1.jpg" width="160" alt="修女化身天使，在废墟教堂中斩灭群魔"></a> | [修女化身天使，在废墟教堂中斩灭群魔](https://x.com/itsSaira_1/status/2108765927194198397) | Seedance 2.5 | [@itsSaira_1](https://x.com/itsSaira_1) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2108765927194198397) |
| <a href="https://x.com/sophiaparkerr_/status/2107096810783461509"><img src="https://media.goodcase.ai/cases/ae2aea3e33c4.jpg" width="160" alt="红裙女子提着食材登上云端山顶小屋"></a> | [红裙女子提着食材登上云端山顶小屋](https://x.com/sophiaparkerr_/status/2107096810783461509) | Seedance 2.5 | [@sophiaparkerr_](https://x.com/sophiaparkerr_) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2107096810783461509) |
| <a href="https://x.com/Zarnab_with_Ai/status/2099683790717325390"><img src="https://media.goodcase.ai/cases/270ba8ecea3b.jpg" width="160" alt="沙发上嬉闹亲吻的兔子情侣"></a> | [沙发上嬉闹亲吻的兔子情侣](https://x.com/Zarnab_with_Ai/status/2099683790717325390) | Seedance 2.5 | [@Zarnab_with_Ai](https://x.com/Zarnab_with_Ai) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2099683790717325390) |

<sub>本类另有 184 条，见 [在线画廊](https://xianyu110.github.io/awesome-seedance-2.5/?cat=cinematic) / `cases.json`。</sub>

<a id="lifestyle"></a>
## 🎒 生活流 / Vlog

61 个作品 · [在线画廊查看本类](https://xianyu110.github.io/awesome-seedance-2.5/?cat=lifestyle)

| 预览 | 作品 | 模型 | 创作者 | 时长 | 提示词 |
|---|---|---|---|---|---|
| <a href="https://x.com/techhalla/status/2083389002552664385"><img src="https://media.goodcase.ai/media/poster/seedance-25-diner-frozen-time-rewind.jpg" width="160" alt="复古餐厅时间冻结与倒放"></a> | [复古餐厅时间冻结与倒放](https://x.com/techhalla/status/2083389002552664385) | Seedance 2.5 | [@techhalla](https://x.com/techhalla) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083389002552664385) |
| <a href="https://x.com/AIwithkhan/status/2092971211169100048"><img src="https://media.goodcase.ai/media/poster/vlog-c8171f712492.jpg" width="160" alt="首尔夏夜 Vlog"></a> | [首尔夏夜 Vlog](https://x.com/AIwithkhan/status/2092971211169100048) | Seedance 2.5 | [@AIwithkhan](https://x.com/AIwithkhan) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2092971211169100048) |
| <a href="https://x.com/Strength04_X/status/2083094742682787939"><img src="https://media.goodcase.ai/media/poster/seedance-25-minidv-coffee-asmr-vlog.jpg" width="160" alt="mini DV 咖啡 ASMR vlog"></a> | [mini DV 咖啡 ASMR vlog](https://x.com/Strength04_X/status/2083094742682787939) | Seedance 2.5 | [@Strength04_X](https://x.com/Strength04_X) | 0:20 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083094742682787939) |
| <a href="https://x.com/AIwithSynthia/status/2108760866422415701"><img src="https://media.goodcase.ai/cases/e7a04f6d6d46.jpg" width="160" alt="首尔地铁反击：女子将挑衅者扔进垃圾桶"></a> | [首尔地铁反击：女子将挑衅者扔进垃圾桶](https://x.com/AIwithSynthia/status/2108760866422415701) | Seedance 2.5 | [@AIwithSynthia](https://x.com/AIwithSynthia) | 0:20 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2108760866422415701) |
| <a href="https://x.com/sipteaandcoffee/status/2104887547243774358"><img src="https://media.goodcase.ai/cases/8394fd6c092a.jpg" width="160" alt="韩国女生的社区健身房晨练"></a> | [韩国女生的社区健身房晨练](https://x.com/sipteaandcoffee/status/2104887547243774358) | Seedance 2.5 | [@sipteaandcoffee](https://x.com/sipteaandcoffee) | 0:45 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2104887547243774358) |
| <a href="https://x.com/BubbleBrain/status/2083659648108990925"><img src="https://media.goodcase.ai/media/poster/youmind-travel-vlog-city-to-beach.jpg" width="160" alt="手持感旅行 Vlog：从公寓到海滩"></a> | [手持感旅行 Vlog：从公寓到海滩](https://x.com/BubbleBrain/status/2083659648108990925) | Seedance 2.5 | [@BubbleBrain](https://x.com/BubbleBrain) | 0:05 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083659648108990925) |
| <a href="https://x.com/techhalla/status/2083585132917579834"><img src="https://media.goodcase.ai/media/poster/youmind-rollercoaster-wig-time-freeze.jpg" width="160" alt="过山车假发闹剧：冻结与倒放的第二次演练"></a> | [过山车假发闹剧：冻结与倒放的第二次演练](https://x.com/techhalla/status/2083585132917579834) | Seedance 2.5 | [@techhalla](https://x.com/techhalla) | 0:05 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083585132917579834) |
| <a href="https://x.com/Strength04_X/status/2091737661061095648"><img src="https://media.goodcase.ai/cases/68ae69f99fe4.jpg" width="160" alt="韩国女生户外泳池 Vlog"></a> | [韩国女生户外泳池 Vlog](https://x.com/Strength04_X/status/2091737661061095648) | Seedance 2.5 | [@Strength04_X](https://x.com/Strength04_X) | 0:20 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2091737661061095648) |
| <a href="https://x.com/Zarnab_with_Ai/status/2106347953711661482"><img src="https://media.goodcase.ai/cases/9f5595620b50.jpg" width="160" alt="宝宝模仿妈妈晨间瑜伽，最后温暖相拥"></a> | [宝宝模仿妈妈晨间瑜伽，最后温暖相拥](https://x.com/Zarnab_with_Ai/status/2106347953711661482) | Seedance 2.5 | [@Zarnab_with_Ai](https://x.com/Zarnab_with_Ai) | 0:20 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2106347953711661482) |
| <a href="https://x.com/saniaspeaks_/status/2098742251472261330"><img src="https://media.goodcase.ai/cases/38369ab7e574.jpg" width="160" alt="韩国女孩的夏日农场体验"></a> | [韩国女孩的夏日农场体验](https://x.com/saniaspeaks_/status/2098742251472261330) | Seedance 2.5 | [@saniaspeaks_](https://x.com/saniaspeaks_) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2098742251472261330) |
| <a href="https://x.com/Lianaalane/status/2106951270380802264"><img src="https://media.goodcase.ai/cases/44495a5166ef.jpg" width="160" alt="韩国女孩的雨天街巷与小店之旅"></a> | [韩国女孩的雨天街巷与小店之旅](https://x.com/Lianaalane/status/2106951270380802264) | Seedance 2.5 | [@Lianaalane](https://x.com/Lianaalane) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2106951270380802264) |
| <a href="https://x.com/doctorwasif/status/2107824210899055039"><img src="https://media.goodcase.ai/cases/a904b5da80b2.jpg" width="160" alt="韩国女子的居家午后：护绿植、叠衣与美甲"></a> | [韩国女子的居家午后：护绿植、叠衣与美甲](https://x.com/doctorwasif/status/2107824210899055039) | Seedance 2.5 | [@doctorwasif](https://x.com/doctorwasif) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2107824210899055039) |

<sub>本类另有 49 条，见 [在线画廊](https://xianyu110.github.io/awesome-seedance-2.5/?cat=lifestyle) / `cases.json`。</sub>

<a id="character"></a>
## 🧑‍🎨 角色一致 / 图生视频

42 个作品 · [在线画廊查看本类](https://xianyu110.github.io/awesome-seedance-2.5/?cat=character)

| 预览 | 作品 | 模型 | 创作者 | 时长 | 提示词 |
|---|---|---|---|---|---|
| <a href="https://x.com/aimikoda/status/2106044483863191748"><img src="https://media.goodcase.ai/cases/4e5f9347c75d.jpg" width="160" alt="蓝夹克双辫女剑士破框而出"></a> | [蓝夹克双辫女剑士破框而出](https://x.com/aimikoda/status/2106044483863191748) | Seedance 2.5 | [@aimikoda](https://x.com/aimikoda) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2106044483863191748) |
| <a href="https://x.com/QtImVCr6WK56152/status/2106252278940541142"><img src="https://media.goodcase.ai/cases/9e3e27e76494.jpg" width="160" alt="Seedance 2.5 生成 30 秒情侣卧室 POV：男友不会哄人只会捏脸（需自备参考图）"></a> | [Seedance 2.5 生成 30 秒情侣卧室 POV：男友不会哄人只会捏脸（需自备参考图）](https://x.com/QtImVCr6WK56152/status/2106252278940541142) | Seedance 2.5 | [@QtImVCr6WK56152](https://x.com/QtImVCr6WK56152) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2106252278940541142) |
| <a href="https://x.com/Chengzilhy/status/2087458506123465088"><img src="https://media.goodcase.ai/media/poster/boa-hancock-water-obstacle-race-prompt.jpg" width="160" alt="Boa Hancock Water Obstacle Race Prompt"></a> | [Boa Hancock Water Obstacle Race Prompt](https://x.com/Chengzilhy/status/2087458506123465088) | Seedance 2.5 | [@Chengzilhy](https://x.com/Chengzilhy) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087458506123465088) |
| <a href="https://x.com/techhalla/status/2085200942060691807"><img src="https://media.goodcase.ai/media/poster/90s-diner-time-freeze-effect.jpg" width="160" alt="90s Diner Time Freeze Effect"></a> | [90s Diner Time Freeze Effect](https://x.com/techhalla/status/2085200942060691807) | Seedance 2.5 | [@techhalla](https://x.com/techhalla) | 0:05 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2085200942060691807) |
| <a href="https://x.com/Xaroon_x/status/2107412153577935128"><img src="https://media.goodcase.ai/cases/474b42d3e724.jpg" width="160" alt="八角笼激战中的逆转击倒"></a> | [八角笼激战中的逆转击倒](https://x.com/Xaroon_x/status/2107412153577935128) | Seedance 2.5 | [@Xaroon_x](https://x.com/Xaroon_x) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2107412153577935128) |
| <a href="https://x.com/Chaemate_/status/2107691578605322348"><img src="https://media.goodcase.ai/cases/f2027a8ab748.jpg" width="160" alt="双人舞从东京夕照舞室到霓虹街巷与天台"></a> | [双人舞从东京夕照舞室到霓虹街巷与天台](https://x.com/Chaemate_/status/2107691578605322348) | Seedance 2.5 | [@Chaemate_](https://x.com/Chaemate_) | 0:05 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2107691578605322348) |
| <a href="https://x.com/CaliraVal/status/2107697202646987178"><img src="https://media.goodcase.ai/cases/c5e375e7e334.jpg" width="160" alt="白色皮草外套女子漫步雪山"></a> | [白色皮草外套女子漫步雪山](https://x.com/CaliraVal/status/2107697202646987178) | Seedance 2.5 | [@CaliraVal](https://x.com/CaliraVal) | 0:04 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2107697202646987178) |
| <a href="https://x.com/saniaspeaks_/status/2091103923440328783"><img src="https://media.goodcase.ai/media/poster/case-365f2a3615b1.jpg" width="160" alt="韩国城市公交站偶遇"></a> | [韩国城市公交站偶遇](https://x.com/saniaspeaks_/status/2091103923440328783) | Seedance 2.5 | [@saniaspeaks_](https://x.com/saniaspeaks_) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2091103923440328783) |
| <a href="https://x.com/Noor_ul_ain43/status/2087774014957850843"><img src="https://media.goodcase.ai/media/poster/seedance-2-5-3f70c2f28d22.jpg" width="160" alt="Seedance 2.5 生成暴雨港口灾难电影序列"></a> | [Seedance 2.5 生成暴雨港口灾难电影序列](https://x.com/Noor_ul_ain43/status/2087774014957850843) | Seedance 2.5 | [@Noor_ul_ain43](https://x.com/Noor_ul_ain43) | 0:05 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087774014957850843) |
| <a href="https://x.com/itsphotogptai/status/2089672910520910279"><img src="https://media.goodcase.ai/cases/4f0337074c6c.jpg" width="160" alt="电影感抹茶茶道"></a> | [电影感抹茶茶道](https://x.com/itsphotogptai/status/2089672910520910279) | Seedance 2.5 | [@itsphotogptai](https://x.com/itsphotogptai) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2089672910520910279) |
| <a href="https://x.com/johnAGI168/status/2101647622582792500"><img src="https://pbs.twimg.com/amplify_video_thumb/2101647260903768064/img/2T7UvprdbiWPfc3G.jpg" width="160" alt="飞行超跑收纳成机械背包（附提示词）"></a> | [飞行超跑收纳成机械背包（附提示词）](https://x.com/johnAGI168/status/2101647622582792500) | Seedance 2.5 | [@johnAGI168](https://x.com/johnAGI168) | 0:14 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2101647622582792500) |
| <a href="https://x.com/ManuAGI01/status/2086035048701341887"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/i-just-created-this-entire-animated-short-using-341887/poster-8febb7853c53c140.jpg" width="160" alt="Animation Study 341887"></a> | [Animation Study 341887](https://x.com/ManuAGI01/status/2086035048701341887) | Seedance 2.5 | [@ManuAGI01](https://x.com/ManuAGI01) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2086035048701341887) |

<sub>本类另有 30 条，见 [在线画廊](https://xianyu110.github.io/awesome-seedance-2.5/?cat=character) / `cases.json`。</sub>

<a id="fantasy"></a>
## 🐉 奇幻 / 世界观

45 个作品 · [在线画廊查看本类](https://xianyu110.github.io/awesome-seedance-2.5/?cat=fantasy)

| 预览 | 作品 | 模型 | 创作者 | 时长 | 提示词 |
|---|---|---|---|---|---|
| <a href="https://x.com/itsSaira_1/status/2107685928647160275"><img src="https://media.goodcase.ai/cases/4a7f9d53f8c5.jpg" width="160" alt="绿裙女子召唤烈焰树灵迎战恶魔群"></a> | [绿裙女子召唤烈焰树灵迎战恶魔群](https://x.com/itsSaira_1/status/2107685928647160275) | Seedance 2.5 | [@itsSaira_1](https://x.com/itsSaira_1) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2107685928647160275) |
| <a href="https://x.com/itsSaira_1/status/2108049177259462719"><img src="https://media.goodcase.ai/cases/680efb813c0b.jpg" width="160" alt="修女化身绿光天使迎战教堂恶魔"></a> | [修女化身绿光天使迎战教堂恶魔](https://x.com/itsSaira_1/status/2108049177259462719) | Seedance 2.5 | [@itsSaira_1](https://x.com/itsSaira_1) | 0:10 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2108049177259462719) |
| <a href="https://x.com/doctorwasif/status/2094285140247896553"><img src="https://media.goodcase.ai/media/poster/case-3b1796c66ab4.jpg" width="160" alt="丧尸列车爆发"></a> | [丧尸列车爆发](https://x.com/doctorwasif/status/2094285140247896553) | Seedance 2.5 | [@doctorwasif](https://x.com/doctorwasif) | 0:02 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2094285140247896553) |
| <a href="https://x.com/frametheory058/status/2087007818721423855"><img src="https://media.goodcase.ai/cases/464939ccd5ab.jpg" width="160" alt="First-Person POV Dragon Rider Cinematic"></a> | [First-Person POV Dragon Rider Cinematic](https://x.com/frametheory058/status/2087007818721423855) | Seedance 2.5 | [@frametheory058](https://x.com/frametheory058) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087007818721423855) |
| <a href="https://x.com/RuzainaMeer/status/2089595902818398461"><img src="https://media.goodcase.ai/media/poster/ruzainameer-seedance-ai-e6073ec318f1.jpg" width="160" alt="Seedance 2.5 1080P 三十秒超写实奇幻大片"></a> | [Seedance 2.5 1080P 三十秒超写实奇幻大片](https://x.com/RuzainaMeer/status/2089595902818398461) | Seedance 2.5 | [@RuzainaMeer](https://x.com/RuzainaMeer) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2089595902818398461) |
| <a href="https://x.com/laviniavelle/status/2107333176985317886"><img src="https://media.goodcase.ai/cases/8bed65d44d4c.jpg" width="160" alt="紫发女巫在暴雨古堡召唤水兽迎敌"></a> | [紫发女巫在暴雨古堡召唤水兽迎敌](https://x.com/laviniavelle/status/2107333176985317886) | Seedance 2.5 | [@laviniavelle](https://x.com/laviniavelle) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2107333176985317886) |
| <a href="https://x.com/laviniavelle/status/2105889515948921057"><img src="https://media.goodcase.ai/cases/3b8cf445eb84.jpg" width="160" alt="白裙女子奔出古堡，飞向粉月浮岛天空"></a> | [白裙女子奔出古堡，飞向粉月浮岛天空](https://x.com/laviniavelle/status/2105889515948921057) | Seedance 2.5 | [@laviniavelle](https://x.com/laviniavelle) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2105889515948921057) |
| <a href="https://x.com/Chaemate_/status/2105958420088328486"><img src="https://media.goodcase.ai/cases/614552b6a770.jpg" width="160" alt="银发双刀女剑士突袭日式城堡"></a> | [银发双刀女剑士突袭日式城堡](https://x.com/Chaemate_/status/2105958420088328486) | Seedance 2.5 | [@Chaemate_](https://x.com/Chaemate_) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2105958420088328486) |
| <a href="https://x.com/Zyrellix/status/2106604455151980846"><img src="https://media.goodcase.ai/cases/2a36c8531837.jpg" width="160" alt="头巾女孩与小鸭兔子的月夜提灯漫游"></a> | [头巾女孩与小鸭兔子的月夜提灯漫游](https://x.com/Zyrellix/status/2106604455151980846) | Seedance 2.5 | [@Zyrellix](https://x.com/Zyrellix) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2106604455151980846) |
| <a href="https://x.com/Zyrellix/status/2108498562199753052"><img src="https://media.goodcase.ai/cases/c9c113132f69.jpg" width="160" alt="紫裙女子在废墟战场挥拳御火"></a> | [紫裙女子在废墟战场挥拳御火](https://x.com/Zyrellix/status/2108498562199753052) | Seedance 2.5 | [@Zyrellix](https://x.com/Zyrellix) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2108498562199753052) |
| <a href="https://x.com/itxabdullaa/status/2107792780395458733"><img src="https://media.goodcase.ai/cases/2ecf28ab3d4e.jpg" width="160" alt="林间守护者循灯发现古树秘境"></a> | [林间守护者循灯发现古树秘境](https://x.com/itxabdullaa/status/2107792780395458733) | Seedance 2.5 | [@itxabdullaa](https://x.com/itxabdullaa) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2107792780395458733) |
| <a href="https://x.com/Zarnab_with_Ai/status/2108504570603491475"><img src="https://media.goodcase.ai/cases/9784906f7de1.jpg" width="160" alt="宝宝与小动物乘西瓜船畅游奇幻水果河"></a> | [宝宝与小动物乘西瓜船畅游奇幻水果河](https://x.com/Zarnab_with_Ai/status/2108504570603491475) | Seedance 2.5 | [@Zarnab_with_Ai](https://x.com/Zarnab_with_Ai) | 0:03 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2108504570603491475) |

<sub>本类另有 33 条，见 [在线画廊](https://xianyu110.github.io/awesome-seedance-2.5/?cat=fantasy) / `cases.json`。</sub>

<a id="commercial"></a>
## 📣 品牌 / 广告

64 个作品 · [在线画廊查看本类](https://xianyu110.github.io/awesome-seedance-2.5/?cat=commercial)

| 预览 | 作品 | 模型 | 创作者 | 时长 | 提示词 |
|---|---|---|---|---|---|
| <a href="https://x.com/abxxai/status/2095179656802844727"><img src="https://media.goodcase.ai/cases/c28b3bfa6a04.jpg" width="160" alt="护肤品自拍口播 UGC 广告"></a> | [护肤品自拍口播 UGC 广告](https://x.com/abxxai/status/2095179656802844727) | Seedance 2.5 | [@abxxai](https://x.com/abxxai) | 0:15 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2095179656802844727) |
| <a href="https://x.com/Just_sharon7/status/2085277106960007654"><img src="https://media.goodcase.ai/cases/5144aead9488.jpg" width="160" alt="Classic Mustang Golden Hour Drive"></a> | [Classic Mustang Golden Hour Drive](https://x.com/Just_sharon7/status/2085277106960007654) | Seedance 2.5 | [@Just_sharon7](https://x.com/Just_sharon7) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2085277106960007654) |
| <a href="https://x.com/AIwithAliya/status/2090780603872624826"><img src="https://media.goodcase.ai/cases/a7f53c61f405.jpg" width="160" alt="手工烘焙坊电影感商业广告"></a> | [手工烘焙坊电影感商业广告](https://x.com/AIwithAliya/status/2090780603872624826) | Seedance 2.5 | [@AIwithAliya](https://x.com/AIwithAliya) | 0:06 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2090780603872624826) |
| <a href="https://x.com/AIWithRay/status/2087544594384773346"><img src="https://media.goodcase.ai/media/poster/seedance-2-5-eba905fedcff.jpg" width="160" alt="Seedance 2.5 深夜厨房手机实录做饭"></a> | [Seedance 2.5 深夜厨房手机实录做饭](https://x.com/AIWithRay/status/2087544594384773346) | Seedance 2.5 | [@AIWithRay](https://x.com/AIWithRay) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087544594384773346) |
| <a href="https://x.com/AIwithWania/status/2108420649467457557"><img src="https://media.goodcase.ai/cases/4e32f2f8334d.jpg" width="160" alt="三位闺蜜的精品店购物与绿裙试穿"></a> | [三位闺蜜的精品店购物与绿裙试穿](https://x.com/AIwithWania/status/2108420649467457557) | Seedance 2.5 | [@AIwithWania](https://x.com/AIwithWania) | 0:05 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2108420649467457557) |
| <a href="https://x.com/sipteaandcoffee/status/2107060987157524524"><img src="https://media.goodcase.ai/cases/ec4e8d1301a8.jpg" width="160" alt="大象抛起女杂技演员翻空落上马背"></a> | [大象抛起女杂技演员翻空落上马背](https://x.com/sipteaandcoffee/status/2107060987157524524) | Seedance 2.5 | [@sipteaandcoffee](https://x.com/sipteaandcoffee) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2107060987157524524) |
| <a href="https://x.com/saniaspeaks_/status/2088605003112235033"><img src="https://media.goodcase.ai/media/poster/vlog-b7d2a3d9d7f2.jpg" width="160" alt="东京手机美食 Vlog"></a> | [东京手机美食 Vlog](https://x.com/saniaspeaks_/status/2088605003112235033) | Seedance 2.5 | [@saniaspeaks_](https://x.com/saniaspeaks_) | 0:05 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2088605003112235033) |
| <a href="https://x.com/AIwithkhan/status/2107081013583089797"><img src="https://media.goodcase.ai/cases/94eb3d1f1cb9.jpg" width="160" alt="戴耳机的女子漫步都市，静享天台落日"></a> | [戴耳机的女子漫步都市，静享天台落日](https://x.com/AIwithkhan/status/2107081013583089797) | Seedance 2.5 | [@AIwithkhan](https://x.com/AIwithkhan) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2107081013583089797) |
| <a href="https://x.com/Naiknelofar788/status/2106439652278411435"><img src="https://media.goodcase.ai/cases/313dd39b0f8a.jpg" width="160" alt="穿越土耳其霓虹古城、碧海与热气球天空"></a> | [穿越土耳其霓虹古城、碧海与热气球天空](https://x.com/Naiknelofar788/status/2106439652278411435) | Seedance 2.5 | [@Naiknelofar788](https://x.com/Naiknelofar788) | 0:06 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2106439652278411435) |
| <a href="https://x.com/MissDelulu9/status/2108101531426083045"><img src="https://media.goodcase.ai/cases/26efe02e5e88.jpg" width="160" alt="素颜女子挥手变身华丽妆容"></a> | [素颜女子挥手变身华丽妆容](https://x.com/MissDelulu9/status/2108101531426083045) | Seedance 2.5 | [@MissDelulu9](https://x.com/MissDelulu9) | 0:05 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2108101531426083045) |
| <a href="https://x.com/AIwithkhan/status/2108180243244818861"><img src="https://media.goodcase.ai/cases/508218b6096e.jpg" width="160" alt="微缩女子的巨型洗衣房冒险"></a> | [微缩女子的巨型洗衣房冒险](https://x.com/AIwithkhan/status/2108180243244818861) | Seedance 2.5 | [@AIwithkhan](https://x.com/AIwithkhan) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2108180243244818861) |
| <a href="https://x.com/tanabe_fragm/status/2096136682055864564"><img src="https://media.goodcase.ai/cases/9012527ae2ae.jpg" width="160" alt="日本网红假日 Vlog"></a> | [日本网红假日 Vlog](https://x.com/tanabe_fragm/status/2096136682055864564) | Seedance 2.5 | [@tanabe_fragm](https://x.com/tanabe_fragm) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2096136682055864564) |

<sub>本类另有 52 条，见 [在线画廊](https://xianyu110.github.io/awesome-seedance-2.5/?cat=commercial) / `cases.json`。</sub>

<a id="music"></a>
## 🎵 音乐 / 长片

49 个作品 · [在线画廊查看本类](https://xianyu110.github.io/awesome-seedance-2.5/?cat=music)

| 预览 | 作品 | 模型 | 创作者 | 时长 | 提示词 |
|---|---|---|---|---|---|
| <a href="https://x.com/Just_sharon7/status/2083422886686031982"><img src="https://media.goodcase.ai/media/poster/seedance-25-kpop-mv-dual-idol.jpg" width="160" alt="双人 K-pop MV 逐镜分镜"></a> | [双人 K-pop MV 逐镜分镜](https://x.com/Just_sharon7/status/2083422886686031982) | Seedance 2.5 | [@Just_sharon7](https://x.com/Just_sharon7) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083422886686031982) |
| <a href="https://x.com/aiwarts/status/2085736621685764503"><img src="https://media.goodcase.ai/cases/seedance-25-kpop-mv-zero-to-pop/poster.jpg" width="160" alt="单人 K-POP MV · Y2K 糖果世界逐秒分镜"></a> | [单人 K-POP MV · Y2K 糖果世界逐秒分镜](https://x.com/aiwarts/status/2085736621685764503) | Seedance 2.5 | [@aiwarts](https://x.com/aiwarts) | — | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2085736621685764503) |
| <a href="https://x.com/Just_sharon7/status/2086067758970851614"><img src="https://media.goodcase.ai/media/poster/seedance-2-5-k-pop-87e2d00e2fe8.jpg" width="160" alt="Seedance 2.5 涩谷街头K-pop舞蹈同步字幕"></a> | [Seedance 2.5 涩谷街头K-pop舞蹈同步字幕](https://x.com/Just_sharon7/status/2086067758970851614) | Seedance 2.5 | [@Just_sharon7](https://x.com/Just_sharon7) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2086067758970851614) |
| <a href="https://x.com/VeraVCreates/status/2087004800462557485"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/i-honestly-didn-t-expect-seedance-2-5-to-hold-557485/poster-8a15f0da66294955.jpg" width="160" alt="I honestly didn&#x27;t expect Seedance 2.5 to hold this together so well.😍"></a> | [I honestly didn't expect Seedance 2.5 to hold this together so well.😍](https://x.com/VeraVCreates/status/2087004800462557485) | Seedance 2.5 | [@VeraVCreates](https://x.com/VeraVCreates) | 0:05 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087004800462557485) |
| <a href="https://x.com/GlennHasABeard/status/2086637239254110436"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/made-with-seedance-2-5-on-110436/poster-6d588971309051d4.jpg" width="160" alt="Made with Seedance 2.5 on"></a> | [Made with Seedance 2.5 on](https://x.com/GlennHasABeard/status/2086637239254110436) | Seedance 2.5 | [@GlennHasABeard](https://x.com/GlennHasABeard) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2086637239254110436) |
| <a href="https://x.com/VeraVCreates/status/2087005484146635022"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/im-genuinely-impressed-by-how-well-seedance-2-5-keeps-635022/poster-9123633f2f24eb91.jpg" width="160" alt="I’m genuinely impressed by how well Seedance 2.5 keeps the geography intact here！😍"></a> | [I’m genuinely impressed by how well Seedance 2.5 keeps the geography intact here！😍](https://x.com/VeraVCreates/status/2087005484146635022) | Seedance 2.5 | [@VeraVCreates](https://x.com/VeraVCreates) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087005484146635022) |
| <a href="https://x.com/frametheory058/status/2095003298747318531"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/created-with-seedance-2-5-318531/poster-791d72efef5f4a74.jpg" width="160" alt="Created with Seedance 2.5"></a> | [Created with Seedance 2.5](https://x.com/frametheory058/status/2095003298747318531) | Seedance 2.5 | [@frametheory058](https://x.com/frametheory058) | 0:04 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2095003298747318531) |
| <a href="https://x.com/minuitIA/status/2086866861480636796"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/made-with-seedance-2-5-on-636796/poster-4c1674d7992f6291.jpg" width="160" alt="Made with Seedance 2.5 on"></a> | [Made with Seedance 2.5 on](https://x.com/minuitIA/status/2086866861480636796) | Seedance 2.5 | [@minuitIA](https://x.com/minuitIA) | 0:15 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2086866861480636796) |
| <a href="https://x.com/_STARPAR/status/2087131232945459303"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/ultra-realistic-spontaneous-vertical-handheld-footage-recorded-during-fi-459303/poster-ec0d9e0fd30adaa5.jpg" width="160" alt="Ultra-realistic spontaneous vertical handheld footage recorded during fighting in"></a> | [Ultra-realistic spontaneous vertical handheld footage recorded during fighting in](https://x.com/_STARPAR/status/2087131232945459303) | Seedance 2.5 | [@_STARPAR](https://x.com/_STARPAR) | 0:03 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087131232945459303) |
| <a href="https://x.com/MadMax_Series/status/2087187209170423842"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/created-in-423842/poster-c7d42d7b131e6175.jpg" width="160" alt="Created in"></a> | [Created in](https://x.com/MadMax_Series/status/2087187209170423842) | Seedance 2.5 | [@MadMax_Series](https://x.com/MadMax_Series) | 0:20 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087187209170423842) |
| <a href="https://x.com/maxescu/status/2087117065874211150"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/here-s-one-of-the-first-tests-211150/poster-50bf8e78d9f30480.jpg" width="160" alt="Here&#x27;s one of the first tests."></a> | [Here's one of the first tests.](https://x.com/maxescu/status/2087117065874211150) | Seedance 2.5 | [@maxescu](https://x.com/maxescu) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087117065874211150) |
| <a href="https://x.com/happycapyai/status/2087150512609304904"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/real-world-action-is-getting-easier-to-direct-304904/poster-1b360351d9704b67.jpg" width="160" alt="Real-world action is getting easier to direct."></a> | [Real-world action is getting easier to direct.](https://x.com/happycapyai/status/2087150512609304904) | Seedance 2.5 | [@happycapyai](https://x.com/happycapyai) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2087150512609304904) |

<sub>本类另有 37 条，见 [在线画廊](https://xianyu110.github.io/awesome-seedance-2.5/?cat=music) / `cases.json`。</sub>

<a id="compare"></a>
## ⚖️ 对比评测

10 个作品 · [在线画廊查看本类](https://xianyu110.github.io/awesome-seedance-2.5/?cat=compare)

| 预览 | 作品 | 模型 | 创作者 | 时长 | 提示词 |
|---|---|---|---|---|---|
| <a href="https://x.com/Just_sharon7/status/2088878042034868640"><img src="https://media.goodcase.ai/cases/8ca3ebd21bfe.jpg" width="160" alt="Seedance 2.5 同人对打：Sharon 大战 Sharon"></a> | [Seedance 2.5 同人对打：Sharon 大战 Sharon](https://x.com/Just_sharon7/status/2088878042034868640) | Seedance 2.5 | [@Just_sharon7](https://x.com/Just_sharon7) | 0:10 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2088878042034868640) |
| <a href="https://x.com/baqiceloudezhu/status/2083105322919731519"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/rainy-temple-martial-arts-epic/poster-55a39828adb7b236.jpg" width="160" alt="雨中寺庙武术史诗"></a> | [雨中寺庙武术史诗](https://x.com/baqiceloudezhu/status/2083105322919731519) | Seedance 2.5 | [@baqiceloudezhu](https://x.com/baqiceloudezhu) | 1:20 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083105322919731519) |
| <a href="https://x.com/johnAGI168/status/2086814865922965824"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/video-prompt-case-965824-965824/poster-fa9493fec5b44432.jpg" width="160" alt="屠龙断岳 🆚 倚天涤尘🔪"></a> | [屠龙断岳 🆚 倚天涤尘🔪](https://x.com/johnAGI168/status/2086814865922965824) | Seedance 2.5 | [@johnAGI168](https://x.com/johnAGI168) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2086814865922965824) |
| <a href="https://x.com/john87445528/status/2083760993222426625"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/video-prompt-case-426625/poster-41d54cf7a9c578f7.jpg" width="160" alt="出来后 2.0 就降智了"></a> | [出来后 2.0 就降智了](https://x.com/john87445528/status/2083760993222426625) | Seedance 2.5 | [@john87445528](https://x.com/john87445528) | 0:15 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083760993222426625) |
| <a href="https://x.com/TanLuAI/status/2083082840229675186"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/pink-haired-wasteland-zombie-chase/poster-9bd7f4f8eadf203a.jpg" width="160" alt="粉发少女废土丧尸追逐"></a> | [粉发少女废土丧尸追逐](https://x.com/TanLuAI/status/2083082840229675186) | Seedance 2.5 | [@TanLuAI](https://x.com/TanLuAI) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083082840229675186) |
| <a href="https://x.com/sailorv321/status/2083129374786949560"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/live-action-dance-comparison/poster-9b83cf7fd76986c9.jpg" width="160" alt="真人舞蹈对比"></a> | [真人舞蹈对比](https://x.com/sailorv321/status/2083129374786949560) | Seedance 2.5 | [@sailorv321](https://x.com/sailorv321) | 0:15 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083129374786949560) |
| <a href="https://x.com/ivannaneuro_ai/status/2083193349549314298"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/protein-shake-ugc-ad/poster-03b884cc1da9837f.jpg" width="160" alt="蛋白奶昔 UGC 广告"></a> | [蛋白奶昔 UGC 广告](https://x.com/ivannaneuro_ai/status/2083193349549314298) | Seedance 2.5 | [@ivannaneuro_ai](https://x.com/ivannaneuro_ai) | 0:21 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083193349549314298) |
| <a href="https://x.com/shirawiggles/status/2085814432895057958"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/mpter-and-comparison-057958/poster-3f4d36269aba7c52.jpg" width="160" alt="MPTER AND COMPARISON"></a> | [MPTER AND COMPARISON](https://x.com/shirawiggles/status/2085814432895057958) | Seedance 2.5 | [@shirawiggles](https://x.com/shirawiggles) | 0:30 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2085814432895057958) |
| <a href="https://x.com/tanabe_fragm/status/2083085216449741212"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/japanese-street-lip-sync-comparison/poster-20ee3fbcebc970f6.jpg" width="160" alt="日本街头对话口型测试"></a> | [日本街头对话口型测试](https://x.com/tanabe_fragm/status/2083085216449741212) | Seedance 2.5 | [@tanabe_fragm](https://x.com/tanabe_fragm) | 0:20 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083085216449741212) |
| <a href="https://x.com/you1873118/status/2083115308693561497"><img src="https://media.beatapi.io/prompt-gallery/seedance-2-5/cbd-rooftop-power-ensemble/poster-0f65ec1a2afe58c4.jpg" width="160" alt="CBD 天台权谋群像"></a> | [CBD 天台权谋群像](https://x.com/you1873118/status/2083115308693561497) | Seedance 2.5 | [@you1873118](https://x.com/you1873118) | 0:15 | [提示词](https://xianyu110.github.io/awesome-seedance-2.5/#2083115308693561497) |

<a id="other"></a>
## 🧩 其他（趣味 / 平台试水）

0 个作品 · [在线画廊查看本类](https://xianyu110.github.io/awesome-seedance-2.5/?cat=other)

_暂无_

## 来源仓库

本次从以下公开仓库挖掘（仅保留公开提示词 + 原帖链接 + 预览封面）：

| 仓库 | 去重后条数 | 说明 |
|---|---:|---|
| [LearnPrompt/awesome-seedance](https://github.com/LearnPrompt/awesome-seedance) | 142 | 证据链 Seedance 2.5 + promptFull |
| [BeatAPI/awesome-seedance-2-5-prompts](https://github.com/BeatAPI/awesome-seedance-2-5-prompts) | 318 | 源帖核验 + 公开提示词 + 封面 |
| 其他（X 原帖 / 混合署名） | 7 | 画廊既有公开提示词条目 |

## 数据

- 机器可读：[`cases.json`](./cases.json)（467 条）
- 在线画廊：<https://xianyu110.github.io/awesome-seedance-2.5/>
- 更新于 2026-10-13 21:11 (UTC+8)

## License

仓库文档采用 CC0；视频与提示词版权归原作者。如需移除条目请开 Issue。
