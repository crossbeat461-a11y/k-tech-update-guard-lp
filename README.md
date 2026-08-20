# K-Tech Update Guard — Landing Page

**K-Tech Update Guard**（v0.1.2）の公式ランディングページです。

- コミュニティの更新を、自分のタイミングで確認
- チェックした項目だけインストールする
- GitHub へ直接確認（作者サーバーには送らない）
- 日本語 / English 切り替え、Buy Me a Coffee

このフォルダは静的サイトです（`index.html` 1枚 + 補助ファイル）。フレームワークは使いません。

## ローカルで見る

```bash
cd c:\Github\K-tech-update-guard_LP
python -m http.server 8080
```

ブラウザで http://localhost:8080 を開きます。

## 公開（確認後）

push と Vercel 公開は、内容を確認してから行います。

想定 URL:

| 先 | URL |
|----|-----|
| GitHub | `https://github.com/crossbeat461-a11y/k-tech-update-guard-lp`（未作成なら新規） |
| Vercel | `https://k-tech-update-guard-lp.vercel.app/` |

Vercel: Import Git → Framework Preset **Other**（static）→ Deploy。

## バージョンを上げるとき

`index.html` の `v0.1.2` を置換:

- `<title>` と meta / JSON-LD
- ヒーローの `#version-badge`
- フッター
- `#changelog` の先頭に `.release` を追加（`latest` クラスを新しい方へ）

`og.svg` と `sitemap.xml` の日付も必要なら更新します。

## リンク

- プラグイン本体: https://github.com/crossbeat461-a11y/k-tech-update-guard
- Releases: https://github.com/crossbeat461-a11y/k-tech-update-guard/releases/latest
- K-Tech Studio: https://k-tech-lab.vercel.app/
- Buy Me a Coffee: https://buymeacoffee.com/k_tech_studio
