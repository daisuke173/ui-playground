# UI Playground

同じコンテンツを、CSSとJavaScriptを使わず、HTMLの情報構造だけを変えて比較するための実験用リポジトリです。

## Current themes

- `themes/newsroom.html` — 見出しと記事を縦に読むニュース型
- `themes/directory.html` — `table` を使った高密度一覧型
- `themes/accordion.html` — `details` / `summary` を使ったJavaScript不要の開閉型
- `themes/media.html` — セクションごとに代表画像を置くメディア型

`index.html` をテーマ選択ページにしています。各テーマにも相互リンクがあり、通常のHTMLリンクだけで切り替えられます。

## Rules

- CSSを使用しない
- JavaScriptを使用しない
- 外部UIフレームワークを使用しない
- HTML標準要素の違いでUIを比較する
- 同じデータセットを各テーマに展開して比較条件を揃える

## Theme ideas for later

- `timeline.html` — 日付中心の時系列表示
- `catalog.html` — カテゴリを目次として使うカタログ型
- `dashboard.html` — `table`, `meter`, `progress` など標準要素を使う情報盤型
- `reader.html` — 画像を抑え、見出しと本文を重視する読書型
- `portal.html` — セクションを入口として整理するポータル型
- `minimal.html` — タイトルとリンクだけの最小構成

テーマを増やす場合は `themes/<theme-name>.html` を追加し、`index.html` と各テーマ上部のナビゲーションへリンクを追加します。
