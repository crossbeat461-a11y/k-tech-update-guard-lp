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

## Live URLs

| Service | URL |
|---------|-----|
| **GitHub** | https://github.com/crossbeat461-a11y/k-tech-update-guard-lp |
| **Vercel** | https://k-tech-update-guard-lp.vercel.app/ |

## Analytics / Search Console

| 項目 | 状態 |
|------|------|
| Search Console 確認ファイル | `google8a8913465dda62dd.html`（他 LP と同一トークン） |
| sitemap | https://k-tech-update-guard-lp.vercel.app/sitemap.xml |
| GA4 測定 ID | `G-1CYZZXRZ3P`（専用） |

確認ファイルの本番 URL:

https://k-tech-update-guard-lp.vercel.app/google8a8913465dda62dd.html

OG 画像: `og.png`（1200×630）

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
