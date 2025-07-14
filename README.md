# 新琴似ヨガクラス LP

静的なランディングページ一式です。`index.html` をブラウザで開くだけで閲覧できます。

## 構成

```
shinkotoni/
├─ index.html          … LP 本体
├─ images/             … 画像をここに配置（hero-placeholder.jpg など）
└─ README.md           … このファイル
```

## 画像の追加

1. `shinkotoni/images` フォルダに HERO 画像などを配置してください。
2. ファイル名は `index.html` で参照している名前と一致させます。

## 表示確認

mac なら Finder から `index.html` をダブルクリックするだけで OK です。

ターミナルから簡易サーバを立てて確認する場合:

```bash
python3 -m http.server 8000
```

その後ブラウザで <http://localhost:8000> を開きます。

## 次のステップ案

- Google Map / Google Calendar 埋め込み
- 画像ギャラリー (Lightbox, Swiper 等)
- Netlify／GitHub Pages などへのデプロイ
- お問い合わせフォームのバックエンド連携
