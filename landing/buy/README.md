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

値上げ・商品変更のときは `subscribe.html` 内の Polar checkout URL だけ差し替えて push。

⚠ **「Early Bird」は商品名ではなくラベル**（2026-08-28・ハブ `playbooks/pricing.md`）。
値上げのために別商品を作らない — 据え置きは Polar の既定動作で保たれるので、現行商品の
価格改定で行う。別商品を作ると、このドアが古い商品を売り続ける
（2026-08-28 に実際に起きた：ドアが Archive 済みの Early Bird へ転送していた）。
