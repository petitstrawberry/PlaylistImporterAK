# PlaylistImporterAK
AK DAP(第4世代)向けのアプリです。
m3u/m3u8形式の外部プレイリストをDAP内部のプレイリストデータベースに登録します。

(公式に再対応されそうなのでもはや必要なくなりそうです。そのようなわけで、ここに放流することで供養とします。)

その他詳細な挙動はアプリ内に書いてます。

# 注意
- Macとの接続前提として作ったのでWindowsのパス形式ではうまく動作しないかもしれません。
- SE100でしかテストしてません。

# インストール
[リリース](https://github.com/PetitStrawberry/PlaylistImporterAK/releases)からダウンロードして、
APKEditorなどで署名を書き換えるなりしてOpenAppService画面からインストール

# 使い方
## 初回のみ
- 内部ストレージまたはSDカードなどの外部ストレージのルートディレクトリにToPlaylistsフォルダを作成
- 設定画面からストレージへのアクセスを許可

## 初回以降
1. USB接続(MTP)
2. ToPlaylistsフォルダにm3u/m3u8ファイルを転送
3. USB接続解除
4. おしまい

