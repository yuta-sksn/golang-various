# 雑多な GO

## GO インストール (anyenv -> goenv 経由)

### anyenv インストール

[公式](https://github.com/anyenv/anyenv)を参照。

### goenv インストール

```
$ anyenv install goenv
```

### 特定のバージョンの GO インストール

`.go-version` に記載されているバージョンのものをインストールしてください。

```
$ goenv install 1.18.0 
```

### ローカル (特定のディレクトリ配下) で使用できるように

今回はこのプロジェクトのドキュメントルート配下で使用できるようにするので、以下を実行。

```
$ goenv local 1.18.0
```

### バージョン確認

```
$ go version
```

## VSCode 環境での準備

推奨された拡張機能をインストール。し忘れたら、`./.vscode/extensions.json` の中身を見てインストール。  
Cmd + Shift + P を押して、`GO: Install/Update tools` を入力 & エンター。