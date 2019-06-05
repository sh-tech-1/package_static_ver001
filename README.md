# package_static_ver001
sassを使った静的サイト

# 使用方法

## 使用するディレクトリにnodeが入っていることを確認

`node -v`

## node_moduleのインストール

`npm i -D webpack webpack-cli sass-loader node-sass style-loader css-loader`

## package.jsonのあるディレクトリ階層で実行。コンパイルさせる。

`npx webpack -watch`
