# trickdeck-site

[TrickDeck](https://github.com/Kazooooo/TrickDeck) のランディング兼サポートページとプライバシーポリシーを配信する静的サイト。

GitHub Pages で配信する。TrickDeck 本体（private）には `web/` サブモジュールとして取り込んでいる。

## 構成

- `index.html` — ランディング / サポートページ（App Store のサポート URL に使用）
- `privacy.html` — プライバシーポリシー（App Store / Google Play の Privacy Policy URL に使用）
- `styles.css` — 共通スタイル（アプリのダークテーマに合わせた配色）
- `.nojekyll` — GitHub Pages の Jekyll 処理を無効化（素の静的ファイルとして配信）

## 公開 URL

- サイト: `https://kazooooo.github.io/trickdeck-site/`
- プライバシーポリシー: `https://kazooooo.github.io/trickdeck-site/privacy.html`

## デプロイ

`main` ブランチに push すると GitHub Pages が自動でデプロイする。

## ローカル確認

```bash
python3 -m http.server 8000
# http://localhost:8000 を開く
```
