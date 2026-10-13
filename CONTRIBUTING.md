# 贡献指南 / Contributing

欢迎补充 **Seedance 2.5** 的公开作品与 Skills：

## 画廊案例

1. 编辑 `cases.json`，按现有格式添加一条（必须附 X 原帖链接、作者 handle、作者明确说明使用了 Seedance 2.5）。
2. **必须有公开提示词**（≥80 字）与预览封面；仅有视频、无提示词的帖子不收录。
3. 同步更新 `README.md` / `README.en.md` 对应分类表格（或说明由维护者 regenerate）。
4. 提交 PR。请用自己的话写简介，不要整段搬运他人文案。
5. **不要**提交仅标注 Seedance / 2.0 / Mini / Fast 而未写 2.5 的条目。

## Agent Skills

1. 新 skill 放在 `skills/<name>/SKILL.md`（可附 `prompts/` 公开提示词原文并署名）。
2. 更新 `skills/catalog.json` 与 `.claude-plugin/marketplace.json`。
3. 安装命令保持：`npx skills add xianyu110/awesome-seedance-2.5`。

作者如需修改或移除条目，请直接提 Issue。
