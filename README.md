# テーブルスタジオ（仮）の招待ページ

TRPGのセッションツール「テーブルスタジオ」（仮）の、招待リンクの案内ページです。

- `join/index.html` … GMが送った招待リンク（`https://reverinudog.github.io/table-studio/join/#招待`）を開くと、PL用アプリを起動して参加画面に招待を入れます。アプリが無い時は入手先を案内します。
- `#` の後ろの招待はサーバーへ送られず、このページもどこにもデータを送りません。

## アプリ用のリンクの名前を変える時

`join/index.html` の `SCHEME` を、PL用アプリの設定（アプリのリポジトリの `app/src-tauri/tauri.pl.conf.json` の `plugins.deep-link.desktop.schemes`）と同じ名前にします。
