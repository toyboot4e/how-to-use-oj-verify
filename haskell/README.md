# Haskell

## 環境構築

Nix ユーザの場合は、たぶん `direnv allow` で環境構築できます。

Nix ユーザ以外は、 `oj-verify` ([verification-helper](https://github.com/online-judge-tools/verification-helper)) と[just](https://github.com/casey/just) をインストール後に `just` を実行してください。

Windows だと恐らく動きません。

## 主なファイル

- [./.verify-helper/config.toml](./.verify-helper/config.toml): `compile`, `execute` を指定しています
- [./compile](./compile): コンパイル用スクリプトです
- [./execute](./execute): 実行用スクリプトです

