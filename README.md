# 文史探險隊 V8 — 國文與社會 RPG 知識解謎

康軒七年級上學期國文與社會的原創互動學習遊戲。包含章節學習地圖、精讀導覽、知識解謎、Boss 戰、練習、模擬考及瀏覽器本機學習進度。

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
