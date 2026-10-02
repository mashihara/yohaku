# Yohaku for Git

Mac 用の Git クライアントです。内部で `git` コマンドをそのまま実行するので、ターミナルや AI エージェント（Claude Code など）で行った操作と表示が食い違いません。

A Git client for macOS. It runs the real `git` command under the hood, so it always agrees with what you do in the terminal.

## ダウンロード / Download

**[最新版をダウンロード（Yohaku.dmg）](https://github.com/mashihara/yohaku/releases/latest/download/Yohaku.dmg)**

DMG を開き、Yohaku を「アプリケーション」フォルダへドラッグしてください。Apple の公証（notarization）済みです。

- 動作環境: macOS 14 以降（Apple シリコン / Intel）
- `git` が必要です。入っていない場合は、初回に macOS が「コマンドライン・デベロッパ・ツール」のインストールを案内します

## できること

- **ホーム**: 登録したすべてのリポジトリの状況（未コミット・未 Push・取込待ち・衝突）を一覧
- **履歴**: グラフ付きのコミット一覧、ブランチの絞り込み、メッセージ・作者・コード内容での検索、2つのコミットの比較
- **変更**: ファイル・ハンク・行単位のステージ、Amend、コミット＆Push
- **ブランチ操作**: マージ、リベース、インタラクティブリベース、チェリーピック、リバート、リセット
- **リモート**: Fetch / Pull / Push（`--force-with-lease`、自動スタッシュ）
- **ワークツリー**: 一覧・作成・削除・作業のないものの片付け
- **その他**: スタッシュ、タグ、ファイル履歴、Blame、衝突の解決、クイック起動（⌘P）

主なショートカットは Fork と同じです（⌘1 変更、⌘2 全コミット、⇧⌘F/L/P Fetch/Pull/Push など）。

## 不具合の報告

[Issues](https://github.com/mashihara/yohaku/issues) へお寄せください。

© 2026 mashiharalab
