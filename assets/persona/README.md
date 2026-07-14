# 人物形象照（封面用）

把你自己的人物半身照放進這個資料夾，作為**所有 YouTube 封面的人物基準**。

## 規格建議
- **格式**：PNG（透明去背最佳，但白底也可）
- **尺寸**：寬高至少 600px
- **構圖**：半身或 3/4 身，臉部清晰、穿著風格固定（封面才會延續這套穿著）
- **光線**：均勻打光、避免逆光與深陰影
- **數量**：放一張就好（gpt-image-2 edit 模式一次只吃一張）

## 目前使用中
人物基準照：`人物形象照.png`（已於 2026-07-14 換成使用者本人照片，並同步更新 `CLAUDE.md`、`AGENTS.md`、`ANTIGRAVITY.md`、`assets/style/cover-style.md`、`skills/*/SKILL.md` 內的引用與人物穿著描述）。

## 若之後要再換人物
1. 把 `人物形象照.png` 換成新檔案（檔名自取）
2. **全文搜尋**並取代以下檔案內的引用：
   - `CLAUDE.md`
   - `AGENTS.md`
   - `ANTIGRAVITY.md`
   - `HANDOFF.md`
   - `assets/style/cover-style.md`
   - `skills/*/SKILL.md`、`skills-backup/*/SKILL.md`

   把 `assets/persona/人物形象照.png` 全部換成 `assets/persona/<你的檔名>.png`，並檢查穿著／髮型描述是否要跟著改。

## 為什麼用 `--edit` 而不是純文字描述？
gpt-image-2 在 edit 模式會延續輸入圖的人物五官、髮型、穿著。純文字 prompt 描述「一個戴眼鏡的男人」每次出來的臉都不一樣，沒辦法做頻道識別。
