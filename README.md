# TexEdiot 公開サイト

TexEdiot（Windows 用の日本語向け TeX エディタ）の紹介・配布ページです。静的 HTML/CSS のみで、ビルド手順はありません。

## ローカルで開く

`index.html` をブラウザで開くだけで確認できます。パスはすべて相対パスです。

```
python3 -m http.server 8000   # 任意。http://localhost:8000/ で確認
```

## 公開

GitHub Pages で `main` ブランチのルートを配信します（Settings → Pages → Deploy from a branch → main / root）。
公開 URL: https://kamokamoriver.github.io/texediot-site/

インストーラーは現在準備中です。公開後は Releases に掲載する予定です。
