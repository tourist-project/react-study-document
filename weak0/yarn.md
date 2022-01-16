# yarnのインストール
※ Node.jsをインストールしていない場合は行えないので必ずそちらを行なってからYarnのインストールをしてください。

## パッケージマネージャとは
React では様々な JavaScript のファイルや外部パッケージを使用します。これらは通常正しい読み込み手順でなければ使用できないなど、使用がとても難しくなってしまいます。

このように依存関係などを気にせずに、パッケージやそのバージョンを管理できるツールがパッケージマネージャです。

Node.js のインストール時に確認した npm や今回の yarn もそのパッケージマネージャの1種になります。

## yarnとは
簡単に言うと npm より高速にインストールが可能（環境によります）なパケージマネージャです。

## インストール
以下のコマンドでyarnをインストールしてください。
```bash
# グローバルにインストール
$ npm install -g yarn

# インストールされているか確認
$ yarn -v
```

## 主に使用するコマンド
```bash
# パッケージをdependenciesにインストール
$ yarn add [パッケージ名]

# パッケージをdevDependenciesにインストール
yarn add -d [パッケージ名]

# パッケージのアンインストール
$ yarn remove [パッケージ名]

# パッケージのアップデート
$ yarn upgrade [パッケージ名]
```