# nono

一行字和一張大 GIF — [nono.itousouta15.tw](https://nono.itousouta.me)

## 改內容

- 文字：改 `public/index.html` 裡的 `<h1>`
- GIF：把新檔案覆蓋 `public/nono.gif`

## 部署

```sh
npx wrangler deploy
```

或 push 到 GitHub main（需要在 repo secrets 設定 `CLOUDFLARE_API_TOKEN` 和 `CLOUDFLARE_ACCOUNT_ID`）。
