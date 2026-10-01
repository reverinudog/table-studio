# テーブルトークテーブルの招待ページ

TRPGのセッションツール「テーブルトークテーブル」の、招待リンクの案内ページです。

- `join/index.html` … GMが送った招待リンク（`https://reverinudog.github.io/table-studio/join/#招待`）を開くと、アプリを起動して、ホームの「参加」に招待を入れます。アプリが無い時は入手先を案内します。
- `#` の後ろの招待はサーバーへ送られず、このページもどこにもデータを送りません。

## アプリ用のリンクの名前を変える時

`join/index.html` の `SCHEME` を、アプリの設定（アプリのリポジトリの `app/src-tauri/tauri.conf.json` の `plugins.deep-link.desktop.schemes`）と同じ名前にします。
