# generate:doc:gitbook
コマンドのためのドキュメントを生成する

**使い方:**
```
$ drupal generate:doc:gitbook [arguments] [options]
$ gdg  
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--path | ドキュメントを生成するパス
--help | このヘルプメッセージを表示する
--quiet | コマンドからの全ての出力を抑制する
--verbose | メッセージの冗長性を上げる: 1は通常の出力、2はより冗長な出力、3はデバッグ用
--version | アプリケーションのバージョンを表示する
--ansi | ANSI出力を強制する
--no-ansi | ANSI出力を無効化する
--no-interaction | 対話的な質問を行わない
--env | 環境の名前
--root | コマンドを実行するDrupalのルートディレクトリを定義する
--no-debug | デバッグモードを無効にする
--learning | 冗長なコードの出力を行う
--generate-chain | コマンドのオプションと引数をチェーンコマンドとして表示する
--generate-inline | コマンドのオプションと引数をインラインコマンドとして表示する
--generate-doc | コマンドのオプションと引数をMarkdownとして表示する
--target | サイト名 (ローカルもしくはリモートサイト向け)
--uri | DrupalサイトのURI (マルチサイトやデフォルト以外のポートを利用している場合に使用する)
--yes | 確認プロセスをスキップする

## 利用可能な引数
引数 | 詳細
---------|-------------
command | 実行するコマンド