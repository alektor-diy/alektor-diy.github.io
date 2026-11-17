# A'sKey Hub

BOOTH・ビルドガイド・ながれキー・X・ブログ・YouTube・GitHubへのリンクをまとめた静的ページです。

## 更新

- index.html：自己紹介、リンク、SEO・OGP
- assets/site.css：表示とレスポンシブ設定
- assets/brand-logo.png、assets/creator.png：提供された公式画像（保持）
- assets/brand-logo.webp、assets/creator.webp：表示サイズに合わせた軽量版
- assets/ogp.png：SNS共有画像

HTML・CSSをUTF-8で直接編集します。外部フォント、JavaScript、依存パッケージ、ビルドは不要です。
元サイトの6つのURLはすべて維持しています。

## GitHub Pages

リポジトリ直下のindex.htmlとassetsをそのまま配信する構成です。
GitHubのSettings → Pagesで、既存の公開ブランチと「/ (root)」を指定する設定に対応します。
.nojekyllを置いています。追加のワークフローは不要です。
GitHub側の公開設定は変更していません。push・本番公開は行っていません。

公開URLを変える場合はindex.html内のcanonical・OGP・Twitter画像URL、robots.txt、sitemap.xmlも更新してください。

## 確認範囲

既存リンク保持、ローカルファイル参照、ページ内リンク、外部リンク属性、HTMLタグ対応を検証しています。
実ブラウザでの表示は環境の接続制限により未確認です。
