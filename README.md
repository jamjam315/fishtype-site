# fishtype-site

Fishtype（釣った魚の写真に魚種名のタイポグラフィを乗せるアプリ）の公開ページ。
GitHub Pages で <https://fishtype.app/> に公開している。

| | |
|---|---|
| トップ | `index.html` |
| 利用規約 | `terms/`（英語）・`ja/terms/`（日本語）※ W3 機能5で追加 |
| プライバシーポリシー | `privacy/`（英語）・`ja/privacy/`（日本語）※ W3 機能5で追加 |
| app-ads.txt | `app-ads.txt` ※ AdMob の値が決まったら追加 |

- 原稿の正本はアプリのリポジトリ（`jamjam315/fishtype` の `docs/legal/`）。ここは公開用の写し
- アプリの Pro の画面・設定は `https://fishtype.app/terms/` などに固定でリンクしている。**URL を変えない**（変えるときは転送のページを残す）
- ビルドの工程は無い。HTML を直して `main` に push すれば反映される
- DNS は Cloudflare（手順は `jamjam315/fishtype` の `docs/store-setup.md` の 7）
