# fishtype-site

Fishtype（釣った魚の写真に魚種名のタイポグラフィを乗せるアプリ）の公開ページ。
GitHub Pages で <https://fishtype.app/> に公開している。

| | |
|---|---|
| トップ | `index.html` |
| 利用規約 | `terms/`（英語）・`ja/terms/`（日本語） |
| プライバシーポリシー | `privacy/`（英語）・`ja/privacy/`（日本語） |
| app-ads.txt | `app-ads.txt` ※ AdMob の値が決まったら追加 |

- 原稿の正本はアプリのリポジトリ（`jamjam315/fishtype` の `docs/legal/*.md`）。ここは公開用の写しで、`python3 -I tool/build_legal.py ../fishtype-site`（fishtype のリポジトリで実行）で作る。**ここの HTML を直接直さない**
- アプリの Pro の画面・設定は `https://fishtype.app/terms/` などに固定でリンクしている。**URL を変えない**（変えるときは転送のページを残す）
- ビルドの工程は無い。HTML を直して `main` に push すれば反映される
- DNS は Cloudflare（手順は `jamjam315/fishtype` の `docs/store-setup.md` の 7）
