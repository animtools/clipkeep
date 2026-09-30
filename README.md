# ClipKeep

> 動画の中から「使いたい瞬間」を見つけて、残す。

大量の動画をサムネイルで眺めながら探せる、Windows 用の動画ライブラリです。中身を開かずにタイルで探し、気になった瞬間を Keep として残して、あとからタグや評価で引き出せます。

画面と使いどころは [紹介ページ](https://animtools.github.io/clipkeep/landing/) にあります。

---

## ダウンロード

[Releases](https://github.com/animtools/clipkeep/releases) から最新のポータブル ZIP（`ClipKeep-<版>-windows_portable.zip`）を取得してください。

- 動作環境: Windows 10 / 11（64bit）と Microsoft Edge WebView2 ランタイム（Windows 11 は標準搭載）
- インストールは不要です。**空のフォルダに解凍して `clipkeep.exe` を起動します。** データは exe と同じフォルダに作られます
- 未署名のため、初回起動で SmartScreen の警告が出ることがあります（[QUICKSTART.md](./QUICKSTART.md#1-ダウンロードと起動)）

## ドキュメント

- [QUICKSTART.md](./QUICKSTART.md) — 解凍から最初の Keep まで
- [USER_GUIDE.md](./USER_GUIDE.md) — 使い方の詳細
- [SUPPORT.md](./SUPPORT.md) — 不具合報告・質問
- [CHANGELOG.md](./CHANGELOG.md) — 変更履歴

## プランとライセンス

**無料で、動画を何本でも登録できます。** 期限はありません。Keep タイルは 100 枚まで、プロファイルは 1 つまでです。上限を超えてもデータは消えず、有料プランにすればそのまま全件に戻れます。

有料プランで開くのは、Keep タイルの無制限・複数のプロファイル・書き出し・スキャン実験室（顔・ポーズ・シーン検出・文字起こし）です。

**いま購入できるのは All-Access（サブスク）だけです。買い切りも将来的に用意する予定ですが、こちらは完成品を永続的に所有する形なので、テスト段階で公開しているいまは出していません。**

詳しくは [USER_GUIDE.md のプランとライセンス](./USER_GUIDE.md#9-プランとライセンス)、料金は [紹介ページ](https://animtools.github.io/clipkeep/landing/#pricing) と [ハブの料金ページ](https://shinosuke-site.vercel.app/pricing.html) を参照してください。購読の管理は [カスタマーポータル](https://polar.sh/shinosuke/portal) から行えます。利用条件は [LICENSE](./LICENSE) を参照してください。

## このリポジトリについて

本リポジトリ（[`animtools/clipkeep`](https://github.com/animtools/clipkeep)）は利用者向けの配布面です。置いてあるのは配布物・公開ドキュメント・紹介ページで、ソースコードは含みません。開発リポジトリは非公開です。
