# 購入ドア（安定 URL）

公開リポジトリ [`animtools/clipkeep`](https://github.com/animtools/clipkeep) の
`landing/buy/` に置く。GitHub Pages 例:

- サブスク: `https://animtools.github.io/clipkeep/landing/buy/subscribe.html`
- 買い切り: `https://animtools.github.io/clipkeep/landing/buy/perpetual.html`

アプリの `.env`:

```env
BUNDLED_LANDING_PUBLIC_ORIGIN=https://animtools.github.io/clipkeep/landing
```

→ `{ORIGIN}/buy/subscribe.html` / `perpetual.html`

Early Bird 終了時は `subscribe.html` 内の Polar checkout URL だけ差し替えて push。
