# ClipKeep

> 動画の"あの瞬間"を、二度と見失わない。

ClipKeep は、動画からサムネイルタイルを生成して一覧し、気になった瞬間を Keep してコレクションできる Windows 向けの動画ライブラリアプリです。動画素材や録画をたくさん溜めている人が、中身を開かずに眺めて探し、使いたい数秒を残しておくための道具です。

本リポジトリ（[`animtools/clipkeep`](https://github.com/animtools/clipkeep)）は利用者向けの配布面です。ソースコードは含みません。

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

**無料で、動画 30 本・Keep タイル 100 枚・プロファイル 1 つまで使えます。** 期限はありません。上限を超えてもデータは消えず、有料プランにすればそのまま全件に戻れます。

- 有料プラン: 書き出し
- All-Access（サブスク）: 書き出しに加えて、スキャン実験室の顔・ポーズ・シーン検出・文字起こしと、検出した結果を書き換える操作（カットフレームの手動編集、シーンの切れ目からのタイル作り直し）

**いま購入できるのは All-Access（サブスク）だけです。買い切りも将来的に用意する予定ですが、こちらは完成品を永続的に所有する形なので、テスト段階で公開しているいまは出していません。**

詳しくは [USER_GUIDE.md のプランとライセンス](./USER_GUIDE.md#9-プランとライセンス)、料金は [ハブの料金ページ](https://shinosuke-site.vercel.app/pricing.html) を参照してください。購読の管理は [カスタマーポータル](https://polar.sh/shinosuke/portal) から行えます。利用条件は [LICENSE](./LICENSE) を参照してください。

## 紹介ページ

- [紹介ページ](https://animtools.github.io/clipkeep/landing/)
