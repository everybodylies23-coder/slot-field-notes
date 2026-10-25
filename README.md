# 実戦ノート

カバネリ・ジャグラーのブラウザ内保存型記録帳。GitHub Pagesのmain / (root)から配信。

## 機種の追加

1. 新しい機種のHTMLを追加する（保存キーとJSON schemaは別にする）。
2. machines.js の配列にname/subtitle/tag/description/path/numberを追加する。
3. HTMLにメインメニューへ戻るリンクを付けて確認・pushする。

## 保存

実戦データはlocalStorage。通信によるデータ送信・サーバー保存・端末間同期はありません。各ノートのJSON書出しでバックアップしてください。同じgithub.ioオリジンのページとは保存領域を共有するため、アプリ固有キーを使っています。

公開リポジトリに実戦JSON・記録入りHTML・会話・個人データを追加しないでください。初期公開HTMLのembedded-dataはnullです。
