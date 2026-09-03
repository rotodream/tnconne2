プロフィール コネクト Cloudflare 完成更新版 2026-09-03
=====================================================

基準
----
・画面 / レイアウト / 管理者ページ: v11完成版
・Chromeで確定した実データ: profile-connect-COMPLETE-HANDOFF-2026-09-02.zip

保存
----
固定情報: HTMLのまま
あなたのプロフィール: D1
事業・活動の追加/編集/表示非表示/順番: D1
事業案内画像: R2
閲覧者から届くプロフィール: D1
閲覧者写真: R2
管理者パスワード: D1

Bindings
--------
ASSETS -> public/
DB -> my-app-db
BUCKET -> my-app-images

wrangler.jsonc に DB / BUCKET の定義を含めています。
Wrangler 4.45+ のリソース自動プロビジョニング対応形式で、
既存の同名リソースを使う前提です。

重要
----
管理者ページのHTML/CSSレイアウトはv11から変更していません。
変更したのは保存処理のJavaScriptだけです。
file:// で開いたChromeテスト時は従来どおりlocalStorageで動作し、
Cloudflare上ではD1/R2へ保存します。

引継ぎ確認
----------
owner name: すっきり 野菜 果物という事業者名
received profiles in handoff: 3
business items in handoff: 7
