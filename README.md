# hsp-server

`hsp3cl`を使用しています。



## httpserver-console.hsp

- メインのファイルです。
- `DIR` ...サーバーのデフォルトフォルダです。
- `PORT` ...サーバーのポート番号です。



## router.hsp

- サンプルの通りです。
- `default` ...`httpserver-console.hsp`で指定したフォルダからファイルを参照して返します。



## apiの追加方法

- apiフォルダに`ping`のサンプルがあるのでそれを参考にしてください。
- apiを追加したら`router.hsp`に追加してください。



## src内のファイル説明

### console.hsp

- コンソールに出力する文字の設定が書いてあります。

### httpserver.hsp

- サーバーの管理を行う関数が入っています。

### log.hsp

- ログの出力に関してです。

### timer.hsp

- 細かい時間を計測するために使用しています。

