# 食欲の秋の、わたしメンテ。 引き継ぎ一式

更新版：スタンダード・梅・ザクロ・ミカン・和漢の5種類を掲載。

## 使い方
- page/index.html をブラウザで開くと完成版を表示できます。
- HTML・CSS・画像はすべて同梱。ビルドやnpmインストールは不要です。
- ローカルサーバーなら、このフォルダで `python3 -m http.server 8000 --directory page` を実行し、http://localhost:8000 を開きます。
- Claude Codeでこのフォルダを開き、CLAUDE.mdの指示に従わせてください。

## Claude Codeに貼る指示

「CLAUDE.mdを読んでください。page/ に完成済みのHTML・CSS・画像があります。これを原本として、全く同じデザインでページを設置してください。元ファイルをそのまま使い、再デザインしないでください。色・余白・フォント指定・文字サイズ・改行・写真・商品画像・構成・レスポンシブ挙動を維持してください。PCとスマホで原本と比較し、商品リンクとFAQも確認してください。楽天への反映・公開はまだ行わないでください。」

## ファイル
- page/index.html：本文・商品リンク・FAQ
- page/style.css：原本のすべてのスタイル
- page/assets/autumn.png：秋のFV写真（AI生成の飲用イメージ）
- page/assets/1000.jpg / 0002.jpg / 0090.jpg：店舗の商品画像
- page/assets/favicon.svg：アイコン
- SHA256.json：原本ファイルの照合用ハッシュ

商品画像は店舗から取得した画像をそのまま使用しています。trial.jpgは初期検討素材で現行ページでは未使用です。価格、期間、クーポンは本特集に追加していません。

## 確認ページ
https://danjiki-autumn-maintenance.sakko-555.chatgpt.site

このURLは所有者限定のため、Claude Codeから閲覧できない場合があります。その場合も同梱のpage/ が原本です。共有権限や既存サイトの認証・運用設定はこのZIPに含めていません。
