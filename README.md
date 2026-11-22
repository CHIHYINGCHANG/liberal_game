# 文史探險隊 V9 — 國文與社會 RPG 知識解謎

康軒七年級上學期國文與社會的原創互動學習遊戲。包含章節學習地圖、精讀導覽、知識解謎、Boss 戰、練習、模擬考及瀏覽器本機學習進度。

## 七上社會 V9 內容

- 地理 6 課：位置、臺灣地形、海域、氣候、水文等
- 歷史 6 課：史前文化、大航海時代、清帝國時期等
- 公民 6 課：人權、性別平等、家庭、校園公共參與、社區與部落等
- 共 18 課、54 個原創分段教學與理解練習，均可進行 RPG 關卡；八上、九上尚未匯入。
- 原有國文 15 單元與舊版進度儲存 key 保留；新章節使用獨立 ID。
- 這些題目為按教材考點原創，尚未將教師用書原卷題目完整辨識與逐題校對。

## Local preview

Open `public/index.html` in a modern web browser.

## Deploy with Cloudflare Workers

Uses the same static assets approach as the math_game project.

```bash
npm install
npx wrangler login
npx wrangler deploy
```

Configure Cloudflare Workers Builds to connect to GitHub `main` with deploy command `npx wrangler deploy` to deploy on subsequent commits.

Note: This is an original study game referencing the curriculum's concepts; it is not an official publisher product. Some exercises are original practice questions rather than verbatim exam items.
